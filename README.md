# ASSESSMENT-OF-THEMATIC-MAPPING-TECHNIQUES-FOR-POPULATION-DISTRIBUTION-VISUALIZATION:
# Comparative study of Dot Density, Filled Isopleth and Unfilled Isopleth
-----
-----
# Abstract 
Thematic maps play a critical role in communicating spatial patterns and supporting geographic decision making. Among the various methods used to represent population density, Dot Density maps, Filled Isopleths (Colour-graded), and Unfilled Isopleths (Contour-based) are widely applied, yet their influence on users’ perception and interpretation of spatial density patterns remains insufficiently understood. This study investigates how these three cartographic representations affect the perception of population density, with particular emphasis on hotspot identification and spatial gradient interpretation. A between-subjects online experiment was 
conducted using maps representing both real-world and synthetic population distributions. 

Participants completed tasks while measure of accuracy, response time, and perceived difficulty were collected. Demographic information and self-reported cartographic experience were also recorded. 

The findings demonstrate that thematic map design substantially affects the interpretation of population density patterns. Filled Isopleths appear to provide the most effective support for both hotspot identification and gradient interpretation, while Dot Density maps remain useful for rapid exploratory assessment of spatial clustering. These results contribute to cartographic perception research and provide practical recommendations for selecting thematic map types in population mapping and related spatial analysis applications. 

# Keywords: 
Cartographic perception, Thematic Maps, Population Density, Filled isopleth, Unfilled Isopleth, Dot Density, Real-World, Synthetic, Hotspot Identification, Spatial Gradients, Map Usability, Spatial Cognition.

----
----
# 1. Introduction

Thematic maps are important tools for visualizing spatial patterns such as population density, income, temperature, and hazard exposure. In cartography, different map representations can influence how users perceive and interpret geographic information.

This project focuses on three thematic mapping techniques: Dot Density maps, Filled Isopleths, and Unfilled Isopleths. Dot Density maps show spatial concentration through repeated points, Filled Isopleths represent density using continuous colour surfaces, while Unfilled Isopleths use contour lines to show areas of equal value.

Although all three methods are valid, they communicate spatial patterns differently. As a result, users may interpret population density, hotspots, and spatial gradients with different levels of accuracy, speed, and difficulty.

The aim of this study is therefore to evaluate how these three map types affect the interpretation of population density patterns using both real-world and synthetic datasets.

----
----
## 1.1 Map Interpretation and User-Centred Design

Map design influences how users read, understand, and interpret spatial information. Thematic maps use abstraction, classification, colour, symbols, and visual hierarchy to communicate complex geographic patterns in a simpler form.

From a user-centred cartographic perspective, the effectiveness of a map depends not only on the data being mapped, but also on the user, the visual design, and the task being performed. Previous studies have shown that different map designs can affect interpretation accuracy, response time, perceived difficulty, and overall map-reading performance.

This study follows a user-centred approach by evaluating how different thematic map types support users in identifying population hotspots and interpreting spatial gradients. The evaluation is based on three usability measures: accuracy, response time, and perceived difficulty.

----
----
## 1.2 Research Gap

Previous studies have shown that thematic map type can influence map-reading performance. However, many existing studies focus mainly on map types such as choropleth maps, graduated symbol maps, and isoline maps.

There is still limited user-based research comparing Dot Density maps, Filled Isopleths, and Unfilled Isopleths within the same experimental framework, especially for population density visualization.

This study addresses that gap by comparing these three map types using both real-world and synthetic population datasets. It evaluates their effectiveness for two common interpretation tasks: hotspot identification and spatial gradient interpretation. 

----
----
## 1.3 Aim of the Study

The aim of this study is to assess how different thematic mapping techniques influence the interpretation of spatial population density patterns.

The study compares Dot Density maps, Filled Isopleths, and Unfilled Isopleths using real-world and synthetic datasets to understand how each representation affects users’ accuracy, response time, and perceived difficulty.

----
----
## 1.4 Research Objectives

### 1.4.1 Main Objective

To assess the impact of different thematic mapping techniques on the interpretation of spatial population distribution patterns.

### 1.4.2 Specific Objectives

1. Compare the effectiveness of Dot Density maps, Filled Isopleths, and Unfilled Isopleths for hotspot identification.
2. Evaluate how the three map types support spatial gradient interpretation.
3. Compare interpretation accuracy and response time across the map types.
4. Assess perceived difficulty associated with each map type and task.
5. Investigate the relationship between perceived difficulty and actual task performance.
6. Evaluate map usability using both synthetic and real-world population datasets.
7. Provide recommendations for selecting appropriate thematic mapping techniques for population density visualization.
----
----

# 2. Methods

This study used a controlled web-based user experiment to evaluate how different thematic map representations influence the interpretation of population density patterns.

A between-subjects experimental design was used. Participants were randomly assigned to one of three map conditions:

- Dot Density maps (DD)
- Filled Isopleths (FI)
- Unfilled Isopleths (UI)

Each participant interacted with only one map type throughout the experiment. This helped reduce learning effects, visual familiarity, and fatigue.

The experiment focused on two spatial interpretation tasks:

1. Hotspot identification
2. Spatial gradient interpretation

Map performance was evaluated using three measures:

- Interpretation accuracy
- Response time
- Perceived task difficulty

Both real-world and synthetic datasets were used. The real-world datasets provided realistic geographic contexts, while the synthetic datasets were generated in Python to create controlled hotspot and gradient patterns.

All maps were created from the same underlying datasets and were standardized using consistent layouts, scales, legends, and visual design settings. Dot Density maps represented population through point symbols, while Filled and Unfilled Isopleths were generated from continuous density surfaces.

Survey data were collected using LimeSurvey and analysed using statistical methods such as Chi-square tests, Kruskal-Wallis tests, and a Generalized Linear Mixed Model (GLMM).
Survey Link: https://survey.plus.ac.at/index.php/624757?lang=en

<img width="725" height="752" alt="image" src="https://github.com/user-attachments/assets/632faa94-ec9c-41d3-bd01-820d6dccb409" />

----
----
# Data Analysis

Data preprocessing and thematic map generation were carried out using GIS and spatial analysis tools, including ArcGIS Pro and Python.

The survey data were cleaned and organized in Excel before statistical analysis. The analysis focused on comparing the performance of the three thematic map types:

- Dot Density maps
- Filled Isopleths
- Unfilled Isopleths

Descriptive statistics were used to summarize participant information, interpretation accuracy, response time, and perceived difficulty ratings.

Comparative statistical tests were then used to examine whether performance differed between the three map types. The analysis also investigated the relationship between perceived task difficulty and actual task performance.

Statistical analysis was conducted in Jamovi, an open-source statistical software built on R. Jamovi was selected because it provides reliable statistical tools through a user-friendly interface, making it suitable for academic quantitative analysis.

----
----
## Statistical Methods Used

- Descriptive statistics
- Chi-square tests for accuracy comparisons
- Kruskal-Wallis tests for response time and difficulty comparisons
- Post-hoc tests where required
- Spearman correlation analysis
- Generalized Linear Mixed Model (GLMM)
----
----
# 3. Main Thesis Results

The results show that the choice of thematic map representation influenced how users interpreted population density patterns.

Overall, **Filled Isopleths** achieved the highest interpretation accuracy and were generally perceived as the easiest map type to use. **Dot Density maps** often supported faster responses, while **Unfilled Isopleths** were associated with higher perceived difficulty and lower overall performance.

## 3.1 Overall Performance

The three map types were compared using:

- Interpretation accuracy
- Response time
- Perceived task difficulty

The overall results suggest that Filled Isopleths provided the strongest balance between accuracy and usability, while Dot Density maps were useful for quick visual interpretation.

<!-- Insert overall accuracy, response time, and difficulty charts here -->

<img width="625" height="407" alt="Overall accuracy result" src="https://github.com/user-attachments/assets/7b904de7-e1ba-4bac-be17-ce6f17dbb5c5" />

<img width="687" height="786" alt="Response time result" src="https://github.com/user-attachments/assets/23bed77a-4e7b-452f-bc21-5e90d2758511" />

<img width="600" height="756" alt="Perceived difficulty result" src="https://github.com/user-attachments/assets/cae410e6-c61e-4779-b9f5-9b4ee0ca313e" />

----
----
## 3.2 Hotspot and Gradient Interpretation

The findings also show that map effectiveness depends on the type of task being performed.

Filled Isopleths were particularly effective for representing continuous density patterns and supporting spatial gradient interpretation. Dot Density maps remained useful for identifying local clustering and hotspot patterns, but they were less consistent in overall accuracy.

This suggests that no single map type is universally best. Instead, the most suitable representation depends on the analytical task and the type of spatial pattern being interpreted.

<!-- Insert hotspot and gradient comparison chart here -->

<img width="648" height="330" alt="Hotspot and gradient comparison" src="https://github.com/user-attachments/assets/62820723-bfb0-454c-ac8e-7720fe7b4b72" />

----
----
## 3.3 Real-World and Synthetic Dataset Comparison

The comparison between real-world and synthetic datasets showed similar performance trends across different spatial contexts.

The real-world datasets provided realistic geographic complexity, while the synthetic datasets allowed controlled testing of hotspot and gradient patterns. Together, they helped confirm that the observed differences were mainly related to the map representation rather than only the dataset type.

<!-- Insert real-world and synthetic dataset result here -->

<img width="555" height="751" alt="Real-world and synthetic dataset comparison" src="https://github.com/user-attachments/assets/15006ca5-306b-452a-81e0-47e950775c6d" />

----
----
## 3.4 Participant Characteristics

Participant characteristics such as age, gender, educational level, and cartographic experience had limited influence on overall task performance.

This suggests that the main performance differences were primarily driven by the map representations themselves rather than by demographic differences between participants.

<!-- Insert participant characteristics results here -->

<img width="716" height="738" alt="Participant characteristics result" src="https://github.com/user-attachments/assets/d6f94da3-91ff-4f76-afb5-df76f94308a1" />

<img width="657" height="306" alt="Participant characteristics summary" src="https://github.com/user-attachments/assets/dd5f8648-c987-4c74-983e-aef7b58d2f8a" />

----
----
## 3.5 Summary of Findings

The main findings of the thesis are:

- Filled Isopleths achieved the highest overall accuracy.
- Dot Density maps supported faster visual interpretation.
- Unfilled Isopleths were generally more difficult to interpret.
- Map effectiveness depended on the analytical task.
- Real-world and synthetic datasets showed consistent performance trends.
- Participant characteristics had limited influence on overall results.

Overall, the study highlights the importance of selecting thematic mapping techniques based on the intended task, the spatial pattern being visualized, and the target audience.






