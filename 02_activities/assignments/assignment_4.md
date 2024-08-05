# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
Python 
    > What software did you use to create your data visualization?
    Python: https://vscode.dev/github/JessilynnKim/visualization/blob/assignment-4/02_activities/assignments/Assignment_4_Python.ipynb

    > Who is your intended audience? 
    Business Analysts and housing policy makers to understand progress of the housing against target in 2024
    
    > What information or message are you trying to convey with your visualization? 
    To understand and visualize Municipalities with less than 50% of progress % in housing supply between January – April 2024  
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    Substantive: observing current progression trend for 2024 housing target against total built which is 2024 Progression % 
    Perceptual: bar chart that will showcase the Municipalities less than 50% to their 2024 target 
    Aesthetic: using bar chart to depict the data and progression by Municipality 
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    Documenting and adding comments to Python codes to be able to reproduce bar charts to represent dataset
    
    > How did you ensure that your data visualization is accessible?  
    Using colourblind-friendly colour and adding label to the chart to read/undestand the visualization 
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    City planners, policy makers, analysts and housing developers for each Municipality 
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    10- year housing target was excluded as from this dataset, it is unclear when the 10-year target starts and ends
    Total housing progress since 2022 was excluded from this dataset as to focus on the data visualization 
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    Reviewing the datasets from Ontario's Open Data Catalogue to understand raw data before choosing the dataset. Excluding two datasets to hone in on visualization 
    Updating column name for more ease of usage
    Added data column %Remaining 
    only including data less than 50% of progression %

Power BI
    > What software did you use to create your data visualization?
    Power BI
    https://vscode.dev/github/JessilynnKim/visualization/blob/assignment-4/02_activities/assignments/Assignment%204%20-%20PowerBI%20Visualization.png
    **could not make the Power BI visualization public

    > Who is your intended audience? 
    Municipal employees relating to housing policy makers/ city planners 
    
    > What information or message are you trying to convey with your visualization? 
    To outline for each municipal exclude ones without target on their progress to date in 2024 against their 2024 total target 

    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    Substantive: visualization excluded grouped municipal without target. This chart showcases the proportion of target vs. progress 
    Perceptual: two different colours have been leveraged to distinguish between two different segments with labels added 
    Aesthetic: data is showcased in simple manner but this is a bit clutter due to number of municipals part of the data set. 

    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    This data is potentially reproducible as visualization labels such as x, y and title is straightforward in terms of inclusion and exclusion datasets for this visualization. Colour scheme was customized to ensure accessibility but this can be reproduced as well 
    
    > How did you ensure that your data visualization is accessible?  
    Using colourblind-friendly colours and two very distinct colours used for each segment. Zoom Slider was added to the visualization to zoom into various Municipalities. Toronto is one of the outlier data with very high 2024 target which makes it hard to read majority of Municipality data. This feature will help with readability of this visualization. Data label has been added but again, similar to overall visualization, zoom slider will assist with viewing this data. 
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    Municipal officals and planner as well as community members. Housing issues continues and lack of supply or low progression in house vs. target may help each municipla assess the current state to improve for remaining 2024
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    Similar to python, 10-year target was not included part of visualization as it's unclear when 10 year starts and ends. Similarly, 2022 to date progression was excluded as I wanted to showcase current state of housing progress. I wanted to visualize in comparison between current progress and the remaining of the total 2024 target for each municiplal to go. 

    > What ‘underwater labour’ contributed to your final data visualization product?
    Same data cleaning done for this visualization. Updated column names and added remaining % column 


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
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
