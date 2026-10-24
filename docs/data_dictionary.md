# Data Dictionary

## Dataset Source
Public insurance cost dataset adapted for exploratory healthcare cost prediction.
While the original dataset structure reflects a non–South African context, variables are interpreted within a South African healthcare and wellness framework.


## Unit of Observation
One insured individual

## Target Variable
charges  
Total annual medical insurance cost (monetary units as per original dataset).
While values are expressed in USD in the source data, results are interpreted conceptually within a South African healthcare cost context.


## Prediction Task
Regression

---

## Feature Descriptions

### Demographic Variables
- age: age of the individual (years)
- sex: biological sex (male / female)
- region: geographic region (used as a proxy for regional healthcare access and cost variation in a South African context)


### Health & Lifestyle Variables
- bmi: body mass index (kg/m²)
- smoker: smoking status (yes / no)

### Family / Coverage Context
- children: number of dependents covered by insurance

---

## Missing Values
- No missing values identified (to be confirmed during exploratory data analysis)

## Known Limitations
- No direct measure of disability or functional impairment
- No clinical diagnosis data
- No direct healthcare utilisation counts (e.g. visits, admissions)
- Regional variable does not explicitly map to South African provinces and is used as a geographic proxy only


---

## OT / Wellness Perspective (Planned)
- BMI as a proxy for functional strain and mobility risk
- Smoking as a proxy for long-term occupational and functional health risk
- Age as a proxy for increasing support needs and functional decline
- Opportunity to engineer composite wellness or risk indices
- Regional differences interpreted in terms of access to care, urban vs rural context, and socioeconomic disparities common in South Africa

