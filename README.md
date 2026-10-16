# Datasets for "Applied Data Science with Python / R / No-Code, Volume I"

Authors: Aymen Salah Bennihi and Brahim Zirari (Python, No-Code); Aymen Salah Bennihi and Abderrahmane Tahi (R).

These four CSV files are the datasets used throughout the book (Table 5.1 in the Python and R editions).
Put them in one folder next to your scripts and read them by file name.

| File | Domain | Rows | Columns | Role in the book |
|---|---|---|---|---|
| NHANES_Dataset.csv | Health survey | 10,000 | 25 | Running example from Chapter 5 onward |
| Quakes_Dataset.csv | Seismology | 1,000 | 7 | Natural science exercises |
| GSS_2024_Dataset.csv | Social science survey | 3,309 | 13 | Social science exercises |
| IPUMS_CPS_2025_Dataset.csv | Labor economics | 142,125 | 10 | Economics exercises |

## Variables

- **NHANES**: ID, Gender, Age, Race1, Education, MaritalStatus, HHIncome, HHIncomeMid, Poverty, HomeRooms, HomeOwn, Work, Weight, Height, BMI, Pulse, BPSysAve, BPDiaAve, TotChol, Diabetes, SleepHrsNight, SleepTrouble, PhysActive, SmokeNow, Depressed
- **Quakes**: lat, long, depth, mag, stations, mag_class, depth_class
- **GSS 2024**: id, year, age, sex, race, marital, educ, coninc, partyid, polviews, happy, health, tvhours
- **IPUMS CPS 2025**: year, age, gender, race, empstat, educ, classwly, wkswork1, uhrsworkly, incwage

## Original sources

- NHANES is modeled on the U.S. National Health and Nutrition Examination Survey (CDC): https://wwwn.cdc.gov/nchs/nhanes
- Quakes follows the Fiji earthquake catalog distributed with R as the built-in `quakes` dataset.
- GSS: General Social Survey, NORC at the University of Chicago: https://gss.norc.org
- IPUMS CPS: Current Population Survey microdata harmonized by IPUMS: https://cps.ipums.org

These files are extracts prepared for teaching. They are not a replacement for the original sources.
Please cite the original providers when you use the data for research.
