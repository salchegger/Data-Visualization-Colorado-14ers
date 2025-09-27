# Data Visualization Project: Colorado 14ers
As an avid hiker and nature lover, I'm fascinated by how people interact with the outdoors - where they go and how distance and difficulty shape their choices. Colorado's 14,000-foot peaks have always intrigued me, so I chose a project that combines both my passion for hiking and my interest in creating meaningful, **accessible data-driven solutions**.


 ## Project Overview
 This project explores Colorado's tallest mountain peaks exceeding 14,000 feet, focusing on **interactive visualizations** and **accessibility for all users**. Using **Pandas** for data preprocessing and **Vega-Altair** for interactive charts, I investigated patterns in:
 - Geospatial distribution
 - Correlations between difficulty and visitor trends
 - Comparative analysis between mountain ranges

The project also demonstrates a **screen-reader friendly website**, highlighting how a simple act of adding some additional code can support accessibility and enhance user experience, even for visually impaired people. <br>
For an **in-depth exploration**, the accompanying notebook provides a comprehensive analysis, methodology and additional visualizations.

## Key Features
- **Interactive Visualizations:** Hoverable tooltips, interactive maps and dynamic filters to explore the data intuitively
- **Accessibility Focus:** Screen-reader compatible web interface and inclusive design for users with visual impairment
- **Clean Data Pipeline:** Preprocessing of raw data to polished insights
- **AI-Assisted Website:** The website was generated with AI to demonstrate effective AI-assisted development while keeping focus on the underlying data


## Visualization Previews (Screenshots)

- **Boxplot:** <br>The boxplots visualize the elevation distributions in feet for Colorado's 14-foot peaks across six mountain ranges. The individual dots represent each mountain peak. In the notebook, you can highlight a single or all ranges by clicking on the according bar or hovering over single dots to get more information. <br>
  - The Sawatch Range displays the widest elevation spread with an interquartile range of approximately 150 feet, while the San Juan Mountains show the most compact distribution.
  - The Sawatch Range and Front Range contain the highest median elevations, both exceeding 14,200 feet.
  - Several ranges including the San Juan Mountains and Sangre de Cristo Range show outliers representing individual peaks that deviate from their range's typical elevation profile.
  - The Elk Mountains demonstrate the most symmetric distribution, while the Mosquito Range shows a slightly negative skew with higher concentration of peaks at the upper elevation range<br> <br>
     <img width="600" height="293" alt="image" src="https://github.com/user-attachments/assets/dcf7334e-d004-45df-bfe2-d1bac7ab022b" />
<br> <br>
- **Geospatial Scatter Plot:** <br> The geospatial scatter plot displays the distribution of Colorado's 14,000-foot peaks across latitude and longitude coordinates, with points colored by elevation gradient from 14,000 feet (cooler/darker colors) to almost 14,500 feet (warmer/brighter colors). In the notebook you are provided with a dropdown menu to highlight individual mountain ranges and a tooltip to get more information about peaks upon hovering on single dots.
  - The peaks follow a distinct north-south alignment along the Rocky Mountain corridor, with clusters in specific geographic regions corresponding to the major mountain ranges.
  - Higher elevation peaks (shown in yellow) concentrate primarily in central Colorado, while lower 14ers (blue/purple) appear more frequently in southern regions.
  - The spatial distribution reveals clear geographic grouping by mountain range, with noticable gaps in between the individual ranges.
  - Density variations indicate areas of concentrated peak existence versus more isolated mountain formations. <br> <br>
    <img width="600" height="411" alt="image" src="https://github.com/user-attachments/assets/c207673c-16e2-404c-a29c-3182de6b9dcd" />
<br> <br>

- **Scatter Plot:** <br> The Scatter plot compares route distance (miles) against elevation gain (feet) for Colorado 14ers, with points color-coded by hiking difficulty class (1-4) and sized by average annual visitor numbers. The visualization is an interactive map that lets you zoom in and out. Hovering over bubbles provides you with the exact stats of the mountain peaks.
  - Class 1 and 2 routes (easier difficulties) cluster in the lower left quadrant with shorter distances under 12 miles and elevation gains below 6,000 feet, while also showing the larger bubble sizes indicating higher visitor traffic.
  - Class 3 and 4 routes (more difficult) extend toward the upper right with longer distances exceeding 15 miles and elevation gains above 5,000 feet, accompanied by smaller bubble sizes reflecting fewer visitors.
  - A positive correlation is evident between route distance and elevation gain, with visitor popularity showing an inverse relationship to technical difficulty rather than route length alone.
  - There is one individual outlier, with a route distance of 26 miles and an elevation gain of 7,500 feet. Its difficulty level is 1, and despite the length it is fairly popular amongst hikers. <br> <br>
     <img width="600" height="289" alt="image" src="https://github.com/user-attachments/assets/3dda815b-6f57-48e7-8d48-2c34804c7d9e" />


## Key Takeaways
- **Data-driven storytelling:** The project shows how combining geospatial and statistical visualizations uncovers clear patterns in geography, difficulty and popularity in hikes.
- **Accessibility in practice:** Even small design decisions, such as choosing proper color schemes or adding screen reader support, can make data insights more inclusive.
- **Technical growth:** I strengthened my skills in Pandas, Altair and structuring a clean data pipeline, while also experimenting with AI-assisted development for building a supporting website.

## How to explore?
- Visit the live website [https://salchegger.github.io/Data-Visualization-Colorado-14ers/] <br>
  *(recommended Browser for screen-reader accessibility: Microsoft Edge)*
- Clone the repository to explore the dataset and visualizations locally:
  
```bash
git clone https://github.com/salchegger/Data-Visualization-Colorado-14ers.git
cd colorado-14ers
