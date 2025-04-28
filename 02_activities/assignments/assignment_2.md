# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      1. South Korea - Demographics by Marc Reid (available here: https://public.tableau.com/app/profile/marc.reid/viz/SouthKorea-Demographics/SouthKoreaPopulationDensityandDemographics): This graphic aims to visualize the changes in the population density and demographics in South Korea by highlighting the decline in 2021, as described in the abstract. However, there are pieces of information either missed or poorly represented in the graphics: 1. There are two maps on the left side that seem to represent duplicated information as the big map is a zoomed view of the map in the left corner, but the authors did not highlight which section is zoom in the small map; 2. The black hexagons are not included in the "Population density for 400 m H3 hexagons [1]" scale, making it dubious if black represents either "missing data" or "unhabited zones"; 3. The following graphs do not have a Y axis, making it hard to interpret: 1. Country Population Density, 1966 - 2022, 2. Female, male, and overall life expectancy, 3. Adolescent and total fertility rates, and 4. Female and male % of total population; 4. The title of the "Female, male, and overall life expectancy" graph is not fully visible in the visualization; 5. The "female and male percentage of the population by age group" graph does not have an x-axis or scale helpful to understand the variations in percentages; 6. In the "Female, male and overall life expectancy [4]" graph, the word "overall" seems to represent one of the lines in the plot but the color used to highlight the word is quite similar to the rest of the text making it confusing; 7. the graph "Population % increase or decrease" does not have a reference, like to other graphs in the visualization. Because of the reasons above, I categorized this visualization under “bad”. The suggested improvements are listed in the following section.   

      2. AI-Powered Climate Change Series: CO2 Monitoring by Harim Jung (Available here: https://public.tableau.com/app/profile/harim.jung/viz/GlobalCODashboardPoweredbyTableauAgent/TableauAgentClimateDashboard): This group of graphics aims to represent the cumulative carbon clock by correlating different metrics of CO2 across multiple comparisons. The following correspond to reasons why these graphics are good examples of visualizations. However, check the improvement suggestions in the next section: 1. All graphs have x and y axes, titles, contrasting color palette, additional comments to fully describe the graphics and provide insight on their interpretation; 2. The 2019 date of interest is highlighted across all graphs; 3. The graphs "CO2 emissions from Energy South Korea from 2019" and "CO2 emission % from energy South Korea from 2019" have data in front of each bar making clear the emissions and percentages, respectively; 4. the graph "CO2 per GDP vs CO2 per Capita" has vertical and horizonal lines in each axes making easier the interpretation of the graph; 5. The cumulative carbon clock on the left has labels per income, in addition to numbers accompanying the plot; 6. The "CO2 Global Share", "CO2 Cumulative Share", "CO2 Cumulative Share/Population", "CO2 Emission", "CO2 per GDP", and "CO2 per Capita" graphs have arrows indicating the pattern of the data behavior - red for low and green for high. Based on the previous reasons, I categorized this graph as "good". 

      ```
    - How could this data visualization have been improved? 
        
      ```
        1. South Korea - Demographics by Marc Reid (Available here: https://public.tableau.com/app/profile/marc.reid/viz/SouthKorea-Demographics/SouthKoreaPopulationDensityandDemographics): Following my observations above, I suggest the following changes: 1. The map in the left corner should be highlighted in the section represented on the big map; 2. Include a black hexagon in the "Population density for 400 m H3 hexagons [1]" scale; 3. Add Y axis on the following graphs: 1. Country Population Density, 1966 - 2022, 2. Female, male, and overall life expectancy, 3. Adolescent and total fertility rates, and 4. Female and male % of total population; 4. Make the title of the graph "Female, male, and overall life expectancy" visible; 5. Add an x-axis or scale helpful to understand the variations in percentages in the graph "female and male percentage of the population by age group"; 6. Change the color of the word "overall" in the "Female, male and overall life expectancy [4]" graph; 7. Add a reference for the graph "Population % increase or decrease"; 8. Try to include the same timescale across all graphs. Good point: the color palette in the maps is a color blind palette, "inferno". 

        2. AI-Powered Climate Change Series: CO2 Monitoring by Harim Jung (Available here: https://public.tableau.com/app/profile/harim.jung/viz/GlobalCODashboardPoweredbyTableauAgent/TableauAgentClimateDashboard): I suggest making the following changes: 1. The Cumulative Carbon Clock on the left should be represented in a better way that includes an informative CO2 emissions scale. Although the figure includes comments that explain data behavior, plotting the clock on a scatter plot could be more beneficial for users who do not have access to those comments (e.g., people looking at a printer visualization for which comments are not available); 2. Explain why tendency lines are not included from the first data date (2016), but instead all lines are plotted from the 2017 data point 3. Vertical and horizontal lines could make the graph interpretations easier; 4. Add x-axes on the graphs "CO2 emissions from Energy" and "CO2 emission % from Energy". 
      ```

- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 30/04/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
