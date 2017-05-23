---
layout: post
author: nvola
title: "Natasha's Logical Turtle Exercise"
---
For my logical turtles exercise I created a basic grade calculator in which the user is prompted to enter the grade received and the weight for the assignment, they are then asked whether they would like to add more grades, if so, they are prompted to continue entering more grades and weights until they are done, at which point the final grade is calculated.


<iframe src="https://trinket.io/embed/python/6c8da1e644?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>



Initially, it was difficult coming up with an idea of what to create for this assignment, so I actually had two ideas that I worked through first before deciding on this. Once I decided on this idea, I began by creating a list for the grades to go into; having not worked with these yet, it was a little difficult figuring out the ins and outs of them. For example, I had some issues with the SUM function took me some time to figure out; the problem was the placement of the function: I had it at the beginning of the code so it wasn't calculating the sume of the full list. Also, I needed to be reminded by the error message that I needed to change the data type of the weighted grade to float to be able to do an operation on them and to add them to the list.


Another difficulty I came across was in creating the loop that allowed for the user to continue entering grades. The actual syntax was fairly simple given that I had used a loop in the Turtlehacks exercise, but testing it to make sure it worked was actually fairly time-consuming as were the small tweaks required to get it to work the way I wanted it to. With more time I would have to include some checks in the code such that if a user enters invalid input they get an error message and are propmted to re-enter their input; this would have been easy to do line by line, however I would want to try to incorporate it into the loop somehow.


Another issue I came across was in printing the final results; initially I did not realize that you could not concatenate strings and lists when printing something. So my lightbulb came on when I received the error saying as much.
