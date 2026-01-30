# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  

    - Good example:
    https://datavizproject.com/wp-content/uploads/examples/Sk%C3%A6rmbillede-2017-01-25-kl.-18.06.17.png
1) Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://users.eecs.northwestern.edu/~jhullman/vis_rhetoric.pdf
      https://data-feminism.mitpress.mit.edu/pub/5evfe9yd/release/5

In my opinion, this visualization is good as the choice of plot (boxplot) is appropriate to represent distributional data. A good visualization should be aesthetic, accurate, and perceptually effectiveness (class slidedeck 1). I think this visualization is aesthetic as it is clean, uncluttered, without any unnecessary details that would distract the reader. It uses an harmonized color palette, which makes it look coherent and increase the credibility (https://doi.org/10.1080/10696679.2019.1616560). It is accurate as the data is not oversimplified into an average or a simple boxplot, all data points are visible, which makes the variability clarly visible and allows for an accurate comparison between players. It is effective in reporting information as it provides lots of information within a simple effective design (boxplot: median, quartiles + point distribution). The data points show raw data, which helps identify outliers, or potentially skewed data... Finally, the use of different colors for each player makes it clear that we are supposed to compare boxplots between each player.

      ```
      
2) How could this data visualization have been improved?  
      ```
A few details still be improved in this graph concerning important information displayed in the axis and titles which are missing (https://www150.statcan.gc.ca/n1/pub/89-26-0005/892600052022001-eng.htm). For example, the plot is missing the unit of the y scale (number of points scored). There could be a difference in color between the background and the actual graph color (grey and white instead of just all grey), so that we can better see the baseline and the start of the graph above the players’ names. The players (x axis) could have been ordered in a particular way that would make sense to the message being conveyed (ex: sorted based on increasing average of points scored; sorted by team; sorted by player’s age…). Finally, additional relevant information could be added to the plot to make appropriate comparisons, for example a reference line that would display the league average.
      ```

    - Bad example: https://datavizproject.com/wp-content/uploads/examples/Sk%C3%A6rmbillede-2017-07-07-kl.-10.33.11.png
1) Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
In my opinion, this visualization is “bad” as its aesthetic could be improved, it is hard to understand some of the data, making it ineffective. At a first glance, it looks attractive, but the use of a donut chart with a circular symmetry implies that categories could be compared, while the type of data categories displayed is wide and probably acquired in various ways. In addition, the perception of information is poorly effective as reader must rotate their attention around the circle, read lots of text with a small font, which overall makes it hard to extract specific insights. In addition, the accuracy of the data seems compromised, first because the colors are reused within multiple categories, which is confusing (https://www.nature.com/articles/s41467-020-19160-7). For example, yellow is used to display sections about “age 0-14”, “access to internet”, “North America” and “adequate nutrition”, which is misleading as it seems to imply a link between those categories. Finally, using a donut plot reduces data granularity because it treats categories as independent. In reality, factors such as poverty, education, and internet access are likely related, but these relationships are not shown here.
      ```
2) How could this data visualization have been improved?  
      ```
To improve this visualization while retaining a donut chart format, I would increase the font size and improve the color strategy. Specifically, each category could be assigned a distinct color, with related outcomes represented using different shades of that color. For example, nutrition could be shown in shades of blue to represent different nutritional outcomes, while age-related variables could use shades of green. 
Instead of using a single donut chart, multiple ones could have made to put emphasis on one variable and allow for more comparisons to be made. For example, five donut charts, one for each continent, could display continent-specific information, reducing information overload while making better use of the underlying data.
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
* Submission Due Date: `23:59 - 10/26/2025`
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
