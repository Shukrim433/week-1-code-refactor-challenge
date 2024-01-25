# week-1-code-refactor-challenge

## Description

- My motivation for this project was to make the existing code of this webpage more accessible. Because the html and css code for this webpage was outdated, it proved to not be very accessible to people with disabilities, for example, visual imparement or blindness. Therefore screen readers and other assistive technologies would not be able to properly convey the information to people with the disabilities. So my refactoring of this webpage's code solves this problem.

## Problems and solutions

- The first problem I came across was in the HTML code. I noticed there were many <div> elements with class attributes that were not necessary, for example <div class="header">. I replaced such elements with their most appropriate semantic equivalent, so for my previous example I replaced it with the <header> element. And for othere elements I kept the class attributes and just replaced the element with a semantic element. These semantic elements made the code more accessible. 

- The second problem I encountered was my changes to the html code ended up changing the appearance of the webpage, which is something you do not want when refactoring. So I went into the css code and figured out I had to change the code to match up with the new html code. So I changed the class selectors (that were previously for the div elements) and changed them to element selectors that matched the new html code. For example the 
".header" class selector was changed to a "header" element selector. So after these updates to the code the webpage reverted back to its original appearance.

-The last problem I noticed with the old code of the webpage was the <img> elements didnt have alt attributes, meaning that screen readers and other assistive technologies wouldnt be able to describe the contents of the images to people with visual impairments. So I went in and added alt attributes to all of the <img> elements in the html code to make it more accessible. 


## Webpage

These are some screenshots of the webpage. The webpage looks and functions the exact same way it did before I added my updates because I was only refactoring the code.

![first screenshot of the webpage](./assets/image.png)
![second screenshot of the webpage](./assets/image-1.png)
![final screenshot of the webpage](./assets/image-2.png)