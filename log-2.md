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
