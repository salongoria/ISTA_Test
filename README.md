# ISTA_Test
## Question 1: Two resources:
- 1.1) https://www.ncbi.nlm.nih.gov/books/NBK606114/
- 1.2) https://www.healthcatalyst.com/learn/insights/reducing-hospital-readmissions-value-analytics

## Question 3: Describe dataset
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
