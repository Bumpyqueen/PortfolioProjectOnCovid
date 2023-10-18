# PortfolioProjectOnCovid: COVID19 CASES IN THE WORLD.

PROCESSES TAKEN IN QUERYING DATA:
1. CREATED A TEMPORARY TABLE #COVIDDEATH, BROKE DOWN COVID CASES(DEATH_RATE, TOTAL_CASES AND  POPULATION) IN EACH CONTINENT
2. INSERTED ONE ADDITIONAL ROW("TOTAL") INTO THE TABLE TO CALCULATE THE TOTAL OF EACH COLUMN
3. CALCULATE AND UPDATED THE SUM OF COLUMN 2,3,4
4. QUERIED THE HIGHEST DEATH OF A COUNTRY FROM EACH CONTINENT

FINDINGS:
FROM THE DATASET AVAILABLE AND ANALYSIS, THERE ARE 6 CONTINENTS INFECTED BY THE COVID VIRUS
(Europe, Asia, North America, South America, Africa, Oceania)
FINDINGS:
1. THE "percent_of_tcases_and_popu" SHOWS THAT ~9.67% OF THE TOTAL POULATION WAS INFECTED BY COVID
2. THE "percent_of_tdeaths_and_popu" SHOWS THAT ~0.09% OF THE TOTAL POPULATION DIED DUE TO THE INFECTION
3. THE "percent_of_tdeath_and_tcases" SHOWS THAT ~0.90% OF THE PEOPLE WHO WERE INFECTED BY THE VIRUS DIED
-----------------------------------------------------------------------------------------------------------------------------------------------

FURTHER ANALYSIS ON "AFRICA": COVID19 CASES IN AFRICA
1.  Compared Total_Cases and Total_Deaths and the % of death rate if covid is contracted in each country in Africa
2.  Compared Total_cases, Population and Percentage of Population Infected with Covid
3.  Comparison between the Total_Death, Population and Percantage of the portion of the population who contracted Covid and died
4.  Comparison between highest infected Country and its Population i.e, Country with the highest infection rate
5.  Countries in Africa with the highest date rate queried in descending order
   
USING THE JOIN FUNCTION: 
1. COVID_DEATHS DATASET AND VACCINATION DATASET WAS JOINED TOGETHER USING UNIQUE KEYS 
2. USED PARTITION BY TO SHOW THE CUMMULATIVE POPULATION
3. USE CTE TO FIND THE CUMMULATIVE VACCINATION PERCENTAGE OF EACH CUMULATIVE VACCINATION



