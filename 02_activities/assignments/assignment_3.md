# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
I choose the Career college key performance indicators data from Ontario's open data catalogue.
https://data.ontario.ca/dataset/private-career-colleges-pcc-key-performance-indicators/resource/707adb0b-745f-4e47-bc56-d97941ed25a4

- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 

- Visualization made in Excel:

    > What software did you use to create your data visualization?
I used Excel and a pivot table.

    > Who is your intended audience? 
The intended audience of this visualization mainly is prospective students (high schoolers for example) wishing to choose a field of study. It could also be of interest to policy makers or institutions.

    > What information or message are you trying to convey with your visualization? 
My visualization aims to clearly identify which program type has the highest graduate rate.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
I considered the type of plot according to the number of program types so that the plot is not too crowded with too many bars. Column chart also allow straightforward comparisons between categories.
I considered the color used (something bold but a single color, do keep the attention on the column comparison) and the font of the text to be lisible.
I increased the size of the chart so that each program type could be readable.
I also considered the sorting of the program type, in a descending order according to the graduation rate, to make programs easy to compare.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
I would say that making a graph in Excel is not reproducible. I used a pivot table to quickly aggregate the data and get the values to be plotted, which can be reproduced using instructions, but the chart itself and the choice of design would not be easily reproduced. This is an issue when trying to dissiminate information, but is also a "loss of knowledge" for the company/agencies who may want to reproduce a similar plot in the future (with more recent data for example).

    > How did you ensure that your data visualization is accessible?  
To ensure accessibility, I ensured there is not too much text in the visualization, and I used a high contrast between the bars and the background. I also used data reported as % which are easy to understand for non-technical audience.

    > Who are the individuals and communities who might be impacted by your visualization?  
The future student might may decision based on these data to choose their study program, knowing what are their chances to graduate. It could also impact the registration rate in colleges offering programs with high graduation rates (Construction, Industrial Trade) and on the contrary decrease registration in programs with lower rate of graduation (Flight Training).

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
I chose simple data, that future student could understand easily and for which the dataset could be aggregated within a dozen of categories, to make the visualization not too big. I excluded information that were too detailed (college information, program categories...) to focus on something more broad.

    > What ‘underwater labour’ contributed to your final data visualization product?
This visualization was possible due to all the organizer and researchers/contributers to the data collected, cleaned, and made available on the Ontario website, but also to all the students or colleges who participated in the surveys necessary to collect the data. It was also made possible thanks to the researchers and educators who conduct research on survey design or data collection best practice.

- Visualization made in Python:
    > What software did you use to create your data visualization?
I used Python, with Pandas, matplotlib and seaborn.

    > Who is your intended audience? 
The intended audience was institutions and policymakers interested in understanding how graduation and employment outcomes relate across program types. It could also be of interest to prospective students though less straight to the point.

    > What information or message are you trying to convey with your visualization? 
My visualization aims to show the relationship between graduation rates and graduate employment rates across program types, and highlight that high graduation rates do not always correspond to high employment.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
I used a scatter plot to emphasize relationships and allow for an easy identification of outliers. I added clear axis labels with percentages, limited visual clutter, and used distinct colors to differentiate program types while keeping the overall design simple.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
This visualization is reproducible as it is generated entirely through code in Python, from data loading to plotting. Anyone with access to the dataset and script can recreate or update the figure, which improves transparency and reusability.

    > How did you ensure that your data visualization is accessible?  
I used a simple layout, high contrast between points and background, and adapted the axis scales to make the points more visible and distinguishable. Since this visualization relies on colors to identify program type, I used a color-blind friendly palette and made sure to have big enough font in the legend.

    > Who are the individuals and communities who might be impacted by your visualization?  
College institutions and policymakers may use it to reflect on program effectiveness and employment alignment. This data could be used to "promote" or encourage students to follow programs with high employment rate. Prospective students may also use this to choose their program.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
I chose simple data, that future student could understand easily and for which the dataset could be aggregated within a dozen of categories, to make the visualization not too big. I excluded information that were too detailed (college information, program categories...) to focus on something more broad.

    > What ‘underwater labour’ contributed to your final data visualization product?
This visualization was possible due to all the organizer and researchers/contributers to the data collected, cleaned, and made available on the Ontario website, but also to all the students or colleges who participated in the surveys necessary to collect the data. It was also made possible thanks to the researchers and educators who conduct research on survey design or data collection best practice.

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 11/02/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
