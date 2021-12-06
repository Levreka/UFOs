# UFOs

# Data Visualization Week 11 Challenge

## Background 
Dana (our customer) satisfied with our first table decided she would like the table to be more dinamic. The request is to add more filters to the charts allowing for users to filter through our table using more than just one variable of search. The ability to search by city and state for example, allows for data results to be both precises and flexible. 

### Objectives
The goals of this challenge are to:

* Create, update, and deploy JavaScript functions to provide additional table filters.
* use forEach (for loop) to loop through the filters and update them with user input.
* populate the dynamic filters and table using JavaScript and HTML.

#esults:
Once we exectuted our JS code and updated our html to reflect our new code we end up with a web page like and filters on the side as shown:<img width="1280" alt="Screen Shot 2021-12-05 at 7 49 27 PM" src="https://user-images.githubusercontent.com/90356052/144779350-03c95c00-8282-4744-a7c3-42fe88812cac.png">
In this image I created a simple search just by state of arizona. This gives us the results of phoenix and maricopa along with other information like shape, duration and comments. The first test was done thinking, of users who may only have one piece of information to search with. 

Running specific search using all the options available to filter the table also yields the proper data as view in the image below.
<img width="1280" alt="Screen Shot 2021-12-05 at 7 49 27 PM" src="https://user-images.githubusercontent.com/90356052/144780098-60350dfd-3321-4eea-a93a-6065281d8cf7.png">
Our results show that our filters work well and can filter as needed.

#Summary:
The web page works well, however on our first testing phase when we search for a city or a value that is not part of our table our webpage returns nothing. In our testing phase I believed that filters werent working. I had to choose from the table a city with actual UFO's, in order to test it. 

Another drawback of our current site is that we don't have the flexibility of typos or close to matches.

#2 Recomendations:
#1: fixing one of our drawbacks, would be to display a message "no ufos sighting with current filters". This way users get some sort of feedback on wether or not the web page is working correctly or if their filters need to be corrected.

2: the second reccomandation would be to allow for close matches in our filters. This is to allow users a margin for errors and still manage to get some data return. 
