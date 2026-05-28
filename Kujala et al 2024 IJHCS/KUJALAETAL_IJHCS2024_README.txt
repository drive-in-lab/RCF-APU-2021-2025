This readme file was generated on 2026-05-28 by Tuomo Kujala


GENERAL INFORMATION

Principal Investigator Information
Name: Tuomo Kujala
ORCID: 0000-0001-8222-8540
Institution: University of Jyväskylä
Address: Seminaarinkatu 15, PO Box 35, 40014 University of Jyväskylä
Email: tuomo.kujala@jyu.fi


- Date of data collection: 2016
- Geographic location of data collection: Finland
- Information about funding sources that supported the collection of the data: This research was supported by Research Council of Finland [Appropriate Uncertainty in Manual and Automated Driving, grant 343259].


SHARING/ACCESS INFORMATION

- Licenses/restrictions placed on the data: CC BY-NC
- Links to publications that cite or use the data: https://doi.org/10.1016/j.ijhcs.2024.103247
- Recommended citation for this dataset:
Kujala, T., Grahn, H., Mäkelä, J., Silvennoinen, J., & Tokkonen, T. (2024). Effects of context-sensitive distraction warnings on drivers’ smartphone use and acceptance: A long-term naturalistic field study. International Journal of Human-Computer Studies, 186, 103247.

DATA & FILE OVERVIEW

File List: 
demographics.csv
touches.csv


METHODOLOGICAL INFORMATION

Description of methods used for collection/generation of data:
Kujala, T., Grahn, H., Mäkelä, J., Silvennoinen, J., & Tokkonen, T. (2024). Effects of context-sensitive distraction warnings on drivers’ smartphone use and acceptance: A long-term naturalistic field study. International Journal of Human-Computer Studies, 186, 103247.

Methods for processing the data:
Kujala, T., Grahn, H., Mäkelä, J., Silvennoinen, J., & Tokkonen, T. (2024). Effects of context-sensitive distraction warnings on drivers’ smartphone use and acceptance: A long-term naturalistic field study. International Journal of Human-Computer Studies, 186, 103247.


DATA-SPECIFIC INFORMATION FOR: demographics.csv
<repeat this section for each dataset, folder or file, as appropriate>

- Number of variables: 14

- Number of cases/rows: 26

- Variable List:

id: participant's id

age: participant's age, years

gender: participant's gender, values: M=male / F=female

dr_exp_yrs: participant's driving experience, years

dr_exp_km: participant's driving experience, km (self-estimated)

km_during_study: participant's mileage during the study, km (self-estimated)

gearbox: type of gearbox, values: M=manual / A=automatic

pct_driving_wifi_on: percentage of driving time the participant had phone's wifi on, % (self-estimated)

email_read: did the participant read the email with instructions on how the reminders and warnings work (self-reported), values: 0=did not read at all / 1=read / 2=read carefully

harmfulness: experienced harmfulness of the application (sum variable, 1-5)

usefulness: experienced usefulness of the application (sum variable, 1-5)

usefulness_voice_warnings: experienced usefulness of the voice warnings (sum variable, 1-5)

timing_reminders: experienced accuracy of the reminder timings (sum variable, 1-5)

usefulness_reminders: experienced usefulness of the reminders (sum variable, 1-5)


- Missing data codes: space



DATA-SPECIFIC INFORMATION FOR: touches.csv

- Number of variables: 16

- Number of cases/rows: 627569

- Variable List:

Device_id: dashboard smartphone's id

Timestamp: timestamp

TimestampLastGpsFix: timestamp of the last GPS signal fix

Latitude: latitude

Longitude: longitude

Altitude: altitude

Speed: speed, m/s

Bearing: bearing

RoadNum: road number in Open Street Map data

Watcher_id: id of the participant's own smartphone

Control: control or experiment phase, values: 0=Experiment / 1=Control

Drivernum: participant's id (participants with Drivernums 11-17, 20-25, 27-34, 36 and 39-42 included in the data analysis in the article: sufficient samples per driver)

Road_type: road type, values: 1=Highway / 2=Main rural road / 3=Local rural road / 4=Urban

Red_touch: did the participant touch smartphone within a reminder area, values: 0=no / 1=yes

Reminder_on: is a reminder displayed, values: 0=no / yes=1

Driving_speed_over2ms: is the driving speed more than 2 meters per second, values: 0=no / yes=1



- Missing data codes: space, NA

