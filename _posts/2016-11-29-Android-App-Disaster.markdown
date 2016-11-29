---
layout: post
title:  "Android App Disaster"
date:   2016-11-29 9:24:35 -0300
categories: School
author: Evan
---

For my Android development class I was asked to make an app that used fragments and had a responsive design. It also needed to use SharedPreferences to save the state of the app so the next time it was opened it would be at the same spot. This seemed fun and interesting so as soon as I had time I jumped on it.

I decided to use Github for once for version control for the project. This ended up being really awesome and I realized I should have been using it for all my assignments, so that was at least a win for me. I started the project by doing some research into fragments and I found some pretty good tutorials for some basic mutliple fragment apps. This was great and I started getting a  lot of ground covered right away, unfortunately I had started the assignment behind schedule and the due date was approaching, on top of that I work a part time job while in school and this time of the year it starts getting pretty busy.

Once I had my fragments set up and working well I decided to look in to responsive design. Found some good resources on this as well. Added the functionality to my app by making a new fragment just for tablet sized displays and created some XML files for phone and tablet sized screens. By the way I found a lot of these tutorials at [Treehouse](https://teamtreehouse.com/), which is an amazing resource. I have been using it to supplement my school learning and have been very happy with it.

The due date was coming up and currently my app was a list of animals and when one was selected it would show a new fragment with the animal image enlarged. The app had a list view for phones anda  grid view for tablets. I thought everything was coming along smoothly when I realized there was another big part of the rubric that I was missing on top of the SharedPreferences. It was using the strings.xml to store all the strings that would be displayed in my GUI. This is where everything started to go downhill.

For 2 days I tried to figure out how to make a static String array in my app using data from the strings.xml file. I found out you could make a String array in the xml file but I just could not get the data from that xml file to translate to a static array in the app. I had already set the app up to have a class with the two arrays I needed, one for the animal names and one for the images, but it was hard coded and the rubric wanted it in the strings.xml. After a few failed attempts and tons of Stack Overflow I eventually gave up on it.

The project was now late but still needed SharedPrefences added. I decided to try and implement a feature where the items in the list would change color after they were selected. Then I would use SharedPreferences to save that information and check for it everytime the app loaded to keep them the new color. After researching some and trying for 2 additional days I just could not get this feature to work with my app. 

In the end I think my app become too large complicated for me to add something like SharedPreferences to it. I learned a lot from the whole process though, so it isn't a total failure for me. I may not get great marks on this assignment but I learned some valuable lessons in planning ahead and scope. I do really enjoy making Android apps so I hope I can really learn a lot and do well on the next assignment.

If you want to check out the app I made it is availbe on my github [here](https://github.com/oakeef/Android-Fragments).