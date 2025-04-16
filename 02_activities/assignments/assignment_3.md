# Data Visualization

## Assignment 3: Data Visualization Ethics

### Requirements:
- Let’s return to the data visualizations we evaluated for Assignment 2.  
- For each visualization: 
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) whether or not you think this data visualization is accessible, reproducible, and equitable. 
        ```
        Your answer...
        Bad: https://datavizproject.com/data-type/convex-treemap/
        - Accessibility: to be accessible, convex treemap will need to be colourblind-friendly palettes, clear labels and adequate contrasts. Colours used in this convex treemap is accessible
        - Reproducible: convex treemap can be reproducible if the visualization process which includes algorithms and data is well documented and accessible. Without it, it will be hard to reproduce
        -Equitable: convex treemap can potentially be equitable if they are designed to fairly represent hierarchical data and do not introduce bias or distortion

        Good: Good: https://datavizproject.com/data-type/stacked-bar-chart/
        - Accessibility: stacked bar chart show different segments contributing to the total. Colourblind-friendly palettes to help distinguish different segments is important. Colours used in this stacked bar chart is accessible, however, the distinction between segments are blurry. Label needs to be clearly outlined but this stacked bar chart does not have any labels.
        Reproducible: this chart is reproducible as stacked bar charts require simple algorithm typically and many tools support this visualization.
        Equitable: stacked bar charts are equitable as this highlights trends that might not be visible with other chart types. Each segment is proportionally displayed
        



        ```
    - How could this data visualization have been improved (in terms of accessibility, reproducibility, equity)?  
        ```
        Your answer...
        Bad:
        - Using colourblind-friendly palettes with contrast and legible texts/background.
        - Adding interactive elements to view information
        - Keyboard navigation/screen reader compatibility for people using assistive technology
        - Detail documentation of data process to make the treemap reproducible with open source code
        - Balanced representation to not distort or obscure important data and avoid misleading visuals

        Good:
        - Visual distinction between different segments and addition of labels
        - Interactive features to zoom/move around the visual
        - Even though stacked bar charts are reproducible, it is a good idea to document data structures to assist with reproducibility
        - Avoid overloading information and mindful of how much information is presented to not clutter visualization
        

        ```

- Word count should not exceed (as a maximum) 300 words for each visualization. 

### Why am I doing this assignment?:
- This ongoing assignment ensures active participation in the course, and assesses learning outcomes 2 and 3:  
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
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * This markdown file (assignment_3.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
