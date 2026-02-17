# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      Your answer...

      Good Data Visualization
      Link: https://public.tableau.com/app/profile/jennifer.eneh/viz/PCOSDashboard_17297311153800/pcosdashboard

      I categorized this visualization as good because of its aesthetic and the storytelling in relaying information that is clear and easy to understand (perceptual). However, there is also opportunity for improvements. 

        + There is use of familiar charts, so less time is spent trying to understand the charts (cognitive load).  Multiple elements such as titles, legends, label on the x axis, tooltips are used to provide explanation and context. The main title is clear and informative. Most of the charts are framed as a simple question, with the visualization directly answering it, which strengthens the storytelling aspect. Descriptive paragraphs offer additional information, but they are not necessary to understand the core message. Annotation lines are used as a form of educational piece in one of the charts that present technical information that some users may not be familiar with.

        + Gestalt principle of enclosure is applied. Each topic is covered in its own shadowed box. 

        + It meets three of the four conventions of data visualization (Sociologists Kennedy et al.) that reinforces perceived objectivity and factual basis of visualization: two-dimensional image, clean layout and use of geometric shapes and lines.  


      Poor Data Visualization
      Link: https://public.tableau.com/app/profile/rizzshi/viz/MedicalSupplierAnalysis/Dashboard1

      There are positive elements to this data visualization, but I classified it as poor data visualization because of the amount of work needed to take in the information presented (cognitive load). 

        - The main title of the data visualization is not clear. At first, I would think it is ‘Hi Rishi, Have a Great Day’. This takes away from grasping the messaging of the data visualization.
        
        - I am not sure why some of the icons are used, for example, the sphere, house etc. There is also repeated use of the LaDataViz logo. This adds extra clutter and increase the cognitive load without providing a clear purpose. The gradient also seems to add to the noise without providing a clear purpose. Not sure what the tiny arrows represent in ‘Supply Coverage Depth’ and ‘Top Supplies / Providers’ charts. More visual elements increase cognitive load.

        - The radial / chord sheet does not appear to be a familiar chart, or at least, it does not seem to be the ideal graph to present the ‘Market Leader Share’ data. Firstly, it took time to understand what information was presented, without the paragraph it probably would have been impossible. Not sure if the paragraph needs to be so detailed (cognitive load). There are many lines from a month to years and they are tightly connected. It takes some effort to highlight a desired month to a year. At a zoom out level some lines appear cut off from in between - with so many other lines, it's difficult to connect the dot. All of these extra steps add to working memory, but working memory is limited.

        - The tooltip has to be used to identify the x and y axis data for the area and the sparkline charts. It's difficult to have an overall view of how each month is separated. This require using the working memory.

        - I was unable to find the source of the data that was presented. One of the four conventions of data visualization that reinforces the perceived objectivity and factual basis of a visualization is inclusion of data source at the bottom of the image.

        - There doesn’t seem to be enough contrast between the light gray texts and white background (accessibility concern). 

        - None of the x and y axes are labelled. Highly reliant on the tooltip to provide additional information. I am not sure how the experience would be for users who only use the keyboard for navigation or how well tableau supports navigating tooltips with keyboard (possible web accessibility concern).


      ```
    - How could this data visualization have been improved?  
      ```
      Your answer...

      How to improve the Good Data Visualization?
      Link: https://public.tableau.com/app/profile/jennifer.eneh/viz/PCOSDashboard_17297311153800/pcosdashboard

        + I was unable to find the source of the data that was presented. Adding the data source would have greatly helped with trusting the information that was presented.

        + For web accessibility, there is not enough between some of the colors that are used together. For example, the following color combinations failed the web aim color contrast checker test (https://webaim.org/resources/contrastchecker/). Persons with visual impairment (low vision) may experience difficulty scanning the graph.

            * the light gray (#ecf1ef) and the white background (#fff)
            * the light blue (#89d9e5) and the light gray (#ecf1ef) 
            * the light blue (#89d9e5) and the light lilac (#ccb5ff)
    
        Increasing the contrast of the colours or creative use of outlines and shapes could make the charts more accessible. 


        How to improve the Poor Data Visualization?
        Link: https://public.tableau.com/app/profile/rizzshi/viz/MedicalSupplierAnalysis/Dashboard1

        + I was unable to find the source of the data that was presented. Adding the data source would have greatly helped with trusting the information that was presented.

        + Have a clear main title. This will help us to understand the message of the visualization (perceptual). 
        
        + Add clear title to the charts to add to the storytelling. 
        
        + Add labels on the x and y axis where needed.

        + Remove visual elements that do not serve a clear purpose. This will help reduce the cognitive load.

        + For web accessibility, increase contrast where needed.   

        + For participation chord, explore using a more common chart type, or present the information in more than one simple charts, if needed.

        + For the charts at the top, the summary is for comparison between two months, but the sparkline charts show yearly info. If the purpose is only to compare two months, perhaps we could make the sparkline graphs simpler by only presenting the two months data or remove them entirely.

        + Make the user less reliant on the tooltip which adds to the working memory. They are great for additional information, but the user should still be able to grasp the core message without relying on the tooltips.


      
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
* Submission Due Date: `23:59 - 02/16/2026`
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
