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


### Day 9: November 22, 2022 

**Today's Progress**: In preparation for the final TOP CSS Grid project, I spent several hours today using YouTube videos and following along with projects by Kevin Powell and Brad Traversy. I completed all of the projects and also paused the videos and spent a significant amount of time using Grid myself to develop my understanding.

**Thoughts:** The video projects were extremely helpful and cleared up a few grey areas, such as the grid syntax which I had written about on day 5 in this log. I also now have a greater understanding of Grids potential when it comes to responsive design, such as by using auto-fit/auto-fill, the fr unit and media-queries. Overall, I feel much more confident in my ability to use Grid manually and not just via Bootstrap/other frameworks.


### Day 10: November 25, 2022 

**Today's Progress**: Today I made a start on the final TOP CSS Grid project that requires me to create a complicated admin-panel style layout. So far I've managed to complete the navigation side panel and the overall Grid layout.

**Thoughts:** Although more confident with the use of Grid, I still find myself very overwhelmed, as even though I had laid out the overall Grid for the page, I feel that I haven't used units/responsive sizing to its full potential, by using minmax or auto-size functions. When tackling the navigation panel, I found myself confused as to how to do it, as there are obviously several ways this could be done. From my brief research, it seems that most people opt for using ul/li/a tags in sections. However, seeing as the project is focused on the use of Grid, I attempted to use Grid as much as possible in the design. I was unsure if I should apply a div to every elemetn that I was going to place in the grid, as there are 2 columns, one for the icon and one for the menu text; I was able to position these correctly without putting everything into a div. However, my first issue was that I needed to space specific rows apart from eachother, which Grid cannot do, it can only apply spacing to all of the rows. My way around this was by putting 2 row's elements into flex-divs and applying a margin-bottom, but this feels shoddy and incorrect. I plan to re-approach the same design and split the grid up into 3 divs that will also be grids so that I can use gap to split the grouped-rows apart, as opposed to using flex-divs and margin-bottom. However, this approach will require me to apply the same column sizing in the first column to each grid to ensure that everything aligns correctly.

### Few days watching project videos ###

### Day 11: November 29, 2022 

**Today's Progress**: Continuing with the CSS Grid admin panel project.

**Thoughts:** I decided to re-create the nav panel on the left side as I was not happy with the result. Thankfully, this was not too difficult a task as most of the code was complete, I just needed to place the content in divs and place everything accordingly using Grid. Following this, I moved on to the header panel at the top that includes a search bar, several icons and text/buttons. To do this, I broke the header up into 2 columns and used a combination of box Grid and Flexbox to align things correctly. One particular thing to note is that I did attempt to use clamp/minmax css functions but found that they didn't work as intended. In place of those functions, I instead used width: 60% and declared a min-width and max-width; this was extremely helpful when designing the input/search bar. It has been quite a challenge so far, I need to remember that both Grid and Flex are at my disposal, using both seems to really speed up the process. Overall, I'm very happy with the progress so far, although it is taking much longer than anticipated.


### Day 12: November 30, 2022 

**Today's Progress**: Today I finally finished up the CSS Grid panel project!

**Thoughts:** I was able to complete both the main content section and the right side panel today, finishing up the project. I've begun to use a different naming-style in this project that uses two underscores as I find it neater and easier to read, opposed to just using a single dash to seperate words. I'm also now endeavouring to use less classes unless I absolutely have to and instead opt to use more selectors, such as nth-child, nth-of-type, first-child, last-child etc etc. Much easier to read my HTML. A few key things to note during this project: I used absolute positioning of a small yellow div to create a yellow line at the beginning of the cards that I made in the main-content section; I remembered to make the parent container position: relative and then used top & left properties to move the bar accordingly. I did come across an issue however of the div overlapping the border-radius I had set on the card, after some Googling I recalled overflow: hidden, which instantly solved the issue, preventing the div from 'leaving' the card.
Furthermore, I used auto-fit and minmax() in several places to make the grid more responsive, especially in themain content section that makes the cards fully responsive. However, I think that the units I used and the sizing I had created for my layout as whole probably could have been better? I'd like to use the clamp function more as I'm now beginning to see how incredibly useful functions such as clamp and minmax really are. Overall, it has been a very challenging but enjoyable project. I'm very happy with the result, even though I recognise that there are a lot of potential tweaks to be made.


### Day 13: December 01, 2022 

**Today's Progress**: Staying on track, after finishing the CSS grid project, I moved on to a Tailwind CSS Udemy course that I had purchased last week as I plan to use it for an upcoming project. I completed the first section of the course: Fundamentals part 1. I plan to move back to The Odin Project course after the tailwind course + project completion.

**Thoughts:** Even though I haven't moved on to the project section of the course yet, I'm finding Tailwind CSS very enjoyable to use. I like that it shares a lot of similarities with Bootstrap, of which I have experience with due to a previous project; Tailwind CSS, however, operates at a much lower-level compared to Boostrap, allowing minor adjustments to be made, as opposed to Bootstraps 'component' styling. Whilst using Bootstrap for my projects in the past, I recall my annoyance with the framework due to the restrictiveness of customisation without using Sass, resulting in using !important to override a lot of styling, which I find clunky and bad practice. With Tailwind, this absolutely is not the case, in fact most things can be adjusted or manipulated. I'm looking forward to using Tailwind CSS as my main go-to framework for CSS!


### Day 14: December 02, 2022 

**Today's Progress**: Continuing with the Tailwind CSS Udemy course by Brad Traversy, I finished Fundamentals part 2 and also a section that followed this on 'Bettering my development environment'.

**Thoughts:** Having finished the fundamentals section, although I've scratched the surface, Tailwind continues to impress me with the sheer amount of possible customisations. Fundamentals part 2 covered topics such as flexbox, grid, breakpoints and even dark mode options. I was especially impressed with the ability to seamlessly add simple animations/transitions to elements using pseudo-classes within the HTML. Better yet, in the 'Better Development Environment' section of the course, I have been introduced to NPM and its ability to not only easily add frameworks such as Tailwind, but also its ability to create scripts that allow me to quickly 'build' and 'watch' my compiled CSS folders. After completing the NPM steps, I went on to see further possibilities due to how Tailwind imports and compiles its CSS; I am able to use PostCSS in my input.css file to create components, similar to Bootstrap. I can create a class within that input file (e.g. .btn-blue) and use @apply, followed by Tailwindcss classes to apply those classes to that new component class. Tomorrow I start on some projects!


### Day 15: December 03, 2022 

**Today's Progress**: The last lesson within the Developer Environment section of the course was setting up the use of WebPack, although this section was optional, I decided to follow along anyway for potential future use. Following this, I made a start on the first handful of mini Tailwind projects. The first mini project was a small, responsive newsletter card. I also had some issues with Git today whilst setting up my repositories that took an hour or so to resolve.

**Thoughts:** Although I've followed along with the videos and I now have a working WebPack developer environment, I am not particularly sure on what WebPack is and its uses; I found myself feeling lost following the video as I set-up more NPM scripts, though I paused and went back in the video as needed to try and grasp what it is I am actually achieving. Thankfully, once the developer environment is set up, I can re-use that folder as a template as and when I need it, so I should not have to repeat the process. Even though I have somewhat of a basic understanding of Webpack, preferably, in the future, I'd like to actually fully understand each step and what it is I'm doing and why that may be useful to me. The mini-project, on the other hand, I had no issues with and understood every step of the video whilst coding along; the project did not take long and I'm beginning to see Tailwinds true strengths in real scenarios. 


### Day 16: December 05, 2022 

**Today's Progress**: Continuing with the mini-projects in the TailwindCSS course, I finished the remaining 4 projects which included: Image-gallery, login-modal, pricing card and product modal. All of which will be uploaded to GitHub.

**Thoughts:** Once again, as I was following along with the tutor coding, I rarely found myself becoming stuck or running into too many issues. However, there were a few occasions where I did find myself confused as to how my tutor came to a certain result with an element. For example, my tutot opted to place an element inside of a a simple class-less div so that the content of that element would specify the size of the empty div, also meaning that flex-type was not applied to it. This allowed me to create a div of a specific size, to fit the content, opposed to the div automatically growing to the width of the parent container. At first, I was unsure how this happened and spent time to understand it. Across most of the mini-projects, it was mostly the case of pausing the video and taking extra time to understand small tweaks here and there that the tutor would make. Overall, I feel confident that I've taken ample time to understand what I've been coding along to, but obviously putting what I've learned into actual use is always a very different story. I'm approximately halfway through the course at this point, with several very large projects coming up that specifically use a tailwind dev environment, rather than just the CDN link.


### Day 17: December 06, 2022 

**Today's Progress**: Moving on from the mini-projects, I began and finished the first 'large' TailwindCSS project that utilised that developer environment I had set up earlier in the course. https://github.com/Moomins07/clipboard-project

**Thoughts:** I was able to finish the project in decent time, again stopping as needed to re-familiarise myself at times with certain classes and/or to understand a block of code. Notable things to take away from this course: I noticed that the author of this course, Brad, uses margin-auto on the x-axis a lot to center his divs, which is something I find myself rarely doing. Most of the time, I will use a large flex container to center my elements; I'm not sure if this is just a preference or if there are advantages to one or the other, but I do like the simpicity of centering a div using margins. I was not too confident when checking the code used for the footer, as it used a lot of divs and classes, making it a little difficult to check over, but I felt confident enough with my understanding to continue. I especially liked the reinforcement of using the input.css file to add custom CSS and group classes using @apply again. There were a few things that bothered me with the layout of the site, such as the logo images overlapping eachother slightly on tablet screens; to fix this, I redcued the padding on the x-axis significantly and added flex-gap to space them out. On that note, Brad uses space-y-[num] and space-x-[num] a lot to space out his elements, even in flex containers. I found this unusual as flex containers can use 'gap' to space apart elements without having the elements mis-aligned within their containers. I found, however, that there are cases when gap either does the same thing as using space-x-[num], or it simply breaks the layout. E.g. When I used gap, an image blew up in size, as opposed to when I used space-y-[num], which caused the image to become the appropriate size. Very confusing.


### Day 18: December 07, 2022 

**Today's Progress**: Today, I began and finished the second TailwindCSS project 'loopstudios'. 

**Thoughts:** This particular project was much larger than the previous projects and even used a bit of JavaScript for a hamburger menu that was created for mobile responsiveness. Once again, we used custom CSS to create components to reduce the amount of classes cluttering our HTML and even created a custom animation for the hamburger icon, which was a lot of fun. I followed the project without hitting any real barriers, but once again I found the footer to be a little confusing at times with the use of so many divs. Things to note: Once again, Brad, centers a lot of his items use mx-auto and max-w-[x] which seems to work great at larger screens and mobile screens, but there are certain breakpoints, such as on an iPad Mini, that cause the elements to be aligned to the left? I think this is due to Brad's lack of flex-containers to center these items, combined with the use of a lot of margins to align items. I was also a little confused as to why Brad did not use Grid for the 8 project images, that were aligned exactly as Grid would have done. I'd imagine this is just to show that you are able to get the same results without the use of Grid? My confusion here, again, is that I am not sure what is best practice due to the variety of methods being used. Though I'd imagine it doesn't particularly matter, a result is a result. https://loopstudios-test.vercel.app/


### Day 19: December 08, 2022 

**Today's Progress**: Today, I began and finished the third TailwindCSS project 'shortly'. 

**Thoughts:** Another large project that I followed without any real issues. As usual, I continue to dislike that Brad uses space-y-[x] as opposed to using flex: gap, as it pushes elements over to the right, making groups of elements un-centered, especially noticeable in mobile view. I'm really beginning to see the repeated classes now and their use-cases in different layouts; Brad showed a great example of using flex-column-reverse, which I had not seen before. This allowed me to have text on the left with an image on the right in desktop view and the image above the text in mobile (column) view. I once again used the hamburger menu code from the previous project and I also used a little JavaScript to code some validity functionality into an input element using regex. Overall, I left the project feeling comfortable, though I will note that I continue to feel slightly lost at times keeping track of the amount of divs and the layout; I tend to spend a lot of time in the devtools to help with this. https://shortly-test.vercel.app/


### Day 20: December 09, 2022 

**Today's Progress**: Today, I began and finished the fourth TailwindCSS project 'Testimonial Grid'. 

**Thoughts:** This particular project was quite small and did not take long to complete, but it did however finally use Grid for the layout which answered a lot of questions that I have had throughout the course until this point. E.g. Not using Grid in the loopstudios project and why Brad may have chosen not to use Grid. It also obviously finally showed me the tailwind syntax for Grid, which just seems to use 'span'. Things to note though, Brad did not use the 'order' Grid syntax that would normally be used with vanilla CSS, but instead used a mix of 'hidden' with different breakpoints to order his layout accordingly. I thought this was a rather 'round-about' way instead of just using the 'order' syntax. I was also introduced to plugins that can be added to TailwindCSS, such as the line-clamp plugin in this example. Line clamp essentially shortens a container to a specified length and allows a 'see-more' option to be added to display the rest of the text. However, I did not see a 'see-more' option which I'd imagine must be added manually by myself, so this is still a grey-area for me of which I will need to look into in the future.
