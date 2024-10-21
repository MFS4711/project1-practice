# Mindful Connect

## Overview

### Purpose
A brief description of the project's purpose, what it aims to achieve, and the value it provides to the users.  
**Guidance:** Begin filling out this section during Phase 1: Ideation & Initial Setup. Clearly articulate the main goal of your project, what it aims to achieve, and how it will provide value to your target audience.

Mindful Connect is a fictional organisation which aims to raise awareness about mental health and foster a supportive community for individuals seeking help or wanting to learn more about mental wellness.
This is achieved by providing organised webpages dedicated to different aspects of the purpose. 
One webpage will be dedicated to providing a beginner friendly information about mental health which will include common issues and manage stress as requested by the project brief.
Further to this, there will be pages which will encourage users to get involved in daily challenges or take part in guided/group sessions and events.
There will also be the ability for users to get involved as part of the organisation.
This project will provide value to users by not only acting as an educational source but also providing a community to be a part of.

### Target Audience
Identify the target audience for your website and explain why this audience will benefit from the project.  
**Guidance:** Use this section to identify who will benefit from your project and why. This should be informed by your user stories and overall project objectives.

There are two main audiences I am targeting for this project; those who are looking for an introduction to mental health topics and how to manage stress, and those who are looking to connect with like-minded people. I will explain each of these further.

This projects targets people looking for an introduction to mental health as it not only provides information regarding common mental health issues, it also outlines ways in which a person can manage stress.
Further to this, this group of people will be able to find self care challenges and guided activities.

This project also caters towards those looking to join a community of people interested in taking part in activities promoting mental health as the website promotes community and events.

## User Stories

### Must-Have User Stories
- **User Story 1:** Briefly describe the must-have feature.  
  **Acceptance Criteria:** List the criteria that define the successful implementation of this user story.
- **User Story 2:** Briefly describe the must-have feature.  
  **Acceptance Criteria:** List the criteria that define the successful implementation of this user story.

(Include all prioritized must-have features)  
**Guidance:** Draft the user stories during Phase 1: Ideation & Initial Setup and update them as you complete Phase 2: Must User Stories Implementation & Testing. Document each must-have feature here along with its acceptance criteria.

### Should-Have User Stories
- **User Story 1:** Briefly describe the should-have feature.  
  **Acceptance Criteria:** List the criteria that define the successful implementation of this user story.
- **User Story 2:** Briefly describe the should-have feature.  
  **Acceptance Criteria:** List the criteria that define the successful implementation of this user story.

(Include all prioritized should-have features)  
**Guidance:** Document the secondary features that you aim to implement in Phase 3: Should User Stories Implementation & Any Advanced Features. Include clear acceptance criteria for each.

### Could-Have User Stories
- **User Story 1:** Briefly describe the could-have feature.  
  **Acceptance Criteria:** List the criteria that define the successful implementation of this user story.
- **User Story 2:** Briefly describe the could-have feature.  
  **Acceptance Criteria:** List the criteria that define the successful implementation of this user story.

(Include any could-have features considered for future enhancements)  
**Guidance:** Document any optional features that are nice to have but not essential.

## Design Decisions

### Wireframes
Include wireframes for key sections of your website.  
Briefly describe the design choices, including layout, colour schemes, and fonts.  
**Guidance:** Start this section during Phase 1: Ideation & Initial Setup and update it throughout Phase 2 and Phase 3. Include digital wireframes created in Phase 1. Document the reasoning behind your layout choices, colour schemes, and font selections.

### Accessibility Considerations
Discuss how accessibility guidelines were adhered to, including colour contrast and alt text for images.  
**Guidance:** Outline how you've incorporated accessibility into your design, ensuring that your project adheres to guidelines such as WCAG.

## AI Tools Usage

### DALL-E
Describe how DALL-E was used for image generation, including examples of successes and challenges.  
**Guidance:** Specifically mention how you used DALL-E for image generation and the impact this had on your design process.

## Features Implementation

### Core Features (Must-Haves)
- **Feature 1:** Description of the implemented feature.
- **Feature 2:** Description of the implemented feature.

(Include all must-have features)  
**Guidance:** Use this section as you complete Phase 2: Must User Stories Implementation & Testing. Document all the must-have features you implemented, explaining how they align with the user stories and acceptance criteria.

### Advanced Features (Should-Haves)
- **Feature 1:** Description of the implemented feature.
- **Feature 2:** Description of the implemented feature.

(Include all should-have features)  
**Guidance:** Include any advanced features you implemented during Phase 3: Should User Stories Implementation & Any Advanced Features. Explain how these features enhance user experience and their alignment with the acceptance criteria.

### Optional Features (Could-Haves)
- **Feature 1:** Description of the implemented feature (if any).
- **Feature 2:** Description of the implemented feature (if any).

(Include any could-have features that were implemented or considered)  
**Guidance:** If any could-have features were implemented, describe them here. This is an opportunity to showcase extra work done beyond the initial scope. But remember - keep it simple! Focus on the Must stories first. Could user story features are commonly earmarked for future project iterations.

## AI Tools Usage

### GitHub Copilot
Describe how GitHub Copilot assisted in coding, including any challenges or adjustments needed.  
**Guidance:** Reflect on how GitHub Copilot assisted in coding, particularly any challenges or adjustments that were needed to align with project goals.

Github Copilot is a code completion and automatic programming tool which assists users by autocompleting code.
This has been particularly beneficial when styling with Bootstrap as there are many divs and it can be difficult to identify where these close.
The editor, with beautify/prettier added on, allows these opening and closing divs to be lined up more easily.
There were however some challenges experienced when copying repeated code to another area, i.e. for the card's. 
This is because a closing div, or closing tag of the first element, would appear on the first line automatically and these could be easily missed.
Therefore, using a validator after writing a block of code was essential to mitigate this and ensure the output appeared as desired.

### ChatGPT

ChatGPT was not used for any coding purpose but was a great aid in creation of this project.
First of all, it was used for brainstorming ideas and producing layout concepts.
Further to this, it was used to generate some of the content appearing on the health information page.
Challenges with this AI software included the need to ask the right questions as it can take the topic in an unintended direction, therefore, it was important to keep on top of this.

## Testing and Validation

### Testing Results
Summarize the results of testing across different devices and screen sizes.  
Mention any issues found and how they were resolved.  
**Guidance:** Summarize the results of your testing across various devices using tools like Chrome DevTools, as outlined in Phase 2. Mention any issues found and how they were resolved.

### Validation
Discuss the validation process for HTML and CSS using W3C and Jigsaw validators.  
Include the results of the validation process.  
**Guidance:** Document your use of W3C and Jigsaw validators to ensure your HTML and CSS meet web standards. Include any errors or warnings encountered and how they were resolved.

#### HTML Validation

HTML validation was achieved using the W3C Validator which ensured the code met web standards. I chose to validate numerous times during the project to ensure any errors or warnings could be resolved early in the process.
I will outline the errors / warnings encountered and how these were resolved in each html page.

##### Validation 1 
- Completed after navbar coding was added 
- No errors or warnings found 
- Project was deployed at this stage as a result of the above

##### Validation 2 
- Completed after footer, hero and purpose section were coded 
- No errors found but there was a warning regarding the 2 sections enclosing the hero and purpose sections respectively.
- Warning was regarding the sections not having a heading element enclosed anywhere
- Resolved by adding a h1 element as a section heading and applying the hidden-heading class which was styled in CSS to not display
- Validation showed no errors or warnings after making this change.

##### Validation 3
- Completed after navcards coding was added 
- No errors or warnings found

##### Validation 4
- Completed after adding all navcards and events info to index.html, and creating health-information.html - also adding common mental health conditions section
- Completed on the health info page
- Some errors were found
- The first error related to the file name of the OCD image as it included spaces
- Resolved by taking the spaces out of the image file and amending the file path in the image code
- The closing div was missing for two of the surrounding divs for the card decks relating to the bootstrap rows class
- Resolved by adding the closing divs
- Validation showed no errors or warnings after making this change.

##### Validation 5
- Completed on index.html immediately after validating the health info page
- No errors shown but 2 warnings were shown relating to the iframe
- The first related to the width on the iframe html being a percentage
- Resolved by removing the width attribute in the html and styling this in CSS instead
- Second warning was relating to the iframe section not having a heading
- Resolved by adding a h1 element as a section heading and applying the hidden-heading class which was styled in CSS to not display
- Validation showed no errors or warnings after making this change.

##### Validation 6
- Completed on health info page after adding the remaining section on the page
- One error was shown relating to the button element with the get help message as it was enclosed in an anchor tag
- Resolved by removing the button code and adding the role=button attribute to the anchor tag
- Validation showed no errors or warnings after making this change.


#### CSS Validation
CSS validation was achieved using the Jigsaw Validator which ensured the code met web standards. I chose to validate numerous times during the project to ensure any errors or warnings could be resolved early in the process.
I will outline the errors / warnings encountered and how these were resolved in each html page.

##### Validation 1 
- completed after navbar coding was added 
- no errors or warnings found 
- project was deployed at this stage as a result of the above

##### Validation 2 
- Completed after footer, hero and purpose section were coded
- No errors or warnings found

##### Validation 3
- Completed after navcards coding was added 
- No errors or warnings found

##### Validation 4
- Completed after adding all navcards and events info to index.html, and creating health-information.html - also adding common mental health conditions section
- No errors or warnings found 


## AI Tools Usage

### GitHub Copilot
Brief reflection on the effectiveness of using AI tools for debugging and validation.  
**Guidance:** Reflect on how GitHub Copilot assisted with debugging and validation, particularly any issues it helped resolve.

## Deployment

### Deployment Process
Briefly describe the deployment process to GitHub Pages or another cloud platform.  
Mention any specific challenges encountered during deployment.  
**Guidance:** Describe the steps you took to deploy your website during Phase 4: Final Testing, Debugging & Deployment, including any challenges encountered.

The project was deployed early in the process to GitHub Pages to ensure any issues encountered could be resolved quickly.
Before deploying the project, I ensured to code a navbar to be able to see if the deployed project correlates with my preview.
The deployment process involved publishing my main branch and root directory which took a few minutes before completing.
The deployed project updated as required after each git push and few, if any, issues were encountered.

## AI Tools Usage

### Reflection
Describe the role AI tools played in the deployment process, including any benefits or challenges.  
**Guidance:** Reflect on how AI tools assisted with the deployment process, particularly how they streamlined any tasks or presented challenges.

## Reflection on Development Process

### Successes
Effective use of AI tools, including GitHub Copilot and DALL-E, and how they contributed to the development process.

### Challenges
Describe any challenges faced when integrating AI-generated content and how they were addressed.

### Final Thoughts
Provide any additional insights gained during the project and thoughts on the overall process.  
**Guidance:** Begin drafting reflections during Phase 1 and update throughout the project. Finalize this section after Phase 4. Highlight successes and challenges, particularly regarding the use of AI tools, and provide overall insights into the project.

## Code Attribution
Properly attribute any external code sources used in the project (excluding GitHub Copilot-generated code).  
**Guidance:** Document any external code sources used throughout the entire project, especially during Phase 2 and Phase 3. Exclude GitHub Copilot-generated code from attribution.

## Future Improvements
Briefly discuss potential future improvements or features that could be added to the project.  
**Guidance:** Reflect on potential enhancements that could be made to the project after Phase 4: Final Testing, Debugging & Deployment. These could be Could user story features you didn’t have time to implement or improvements based on testing feedback.