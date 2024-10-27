# **Analysis of Historical Trends in Crimes Against Women in India (2001-2014)**

## **Introduction**
Between 2001 and 2014, crimes against women in India garnered increasing national attention, prompting debates, policy reforms, and social movements. This report provides a comprehensive analysis of crime data from this period, aiming to uncover trends, patterns, and regional disparities in crimes against women across Indian states and Union Territories. 

## **Objectives**
The primary objectives of this analysis are:
1. To understand historical crime trends against women across India.
2. To identify regions with the highest and lowest reported incidents for various types of crimes.

## **Data Overview**
The dataset used in this analysis includes reported cases across seven primary crime categories from 2001 to 2014 for each district within India’s states and Union Territories. The dataset contains the following columns:

- `STATE/UT`: Name of the State or Union Territory
- `DISTRICT`: Name of the district
- `Year`: Year of record
- `Rape`: Number of reported rape cases
- `Kidnapping and Abduction`: Number of reported cases
- `Dowry Deaths`: Reported dowry-related deaths
- `Assault on women with intent to outrage her modesty`
- `Insult to modesty of Women`
- `Cruelty by Husband or his Relatives`
- `Importation of Girls`: Reported cases of trafficking or importation

## **Data Cleaning and Preparation**
To ensure the accuracy and consistency of analysis:
1. Duplicated `STATE/UT` names were normalized to uppercase.
2. Inconsistent values were corrected (e.g., "DELHI UT" was standardized to "DELHI").
3. A `Total crime` column was added, representing the sum of all crimes for each row.

### **Cleaned Data Sample**
| STATE/UT       | DISTRICT | Year | Rape | Kidnapping and Abduction | Dowry Deaths | Assault on women... | Insult to modesty... | Cruelty by Husband... | Importation of Girls | Total crime |
|----------------|----------|------|------|---------------------------|--------------|----------------------|----------------------|-----------------------|----------------------|-------------|
| ANDHRA PRADESH | ADILABAD | 2001 | 50   | 30                        | 16           | 149                  | 34                   | 175                   | 0                    | 454         |

## **Data Analysis**

### **Proportion of Crimes Against Women (2001-2014)**
Each crime category was analyzed to identify its proportional contribution to total reported cases from 2001 to 2014. The results, visualized as a pie chart, reveal that:
- **Cruelty by Husband or Relatives** accounts for the highest proportion (approximately 41.6%).
- **Assault on Women with Intent to Outrage Modesty** follows at 22.6%.
- **Kidnapping and Abduction** (13.9%) and **Rape** (11.5%) also constitute significant portions.

### **Trends Over Time (2001-2014)**
An examination of overall crime trends reveals a clear escalation in reported cases over the years. Key observations include:
1. Total reported cases rose consistently, with significant increases post-2008.
2. The years 2013 and 2014 show the highest spike in crime counts, likely due to increased awareness and reporting after major national incidents.

The line chart depicting yearly crime trends underscores a sharp incline, particularly from 2012 to 2014, with a jump from approximately 465,000 cases in 2012 to over 634,000 in 2014.

### **Trends by Crime Type**
Yearly trends for each specific crime category show varied growth rates:
- **Rape and Kidnapping/Abduction**: Both saw a consistent increase, with marked spikes post-2012.
- **Assault and Insult to Modesty of Women**: Showed significant year-on-year growth, especially from 2007 onward.
- **Cruelty by Husband or Relatives**: Despite being the most reported crime, it exhibited more gradual growth relative to others.

### **State-Wise Crime Distribution**
Analysis of state-wise crime occurrences highlights regions with disproportionately high reported incidents. Notably:
- **Uttar Pradesh** and **Andhra Pradesh** recorded the highest crime counts across categories.
- **West Bengal** ranks high in crimes involving cruelty by husbands or relatives.
- **Rajasthan** and **Madhya Pradesh** also report high counts, especially in Rape and Kidnapping/Abduction.

| State/UT         | Rape | Kidnapping and Abduction | Dowry Deaths | Assault on women... | Insult to modesty... | Cruelty by Husband... | Importation of Girls |
|------------------|------|--------------------------|--------------|---------------------|----------------------|-----------------------|----------------------|
| Uttar Pradesh    | 51,150 | 135,906 | 57,256 | 91,212 | 53,130 | 193,738 | 6 |
| Andhra Pradesh   | 32,150 | 34,504 | 13,844 | 126,952 | 86,964 | 280,906 | 34 |
| West Bengal      | 47,876 | 61,158 | 12,308 | 66,908 | 5,348 | 344,124 | 254 |
| Rajasthan        | 45,684 | 66,278 | 11,854 | 83,362 | 794 | 262,200 | 14 |

## **Key Findings and Observations**
1. **Cruelty by Husband or Relatives** is the most prevalent crime across most states, with Andhra Pradesh and West Bengal reporting particularly high numbers.
2. **Uttar Pradesh** leads in reported cases of **Kidnapping and Abduction**.
3. **Rape** incidents rose considerably, especially in **Madhya Pradesh**, which ranks among the highest for this crime type.

## **Conclusion**
The analysis of historical crime data from 2001 to 2014 highlights an upward trend in reported crimes against women across India. These findings suggest increased awareness and reporting, particularly in the later years. However, the persistent high counts of domestic and sexual violence underline the urgent need for continued policy interventions, public awareness, and support systems to address and reduce crimes against women.

## **Future Scope**
Further studies could explore:
- Socioeconomic and demographic factors driving regional disparities.
- The impact of government policies and social campaigns on crime rates post-2014.
- Comparative analysis with more recent data to understand current trends and improvements, if any.
