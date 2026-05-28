This readme file was generated on 2026-05-28 by Tuomo Kujala


GENERAL INFORMATION

Principal Investigator Information
Name: Tuomo Kujala
ORCID: 0000-0001-8222-8540
Institution: University of Jyväskylä
Address: Seminaarinkatu 15, PO Box 35, 40014 University of Jyväskylä
Email: tuomo.kujala@jyu.fi


- Date of data collection: June-2024
- Geographic location of data collection: Jyväskylä, Finland
- Information about funding sources that supported the collection of the data: This research was supported by Research Council of Finland [Appropriate Uncertainty in Manual and Automated Driving, grant 343259]. 


SHARING/ACCESS INFORMATION

- Licenses/restrictions placed on the data: CC BY-NC
- Links to publications that cite or use the data: https://doi.org/10.1145/3706598.3713590
- Recommended citation for this dataset:
Kujala, T., & Sarkar, A. (2025, April). Evaluating In-Car Tasks’ Distraction Effects with Drive-In Lab. In Proceedings of the 2025 CHI Conference on Human Factors in Computing Systems (pp. 1-24).


DATA & FILE OVERVIEW

File List: 
KUJALASARKAR-CHI2025.csv


METHODOLOGICAL INFORMATION

Description of methods used for collection/generation of data:
Kujala, T., & Sarkar, A. (2025, April). Evaluating In-Car Tasks’ Distraction Effects with Drive-In Lab. In Proceedings of the 2025 CHI Conference on Human Factors in Computing Systems (pp. 1-24).

Methods for processing the data:
Kujala, T., & Sarkar, A. (2025, April). Evaluating In-Car Tasks’ Distraction Effects with Drive-In Lab. In Proceedings of the 2025 CHI Conference on Human Factors in Computing Systems (pp. 1-24).



DATA-SPECIFIC INFORMATION FOR: KUJALASARKAR-CHI2025.csv

- Number of variables: 24

- Number of cases/rows: 704

- Variable List:

id: participant's id

car: studied car (model), values: EV9=Kia EV9 / ID7=Volkswagen ID.7

task: studied in-car task or baseline drive, values: a_baseline=Baseline drive / ac_suunta=AC direction / ac_temp=AC temperature / ajotila=Drive mode / kirkkaus=Touchscreen brightness / lane=Lane-keeping assist / latausasema=Navi to charge / navi=Navi to address / puhelu=Call / radio=Radio / seat=Seat heating

order: task order (randomized between participants), values: 1-10 (missing for a_baseline)

attentive_percentage: percentage of driving time the participant was attentive, %

inattentive_percentage: percentage of driving time the participant was inattentive, %

eyeglasses: did the participant wear eye glasses, values: 1=glasses / 2=no glasses

age: participant's age, years

gender: participant's gender, values: 1=female / 2=male / 3=other

dr_lic_years: how many years the participant had possessed a driver's license, years

annual_km: how many kilometers the participant drove per year (self-assessment), km

lifetime_km: how many kilometers the participant had driven during their lifetime (self-assessment), km

VST1: visual search task score (arrows task), first trial, correct upward arrow selections per 1 min

VST2: visual search task score (arrows task), second trial, correct upward arrow selections per 1 min

VST3: visual search task score (arrows task), third trial, correct upward arrow selections per 1 min

VST_avg: mean visual search task score across trials 1 to 3 (arrows task), correct upward arrow selections per 1 min

tasks: how many in-car tasks the participant was able to finish during the 3-min drive

zero_tasks: was the participant able to conduct any tasks during the 3-min drive, values: 0=more than zero tasks / 1=zero tasks

inattentiveness_ratio: ratio of participant's inattentiveness_percentage with the studied in-car task to participant's inattentiveness_percentage in Baseline drive (a_baseline)

Zorder: Z-score of order

Ztasks: Z-score of tasks

Zdr_lic_years: Z-score of dr_lic_years

Zage: Z-score of age

Zinattentiveness_ratio: Z-score of inattentiveness_ratio


- Missing data codes: space
