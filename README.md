# COVID-Data-Analysis-and-Wrangling

## Project Purpose 
The COVID-19 pandemic resulted in horrific mortality rates in the United States. However, not all states, regions, and racial groups suffered equally. The questions I wish to explore look at whether COVID cases per death differences exist either geographically or racially. If such differences do exist, state practices can be explored to mount a more effective public health response in the future.

## Questions for Analysis
1) Do COVID death rates when compared to number of COVID cases differ to a large degree between various U.S. states? My criteria will be if a state's death rate is 2 times that of the state with the lowest death rate.
2) Do COVID death rates when compared to number of COVID cases differ to a large degree between Caucasian and African/Black Americans? My criteria will be if a racial group's death rate is 2 times that of the racial group with the lowest death rate.

### Dataset Description
The state data can be found at [The COVID tracking project](https://covidtracking.com/data/download). Once at the webpage, click on the button "data for all states" and download link as a csv file. The race data can be found at [The COVID tracking project race dashboard](https://covidtracking.com/race/dashboard) click on the button "csv" and download link as a csv file.  The dataset consists of over 110K + records, 2 ID columns, 10 predictor variables, and the no-show column of 

   ### The following variables were found in the dataset:
      - PatientId: Identification of a patient
      - AppointmentID: Identification of each appointment
      - Gender: Male or Female
      - DataMarcacaoConsulta: The day of the actual appointment.
      - DataAgendamento: The day someone called or registered the appointment.
      - Age: Age of patient
      - Neighbourhood: Where the appointment takes place.
      - Scholarship: Yes or no
      - Hipertension: Yes or no
      - Diabetes: Yes or no
      - Alcoholism: Yes or no
      - Handicap: Yes or no
      - SMS_received: 1 or more messages sent to the patient.
      - No-show: Yes or no


