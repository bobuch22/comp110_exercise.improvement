---
# Do not edit the text between these lines!
layout: default
---

# Analysis Summary
We decided to pursue the idea of adding extra programming exercises to the COMP110 course schedule under the assumption it would provide students with more practice and more examples to draw on, leading to a better understanding of the class as a whole. 
Our analysis process was taking a very large selection of data and then preparing it to be used in graph making. Our steps were to:
1. Pulling survey responses from Professor Hinks' class survey
2. Converting the survey responses into usable data
3. Filtering the data, using a custom function to look for responses with only a specific answer in one column and then reducing the visible columns in our tables to the data that we wanted to look at. 
From there, several plots and graphs were created through Seaborn to represent the data and see if we could draw a conclusion.

# Graphs
<img src="static/imgs/Seaborn Box Plot.png" alt="Box Plot of the number of personal examples a student used versus their percieved understanding of the class. " width="500" height="500"/>

<img src="static/imgs/Seaborn Histogram.png" alt="Histogram of the number of responses for each of the options, rating from 1 to 7 with 1 meaning little/no understanding and 7 meaning the most understanding. " width="500" height="500"/>

<img src="static/imgs/Seaborn Line Plot.png" alt="Line Plot of how effective students believe programming exercises are for understanding course concepts and their percieved understanding of the class. " width="500" height="500" />

# Conclusion
This data may be impacted by those who have higher understanding or attendance doing less additional examples to begin with, and those who have a lower baseline understanding needing more examples to get to the same place. While data shows a positive correlation between how helpful people believe programming practice is to the class and how much the say they understand the class overall, having more examples of code that represents or fulfills specific concepts doesn't seem to have any major effects on overall class understanding. Overall, the data doesn't refute or accept the theory that having more exercises increases student understanding. One part of additional data collecting that could be done would be to run an experiment. Select 2 groups of students, and provide one group with an extra set of coding exercises to complete. Provide the other group with the regular amount of exercsies for the course. Then, have both sets of students complete a timed code writing activity, and compare scores between the two groups. A cost of experimenting with our idea is that students could potentially feel overwhelmed with the additional workload, and those who are not moving on in computer science will not necessarily need these concepts ingrained in their heads. This extreme workload is likely to make students consider not taking the class, or taking a different section with a reduced number of exercises. 
