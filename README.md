# ISTA_Test
## Question 1: Two Resources:
- 1.1) https://www.ncbi.nlm.nih.gov/books/NBK606114/
- 1.2) https://www.healthcatalyst.com/learn/insights/reducing-hospital-readmissions-value-analytics

## Question 3: Describe Dataset
| Column Name | Description | Data Type |
|---------------|-------------|------------|
| Facility Name | Name of the hospital or healthcare facility | Categorical (object) |
| Facility ID | Unique numerical identifier for the facility | Numerical (int64) |
| State | U.S. state abbreviation where the facility is located | Categorical (object) |
| Measure Name | Specific readmission measure being reported (e.g., why the patient came back) | Categorical (object) |
| Number of Discharges | Total number of discharges counted in the measure | Numerical (float64) |
| Footnote | Additional notes or explanations about the readmission | Numerical (float64) |
| Excess Readmission Ratio | Ratio of observed to expected readmissions (1 = expected amount of readmissions) | Numerical (float64) |
| Predicted Readmission Rate | Predicted rate of readmissions based on that specific facility/hospital | Numerical (float64) |
| Expected Readmission Rate | Expected average rate of readmissions at that specific facilty/hospital | Numerical (float64) |
| Number of Readmissions | Number of readmissions recorded | Categorical (object) |
| Start Date | Start date of the measurement period | Categorical (object, date in string format) |
| End Date | End date of the measurement period | Categorical (object, date in string format) |

## Question 4: Research Question
- Can we predict which hospitals/medical facilities are likely to incur higher costs due to higher readmission rates given in the dataset?

## Question 5: Question Significance
- As said in the original mission statement hospital readmissions are a significant driver of healthcare costs in hospitals and healthcare facilities. When patients get readmitted, the hospital not only has to endure the cost of operational expenses for that patient, but can also potentially face finacial penalties/fines from national programs like CMS and HRRP. By making this model to predict which hospitals in the country are most likely to incur these higher costs due to higher readmission rates, we can help the board make infromaed decisions on where to focus resources and efforts around the country (I am assuming this a "board" for every single medical facility\ies listed on the dataset). Ultimately, this research helps the hospital proactively identify high-risk areas and implement strategies to reduce unnecessary readmissions, improving patient outcomes while controlling costs. Beyond financial savings, reducing readmissions means patients experience better care and fewer disruptions to their recovery.
