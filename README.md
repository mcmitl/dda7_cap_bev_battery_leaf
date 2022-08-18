
# Intro: 2011 to 2017 Nissan LEAF surveys: Battery Degradation Analysis
  Analysis on BEV lithium-ion batteries durability using the Nissan LEAF as a case study.
  * by Mitl Data Analytics Full-Time 7 Nashville Software School Cohort

  ## Table of contents
  * [Executive Summary](#Executive Summary)
  * [Motivation](#Motivation)
  * [Data Question](#Data Question)
  * [Methodology](#Methodology)
  * [Data Sources](#Data Sources)
  * [Technologies](#technologies)
  * [Known Issues and Challenges](#Known Issues and Challenges)

## Executive Summary
  2011 to 2017 Nissan LEAF surveys: Battery Degradation Analysis
  Looking at historical data from the Nissan LEAF, 1st mass-produced electric vehicle, to determine long-term EV battery performance

## Motivation
  As battery electric vehicles (BEV) are increasingly being marketed as an economic option to internal combustion engine vehicles (ICE), I took a look into the reports of Nissan LEAF owners regarding the battery capacity, mileage and range to see when the battery will need to be replaced and how that would impact the cost.
  The battery replacement costs are often omitted in most advertisements. How much could battery deterioration affect the overall cost of a used BEV?

## Data Question
  Actual Nissan LEAF owners submitted surveys about their LEAFs which date back to model 2011, including mileage and the number of battery capacity bars on display at the time of survey. Over time as the battery loses capacity, the car displays fewer battery capacity bars. This is an indicator of battery longevity.
  Will the battery degrade significantly over time and require costly replacement?  
  What is the total cost when replacement is considered and how does it compare to a internal combustion engine (ICE) vehicle of a similar model?

## Methodology
  ### Data Acquisition
  Survey data on 647 Nissan LEAFs from Plugin America. 647 vehicles reported from 2011 to 2019 model year.
  I gathered data on the age, mileage and battery capacity bars of Nissan LEAF cars from Plug In America’s surveys, in which car owners around the world self-report real-life vehicle stats. This data covers LEAFs built between 2011 and 2019, of various age and mileage.

  ### Exploratory Analysis of Surveys from Plug In America
      ● I then analyzed the information which covered over a thousand entries across 647 vehicles, in order to understand the relationship between battery capacity bars and the age and mileage of a battery electric vehicle (BEV).
      ● 601 surveys came from the United States and the remaining 46 from other countries.
      ![Survey US](../media/Survey_United_States.png)
      ● Half of surveys are from the 2011 Nissan LEAF model which gives us the most span of years. Due to a very low number of surveys, I decided not to include recent model years and kept 2011 to 2017 model year vehicles.
      ![Model Year](../media/LEAF_Model_Year.png)
      * Outliers
      ● I found statistical outliers in the survey data and used the IQC method.
      ![Outliers](../media/IQR.png)

  ### Findings
  How does range change over the first few years of car ownership?
  ![Avg Years](../media/LEAF_Avg_Years.png)
  Battery degradation occurs at earlier miles in warmer states than in colder states
  The 1st capacity bar is lost (bar 11) at an average of 26,000 miles and 2.4 years
  LEAF Battery Degradation by mileage
  ![Avg Mileage](../media/LEAF_Avg_Mileage.png)
  Created a dashboard in Tableau to present findings


##Data Sources
  * Plugin America.org survey data
  * Nissanusa.com for battery specs, chargers and installation prices
  * Kelly Blue Book for used vehicle prices (kbb.com)
  * LEAF forums and other auto trade journals (optional)

##Technologies
  * Jupyter Notebook
  * Python 3.9
  * Tableau Desktop
  * Microsoft Excel
  * Microsoft PowerPoint

##Known Issues and Challenges
  * ●	Unable to get actual Nissan LEAF data from manufacturer as it’s confidential.
  * ●	Limited Data from Surveys as only 647 vehicles were reported out of more than 500,000 sold worldwide.
