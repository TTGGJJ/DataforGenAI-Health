# Public survey dataset: Generative AI and health

This folder contains the analysis-ready public version of the survey data for the article: Evaluations of Generative AI Are Associated with Health Behavior and Health Anxiety: The Candidate Roles of Instrumental and Relational Dependence


## Files

- `Data_public.csv`: participant-level survey data.
- `README.md`: dataset notes and response-scale reference.

## Dataset summary

- Participants: 494
- Variables: 13
- Unit of analysis: one participant per row
- Data type: survey responses coded as integers
- Missing values in the supplied participant records: none
- Encoding: UTF-8 with BOM

## Variables

| Prefix | Variable | Description |
| --- | --- | --- |
| Q3-Q15 | Background and AI use | Gender, birth year, education, income, health status, AI use duration, and frequency of AI health queries |
| Q17_1-Q17_3 | PCP | Perceived capability |
| Q17_13-Q17_15 | IQ | Information quality |
| Q18_3-Q18_4 | TAIGHA_Distrust | Distrust in AI-generated health advice |
| Q19_1-Q19_12 | LLM-D12 | Instrumental dependency (ID) and relational dependency (RD) |
| Q22_1-Q22_3 | HA | Health anxiety |
| Q26_1-Q26_12 | HBISF | Health behavior |



## Response scales

| Items | Scale |
| --- | --- |
| Q3 | 1 = Male; 2 = Female |
| Q4 | Four-digit birth year |
| Q5 | 1 = High school or below; 2 = Junior college; 3 = Bachelor's degree; 4 = Master's degree or above |
| Q6 | 1 = CNY 5,000 or below; 2 = CNY 5,001-10,000; 3 = CNY 10,001-15,000; 4 = CNY 15,001-20,000; 5 = More than CNY 20,000 |
| Q7 | 1 = Very healthy; 2 = Healthy; 3 = Fair; 4 = Poor |
| Q13 | 1 = 3 months or less; 2 = 3-6 months; 3 = 6-12 months; 4 = 1-2 years; 5 = More than 2 years |
| Q15 | 1 = 0 times; 2 = 1-3 times; 3 = 4-6 times; 4 = 7-10 times; 5 = More than 10 times |
| Q17 | 1 = Strongly disagree to 5 = Strongly agree |
| Q18 | 1 = Strongly disagree to 5 = Strongly agree |
| Q19 | 1 = Strongly disagree to 6 = Strongly agree |
| Q22 | 1 = Strongly disagree to 5 = Strongly agree |
| Q26 | 1 = Very inconsistent with me to 7 = Very consistent with me |

## Reverse-coded items

Raw responses are retained throughout the dataset.

- `Q19_10` is the reverse-worded LLM-D12 relational dependency item RD5.
  Recode it as `7 - response` before scoring.
- `Q26_4`, `Q26_5`, `Q26_6`, `Q26_10`, `Q26_11`, and `Q26_12` are
  reverse-worded HBI-SF items. Apply the scale's documented reverse-coding
  procedure before scoring.

## Disclosure

The file contains year of birth and other demographic details but no names,
contact details, participant IDs, IP addresses, or device identifiers.
Anyone redistributing or reusing the data should confirm that public release
is consistent with the applicable ethics approval and participant consent.

English question wording is provided to make the public dataset readable.
Where a validated English source wording exists, cite the original scale
publication rather than treating these labels as a new validated translation.
