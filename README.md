# GitHub_Issue_Tracker
Problem Description 

Create a repository on GitHub and write a program in any programming language that will do the following: 

Input : User can input a link to any public GitHub repository

Output :

Your UI should display a table with the following information -

- Total number of open issues

- Number of open issues that were opened in the last 24 hours

- Number of open issues that were opened more than 24 hours ago but less than 7 days ago

- Number of open issues that were opened more than 7 days ago 

Solution:

This is a program to track open issue count for a public Git repo. 
The scrpit is written in python and I used the Flask frame work to design the solution.
To keep track of the time I am useing python standatrd datetime libraries. And the solution is designed based on the RESTful webservice provided by GitHub to keep track of the issues.
This application is live on https://istr.herokuapp.com/ for next 14 hrs from now(till 8 AM 27-mar-16).
Input is any public Git repo url and output will be according to the problem description.
