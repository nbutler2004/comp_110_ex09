---
# Do not edit the text between these lines!
layout: default
---

# Continuous Improvement: Finding the Productive Struggle in Comp110

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->

## Project Overview
Courses, like any product, can be improved through intentional iteration. In this project, we analyzed anonymized survey data from Comp110 students to identify how prior programming experience impacts their perceived course difficulty and overall understanding. Our goal was to determine if the course creates equal value for absolute beginners as well as experienced students.

## Analysis
The primary question we explored was: "Does varying ranges of prior experience create a "value gap" where beginners feel overwhelmed while experienced students feel under-challenged?"

## Visualization 1: Understanding vs Prior Experience
<img src="static/imgs/figure1.png" alt="Figure 1: A boxplot comparing student understanding grouped by their self-reported prior experience." width="500"/>
Figure 1: A boxplot comparing student understanding grouped by their self-reported prior experience.

The data reveals a significant floor difference. Students with "None to less than one month" of experience show a much wider variance in understanding, with several outliers feeling "Lost" (ratings 1-2). Conversely, students with 1-2 years of experience have a much tighter distribution near the top of the scale (ratings 6-7). This confirms that beginners face a steeper learning curve that may require more targeted instructional "scaffolding" early in the semester.

## Visualization 2: The Distribution of Course Difficulty
<img src="static/imgs/figure2.png" alt="Countplot of difficulty ratings" width="500"/>
Figure 2: A countplot showing the frequency of each difficulty rating from Very Easy to Very Difficult.

The distribution of difficulty is bell-curved, but shifted right, with the most common responses being 5 and 6. This suggests that Comp110 successfully avoids being "too easy" for the majority of the population. However, because the peak is at 6, the course is hovering on the edge of the "Productive Struggle" threshold. If the difficulty pushes further to 7, we risk a significant drop in student retention and sentiment.

## Visualization 3: Office Hour Impact on Understanding
<img src="static/imgs/figure3.png" alt="Pointplot of OH visits vs understanding by experience" width="500"/>
Figure 3: A pointplot illustrating the relationship between the number of Office Hour visits and student understanding, categorized by experience level.

This visualization provides the most actionable insight. For beginners, there is a positive correlation between the frequency of Office Hour visits and their reported understanding. For experienced students, understanding remains high regardless of OH visits. This indicates that Office Hours are currently the primary value-creator for beginners, acting as the essential bridge that helps them catch up to their experienced peers.

# Final Conclusions and Recommendations
## Summary of Findings:
Our analysis indicates that while Comp110 is challenging for everyone, the value is delivered differently across groups. Beginners rely heavilty on 1:1 support to maintain understanding, while experienced students maintain high understanding but may find the "intellectual interest" plateauing if the difficulty doesn't scale with their skills. 

## Recommendation: Dynamic Scaffolding
Dynamic Scaffolding involes:
1. Beginner-Specific OH Queues: Prioritizing students with "None" experience to ensure they reach the "understanding" threshold faster.

2. Optional Extra-Challenging Challenge Questions: Providing optional, high-depth exercises for students with 2+ years of experience to ensure the course remains valuable to them.

## Potential Costs and Trade-offs
The primary cost is instructional bandwidth. Managing two different levels of support requires more TAs and more complex assignment design. There is also a risk that beginners might feel discouraged if they see "Challenge" content they aren't ready for, so it is important to be labeled as optional. Maybe to incentivize them to be completed, add in a small extra credit as a reward.

## Future Work
Future iterations of this class should collect data on time-to-completion for assignments. Knowing if a beginner spends 10 hours on a task that takes an experienced student 1 hour would more accurately depict the "Value" from the course by adjusting assignment weights.