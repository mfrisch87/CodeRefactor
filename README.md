# CodeRefractor Project

## Objective
    The objective of this project is to take prebuilt code and fix any functions that are not working and document changes to the CSS that are made. Also we are to consolidate the given CSS in order to reduce the code in the CSS to make it easier to read and change. Below are the steps I took.


### Changes Made

1. I started with the index.html file and found some functions that I felt needed changes/fixing.
    * The 'search-engine-optimization' link was not working properly. This was fixed by giving the div for 'search-engine-optimization' a class so that the pre-existing link would properly jump to that section of the page.
    * Next I noticed that nothing was in the 'title' tags of the page therefore the browser just said 'website' therefore I added 'Horiseon Marketing' between the tags to fix
    * I noticed that the h1 tags had the name 'Horiseon' broken up and the class was weirdly named. I made the change to join the full name together betwen the span and h1 tags and renamed the 'seo' class to 'horiseon'. For this class change, I made sure to reflect that change in the CSS file.

2. My next goal was the go through the CSS file and consolidate as much as I could to keep the integrity of the page.

    * I was able to consolidate the two h1 tags as they were both influcencing the same single content.
    * I consolidated all the different h2 tags since they all had the exact same properties.
    * Just for looks on the css files, I eliminated some extra space between the footer and img tags.
    * I consolidated the tags formatting the three divs under the 'content' div to be a single '.content div' tag since they were all had same properties.
    * I consolidated the img tags under the 'benefits' div since they shared the same properties.
    * Made a similar consolidation of the div tags under the 'benefitss' div.
    * I made notation of the different changes that were made.



These were all of the changes I was able to find and make to 'clean-up' the code given.