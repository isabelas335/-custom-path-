---
# Do not edit the text between these lines!
layout: default
---

# Choosing an idea to analyze

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->

Idea to analyze with available data: This course should have two grading paths: one that includes class participation and one that doesn’t, and whichever score is higher is kept (other classes like ECON410 do this). This would be beneficial to students because it would reward students who attend lectures every day, but also not penalize those who might not feel they need to come to class every day. 

This idea is more valuable than the others brainstormed because: It would be a very easy idea to implement, as it would just require slighlty modifying the grading rubric (adding an optional participation score), and collecting participation in classes via a poll or other method. Additionally, this idea will be easy to analyze with our given dataset, as our dataset contains information on student's different levels in the class and whether they find lectures helpful. 


# Visual Analysis

## Graph 1 

<img src="{{ site.baseurl }}/static/COMP110_EX09_Graph1.png" alt="Count Plot" width="500"/>

Explanation: This visualiztion shows us how strongly students want lectures to be recorded. This is an example of a count plot visualization, which is commonly used to show the distribution of quantity of a (typically discrete) variable. The variable we are looking at is add_livestream, which tracks how strongly students want in-person lectures to be recorded so that not everyone has to attend — 1 being strongly disagree, and 7 being strongly agreeing. This variable also can be interpreted as how much flexibility with lectures students desire, either for rewatching them again, or becausse they don't want to attend lectures everyday and only watch the livestream.


Overall, we can see a clear left-tailed distribution, showing that the majority of students prefer the class to be live-streamed, which we could intepret as the majority of the class wanting greater flexibility with attending lectures. We see that add_livestream count starts at about 10, and goes up significantly almost each time. This shows that overall, students would want their lectures to be live-streamed.

## Graph 2

<img src="{{ site.baseurl }}/static/COMP110_EX09_Graph2.png" alt="Box Plot" width="500"/>

Explanation: We created a Box Plot plot to test how students' opinions on live-streaming lectures change in relation to their grade level at UNC. For seniority_level, 1 is Freshman, 2 is Sophomore, 3 is Junior, and 4 is Senior. Add_livestream is the same variable as in the last graph, tracking how much students want class to be live_streamed, 1 being the least and 7 being the most. 

Overall, we see that as the seniority_level increases, the median response rises from freshman 5 to sophomore 6 and then remains at 6 for juniors and seniors. This suggests that the upper class might want live streams to be recorded more, meaning they want more flexibility in attending lectures. 

Also, we can see that Seniors have a stronger preference for live-streaming than the younger grade levels as they have the narrowest distribution that is at the highest levels of add_livestream. The lower quartile range is 5, while all of the others start at 4. This means that 75% of Seniors gave a score of 5 or higher. Also, the senior group is the only one that has an outlier, representing a specific senior who strongly disagrees with live-streaming, which is very different from the rest of his class. This shows that almost all seniors did not strongly agree with not implementing live streaming. This could suggest that as students progress throughout their college career, they gain a stronger understanding of whether they need to attend lecture or not and desire more flexibility in the matter. 

## Graph 3 

<img src="{{ site.baseurl }}/static/COMP110_EX09_Graph3.png" alt="Relational Plot" width="500"/>

Explanation: We created a relational plot to visualize the relationship between how well students feel like they understand the material and how difficult they find the course. Then by grouping students on these two criteria, we see what each group’s median add_livestream response is. In the graph this is represented by the hue, with the lightest color representing the least desire for the class to have a livestream, and the darkest color responding the most desire for a live stream to be added to the class. 

Overall, there is no clear correlation between difficulty and understanding, it's very wide spread. However, there are still some specific clusters we can observe. Specifically, we observe that where the darkest dots tend to be (the highest desire for a livestream) are in the bottom left corner and the top right corner of the graph. The bottom left corner represents students who find the class very difficult and have little understanding. Perhaps they want a livestream added because they feel they need the lectures the most. A livestream would allow them to review the lecture again after watching it in person, and also not having to skip lecture if they are feeling too sick or tired to attend in person. This suggests that this grouping of students, who struggle the most in the class, actually use the lectures. Because of this, they would highly benefit from if there was a participation grade because it would act as extra points for them since they are seeming to actually attend lecture. On the opposite corner, in the top right, are the students who have the highest understanding and don’t find the class difficulty. Perhaps they also want a live stream because they already are not attending in person lectures, but would find the live streams useful for reviewing for quizzes and assignments. 

# Conclusion

Summary of Findings and Recommendations

Our analysis suggests that while this class already offers student’s flexibility by not taking a participation grade, it would be possible to help students that are struggling in the class by creating a two-path grading schema: one that counts participation and one that doesn’t. Under this model, student’s participation in lectures would be taken via polls (or other methods), and their final grade would be calculated including and not including this participation weight. Only the highest grade would be kept. In this way, students who attend lectures everyday would be rewarded for it, while students who don’t attend lectures wouldn’t be penalized for it. 

The data from Graph 1 shows a massive demand for livestreams (flexibility), as the count plot is heavily left-tailed. Graph 2 also suggests as students progress throughout their college career, they gain a stronger understanding of whether they need to attend lecture or not and desire more flexibility in the matter. Additionally we calculated earlier that upperclassmen (juniors and seniors) make up more than 60% of the class. Graph 3 revealed that students who find the class most difficult and have the lowest understanding are also the ones most strongly desiring these resources. Because these students are struggling with the coursework, they are likely attending or watching lectures to catch up. This means they are already doing all of the work of participation without it helping their grade at all. Implementing a participation path would provide a grade boost for these students that likely are the ones that need it the most, essentially rewarding the effort they are putting in my engaging with lectures in order to try to improve their understanding. Additionally, another group who had a very high desire for adding a live stream were those who had the highest understanding and found the class to be the least difficult. We hypothesize that they already are not attending lectures, but would find live streams helpful for reviewing material before quizzes and the final. These students would be hurt if participation was always calculated in the grade, and they likely wouldn’t gain much from attending lectures since they already understand the course material.

Overall, our findings demonstrate there is already a clear desire for greater flexibility in lectures, and that this class has a wide variety of students who have different levels of understanding of the course content. Because of these various clusters of students, this class would greatly benefit from a two-path participation grading schema. 

Potential Costs, Downsides, and Trade-offs

One trade off to this idea is that students who aren’t attending lectures everyday already may feel they have to attend class to get the extra credit. This might cause conflicts in their other commitments like class or work. 

Another trade off is that participation being added to a student's grade might cause grade inflation. If a significant amount of the students uses participation to make up for their low quiz scores, the final grades may be inflated. However, this could be adjusted in the future by either making the quizzes more difficult or changing the letter grade criteria. 

Extensions and Future Work

One extension for the future could be to investigate the relationship between adding a participation grade and the students' understanding in the scatterplot. This should investigate if people who attend class because of the participation weight actually leads to increased understanding over time. This could help determine if maybe there are just students who like attending lectures and those who don’t, regardless of their standing in the class. 

We should collect data on why students currently choose not to attend even though there is no penalty, to see if a two-path grading criteria would potentially incentivize more students to attend lectures.