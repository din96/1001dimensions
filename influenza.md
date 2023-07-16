
![influenza-banner-web](_static/assets/influenza-banner-web.png "influenza-banner-web")

# Influenza Data Set
This data set contains information about influenza deaths, population, lab results, and flu shot rates in the United States. The data set consists of four sources:
- **Influenza deaths:** Number of deaths by week, state, and age group from 2014 to 2020. Source: CDC's NCHS Mortality Surveillance System.

- **Population data:** Population estimates by state and age group from 2010 to 2019. Source: U.S. Census Bureau's Population Estimates Program.

-  **Counts of influenza lab results:** Number of specimens tested by week, state, and type/subtype from 2014 to 2020. Source: CDC's FluView Interactive application.

-  **Survey of flu shot rates in children:** Percentage of children vaccinated by month, state, and age group from 2018 to 2020. Source: CDC's National Immunization Survey-Flu.

The data set was used to analyze and compare flu activity and vaccination in the US.

---
## Objectives
```{admonition} Learning objectives
:class: dropdown
- Write hypotheses and plan the research design
- Mine data
- Conduct descriptive statistics
- Test hypotheses or make estimates with inferential statistics
- Master Excel and Tableau
```
```{admonition} Project objectives
:class: dropdown
AMN Healthcare is a medical staffing agency that supplies temporary workers to clinics and hospitals on a contingency basis. The agency wants to forecast staffing needs across the country for the upcoming Influenza season, a period of high demand for additional staff. <br/>
Investigate the patterns and correlations and decide how to allocate temporary medical staff across the states for the upcoming season.
```

## Project Plan
| Milestone                         | Tasks                                                                                                                                                                                                      | Deliverables                                  |
|-----------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------|
| Data Research Design              | Analyse project brief, align with stakeholders, generate project's hypothesis, and design data research project. Review available literature, and describe the data set, incl. relevance, and limitations. | project overview and plan, pdf                |
| Data Set Investigation & Cleaning | Create data profiling and integrity audit, measure data quality, and create a cohesive data set for statistical analyses.                                                                                  | Excel file, documentation file                |
| Statistical Analysis              | Conduct descriptive analysis and statistical hypothesis testing.                                                                                                                                           | Excel file, documentation file                |
| Interim Data Analysis Report      | Create an interim report with insights and findings.                                                                                                                                                       | Report pdf                                    |
| Data Visualization                | Decide on the best fitting data visualization type, create charts and the dashboard in Tableau. Consolidate findings.                                                                                      | Tableau dashboard, final documentation folder |
| Presentation                      | Present the research findings and recommendations to the key stakeholders.                                                                                                                                 | Tableau dashboard, presentation file          |

## Process
### Data Preparation
First, I performed **data profiling** to assess the structure, content, and quality. I used Excel functions and formulas to explore the data set. I checked for errors, inconsistencies, or missing values in the data and documented them in a data quality report.

Next, I implemented **data integrity and quality checks** to identify and resolve issues. I used Excel's data validation and conditional formatting features to highlight and correct invalid or inaccurate data entries. I also used Excel's Pivot Tables and Charts to summarize and visualize the data distribution and identify any outliers or anomalies.

```{admonition} Results in Excel file
:class: seealso
<a href="https://docs.google.com/spreadsheets/d/1rqjnr1F8Macox26OKS4aKBwt1jY3oT4S2KYvfqFMfw4/edit?usp=sharing" target="_blank">Explore the Excel file</a> exported to Google Sheets.
```

The final step was to apply **data transformations** such as filtering, sorting, grouping, and aggregating to integrate data from multiple sources into a unified data set for analysis. I used Excel's VLOOKUP function to join data from different worksheets based on common keys. 


### Data Analysis 


::::{grid}

:::{grid-item}
:columns: 6
I conducted various **statistical analyses** to explore the data and answer the research question. Next, I calculated the **variance and standard deviation** for key variables to measure their dispersion and variability. Then I identified **correlations** between variables to examine their linear relationship. I formulated a statistical **hypothesis** based on the research question and conducted hypothesis testing using appropriate methods and significance levels. 
```{admonition} Hypothesis
:class: hint
*The bigger fraction of 65+ years old people in the state results in proportionally higher numbers of death caused by influenza.*
```
:::
:::{grid-item}
:columns: 6
![influenza-hypothesis](_static/assets/influenza-report.png "influenza-report")
:::
:::{grid-item}
:columns: 12
I interpreted the results of the hypothesis testing and drew conclusions. Then I created a comprehensive interim report consolidating the findings of the statistical analyses and providing recommendations. 
:::
::::

```{admonition} Interim Report
:class: seealso
Explore the results from the <a href="_static/influenza/influenza-report.pdf" target="_blank">interim report.</a>
```

### Data Vizualisation & Findings
In the final part of the project I used Tableau to create various types of charts and visualizations to present the data analysis results. I showed the parts of a whole and the differences between categories by using composition and comparison charts such as pie charts, bar charts, and stacked area charts. 

## Results
````{div} full-width
<div class='tableauPlaceholder' id='viz1689516709704' style='position: relative'><noscript><a href='#'><img alt='Influenza in USA ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;In&#47;Influenza-Storyv_1_5&#47;InfluenzainUSA&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Influenza-Storyv_1_5&#47;InfluenzainUSA' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;In&#47;Influenza-Storyv_1_5&#47;InfluenzainUSA&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1689516709704');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
````

<!---
## Challenges
- Tableau settings for responsiveness
- Excel VLOOKUP
- Problem with data sets
- Data sets research and new data integration
--->