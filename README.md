<p align="center">
  <img width="200" height="200" src="https://github.com/a-pradono/padi_scuba_diving/blob/main/Images/header.jpg">
</p>
<p align="center">
Photo by <a href="https://unsplash.com/@pascalvendel?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Pascal van de Vendel</a> on <a href="https://unsplash.com/photos/scuba-diver-watching-school-of-gray-fish-underwater-gcG_b9ijyqU?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
</p>


## Table of Contents

- [I. Introduction](#i-introduction)
- [II. Data and Methodology](#ii-data-and-methodology)
- [III. Results](#iii-results)
- [IV. Conclusions](#iv-conclusions)

## I. Introduction
Scuba diving allows you to explore the underwater world, whether looking into coral reefs or swimming with beautiful ocean creatures. I got my first taste of underwater experience when I got my open water scuba diving certification from the Professional Association of Diving Instructors (PADI) in 2016. Since that day, scuba diving has become one of my favorite outdoor activities, and I look forward to each opportunity to dive into this incredible adventure. Having experienced diving at various dive sites across Indonesia, I'm more inspired to explore other dive destinations around Southeast Asia—a dream that's now on my bucket list. Therefore, the objective of this project was to explore PADI scuba diving data in Southeast Asia through analytical processes.

## II. Data and Methodology
This project is built using PADI scuba diving data, which can be found on the [PADI](https://www.padi.com/dive-sites/all/) website. The information is reliable since it was retrieved from the official website. 

<p align="center">
  <img width="400" height="200" src="https://github.com/a-pradono/padi_scuba_diving/blob/main/Images/workflow.jpg">
</p>

The workflow above illustrates the process of achieving the objective. In the first place, the data was automatically scraped or extracted from the website. Once the data was stored in the data frame, data cleaning was performed to identify incorrectly formatted structure data or fix incorrect values to ensure data is reliable for further analysis. Finally, data analysis is the final step to explore the data frame to summarize the main findings that include some data visualizations.

## III. Results
The first figure below explains the initial findings of the data that was first gathered from web scraping. The content column has more information regarding the scuba diving data. 

<p align="center">
  <img width="500" height="200" src="https://github.com/a-pradono/padi_scuba_diving/blob/main/Images/plot01.PNG">
</p>

In this cleaning process, the essential first step was to split the data based on the delimiter '/' in the content column, which helps for easier parsing of individual components within each entry. Following this, some important values were selected from the split data, filtering out any irrelevant or redundant information. Moreover, some characters should be replaced to correct errors or standardized formats to maintain the consistency of the data frame.

<p align="center">
  <img width="200" height="200" src="https://github.com/a-pradono/padi_scuba_diving/blob/main/Images/plot02.PNG">
</p>

After the data cleaning part, the data frame consists of 11 countries across Southeast Asia. Based on the bar plot, the Phillipines has the most diving sites among other countries, followed by Indonesia and Thailand. On the other hand, India has the smallest amount of diving sites in Southeast Asia. This makes sense since India is part of South Asia, and the inclusion of this dive site perhaps largely due to their geographical proximity relative to Southeast Asia.

<p align="center">
  <img width="500" height="250" src="https://github.com/a-pradono/padi_scuba_diving/blob/main/Images/plot03.png">
</p>

How deep are these diving sites? That was my question. The figure indicates that the Philippines has the deepest dive site, reaching up to 120 meters. Vietnam has the shallowest dive site, which is around 18 meters.

<p align="center">
  <img width="500" height="250" src="https://github.com/a-pradono/padi_scuba_diving/blob/main/Images/plot04.png">
</p>

In addition, I have created an interactive chart to visualize all the dive sites around Southeast Asia. The dropdown button was added for filtering countries to see dive sites, which provides a user-friendly way to explore dive sites by country that includes valuable information about dive types, water types, and entry.

<p align="center">
  <img width="400" height="200" src="https://github.com/a-pradono/padi_scuba_diving/blob/main/Images/plot05.gif">
</p>
<p align="center">
Interactive chart can be accessed <a href="https://datapane.com/u/apradono94/reports/E7yl2P3/chart-3/">here</a>
</p>

## IV. Conclusions
The objective of this project was to investigate the PADI scuba diving data in Southeast Asia. The following are the conclusions drawn from this project:
  * Out of all the other countries, Phillipines has the most dive sites around Southeast Asia.
  * Vietnam has the shallowest dive site, while Phillipine has the deepest dive site.
  * By following this workflow, we are able to efficiently turn large unstructured website data into valuable insights regarding the underwater world.
