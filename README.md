# Readme
This .csv format dataset contains point-in-time homeless population counts from 2019, focusing on the rural Northern California counties including Humboldt, Mendocino, Redding/Shasta, Siskiyou, Lassen, Plumas, Del Norte, Modoc, Sierra counties. 

It was created for a class at the University of Washington iSchool in March 2021. The intended audience is policymakers and social service workers, with the intended purpose to create legislation and services serving rural homeless communities as well as tracking the rates of homelessness in remote areas of Northern California. The dataset was created from open access government reports from the Department of Housing and Urban Development (HUD), as provided by Continuums of Care (CoC), and it is freely available to the public.

The naming convention for files should be: 'year_datasettype'. The year indicates the year in which the point-in-time count occurred, and the data set type indicates whether the data is raw or normalized. 

# Data Dictionary
  |Variable | Variable Name |	Measurement Unit |	Allowed Values |	Definition |
  |----------|---------------|------------------|-----------------|-------------|
  | hudCoc |	HUD CoC	| String |	HUD CoC codes |	County codes assigned by HUD and CoC |
  | countyName	| County Name	| String	| Names of California counties	| Names of counties within California |
  | date	| Date |	Date |	MM-DD-YYYY |	Date of point-in-time count of homeless population |
  | genderFemale |	Female | 	Numerical |	Numbers greater or equal to 0 |	Count of female-identifying homeless persons |
  | genderMale |	Male | 	Numerical |	Numbers greater or equal to 0 |	Count of male-identifying homeless persons |
  | genderTrans  |	Transgender |	Numerical |	Numbers greater or equal to 0 |	Count of transgender-identifying homeless persons |
  | genderNone |	Gender Noncomforming  |	Numerical |	Numbers greater or equal to 0 |	Count of gender non-conforming homeless persons |
  |totalCount |	Total Count |	Numerical |	Numbers greater or equal to 0 |	Total count of homeless persons |
  
# Metadata
  Schema used: Project Open Data
  | Attribute | Value |
  |-----------|-------|
  | conformsTo |	https://project-open-data.cio.gov/v1.1/schema |
  |accessLevel |	public|
  |accuralPeriodicity |	R/P1Y |
  |fn	| Madeline Carruthers |
  |hasEmail |	mailto: madelinecarruthers@gmail.com|
  |description |	This dataset is a combination of point-in-time homeless counts conducted in January 2019 for a set of rural Northern California communities, including Humboldt, Mendocino, Redding/Shasta, Siskiyou, Lassen, Plumas, Del Norte, Modoc, Sierra counties. The intended audience is policymakers and social services. This dataset was curated for a class project within the University of Washington iSchool in Winter 2021.|
  |format |	CSV |
  |mediaType  |	CSV |
  |issued |	2021-03-07 |
  |keyword	| "homeless population", "point-in-time count", "northern california", "rural communities", "mendocino", "humboldt", "redding/shasta", "siskiyou", "lassen", "plumas", "del norte", "modoc", "sierra" |
  |language |	en-us |
  |modified |	2021-03-08  |
  |publisher  |	Madeline Carruthers |
  |references |	https://files.hudexchange.info/reports/published/CoC_PopSub_CoC_CA-516-2019_CA_2019.pdf, https://files.hudexchange.info/reports/published/CoC_PopSub_CoC_CA-522-2019_CA_2019.pdf, https://files.hudexchange.info/reports/published/CoC_PopSub_CoC_CA-509-2019_CA_2019.pdf |
  |rights |	These data are publicly available to all within their respective government repositories and within this repository.|
  |temporal |	2020/P1Y  |
  |theme  |	"homeless population", "northern california", "rural communities" |
  |title |	Rural Northern California Homeless Population |
  
 # Security
 The data is freely available to the public.
 
 # Contact
 Madeline Carruthers, madelinecarruthers@gmail.com
