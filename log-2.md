# 100 Days Of Code V2- Log

[Having completed a 100DaysOfCode Challenge a few months back I've decided to begin a 100 days of code challenge again! 
I found myself much more consistent when taking part in the challenge.]

### Day 1: November 05, 2022 
### The Odin Project [CONTINUATION]

##### [Having completed the foundation section of The Odin Project, as seen in the first log.md, the course then allowed me continue on with a specific full-stack JavaScript course.]  

**Today's Progress**: Continuing with The Odin Project course, I am currently within the Intermediate CSS section which has covered important topics such as advanced selectors, positioning, functions and now forms. Having completed all of the above so far, I was tasked with copying a website layout including a form to the best of my ability. I am about finished with the project except for the JavaScript functionality which I will be adding tomorrow.

**Thoughts:** I was quite excited to begin a new project using mostly CSS and HTML again as I had recently spent a significant amount of time using both for a previous, large project. However, embarrassingly, I found myself staring blankly at the screen wondering just how I was going to copy the website example I had been provided with. Whilst building the site, I attempted to use as many newly-learned pieces of code as I could, which I think I could have done better with, but I'm content nonetheless. Mostly, I used more specific selectors rather than giving every single element a class as I had done in the past. This reduced the amount of classes I'd normally use significantly and made it easier to navigate my code. I also used positioning whilst now actually understanding why I achieved a certain result! For example, I had 2 divs, one left, one right. I attempted to position an 'absolute' element in the left div that would use 100% width, but instead it would span across both divs. I fixed this as I had remembered that the parent element, the left div in this case, must be set to a position of 'relative' before the absolute-positioned element can use the left div as a parent element. Overall, I'm very happy with the project result so far, I will be continuing tomorrow with the JavaScript functionality.

---

### Day 2: November 07, 2022 

**Today's Progress**: Continuing with the form project, I've now implented JavaScript that check if both password fields contain the same values, and if so, sets the border-colours of those fields accordingly. Green if correct, red if incorrect. I also made some adjustments to the form itself as I noticed I had accidentally placed the create account button outside of the form; unfortunately, that mistake cost a little time as I had trouble re-constructing the containers using flexbox.

**Thoughts:** I came across many walls whilst implementing the password field code, of which I will list out. Firstly, I added a single eventListener that simply checks if the password fields contain/do not contain the same values. However, I had only applied this eventListener to the confirm_password field, which meant that any changes to the first password field would not make those checks. The first solution I tried was to add another eventListener to the other password field too, but this would cause the password field to un-focus after a single input and move to the confirm_password field. I then tried putting both password fields into a nodeList and looping through them to apply to code to both at the same time, but this unfortunately had the same result and continued to un-focus the field after 1 input. Putting the 'check' code into its own function and passing that function into the nodeList eventListener also did not work, same result. The best result I could get was actually by adding another attribute in my password field's html code, specifically "onChange" where I then also passed in my JavaScript function that made the checks. onChange = "onChange()". The only fault I can see is that the checks are not made until I have un-focused the field, meaning the checks do not seem to be made on each input? Overall, a very informative day, happy to be moving on from this project.\
*Edit: I'd also eventually like to code the fields to only appear invalid with a red border AFTER an input. Currently, the fields appear red on initial load.*

---

### Day 3: November 10, 2022 

**Today's Progress**: Today I completed another follow-along JavaSript project using FreeCodeCamp YouTube videos. Today's project was creating a functional and responsive navbar.

**Thoughts:** I found this particular project very interesting as I've used responsive navbars many times in previous projects, normally using frameworks to do the work for me, so being able to see how it works under the hood was practically relieving to see. The project was a little short and the JavaScript itself not too complex, as it was using an event-listener to make a hamburger menu change the height of an element using classList toggle. Fun project, looking forward to getting through the video one project at a time.

---

### Day 4: November 12, 2022 

**Today's Progress**: Continuing with the Odin project today, I'm finally exploring CSS Grid, tinkering with the different options and reading up on a lot of documentation.

**Thoughts:** Having spent a lot of time exclusively using flexbox for my web development needs, it's refreshing and exciting to finally move onto learning Grid. Today has mostly been introductions to Grid, but I can see how powerful Grid is going to be for my webpage layouts in the future. Speficially, the focus of today was not just to learn about CSS Grid as a whole (including its history) but specifically to understand Grids use of implicit and explicit tracks. I'm very excited to begin using Grid in future projects and especially my personal projects.

---

### Day 5: November 13, 2022 

**Today's Progress**: Continuing with the Odin project, I further explored CSS Grid and other methods of using CSS Grid, such as using named grid-template-areas. I followed a Kevin Powell CSS Grid project on YouTube, completed an Odin Project Grid exercise and also finished all levels on https://cssgridgarden.com/.

**Thoughts:** After today, I feel much more confident in my ability to use CSS Grid, however, I am still unsure about the shorthand syntax of Grid as there are several that I confuse together including the actual layout of the syntax itself. I will further research into the following syntax: grid-template, grid-template-area and grid-area. I'd also like to further understand the ability to use '0' as a height when laying out the Grid and what effects that has. I am very happy with todays progress.

---

### Day 6: November 16, 2022 

**Today's Progress**: Continuing with the Odin project, I've begun working on the final CSS Grid project that requires me to use what I have learned from the documentation across the last few days.

**Thoughts:** I found todays project extremely frustrating as I ran into several walls that had me stuck for hours. For some reason, when I'm declaring the size of the grid, there's the recurring issue of an extra column and/or row being added that I struggle to remove. This happened the first time to the header of the site causing 2 rows to appear when I only needed 1; I resolved this, somehow, by setting the height of the site to use 100% view height? I also ran into the issue of trying to move a div to the left side of my grid as using the class to select that div would not work; I was only able to move the div once I selected it using a child selector of the header. I also got stuck on using Grid as a way to design a navbar as I forgot that I should apply the display type of grid to the 'ul', not the parent container of that ul. I'm around half-way finished with the project, slowly working through the little hurdles. I am currently experiencing the same issue of extra rows and columns being created with inthe left side-bar of which I will have 4 boxes aligned vertically. I hope to have the project completed by tomorrow.

---

### Day 7: November 18, 2022 

**Today's Progress**: Today I continued to work on the CSS Grid project.

**Thoughts:** Unfortunately, this project continues to be frustrating as I come across multiple walls that keep me from achieving a result that is relatively similar to the final-project image. Using template-areas I was able to quite quickly achieve the overall layout of the grid, of which worked perfectly as I began to make finer tweaks to other sections of the grid. However, once I got to the middle-section of the grid that required me to use responsive functionality to fit cards into the space, the cards would break. I even double-checked my solution with the projects final solution to find that my code was in fact exactly the same. I used repeat(auto-fit, minmax(250px, 1fr)). I will continue more tomorrow.

---

### Day 8: November 21, 2022 

**Today's Progress**: Today I was finally able to finish up the CSS Grid project.

**Thoughts:** I frustratingly continued to attempt to tweak the grid using template-areas to no avail, as the cards in the middle-section would still break. Due to this, I decided to start over, this time without using grid-template-areas and individually placing child elements within the crid using grid-row and grid-column. Fortunately, this solved the problem, but I am disappointed that I was not able to make the grid work using my own method of template-areas; I guess that's what I get for trying to run before I can walk! The grid matched the finished-project image perfectly although the grid was not using 100vh, so the footer would sit half-way up the page when stretched. I checked the solution code to find that this is actually intended, which I feel the course should have been more explicit about, as I was under the impression that the footer would sit at the bottom of the page.. Like most footers. In hindsight, using 100vh for my grid container in my original attempt to create the grid may even have been the issue. On to the next project tomorrow!

---

### Day 9: November 22, 2022 

**Today's Progress**: In preparation for the final TOP CSS Grid project, I spent several hours today using YouTube videos and following along with projects by Kevin Powell and Brad Traversy. I completed all of the projects and also paused the videos and spent a significant amount of time using Grid myself to develop my understanding.

**Thoughts:** The video projects were extremely helpful and cleared up a few grey areas, such as the grid syntax which I had written about on day 5 in this log. I also now have a greater understanding of Grids potential when it comes to responsive design, such as by using auto-fit/auto-fill, the fr unit and media-queries. Overall, I feel much more confident in my ability to use Grid manually and not just via Bootstrap/other frameworks.

---

### Day 10: November 25, 2022 

**Today's Progress**: Today I made a start on the final TOP CSS Grid project that requires me to create a complicated admin-panel style layout. So far I've managed to complete the navigation side panel and the overall Grid layout.

**Thoughts:** Although more confident with the use of Grid, I still find myself very overwhelmed, as even though I had laid out the overall Grid for the page, I feel that I haven't used units/responsive sizing to its full potential, by using minmax or auto-size functions. When tackling the navigation panel, I found myself confused as to how to do it, as there are obviously several ways this could be done. From my brief research, it seems that most people opt for using ul/li/a tags in sections. However, seeing as the project is focused on the use of Grid, I attempted to use Grid as much as possible in the design. I was unsure if I should apply a div to every elemetn that I was going to place in the grid, as there are 2 columns, one for the icon and one for the menu text; I was able to position these correctly without putting everything into a div. However, my first issue was that I needed to space specific rows apart from eachother, which Grid cannot do, it can only apply spacing to all of the rows. My way around this was by putting 2 row's elements into flex-divs and applying a margin-bottom, but this feels shoddy and incorrect. I plan to re-approach the same design and split the grid up into 3 divs that will also be grids so that I can use gap to split the grouped-rows apart, as opposed to using flex-divs and margin-bottom. However, this approach will require me to apply the same column sizing in the first column to each grid to ensure that everything aligns correctly.

### Few days watching project videos ###

---
### Day 11: November 29, 2022 

**Today's Progress**: Continuing with the CSS Grid admin panel project.

**Thoughts:** I decided to re-create the nav panel on the left side as I was not happy with the result. Thankfully, this was not too difficult a task as most of the code was complete, I just needed to place the content in divs and place everything accordingly using Grid. Following this, I moved on to the header panel at the top that includes a search bar, several icons and text/buttons. To do this, I broke the header up into 2 columns and used a combination of box Grid and Flexbox to align things correctly. One particular thing to note is that I did attempt to use clamp/minmax css functions but found that they didn't work as intended. In place of those functions, I instead used width: 60% and declared a min-width and max-width; this was extremely helpful when designing the input/search bar. It has been quite a challenge so far, I need to remember that both Grid and Flex are at my disposal, using both seems to really speed up the process. Overall, I'm very happy with the progress so far, although it is taking much longer than anticipated.

---
### Day 12: November 30, 2022 

**Today's Progress**: Today I finally finished up the CSS Grid panel project!

**Thoughts:** I was able to complete both the main content section and the right side panel today, finishing up the project. I've begun to use a different naming-style in this project that uses two underscores as I find it neater and easier to read, opposed to just using a single dash to seperate words. I'm also now endeavouring to use less classes unless I absolutely have to and instead opt to use more selectors, such as nth-child, nth-of-type, first-child, last-child etc etc. Much easier to read my HTML. A few key things to note during this project: I used absolute positioning of a small yellow div to create a yellow line at the beginning of the cards that I made in the main-content section; I remembered to make the parent container position: relative and then used top & left properties to move the bar accordingly. I did come across an issue however of the div overlapping the border-radius I had set on the card, after some Googling I recalled overflow: hidden, which instantly solved the issue, preventing the div from 'leaving' the card.
Furthermore, I used auto-fit and minmax() in several places to make the grid more responsive, especially in themain content section that makes the cards fully responsive. However, I think that the units I used and the sizing I had created for my layout as whole probably could have been better? I'd like to use the clamp function more as I'm now beginning to see how incredibly useful functions such as clamp and minmax really are. Overall, it has been a very challenging but enjoyable project. I'm very happy with the result, even though I recognise that there are a lot of potential tweaks to be made.

---
### Day 13: December 01, 2022 

**Today's Progress**: Staying on track, after finishing the CSS grid project, I moved on to a Tailwind CSS Udemy course that I had purchased last week as I plan to use it for an upcoming project. I completed the first section of the course: Fundamentals part 1. I plan to move back to The Odin Project course after the tailwind course + project completion.

**Thoughts:** Even though I haven't moved on to the project section of the course yet, I'm finding Tailwind CSS very enjoyable to use. I like that it shares a lot of similarities with Bootstrap, of which I have experience with due to a previous project; Tailwind CSS, however, operates at a much lower-level compared to Boostrap, allowing minor adjustments to be made, as opposed to Bootstraps 'component' styling. Whilst using Bootstrap for my projects in the past, I recall my annoyance with the framework due to the restrictiveness of customisation without using Sass, resulting in using !important to override a lot of styling, which I find clunky and bad practice. With Tailwind, this absolutely is not the case, in fact most things can be adjusted or manipulated. I'm looking forward to using Tailwind CSS as my main go-to framework for CSS!

---
### Day 14: December 02, 2022 

**Today's Progress**: Continuing with the Tailwind CSS Udemy course by Brad Traversy, I finished Fundamentals part 2 and also a section that followed this on 'Bettering my development environment'.

**Thoughts:** Having finished the fundamentals section, although I've scratched the surface, Tailwind continues to impress me with the sheer amount of possible customisations. Fundamentals part 2 covered topics such as flexbox, grid, breakpoints and even dark mode options. I was especially impressed with the ability to seamlessly add simple animations/transitions to elements using pseudo-classes within the HTML. Better yet, in the 'Better Development Environment' section of the course, I have been introduced to NPM and its ability to not only easily add frameworks such as Tailwind, but also its ability to create scripts that allow me to quickly 'build' and 'watch' my compiled CSS folders. After completing the NPM steps, I went on to see further possibilities due to how Tailwind imports and compiles its CSS; I am able to use PostCSS in my input.css file to create components, similar to Bootstrap. I can create a class within that input file (e.g. .btn-blue) and use @apply, followed by Tailwindcss classes to apply those classes to that new component class. Tomorrow I start on some projects!

---
### Day 15: December 03, 2022 

**Today's Progress**: The last lesson within the Developer Environment section of the course was setting up the use of WebPack, although this section was optional, I decided to follow along anyway for potential future use. Following this, I made a start on the first handful of mini Tailwind projects. The first mini project was a small, responsive newsletter card. I also had some issues with Git today whilst setting up my repositories that took an hour or so to resolve.

**Thoughts:** Although I've followed along with the videos and I now have a working WebPack developer environment, I am not particularly sure on what WebPack is and its uses; I found myself feeling lost following the video as I set-up more NPM scripts, though I paused and went back in the video as needed to try and grasp what it is I am actually achieving. Thankfully, once the developer environment is set up, I can re-use that folder as a template as and when I need it, so I should not have to repeat the process. Even though I have somewhat of a basic understanding of Webpack, preferably, in the future, I'd like to actually fully understand each step and what it is I'm doing and why that may be useful to me. The mini-project, on the other hand, I had no issues with and understood every step of the video whilst coding along; the project did not take long and I'm beginning to see Tailwinds true strengths in real scenarios. 

---
### Day 16: December 05, 2022 

**Today's Progress**: Continuing with the mini-projects in the TailwindCSS course, I finished the remaining 4 projects which included: Image-gallery, login-modal, pricing card and product modal. All of which will be uploaded to GitHub.

**Thoughts:** Once again, as I was following along with the tutor coding, I rarely found myself becoming stuck or running into too many issues. However, there were a few occasions where I did find myself confused as to how my tutor came to a certain result with an element. For example, my tutot opted to place an element inside of a a simple class-less div so that the content of that element would specify the size of the empty div, also meaning that flex-type was not applied to it. This allowed me to create a div of a specific size, to fit the content, opposed to the div automatically growing to the width of the parent container. At first, I was unsure how this happened and spent time to understand it. Across most of the mini-projects, it was mostly the case of pausing the video and taking extra time to understand small tweaks here and there that the tutor would make. Overall, I feel confident that I've taken ample time to understand what I've been coding along to, but obviously putting what I've learned into actual use is always a very different story. I'm approximately halfway through the course at this point, with several very large projects coming up that specifically use a tailwind dev environment, rather than just the CDN link.

---
### Day 17: December 06, 2022 

**Today's Progress**: Moving on from the mini-projects, I began and finished the first 'large' TailwindCSS project that utilised that developer environment I had set up earlier in the course. https://github.com/Moomins07/clipboard-project

**Thoughts:** I was able to finish the project in decent time, again stopping as needed to re-familiarise myself at times with certain classes and/or to understand a block of code. Notable things to take away from this course: I noticed that the author of this course, Brad, uses margin-auto on the x-axis a lot to center his divs, which is something I find myself rarely doing. Most of the time, I will use a large flex container to center my elements; I'm not sure if this is just a preference or if there are advantages to one or the other, but I do like the simpicity of centering a div using margins. I was not too confident when checking the code used for the footer, as it used a lot of divs and classes, making it a little difficult to check over, but I felt confident enough with my understanding to continue. I especially liked the reinforcement of using the input.css file to add custom CSS and group classes using @apply again. There were a few things that bothered me with the layout of the site, such as the logo images overlapping eachother slightly on tablet screens; to fix this, I redcued the padding on the x-axis significantly and added flex-gap to space them out. On that note, Brad uses space-y-[num] and space-x-[num] a lot to space out his elements, even in flex containers. I found this unusual as flex containers can use 'gap' to space apart elements without having the elements mis-aligned within their containers. I found, however, that there are cases when gap either does the same thing as using space-x-[num], or it simply breaks the layout. E.g. When I used gap, an image blew up in size, as opposed to when I used space-y-[num], which caused the image to become the appropriate size. Very confusing.

---
### Day 18: December 07, 2022 

**Today's Progress**: Today, I began and finished the second TailwindCSS project 'loopstudios'. 

**Thoughts:** This particular project was much larger than the previous projects and even used a bit of JavaScript for a hamburger menu that was created for mobile responsiveness. Once again, we used custom CSS to create components to reduce the amount of classes cluttering our HTML and even created a custom animation for the hamburger icon, which was a lot of fun. I followed the project without hitting any real barriers, but once again I found the footer to be a little confusing at times with the use of so many divs. Things to note: Once again, Brad, centers a lot of his items use mx-auto and max-w-[x] which seems to work great at larger screens and mobile screens, but there are certain breakpoints, such as on an iPad Mini, that cause the elements to be aligned to the left? I think this is due to Brad's lack of flex-containers to center these items, combined with the use of a lot of margins to align items. I was also a little confused as to why Brad did not use Grid for the 8 project images, that were aligned exactly as Grid would have done. I'd imagine this is just to show that you are able to get the same results without the use of Grid? My confusion here, again, is that I am not sure what is best practice due to the variety of methods being used. Though I'd imagine it doesn't particularly matter, a result is a result. https://loopstudios-test.vercel.app/

---
### Day 19: December 08, 2022 

**Today's Progress**: Today, I began and finished the third TailwindCSS project 'shortly'. 

**Thoughts:** Another large project that I followed without any real issues. As usual, I continue to dislike that Brad uses space-y-[x] as opposed to using flex: gap, as it pushes elements over to the right, making groups of elements un-centered, especially noticeable in mobile view. I'm really beginning to see the repeated classes now and their use-cases in different layouts; Brad showed a great example of using flex-column-reverse, which I had not seen before. This allowed me to have text on the left with an image on the right in desktop view and the image above the text in mobile (column) view. I once again used the hamburger menu code from the previous project and I also used a little JavaScript to code some validity functionality into an input element using regex. Overall, I left the project feeling comfortable, though I will note that I continue to feel slightly lost at times keeping track of the amount of divs and the layout; I tend to spend a lot of time in the devtools to help with this. https://shortly-test.vercel.app/

---
### Day 20: December 09, 2022 

**Today's Progress**: Today, I began and finished the fourth TailwindCSS project 'Testimonial Grid'. 

**Thoughts:** This particular project was quite small and did not take long to complete, but it did however finally use Grid for the layout which answered a lot of questions that I have had throughout the course until this point. E.g. Not using Grid in the loopstudios project and why Brad may have chosen not to use Grid. It also obviously finally showed me the tailwind syntax for Grid, which just seems to use 'span'. Things to note though, Brad did not use the 'order' Grid syntax that would normally be used with vanilla CSS, but instead used a mix of 'hidden' with different breakpoints to order his layout accordingly. I thought this was a rather 'round-about' way instead of just using the 'order' syntax. I was also introduced to plugins that can be added to TailwindCSS, such as the line-clamp plugin in this example. Line clamp essentially shortens a container to a specified length and allows a 'see-more' option to be added to display the rest of the text. However, I did not see a 'see-more' option which I'd imagine must be added manually by myself, so this is still a grey-area for me of which I will need to look into in the future.

---
### Day 21: December 12, 2022 

**Today's Progress**: Today, I began and finished the fifth TailwindCSS project 'Fylo'. 

**Thoughts:** This project followed a pretty typical coding style to the previous projects in terms of layout and containers/setions, but with the addition of a light and dark mode button in the header, of which was a lot of fun to develop! The button uses JavaScript for its functionality and even goes as far as storing the 'theme' in the browser's local storage as to allow the theme to persist after closing the browser. I will absolutely be using this in future website projects, as I personally struggle to use websites without a dark theme. As usual, a lot of flex containers that we set to column for the sake of responsive design, that we then style into medium sized screens and up; I do not believe I have yet specifically styled a screen for large and above? I found the footer easier to follow in terms of div structure this time around, though this footer was not particularly complex. I need to remember that there always needs to be one main container that will switch its flex-direction based on the size of the screen. I also found it interesting that Brad styled the main content container using padding to be approximately the size of a large desktop screen, as opposed to just using 100vh? I can only imagine that he did this to avoid the trouble of the main content container shrinking too much on phone screens. Overall, this was a very fun project that has a lot of re-useable code, that I certainly plan to re-use in the future. 

---
### Day 22/23: December 13/14, 2022 

**Today's Progress**: Across 2 days, I began and finished the final TailwindCSS project 'Bookmark'. 

**Thoughts:** The last project was surprisingly large and included a variety of components on a single site that I have not used before, such as tabs, coloured divs for the sake of the design (that disappear at certain breakpoints) and even an accordion for a FAQ section. Once again, most of the site followed a very typical TailwindCSS layout in terms of sections and containers, followed by flex containers that use breakpoints for responsiveness. However, due to the components used in this project, a decent amount of JavaScript was required for both the 'tabs' functionality and also the hamburger menu once again. I enjoyed using JavaScript to add functionality for the tabs, as it was a lot of fun to finally see some extra JavaScript in action to manipulate the DOM. I felt quite confident with most of the JavaScript, but there were several syntax that I have not encountered before, such as 'children[0]' and 'getElementByClassName'. I followed the logic of the code as best I could and took some time to research the syntax I am not familiar with, as as usual, I'd like to re-use this code in future projects. I also used a basic if-else statement at the end to switch out 2 different logos depending on whether or not the hamburger menu is open; this used another unfamiliar syntax 'setAttribute' which I can see being very useful in the future. With this last project complete, I am done with the course! I had wanted to learn TailwindCSS for a very long time as it seems to be the industry standard, along side Bootstrap of which I have also learned. I still have a long way to go with Tailwind but I'm certainly feeling more confident with its use and syntax. Back to JavaScript!

---
### Day 24: December 15, 2022 

**Today's Progress**: After finishing the Udemy Tailwind course, I started/finished working on a landing page for the company that I am currently working for. 

**Thoughts:** It was quite a drastic change going from follow-along projects to suddenly designing a landing page from scratch. I found that I did not particularly get very stuck with the syntax though, that seems to have stuck after a week of constant Tailwind projects, but I did get stuck on remembering how certain elements behaved, such as containers. I forget sometimes that, Tailwind being as low-level framework, does not auto-center anything, as opposed to Bootstrap which does, of which I have experience with. The first hurdle I encountered was actually inspiration for a design, not the code, followed by appropriate images that can be used for free, that will suit the design I had in mind. Originally, the design I had in mind was a single page, clean/sleek website that all fit within a screen viewport. Unfortunately, I did not have as much space as I had hoped for and had to introduce a scrollbar and button that would navigate to a 'previous projects' section. The second hurdle I encountered was SVG images not loading. I had spent a significant amount of time trying to Google why SVGs would not load within the browser to find that my directory was pointing to 'images' and not 'Images'. I thought I had learned my lesson about capitalising directory names long ago, but apparently not! I had contemplated many times whether or not to add some JS to the page to make the site more dynamic-looking, but opted against it when I realised that Tailwind itself has some very sleek pre-made animations that don't require much tweaking and can be added straight onto the element itself. This way, the site isn't 'overloaded' and retains its clean / simple style. Overall, I'm quite happy with the site, though I naturally feel like I could do more/better and potentially change some things around.. https://casoftware-landing-page.vercel.app/

---
### Day 25: December 16, 2022 

**Today's Progress**: With the Tailwind course/landing page complete, I returned back to The Odin Project course in hope to get back to using JavaScript asap to avoid feeling too rusty. I've learned about ESlint and set it up for my own use in my Dev environment, followed by watching several videos on JavaScript Object-oriented programming and what NPM is and deep-dived into some of its uses/syntax.

**Thoughts:** To be completely honest, I'm quite intimidated by The Odin Project right now as I haven't used JavaScript in a while and I'm on to the more advanced JavaScript concepts/features. I'm certainly not feeling confident about the upcoming JS projects. I attempted to follow The Odin Project's guide on installing and using ESlint, but it assumed knowledge of NPM, which I did not have, and so I was only able to set it up using a YouTube guide that took me through the installation process step by step. My concern is that, even though I now have ESlint set up in this temporary project folder that was used for the sake of the video, how do I now use ESlint on future projects? Do I have to begin the process all over again? In hope to answer these questions, I watched a full video on NPM, but I unfortunately still did not learn how to move ESlint over to other projects. I did, however, learn about the difference between local and global packages, which may be the asnwer to my questions tomorrow when I begin my new projects. It is almost relieving to finally have a better understanding of the commands that I'm constantly told to type into the terminal by most of the tutorials I follow. It's a shame that none of those tutorials went into greater depth about NPM.


## [10-day break due to illness and Christmas holidays]

---
### Day 26: December 27, 2022 

**Today's Progress**: Moving back to The Odin Project course, I continued with the advanced JavaScript section which now has me covering more advanced concepts of Object Oriented Programming. Today, I mostly researched and learned about prototypical inheritance/object constructors.

**Thoughts:** I had only briefly covered Object literals in a past JavaScript course during my first 100 days of code challenge. The concept of object constructors and prototypical inheritance are new to me. I feel somewhat confident that I understand the concept, but I was overwhelmed by the many number of ways that you can essentially get to the same result of creating an object prototype. I personally liked the syntactic sugar of ES6 'Classes' but the Odin Project, at least for now, does not suggest the use of Classes. I definitely need to play around with prototypes; more specifically, I need to better understand the prototype chain and feel more confident in creating a prototype for an object.

---
### Day 27: December 28, 2022 

**Today's Progress**: I spent several hours today watching videos on OOP in JavaScript. The videos mostly covered the use of Object.create and a general overview of what OOP is and why it is used.

**Thoughts:** I now have a much better understanding of why we use OOP in programming and I learned about the 4 principles of OOP: Abstraction, Ecapsulation, Inheritance and Polymorphism. I'm still not confident in my ability to use OOP, so I will be spending tomorrow following an OOP section of a JavaScript course. I am doing this in preparation for a OOP project within The Odin Project course that I hope to start within the next few days.

---
### Day 28: December 29, 2022 

**Today's Progress**: Continuing to learn OOP, I have returned to a JavaScript Udemy course that I first started earlier in the year. I completed several sections on prototypal inheritance.

**Thoughts:** As usual, I found that the lectures from the JavaScript Udemy course cleared up a lot of misunderstandings I had with OOP, and I'm only 2 lectures in! A great example of this is the fact that constructor functions themselves don't have a prototype, even though the syntax makes it look so (Person.prototype). What we're essentially saying here is 'the prototype of objects created using the Person constructor function'. It was also interesting to learn that JavaScript doesn't really have traditional 'classical OOP' classes and so it's important to learn some of the distinctions in the terminology. There's seemingly A LOT to OOP and I'm finding it somewhat overwhelming so far and I'm especially intimidated by The Odin Project OOP project that I will need to complete soon.

---
### Day 29: December 30, 2022 

**Today's Progress**: Today I continued with the JavaScript course on OOP. I learned more about prototypical inheritance and learned about new concepts such as the prototype chain and prototypical inheritance on built-in objects.

**Thoughts:** Although I feel that I've developed a good understanding of prototypes and its uses, it wasn't really until the lecture on 'Prototypical inheritance on built-objects' that I've really began to see the true potential of prototypes. The lecturer answered a lot of questions that I've had for a long time, such as why we have access to some methods by default with JavaScript. Functions themselves and even Arrays are objects within JavaScript, all of which are created through a much higher-level constructor function, in turn causes our Arrays to inherit methods from that higher-level prototype. This is why we can use methods such as .push() .pop() etc on our arrays! The lecturer even explained that we can in fact create methods and store them in our higher-level Array constructor function, but it is bad practice to do so in case JavaScript is updated to include a method name the same as one you may have created, breaking your code. Very informative lectures.

---
### Day 30: December 31, 2022 

**Today's Progress**: Further lessons on OOP in JavaScript today, I completed a coding challenge and finished a lesson on ES6 classes.

**Thoughts:** I did not find the coding challenge very difficult and completed it quickly as I found it was mostly recalling syntax; I was required to create a function constructor that accepted 2 arguments, followed by creating 2 methods stored in the prototype of that constructor. I did this by using 'Car.prototype.method' Moving on from the coding challenge, I learned about ES6 classes which is essentially just a much nicer way of storing object constructors and their prototype methods in a neat code block (Syntactic sugar). I much prefer ES6 classes as I find it easier to read, follow and use in comparison to just having single lines of code that store methods in the prototype outside of any code block.

---
### Day 31: January 09, 2023

**Today's Progress**: Continuing with lessons on OOP in JavaScript, I followed along with 2 more lectures: Setters & Getters and Static methods.

**Thoughts:** I have a lot of unanswered questions on how Setter and getters work and I am not very confident on the topic so far. Whilst I feel like I have a 'decent' idea as to how they work, I'm not particularly sure on the common uses of them; the lecturer used them for property validation. I plan to watch a few more lectures tomorrow on Setters and getters in hope to see more examples. Static methods on the other hand seem quite straight forward, essentially just a method created within the constructor function and not inherited on to other object instances as the method is not in the prototype; supposedly static methods are useful for creating constructor helper-functions, but again, my inexperience disallows me from knowing a specific case in which a static function could be handy. I don't plan to be on these 2 subjects too long as I'd like to finish the OOP section asap to re-continue with The Odin Project.

---
### Day 32: January 10, 2023

**Today's Progress**: Continuing with lessons on OOP in JavaScript, I followed along with 2 more lectures: Object.create and Coding challenge #2.

**Thoughts:** No real issues with following the lecture on Object.create or completing the coding challenge. Object.create is just another way to directly link an object to a prototype. E.g. const steven = Object.create(PersonProto). I'm feeling a little overwhelming with the fact that there are 3 ways so far add code to prototypes. According to the lecturer, Object.create is the least common method of doing so, but is necessary to learn as it is occasionally used. I'm personally still more comfortable with ES6 Classes and I'll continue to use Classes over the other methods. The coding challenge was simply taking code from the previous coding challenge, except this time adding a get method, and a set method. The get method returns the car's current speed divided by 1.6, giving us MPH. The set method multiplied the speed by 1.6 once again giving us KMPH, allowing us to have access to both MPH and KMPH using the property name. Overall, feeling quite confident with the lessons so far.

---
### Day 33: January 12, 2023

**Today's Progress**: Continuing with lessons on OOP in JavaScript, I followed along with 2 more lectures: Inheritance between classes: constructor functions and Coding challenge #3.

**Thoughts:** Once again, I do not feel like I had any real issues with either the lecture or the coding challenge itself. The lecture on inheritance between classes was mostly emphasising how we are able to use the call() method to link the 'this' keyword back to the original parent constructor whilst using a child constructor, so that we are able to avoid repeating code. It is through this way that we are able to add child classes with both additional parameters and the parent constructor function parameters/code. The coding challenge required me to put the prior mentioned into practice. I created two constructor functions, one parent and one child, in this case it was "Car" and "EV" (Electric Vehicle). The Car constructor function passes two arguments 'make'/'speed' whilst the EV constructor function passes the same arguments with the additional argument of 'charge'. I also used Object.create to link the prototypes between the two constructors.

---
### Day 34: January 13, 2023

**Today's Progress**: Today I finished the OOP section in my JavaScript Udemy course. The lectures I completed are the following: Inheritance between "classes": ES6 Classes.

**Thoughts:** This particular lecture was essentially the same as the previous lecture on inheritance between classes, however now with the addition of ES6 syntactic sugar 'Classes'. I was already a fan of ES6 classes as I find it much easier to read and use, so I'm very excited to see that Classes go even further and make prototypical inheritance even easier to use and read. I'll definitely be opting to use Classes in the future; although I by no means feel very confident in my ability to program using the OOP paradigm yet. I feel like I've also developed a better understanding of the Call() method/ 'super' keyword with classes. Overall, I've found this lecture very informative and I'm looking forward to future projects using Classes.

---
### Day 35: January 16, 2023

**Today's Progress**: Continuing with lessons on OOP in JavaScript, I followed along with a lecture: Inheritance between "classes": Object.create, Another Class Example, Encapsulation: protected properties and methods, Encapsulation: Private class fields and methods, Chaining methods, ES6 classes summary and finally a Coding Challenge (#4).

**Thoughts:** Today was a particularly productive day, a lot to go through! It was very interesting to see in the first lecture, Inheritance: Object.create, that you can essentially just create literal objects with methods and make that the prototype of other objects using Object.create; essentially just linking objects to other objects as you see fit, there's a beautiful simplicity in it, even if it isn't the 'orthodox' way of creating prototypes. 'Another Class Example' emphasised that we can store other data types inside of the constructors, such as empty arrays and also call methods within methods to avoid repeating code whilst still getting the desired result. Following this, I learned about the 'convention' of using underscores to define whether or not a particular property or method should be 'protected' within its enclosed classed. E.g. _methodOne. As JavaScript does not have actual protected classes, these properties and/or methods can be accessed outside of their classes, but the idea is that other developers would see that it shouldn't be accessed or manipulated outside of its class. After this lecture, I learned about actual privatised fields and methods within JavaScript as the syntax is currently in development and could potentially enter the language with browser support in the near future. I learned about the 8 different, proposed fields and methods such as public/private fields/methods. We can make properties/methods private by adding # to the beginning instead of underscore, which gives that property true privatisation, returning an error if we try to access that property outside of its enclosed class. Extremely useful and a great direction for the language in my opinion, I hope its added soon so that I may use it in future projects. Edit: There was also a small lecture on chaining methods which is useful to note. Methods return undefined if there is no return keyword. It is important to make the method 'return this' if we want to chain methods together.

---
### Day 36: January 18, 2023

**Today's Progress**: Having finished the OOP section of my JavaScript Udemy course, I've returned to The Odin Project to work on a project without any 'hand-holding'. The project is 'Book library'.

**Thoughts:** Typically, I find myself staring blankly at the screen pondering how I'm going to approach the project from scratch. I decided to first sketch out the project on paper with pencil so that I had an idea as to how it will look. Recently having spent a decent amount of time learning Tailwind CSS, I decided to use Tailwind for the CSS, which took a little re-familiarisation, but has allowed me to follow my design almost perfectly, including mobile responsiveness. The project is missing the main JS OOP functionality that will allow me to add books, but I've added some basic JS that allowed me to implement a light and dark mode to the site. Overall, I'm very happy with how it looks and I'm looking forward to getting into the logic.

#### [3 Week break due to other commitments]
---
### Day 37: February 11, 2023

**Today's Progress**: Finally able to get back on the horse! Today, I've began easing myself back into The Odin Project course by taking some time to re-familiarise myself and took a small dig at the book library project I had begun on Day 36.

**Thoughts:** Admittedly, I feel very rusty having taken such an extended break and struggled for a few hours to work out where I had left off with the project and where abouts I had gotten up to. Thanks to this coding log, it was much easier than anticipated! I firstly returned to my TailwindCSS and decided that I am happy with the front-end design so far. Following this, I returned to the JavaScript to make sense of what I had so far and began working on the 'Add Book' functionality. The first issue I ran into is that my '+' button was refreshing the page upon click and not allowing me to properly see the text I was logging to the console; I took some time to research the issue and found that it is because the button is within a form and its default behaviour is to 'submit' and refresh the page. The first solution I had found was to simply declare the type of the button in the HTML to 'button', thus no longer making it a type of 'submit'. The second solution I found was to add the method event.preventDefault() to the JavaScript code that was being executed upon the click of that particular button. I opted to use preventDefault() instead of changing the type of the button. I still have a long way to go with the project, especially since the aim of the project is to specifically use OOP, of which I haven't really done yet. Looking forward to finally using some ES6 classes!

---
### Day 38: February 14, 2023

**Today's Progress**: Refreshing myself with certain JavaScript concepts via Brad Traversy's JavaScript course.

**Thoughts:** Trying very hard not to stay out of 'tutorial hell', hoping to re-familiarise myself with concepts that I'll be using in my current project so that I'm not unnecessarily studying concepts that I've already taken several courses on. Currently going over destructuring and eventually Object prototypes once again before I continue with my book library project.

---
### Day 39: February 15, 2023

**Today's Progress**: Continuing with Brad Traversy's JavaScript course to refresh my knowledge.

**Thoughts:** I'm really enjoying Brad Traversy's course, been a big fan of his courses since I completed his TailwindCSS course. Today I mostly spent my time briefly going over more concepts and diving deeper into destructuring as I did not feel very confident with it. I also spent time looking into some 'under the hood' concepts again such as execution context, hoisting (specifically the difference between let and var) and the temporal dead zone. However, I would like to get back to developing projects again ASAP.

---
### Day 40: February 16, 2023

**Today's Progress**: Continuing with Brad Traversy's JavaScript course, I covered a few older areas and decided to have a go at some coding challenges, of which included objects and functions.

**Thoughts:** Thankfully, I found myself feeling very confident with these challenges; I say thankfully as they are your typical 'intro' challenges to these particular JavaScript concepts. Although, it definitely didn't hurt to brush up on the concepts as I did in fact find myself a little stuck with arrow functions, forgetting the syntax, and also found myself unable to remember how to use an Immediately Invoked Function Expression (IIFE). The most notable challenge for me however, was definitely on destructuring, as it's something I'd like to understand and use more. Again, fortunately I did not have any struggles with the destructuring challenge and found that my solution was the same as the lecturers! 

---
### Day 41: February 18, 2023

**Today's Progress**: More JavaScript course sections and some challenges!

**Thoughts:** As to avoid 'tutorial hell', I find myself still mostly picking and choosing certain topics that I'm not familiar with as opposed to just watching the entire course and wasting time, potentially. Today, I covered quite a wide-range of topics, but most of today's lectures covered high-order functions such as forEach, filter, map etc. I also briefly covered some loops that I'm not very confident with, such as for...of and for...in loops, which I now have a much greater understanding of and will likely use in my up-coming projects. Overall, I'm finding that my current method of learning is working very well.

---
### Day 42: February 19, 2023

**Today's Progress**: Today I completed all of the lectures on high-order JS functions and the coding challenges following them.

**Thoughts:** I recall having issues with high-order functions when they were first introduced to me during a previous JavaScript course. I was using them from time to time in my personal JS projects, but I struggled as I didn't fully understand the syntax/results or the use-cases. Brad Traversy has explained the high-order functions very clearly and provided various examples as to where they may be useful and how they interact with other high-order functions to get very specific values. I'm feeling much more confident using them and I didn't have any issues completing the coding challenges at the end of the section that required me to use all of the high-order functons that I had learned in the previous lectures.

---
### Day 43: February 22, 2023

**Today's Progress**: Having completed the array section of the JS course, I moved on to the DOM manipulation section.

**Thoughts:** I was very sceptical of doing this section in the course as I feel that I've covered most of it before and would only be repeating myself unnecessarily. Surprisingly, from the very first lecture, I found that I was learning new things, encouraging me to continue with the DOM section. I learned how to traverse the DOM using properties such as 'parentSibling' or 'childSibling' to select certain elements. I was also taught the difference between elements and nodes and how to use the node to my advantage if need be. I especially liked that Brad explained his preferences as an experienced/senior developer and broke down how he personally would have approached a certain coding challenge, which entailed him breaking one function up into several functions for more re-useability. I felt very confident throughout this section with regards to following and understanding, but I do not remember a lot of the syntax or certain ways of achieveing vertain results that Brad had done throughout a lot of these lectures. I struggled on the coding challenge at the end that required me to create a 'insertAfter' function by using the already existing insertBefore function. Although I did not complete this challenge by myself, I understood the result that Brad came to.

---
### Day 44: February 26, 2023

**Today's Progress**: 3 more DOM manipulation lectures/coding challenges and making a start on event lectures. 

**Thoughts:** Even though I have covered DOM manipulation in a previous JS course, it's surprising me how much more is either becoming clearer to me, or just how many new concepts/syntax I am learning. I learned more about removing and replacing elements, but more specifically, Brad breaks down several ways that an algorithm can be solved using the new syntax. Even better, Brad continues to refactor the code into simpler blocks of code and explains why and how. Although my coding solutions are not always the same as Brad's, I get the same result and it's normally a solution Brad covers, to which he then continues to improve upon. I feel that I am learning a lot more from this course than previous courses and I plan to finish the course in its entirety. I have also made a start on 'events' and covered 'onclick' and event listeners, of which I am familiar with, but once again learning more!

---
### Day 45: February 28, 2023

**Today's Progress**: I continued with the events lectures and completed a coding challenge. 

**Thoughts:** Again, although I've completed several lectures on events from previous courses, I continually find myself learning more with Brad's course. Brad lists out a lot of different listening syntax but clearly explains what they all do and the differences between them. Although this is quite overwhelming, as he goes through upwards of 10 of them, it's complimented by the fact that Brad took time to create markdown notes on all of his lectures to be used as future reference notes. Other lectures on events include mouse events, keyboard and inouts events. Following these lectures, I was required to complete a coding challenge that would put all of the previous mentioned into practice. The challenge was to add the logic to a very basic UI that displays the letter pressed on the keyboard, along with the event code for that letter as well as the event keyCode. I struggled on this challenge, as I was able to somewhat get the logic to work, but my method resulted in other elements being removed from the parent element. E.g. The boxes would correctly display the keys I press, but the titles would be removed. In the end, I followed Brad's method and learned what I could have done better; I realise now that I should have either used innerHTML and included all of the HTML code to ensure that all of the other elements reamin upon a keypress. Or alternatively, the preferred and cleaner method of having the elements essentially re-created everytime a key is pressed. (innerHTML is a bit of a lazier method supposedly)

---
### Day 46: March 02, 2023

**Today's Progress**: Today I completed several more lectures within the events section. Today included lectures on Input events, Forms and submission and formDAta object, event bubbling and lastly event delegation. 

**Thoughts:** Handling form data is a topic I haven't covered much of and recently, in a previous project, found myself stuck for the first time on a form continually submitting and refreshing the page; I solved this at the time by using e.preventDefault(). I was a little disappointed that this wasn't covered in any of the courses I had done at the time, but as usual, Brad continues to impress and covers this and more in his lecture on form data. He goes even further and also clearly shows me how to use the formData object to build an iterator that I can then loop over using a for...of loop to get the data I need. The most educational lectures for me today, however, was definitely event bubbling and event delegation. Both of these lectures were relatively small and I had covered them briefly in other courses but didn't feel particularly confident, but that has certainly changed today after Brad's lessons. I find event bubbling very easy to understand now and it's very helpful to know that I can use the stopPropagation() method to prevent an element bubbling. The lecture on event delagation was even better as Brad went into detail on a question that had been on my mind for a very long time. Do I apply event listeners to each element using querySelectorAll, or is there a more efficient way to do it? In Brad's example, rather than applying an event listener to every single 'li' tag using a forEach loop, he targets the 'ul' parent instead and uses an if statement to check if we e.target an 'li' within that 'ul'. This is a more efficient way of using event listeners.

---
### Day 47: March 03, 2023

**Today's Progress**: I finished up the last section on events 'window and page load events'. Following this, I made a start on the courses first project. 'Shopping List'! 

**Thoughts:** The window/page load events lecture was quite straight forward and just essentially showed how the script is loaded depending on its placement in the HTML file and various methods of placing that script. For example, using 'defer' to allow us to place the script in the header tag, whilst still having the script load as if it were placed at the bottom of the body tag. I've built a few projects very similar to a shopping list in the past, but I'm finding, naturally, that the code is a little more complex than I anticipated. The project is using what we've learned so far, so most of it I am following without any issues, but there are a few things that I would not have been aware of. An example of this is Brad creating a function called 'checkUI' that continuously checks to see if our shopping list has an item in it, and if not, we remove some of the surrounding elements such as the filter bar and clear all button. This is just to make the shopping lsit a little more dynamic without too much complexity. Overall, I'm following along and I understand the code, but I feel like I definitely would not have written the code the same way, even though Brad's method of coding is extremely clean. I hope I'll be as clean with my code in the future! 

---
### Day 48: March 06, 2023

**Today's Progress**: Continuing with the Shopping List project, I covered filtering items, additems to local storage, displaying those items in localsotrage and lastly, removing the items from local storage.

**Thoughts:** Local storage is a subject I've wanted to cover for a very long time and I found the lessons very easy to follow. I feel comfortable with local storage and I'm quite confident that I can use what I've learned today in my own future projects if required. However, I did run into trouble today and found myself stuck for a considerable amount of time. I unfortunately found that my list items would sometimes be removed from local storage when deleted from the list, and other times they would not be removed. I spent a while checking my code, especially the chain of functions that remove the list items; I tried switching my 'filter()' function for a 'pop()' function which sadly gave the same result. I also round that, ocassionally, my forEach function that loads on DOMContentLoad to display the local storage items would also sometimes break as the variable being looped through was not an array? I tried adding an explicit check using 'isArray' which would convert the variable to an array if it was false, but this also only band-aided the problem temporarily. I continued to dive deeper and eventually found that the issue came from some code I added myself earlier in the course videos, which capitalises the first letter of any added list items. The local storage items were being checked against the textContent of the list items, which means that the list items always had a capital letter. However, local storage stores whatever was input into the submit field reagrdless of capitalisation. I fixed the problem by ensuring that all items added to localStorage were added in lower-case followed by ensuring that the list items textContent were also set to lower-case, guaranteeing the check logic and allowing the filter function to work!

---
### Day 49: March 07, 2023

**Today's Progress**: Today I finished the shopping list project and deployed it to Netlify. I added functionality to my shopping list that allows me to edit and update the list both in the DOM and within local storage. There was also a quick video on preventing duplicates within the list.

**Thoughts:** I followed the tutorial throughout without any real issues except for on day 48, wherein case-sensitivity had me stuck on filtering my shopping list and local storage for a while. Overall, I think that this project has been very educational for me, and not just because I had used a lot of what I had learned in previous lessons, but because I was able to watch a very experienced programmer tackle the project. The way Brad structured his code is quite unique and I found it very easy to follow along and understand and I will try to structure my code similarly in the future. In saying that, I did however find that the complexity of the code increased very quickly and began to almost feel like I was well out of my depth; I often needed to pause the lectures to break down what was happening within the code, even though Brad was explaining it as he went. There were many times I felt as if I was just 'following along' as opposed to actually taking something in, which is something I strongly try to avoid when following these lectures. Definitely not feeling confident or 100% with all of the code that I have written, but I'm going to contineu to push on with the course and potentially return to previous lectures at a later date.

---
### Day 50: March 08, 2023

**Today's Progress**: Following the shopping list project, I've made a start on the Asynchronous JavaScript section of the course. So far covering, 'Thread of Execution', 'How Async JS works', 'setTimeout and clearTimeout functions', 'setInterval and clearInterval functions', and lastly, 'Callbacks'

**Thoughts:** Asynchronous JavaScript is a completely new topic for me, but so far I feel that I've been able to follow the lessons without trouble. I definitely have a better understanding of JavaScript as a programming language after the lessons on Thread of Execution and How Async JS works; it's nice to have a deeper understanding of why certain things work the way they do and I can imagine it coming in handy later down the line. The lessons on the various Async JS functions were a lot of fun and I'm looking forward to eventually being able to use them in a project, as they look to be a very powerful tool in the programmer's arsenal. Admittedly though, the 'Callback' lecture was much more complex and somewhat dwindled my confidence on the topic. Brad displayed a very specific example that included 2 functions that run at different times, causing only one function to do its job and display elements on the DOM. This was solved by creating another parameter in the first function and then invoking that parameter within the same function. We would then pass in our second function as an argument into the first function. I found this quite a complex concept, even though I understand why it works. I get the feeling that Async JS is going to be quite a hurdle.

---
### Day 51: March 09, 2023

**Today's Progress**: Today I continued with the Async JS lessons and completed several more lectures, including a small project challenge! I covered 'HTTP Requests', 'DevTools Network Tab', 'AJAX & XHR Object' and lastly, the 'Chuck Norris Joke Generator project challenge'.

**Thoughts:** A majority of the lectures today didn't really include much 'code along', but instead were mostly theory lectures that I took notes on. The AJAX & XHR object lecture did require me to code-along and to use APIs, of which I'm really excited to finally be doing. 'APIs' is a word I've been hearing a lot over the last year of my studying, but I had yet to actually reach a lesson on the use of APIs. In the small coding project challenge, I had to use a Chuck Norris Jokes API to display a random joke on screen after a click of a button; I didn't have any real issues with this challenge and found myself completing it very quickly, even though it intimidated me at first. I am really looking forward to using more APIs to create some interesting projects in the course. I am especially excited to, hopefully, become experienced enough to use APIs in my own projects. 

---
### Day 52: March 11, 2023

**Today's Progress**: Continuing with the Async JS section of the course, I covered 'Callback Hell', 'Promises', 'Callback to Promise Refactor', 'Promise Chaining' and lastly 'Promises vs Callback Hell'.

**Thoughts:** The lectures on callbacks continue to stump me a little as I find the concept a little difficult to follow at times. In 'callback hell', Brad creates an example of how we can use callbacks in our functions to ensure that certain operations are completed in the correct order, but this requires multiple nested callbacks, eventually creating a 'callback hell'. A solution to this is covered in the next lecture 'Promises', which is a topic I've been looking forward to covering for a long time! I do not feel confident on Promises, but I understand how and why they are used, especially when retrieving data from an API or general HTTPRequests. Due to my 'not-so-confident' understanding on Promises, I also didn't really feel like the following lecture on Promises were very clear for me. However, once again, I do understand the reasoning behind the different uses; Callback to promise refactoring, self-explanatory, avoiding callback hell; Promise chaining, replacing callback hell with a clearer syntax, making nesting look cleaner; Promises vs callback hell, clearly distinguishing the advantages of using Promises over too many callbacks. I feel like I have a long way to go with Promises.

---
### Day 53: March 13, 2023

**Today's Progress**: Today I finished the Async JS section of the course, finishing up with 'promise.all()' and made a start on the next section that covers 'fetch API' and 'Async await. In the new section, I covered 'fetch basics' and finished a 'random-user mini project'.

**Thoughts:** I can see how useful promise.all() will be, as it is essentially the same as nesting callbacks/using repeat .then() methods except much cleaner with an easier to use syntax in my opinion. I'll definitely try to use promise.all() for the cases in which I need several .then() methods. I continue to lack confidence with promises, but once again, I understand the concept. After this, I covered a few basics on 'fetch', which is a more modern method of fetching data from an API that automatically creates a promise for us; in previous lessons I had covered the XHR object to retrive data from APIs but this is an older method of doing so. I then started and finished a follow-along mini project that used 'fetch' to retrieve data from a 'random user' API that simply generated random info that I could then display on the DOM via innerHTML. I'm enjoying using APIs and I'm looking forward to making a start on the more complex projects that utilise APIs.

---
### Day 54: March 14, 2023

**Today's Progress**: Following completion of the mini project yeterday, I continued with the Fetch/Async Await section and completed 'Fetch options: method, body header' along with starting a new mini project: 'Typicode todos'.

**Thoughts:** Slowly but surely, 'fetch' becomes a little more complicated as Brad delves deeper into the full potential of 'fetch'. In the lecture on Fetch options, Brad covers several other functions of fetch and how we can use it to our full advantage when dealing with public APIs. I'm not yet particularly confident overall with using fetch myself, but I definitely feel more knowledgeable on the subject. The new mini-project that I have started 'Typicode todo' has me feeling a little overwhelmed as the focus of the project is to obviously use fetch and its full functionality to both retrieve and post data from/to an API and display it on the DOM. Whilst I haven't had any problems following along so far, I find myself sometimes struggling to follow along with the structure of the code and what is doing what. I often pause the video to go back over the code several times to figure out why Brad did something a certain way. Overall, keeping up with the lessons, feeling more knowledgeable, but also feeling easily overwhelmed at times.

---
### Day 55: March 15, 2023

**Today's Progress**: Continuation of the 'typicode todos' project - part 2.

**Thoughts:** Part 2 of the project focused on using fetch to now also update and delete data using the 'PUT' & 'DELETE' method. I feel like I have a somewhat decent grasp on the use of fetch itself, but I again found myself feeling a little overwhelmed with some of the code Brad has used. This is sometimes just simply trying to understand exactly what is happening in a particular function and then following the callstack/queue of invokes. I'm also confused by the 'init' function that Brad placed at the bottom of the code that contains the event listeners; the init function is invoked directly after at the very bottom of the code. The event listeners persist once the function has been invoked once? I'll need to research this more.

---
### Day 56: April 23, 2023

**Today's Progress**: Returning from an extended break, I mostly spent today refamiliarising myself with the last topic I had covered.

**Thoughts:** Naturally, having taken such a long break, I'm lacking a lot of confidence and I'm very unsure as to how I'm going to re-continue with my studies. I believe that the best plan of action is to cover the last topic I left off at in my course and continue onwards. I went back through a few hours of lectures and I now remember where I left off, but my confidence with regards to applying that topic is low. Even though I haven't coded for a long period, I think it would be more detrimental to go back on myself and prevent progress. The topic I refer to is mentioned in the previous, day 55.

---
### Day 57: April 25, 2023

**Today's Progress**: Continuing to refresh myself on where I had left off, I spent today once again re-watching previous lectures.

**Thoughts:** Though it feels like it's definitely helping to re-watch previous lectures, I feel that maybe simply re-watching them isn't enough and that I should in fact go over these lectures once again and follow along with the coding. The more previous lectures I watch, the more that I feel like I should continue to go back on myself as a lot of these previous topics are lost to me.

---
### Day 58: April 26, 2023

**Today's Progress**: I took yesterday me's advice and began coding along with previous lectures.

**Thoughts:** Coding along with lectures I'd already covered in the past is definitely taking steps backwards, but I feel like it's best to invest a little extra time to ensure that I'm fully prepared to tackle the upcoming projects in the course as I'm quite certain that I'm going to find myself stumped at certain parts, failing to understand why the lecturer did things a certain way. This begs the question though, how far back should I go? Currently I'm considering the entire section on Async JS, High Order Array Methods and Fetch API/Async Await.

---
### Day 59: April 28, 2023

**Today's Progress**: Today I covered 5 more lectures in the Async JavaScript section of the course. This includes: setTimeout & clearTimeout Functions,
setInterval & clearInterval Functions, Callbacks, ,Crash Course On HTTP Requests and lastly, DevTools Network Tab

**Thoughts:** As mentioned in day 58, I'm feeling much more confident gonig forward re-doing some of these lectures due to the large break I had taken earlier this year. Rewatching these lectures and following along with the code once again feels a lot like re-watching a movie, as I'm discovering things that I did not notice before. As eager as I am to make progress with the course, it's been very refreshing to go over these topics again and I feel like I've developed a new confidence in their use. I'm certain now that I'll be covering other, more important topics that I had covered in the past.

---
### Day 60: May 03, 2023
 
**Today's Progress**: Continuing with lectures in the Async JavaScript section of the course, today I completed a lecture on AJAX and XHR Object followed by a mini-project Joke generator challenge.

**Thoughts:** I recall the AJAX and XHR lessons well from the past and didn't have any issues with following the lecture. Whilst it is still useful to know the AJAX and XHR method of Async JS, it is also an outdated method and not something I'll particularly spend much extra time on. I was able to once again complete the Joke generator challenge by myself without following the lecture, which I'm happy with. I did hit a small snag wherein I forgot to place the section of code that 'opens' XHR and placed it outside of my function that was being invoked when 'generating a new joke'. I realised that this piece of code needed to run with every click of the button, not just the one time outside of the function. Other than that, everything works perfectly and I'm feeling confident moving forward. 

---
### Day 61: May 09, 2023
 
**Today's Progress**: Continuing with lectures in the Async JavaScript section of the course, today I completed a lecture on Callback hell, Promises and Callback to Promises refactoring.

**Thoughts:** Considering the last time I completed the lecture on callback hell, I feel that I have a greater understanding of why it is people may find themselves in 'callback hell' and how promises are a great solution to this issue. However, promises on the other hand, I still find somewhat difficult to follow at times. I absolutely have a better understanding of the topic now compared to when I had first completed this same lecture on promises several months ago, but I clearly need to use them practically in a project. Callback to promises refactor was a nice lecture to follow, once again shows how I can avoid using callbacks with promises. Overall, I'm not 100% there with these topics but I'm feeling more confident. I'm going to avoid returning to these topics now and power forward so that I can begin working on new things.

---
### Day 62: May 13, 2023
 
**Today's Progress**: Having now caught up to where I was previously in the course, I've moved on to the Fetch API & Async Await section of the course. Today, I completed 'Fetch basics' and 'Random user mini-project'. 

**Thoughts:** The first thing that stands out to me now is that I generally have a much better understanding of promises, even if I'm not entirely confident in using them yet. Due to this, I'm more confident in my ability to use fetch API, which innately uses promises to handle data. I'm by no means proficient at using the fetch API yet, but definitely feel that I have better grounds to learn more confidently and to use it more often. The random user mini-project is a project that I had completed in the past, using the video for help now and then when I'd find myself stuck. This time around, however, I found myself unsure of where to start and took initiative with my own code once I got going with the lecture. I'm slowly finding myself able to tackle more particular issues, especially when it comes to generating and creating new elements within the DOM. 

---
### Day 63: May 16, 2023
 
**Today's Progress**: Moving on with the Fetch API & Async await section of the course, I completed the following: Fetch Options - Method, Body & Headers, Typicode Todos Mini-project part 1 and part 2.

**Thoughts:** No real issues following along with Fetch Options, Brad explains the various bits of data that we can use in our fetch requests; he briefly goes into a little more detail with regards to tokens with the Headers as some APIs require authentication. Following that lecture, I completed another mini-project by following along with Brad's code. The mini-project is a simple To-do list that manipulates the DOM by placing elements in a simple flex-wrap. We added various functionality such as the form input obviously being the title of the To-do box, left clicking the boxes to mark them as done indicated by change of colour and lastly double-clicking to remove the box from the DOM. Those functionalities also used fetch to interact with the API; POST for adding a To-do, a 'GET' to place the first 5 To-dos in the API on the DOM, 'PUT' to update the To-do and lastly 'DELETE' to delete the To-do. This project, though basic, gave me some trouble with regards to following and making sense of some of the code. I did not move on until I was comfortable that I understood how the code was functioning. More specifically, I sometimes feel overwhelmed when following a chain of functions that pass their arguments into each other, this may be because I am overcomplicating it and need to change my angle. The project has helped me understand the basics of fetch and some of its capabilities when working with an API. 

---
### Day 64: May 18, 2023
 
**Today's Progress**: Today I finished off the Fetch API & Async await section of the course. I completed the following lectures: Fetch API error handling, Async & await, Try...Catch statements, Error handling with Async & await and lastly multiple promises with Async & await.

**Thoughts:** Today was a busy day, I've finally moved on to new concepts having now covered previously watched and completed lectures in preparation for a large project that I will be beginning tomorrow. This particular section of the course has been quite overwhelming, but also enjoyable as I have been looking forward to learning about APIs. There seems to be many different ways of acquiring a response from an API, all of which with their own caveats, which is why I found some of the lectures overwhelming. There's a lot of various syntax combinations that can be used to connect to an API and handle a promise. For example, it is explained in the Fetch API error handling lecture that if we are using fetch() and .then()/.catch(), the ./then() will still run on a 404 error and the error is not caught, whereas the .then() will not run on a network error (website doesn't exist) and the error will be caught in this scenario; on a 404 error, we must use an if statement to check if !response.ok (response is not ok - ie. false) and explicitly throw a new error to be able to catch a 404 error and stop the .then() from running. I find async & await to suit my preference a bit more in terms of code layout and I think I'll endeavour to use async more often than .then(). I'm still not 100% on this section as it seems that the various syntax combinations that can be made simply end up coming down to preference and a particular coding style, which I have not developed yet. 

I'm also still not very confident with my understanding on handling the fetch responses and this is something I will be spending more time on. Try...Catch statements are relatively straight forward in concept and I'm going to try to incorporate them more often in my personal code for easier error handling. I continue to find myself overwhelmed when it comes to handling multiple promises at once as the general structure of the syntax changes quite a bit, in fact, in this lecture Brad also used destructuring to apply variable names to each response that he received from his 3 promises made in his code. This was another painful reminder that destructuring always seems to be lost to me, even though I've spent many hours studying it; I need to use destructuring more! To summarise, I've managed to follow the lectures within Fetch API & Async await section without many issues, but I'm far from confident and feeling somewhat overwhelmed by just how many ways there are to achieve the same result. I'm going to try to pay specific attention to how Brad uses the syntax from this section in the upcoming project in hope to develop a deeper understanding.

---
### Day 65: May 19, 2023
 
**Today's Progress**: I spent today on a few fundamentals such as Data Types to refresh my theory knowledge and also deep-dived into my VSCode settings in hope to make my keybinds and general use more efficient long-term. 

**Thoughts:** Not much to report today as I wanted to refresh my memory on the various data-types and build on my theory knowledge. I often find myself regularly returning to fundamental/basic theory lectures just as a quick reminder. Following this I noticed that in a lot of the lectures the lecturer only tends to use the keyboard to navigate his code and rarely uses his mouse. I could see the benefits of this, quite literally, and decided to find out how exactly he was doing it. Thankfully, Brad did have a lecture on shortcuts and commands etc, but my keybinds were completely different to his as he uses a Mac, whereas I am on Windows. In the end, I found myself asking Chat-GPT what the MacOS keybind equivalent was for Windows and worked my way from there, slowly rebinding my keys to more accessible ones. Now it's just a matter of getting used to only using the keyboard, at least now my tools are configured!

---
### Day 66: May 20, 2023
 
**Today's Progress**: Having now finished the Fetch API & Async await section of the course, I've finally moved on to the next section which is a fairly large project. The project is to create a website that utilises a movie/tv show API to create an interactice site that we can select and display movie info on. I completed the following lectures today: Theme overview and prep, API overview and API key, Page router and Active link, Display popular movies and Spinner & Popular TV shows.

**Thoughts:** Theme overview and prep was simply making the necessary adjustments and preparations to have the site ready for the JavaScript to be added. Brad had mentioned API keys/tokens many times across the lecture and so it was great to finally see what that actually meant and how to use them. It was on Page Router & Active Links onwards that things naturally became more difficult, especially since these concepts are new to me. Now that I've used page-routing, I already have a greater understanding as to how websites are able to use several interactive, independent pages; obviously, this is incredibly valuable knowledge that I can begin to include in my own projects. A few important things to note from the page-routing lecture: 

##### Page Routing
Firstly, I now know that to find the current page, I must use window.location.pathname. In the project, we've stored that into an object called 'global' as I'd imagine there's many more to add. global.currentPage now returns the current page I am. Secondly, for the page routing, we stored a switch statement inside of a init() function that loads on 'DOMContentLoaded', so that the init() function continues to run everytime the page has loaded, which is obviously important as we need the checks to be made everytime we load a new page. The switch statement checks global.currentPage to our various website pages such as '/', '/shows.html' etc and returns a simple console.log for now, to confirm that it works. Which it does!

##### Active Links
Following this, I was tasked with creating the 'active-links', the nav bar page names changing colour when it is the current page we are on. I attempted to add the Active-Link functionality myself but ultimately found myself stuck when I did not realise that a CSS class of 'active' already existed and I did not use it. I realised that I'd first need to check the currentPage against the Nav-link. I poorly attempted this by trying to store both Nav-links in a variable and using nth-child selectors. As there were only 2 links, I did not think to use querySelectorAll which is clearly the better option regardless. Following this I tried to make the if statement check the 'href' of the pages without using getAttribute('href'), which is why it inevitably would not work. I realised this early on, but I could not remember the 'getAttribute' method, so I suppose I was 'close' to solving this issue. I also realised early on that I'd need to add our 'highlightActiveLink' function at the bottom of our init() function as we'd need it to make these checks every time we change current page.

##### Display Popular Movies 
In this lecture, I'm actually using the API and displaying the top 20 popular movies on the front page of the website. Whilst a little complex and completely new to me, this was extremely fun to do, as I can only imagine just how much has opened up to me now that I can retrieve data from an API. We first created a function 'fetchAPIData' that we can use to fetch data from the API which sends off our API key every time we use it as it's required. The API url is stored in a variable, which we combine with the endpoint URL (E.g. movies/popular) to fetch the required data. I then created a function that displayed the popular movies. Using destructuring, I pulled 'results' from the returned API data that we retrieved using the 'fetchAPIData' function. Once that data was captured, I looped over it using forEach() and created a div with the class of 'card' so that the CSS is applied. The div.innerHTML is set to the original HTML used to create the 'original' cards where we now use template literals to add the relevant data from the API. We then append those cards to the parent element #popular_movies.
As a fun side project, I tried to reduce the cards from 20 to 4, but found that the API always returns 20 no matter what. After some research, the only way to do this would be to use the slice() method. I stored results.slice(0,4) into a variable and looped through that instead, thus only displaying 4 movies on screen!

##### Spinner and Popular TV Shows
The spinner was quite straight as it has already been developed, I simply had to add the showSpinner() and hideSpinner() functions inside of the fetchAPIData function before the  response and after the response respectively. This lecture was essentially the same as displaying the popular movies lecture except for a few obvious differences, such as changing the template literals that we use to access the results data. E.g. Movies use ${movies.title} whereas shows use ${shows.name}. I once again had to remove the hard-coded cards from the shows.html page so that JavaScript could populate the DOM with the divs/cards we create from the same displayPopularMovies() function. Following this, we obviously now need to add this function into our init() switch statement so that it only runs when we are on the TV Shows page. As a small adjustment, I noticed that Brad's CSS did not take into account smaller images inside of the cards which meant that some text did not sit correctly at the bottom of the card. To fix this, I applied a display type of flex to the cards and used space-between. All fixed!

Overall, this project so far has been a lot of fun. I'm now beginning to see the power of APIs and just how much is available to me. It's especially fun to be using concepts such as Page Routing and Active Links as this is essentially the back-bone of a functional website. I'm looking forward to the next lecture!

---

### Day 67: May 22, 2023
 
**Today's Progress**: Continuing with the Flixx App project, today I completed the 'Movie Details Page' and 'Details Page Backdrop' lectures.

**Thoughts:** Populating the movie details page was a little more complex as I'm now having to check the id in the html search bar. As per usual, I made a displayMovieDetails() function that will obviously populate the page when invoked, of which I then place in the page routing switch statement to ensure that this function only runs on the movie-details page.

Using window.location.search I'm able to store the movie id in a variable e.g.'?id=502356'.
As we only need the number, I can use the split() method to do so. 
split('=') will return an array with 2 items. ([?id, 402356]). I then store that number in a variable. The finished line is as follows: 
  ```const movieId = window.location.search.split('=')[1];```

I can then use both the movieId and the fetchAPIData() function to dynamically call the different movie detail pages!
  ```const movie = await fetchAPIData(`movie/${movieId}`);```

Similarly to previous pages, I again create a div using createElement() and use innerHTML to add the html and css, followed by replacing hard-coded values within the movie data. 
E.g. ```<h2>${movie.title}</h2>```

One particular thing to note in this lecture is the use of .map(), which I have not done in a while. I had to refamiliarise myself with the syntax.
```
<ul class="list-group">
      ${movie.genres.map((genre) => `<li>${genre.name}</li>`).join(', ')}
    </ul>`
```

Here, I called the data inside of movie.genres and map over it. The map function loops over the data via our callback function and returns a new array of the data. Using template literals again, I create a list item for every genre item and include the 'genre.name'.
As it returns an array, the data within the site looks something like the following:

Universal Pictures <br>
, <br>
Illumination <br>
, <br>
Nintendo. <br>

To fix this, I use the join() method to convert the array into a string.

I noticed that some movies were lacking data on their budget and revenue and the API would return '0'. I did not like the look of this, so I made 2 variables that used ternary operators to check if movie.budget/revenue was 0, and if so, change to 'N/A'. 

```
const checkBudget =
    movie.budget != 0 ? `$${numberWithCommas(movie.budget)}` : 'N/A';
  const checkRevenue =
    movie.revenue != 0 ? `$${numberWithCommas(movie.revenue)}` : 'N/A';
```
    
The API includes 'movie backdrop', which we can use to make the site look a little more professional.
I used the the backdrop on both the movie details and tv details page.
I first created a function called displayBackgroundImage with 2 parameters (type and backgroundPath)
displayBackgroundImage(type, backgroundPath)

Inside of this function I created a div.
I then use style.backgroundImage to target the specific url needed to access the image backdrops with the id.
`overlayDiv.style.backgroundImage = `url(https://image.tmdb.org/t/p/original/${backgroundPath})`;`
Followed by a lot of CSS styling inside of the function, which I'm not too sure if I'm happy with. I personally feel like it may have been better to store these styles in a class within the stylesheet, especially as there is so many of them.

Lastly, an if statement that checks whether it is tv details or movie details.
```
if (type === 'movie') {
document.querySelector('#movie-details').appendChild(overlayDiv);
} else document.querySelector('#show-details').appendChild(overlayDiv);
```

By calling this function inside of our displayMovieDetails() function, our backdrop is added!

---

### Day 68: May 23, 2023
 
**Today's Progress**: Continuing with the Flixx App project, today I completed the 'TV Show Details Page', 'Swiper Slider' and 'Search Functionality' lectures.

**Thoughts:** <br>
#### TV Show Details Page
This was obviously once again very similar to our movie details page. I removed the hard-coded values from the HTML and copied our displayMovieDetails function and changed the template literals as needed to produce the data on the site.

No real issues to report, except for the lack of mobile responsiveness in the site as flexbox/grid was not properly being utilised on the details pages. I somewhat fixed this but I can appreciate that this project is obviously for JavaScript purposes, not necessarily making the website look 'perfect'.

Some of the data property names change when using TV shows data, rather than the movie data, so I naturally found that a lot of the code wasn't necessarily returning the data when I simply changed our data variable from movie > show. Thankfully my lecturer is already aware of this and knows the correct API data property names, but obviously if this were not the case, I would have to console.log and check the returned data myself or refer to the API reference guide.

#### Swiper Slider
This lesson was really cool and something I've wanted to do for a long time, which is to use a library to create some animated site effects.
After following this lecture, there's a 'Now Playing' section at the top of the site that scrolls through movies that are currently playing in Cinemas. It is also mobile responsive and customiseable!

The code itself was not particularly difficult to follow as it's followed somewhat of the same general process as previous functions.

First I created the function displaySlider(), which is placed with our index.html section in the page-routing. I async await using the fetchAPIData() function from 'movie/now_playing'. 

I destructure and 'pull' the 'results' from that data followed by looping through that data and once again creating a div for each movie. I then add a class of 'slider-swipe' to each div created and then set the innerHTML of the created divs as follows:

```
            `<a href="movie-details.html?id=${movie.id}">
              <img src="https://image.tmdb.org/t/p/w500${movie.poster_path}" alt="${movie.title}" />
            </a>
            <h4 class="swiper-rating">
              <i class="fas fa-star text-secondary"></i> ${movie.vote_average} / 10
            </h4>`;
```
I make sure they are clickable links by using anchor tags and movie.id. I use poster_path again for the images, followed by the rating of the movie and appending the div to the parent container of .swiper-wrapper.

It's important to note that the swiper animation requires a little more setting up, so I also invoke the function of 'initSwiper()' within the forEach loop so that it is called everytime a div is created.

The initSwiper function is mostly just configuration as you can see below: 
```
function initSwiper() {
  const swiper = new Swiper('.swiper', {
    slidesPerView: 1,
    spaceBetween: 30,
    freeMode: true,
    loop: true,
    autoplay: {
      delay: 4000,
      disableOnInteraction: false,
    },
    breakpoints: {
      500: {
        slidesPerView: 2,
      },
      700: {
        slidesPerView: 3,
      },
      1200: {
        slidesPerView: 4,
      },
    },
  });
}
```
Definitely using this again!


#### Search Functionality
This lecture was a little more difficult to follow as search functionality is an entirely new concept to me. I felt like I was however able to keep up with the lecture and understand the code.

The first important changes to note here was Brad's decision to move the API key and URL from the fetchAPIData() function into the global object as well as adding a new search object with keys that we'll be using later to determine whether we're searching for a movie or a tv show.
```
const global = {
   currentPage: window.location.pathname,
   search: {
    term: '',
    type: '',
    page: 1,
    totalPages: 1,
 },
   api: {
    apiKey: 'xxxxxxxxxxxxxxxxxxxxxxxxxx',
    apiUrl: 'xxxxxxxxxxxxxxxxxxxxxxxxxx',
 },
};
```
Interestingly, the search submit button actually directs to a different HTML page entirely, appropriately named 'search.html'. Due to this, I have created a search() function that is placed in the page-routing under our search.html page.

Firstly, the search function needs to store two important pieces of data.
window.location.search again, followed by the search parameters.
```
const queryString = window.location.search;
const urlParams = new URLSearchParams(queryString);
```
queryString has stored '?type=movie&search-term=[whatever we search here]'

urlParams has stored an instantiation of the object URLSearchParams that I have passed queryString into.

This is important as the URLSearchParams object gives me access to a variety of methods made available within the prototype object such as 'get()'.

By using get(), I am able to specifically return the 'type' or 'search-term' that we can then use for condition checks to see exactly what we are searching for, and whether or not the 'type' is a movie or tv-show!
```
global.search.type = urlParams.get('type');
global.search.term = urlParams.get('search-term');
```
I'll now store the 'type' and 'search-term' inside of the global object and run a condition check to see whether or not there is text within the search bar, and if there isn't, alert the user on screen.
```
if (global.search.term !== '' && global.search.term !== null) {
 const results = await searchAPIData();
 console.log(results);
 } else {
 showAlert('Please enter a search term');
 }
```
If the condition passes, we want to await data from the new searchAPIData function which is very similar to the fetchAPIData function. The main differences here being that I'm now adding a 'search type' and a 'search term' from the global object into the API URL.
```
const response = await fetch(
`${API_URL}search/${global.search.type}?api_key=${API_KEY}&language=en-US&query=${global.search.term}`
);
```
The global object will update according to whether or not we have Movies or TV Shows selected when we search and now provide is with the correct search results!

I'm very happy with the progress so far, I'll be using many of the concepts that I've learned in this project so far, it's great to really start working on the 'backbone' of webdev. However, search functionality is proving to be quite a lot to take in, even if I am able to understand the code. 

---

### Day 69: May 24, 2023
 
**Today's Progress**: Continuing with the Flixx App project, today I completed the 'Display Search Results'.

**Thoughts:** <br>
Displaying the search results on screen wasn't as complicated as I thought it would be and in fact was very similar to displaying the movie and tv shows on the DOM as I had done in the previous lectures.

In the search() function, I have now added an additional if statement to check if there are any search results, and if there aren't any, show an alert 'No results.'
```
if (results.length === 0) {
showAlert('No results');
return;
}
```
If this passes, and there are results, then I want to run a function that displays the search results in the DOM and clear the input field.
```
displaySearchResults(results);
document.querySelector('#search-term').value = '';
```
For the most part, the displaySearchResults function was very similar to my displayPopularMovies / Tv-shows function as I'm once again looping through the results, creating a div with a class of 'card' and then setting the innerHTML of those divs. As the cards have remained the same throughout the website, I've copied the card innerHTML from my other functions and changed the template literals appropriately.

One key thing to note however is that 'movies' have a value pair of 'title' and tv-shows have a value pair of 'name'. Due to this, I had to include a conditional check to determine whether or not the title will be a movie, or a tv-show. As seen below:
```
<h5 class="card-title">${
global.search.type === 'movie' ? result.title : result.name
}</h5>
```
The global.search.type is obviously updated depending on which radio button is checked when using the search input. This was also the same case with release date, as tv-shows do not have a 'release date', but instead a 'first_air_date'.
```
<small class="text-muted">${
global.search.type === 'movie'
? result.release_date
: result.first_air_date
}</small>
```
Whilst I'm confident with the repetition of code that I'm seeing when it comes to creating new elements, adding the innerHTML and displaying those elements in the DOM etc, it's the 'smaller' details that are making a big difference that I'm not confident that I will remember.

An example of this is when Brad, during the lecture, decided to update the showAlert() function in a way that I have not seen before.
```
function showAlert(message, className = 'error') {}
```
Brad assigned the second parameter a default value of 'error', meaning that the function can be invoked without having to specify a second argument if we'd just like to use the red-background in the .error CSS.

This doesn't mean that I cannot assign a different second argument. I can also pass a second argument of 'success' if I'd like to use my .success class in my CSS thus changing the background colour of the alert to green.

A very small, but very useful amendment to the function that I hope I will remember to use in the future.

I also noticed that when a single result was returned in the search, the styling would cause the singular card to occupy the entirety of the page, causing the hover over effect to cover the page buttons and also distort the card image due to its size. Obviously, this isn't intended and so I also added an extra conditional and styling to fix the problem.

```
if (results.length === 1) {
  document.querySelector('.card').style.maxWidth = '50%';
  document.querySelector('#search-results').style.display = 'flex';
  document.querySelector('#search-results').style.justifyContent = 'center';
}
```
Max-width alone was not enough to solve the issue, is the card would also sit off-center and look out of place, so I also had to add flexbox to center the card. Another issue I faced after this however was the page buttons sitting directly under the card rather than at the bottom of the page with the footer. This is because Brad did not couple the footer and page buttons together in the HTML and I previously fixed the footer by using margin-top auto, which now pushes the page buttons up. I've decided to leave this issue as obviously the main focus of these lectures is the JavaScript.
