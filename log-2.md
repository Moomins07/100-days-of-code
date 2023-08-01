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

Note: Also spent the evening completing beginner CodeWar challenges to re-familiarise myself with some basic Array functions etc.

---

### Day 70: May 25, 2023
 
**Today's Progress**: Continuing with the Flixx App project, today I completed the 'Add Pagination for Search'.

**Thoughts:** <br>
In this lecture, I'm learning how to add dynamic page buttons that will allow the user to cycle through the search results, as only 20 are displayed on screen at a time. To do this, next/prev page will be fetching data from the API and re-populating the screen with data from the correct page. <br>

To start, I add three new key/value pairs to my global object:
```
    page: 1,
    totalPages: 1,
    totalResults: 0,
```

As I will require all three to track the current page out of the total pages.

Following this, inside of my search() function, I need to return more data from the API such as total_pages, page and total_results so that I can then update my global object equivalents with that data. As seen below:

```
if (global.search.term !== '' && global.search.term !== null) {
const { results, total_pages, page, total_results } = await searchAPIData();

    global.search.page = page;
    global.search.totalPages = total_pages;
    global.search.totalResults = total_results;
```

Firstly, I add a heading within my displaySearchResults() function so that we can display how many results are being displayed out of how many total results were found.
```
document.querySelector('#search-results-heading').innerHTML = ` <h2>${results.length} of ${global.search.totalResults} results for ${global.search.term}</h2>
`;
```
This will display "20 of 150 results for [search input]" <br>

As for the pagination, I first created a function called displayPagination() :
```
function displayPagination() {
const div = document.createElement('div');
div.classList.add('pagination');
div.innerHTML = `        <button class="btn btn-primary" id="prev">Prev</button>
          <button class="btn btn-primary" id="next">Next</button>
          <div class="page-counter">Page ${global.search.page} of ${global.search.totalPages} </div>
        </div>`;
}
```
The function follows the same process as most other functions populating the DOM. Here I create 2 buttons (prev/next) followed by a page counter to allow us to which page we are on out of how many pages total.

Now that the buttons are seen on the DOM and soon to be functioning, I need to add some basic conditionals that disables the prev button on the first page, and the next button on the last page:
```
// Disable prev button if on first page
if (global.search.page === 1) {
document.querySelector('#prev').disabled = true;
}

// Disable next button if on last page
if (global.search.page === global.search.totalPages) {
document.querySelector('#next').disabled = true;
}
```
Furthermore, I need to add an event listener to the buttons.
Everytime a button is clicked, it was be fetching data from the API, meaning that the function will be async.
```
// Next page
document.querySelector('#next').addEventListener('click', async () => {
global.search.page++;
const { results, total_pages } = await searchAPIData();
displaySearchResults(results);
});
// Prev page
document.querySelector('#prev').addEventListener('click', async () => {
global.search.page--;
const { results, total_pages } = await searchAPIData();
displaySearchResults(results);
});
```
When the button is clicked, the global.search.page value is incremented by 1 (page 2).
I assign destructure results again from our returned data and invoke the displaySearchResults() function with the newly returned data.

Important note! The searchAPIData function that we call to return data from the API must be updated so that the correct page of data is returned. To do this, I added another query-string to the end of the URL.

${API_URL}search/${global.search.type}?api_key=${API_KEY}&language=en-US&query=${global.search.term}`&page=${global.search.page}`

The buttons are now working, but the pervious page of data remains on the screen, causing the results/pagination buttons to double whenever we click next or previous page. To fix this, I can clear the previous search results by adding the following code at the very top of the displaySearchResults() function:
```
document.querySelector('#search-results').innerHTML = '';
document.querySelector('#search-results-heading').innerHTML = '';
document.querySelector('#pagination').innerHTML = '';
```
Now, whenever the displaySearchResults() function is called, the above elements are set to '' I.e. Nothing.

This was a much longer lecture and there was a lot to take in. I definitely won't remember everything here, especially as this was one of the more complex lessons. I'm very happy to have this project complete, I'm hopeful that I can take a lot away from this and implement what I've learned in future projects.

---

### Day 71: May 26, 2023
 
**Today's Progress**: Now that I have completed the Flix App project, I have decided to begin a mini-project that will use an API in hope to solidify what I've learned.

**Thoughts:** <br>
The original plan was to build a simple landing page using TailwindCSS as it's my general 'go to' framework for CSS now. However, it's been many months since I used it last and I found myself unsure as to how to continue. My first hurdle was not necessarily trying to remind myself of Tailwind's syntax, but more so brushing up on my general CSS fundamentals and then even trying to decide on a design for the website.

I poorly attempted to convince myself that the landing page was not particularly important, as the project was obviously for JavaScript purposes, but I set out to refamiliarise myself with Tailwind once again and learn new things along the way.

Even though it took many, many hours of research and referring to documentation, I eventually created somewhat of an acceptable, yet basic, looking landing page for the humble beginnings of my project.

I did not stop there though. I decided that I wanted to animate a message on the landing page wherein a message would 'fade-in', pause for a few seconds, 'fade-out' and then fade-in once again with a different message. Although this sounded simple by design, I found myself constantly 'close' to a result, but only found that the animations would break.

The first attempt at trying to add such an animation to my page was as follows: <br>
I created custom animations through the 'tailwind config' file. The first animation fades the element in, pauses for 5 seconds or so and then fades out; the text would suddenly re-appear however, and I learned that I needed to add 'forwards' to my animation, which makes the element use the last animation frame when it ends (faded out). I then created a second animation that would only fade-in, once again using the newly learned 'forwards' syntax. Example below:

```
fadeInOut: {
          '0%': { opacity: '0' },
          '20%': { opacity: '1' },
          '80%': { opacity: '1' },
          '100%': { opacity: '0' },
        },
 ```

My first attempt was by adding two different 'h1' elements and applying the 'fadeInOut' animation to the first h1, followed by the second 'fadeIn' animation to the second h1. Using JavaScript to apply these classes unfortunately did not work everytime, they were very volatile and seemed to break at random. I created a function within my JavaScript that would add the animate class to my first h1 and then use setTimeOut() to wait for that animation to finish, followed by adding the fadeIn animation to my second h1. This did not work and also had the undesired effect of naturally having 2 different elements in 2 different positions on sreen (two block elements). I considered using 'absolute' positioning to solve this, but I feared that the elements would not sit correctly on all screen sizes. It was clear that I would not simply be able to just add the animation classes to my elements through JS, I need to find another approach.

I'm getting close, but I'm not quite there yet. More tweaking is required.


---

### Day 72: May 27, 2023
 
**Today's Progress**: Continuing with my personal project, I've managed to tweak and fix the h1 animations to get the result I was after. I have also added some extra responsive/user experience features to the 2 buttons on the landing page that will be used to populate the site.

**Thoughts:** <br>
Continuing from yesterday, I thought that the continuous animation malfunctions was an issue with my 'Tailwind-starter' folder that I created 5-6 months ago, I set up a new, updated folder for TailwindCSS that now uses 'Vite'. The updated Tailwind folder is much 'cleaner' now and easier to manage then my previous folder, but this unsurprisingly did not solve the issue of my animations not working. On the bright side, my new project now also uses Just-In-Time, meaning that only the classes I call are being used in my project!

I realised that I only need the one element manipulated to achieve the desired effect, and so I once again tweaked my function, this time using a setTimeout function that would perform the code once the initial animation finished (fade in and fade out). Within that setTimeout function, I removed the fadeInOut animation, added the 'fadeIn' animation and also set the textContent to the new message that I'd like the user to see. This worked! Seen below.

```
function titlesFadeInOut() {
  return new Promise((resolve) => {
    // Fade in first message
    const firstMessage = document.getElementById('firstMessage');
    firstMessage.classList.remove('opacity-0');

    // After 8 seconds, fade out the first message and fade in the second
    setTimeout(() => {
      firstMessage.classList.remove('animate-fadeInOut');
      firstMessage.classList.add('animate-fadeIn');
      firstMessage.textContent = 'Click to get started!';
      resolve();

      // Allow for the first message to fade out before the second message starts to fade in
    }, 9000); // 8 seconds
  });
}
```

Following this, I wanted my 2 image buttons to be a little more dynamic and responsive. My first idea was to add a 'bounce' animation to the images if they are not interacted with for a period of time, prompting the user to make a selection. This needed to occur once the h1 animations had finished, which I was able to achieve by using async/await and a promise in the titlesFadeInOut() function, seen above and below. 

```
async function imgPromptAnimation() {
  await titlesFadeInOut();
  const promptBtns = document.querySelectorAll('.promptBtn');
  let timerId = null;
  //   Adds initial bounce animation to prompt user after 12 secs
  setTimeout(() => {
    document.getElementById('srv').classList.add('animate-lessBounce');
    // 1.5 sec delay on other img so they bounce out of sync
    setTimeout(() => {
      document.getElementById('klr').classList.add('animate-lessBounce');
    }, 1500);
  }, 12000);
  //   Remove bounce effect on hover
  promptBtns.forEach((button) => {
    button.addEventListener('mouseenter', () => {
      // If there is a previous timer, clear it
      if (button.dataset.timerId) {
        clearTimeout(button.dataset.timerId);
      }
      button.classList.remove('animate-lessBounce');
      //   Time out function to add bounce effect after 12 seconds of inactivity
      // Set up a new timer
      button.dataset.timerId = setTimeout(() => {
        button.classList.add('animate-lessBounce');
      }, 12000);
    });
  });
}

```
I wanted the buttons to bounce when they were not interacted with after 12 seconds, which I was able to do with a rather basic setTimeout function, as seen above. Both buttons would bounce at the same time, so I used another setTimeout function to animate the right button 1.5 seconds after the left button. I then looped over each button and listened for a 'hover' (mouseenter) event. When this occurred, the bounce animation is removed. To add to this, I wanted the buttons to once again bounce if another 12 seconds pass without any interaction, which is why I have a conditional check to check if the button has dataset.timerId, and if there is already a timer, clear that timer. I had to do this, as originally if I continued to hover over the button, several Timeout functions would begin to run simultaneously.
After 12 seconds, the lessBounce animation is added again.

Note that I first discovered the default Tailwind bouce animation to be too 'bouncy', so I created a custom bounce animation called lessBounce and used that instead.

```
keyframes: {
        lessBounce: {
          '0%, 100%': {
            transform: 'translateY(-5%)',
            animationTimingFunction: 'cubic-bezier(0.8,0,1,1)',
          },
          '50%': {
            transform: 'none',
            animationTimingFunction: 'cubic-bezier(0,0,0.2,1)',
          },
 ```

All of the functions are added to my init() function, which is invoked on DOMContentLoaded. Today has been very educational, but also very frustrating. Slow and steady progress! Tomorrow, I will be looking to change the HTML to load via our JS as well as populating the site with some API data.


---

### Day 73: May 28, 2023
 
**Today's Progress**: Today I completed several hours of beginner challenges on Codewars.com.

**Thoughts:** This is quite interesting, because I recall over a year ago, struggling to make sense of some of the basic JavaScript beginner challenges. I recall being extremely demoralised, because so many online resources swear by Codewars as a big and potentially important part of a programmer's learning resources. I decided that in time, I would return to Codewars to see my progress, and I am happy to report that I was able to complete all but one beginner challenge across several days. Better yet, I not only passed these challenges, but I also refactored my code often down to single lines, which obviously isn't totally necessary, and not all that practical in terms of readability, but fun nonetheless. I'll definitely be incorporating more challenges into my day when I find myself looking for something to pass some time. Hopefully, in time, I will also find myself returning once again completing more advanced challenges. 

---

### Day 74: May 29, 2023
 
**Today's Progress**: Continued working on my personal project site that uses a Dead By Daylight API. I added in some placeholder images to replace when I access the API and also tweaked the layout a bit. I also did manage to access the API today, but not without its frustrations.

**Thoughts:** I originally planned this project to be 'quick' and 'simple' just to solidify what I had learned from my previous API lessons in the JavaScript course I am following. However, it is taking much longer than anticipated. 

As previously mentioned, I've found myself having to essentially re-learn TailwindCSS whilst also coming to grips with HTML and CSS again as I go. I've managed to achieve the simple look and style, which isn't working 100% of the time in terms of mobile responsiveness etc, but the focus here is obviously the JavaScript.

I've noticed that my site tends to be very volatile, with the animations sometimes just breaking without any real reason, and then simply resolving itself whenever it feels like it. I've still no idea why the website does this, maybe it's something to do with my browser cache? I hope to find some answers on this soon.

The first major issue I ran into whilst attempting to pull data from the API I had chosen (https://dbd.tricky.lol/apidocs/) was a 'CORS' error. This error is completely new to me and I've yet to understand what it actually means, but it was a hurdle I needed to jump. I began researching on the topic to find that this isn't uncommon when working with APIs, and that there is in fact an NPM package called 'cors-anywhere' that allows the user to essentially 'by-pass' the error.

From what I can see, and I could be wrong, the API requires us to be using a secure server if we wish to pull the data, of which I obviously do not have as I'm attempting to pull the data directly from the API first, NOT from my own back-end server. 

Cors-anywhere essentially allows us to set up a server that meets the correct criteria to be able to pull the data we'd like from the API. I did this by creating a server.js file and using the following code:

```
const cors = require('cors-anywhere');

cors
  .createServer({
    originWhitelist: [], // Allow all origins
    requireHeader: ['origin', 'x-requested-with'],
    removeHeaders: ['cookie', 'cookie2'],
  })
  .listen(8080, '0.0.0.0', function () {
    console.log('Running CORS Anywhere on ' + '0.0.0.0' + ':' + '8080');
  });
```

After this, I simply needed to update my fetchAPIData function to include the server URL before the API url:

```
const API_URL = 'http://localhost:8080/' + global.api.apiUrl;
```

This did the trick! I'm now able to pull data from the API. However, it's important to note here that this is clearly going to be insecure and will only be used for development and educational purposes. Unfortunately, I have to run this server manually via Node.js in the console with `node server.cjs` before I can obviously use it. This means that I will not be able to fetch data from the API if I were to actually make this website live on a domain. 

Nonetheless, tomorrow I'll be attempting to use the API to populate my website locally and see what I can do with it. Not the exact result that I would have hoped for, but this has been incredibly educational as I'm sure this won't be the last time that I'll encounter the 'CORS' error.

---

### Day 75: June 01, 2023
 
**Today's Progress**: With several job opportunities arriving, I'm taking a small break from my personal project to focus on learning tech stacks that could potentially benefit me in upcoming projects. Today, I focused on following an 'Astro' lecture as I plan to eventually use both Astro and TailwindCSS to get Landing Pages up quickly and efficiently.

**Thoughts:** Now that I've finally began touching on a framework that uses components, with regards to JavaScript, I'm beginning to see the fruits of my labour. It's very strange yet also very exciting to start using a framework that actually requires the use of JavaScript to streamline the process of creating a website. It's quite a strange concept for me, as I haven't used such a framework before, but it's a lot of fun to build individual components using a combination of HTML, CSS and JavaScript, followed by using JavaScript to import and export components across different pages of the site. I can see how this can greatly increase the speed of setting up a site once you gain some experience. Note that JavaScript can be used inside of curly brackets.

An example of this that I found really fun, was creating a 'card' component that I could then easily re-use across my site if required. See below:

```
---
export interface Props {
  title: string;
  body: string;
  dark?: boolean;
}

const { title, body, dark = false } = Astro.props as Props;
---

<div class={`card ${dark && 'dark'}`}>
  <h3>{title}</h3>
  <p>{body}</p>
</div>

<style>
  .card {
    background: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    margin-bottom: 20px;
  }

  .dark {
    background: var(--color-primary);
    color: #fff;
  }
</style>
```

As you can see, it's explicitly declared via Props that those key/value pairs will include a certain data type. I then destructure and assign those variables to Astro.props as Props.
Following this, I assign those now dynamic values into the card. I've also noticed the important of using the AND operator to short-circuit when handling conditionals for the components.
`<div class={``card ${dark && 'dark'}``}>` Assigns the class of card and then uses a template literal for the expression to determine whether or not dark is true, and if so, assign the 'dark' as a class.
This makes sense to me, but again, is not something that I have done or used before.

I can now use this component, for example, in my 'features' section of the web-page. Seen below:

```
---
import Card from './Card.astro';

const featuresData = [
  {
    title: 'Zero JavaScript Runtime',
    body: ' Astro renders HTML on the server and strips away any remaining, unused JavaScript.',
  },
  {
    title: 'The Power of Islands',
    body: ' Need interactive UI? Load individual, non-blocking component islands in parallel.',
  },
  {
    title: 'Lazy-Loading Islands',
    body: "Components only hydrate when they scroll into view. If you don't see it, Astro won't load it.",
  },
];
---

<section class="features">
  <div class="container">
    {
      featuresData.map((feature) => (
        <Card title={feature.title} body={feature.body} />
      ))
    }
  </div>
</section>

<style>
  /* Cards */
  .features .container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 20px;
    padding: 0 20px;
    margin: 30px auto;
  }
  @media (max-width: 500px) {
    .features .container {
      grid-template-columns: 1fr;
    }
  }
</style>
```

Firstly, I have to import the Card component, followed by explicitly declaring the text that will sit inside of those cards, which works as I made the card component dynamic and did not hard-code any text. Inside of the container, I now use curly brackets to start a JavaScript expression, wherein I use .map() to loop through the featuresData array of objects, and for each 'feature', assign Card title and body featuresData.title & body respectively. Note that if I add an expression to explicitly add the class of dark = true, then the dark-mode styling in the Card component will execute. 

Overall, this is quite a sudden change for me as I have yet to use React, which is a framework that I had planned to eventually learn before other similar frameworks, but Astro had caught my eye a few times and curiosity got the better of me. Whether or not I continue to use Astro going forward, I don't know, but I'd like to have at least a project or two that uses Astro for portfolio purposes. 

---

### Day 76: June 02, 2023
 
**Today's Progress**: Today I finished the Astro project and deployed it to Netlify.

**Thoughts:** I covered a lot during this lecture but I will note particular topics of interest below.

Firstly, the power of Props, that I have still yet to fully understand. 
When creating the Tabs component, I needed the Headings and Content of those tabs to be customiseable and not hard-coded, as this obviously made the component dynamic and re-useable. To do this, I first needed to 'export interface Props' and declare key/value pair headings/contents with their data type. In this case, it was an array of strings. I then followed typical procedure by destructuring those keys and assigning them as Props. See below:
```
---
export interface Props {
  activeTextColor?: string;
  headings: string[];
  contents: string[];
}

const {
  headings,
  contents,
  activeTextColor = '#A741FF',
} = Astro.props as Props;
---

<div class="tabs">
  <ul class="tabs-header">
    {headings.map((heading) => <li>{heading}</li>)}
  </ul>
  <ul class="tabs-content">
    {contents.map((content) => <li class="tab">{content}</li>)}
  </ul>
</div>
```
As you can see above, typical procedure is followed by then using the .map() function to create our new array of <li> tags with a dynamic 'heading'.
The exact same process is followed for the tabs-content too, except we now obviously use {contents}, not {heading}.
 
To make full use of this component, I now need to place it in my index page after importing the component. The difference now being that I can actually place an array of strings inside of that component that are fully customiseable within the index page itself. See below:
```
 <Tabs
        headings={['NPM', 'PNPM', 'YARN']}
        contents={[
          '$ npm create astro@latest',
          '$ pnpm create astro@latest',
          '$ yarn create astro',
        ]}
      />
```
 
The second notable topic is the use of Markdown in my project to create blog posts that can also expand into a more detailed post on that particular blog post.
This is a new concept to me. I firstly had to create markdown posts that followed a specific structure:
 
```
 ---
title: Astro 1.0 Release Update
slug: astro-1-0-release-update
excerpt: orem ipsum dolor sit amet, consectetur adipiscing elit. Integer iaculis ante at sem ultrices iaculis.
date: 02-06-2021
author: Jane Doe
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer iaculis ante at sem ultrices iaculis. Praesent at ultricies risus. Aliquam consequat porttitor sollicitudin.
```

Naturally, I then created a blog page for the website that used 'Layout' to apply the Header and footer. As there is more than one post, typical process it followed once again by using the .map() function to create new arrays, that will place our blogs dynamically on the page. I did however needed to use await on the posts folder, followed by specifying that I am waiting for all .md files.

`const posts = await Astro.glob('../posts/*.md');`
```
 <section class="page-content">
    <div class="container">
      {
        posts.map((post) => (
          <Card>
            <h3>{post.frontmatter.title}</h3>
            <div>
              Written by <strong>{post.frontmatter.author}</strong> on{' '}
              {new Date(post.frontmatter.date).toLocaleDateString()}
            </div>
            <p>{post.frontmatter.excerpt}</p>
            <a class="btn" href={`/${post.frontmatter.slug}`}>
              Read More
            </a>
          </Card>
        ))
      }
    </div>
  </section>
```
 
Key to note here that I specifically had to use 'frontmatter' to access the keys in my markdown files. 
I now have the blogs placed as cards on my blog page, thanks to the help of the Card component, that include a button that will take us to `{`/${post.frontmatter.slug}`}`.

This is where I began to feel out of my depth with the course as I haven't worked with much backend before and the following process is supposedly very similar to Next.js.
To now make the blog cards button take us to an expanded version of the blog, I have to create a new page `[slug].astro`. 
I created a function 'getStaticPaths' that again awaits the markdown files, followed by mapping over the post md files and assigning 2 objects. 'params' with a key of slug with a value pair and 'props' with only a key 'post'.
```
 export async function getStaticPaths() {
  const posts = await Astro.glob('../posts/*.md');

  return posts.map((post) => ({
    params: {
      slug: post.frontmatter.slug,
    },
    props: {
      post,
    },
  }));
}

const { Content, frontmatter } = Astro.props.post;
---
```
 
I somewhat struggled to follow along at this point, but continually attempted to breakdown what exactly the code is doing. I don't recall how I have access to 'Content', I can only presume that this is an object that is already existing inside of Astro.props.post. Frontmatter, on the other hand, I know points to the top-section of the blog posts and gives me access to the key/value pairs. For the content of the 'expanded blog' page, I used the following:
```
<Layout title={frontmatter.title}>
  <section class="page-content">
    <div class="container">
      <Card>
        <a class="btn" href="/blog">Go Back</a>
        <h2>{frontmatter.title}</h2>
        <div>
          Written by <strong>{frontmatter.author}</strong> on {
            new Date(frontmatter.date).toLocaleDateString()
          }
        </div>
        <Content />
      </Card>
    </div>
  </section>
</Layout>
```
frontmatter.xxx points to the key/value pairs in the markdown posts and `<Content />` is referring to the Lorem Ipsum that is placed outside of those key/value pairs.
I'm definitely not 100% on exactly how everything is working together, but I am quite confident that I could re-create this and create my own blog/posts in the future if required. 

Overall, Astro has been very different for me, a lot of fun to use and very educational, but component-based building is clearly something that I need to do more of. I'm looking forward to using it more in the future.
 
 ---
 
 ### Day 77: June 04, 2023
 
**Today's Progress**: Having finished the a lecture on Astro, and with my Astro template finished and working, I've begun to move an older project over to Astro in order to practice but also to "Leverage Astro's unique zero-JS frontend architecture to unlock higher conversion rates with better SEO." 

**Thoughts:** Not much to report today, I haven't had anay issues moving over the project yet. I was a little afraid of the site breaking when I added TailwindCSS to the project, but via Astro's online documents, I've managed to do that without any real issues. I've began to slowly remove redundant in-line CSS from my Astro components and tweak some styling. For example, I wasn't happy with the image cards on the homepage as a single column on phone screens, it took up an unnecessary amount of space and required more scrolling. To fix this, I opted for display: grid instead of flexbox, giving me more control over how many columns there should be at which break-points With that now working, I made a start on hooking up the Astro components appropriately and changing the homepage text etc.

 
---
 
 ### Day 78: June 05, 2023
 
**Today's Progress**: With the site mostly as I'd like it in terms on the landing page, I spent today experimenting with animations as I wasn't particularly happy with how my animations turned out in a previous project. 

**Thoughts:** This time, I decided to try and find a library for my animations, instead of using/creating TailwindCSS animations. I was not able to get a library called 'aos' (animate on scroll' to work and I think this is due to how Astro manages the web files. However, I was able to get results by using a library called 'animate.css' that easily allowed me to place animations on my elements by using classes. The first issue I noticed was that the default animations were not very customiseable and didn't give me all of the freedom that I would have liked. To solve this, I used JavaScript and setTimeout methods to create a 'flow' of animations on-screen. See below: 

```
 document.addEventListener('DOMContentLoaded', function () {
    const boxOne = document.querySelector('.boxOne') as HTMLElement;
    const boxTwo = document.querySelector('.boxTwo') as HTMLElement;
    const boxThree = document.querySelector('.boxThree') as HTMLElement;
    const boxFour = document.querySelector('.boxFour') as HTMLElement;
    setTimeout(() => {
      setTimeout(() => {
        boxOne.style.visibility = 'visible';
        boxOne.classList.add('animate__animated', 'animate__fadeIn');
      }, 300); // Start after 300ms

      setTimeout(() => {
        boxTwo.style.visibility = 'visible';

        boxTwo.classList.add('animate__animated', 'animate__fadeIn');
      }, 600); // Start after 600ms

      setTimeout(() => {
        boxThree.style.visibility = 'visible';

        boxThree.classList.add('animate__animated', 'animate__fadeIn');
      }, 900); // Start after 900ms
      setTimeout(() => {
        boxFour.style.visibility = 'visible';

        boxFour.classList.add('animate__animated', 'animate__fadeIn');
      }, 1200); // Start after 1200ms
    }, 3500);
  });
```
 
I wanted each box to appear one after the other, not simultaneously, and the animate.css library default classes did not allow me to do this. To solve this issue, I set theboxes to hidden in their default styling, followed by changing 'hidden' to 'visible' and then applying the animation classes. Every .3 seconds, this occurs and creates the effect of a staggered animation. Furthermore, I wanted to animate the homepage title and hero section which took approximately 3 seconds to complete. This is why I also set another setTimeout function around the box setTimeouts, so that the title animations could finish before the boxes appear.
 
I'm very happy to finally get some consistent working animations on screen, it's something that I've wanted to do for a long time and only recently began to get results that I'm happy with. I'll be sure to use these animations, albeit sparingly, in future projects.
 
Note: As a bonus project, I also attempted to create my own 'animate on scroll', which I was able to do but not necessarily with my own JavaScript knowledge. Using resources, I was able to find the code below:

```
 document.addEventListener('DOMContentLoaded', function () {
    // Get our element
    const element = document.querySelector('.features');

    // Define our scroll check function
    function checkScroll() {
      const rect = element.getBoundingClientRect();

      if (rect.top < window.innerHeight) {
        element.classList.add('animate__animated', 'animate__fadeInLeft');
      }
    }

    // Listen for scroll events
    window.addEventListener('scroll', checkScroll);

    // Run our scroll check function once to check initial position
    checkScroll();
  });
```
This also worked successfully every time without issues and it's something I could consider using in the future.
I'm looking forward to playing around with more animations!

---
                                        
### Day 79: June 06, 2023
 
**Today's Progress**: Continuing to make tweaks to the website, I decided to add a max-width to the header to ensure that the logo and privacy policy nav item don't sit at the very edge of the screen. I also continued to tweak the site in terms of mobile responsiveness.

**Thoughts:** Setting up the nav bar header to use a max-width ended up being a little more problematic than I had planned as setting as max width was naturally causing white bars to appear around my header, as my background was set directly to that header. The easiest solution in the end was to add another div within the header and apply my max-width to that instead, meaning that the background colour was unaffected. Following this, I added in my 'previous project' cards but found they were not working correctly; I realised that this is because the styling I had used for these cards in a previous project were using TailwindCSS components and I also needed to move this into the global.css file. 
                                        
The cards originally weren't working, I tried and failed to set up postcss and autoprexifer which resulted in removing them entirely. I eventually realised that the cards were working all along, and that it was a z-index issue causing an overlap in elements. Hence my cursor was not in fact hovering over the cards and the animations were not working.. 
                                       
---
       
### Day 80: June 07 , 2023
 
**Today's Progress**: More tweaks! Today I fixed up spacing, typography, responsiveness, added a Privacy Policy page and also added a few scripts with refactoring!

**Thoughts:** I covered a lot today with a bit of everything to clean up the site and get it ready for deployment. Firstly, I decided to clean up the code to the animated logo boxes on the homepage as I wasn't happy with how I had declared individual variables for each box, which is unnecessary when I can simply loop over the. You can see that code below:

```
document.addEventListener('DOMContentLoaded', function () {
    const boxes = document.querySelectorAll(
      '.logoBox'
    ) as NodeListOf<HTMLElement>;

    boxes.forEach((box) => {
      setTimeout(() => {
        setTimeout(() => {
          boxes[0].style.visibility = 'visible';
          boxes[0].classList.add('animate__animated', 'animate__fadeIn');
        }, 300); // Start after 300ms

        setTimeout(() => {
          boxes[1].style.visibility = 'visible';
          boxes[1].classList.add('animate__animated', 'animate__fadeIn');
        }, 600); // Start after 600ms

        setTimeout(() => {
          boxes[2].style.visibility = 'visible';
          boxes[2].classList.add('animate__animated', 'animate__fadeIn');
        }, 900); // Start after 900ms
        setTimeout(() => {
          boxes[3].style.visibility = 'visible';
          boxes[3].classList.add('animate__animated', 'animate__fadeIn');
        }, 1200); // Start after 1200ms
      }, 3500);
      box.classList.remove('animate__animated', 'animate__fadeIn');
    });
  });
      
```
As you can see, I've now given everybox a class of 'logoBox' and used querySelectAll with the addition of 'as NodeListOf<HTMLElement>' due to TypeScript strictness. Following this, I've used a forEach loop to essentially do the exact same thing as before, except now I'm targetting those boxes as I would an array 'boxes[0]', as opposed to targetting each box individually with its own variable.
                                        
The rest of today's work is a lot of little tweaks to spacing at different breakpoints to ensure that the website is looking correct on smaller devices. Unfortunately, I've yet to work out how to get a website to work correctly on 'Nest Hubs'/'Nest Hub Max'; it seems that Tailwind considers them a completely different breakpoint to what comes default within TailwindCSS and I would likely need to set up a custom breakpoint for Nesthubs in the tailwind.config file. I may get around to adding this functionality but for now I'm happy with the website working on what seems to be 95% of devices.

On the topic of responsiveness and site functionality, I recently learned of a DevTool called 'Lighthouse' which scans my website and gives me scores based on several factors, but most importantly, accessibility. My score for accessibility was originally quite low, so I set out to add accessibility features such as aria-labels, sequenced headings and focus outlines so that the website can be navigated using the 'tab' key.
       
After I had added the privacy policy page, I decided to add some JavaScript to detect the page that the user is currently on and then change the innerHTML based on that condition. See below: 
```
const privacy = document.querySelector('.privacy');
  if (window.location.pathname === '/privacy') {
    privacy.innerHTML = `<a
        href="/"
        class="privacy flex tracking-widest hover:text-white transition duration-500"
        >HOME</a>`;
  } else {
    privacy.innerHTML = `<a
        href="/privacy"
        class="privacy flex tracking-widest hover:text-white transition duration-500"
        >privacy policy</a
      >`;
  }
```
This worked locally and allowed that anchor tag to work both as a link to the privacy page and the home page, but seems to break after deployment to netlify, which I think is due to how Astro handles its JavaScript. Upon checking the source files, I noticed that this script wasn't being hoisted; I will be spending more time tomorrow looking into this and hopefully finding some answers. I also noticed that the homepage background image is not being uploaded to GitHub and therefore also isn't displayed on the homepage. This is also something I'll be looking into tomorrow.
Overall, a very productive day today, the finish line is in site, just a few more things to fix!
                                        
                                        
                                        
---
       
### Day 81: June 08, 2023
 
**Today's Progress**: More fixes and tweaks to the CASoftware landing page!

**Thoughts:** I discovered a few more minor bugs, but I knew I wouldn't be satisfied until I had resolved them.
I noticed the other day that content would overflow into other sections when I shrunk the screen vertically. Googling and AI was not of much help and so I decided to sleep on the matter and give it some thought. Incredibly, I actually found myself waking up the next morning with the fix, as I realised that my sections were set to height: 100vh (screen size), NOT min-height. This meant that the sections had a max-height and would grow to the size of the screen but were also able to shrink vertically. Declaring a min-height solved this issue.
                                        
I'm also beginning to question 'best practices' as I'm not sure how happy I am with how I've laid out and spaced my website. I've been using a lot of individuals containers with padding and margin to space them out across the screen. However, I feel like some of these elements could use flexbox and be aligned vertically that way instead, as I currently have my 'box container' separated from the paragraph it by padding and margins. Could flexbox be better practice/more useful if I'm specifically setting that section to fill the entire screen? For now, it's not making much of a difference, but I'll need to inspect others code or watch a few tutorials online to get an idea as to how I can do better on that topic.
       
I'm yet to work out how to resolve the issue of the privacy policy text changing depending on the current active page. I may just have to leave it as it is and hope that the company logo will suffice as an 'obvious' way to go back to the main page. 
Quite happy with what I have so far, hoping to have everything fixed and deployed soon.

---
                                        
### Day 82: June 10, 2023
 
**Today's Progress**: Made a start on the OOP section of Brad Traversy's JavaScript course. I completed 6 lectures: 
'What Is OOP?',
'4 Basic Principles of OOP',
'More on Object Literals & this Keyword',
'Constructor Functions',
'Literals vs Built-in Constructors',
'Working With Object Properties',
                                        
**Thoughts:** Returning to the Odin Project course once again, I've decided to use Brad Traversy's course as a supplement to my learning via the Odin project. Unsurprisingly, I've found that I'm not retaining as much as I thought I would when completing some of the projects in the course. The Odin Project requires you to complete projects through your own means of knowledge and research. Originally I had planned to complete Traversy's course to re-continue with The Odin Project, but this doesn't make sense, as I should be applying what I've learned almost immediately. As I haven't been doing this, I'm not retaining as much as I would like.
       
I briefly learned about OOP around 5-6 months ago as part of a project in The Odin Project course. The project was to create an interactive library, similar to a to-do app, which allows the user to add, remove and update their progress on a book. 
       
Once I have finished all lectures on OOP in Brad's course, I will return to the Library Project. 
                                        
                                        
---
                                        
### Day 83: June 11, 2023
 
**Today's Progress**: Continuing with the OOP section of Brad Traversy's JavaScript course. I completed 4 more lectures: 

'Prototypes & The Prototype Chain',
'Adding Methods to the Prototype',
'Using Object.create()',
'Prototypical Inheritance & call()'.
                                        
**Thoughts:** I recall covering prototypes in previous lectures and the various syntax that can be used to form a prototype chain. The method of prototypical inheritance covered in the above lectures uses, in my opinion, a somewhat chaotic and confusing structure. See below:

```                              
function Shape(name) {
  this.name = name;
}

Shape.prototype.logName = function () {
  console.log(`Shape Name: ${this.name}`);
};

function Rectangle(name, height, width) {
  Shape.call(this, name);

  this.height = height;
  this.width = width;
}
                                        
Rectangle.prototype = Object.create(Shape.prototype);
                                        
Rectangle.prototype.constructor = Rectangle;
                                        
const rect = new Rectangle('Rectangle 1', 20, 20);
```
                                        
As you can see above in this block of code, a few steps must be completed before I am able to create new Shapes using constructors.
Firstly, I've created a a generic 'Shape' function with a parameter of 'name' as all of our shapes will have a name, followed by adding a function called 'logName' to the prototype of that Shape constructor function that will allow me to log the name of the shape. 
       
Secondly, I create a Rectangle constructor function with the parameters of name, height and width. However, 'name' is being 'called' from our Shape constructor function. To do this, I must use the .call() method and pass in 'this' to set the 'this' keyword to the current function followed by which parameter I am calling from that constructor function, in this case it's 'name'.
                                        
Thirdly, I've decided that I want to link the Shape constructor function's prototype to my Rectangle constructor function so that I can use logName and log the name of the Rectable. To do this, I must assign Rectangle.prototype to Shape.prototype. However, it's important to note that I MUST use Object.create to instantiate a new object of that prototype and not link them directly. `Rectangle.prototype = Object.create(Shape.prototype);`
       
Now that I have linked the two prototypes, I can even store logName inside of my Rectangle constructor's prototype but change the output to suit my needs. This is a great exmaple of polymorphism. 
```
Rectangle.prototype.logName = function () {
  console.log(`Rectangle Name: ${this.name}`);
};
```
Also note that the prototype constructors were set to 'Shape' which is not what I want when I'm creating a Rectangle, for example. To set instantiated Rectangle's constructor to Rectangle, I must also use the following code:
`Rectangle.prototype.constructor = Rectangle;`
                                        
Lastly, to instantiate a new Rectangle object:
`const rect = new Rectangle('Rectangle 1', 20, 20);`
                                        
I don't find this syntax or structure easy to read and I won't be using this particular syntax once I have covered Classes.
                                        
---
                                        
### Day 84: June 12, 2023
 
**Today's Progress**: Continuing with the OOP section of Brad Traversy's JavaScript course. I completed 3 more lectures: 
'OOP Game Challenge',
Followed by making a start on the second OOP section: 14 - OOP - Classes, Getters, Setters & Private Properties:
'Classes',
'Class Inheritance',
                                        
**Thoughts:** I felt confident moving on to the OOP game challenge, but actually found myself stuck with the logic. I over-complicated the logic as the focus on the challenge was simply to use what I had learned on prototypes and inheritance. I also did not fully understand Brad's wording for the challenge as he specified that a function will accept a number between 1-10 but Brad did not add conditional checks for this and his solution could accept both number above and below 1/10. However, I was relatively close to achieving a very similar result and I understood how prototypical inheritance was working in my code, which again, was the main focus of the lesson. 
       
On the topic of classes, I'm just very glad to get started with them as I do not like the messy code of explicitly declaring .prototype etc. Classes are much cleaner and easier to read/use in my opinion. Really looking forward to having this section complete so that I can get back to The Odin Project!
                                       
---
                                        
### Day 85: June 13, 2023
 
**Today's Progress**: Continuing with the OOP section of Brad Traversy's JavaScript course. I completed 3 more lectures: 
'Static Methods',
'bind() & Defining this',
'Getters & Setters with Classes'.
                                        
**Thoughts:** I'm definitely not feeling as confident as I begin to slowly approach topics that are new to me. Whilst I have somewhat of a decent understanding of all of the topics that I covered today, I definitely don't have the full picture just yet. My understanding so far of the 3 topics is as follows:
Static methods are simply functions that are declared inside of a Class to work with data that is 'static', it doesn't use any data from the constructor function. An example of this is just returning the class name:
```
   static getClass() {
    return 'Rectangle';
  }
}
```
I'm not quite sure of a typical use-case just yet.
                                        
The bind() function was a little lost to me at first, but I think I'd grasped the concept toward the end of the lesson. Here's the code I used during my lecture:
```
class App {
  constructor() {
    this.serverName = 'localHost';

    document
      .querySelector('button')
      .addEventListener('click', this.getServerName.bind(this));
  }

  getServerName() {
    console.log(this.serverName);
  }
}

const app = new App();
```

Here we have a typical constructor called App that simply assigns this.serverName to a string of localHost. I then also created a function called getServerName() that logs this.serverName to the console.
The problem occurs when I want to add an event listener to my class that will invoke the getServerName(). This is because getServerName() will be placed in our event listener as a callback function, which automatically means the 'this' keyword will refer to the object that triggered the event, which in this case would be a button; 'undefined' would be returned on click. To solve this, we use 'bind()', which creates a new function that refers to the class App ensuring that the getServerName() is invoked. To summarise, we can use bind() to ensure our 'this' keyword refers to the class.

Getters and Setters, in concept, make sense to me but I don't feel confident about their use or use-cases. Again I will post code that I worked with and break down my understanding:
       
```
class Person {
  constructor(firstName, lastName) {
    this._firstName = firstName;
    this._lastName = lastName;
  }

  get firstName() {
    return this.capitaliseFirst(this._firstName);
  }

  set firstName(value) {
    this._firstName = this.capitaliseFirst(value);
  }

  get lastName() {
    return this.capitaliseFirst(this._lastName);
  }

  set lastName(value) {
    this._lastName = this.capitaliseFirst(value);
  }

  get fullName() {
    return `${this.firstName} ${this.lastName}`;
  }

  capitaliseFirst(value) {
    return value.charAt(0).toUpperCase() + value.slice(1);
  }
}

const person1 = new Person('john', 'doe');
```

The first important note is that JavaScript developers follow a naming convention when handling private properties; it will be indicated with an underscore before the variable. E.g. this._firstName. This means that the property should not be accessed directly.
To handle the private properties without directly accessing them, Getters and Setters can be used, for example, in the case above I am using a capitaliseFirst() method to capitalise the first letter of firstName and lastName without actually directly accessing 'this._firstName'.

get firstName will return 'John' and lastName will return 'Joe'. Therefore we have actually mutated the data provided to use without touching our private properties.

Setters also allow us to mutate the data without accessing the private property. You can use dot notation on the instantiated object 'person1' to simply mutate the properties. E.g.
```
person1.firstName = 'joe';
person1.lastName = 'smith';
```

'John Doe' would now be 'Joe Smith'.

We can even go another step and use 'get' to return a full name by concatenating our firstName and lastName getters:
```
get fullName() {
    return `${this.firstName} ${this.lastName}`;
  }
```
`console.log(person1.fullName);` would now return "Joe Smith".

These new topics have been quite overwhelming as there's a lot to cover. Even though I lack confidence on the use of the syntax, I feel confident in my understanding of the concepts, especially after the above breakdowns of the code that I have used.

---

### Day 86: June 14, 2023
 
**Today's Progress**: Continuing with the OOP section of Brad Traversy's JavaScript course. I completed 2 more lectures: 
'Getters & Setters with defineProperty()',
'Private Property Underscore Convention'.
                                        
**Thoughts:** This is where I've began to feel overwhelmed as, typically with programming, I've been shown another way of using getters and setters, this time without using classes. See below:
```
function Person(firstName, lastName) {
  this._firstName = firstName;
  this._lastName = lastName;

  Object.defineProperty(this, 'firstName', {
    get: function () {
      return this.capitaliseFirst(this._firstName);
    },
    set: function (value) {
      this._firstName = value;
    },
  });
```

The key differences here is that we're calling the 'defineProperty' function to bind 'this' and our getters and setters. There is no advantage or disadvantage to this particular syntax, it's just preference. 

Brad also explained how to use getters and setters inside of an object literal:
```
const PersonObj = {
  _firstName: 'jane',
  _lastName: 'doe',

  get firstName() {
    return Person.prototype.capitaliseFirst(this._firstName);
  },
  set firstName(value) {
    this._firstName = value;
  },

  get lastName() {
    return Person.prototype.capitaliseFirst(this._lastName);
  },
  set lastName(value) {
    this._lastName = value;
  },

  get fullName() {
    return this.firstName + ' ' + this.lastName;
  },
};

const person2 = Object.create(PersonObj);
```

The key difference when using getters and setters inside of an object literal is that we instantiate that object by using Object.create(), not the 'new' syntax. 

In the private properties convention lecture, Brad goes into more detail about the naming convention of placing an underscore ('_') at the beginning of our properties. I originally struggled somewhat with this concept as in JavaScript, it is just a naming convention and not an actual secure property; I also struggle to imagine where I would need to use a secure property. Brad fortunately goes into detail and explains that it's to ensure that our constructor properties are not interacted with directly by the user. See below:

```
class Wallet {
  constructor() {
    this._balance = 0;
    this._transactions = [];
  }

get balance() {
    return this._balance;
  }
get transactions() {
    return this._transactions;
  }
 }
```

As explained from previous lectures, through the use of getters, like in the code above, I can now access balance and transactions without making changes to the 'secure' properties in the constructor function. Note that a similar result can also be achieved through the use of functions, getters are not always required:
```
_processWithdrawal(amount) {
    console.log(`Withdrawing ${amount}`);

    this._transactions.push({
      type: 'withdraw',
      amount,
    });
  }
```

Through this function, I am able to send data to the '_transaction' array and use a 'withdraw' function to access it:
```
withdraw(amount) {
    if (amount > this._balance) {
      console.log(`Not enough funds`);
      return;
    }
    this._processWithdrawal(amount);
    this._balance -= amount;
  }
```

With current lectures, I'm finding better results in reducing the amount of lectures per day simply due to the amount of new information. 

---
                                        
### Day 87: June 15, 2023
 
**Today's Progress**: Continuing with the OOP section of Brad Traversy's JavaScript course. I completed 3 more lectures, completing this section of the course: 
'ES2022 Private Class Fields',
'Property Flags & Descriptors',
'Sealing & Freezing Objects'.
                                        
**Thoughts:** Private class fields was very interesting, to see that JavaScript does in fact have a way of making properties a true private property as opposed to the naming convention that is currently used to indicate if a propert yis private. It's a shame that, as a new feature, it is currently not supported by all browsers, making the new feature seemingly more-so eye-candy that a feature that can be used practically. However, it's great to see that it could potentially become a commonly used feature within the next few years and obviously useful to know that it exists.

Unsurprisingly, the OOP rabbit hole goes deeper and I've learned that each object property individually has access to a 'descriptors' object, which allows the developer to alter 4 different, individual properties of the descriptor object. The properties are as follows: 
[[Configurable]] - if `true`, the property can be deleted and these attributes can be modified, otherwise not
[[Enumerable]] - if `true`, the property will be returned in a `for...in` loop, otherwise not
[[Writable]] - if `true`, the value of the property can be changed, otherwise not
[[Value]] - the value of the property.

Through descriptors, we can ensure that an object can only be interacted with in a very certain way. I.e. We don't want that object to be displayed in a loop, so we can set enumerable to true etc.
```
Object.defineProperty(rectObj, 'name', {
  writable: false,
  configurable: false,
  enumerable: true,
});
```

Following this, I learned about 2 more properties that work essentially the same as the descriptors except with pre-coded values, to save time.
[[Sealing]] - Prevents properties from being added or removed. Can still be changed.
[[Freezing]] - Prevents properties from being added, removed or changed.

The syntax is as follows:
`Object.freeze(circleObj);`
`Object.seal(rectObj)`

You can then also check if an onject is frozen or sealed with `Object.isSealed(rectObj)` / `Object.isFrozen(circleObj)`.

---

### Day 88: June 16, 2023
 
**Today's Progress**: Today I moved on to the OOP project 'Tracalorie'. The app will allow a user to input their daily calorie goals and workouts, whilst counting the amount of calories consumed and burned based on worksouts/food eaten. There will also be a progress bar and filter options.
                                        
**Thoughts:** Having finished the first 3 lectures of the project section, Brad gives a clear overview of what the project is, how it will work and what we will be doing in terms of OOP to get the results we'd like. This project is definitely intimidating compared to the previous projects that I have completed, because there is just so many different concepts to cover in OOP.

I did not feel like I fully understood the flow chart that Brad had presented in one of the lectures that explained the various functions that will be implemented into different classes. On the other hand, Brad also went over the theme for the project, which is just a relatively basic Bootstrap theme, which I do understand as I have used Bootstrap in the past.

Overall, I'm excited to get going, but also very intimidated by the size of the project.


---

### Day 89: June 19, 2023
 
**Today's Progress**: Continuing with the Tracalorie app, I completed 2 lectures:
'Base Tracker, Meal & Workout Class',
'Display Tracker Stats'.
                                        
**Thoughts:** I'm finding this OOP project a little difficult to follow at times. I'm definitely lacking confidence and full understanding of how OOP is used to build full size projects such as this. Whilst the code itself makes sense to me, I struggle sometimes to see how exactly the various methods within classes interact with one another.
I'm especially confused at times as to why some methods are public, and why others are not. Brad did cover this in a previous lecture, explaining what methods will go in which classes etc, but at the end of the day, I'm simply following along with the project in attempt to soak up what I can before returning to The Odin Project.
I definitely need to come to better terms with the concept of OOP and understand why some of the methods are private rather than public. I'm not sure what the *actual* reason is behind opting to keep some methods private and public, what has a programmer make that decision? Obviously, I understand however, that a private method is a way of accessing constructor properties without directly interacting with them, which is why private methods are especially useful. I haven't user any getters or setters so far though.

I'm following along and managing to understand the code and somewhat get by, but I feel like I'm lacking a lot of key information with some knowledge gaps and that's causing me to lack confidence on the topic.

Another concept that makes sense but seems sloppy to me, is the use of a render method. This is to ensure that everytime I 'Add a workout' or 'Add a meal', other methods, such as display total calories is invoked and updated in the DOM.
See below:
```
addMeal(meal) {
    this._meals.push(meal);
    this._totalCalories += meal.calories;
    this._render();
  }

_render() {
    this._displayCaloriesTotal();
    this._displayCaloriesConsumed();
    this._displayCaloriesBurned();
    this._displayCaloriesRemaining();
  }
```   
As you can see, addMeal pushes our meal to an array and we then use render to run all of our methods to update our DOM. Though this makes sense, it feels messy and something that I would easily overlook.
                                                                         
---

### Day 90: June 21, 2023
 
**Today's Progress**: Continuing with the Tracalorie app, I completed 3 lectures:
'Progress Bar & Calorie Alert',
'App Class, New Meal & Workout',
'Refactor to Single _newItem Method'.
                                        
**Thoughts:** 
The progress bar was a lot of fun to code as it's something that I've specifically wondered how to do for a while and would like to use it in my personal projects. The progress bar was relatively straight forward, as well as coding the style changes if the user consumes too many calories; this was a typical use case for an if statement and background style change depending on the condition. 

Starting on the App class and new Meal/Workout however is where I've once again become a little stumped, as I still question at times why Brad has chosen to put methods in certain places and how those interact with the other classes. Something that is new to me and was not really explained, is the ability to instantiate a new object inside of a classes constructor.

```
class App {
  constructor() {
    this._tracker = new CalorieTracker();

    document
      .getElementById('meal-form')
      .addEventListener('submit', this._newItem.bind(this, 'meal'));
    document
      .getElementById('workout-form')
      .addEventListener('submit', this._newItem.bind(this, 'workout'));
  }
}
```

As you can see above, I've instantiated CalorieTracker and assigned it to a private property '_tracker'. I was not aware that this was possible and I'm not 100% on how exactly that works. This now gives me access to public CalorieTracker methods to use in my App class. Ie. newMeal and newWorkout.

I'm also going to add a few notes during the refactor of my newWorkout/newMeal methods in the App class as I was unsure as to how this worked for a moment.

```
_newItem(type, e) {
    e.preventDefault();

    const name = document.getElementById(`${type}-name`);
    const calories = document.getElementById(`${type}-calories`);

    // Validation inputs
    if (name.value === '' || calories.value === '') {
      alert('Please fill in all fields');
      return;
    }

    if (type === `meal`) {
      const meal = new Meal(name.value, +calories.value);
      this._tracker.addMeal(meal);
    } else {
      const workout = new Workout(name.value, +calories.value);
      this._tracker.addWorkout(workout);
    }

    name.value = '';
    calories.value = '';

    const collapseItem = document.getElementById(`collapse-${type}`);
    const bsCollapse = new bootstrap.Collapse(collapseItem, {
      toggle: true,
    });
  }
}
```

By using template literals and the event listeners in the class App constructor, either meal or workout is passed into the function, and depending on which is passed through, 2 different elements are selected, followed by an if statement that instantiates a new object of either Workout or Meal. This is a refactor from originally have 2 separates methods for addMeal and addWorkout.
The code makes sense to me, but I don't think this is something I would have done myself had I not been following a tutorial.




---

### Day 91: June 22, 2023
 
**Today's Progress**: Continuing with the Tracalorie app, I completed 1 lecture:
'Display New Meal & Workout'.
                                        
**Thoughts:** Not a lot to report on this topic. Typical process of making the 'Add Meal/Workout' element actually add a newly created element to the DOM. See below:
```
_displayNewWorkout(workout) {
    const workoutsEl = document.getElementById('workout-items');

    const workoutEl = document.createElement('div');
    workoutEl.classList.add('card', 'my-2');
    workoutEl.setAttribute('data-id', workout.id);
    workoutEl.innerHTML = `
    <div class="card-body">
                <div class="d-flex align-items-center justify-content-between">
                  <h4 class="mx-1">${workout.name}</h4>
                  <div
                    class="fs-1 bg-secondary text-white text-center rounded-2 px-2 px-sm-5"
                  >
                    ${workout.calories}
                  </div>
                  <button class="delete btn btn-danger btn-sm mx-2">
                    <i class="fa-solid fa-xmark"></i>
                  </button>
                </div>
              </div>
    `;
```

I create and assign a div 'workoutEl' with the parent container that I want to add the child elements today assigned as 'workoutsEl'.
Once the div is created, I assign it a class of 'card' and 'my-2' for Bootstrap functionality. I then assign workoutEl data attributes as I need to be able to select specific elements later to delete them.
I've then taken the original hard-coded HTML and used that and innerHTML to add the full card content along with template-literals to add the dynamic values such as 'workout.name' etc.

This is a process that I'm becoming very familiar with. However, I often hear that using innerHTML is not the best practice and should be avoided in some projects due to security issues; it's been referred to as the 'quick and dirty' way of adding elements to the DOM by my lecturer, but he continues to use this method a lot? I will need to research more and find out why Brad is opting for this method of adding an element.

I'm also becoming a little overwhelmed with how many functions the data is being passed through and find myself overthinking and analysing the functions and going back on myself regularly. I think this is definitely more prevalent after a shirt-break from the project and trying to re-familiarise myself with the structure of the code. 

---

### Day 92: June 26, 2023
 
**Today's Progress**: Continuing with the Tracalorie app, I completed 1 lecture:
'Remove Meal & Workout'.
                                        
**Thoughts:** Again, not feeling very confident with what I'm learning, although I can understand what is happening to an extent. This lecture was about using event delegation by adding an event listener to the parent element of the cards that contain the delete buttons.
```
document
      .getElementById('workout-items')
      .addEventListener('click', this._removeItem.bind(this, 'workout'));
```
Again, bind is used to ensure that 'this' points to the object and not the element that is being clicked. I also pass in 'workout' so that I can make conditional checks later. '_removeItem' is invoked on click.

```
_removeItem(type, e) {
    if (
      e.target.classList.contains('delete') ||
      e.target.classList.contains('fa-xmark')
    ) {
      if (confirm('Are you sure?')) {
        const id = e.target.closest('.card').getAttribute('data-id');

        type === 'meal'
          ? this._tracker.removeMeal(id)
          : this._tracker.removeWorkout(id);

        e.target.closest('.card').remove();
      }
    }
  }
```

Firstly, inside of the parent element 'workout-items', I check if the element being clicked contains the classes either 'delete' or 'fa-xmark' as this is both the red box and the x. I follow this with another if check to confirm if the user is sure they want to delete, and if so, store the closest '.card's' id in a variable. I then use a ternary operator to check if the type is equal to meal, and if so, use removeMeal(id) or removeWorkout(id) from the '_tracker' object. The element is then removed.

The removeMeal/Workout function is as follows:
```
removeMeal(id) {
    const index = this._meals.findIndex((meal) => meal.id === id);
    if (index !== -1) {
      const meal = this._meals[index];
      this._totalCalories -= meal.calories;
      this._meals.splice(index, 1);
      this._render();
    }
  }
```

Firstly, find and store the index by using findIndex() and looping through the _meals array until a meal.id is found that matches the passed in id. 
If that item exists, store that meal as that index in a variable 'meal', takeaway the meal.calories from the totalCalories, splice() to remove that item from the array and lastly, use render() to update the DOM.

As previously mentioned, I feel that I'm able to understand the process, but I'm feeling overwhelmed and lack confidence in my ability to do something like this myself outside of a tutorial.

---

### Day 93: July 04, 2023

**Today's Progress:** Continuing with the Tracalorie app, I completed 2 lectures:
'Filter & Reset',
'Set Calorie Limit'.

**Thoughts:** Unfortunately, life has gotten in that way of my studying the past few weeks and I was forced to take a break, meaning that my learning has been inconsistent. Returning to a half-finished project has made this all the more difficult, especially since I already found myself very overwhelmed with this particular project, with OOP already being a new concept to me.

I was able to follow the lectures with ease, but I feel that at this point I am just essentially following along and typing away whilst not retaining as much as I'd like. I do try to take pauses here and there to understand the code, and for the most part I do understand it, but I could never imagine myself developing such code by myself without a tutorial to follow.

I will add the code used to create a filter below:
```
 document
      .getElementById('filter-meals')
      .addEventListener('keyup', this._filterItems.bind(this, 'meal'));
document
      .getElementById('filter-workouts')
      .addEventListener('keyup', this._filterItems.bind(this, 'workout'));

_filterItems(type, e) {
    const text = e.target.value.toLowerCase();
    document.querySelectorAll(`#${type}-items .card`).forEach((item) => {
      const name = item.firstElementChild.firstElementChild.textContent;

      if (name.toLowerCase().indexOf(text) !== -1) {
        item.style.display = 'block';
      } else {
        item.style.display = 'none';
      }
    });
  }
```

Naturally, I first add an event listener to both filter elements (workout and meal) and have it check for a keyup event, as we'll be typing to filter.  I bind 'this' to the object and not the element and also pass in 'meal' / 'workout' so that we can use a conditional to check which filter is being used.

Inside of the _filterItems function, a 'type' and 'event' is passed in. I store the text being typed into the filter using `const text = e.target.value.toLowerCase();` also making sure that the text is lower-case in our checks, so it is not case-sensitive in our application.
I select all of the '.card' s under the parent element of `#${type}-items`, depending on whether 'workout' or 'meals' is passed into our function. I then loop through those cards using forEach, first storing the name of the workout or meal with `const name = item.firstElementChild.firstElementChild.textContent;`.
Next, I use an if statement to check if 'name' (E.g. Lunch) contains 'text' (checked on every keyup event). If so: display block, else: display none.


Resetting the page, on the other hand, was relatively straight forward. 
```
document
      .getElementById('reset')
      .addEventListener('click', this._reset.bind(this));

 _reset() {
    this._tracker.reset();
    document.getElementById('meal-items').innerHTML = '';
    document.getElementById('workout-items').innerHTML = '';
    document.getElementById('filter-meals').value = '';
    document.getElementById('filter-workouts').value = '';
  }

reset() {
    this._totalCalories = 0;
    this._meals = [];
    this._workouts = [];
    this._render();
  }

```

Add an event listener to reset button, on click, invoke private _reset function.
_reset invokes public reset function in our _tracker class.
Set all relevant fields to none ( = '').
In the public reset function, reset all private properties to default/none and use render to display these changes on screen.


Lastly, setting a new calorie limit.
```
document
      .getElementById('limit-form')
      .addEventListener('submit', this._setLimit.bind(this));

 _setLimit(e) {
    e.preventDefault();

    const limit = document.getElementById('limit');

    if (limit.value === '') {
      alert('Please add a limit.');
      return;
    }

    this._tracker.setLimit(+limit.value);
    limit.value = '';

    const modalEl = document.getElementById('limit-modal');
    const modal = bootstrap.Modal.getInstance(modalEl);
    modal.hide();
  }


setLimit(calorieLimit) {
    this._calorieLimit = calorieLimit;
    this._displayCaloriesLimit();
    this._render();
  }
```

Added an event listener, on submit, invoke private function _setLimit().
_setLimit first prevents default, stopping the refresh from occurring on submit.
If statement to check if anything is inside of the field before submitting.

Next I use _tracker class' public function of setLimit to pass in limit.value. (added a + at the beginning to make the output a number).
I then set limit.value to nothing ( = '').

```
 const modalEl = document.getElementById('limit-modal');
    const modal = bootstrap.Modal.getInstance(modalEl);
    modal.hide();
```
The above code is just bootstrap code to close the modal once a new calorie limit has been set.

Overall, I'm finding it a little tough getting back into the 'flow' of this project and understanding all of the code, but I am managing to slowly work through the project, spending time on brekaing down the code and understanding it as I have done here in this log. 

---

### Day 94: July 09, 2023

**Today's Progress:** Continuing with the Tracalorie app, I completed 2 lectures:
'Storage Class & Calorie Limit Persist',
'Persist Total Calories To Local Storage'.

**Thoughts:** As I approach the end of this project, I've finally began to store the data in local storage so that the user's data can persist through website reloads/closure. I've found this part of the course a little difficult to follow, but I will do my best to breakdown the code I have added to the project below.

First, I created a storage class that will contain static methods. Static methods are methods that can be called without the requirement of instantiating the object. E.g. With the class 'Storage' and the method called 'updateTotalCalories', I can simply type: Storage.updateTotalCalories(). There is no need to instantiate. The reason I use static methods inside of the Storage class is because I do not need multiple instances of storage, it's local-storage, which is one entity.

```
class Storage {
  static getCalorieLimit(defaultLimit = 2000) {
    let calorieLimit;
    if (localStorage.getItem('calorieLimit') === null) {
      calorieLimit = defaultLimit;
    } else {
      calorieLimit = +localStorage.getItem('calorieLimit');
    }

    return calorieLimit;
  }

  static setCalorieLimit(calorieLimit) {
    localStorage.setItem('calorieLimit', calorieLimit);
  }

  static getTotalCalories(defaultCalories = 0) {
    let totalCalories;
    if (localStorage.getItem('totalCalories') === null) {
      totalCalories = defaultCalories;
    } else {
      totalCalories = +localStorage.getItem('totalCalories');
    }

    return totalCalories;
  }

  static updateTotalCalories(calories) {
    localStorage.setItem('totalCalories', calories);
  }
}
```

getCalorieLimit() initialises a variable calorieLimit and then checks if localStorage contains the key 'calorieLimit', if it doesn't, set calorieLimit to the defaultLimit of 2000, else set calorieLimit to the calorieLimit in localStorage.
setCalorieLimit() simple sets the key of calorieLimit in localStorage using whatever is passed into the function.
I then repeat essentially the same code for TotalCalories as I also want this stored in localStorage also.

For the data inside of localStorage to work, I have to make sure that the constructors are using the data inside of localStorage and not hard-coded data. _calorieLimit and _totalCalories is set to use values from Storage, as you can see below:

```
class CalorieTracker {
  constructor() {
    this._calorieLimit = Storage.getCalorieLimit();
    this._totalCalories = Storage.getTotalCalories(0);
    this._meals = [];
    this._workouts = [];
```

I now also need to ensure that the calorie limit is set inside of localStorage when the calorie limit is set in the app. To do this, I need to add the setCalorieLimit function inside of the setLimit public function.
```
setLimit(calorieLimit) {
    this._calorieLimit = calorieLimit;
    Storage.setCalorieLimit(calorieLimit);
    this._displayCaloriesLimit();
    this._render();
  }
```

Now, whenever the calorieLimit is set, it will be stored in localStorage also.

However, if the user modifies those values in the app, we also need to update the total cloaries inside of localStorage. This is achieved with the updateTotalCalories() function. You can see this 3 code snippets up.
updateTotalCalories should be invoked whenever the user adds/removes a meal/workout, as this will affect the total calories in our app.

```
 addMeal(meal) {
    this._meals.push(meal);
    this._totalCalories += meal.calories;
    Storage.updateTotalCalories(this._totalCalories);
    this._displayNewMeal(meal);
    this._render();
  }
```

I add the line `Storage.updateTotalCalories(this._totalCalories);` after the line of code that adds calories to _totalCalories.
This same line of code will also be included inside of addWorkout, removeWorkout and removeMeal.

Overall, I feel that I've understood the code and broken it down well, but again, I simply can't imagine myself being able to write this code by myself/independently. This project has been very humbling for me, and a quick reminder that I still have a very long way to go.

---

### Day 95: July 14, 2023

**Today's Progress:** Continuing with the Tracalorie app, I completed 4 lectures:
'Save Meals To Local Storage',
'Save Workouts To Local Storage',
'Remove Meals & Workouts From LocalStorage',
'Clear Storage Items'.

**Thoughts:** Continuing with saving data to local storage, thankfully a lot of the code is somewhat straight forward and re-useable, making these lectures quite short and to the point. 

**Saving meals/workouts to localStorage**:
Typically, I first created a function to get the meals from localStorage if it exists there, followed by then pushing the new meal into the 'meals' array and re=saving the updated meals array in localStorage.

```
static getMeals() {
    let meals;
    if (localStorage.getItem('meals') === null) {
      meals = [];
    } else {
      meals = JSON.parse(localStorage.getItem('meals'));
    }
    return meals;
  }

  static saveMeal(meal) {
    const meals = Storage.getMeals();
    meals.push(meal);
    localStorage.setItem('meals', JSON.stringify(meals));
  }
```

getMeals() checks if 'meals' exists in localStorage, if it doesn't, create an empty array called 'meals', else 'meals' is assigned 'meals' from localStorage followed by returning 'meals'.

saveMeal() stores whatever is returned from our getMeals() function inside of 'meals', pushes the passed in meal into the meals array followed by then re-saving the newly updated array in localStorage (using setItem).

saveMeal() will need to be added to the public addMeal() function so that the meals is also saved to localStorage when a new meal is added. Shown below:
```
addMeal(meal) {
    this._meals.push(meal);
    this._totalCalories += meal.calories;
    Storage.updateTotalCalories(this._totalCalories);
    Storage.saveMeal(meal);
    this._displayNewMeal(meal);
    this._render();
  }
```

The CalorieTracker constructor will also need to be updated so that this._meals is not set to an empty array anymore, but instead whatever is stored in localStorage: `this._meals = Storage.getMeals();`

Lastly, the newly added meals/workouts will need to be added to the DOM. To do this, I created a function called 'loadItems()' that does the following:
` this._meals.forEach((meal) => this._displayNewMeal(meal));`

A loop through the _meals array that runs _displayNewMeal() for each meal in the array. 

A side note: I had so many event-listeners inside of the App class constructor that I placed them all in their own function '_loadEventListeners' and simply invoked that function inside of the App constructor instead.

get/saveMeals() is essentially the exact same code to also do the same for 'workouts', just simply changing 'meals' to 'workouts' was enough.

**Removing Meals/Workouts from storage**:
When a meal is removed from the DOM, it also needs to be removed in localStorage. To do that, I used the following function:
```
static removeMeal(id) {
    const meals = Storage.getMeals();
    meals.forEach((meal, index) => {
      if (meal.id === id) {
        meals.splice(index, 1);
      }
    });

    localStorage.setItem('meals', JSON.stringify(meals));
  }
```

'meals' is once again assigned the output of getMeals(), followed by looping over that array and passing in a meal/index.
If the meal.id that is passed in by the looped item matches the id passed into the removeMealfunction, I use splice() to remove that meal at the passed in index. Once the item is removed from the meals array, it needs to be re-saved to localStorage again, which is done by using the last line of code (setItem).

The exact same code is also used for workouts to achieve the same result.

Similarly to when I added saveMeal() to the public addMeal() function, I must also do the same here but instead with the public removeMeal() function.
This is also so that when a meal is removed, localStorage is updated accordingly. I add `Storage.removeWorkout(id);` to removeMeal() to do so as seen below:
```
 removeMeal(id) {
    const index = this._meals.findIndex((meal) => meal.id === id);
    if (index !== -1) {
      const meal = this._meals[index];
      this._totalCalories -= meal.calories;
      Storage.updateTotalCalories(this._totalCalories);
      this._meals.splice(index, 1);
      Storage.removeMeal(id);
      this._render();
    }
  }
```

Again, the same is done for workouts also.

**Clear Storage Items**:
Firstly, I set the current value inside of _calorieLimit to the input field of the 'set calorie limit' modal by adding the following line of code to the CalorieTracker class: `document.getElementById('limit').value = this._calorieLimit;`. This is just a simple nicety that means that user will not need to re-type the calorie limit if they want to use the same limit after resetting the App.

The idea here is to reset both the DOM and localStorage as we are now obviously pulling data from localStorage. To begin with, I added a function 'clearAll()' to the public reset() function (which is obviously hooked up to our reset button on the app).

There were two ways to do this, as the calorieLimit is also saved in localStorage. If I want the calorieLimit to persist through a reset, I would need to individually clear all of localStorage items except for calorieLimit so that it stays. However, if I don't mind everything resetting (which I don't), then I can simply use the clear() function. 

```
static clearAll() {
    localStorage.clear();
  }
```

**Project finished/final thought's**:
With that this project is finally finished! Unfortunately I found this project to be quite overwhelming, though I'm sure I've learned a lot I feel that I haven't gained a strong grasp on using OOP. I will be building a small project in The Odin Project course that requires me to use OOP, so I'm hopeful that I can use what I've learned here in that project. As seen by the dates, this project took a couple weeks of inconsistent work to complete, which has definitely affected how much information I have retained over the course of this project. I regret that I wasn't more consistent, as I may have felt more confident going into the TOP project. However, I have taken time after every lecture to break down the code I have written, how it works and how I feel about that particular subject, which has certainly helped a lot.


---

### Day 96: July 18, 2023

**Today's Progress:** Moving on from Brad's JavaSript course and the Tracalorie app project, I've returned to The Odin Project as I now plan to complete TOP whilst supplementing my learning with Brad's course. I returned to an old, previous 'book library' project in the TOP course, which requires me to use OOP. The app will accept 2 user inputs, a book title and author name, followed by a button or keypress that will store the book(s) in a table, in the DOM.

**Thoughts:** I decided to first hardcode and style the table/elements that will be added when the user adds a book to the page. This surprisingly gave me quite a bit of trouble, as I was deciding what the book element would look like on the page once it's added. In the end, I decided to use a HTML table with borders/dividers as this stood out to me the most. The issue with this is that there is no real way to make tables responsive, causing the table to break on mobile; to solve this, I hide the table on small screens and replace the table with simple cards that neatly store the book information instead.
I've definitely become rusty with TailwindCSS< finding myself referring to the documentation often as I can't remember syntax. Overall, I've spent too much time away from some of the fundamentals such as CSS and HTML requiring me to spend more time on the 'simpler' things than I had anticipated. However, the design is essentially done, I now need to move on to the logic. Below I will add the code that allowed me to hide the table on large screens and display the cards on mobile:
```
<table class="w-full mt-6 divide-y hidden md:table dark:border-gray-800 light:border-black">

 <div class="md:hidden block">
            <div
              class="border rounded p-4 mb-2 space-y-2 flex flex-col sm:items-center text-left mt-6"
            >
              <!-- this div represents a row -->
              <div><span class="font-bold">Name: </span>Lord of the Rings</div>
              <div><span class="font-bold">Author: </span>Tolkien</div>
              <div><span class="font-bold">Read: </span>Yes</div>
              <button
                class="uppercase tracking-wider text-sm border px-4 py-2 rounded hover:bg-white hover:text-black hover:border-black transform transition duration-250 ease-in-out w-fit sm:px-12"
              >
                Remove
              </button>
            </div>
  </div>
```

The table is hidden on mobile view (TailwindCSS uses a mobile-first design) but displayed on medium and above (md:table)
The card is hiddein on medium screens (md:hidden) but displayed on mobile screens (block).

---

### Day 97: July 19, 2023

**Today's Progress:** Continuing with the TOP Library project, I began working on the functionality of the app whilst ensuring I use OOP to do so. Today, I managed to correctly place the light/dark mode code within classes and also added a Book class as well as private and public methods.

**Thoughts:** As usual, I was very unsure as to how to start with this project, but I was fortunately able to use the previous project (Tracalorie App) that I had completed during Brad's JS course as reference. 
As usual, I doubt my ability and also my methods of completing this particular project. Should I be completing it from start to finish without referring to previously written code? I can't help but feel like using a previous course as reference is damaging my learning. I'm contemplating starting the project from scratch to see how far I can get. I will however, break down what I have written below regardless.

Similarly to the Tracalorie App, I created 2 main classes: Library which will store the books and contain public and private methods to interact with that data, and 'App', which will be the instantiated class to essentially run the Application.

```
class Library {
  constructor() {
    this._myLibrary = [];
  }

  // Public methods
  addBook(book) {
    this._myLibrary.push(book);
    this._displayNewBook(book);
    console.log(`Adding ${book} to "myLibrary" array`);
  }

  removeBook(id) {
    const index = this._myLibrary.findIndex((book) => book.id === id);
    if (index !== -1) {
      this._myLibrary.splice(index, 1);
    }
  }

  // Added this function to App class so items in array are displayed on load
  loadItems() {
    this._myLibrary.forEach((book) => this._displayNewBook(book));
  }

  // Private methods

  // Function to display the newly added book in the DOM
  _displayNewBook(book) {
    const booksEl = document.getElementById('book-table');

    const bookEl = document.createElement('tr');
    bookEl.classList.add('border-b');
    bookEl.setAttribute('data-id', book.id);
    bookEl.innerHTML = `
    <tr class="border-b">
    <td class="py-6">${book.name}</td>
    <td>${book.author}</td>
    <td>
      <button
        class="uppercase tracking-wider text-sm border border-white px-4 py-2 rounded hover:bg-white hover:text-black hover:border-black transform transition duration-250 ease-in-out hover:scale-105"
      >
        Yes
      </button>
    </td>
    <td class="flex justify-end py-6">
      <button
        id="remove-book"
        class="uppercase tracking-wider text-sm border border-white px-4 py-2 rounded hover:bg-white hover:text-black hover:border-black transform transition duration-250 ease-in-out delete"
      >
        Remove
      </button>
    </td>
  </tr>
  `;

    booksEl.appendChild(bookEl);
  }
}
```
Inside of the Library constructor, I've only contained an empty array assigned to _myLibrary as it's all I currently need in terms of data from the user.
Public methods: addBook(), removeBook() and loadItems(). addBook will push the passed in book into the _myLibrary array and then also run _displayNewBook to ensure that the book is added to the DOM. removeBook() finds the index of a particular item in the _myLibrary array by checking the passed in id with the books in the array. If it finds a match, it returns that book and then 'splices' it (removes it). loadItems() is a simple function that loops through the _myLibrary array and runs _displayNewBook for each item inside of the array. This is just to ensure that any books stored inside of the array are placed in the DOM on application start.

Private methods: _displayNewBook takes in a book as an argument and creates a new table-row (tr) element that also includes setting an extra attribute (data-id) assigned the value of the book's id (book.id). Lastly, the newly created book/element is appended to the table so that it is shown on the page.


class Book {
  constructor(name, author) {
    this.id = Math.random().toString(16).slice(2);
    this.name = name;
    this.author = author;
  }
}

Funnily enough, as simple as this is, I got stuck here because I simply forgot that I should make Book its own class. Simple Book class that tikes in two arguments and a typical constructor. The id is quite importantly here, as it generates a random code that we use in _displayNewBook to set data-id attribute and also in the removeBook function to compare the id with whatever is passed in. I realise the important of this simple line of code, as it makes any element unique and easier to handle.

```
class App {
  constructor() {
    this._bookLibrary = new Library();
    this._bookLibrary.loadItems();
    this._loadEventListeners();
    this._setDarkMode();
  }

  _loadEventListeners() {
    document
      .getElementById('theme-toggle')
      .addEventListener('click', this._toggleMode.bind(this));
    document
      .getElementById('link-form')
      .addEventListener('submit', this._newBook.bind(this));

    document
      .getElementById('add-book')
      .addEventListener('submit', this._newBook.bind(this));
    document
      .getElementById('book-table')
      .addEventListener('click', this._removeBook.bind(this));
  }

  _removeBook(e) {
    if (e.target.classList.contains('delete')) {
      {
        if (confirm('Are you sure?')) {
          const id = e.target.closest('.border-b').getAttribute('data-id');
          this._myLibrary.removeBook(id);
          e.target.closest('.border-b').remove();
        }
      }
    }
  }

  _newBook(e) {
    e.preventDefault();
    const bookTitle = document.getElementById('title');
    const authorName = document.getElementById('author');

    if (bookTitle.value === '' || authorName.value === '') {
      alert('Please fill in all fields');
      return;
    }

    const book = new Book(bookTitle.value, authorName.value);
    this._bookLibrary.addBook(book);

    bookTitle.value = '';
    authorName.value = '';
    console.log(this._bookLibrary._myLibrary);
  }

  _toggleMode() {
    const themeToggleDarkIcon = document.getElementById(
      'theme-toggle-dark-icon'
    );
    const themeToggleLightIcon = document.getElementById(
      'theme-toggle-light-icon'
    );
    // Toggle icon
    themeToggleDarkIcon.classList.toggle('hidden');
    themeToggleLightIcon.classList.toggle('hidden');

    // If is set in localstorage
    if (localStorage.getItem('color-theme')) {
      // If light, make dark and save in localstorage
      if (localStorage.getItem('color-theme') === 'light') {
        document.documentElement.classList.add('dark');
        localStorage.setItem('color-theme', 'dark');
      } else {
        document.documentElement.classList.remove('dark');
        localStorage.setItem('color-theme', 'light');
      }
    } else {
      // If not in localstorage
      if (document.documentElement.classList.contains('dark')) {
        document.documentElement.classList.remove('dark');
        localStorage.setItem('color-theme', 'light');
      } else {
        document.documentElement.classList.add('dark');
        localStorage.setItem('color-theme', 'dark');
      }
    }
    // DARK / LIGHT MODE BUTTON
  }

  _setDarkMode() {
    const themeToggleLightIcon = document.getElementById(
      'theme-toggle-light-icon'
    );
    const themeToggleDarkIcon = document.getElementById(
      'theme-toggle-dark-icon'
    );
    if (
      localStorage.getItem('color-theme') === 'dark' ||
      (!('color-theme' in localStorage) &&
        window.matchMedia('(prefers-color-scheme: dark)').matches)
    ) {
      // Show light icon
      themeToggleLightIcon.classList.remove('hidden');
    } else {
      themeToggleDarkIcon.classList.remove('hidden');
    }
  }
}

const app = new App();
```

The App class is what I've used to essentially represent the actual 'running' app, which is why the constructor also includes instantiating the Library class `this._bookLibrary = new Library()`. I am then able to use this._bookLibrary to call methods inside of the Library class, which I do below to invoke the loadItems function, meaning that this function will be run on app start. This is because code inside of constructors is run straight away. As this is the case, I also invoke _loadEventListeners and _setDarkMode. The function _loadEventListeners is simply to ensure that all of the elements have their event listeners applied to them straight away. 

Following this there's _removeBook() which is first checks if the element being interact with contains the class 'delete', and if so, check if the user has selected 'Yes' when prompted with 'Are you sure?'. If these pass, I then find the closest element with 'border-b', which should be the closest <tr> element, store that id and then remove the book using removeBook with that id passed in. However, this function at the time of writing this is not working 100% and requires tweaking. I believe it is because I have hard-coded books in the project that do not contain an id, as the idea is only set when a book is created through the newBook function. 

I also had some issues with the event listener and trying to get _removeBook to work when clicking the remove button on the web page. I realised this was because I did not properly use event delegation and did not apply the event listener to the entirety of my table, which I have corrected now. Lastly, and importantly, I created _newBook(e), which will be run when the user submits the book with both input fields populated. Firstly, preventDefault must be used so that the webpage is not refreshed, especially without localStorage set up for now. I stored both input fields in variables, followed by a simple check to make sure that both fields are filled in.

```
if (bookTitle.value === '' || authorName.value === '') {
      alert('Please fill in all fields');
      return;
    }
```

If this passed, the function then runs:
```
const book = new Book(bookTitle.value, authorName.value);
    this._bookLibrary.addBook(book);
```

I instantiate a new Book here with the values of the input fields as the arguments to our Book object. I then invoke addBook() to add the book to the DOM. I am able to use addBook() because I instantiated a new Library in the App's constructor function. 
Lastly, a few simple lines of code just to reset the input fields after the previous code has run:
```
bookTitle.value = '';
authorName.value = '';
```

The rest of the code is just for light/dark mode functionality that I don't feel the need to breakdown, as the project did not require light/dark mode, it was just a nicety that I wanted to add for fun.

**Summary**
Overall, I continue to find OOP quite difficult to grasp, especially since the last 18 months have mostly been procedural programming. As explained at the beginning of this log entry, I find myself feeling somewhat guilty that I've used a previous project for reference, because I simply cannot see myself writing this level of code from scratch off the top of my head. Should I be able to? What determines a great programmer? His/her ability to write great code from the top of his head? Or his/her ability to find re-useable code from a previous project, followed by the ability to adapt that code within a reasonable amount of time for a new project? Sometimes these long-winded projects and courses make me feel somewhat like the Karate Kid, spending his days mopping up water and sweeping dust, longing to do more, until suddenly I realise that code isn't necessarily about writing it, but understanding it. Maybe I'm wrong. Regardless, I'll make sure to thoroughly understand what I've written for this project so far, or potentially write it from scratch.


---


### Day 98: July 24, 2023

**Today's Progress:** Continuing with the TOP Library project, today I implemented the remove and read/not read button. I also made sure that functionality was working with both the mobile and desktop elements.

**Thoughts:** Today was particularly educational, because the guilt of 'referencing previous' code is lessening as I continue to add more and more of my own code to ensure that the code is going to work for this library project. 

I realised that although I could now add books, the books were only being added to the desktop table and the other buttons were not working (Yes/no/remove). I first decided to make sure that the book being added was also added to the mobile view, which turned out to be quite simple, as it only required me to update the _displayNewBook() function to also include a mobile element being added. What was most important here is that both the mobile and desktop elements had the same id, to ensure that both elements are removed if the user decides to remove it.

I became a little stuck when I got to the remove button functionality as I wasn't entirely sure at first how to remove all elements that shared the same id, but in the end I was able to do it with the following code added to _removeBook():
```
_removeBook(e) {
    if (e.target.classList.contains('delete')) {
      {
        if (confirm('Are you sure?')) {
          const id = e.target
            .closest('.border-b, .mobile-div')
            .getAttribute('data-id');
          this._bookLibrary.removeBook(id);
          const elementsToRemove = document.querySelectorAll(
            `[data-id="${id}"]`
          );
          elementsToRemove.forEach((el) => el.remove());
        }
      }
    }
  }
```

The key line here is `const elementsToRemove = document.querySelectorAll(`[data-id="${id}"]`)`.
This line specifically selects all elements that match the id that is passed in, followed by:
`elementsToRemove.forEach((el) => el.remove());` to loop through the nodelist and remove all of those elements with the particular id. 

Lastly, I had to add functionality to the 'read' button, which was also quite simple as it only required an 2 event listeners for both the mobile and desktop elements followed by a simple function that just checks the textContent of the button. 
```
_checkIfRead(e) {
    if (e.target.classList.contains('read-btn')) {
      console.log('clicked');
      if (e.target.textContent.trim() == 'yes') {
        e.target.textContent = 'no';
      } else {
        e.target.textContent = 'yes';
      }
    }
  }
```

Note that I added the class 'read-btn' to both the mobile and desktop button to ensure that this function worked for both.

**Summary**: Overall, I'm feeling a lot better about this project as I continue to make more tweaks and add more of my own custom code. I'm slowly feeling more confident that I can move along from this project having a much better understanding of how to use OOP. I'm still not 100% sure on what functions I'd place in which classes and why some functions are public and others not, but I suppose that's rather trivial as opposed to actually learning the concepts.

Next up, I'd like to add localStorage to this project but I may return to this project to do that at a later date, as I've mostly wanted to use this project specifically to concrete my understanding of OOP. On to more things!

---

### Day 99: July 29, 2023

**Today's Progress:** Continuing with the TOP course, I learned about factory functions, what they are, why they're useful and how constructor functions aren't necessarily the only way to get a result.

**Thoughts:** Seeing as I've spent the last few months learning OOP and exclusively using constructor functions/classes, it was a little intimidating and even demoralising to an extent when I learned that there is an entirely different way of returning an object from a function, similar to a constructor. Obviously, I realise the importance of learning the different ways that I can achieve that particular result, as I may run into factory functions in the future. 

**Factory functions**
A factory function performs very similarly to a constructor, but it does not use the 'new' keyword, instead it simply sets up and returns the new object when the function is invoked. Example below:

```
const personFactory = (name, age) => {
  const sayHello = () => console.log('hello!');
  return { name, age, sayHello };
};

const jeff = personFactory('jeff', 27);

console.log(jeff.name); // 'jeff'

jeff.sayHello(); // calls the function and logs 'hello!'
```

personFactory is created that accepts 2 parameters. Inside of the function, sayHello is another function that simply logs 'hello!' to the console. The function then returns the parameters and the function as an object. `const jeff = personFactory('jeff', 27)` instantiates the 'jeff' object. This then allows me to call the sayHello function on the jeff object, as the sayHello function was returned from the personFactory function. Important to note that I would not be able to use the sayHello function if it were not returned from the function due to scope and closure.

For reference, here is the same thing created using the constructor pattern:
```
const Person = function(name, age) {
  this.sayHello = () => console.log('hello!');
  this.name = name;
  this.age = age;
};

const jeff = new Person('jeff', 27);
```

Important to note that factory functions do not utilize the prototype, which is a performance penalty when creating thousands of objects.

**Scope & Closure**
I also touched on scope and closure again, which is a concept I am familiar with, but I had not come across the term 'closure' before. 'Closure' is described as the following:
`The concept of closure is the idea that functions retain their scope even if they are passed around and called outside of that scope.`

```
const FactoryFunction = string => {
  const capitalizeString = () => string.toUpperCase();
  const printString = () => console.log(`----${capitalizeString()}----`);
  return { printString };
};

const taco = FactoryFunction('taco');

printString(); // ERROR!!
capitalizeString(); // ERROR!!
taco.capitalizeString(); // ERROR!!
taco.printString(); // this prints "----TACO----"
```

Because of the concept of scope, neither of the functions created inside of FactoryFunction can be accessed outside of the function itself, which is why lines 9, 10, and 11 fail. The only way to use either of those functions is to return them in the object (see line 4), which is why we can call taco.printString() but not taco.capitalizeString(). The big deal here is that even though we can’t access the capitalizeString() function, printString() can. That is closure.

**Factory function inheritance**
Inheritance within factory functions is also important to note as they do not use the prototype. So in the case of factory functions, you can destructure and pull a specific function out of an object created by a factory function. Example below:
```
const Person = (name) => {
  const sayName = () => console.log(`my name is ${name}`);
  return {sayName};
}

const Nerd = (name) => {
  // simply create a person and pull out the sayName function with destructuring assignment syntax!
  const {sayName} = Person(name);
  const doSomethingNerdy = () => console.log('nerd stuff');
  return {sayName, doSomethingNerdy};
}

const jeff = Nerd('jeff');

jeff.sayName(); // my name is jeff
jeff.doSomethingNerdy(); // nerd stuff
```

The Person() factory function returns the {sayName} function as an object. In the Nerd() factory function, `const {sayName} = Person(name)`, allows me to destructure/'pull' the sayName object from the Person factory function, allowing me to now use the sayName() method in an instantiated object of Nerd(). 
E.g. `jeff.sayName(); // my name is jeff`.

**Module pattern**
Modules is something new to me, but I can already see the power and benefit of using modules. Modules are very similar to factory functions, but they are created differently. An example that was used in my course is the following:
```
const calculator = (() => {
  const add = (a, b) => a + b;
  const sub = (a, b) => a - b;
  const mul = (a, b) => a * b;
  const div = (a, b) => a / b;
  return {
    add,
    sub,
    mul,
    div,
  };
})();

calculator.add(3,5); // 8
calculator.sub(6,2); // 4
calculator.mul(14,5534); // 77476
```

The concepts are exactly the same as a factory function, but instead of using a factory function to create multiple objects, the module pattern wraps the factory in an IIFE (Immediately Invoked Function Expression).
`A useful side-effect of encapsulating the inner workings of our programs into objects is namespacing. Namespacing is a technique that is used to avoid naming collisions in our programs. `

**Summary**
This section of the course has been a lot to cover and a little overwhelming, especially as there are multiple concepts within the one lesson. I'm not sure how important factory functions are or if they're used regularly, but I've endeavoured as best I can to learn the basics of them. I'll attempt to use them in an upcoming project in hope to retain what I've learnd here.

---

### Day 100: August 1, 2023

**Today's Progress:** As part of the TOP course, I have now been tasked with creating a tic-tac-toe app without using too much global code. I am advised to use modules and factory functions.

**Thoughts:** As I was fairly stuck with how to approach this project, I decided to first watch a tutorial on YouTube to see how others develop this project. Following this, my plan is to then attempt to re-create the project using factory functions and modules, referring back to the video or this log when I get stuck.

I found the CSS that was used to style the tic-tac-toe project in the YouTube tutorial very advanced and well outside of my comfort zone, especially since it's been a long time since I last used vanilla CSS. When creating the X's and O's that would appear transparently over the gameboard on hover, the developer used CSS to do this, not JavaScript. The main logic to the game is based on where their is a class of 'circle' or 'x' on the main 'board' div. 

```
.board.x .cell:not(.x):not(.circle):hover::before,
.board.x .cell:not(.x):not(.circle):hover::after,
.board.circle .cell:not(.x):not(.circle):hover::before {
  background-color: lightgrey;
}
```

The above CSS alters the X or O content that is displayed within the gameboard cells by checking if the cell does NOT contain a placed O or X (class of .circle or .x). If the cell does not contain a placed X or O, the background color will give provide the effect of transparency when the user hovers over an unpopulated gameboard cell.

I have not really created objects with CSS before as I usually use SVGs, but I do recall having to build an X for a hamburger menu in the past, which was essentially the same code in this project also.

**The JavaScript**:
I found the JavaScript mostly easy to follow except for a few concepts that are new to me. 
Firstly, I needed a handeClick() function that will also invoke several other functions:
```
function handleClick(e) {
  const cell = e.target;
  const currentClass = circleTurn ? CIRCLE_CLASS : X_CLASS;
  // placeMark
  placeMark(cell, currentClass);
  // Check for Win
  if (checkWin(currentClass)) {
    endGame(false);
    // Check for Draw
  } else if (isDraw()) {
    endGame(true);
  } else {
    swapTurns();
    setBoardHoverClass();
  }
}
```

Checks current turn with 'currentClass'.
Places an X or an O on the gameboard depending on currentClass.
If statement to check if someone wins or draws followed by calling the endGame() function. Else, swapTurns.

To check for a win, I had to first store all possible win conditions in an array:
```
const WINNING_COMBINATIONS = [
  [0, 1, 2],
  [3, 4, 5],
  [6, 7, 8],
  [0, 3, 6],
  [1, 4, 7],
  [2, 5, 8],
  [0, 4, 8],
  [2, 4, 6],
];
```

Followed by the code that will loop through these win conditions and check them against the cells placed on the game board.

```
function checkWin(currentClass) {
  return WINNING_COMBINATIONS.some((combinations) => {
    return combinations.every((index) => {
      return cellElements[index].classList.contains(currentClass);
    });
  });
}
```

I found this function quite confusing as I have not used 'some()' or 'every()' before. My understandin of the function is as follows:

> .some() tests whether at least one element in the array passes the test implemented by the function.
> Within the .some() method, an arrow functions takes 'combinations' as an argument to represent each winning combination.
> Inside of the some() function, .every() is used on 'combinations' to to test whether all elements in the array pass the test implemented by the provided function. It is here that it checks whether every cell in the current combination has been marked by the 'currentClass' player.
> In the .every() function, the arrow function takes 'index' as an argument. 'index' represents each individual cell in the current winning combination.
> Lastly, `cellElements[index].classList.contains(currentClass)` checks if the CSS class list of the current cell (cellElements[index]) contains currentClass. If it does, this means that the current cell has been marked by the 'currentClass' player.
> cellElements[index].classList.contains(currentClass) check is returned to the .every() method. If all cells in the current combination contain currentClass, the .every() method returns true.
> This true or false value is then returned to the .some() method. If at least one combination returns true, the .some() method also returns true.

To summarise, this function is checking whether the player represent by 'currentClass' has any winning combinations on the gameboard.

I also found the 'isDraw()' function to be a little confusing, as once again .every() is used, which is a new concept to me.
```
function isDraw() {
  return [...cellElements].every((cell) => {
    return (
      cell.classList.contains(X_CLASS) || cell.classList.contains(CIRCLE_CLASS)
    );
  });
}
```

Firstly, to use .every(), it must be invoked on an array, which was achieved by converting cellElements to an array with the spread operator `[...cellElements]`.
.every() will now apply the following test to every cell:
`cell.classList.contains(X_CLASS) || cell.classList.contains(CIRCLE_CLASS)`
If every cell contains the class of 'X_CLASS' OR 'CIRCLE_CLASS', then return TRUE.

Overall, I feel that this project is outside of my current ability? I understand the code for the most part, but as usual, I don't feel like this is code I would have written by myself without having watched a tutorial. I'll be trying to re-create this project using factory functions and modules, and likely returning to this code as I've already taken time to understand how the 'checkWin()' function works, for example. 
