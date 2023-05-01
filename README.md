Download Link: https://assignmentchef.com/product/solved-cecs-551-programming-assignment-2
<br>
<h1>Preparatory Reading</h1>

Read Sections 4.2 and 5.1.

<strong>Presenting Your Work.</strong>

Submit via email an R script named assign2-StudentFirstName.R. For example, if your first name is George, then you would submit the file assign2-George.R. Line 1 of the file should include your full name as a comment. Also, for each block of code that pertains to some exercise, say Exercise 1, preface the code with the comment (all in caps)

#EXERCISE 1

Each function should be named <em>exactly </em>as it appears in the exercise, and have an input signature that follows the order specified in the exercise.

<strong>Important: </strong>make sure your file produces no errors when sourced by the R interpreter. Otherwise your work will not be graded. Therefore, the answers to Exercises 4 and 5 should be placed in comments. For example,

#EXERCISE 5

# w = (-4.5,10.8, -5.6, 12.5, 11.2), b = -0.3

1

Your email submission should be postmarked no later than the time shown on the due date. Submissions received after that time, but on the same day will lose one letter grade. Submissions emailed on a later day will either not be accepted, or will lose two letter grades.

<h1>Exercises</h1>

<ol>

 <li>Write an R function called <strong>simple learner </strong>that takes as input a data frame df (you may assume that all columns of df are numeric, and the final column provides a class label of 1 or −1) and returns a list having two attributes <em>w </em>and <em>b</em>, where <em>w </em>= <em><span style="text-decoration: line-through;">c</span></em><sub>+ </sub>− <em><span style="text-decoration: line-through;">c</span></em><sub>− </sub>and <em>b </em>= <em><span style="text-decoration: line-through;">w </span></em> <em><span style="text-decoration: line-through;">c</span></em>, where <em><span style="text-decoration: line-through;">c</span></em><sub>+ </sub>and <em><span style="text-decoration: line-through;">c</span></em><sub>− </sub>are the respective centers of mass of the positive and negative datapoints, and <em><span style="text-decoration: line-through;">c </span></em>= (<em><span style="text-decoration: line-through;">c</span></em><sub>+ </sub>+ <em><span style="text-decoration: line-through;">c</span></em><sub>−</sub>)<em>/</em>2 is a point on the linear decision surface.</li>

 <li>Write an R function called <strong>perceptron learner </strong>that takes as input a data frame df (you may assume that all columns of df are numeric, and the final column provides a class label of 1 or −1) and returns a list having two attributes <em>w </em>and <em>b</em>, where <em>w </em>and <em>b </em>are obtained by performing the perceptron learning algorithm using the vectors from df.</li>

 <li>Write an R function called <strong>classify </strong>that takes as input i) data frame df, and ii) linear decision surface parameters <em>w </em>and <em>b</em>, and returns a vector <em>v </em>that provides the classifications of each of the vectors of df. Thus each component of <em>v </em>is either 1 or -1, and the length of <em>v </em>equals the number of vectors of df. Moreover, we assume that the number of columns of df is equal to the dimension of <em><span style="text-decoration: line-through;">w</span></em>.</li>

 <li>Use the data in file exercise-4.csv to build a data frame df, and provide the <em><span style="text-decoration: line-through;">w </span></em>and <em>b </em>values that are returned by simple learner(df).</li>

 <li>Repeat Exercise 4, but now provide the <em><span style="text-decoration: line-through;">w </span></em>and <em>b </em>values that are returned by perceptron learner(df).</li>

</ol>

2