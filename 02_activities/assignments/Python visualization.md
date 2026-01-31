# Data Visualization

## Assignment 3: Visualization made in Python

I choose the Career college key performance indicators data from Ontario's open data catalogue.
https://data.ontario.ca/dataset/private-career-colleges-pcc-key-performance-indicators/resource/707adb0b-745f-4e47-bc56-d97941ed25a4


- For each visualization, describe and justify: 
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