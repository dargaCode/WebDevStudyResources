### My Other Resource Lists
* *[Portfolio Examples](https://github.com/dargaCode/PortfolioExamples)*
* *[Logic and Coding Games](https://github.com/dargaCode/LogicAndCodingGames)*

# Web Development Study Resources
In my experience, learning how to program itself isn't nearly as hard as deciding what to study, and where, and when.

With that in mind, here's a list of the webdev resources I've found most useful so far.

The topics are ordered based on [several bootcamp curricula](https://docs.google.com/spreadsheets/d/1sF3QfsbIqvHU9voigpPKD4BavspHQ_K0GeR0Hl3JE_0/edit#gid=1911839646) I've gathered, as well as my own experience tackling things in what I feel was the wrong order. 

There are some paid resources in this list, but I've only included the ones I've found valuable, and I've tried to mark them clearly. I don't receive any referral benefits from these resources.

## Table of Contents
* [Important Workflow Items](#important-workflow-items)
    * [The Command Line](#the-command-line)
    * [Git and GitHub](#git-and-github)
* [Front-End Development](#front-end-development)
    * [HTML and CSS](#html-and-css)
    * [Deploying Front-End Websites](#deploying-front-end-websites)
    * [Bootstrap](#bootstrap)
    * [Basic JavaScript](#basic-javascript)
    * [Functional JavaScript](#functional-javascript)
    * [Manipulate the DOM with "Vanilla" JavaScript](#manipulate-the-dom-with-vanilla-javascript)
    * [Manipulate the DOM with jQuery](#manipulate-the-dom-with-jquery)
    * [Regular Expressions](#regular-expressions)
    * [JavaScript Challenges I](#javascript-challenges-i)
    * [JavaScript Challenges II](#javascript-challenges-ii)
    * [JavaScript Challenges III](#javascript-challenges-iii)
    * [Intermediate JavaScript](#intermediate-javascript)
* [Back-End Development](#back-end-development)
    * [Deploying Back-End Web Apps](#deploying-back-end-web-apps)
    * [Node.js and Express.js](#nodejs-and-expressjs)
    * [MongoDB](#mongodb)

## Important Workflow Items
Both Command Line Interface and Git/GitHub are often presented toward the end of online classes, but I learned them beforehand and I'm glad I did.

Basic knowledge of The CLI and Git can do a lot to improve day-to-day quality of life, and they both also have a lot of small tricks to pick up over months and months. For both these reasons, they're good topics to tackle as early as possible.

Checking in code and deploying real webpages also allows development outside of CodePen, Cloud9, and other online editors. Making sure that all the scripts are integrated properly etc is a lot more difficult at first, but extremely educational.

### The Command Line
Typing text commands into the console seems extremely arcane at first, but becomes familiar surprisingly quickly.

It's useful for Git, Node development, and lots of other things, and honestly it also just feels cool and fun and hacker-y.

*   [Codecademy - Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line)
    * Free - 4 Units, 4 Lessons (3 hours)
    * Paid ($20/Month) - 4 Quizzes, 7 Projects
*   [Udemy - The Web Dev Bootcamp / Unit 21: The Command Line](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/t/lecture/3925818)
    * Paid ($35 Course) - 5 Lessons (45 minutes), 1 Exercise
*   [dargaCode - “mkdir /data” and “mkdir data” are NOT the Same](http://blog.dargacode.com/post/144129893311/mkdir-data-and-mkdir-data-are-not-the-same)
    * Free - Blog Post

### Git and GitHub
Git helps prevent loss of work, and GitHub makes it easy to collaborate and share work with others. 

*   [Code School - Try Git](https://try.github.io/levels/1/challenges/1)
    * Free - 25 Exercises (15 minutes)
*   [Codecademy - Learn Git](https://www.codecademy.com/learn/learn-git)
    * Free - 4 Units, 4 Lessons (2 hours)
    * Paid ($20/Month) - 4 Quizzes, 8 Projects
*   [Udemy - The Web Dev Bootcamp / Unit 37: Git and GitHub](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/t/lecture/4042652)
    * Paid ($35 Course) - 3 Lessons (1 hour)
*   [Chacon & Straub - Pro Git](https://git-scm.com/book/)
    * Free - Online Book, 10 chapters
*   [Roger Dudler - Simple Git Guide](http://rogerdudler.github.io/git-guide/)
    * Free - Cheatsheet webpage
*   [John Kary - "git add -p", The Most Powerful Git Feature You're not Using Yet](http://johnkary.net/blog/git-add-p-the-most-powerful-git-feature-youre-not-using-yet/)
    * Free - Blog Post
*   [Chris Beams - How to Write a Git Commit Message](http://chris.beams.io/posts/git-commit/)
    * Free - Blog Post
*   [Tuts+ - Leveraging the Power of "git stash"](http://code.tutsplus.com/tutorials/quick-tip-leveraging-the-power-of-git-stash--cms-22988)
    * Free - Blog Post

## Front-End Development
Most simply, "front-end" refers to the content that is actually presented on a webpage. The text, the images, the colors.

For example: A portfolio website that contains a bio, links to projects, and photos.

### HTML and CSS
HTML builds the structure of a webpage, and CSS dictates its layout and appearance.

I originally tried learning HTML a long time ago, and was pleasantly surprised to see that all the layout is now handled by CSS rules rather than horrible nested tables and frames.

*   [Codecademy - Make a Website](https://www.codecademy.com/learn/make-a-website)
    * Free - 4 Units, 4 Lessons (4 hours)
    * Paid ($20/Month) - 4 Quizzes, 4 Projects
*   [Codecademy - Learn HTML & CSS](https://www.codecademy.com/learn/web)
    * Free ($35 Course) - 6 Units, 12 Lessons (7 hours)
    * Paid ($20/Month) - 6 Quizzes, 16 Projects
*   [Udemy - The Web Dev Bootcamp / Units 2-6: HTML & CSS](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/t/lecture/3901230)
    * Paid ($35 Course) - 52 Lessons (6 hours), 8 Exercises
*   [YouTube / EJ Media - HTML Tutorial for Beginners
](https://www.youtube.com/playlist?list=PLr6-GrHUlVf_ZNmuQSXdS197Oyr1L9sPB)
    * Free - 29 Lessons (1.5 hours)
*   [YouTube / EJ Media - CSS Tutorial for Beginners
](https://www.youtube.com/playlist?list=PLr6-GrHUlVf8JIgLcu3sHigvQjTw_aC9C)
    * Free - 60 Lessons (4 hours)
*   [YouTube / EJ Media - CSS Layout Tutorial
](https://www.youtube.com/playlist?list=PLr6-GrHUlVf9ZleRsd5oTcrziNglndsXW)
    * Free - 19 Lessons (1.5 hours)
*   [Code School - Discover DevTools / Unit 1: Elements](http://discover-devtools.codeschool.com/chapters/1?locale=en)
    * Free - 2 Lessons (10 minutes), 10 Exercises
*   [Code School - Discover DevTools / Unit 2: Sources](http://discover-devtools.codeschool.com/chapters/2?locale=en)
    * Free - 1 Lesson (2 minutes), 3 Exercises
*   [Luke Pacholski - CSS Diner](https://flukeout.github.io/)
    * Free - Game, 32 Levels
*   [NthMaster - Master the :nth-child Selectors](http://nthmaster.com/)
    * Free - Cheat sheet, 11 examples
*   [Liquidapsive - 1 site styled with multiple layout types, for comparison](http://www.liquidapsive.com/)
    * Free - 4 examples
*   [Learn Layout](http://learnlayout.com/)
    * Free - 19 Lessons
*   [Barely Fitz - Learn CSS Positioning in Ten Steps](http://www.barelyfitz.com/screencast/html-training/css/positioning/)
    * Free - 9 Lessons, interactive examples
*   [Geddski Mastery Games - Flexbox Zombies](https://mastery.games/p/flexbox-zombies)
    * Free - Game, 168 Levels
*   [General Assembly - Build a Custom Tumblr Theme](https://dash.generalassemb.ly/projects/tumblr)
    * Free - 6 units, 60 Exercises (3 hours)
*   [CSS Tricks - Box Sizing](https://css-tricks.com/box-sizing/)
    * Free - Blog Post
*   [Stack Overflow - When to use HTML &lt;img&gt; vs CSS background-image property?](http://stackoverflow.com/questions/492809/when-to-use-img-vs-css-background-image)
    * Free - Tutorial
*   [Stack Overflow - How to Remove the Space Between inline-block Elements?](http://stackoverflow.com/questions/5078239/how-to-remove-the-space-between-inline-block-elements)
    * Free - Tutorial
*   [Darga Code - CSS Margin Collapsing, another dangerous "unknown unknown"] (http://blog.dargacode.com/post/148715151721/css-margin-collapsing-another-dangerous-unknown)
    * Free - Blog Post  

### Deploying Front-End Websites
Deployment is putting webpages on the internet where other people can actually see and use them.

*   [Team Treehouse - Using GitHub Pages to Host Your Website](http://blog.teamtreehouse.com/using-github-pages-to-host-your-website)
    * Free - Blog Post
*   [Codecademy - Deploy a Website](https://www.codecademy.com/learn/deploy-a-website)
    * Free - 3 Units, 3 Lessons (4 hours)

### Bootstrap
Boostrap is mainly a ton of pre-built CSS classes which can be applied directly to HTML instead of writing custom CSS.

I originally tried to learn Bootstrap before understanding CSS well, which ended up being very confusing and frustrating. Over time I've come to appreciate its usefulness for making quick prototypes etc.

*   [Udemy - The Web Dev Bootcamp / Unit 7: Bootstrap](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/t/lecture/3908606)
    * Paid ($35 Course) - 11 Lessons (2 hours), 2 Exercises
*   [Hacker Themes - Bootstrap 4 Cheat Sheet](http://hackerthemes.com/bootstrap-cheatsheet/)
    * Free - Cheat sheet

### Basic JavaScript
JavaScript is the only programming language that can reach into a webpage and modify the content of the HTML or the styling of the CSS.

This section covers its basic syntax and control structures, which must be learned first. 

*   [Khan Academy - Intro to JS](https://www.khanacademy.org/computing/computer-programming/programming)
    * Free - 53 Lessons, 33 Exercises, 4 Quizzes, 9 Projects
*   [Codecademy - Learn JavaScript](https://www.codecademy.com/learn/javascript)
    * Free - 8 Units, 16 Lessons (10 hours)
    * Paid ($20/Month) - 9 Quizzes, 1
*   [Udemy - The Web Dev Bootcamp / Units 8-12: JavaScript](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/t/lecture/3861318)
    * Paid ($35 Course) - 54 Lessons (6 hours), 19 Exercises
*   [YouTube / EJ Media - JavaScript Tutorial for Beginners / Lessons 1-24](https://www.youtube.com/playlist?list=PLr6-GrHUlVf96NLj3PQq-tmEB6woZjwEl)
    * Free - 24 Lessons (1.5 hours)
*   [Code School - Discover DevTools / Unit 3: Console](http://discover-devtools.codeschool.com/chapters/3?locale=en)
    * Free - 3 Lessons (6 minutes), 11 Exercises
*   [Code School - Discover DevTools / Unit 4: Debugging](http://discover-devtools.codeschool.com/chapters/4?locale=en)
    * Free - 3 Lessons (7 minutes), 9 Exercises
*   [James Padolsey - Truthy and Falsey](http://james.padolsey.com/javascript/truthy-falsey/)
    * Free - Blog Post
*   [Wikipedia - Immediately-Invoked Function Expressions](https://en.wikipedia.org/wiki/Immediately-invoked_function_expression)
    * Free - Blog Post
*   [2ality - Initializing an Array with Values](http://www.2ality.com/2013/11/initializing-arrays.html)
    * Free - Blog Post
*   [Stack Overflow - Is 'switch(true){...' valid JavaScript?](http://stackoverflow.com/questions/14118996/is-switchtrue-valid-javascript)
    * Free - Tutorial
*   [Douglas Crockford - Code Conventions for JavaScript](http://javascript.crockford.com/code.html)
    * Free - Blog Post

### Functional JavaScript
Using functional programming is one of those weird things in programming that's actually more easily done than described.

Most of what FP means (at least early on) is using functions to iterate through arrays, rather than writing loops all over the place. It's more readable, and less error-prone. 

*   [Mind About JS - The Three JavaScript Musketeers](http://mindaboutjs.com/2015/07/18/the-three-javascript-musketeers/)
    * Free - Blog Post
*   [Youtube / Funfunfunction - Functional Programming in JavaScript](https://www.youtube.com/playlist?list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84)
    * Free - 12 Lessons (2.5 hours)

### Manipulate the DOM with "Vanilla" JavaScript
The DOM is another concept that sounds scarier than it is.

The Document-Object Model is just the content of a webpage, parsed into an object so that JS can read and manipulate it.

*   [Udemy - The Web Dev Bootcamp / Units 13-14: DOM Manipulation](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/t/lecture/3861434)
    * Paid ($35 Course) - 15 Lessons (2.5 hours), 4 Exercises
*   [Udemy - The Web Dev Bootcamp / Unit 15: Color Game](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/t/lecture/5250406)
    * Paid ($35 Course) - 9 Lessons (3 hours)
*   [YouTube / EJ Media - JavaScript Tutorial for Beginners / Lessons 25-51](https://www.youtube.com/playlist?list=PLr6-GrHUlVf96NLj3PQq-tmEB6woZjwEl)
    * Free - 27 Lessons (2 hours)

### Manipulate the DOM with jQuery
jQuery is a JavaScript library that mainly enables DOM manipulation with more tersely-written code.

*   [Codecademy - Make an Interactive Website](https://www.codecademy.com/en/skills/make-an-interactive-website)
    * Free - 5 Units, 5 Lessons (5 hours)
*   [Codecademy - Learn jQuery](https://www.codecademy.com/learn/jquery)
    * Free - 5 Units, 5 Lessons (3 hours)
    * Paid ($20/Month) - 5 Quizzes, 15 Projects
*   [Udemy - The Web Dev Bootcamp / Units 16-17: jQuery](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/t/lecture/3861488)
    * Paid ($35 Course) - 12 Lessons (2 hours), 1 Exercise
*   [Udemy - The Web Dev Bootcamp / Unit 18: Todo List](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/t/lecture/3861520)
    * Paid ($35 Course) - 9 Lessons (1 hour)
*   [YouTube / EJ Media - jQuery Tutorial for Beginners](https://www.youtube.com/playlist?list=PLr6-GrHUlVf_RNxQQkQnEwUiHELmB0fW1)
    * Free - 43 Lessons (2.5 hours)

### Regular Expressions
Regular Expressions (Regex) are a way to easily parse some text and find all the places that match a given pattern.

For example, matching all the email addresses in a string, or all the 5-letter names starting with "Ja".

*   [Stack Overflow - Learning Regular Expressions](http://stackoverflow.com/questions/4736/learning-regular-expressions)
    * Free - Overview
*   [RegexOne - Regex Lessons](http://regexone.com/)
    * Free - 16 lesssons, 8 Exercises
*   [Regexr - Learn, Build, and Test Regex](http://www.regexr.com/)
    * Free - Reference, Cheat sheet, interactive sandbox
*   [Regex Crossword - Regex Puzzles](https://regexcrossword.com/)
    * Free - 10 difficulties, 55 challenges
*   [JavaScript Kit - Regular Expressions Methods and Usage](http://www.javascriptkit.com/javatutors/redev3.shtml)
    * Free - Cheatsheet, 6 functions
*   [Regex Guru - Replacement Text Syntax for JavaScript's String.replace()](http://www.regexguru.com/2010/06/replacement-text-syntax-for-javascripts-stringreplace/)
    * Free - Blog Post

### JavaScript Challenges I
There are all kinds of useful topics that come up on Code Wars exercises.

*   [Code Wars - 8 kyu / Fundamentals](http://www.codewars.com/kata/search/javascript?beta=false&order_by=popularity+desc&q=&r=-8&tags=Fundamentals&xids=completed)
    * Free - 161 Challenges

### JavaScript Challenges II
Seeing everyone else's solutions (and discussions about them) is a great way to pick up new concepts and tricks.

*   [Code Wars - 8 kyu / All Remaining](http://www.codewars.com/kata/search/javascript?q=&r[]=-8&xids=completed&beta=false&order_by=popularity+desc)
    * Free - 39 Challenges
*   [Code Wars - 7 kyu / Algorithms](http://www.codewars.com/kata/search/javascript?beta=false&order_by=popularity+desc&q=&r=-7&tags=Algorithms&xids=completed)
    * Free - 190 Challenges

### JavaScript Challenges III
Code Wars includes support for the newest features in JavaScript, and it's also a great place to learn about writing Test Cases.

*   [Code Wars - 7 kyu / Remaining Fundamentals](http://www.codewars.com/kata/search/javascript?beta=false&order_by=popularity+desc&q=&r=-7&tags=Fundamentals&xids=completed)
    * Free - 303 Challenges

### Intermediate JavaScript
JS definitely has some interesting and potentially-confusing quirks, but learning about them is very satisfying.

*   [YouTube / LearnCode.Academy - JavaScript is Weird... and AWESOME](https://www.youtube.com/playlist?list=PLoYCgNOIyGABI011EYc-avPOsk1YsMUe_)
    * Free - 5 Lessons (0.5 hours)
*   [YouTube / Java Brains - JavaScript Scopes and Closures In-Depth](https://www.youtube.com/playlist?list=PLqq-6Pq4lTTZ_LyvzfrndUOkIvOF4y-_c)
    * Free - 23 Lessons (2.5 hours)
*   [YouTube / Java Brains - JavaScript Objects and Prototypes In-Depth](https://www.youtube.com/playlist?list=PLqq-6Pq4lTTaflXUL0v3TSm86nodn0c_u)
    * Free - 19 Lessons (2.5 hours)
*   [YouTube / Tony Alicea - JavaScript: The Weird Parts (Preview)](https://youtu.be/Bv_5Zv5c-Ts)
    * Free - 31 Lessons (3.5 hours)
*   [Udemy / Tony Alicea - Javascript: The Weird Parts](http://learnwebdev.net/)
    * Paid ($19 Course) - 80 Lessons (11.5 hours)
*   [Ryan Morr - Exploring the Eternal Abyss of Null and Undefined](http://ryanmorr.com/exploring-the-eternal-abyss-of-null-and-undefined/)
    * Free - Blog Post
*   [2ality - Apply and Arrays: 3 Tricks](http://www.2ality.com/2012/07/apply-tricks.html)
    * Free - Blog Post
*   [Cool Coder - Everything You Need to Know about JavaScript Scope](http://www.coolcoder.in/2014/03/everything-you-need-to-know-about.html)
    * Free - Blog Post
*   [Nathan Friedly - Objects, Arrays, and Array-Like Objects](http://www.nfriedly.com/techblog/2009/06/advanced-javascript-objects-arrays-and-array-like-objects/)
    * Free - Blog Post
*   [2ality - Tail Call Optimization in ES6](http://www.2ality.com/2015/06/tail-call-optimization.html)
    * Free - Blog Post
*   [Todd Motto - Mastering the JS Module Pattern](https://toddmotto.com/mastering-the-module-pattern/)
    * Free - Blog Post
*   [YouTube / Kyle Robinson Young - Mastering JavaScript Callbacks](https://youtu.be/qN0dkXj7jc0)
    * Free - 1 Lesson (15 minutes)

## Back-End Development
"Back-end" largely refers to gathering and assembling information on the server side, before sending it to the browser to be displayed.

The archetypical back-end pages are those that users can log into, and which store a lot of information about its users and their activities. For example: Facebook, Reddit, and Yelp.

### Deploying Back-End Web Apps
Webpages which require a server are basically too complicated to be deployed the same way as a simpler front-end page.

Heroku and similar services can host server-side projects (also called "apps") and serve them to users.

*   [Udemy - The Web Dev Bootcamp / Unit 38: Deploying](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/t/lecture/4473706)
    * Paid ($35 Course) - 6 Lessons (1 hour)

### Node.js and Express.js
JavaScript was originally only usable inside the client of a web browser. Node sets it free for use as a server-side language.

Express is a JS framework that makes it possible to write a server-side Node app more simply and tersely.

*   [Udemy - The Web Dev Bootcamp / Units 22-25: Node & Express](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/t/lecture/3861568)
    * Paid ($35 Course) - 26 Lessons (5 hours), 4 Exercises
*   [dargaCode - Custom EJS Delimiter](http://blog.dargacode.com/post/143421307771/custom-ejs-delimiter)
    * Free - Blog Post

### MongoDB
MongoDB and other databases are the main way that sites store data permanently, so the data won't be reverted every time the program restarts.

For example: Facebook friends lists, Netflix queues, and Reddit comments.

*   [Udemy - The Web Dev Bootcamp / Units 26-31: Databases](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/t/lecture/3861630)
    * Paid ($35 Course) - 32 Lessons (6 hours), 1 Exercise
*   [Udemy - The Web Dev Bootcamp / Units 32-36: YelpCamp](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/t/lecture/3861676)
    * Paid ($35 Course) - 26 Exercises (5 hours)
