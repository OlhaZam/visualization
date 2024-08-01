# Data Visualization

## Assignment 3: Data Visualization Ethics

### Requirements:
- Let’s return to the data visualizations we evaluated for Assignment 2.  
- For each visualization: 
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) whether or not you think this data visualization is accessible, reproducible, and equitable. 
        ```
        
        Visualization 1 (Good)
        https://public.tableau.com/app/profile/ellen4268/viz/heart_17176865031980/2

        Accessibility:

        - Color

        Contrast Ratio Test(https://accessibleweb.com/color-contrast-checker/): 
        Text (#B99595) on Background (#FCF2F3 & #F7E7E9) - 2.45:1 - 2.25:1. Test Result: Fail. 
        Text with this contrast ratio would not be considered accessible according to WCAG standards. This lower contrast may make it difficult for some users to read the text, particularly those with visual impairments. To improve accessibility, it's important to increase the contrast ratio to meet or exceed the WCAG guidelines.

        Visual Elements on Background (#FCF2F3):
        Yellow (#EADF42) - Contrast Ratio: 1.16:1, Test result: Fail.
        Red (#D82E22) - Contrast Ratio: 4.05:1, Test result: Pass.
        Green (#66B13D) - Contrast Ratio: 2.22:1, Test result: Fail.
        Purple (#423BC0) - Contrast Ratio: 6.71:1, Test result: Pass.

        The yellow and green  elements fail the accessibility test due to insufficient contrast ratios. These colors are not suitable for text or visual elements if accessibility is a priority. The red and purple elements pass the accessibility test, and these colors provide sufficient contrast and are accessible for most users.


        - Text

        Typeface Family: Sans-Serif, accessible.
        Font Size and Spacing: 12 px for labels and chart description. While 12 px is generally readable, it’s important to note that some users, particularly those with visual impairments, might find this size too small. Thus, ensuring proper contrast and providing options to increase text size can enhance accessibility.


        - Image Description

        Alt text is missing. 


        Reproducibility:

        The provided data visualization includes the data source but lacks details about the raw data, methods, and tools used in its creation. As a result, this data visualization is not reproducible.


        Equitability:

        The chart demonstrates strong equitability by effectively combining aesthetic appeal with clarity and perceptibility. Its harmonious color scheme and intuitive heart-shaped pie chart design ensure visual engagement while remaining inclusive. The clear labels and well-defined axes facilitate accurate data interpretation for all viewers, making the information easy to understand without additional context. 



        Visualization 2 (Bad)
        https://public.tableau.com/app/profile/rush1056/viz/Electricitygenerationpercapita2022/ElectricityGenerationpercapita2022

        Accessibility:

        - Color

        Contrast Ratio Test(https://accessibleweb.com/color-contrast-checker/): 
        Text (#000000) on Background (#FCFCFC) - 20.47:1. Test Result: Pass. 
        An exceptionally high level of contrast between text and background.

        Visual Elements on Background (#FCFCFC):
        Grey (#898989) - Contrast Ratio: 3.41:1, Test result: Pass/Fail.
        Light-grey (#D8D8D8) - Contrast Ratio: 1.39:1, Test results: Fail.
        Orange (#E4754E) - Contrast Ratio: 2.94:1, Test results: Fail.

        A contrast ratios for visual elements indicates insufficient contrast, potentially making these elements difficult to distinguish, especially for users with visual impairments.


        - Text

        Typeface Family: Serif and Sans-Serif. On screens, serif fonts can be less readable if the rendering is poor or if the font size is small.

        Font Size and Spacing: 12 px. While 12 px is generally readable, it’s important to note that some users, particularly those with visual impairments, might find this size too small. Thus, ensuring proper contrast and providing options to increase text size can enhance accessibility.


        - Image Description

        Alt text is missing. 


        Reproducibility:

        The provided data visualization includes the data source but lacks details about the raw data, methods, and tools used in its creation. As a result, this data visualization is not reproducible.


        Equitability:

        The data visualization excels in aesthetic design, with a clean and engaging appearance that attracts viewers. However, it falls short in equitability due to significant issues with substantive and perceptual elements. The plot lacks essential labels and units, making it difficult for viewers to interpret and understand the data.


        ```
    - How could this data visualization have been improved (in terms of accessibility, reproducibility, equity)?  
        ```
        Visualization 1 Suggestions for Improvements:
        
        1. Accessible colors. Ensure that any color choices for text and important visual elements meet the WCAG minimum contrast ratios: At least 4.5:1 for normal text and 3:1 for large text. Increase the contrast by choosing a darker shade of text color and specific visual ellements (yellow and green) or switching to a different color that has a higher contrast ratio against the background.

        2. Text size. For critical information like labels and chart description, consider using a slightly larger font size (e.g., 16 px and more) to enhance visibility.

        3. Alt text. Providing alternative text (alt text) for images, including charts, is crucial for web accessibility. Alt text helps users who rely on screen readers understand the content and purpose of images. 

        4. Reproducibility. Providing access to the raw dataset, documenting data processing methods, sharing the analysis code and tools used, and specifying the computing environment. 


        Visualization 2 Suggestions for Improvements:
        
        1. Accessible colors. To improve accessibility and usability some of the graphic elements, increase the contrast ratio to at least 4.5:1 to ensure they are easily identifiable and inclusive for all users.

        2. Text size. For critical information like labels and chart description, consider using a slightly larger font size (e.g., 16 px and more) to enhance visibility.

        3. Alt text. Providing alternative text (alt text) for images, including charts, is crucial for web accessibility. Alt text helps users who rely on screen readers understand the content and purpose of images. 

        4. Equitability. To improve equitability, it is crucial to add comprehensive labels, a detailed legend, and clear explanations of what each line or section represents. This will ensure that all users, regardless of their background or level of expertise, can accurately interpret and engage with the data.



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
