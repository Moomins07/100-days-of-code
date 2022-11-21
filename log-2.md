# 100 Days Of Code V2- Log

[Having completed a 100DaysOfCode Challenge a few months back I've decided to begin a 100 days of code challenge again! 
I found myself much more consistent when taking part in the challenge, and so here we are again.]

### Day 1: November 05, 2022 
### The Odin Project [CONTINUATION]

##### [Having completed the foundation section of The Odin Project, as seen in the first log.md, the course then allowed me continue on with a specific full-stack JavaScript course.]  

**Today's Progress**: Continuing with The Odin Project course, I am currently within the Intermediate CSS section which has covered important topics such as advanced selectors, positioning, functions and now forms. Having completed all of the above so far, I was tasked with copying a website layout including a form to the best of my ability. I am about finished with the project except for the JavaScript functionality which I will be adding tomorrow.

**Thoughts:** I was quite excited to begin a new project using mostly CSS and HTML again as I had recently spent a significant amount of time using both for a previous, large project. However, embarrassingly, I found myself staring blankly at the screen wondering just how I was going to copy the website example I had been provided with. Whilst building the site, I attempted to use as many newly-learned pieces of code as I code, which I think I could have done better with, but I'm content nonetheless. Mostly, I used more specific selectors rather than giving every single element a class as I had done in the past. This reduced the amount of classes I'd normally use significantly and made it easier to navigate my code. I also used positioning whilst now actually understanding why I achieved a certain result! For example, I had 2 divs, one left, one right. I attempted to position an 'absolute' element in the left div that would use 100% width, but instead it would span across both divs. I fixed this as I had remembered that the parent element, the left div in this case, must be set to a position of 'relative' before the absolute-positioned element can use the left div as a parent element. Overall, I'm very happy with the project result so far, I will be continuing tomorrow with the JavaScript functionality.


### Day 2: November 07, 2022 

**Today's Progress**: Continuing with the form project, I've now implented JavaScript that check if both password fields contain the same values, and if so, sets the border-colours of those fields accordingly. Green if correct, red if incorrect. I also made some adjustments to the form itself as I noticed I had accidentally placed the create account button outside of the form; unfortunately, that mistake cost a little time as I had trouble re-constructing the containers using flexbox.

**Thoughts:** I came across many walls whilst implementing the password field code, of which I will list out. Firstly, I added a single eventListener that simply checks if the password fields contain/do not contain the same values. However, I had only applied this eventListener to the confirm_password field, which meant that any changes to the first password field would not make those checks. The first solution I tried was to add another eventListener to the other password field too, but this would cause the password field to un-focus after a single input and move to the confirm_password field. I then tried putting both password fields into a nodeList and looping through them to apply to code to both at the same time, but this unfortunately had the same result and continued to un-focus the field after 1 input. Putting the 'check' code into its own function and passing that function into the nodeList eventListener also did not work, same result. The best result I could get was actually by adding another attribute in my password field's html code, specifically "onChange" where I then also passed in my JavaScript function that made the checks. onChange = "onChange()". The only fault I can see is that the checks are not made until I have un-focused the field, meaning the checks do not seem to be made on each input? Overall, a very informative day, happy to be moving on from this project.\
*Edit: I'd also eventually like to code the fields to only appear invalid with a red border AFTER an input. Currently, the fields appear red on initial load.*


### Day 3: November 10, 2022 

**Today's Progress**: Today I completed another follow-along JavaSript project using FreeCodeCamp YouTube videos. Today's project was creating a functional and responsive navbar.

**Thoughts:** I found this particular project very interesting as I've used responsive navbars many times in previous projects, normally using frameworks to do the work for me, so being able to see how it works under the hood was practically relieving to see. The project was a little short and the JavaScript itself not too complex, as it was using an event-listener to make a hamburger menu change the height of an element using classList toggle. Fun project, looking forward to getting through the video one project at a time.


### Day 4: November 12, 2022 

**Today's Progress**: Continuing with the Odin project today, I'm finally exploring CSS Grid, tinkering with the different options and reading up on a lot of documentation.

**Thoughts:** Having spent a lot of time exclusively using flexbox for my web development needs, it's refreshing and exciting to finally move onto learning Grid. Today has mostly been introductions to Grid, but I can see how powerful Grid is going to be for my webpage layouts in the future. Speficially, the focus of today was not just to learn about CSS Grid as a whole (including its history) but specifically to understand Grids use of implicit and explicit tracks. I'm very excited to begin using Grid in future projects and especially my personal projects.


### Day 5: November 13, 2022 

**Today's Progress**: Continuing with the Odin project, I further explored CSS Grid and other methods of using CSS Grid, such as using named grid-template-areas. I followed a Kevin Powell CSS Grid project on YouTube, completed an Odin Project Grid exercise and also finished all levels on https://cssgridgarden.com/.

**Thoughts:** After today, I feel much more confident in my ability to use CSS Grid, however, I am still unsure about the shorthand syntax of Grid as there are several that I confuse together including the actual layout of the syntax itself. I will further research into the following syntax: grid-template, grid-template-area and grid-area. I'd also like to further understand the ability to use '0' as a height when laying out the Grid and what effects that has. I am very happy with todays progress.


### Day 6: November 16, 2022 

**Today's Progress**: Continuing with the Odin project, I've begun working on the final CSS Grid project that requires me to use what I have learned from the documentation across the last few days.

**Thoughts:** I found todays project extremely frustrating as I ran into several walls that had me stuck for hours. For some reason, when I'm declaring the size of the grid, there's the recurring issue of an extra column and/or row being added that I struggle to remove. This happened the first time to the header of the site causing 2 rows to appear when I only needed 1; I resolved this, somehow, by setting the height of the site to use 100% view height? I also ran into the issue of trying to move a div to the left side of my grid as using the class to select that div would not work; I was only able to move the div once I selected it using a child selector of the header. I also got stuck on using Grid as a way to design a navbar as I forgot that I should apply the display type of grid to the 'ul', not the parent container of that ul. I'm around half-way finished with the project, slowly working through the little hurdles. I am currently experiencing the same issue of extra rows and columns being created with inthe left side-bar of which I will have 4 boxes aligned vertically. I hope to have the project completed by tomorrow.


### Day 7: November 18, 2022 

**Today's Progress**: Today I continued to work on the CSS Grid project.

**Thoughts:** Unfortunately, this project continues to be frustrating as I come across multiple walls that keep me from achieving a result that is relatively similar to the final-project image. Using template-areas I was able to quite quickly achieve the overall layout of the grid, of which worked perfectly as I began to make finer tweaks to other sections of the grid. However, once I got to the middle-section of the grid that required me to use responsive functionality to fit cards into the space, the cards would break. I even double-checked my solution with the projects final solution to find that my code was in fact exactly the same. I used repeat(auto-fit, minmax(250px, 1fr)). I will continue more tomorrow.


### Day 8: November 21, 2022 

**Today's Progress**: Today I was finally able to finish up the CSS Grid project.

**Thoughts:** I frustratingly continued to attempt to tweak the grid using template-areas to no avail, as the cards in the middle-section would still break. Due to this, I decided to start over, this time without using grid-template-areas and individually placing child elements within the crid using grid-row and grid-column. Fortunately, this solved the problem, but I am disappointed that I was not able to make the grid work using my own method of template-areas; I guess that's what I get for trying to run before I can walk! The grid matched the finished-project image perfectly although the grid was not using 100vh, so the footer would sit half-way up the page when stretched. I checked the solution code to find that this is actually intended, which I feel the course should have been more explicit about, as I was under the impression that the footer would sit at the bottom of the page.. Like most footers. In hindsight, using 100vh for my grid container in my original attempt to create the grid may even have been the issue. On to the next project tomorrow!
