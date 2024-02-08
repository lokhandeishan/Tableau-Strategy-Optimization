<h1>Strategy Optimization using Tableau</h1>

<h2>Description</h2>

This project is a strategic analysis supporting Boston's zero-emissions goal, harnessing building data to steer the city's environmental policies. It integrates data processing, trend analysis, and geographic mapping to pinpoint areas for intervention, providing a robust tool for policymakers and stakeholders to visualize progress, ensure compliance, and strategize enhancements towards a sustainable future.

Through this project, we aim to reform policy decisions, monitor ordinance adherence, and identify focus areas for energy efficiency improvements, all through a user-friendly dashboard interface.

<h2>Project Overview</h2>

We undertake an in-depth analysis of Boston's building emissions data, with an eye on the city's 2050 zero-emissions target. The project's framework involved:

- Data preprocessing and exploration.
- Feature engineering, and selection using pandas and numpy in Python.
- Joining data in Tableau
- Visualization of results using Tableau.
- Inference driven recommendations.

<h2>Data Cleaning Methodology</h2>

The data sources for this research project are the <strong>Building Energy Reporting and Disclosure Ordinance (BERDO)</strong>, <strong>City of Boston Census data from 2016-2020 (4 datasets consolidated in 1) , Neighbourhood demographics</strong> and the <strong> City of Boston Utility Data</strong>, all of which are available in CSV format from the Boston Open Data Portal. The BERDO dataset provides information on energy and water usage for buildings that are required to report their energy usage annually to the City of Boston. The City of Boston Utility Data contains monthly energy usage data for municipal buildings, streetlights, and traffic signals, among other things.

The data is well-suited to address the research problem because it provides detailed information on energy usage and emissions from buildings in Boston, which is the primary focus of the zero-emissions ordinance. By analyzing this data, we can identify trends and patterns in building emissions and energy usage, which can help inform policy decisions and identify areas for improvement.

- <strong>Data Cleaning and Preprocessing:</strong> Utilized Python to cleanse the data, address missing values, and correct errors. Ensured data quality for accurate analysis.
- <strong>Data Selection:</strong> Focused on data from 2016 to 2020 to align with BERDO's availability. Targeted recent years for the most relevant emission trends.
- <strong>Emissions Threshold Flagging:</strong> Developed indicators in Tableau to spotlight buildings exceeding emission thresholds for 2016-2020.


<h2>Dashboards and Visualization</h2>
<br />

<p align="center">
<strong> Emission Analysis based on Zip Code / Postal Code </strong> <br />
<img width="1465" alt="image" src="https://github.com/lokhandeishan/Tableau-Strategy-Optimization/assets/157990694/61edd423-744e-49f0-ba8e-55572d2d42b7">

<br />
<br />

<p align="center">
<strong> Segregating Buildings into Age Buckets (New : >1950 ; Old : <1950) </strong> <br />
<img width="1470" alt="image" src="https://github.com/lokhandeishan/Tableau-Strategy-Optimization/assets/157990694/ff1d7bf1-84e1-403e-b6d3-ec8f6d6d8c89">
<br />
<br />

<p align="center">
<strong> Emmission Intensity Analysis Monitor (We define intensity as KgCo2/SqFt)</strong> <br />
<img width="1464" alt="image" src="https://github.com/lokhandeishan/Tableau-Strategy-Optimization/assets/157990694/dfe5f8ab-2ad8-43b7-b1b2-f3190f24bcf6">
<br />
<br />

<p align="center">
<strong>Condtions set to flag establishments</strong> <br />
<img width="495" alt="image" src="https://github.com/lokhandeishan/Tableau-Strategy-Optimization/assets/157990694/88b046de-66fe-458a-b737-84c929de293f">
<br />
<br />

<p align="center">
<strong>An Excel-like consolidated Overview sheet flagging emissions over the years 2016 to 2020 </strong> <br />
<img width="1466" alt="image" src="https://github.com/lokhandeishan/Tableau-Strategy-Optimization/assets/157990694/c67ff04e-c80e-417c-b18c-266425cc6abc">
<br />
<br />



<h2>Inference and Recommendation</h2>

<strong> Inference </strong>
- <strong>Building Age and Energy Efficiency :</strong> The analysis shows that older buildings have a significant impact on the city’s emissions. Targeting these buildings for retrofitting and energy efficiency improvements can lead to substantial reductions in overall emissions.
- <strong>Industry-Specific Emissions :</strong> Certain industries, notably hospitality, healthcare, and retail, have been identified as high emitters per square foot. These industries should be the focus of aggressive energy efficiency measures
- <strong>Geographic Emissions Intensity :</strong> Emissions are not evenly distributed across Boston. Some zip codes have higher emission intensities, highlighting areas where interventions could be most impactful.
- <strong>Trend Analysis :</strong> The emissions intensity trend over time reveals that despite some progress, more efforts are needed to meet future BERDO standards. This suggests the importance of sustained efforts and policy reinforcement.

<strong> Recommendation </strong>  

- Develop a tiered system for addressing energy efficiency in buildings, with priority given to older buildings and those in high-emission zip codes.
- Initiate targeted programs for the identified high-emission industries to facilitate the adoption of greener practices and technologies
- Leverage the Tableau dashboard for real-time tracking of emissions and to ensure accountability. Regularly update the dashboard with the latest data to reflect current trends and progress.
- Engage with property owners, especially those at risk of non-compliance, providing them with resources, guidance, and incentives to upgrade their properties.
- Engage with property owners, especially those at risk of non-compliance, providing them with resources, guidance, and incentives to upgrade their properties.

<h2>Libraries Used</h2>

- pandas
- numpy

<h2>Data Source</h2>

The data was sourced from a Analyze boston (https://data.boston.gov/)
