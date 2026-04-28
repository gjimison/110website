---
# Do not edit the text between these lines!
layout: default
---

# Welcome to my COMP110 Project Website!

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="110Website/static/imgs/logo.png" alt="Image of Comp110 rainbow logo. "  width="500"/>

## About the Project

In this project, we analyzed the COMP 110 class survey to determine if lecture videos should be added to the course. The survey asks multiple questions about students' preferences for recording/streaming the lectures, which can be related to student outcomes and comfort with the course material, to determine if there is a relation between student success in the course and preferences for class videos. These preferences can also be related to students' year, major, and whether they take notes or not. The course should implement lesson videos as they are a useful study tool for students in the class.

In our analysis, we created a series of bar charts to visualize the extent to which students believe lecture videos are useful and should be added, as well as a graph displaying attitudes on live-streaming lectures. These bar charts were created using Likert-scale data from the survey. Additionally, we created a line plot relating how well students were doing in the class based on their self-reported understanding of course material and difficulty with the course. Finally, we compared how useful students perceived video lectures to be with other study tools in a data table using the mean value of Likert responses.

## Analysis & Results

For the first part of the analysis, I will gauge students' general favorability of course videos/live-streams by creating catplots of their responses to the three seven-point Likert-scale questions regarding these topics that they were asked in the survey. These questions ask if lesson videos are effective in helping students learn the topics of the course, if optional pre-lecture videos that prepare students for the content of each lecture would be helpful for their learning, and if in-person lectures should be live-streamed so that not everyone is required to attend in person.

<img width="531" height="529" alt="image" src="https://github.com/user-attachments/assets/99808d65-763f-479c-91a0-7a6d2946fb63" />

<img width="528" height="529" alt="image" src="https://github.com/user-attachments/assets/eaa03cd2-8afe-4e04-93c2-1cc7270c8770" />

<img width="528" height="529" alt="image" src="https://github.com/user-attachments/assets/a511f199-e2b3-4a1e-a105-1e6d5a395021" />

This data shows that students broadly view the addition of lesson videos and live-streamed lectures as a benefit to their learning, and find lesson videos to be an effective study strategy.

We can also examine the mean value of the Likert response for each question relating to helpful learning strategies to determine how important video lectures are as a study tool, as compared to other methods of studying (e.g., quiz preparation, programming).

| Study Tool            | Mean Likert Score |
|---------------------|-------------------:|
| Videos              | 5.19            |
| Post-Session Problems | 5.02         |
| Programming Practice | 5.42           |
| Quiz Prep           | 5.43            |
| Office Hours        | 4.97            |
| Tutoring            | 4.99            |

Based on the data in the table, students find lesson videos to be the third most effective study tool of the six introduced in the survey.

To further examine trends in this data, we will look to see if there is a relation between students' preference for videos and their relative comfort with the class, as determined by responses to whether they find the material difficult, and if they typically understand it.

<img width="562" height="463" alt="image" src="https://github.com/user-attachments/assets/e126bf86-6446-4d32-aad6-318d113d41fa" />

This plot shows that students' perceived difficulty of COMP 110 increases, and their understanding of the material decreases with their perceived efficacy of lesson videos. However, there is a large margin of error in the data

## Conclusions

Our proposed idea was that COMP 110 should implement lesson videos, as they are a useful study tool for students in the class. To test this hypothesis, we analyzed the student survey to assess student attitudes about lecture videos and the relationship between these attitudes and student performance in the course. The data shows that students broadly support the addition of lecture videos, find them to be an effective study tool, and additionally believe that classes should be livestreamed. The vast majority of Likert responses to these survey topics agreed that they should be implemented into the class, with few students disagreeing with this premise. Moreover, surveyed students believe that lecture videos are the third most effective study tool, behind only studying for quizzes and performing programming exercises. While this data supports the addition of lecture videos, the relational study showed that perceived efficacy of lecture videos as a study tool is correlated with perceived difficulty of the class and inversely correlated with understanding of course material, although the line plot did have a high standard error. These correlations could indicate one of two things: students that perfer lecture videos perform worse since they are not actually an effective study tool, or that the lack of lecture videos hampers these students' ability to study as effectively as they could.

Given the analysis of this data, we recommend that lecture videos be added to COMP 110, but with caution. Adopting this idea would introduce a widely regarded study tool, potentially improving student outcomes. However, there are potential downsides to using lecture videos and live-streaming classes, in that they may harm students' understanding by reducing lecture attendance and providing a redundant study tool that is less effective than others currently implemented in class. As such, these students may negatively impact stakeholders in this scenario. Further analysis could clarify the efficacy of lecture videos as a study strategy by comparing the effects of student outcomes between them and other study tools, such as office hours and quiz studying. Additionally, the amount of data on outcomes of students who don't consider it to be an effective tool is limited. Finally, this data can be correlated with final grades to give a more objective measure of student outcomes, rather than just how well the percieve themselves to be doing in the class.
