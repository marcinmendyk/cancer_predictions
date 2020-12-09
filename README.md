# cancer_predictions

My goal for this analysis was to look for relationships between socioeconomic status and cancer by way of combining data from disparate open sources. I hypothesized that poorer regions would have fewer trials, and higher per capita cancer incidence and death rates.

This analysis Joins data from clinicaltrials.gov, cancer.gov & census.gov to examine cancer trials, mortality, incidence and demographics.

Input Data:
1. clinical trials ('study_fields.csv')
(.csv & .xml for all cancer trails 01/01/2010 through 06/01/2016)



2. Census income/poverty by county ('cen_income.csv'):

3. FIPS/ZCTA ('fips_zip_x.csv'):


4. Census population by county ('census_county_population.csv'):


5. Cancer incidence rates by county ('incdf_r.csv'):


6. Cancer death rates by county ('death_r.csv'):


Joined Data:
1. Grouped by county level ('countyData.csv')
studyCount feature aggregated by count, all others by mean
2. Grouped by zip code level ('zipCodeData.csv')
all features aggregated by mean
3. Ungrouped ('fullData.csv')