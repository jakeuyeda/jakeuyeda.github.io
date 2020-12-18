---
layout: project
type: project
image: images/code_square (1).png
title: Bank Interface
permalink: projects/bankinterface
# All dates must be YYYY-MM-DD format!
date: 2018-11-27
labels:
  - C++
  - C
  - Programming
summary: A bank system I developed for ICS 212.
---

This was one of the projects where I only had myself to depend on. I had to code a bank interface that could add a record, print a record, delete a record from their database. This is a type of project where I learned a lot of things when working by myself.
The main thing I got out of this project was to make sure you do not procrastinate. Make sure you are working on this every day so when the due date is coming up, you are not too busy and pulling all-nighters. I spent the last three days trying to do this project when I could have done parts of it earlier during the week. Even though I finished it on the last day, I do not want to have that feeling ever again. Now, I usually do my assignments pretty early so I do not have to worry about it.
When writing the code, I learned a lot of things. One thing I learned was how to debug your code when it is pretty long. In this project, I had hundreds of lines of code. If there was a syntax or semantics error, I had to find out what was wrong through all my lines of code. And knowing me, I had a lot of errors when making this project. I had to find out how my values were being changed in my project when there was an outcome that was not supposed to be there. This project taught me a lot about debugging a program.

Here is some of my code that shows the interface:

    while (run == true) {

        int user;
    
        std:: cout << "Main Menu\n";
        std:: cout << "Enter the number next to the command.\n";
        std:: cout << "[1] Add a new record to the databse.\n";
        std:: cout << "[2] Print information about a record using accountno as the key.\n";
        std:: cout << "[3] Print all information in the database.\n";
        std:: cout << "[4] Delete an existing record from the database using the accountno as key.\n";
        std:: cout << "[5] Reverse the order of the database.\n";
        std:: cout << "[0] Quit the program.\n";    
    
        user = userInterface();        
    } 
