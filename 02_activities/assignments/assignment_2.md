# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
    ```
# Data Visualization Assignment 2: Good and Bad Examples
##  Good Data Visualization (Right Chart - Clean Chart)   
![Good & Bad Visualization - Inventory Bar Chart](/02_activities/assignments/good-chart-2.png)
     
**Visualization:** "Total Items Sold" - Clean Bar Chart
Shows sales data for office supplies (Desk, Binder, Pen Set, Pencil, Pen)

### Why This is Goods 

**Effective Design Elements:**
- **Simple and clear**: Uses a basic bar chart that's easy to read and understand immediately
- **Proper sorting**: Items are arranged from highest to lowest sales, making comparisons effortless
- **Clean layout**: Minimal visual clutter with no unnecessary decorations
- **Direct labeling**: Each bar shows the exact value on top, eliminating the need to estimate from the y-axis
- **Appropriate use of color**: Single color (purple/blue) keeps focus on the data rather than distracting with multiple colors
- **Clear axis labels**: Y-axis labeled as "EURO" and items clearly labeled on x-axis

**Communication Strengths:**
- **Instant insights**: You can immediately see that Desk has the highest sales (13850) and Pen has the lowest (1560.57)
- **Easy comparisons**: Bar heights make it simple to compare values between categories
- **Professional appearance**: Clean and business-appropriate without being boring
- **Follows best practices**: Aligns with Edward Tufte's principles of maximizing data-ink ratio
- **Accessible**: Simple design works for all audiences, including those with limited data literacy

**Data Integrity:**
- Y-axis starts at zero, providing accurate visual representation
- Bar heights are proportional to actual values
- No distortion or manipulation of the data
- Straightforward presentation builds trust with the audience

This visualization successfully communicates the sales data in the most efficient way possible, allowing viewers to extract insights quickly and make informed business decisions.


##  Bad Data Visualization (Left Chart - Bad Chart)   
![Good & Bad Visualization - Inventory Bar Chart](/02_activities/assignments/good-chart-2.png)
**Visualization:** "Total Items Sold" - Cluttered Combination Chart  
*Same data but presented with multiple unnecessary elements*

### Why This is Bad (≈400 words)

**Major Design Flaws:**

**1. Too Many Visual Elements:**
- **Unnecessary line graph**: The blue trend line adds no meaningful information
- **Error bars/whiskers**: The black lines above and below bars create confusion
- **Dual chart types**: Combining bar and line charts without clear purpose
- **Competing for attention**: Multiple elements make it unclear where to focus

**2. Poor Organization:**
- **Random ordering**: Items aren't sorted by value, making comparisons difficult
- **Illogical sequence**: Jumping from Binder (8766) to Desk (13850) to Pen (1560.57) forces viewers to work harder
- **No clear pattern**: The arrangement doesn't serve any analytical purpose

**3. Visual Clutter:**
- **Excessive gridlines**: Too many horizontal lines create visual noise
- **Redundant legend**: Shows "Total" and "Linear (Total)" when bars are already labeled
- **Data table at bottom**: Repeats information already shown in the chart
- **Multiple labels**: Same information appears in different places unnecessarily

**4. Confusing Elements:**
- **Trend line purpose unclear**: What does the linear trend represent across unrelated categories?
- **Error bars misleading**: No explanation for what these ranges mean
- **Too much to process**: Viewers must decode multiple layers of information
- **Cognitive overload**: Brain works overtime to figure out what's important

**5. Violates Design Principles:**
- **Low data-ink ratio**: Most ink is used for decoration, not data (Tufte's principle violated)
- **Chartjunk present**: Unnecessary elements that don't add value
- **Reduced clarity**: Complex design obscures rather than reveals insights
- **Inefficient communication**: Takes longer to understand the same information

**Impact on Communication:**
- Audience wastes time decoding the visualization
- Risk of misinterpretation increases
- Key insights get buried in complexity
- Reduced credibility due to confusing presentation
- Decision-makers may miss important patterns

### How to Improve:

**Remove Unnecessary Elements:**
- Delete the trend line completely
- Remove error bars/whiskers
- Eliminate the data table at the bottom
- Simplify the legend or remove it entirely

**Reorganize the Data:**
- Sort bars from highest to lowest value (descending order)
- Use consistent spacing between bars
- Keep only the bar chart format

**Simplify Visual Design:**
- Reduce number of gridlines (use only major gridlines)
- Keep direct labels on bars but remove redundant information
- Use single color for all bars
- Remove the "Sum of Total" tag that adds no value

**Better Alternative Approach:**
- Follow the "clean chart" example on the right
- Use simple horizontal or vertical bar chart
- Ensure y-axis starts at zero
- Add a clear, descriptive title
- Include data source if presenting publicly

**Key Lesson:**  
The bad visualization commits the common mistake of thinking "more is better." In data visualization, simplicity and clarity should always win over complexity. The goal is to communicate information efficiently, not to show off all the features available in visualization software.

---

## Summary

The comparison between these two charts clearly demonstrates that effective data visualization is about **clarity over complexity**. The clean chart on the right allows viewers to extract insights in seconds, while the cluttered chart on the left creates unnecessary cognitive work. Good data visualization respects the viewer's time and intelligence by presenting information in the most straightforward way possible.


## References:

- Data Visualization Principles With Good & Bad Examples https://ajelix.com/data/data-visualization-principles/
- Bad Data Visualization: 9 Examples to Learn From https://www.luzmo.com/blog/bad-data-visualization

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
