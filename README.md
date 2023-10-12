[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/oB7VDeFN)
# ExplorationActivity1
## Question 1: What library
The library I use for the first instance of the exploration projects is a JavaScript library called Charts.js. It's functionality is that it creates an  HTML extension in the browser of your choice and displays your data in the form of various graphs and charts.
## Question 2: How to run
To run this file you must have some sort of text editer and terminal combination. I used Visual Studio as it is my standard text editor and it also very easy to use in terms of html web pages and has the terminal built in. To run my file you can either press _Run_ on the taskbar and choose the _Start Debugging_ in the dropdown and it will proceed to open up the broswer of your choice conversely you can run it through a terminal. Like usual you must traverse to the directory that the file is stored in, the command to run is: _google-chrome testingChart.html_ this is just an example because I am partial to Chrome but any web browser will do.
## Question 3: Purpose
The purpose of this program is to show the utility of this library, I took one of Connor's graphs that he sends us after the programming questions are due showing the distribution of questions picked and plugged that data in to show how applicable and useful this library is. My second graph was to display the variety of the graphs by choosing a polar area chart to present data in a different style then a basic bar chart. I have been very in to fantasy football lately and diving into the data analytics side of it, so for my example I showed the top 5 fantasy point running back leaders in the 2022 NFL season. If I was a youtuber or journalist I could use chart.js to show football stats and anayltics to suggest certain players or teams, the image below is a great example of this being used in action on the extremely reputable football site Pro Football Focus:\
<img width="300" alt="image" src="https://github.com/CS2613-FA23/explorationactivity1-Staebe/assets/144264731/b41f00f5-840f-43bf-b204-38f78986c0da">
 [Image link](https://www.pff.com/news/fantasy-football-perfect-2023-fantasy-football-draft-strategy-round-by-round-picks-1-3)
## Question 4: Sample Input/Output
For this example it was more effective to create the data according to Connor's email but we have experience with I/O enough to request data from the user and store it in an array. It would not be hard at all considering the hardest part was coding the html output. An example would be:\
_console.log("Please input a comma separated set of values you would like graphed:");_\
_const prompt = require('prompt-sync')([sigint: true]);_\
_let data = prompt("");_\
_const array = data.split(',');_\
This brief example would now have the list of data inputted from the user stored in the array and be ready to be outputted into a graph.

 
