# PROJECT-Mathematical-analysis-of-armed-conflicts

## Project Description

This repository presents my thesis, in which I analyze how six key factors influence the occurrence of international wars. The study is based on the work of **J. David Singer**, who originally proposed six indicators: Military Expenditures, Military Personnel, Energy Consumption, Iron and Steel Production, Total Population, and Urban Population. In the 1970s, he conducted extensive analyses using these factors as part of the **Correlates of War** project, which he founded to collect and examine data on international conflict — the primary data source used in my project. This thesis aims to revisit and extend his approach using both historical and modern data.

The work is divided into three main parts:

1. Replication and comparison – I reproduce Singer's original models (four variants using different sets of factors from 1825 to 1960) to analyze how his approach compares with today’s data and perspectives.
2. Parameter adjustment – I experiment with modifying the key parameter Singer used (originally set to 5) by testing values of 1 and 10, to explore how different time intervals affect the accuracy of conflict analysis.
3. Forecasting conflicts – I build predictive models based on both older and more recent datasets, to understand whether long-term or short-term historical data is more useful for forecasting international conflicts.

A brief summary of the results is provided in the **Summary** section of the thesis. It is recommended to read the first chapter "Theoretical Background of Armed Conflict Analysis" to better understand the methodology and context.

## Components
`Thesis_PL.pdf` - Original thesis in Polish (graded with 5).

`Thesis_ANG.pdf` -  My personal English translation of the thesis (not professional, but readable).

`Script_thesis.ipynb` – Python script used for all data analysis and modeling in the project.

`Presentation.ppt` – Final presentation of the project (in Polish).

`DATA` folder – Contains the following folders with datasets and accompanying documentation:

1. National Material Capabilities – Folder containing dataset (`NMC-60-abridged.csv`) with six key indicators for all recognized states from 1816 to 2016. Includes codebook (`NMC_Documentation_v6_0_final_v2.pdf`) describing data collection methods and definitions.

2. States – Contains a dataset identifying major powers (`majors2016.csv`) used in this project between 1816 and 2016, along with a codebook (`State-System-Membership-Codebook-V2016.pdf`) explaining the criteria for recognizing entities as sovereign states.

3. Wars – Dataset on international wars between 1823 and 2003 (`Inter-StateWarData_v4.0.csv`), involving recognized sovereign states. Codebook included (`Inter-StateWars_Codebook.pdf`).
