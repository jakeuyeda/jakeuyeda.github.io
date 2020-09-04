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

This was one of the projects where I only had my self to depend on. I had to code a bank interface which could add a record, print a record, delete a record from there database. This is a type of project where I learned a lot of things. One of the things I learned was how to debug code that was pretty long.

 Here is some of my code:
 

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
