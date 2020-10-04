---
layout: post
title:      "CLI Project "
date:       2020-10-04 22:09:39 +0000
permalink:  cli_project
---


For my very first Flatiron project, I decided to design a CLI which would extract data from an API and provide users with a list of titles that matched their keyword search; originally, I attempted to use the Harvard University Library API but found it difficult to parse, leading me to switch to OpenLibrary's API. Upon retrieving the list, users would then be able to enter the number of whichever book they were interested in and it would return pertinent information related to the book. I initially conceived of a specific user in my mind: a recent PhD recipient hired on to teach art history at a state university, even though all of his graduate and doctoral work has been in history (with a specialization in World War II aviation.) In this imagined scenario, our poor fellow would not want to use any popular search engine for fear that his employer could view his browsing history and discover he is no expert at all in art history and has no business teaching it. Enter: Matt's Book Finder, the perfect place to retrieve a list of texts relevant to whatever your search query is.

For my CLI, I created three different classes: API, Book, and CLI. My API class retrieved books which matched a user query from the OpenLibrary API, my Book class created and stored book objects, and my CLI class was my main work horse- pulling class methods from both of my other classes, doing user interface, and running my loop. 

I worked first on my model (Book) and API class, building the skeleton of my CLI class around what methods and variables I was slowly making available to it. Once I felt my Book and API classes were well established, I went to work heavily on my CLI class. A major issue I ran against was the problem of my print_books instance method, where I continued to receive error messages whenever I would try to run each.with_index over my Book class method find_by_query. Finally, I decided to set the class method to a variable (I named it "results") and iterate over that variable in the next line. Worked like a charm! Curious, I thought. I'm still not quite sure why it will run on the variable but wouldn't run when I had typed it out in entirety. Perhaps a syntactical error I overlooked? I'm unsure. I experienced mostly smooth sailing from thence out. 

I feel this project has helped my understanding of object oriented Ruby immensely. I was very unsure of myself before I began and the blank screen was so intimidating! I found once I began the project and took it slowly and methodically (with lots of references back to video lectures by my great cohort leader), I was able to make progress - little by little, then all at once. 
