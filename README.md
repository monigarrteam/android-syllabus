# android-syllabus
Syllabus for the Android development training with MoniGarr.com 


* **Course:** [AndroidDev2016, MoniGarr.com](http://www.MoniGarr.com)
* **Instructor:** Monica Peters, [monigarr@yahoo.com](mailto:monigarr@yahoo.com)
* **Need help?**
    * Look through and create [issues](https://github.com/monigarrteam/android-syllabus/issues)
   * [Email](mailto:monigarr@yahoo.com) for 1-on-1 help, or to set up a time to meet

## COURSE DESCRIPTION

Learn how to develop an Android app with java and android studio in this intensive, 12 week course. Topics include software installation, best practices, android ui, material design, java programming language, debugging and . Discover some of the lesser-known useful features of android software development, such as how to improve your android app performance, security and stability provides the best end user experience available. Create Android apps for mobile phones, wearables and more using industry standard Android Studio.

You will use your own apple laptop.

## PREREQUISITES
All of the following is required from you, BEFORE your first class.

* Your Own Laptop
* Android Device
* Social Network Profiles Setup for class work & to share with entire class.
	* Facebook profile: http://www.FaceBook.com
	* Twitter profile: http://www.Twitter.com
	* LinkedIn Profile: http://www.linkedin.com
	* Google+ profile: http://plus.google.com
	* YouTube Channel: https://www.google.com/search?q=how+to+create+a+youtube+channel&ie=utf-8&oe=utf-8
	
* Install Github Desktop: https://desktop.github.com/ 
* Read Git Basics: http://git-scm.com/book/en/v2/Getting-Started-Git-Basics
* Install Android Studio: http://developer.android.com/sdk/index.html
* Basic computer, mobile device and internet skills: web browsing, typing, copying, pasting, saving files, downloading content, sharing content on social networks, emailing, messaging, watching youtube videos, communicating with social networks.

## COURSE OVERVIEW

Students will dive into Android software development skills and tools. Research, practice, testing and weekly projects to actually build solutions that will be added to each student's public portfolioon social networks. The focus will be on developing weekly android app projects that build on the previous weeks' projects while helping the student create their own online branded portfolio.

## WEEKLY ANDROID HOMEWORK / PROJECTS INCLUDE:

Basics:
* Week 1: Intros, Schedules & Success Plan
* Week 1: 1st App, Lifecycle, Dynamic UI
* Week 2: Save Data, Interact, Permissions
* Week 3: Content Sharing
* Week 4: Multimedia, Graphics, Animation
* Week 5: Connectivity, Cloud
* Week 6: Location & Maps
* Week 7: User Info & Sign-in
* Week 8: Wearables, TV, Auto
* Week 9: Google Services
* Week 10: Best Practices
* Week 11: Android Portfolio Polish

Topics will be demonstrated through live-code examples during scheduled video hangouts.

## HOMEWORK/PROJECTS

All your assignments are listed within the [Course Outline](#course-outline).

### WORKFLOW

If you're using GitHub Desktop, [these instructions](https://help.github.com/desktop/guides/contributing/) will help explain the Git/GitHub concepts. Here are the overall steps:

1. Fork the repository for the exercise/project (found under [github.com/monigarrteam](https://github.com/monigarrteam)).
1. Clone the repository to your computer.
1. Create a New Android Project or Open your Existing Android Project in the same directory that your repository is found on your own computer.
1. Work on your New or Existing Android Project in Android Studio and save your work in your local computer's repository. 
1. Commit all your code. 
1. Push/sync your code up to GitHub.
1. [Create a pull request](https://help.github.com/articles/creating-a-pull-request/) on the original repository. 
1. All work is due by Thursday midnight the latest, unless otherwise specified.
1. You can continue to push fixes and improvements until the close date (listed in Classes) – just add a comment in the pull request to let the instructor know your work has been updated.

When the pull request is created, you should see a message saying that "the Travis CI build is in progress" – this means your solution is being automatically checked for syntax errors.  If this "build" ends up failing (which will show a red "X"), click through the "details" link and scroll to the bottom to see what the errors were.  Per the [requirements](#requirements) below, please fix your issues and push up the changes.

Feedback will be given in the pull request, so please respond with your thoughts and questions!  You are welcome to open the pull request as the work is still in-progress if you are stuck and want to ask a question – just mention `@monigarr` with the question to make sure the instructor will know to look at it sooner.

Your solution will also be live at `http://USERNAME.github.io/YOURPROJECTNAME`.  For exercises with multiple levels/versions, leave a new comment in the pull request saying "Level X finished!" before pushing commits for the next level. "BONUS" levels are for extra credit.

### REQUIREMENTS

These apply to real life, as well.

* [Travis CI](https://docs.travis-ci.com/) build should pass and includes:
    * All HTML files should pass [W3C Markup Validation](http://validator.w3.org).
    * All written JS should pass [JSHint](http://jshint.com).
* Must apply "good programming style" learned in class
    * Functions should be "short" (see [Sandi Metz's rules for developers](https://robots.thoughtbot.com/sandi-metz-rules-for-developers)).
    * Optimize for readability.
        * ["Programs must be written for people to read, and only incidentally for machines to execute." -Harold Abelson](https://www.goodreads.com/quotes/9168-programs-must-be-written-for-people-to-read-and-only)
    * Avoid using anonymous callbacks within other functions, especially if the callback is more than one or two lines.
    * For projects, use Object-Oriented Programming.
* Any borrowed code must be properly [annotated](http://documentup.com/advanced-js/syllabus#statements-on-plagiarism/instructor).
* Bonus points for:
    * [Automated tests](#test-frameworks)
    * Creativity as long as requirements are fulfilled


## COURSE OUTLINE

### WEEK 1 CLASS

1. Intro
    * Introduce yourselves in private online class: your name, github link, facebook link, twitter link, linkedin link, youtube link and google+ link
    * Details about what the class is going to cover
1. Verify Students' Setups
    * Android Studio
    * Git/GitHub
    * Social Networks: github, fb, twitter, linkedin, youtube channel
1. GitHub workflow
    * Walk through [workflow](#workflow)
    * Create pull request on [students repository](https://github.com/monigarrteam/students)
1. Explain Weekly Project Expectations - how to be successful

#### WEEK 1 HOMEWORK

* Join [the class community](https://plus.google.com/u/2/communities/108491196328338711093).
* Access [MoniGarr.com Classes](https://www.monigarr.com) page, where grades will be posted.
    * [Documentation](https://www.monigarr.com/android2016course/Student+Quick-Start)
* Read [Android Studio Overview](http://developer.android.com/tools/studio/index.html).
* Finish up and submit [AndroidProjectOne](https://github.com/monigarrteam/androidprojectone)
* Add link with your statement (what went well, what needs improvement) about your Android Project One to your own social network profiles: facebook, twitter, linkedin, youtube and google+

### WEEK 2 CLASS

1. Look at various approaches for `countdown()`
    * Show recursive solution
1. Developer Tools walkthrough
    * Elements (HTML)
    * Console (JS)
    * Scripts (JS)
1. Pair program to build [Memory v1](https://github.com/advanced-js/memory) (see [pairing tips](#pairing-tips))
1. Cover OOP, though "oop_inheritance" slide
    * [Encapsulation example](http://jsbin.com/baqopu/1/edit?css,js,output)
    * Look at [Backbone.js Events](http://backbonejs.org/docs/backbone.html)

#### WEEK 2 HOMEWORK

* Read [Mozilla's Introduction to Object-Oriented Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript)
* [OOP exercise](https://github.com/advanced-js/oop), through V2
* [Memory v2](https://github.com/advanced-js/memory#v2) (individual)

### Class 3

1. Code review Memory
1. Get through [`oop_inheritance`](http://advanced-js.github.io/deck/examples/oop_inheritance/) slide
1. Cover automated testing
    * Build up a test framework from scratch
    * Examples in QUnit
        * [Simple](http://jsbin.com/woqusi/edit?html,js,output)
        * [Classes](http://jsbin.com/nukamun/edit?js,output)
        * [QUnit documentation](http://qunitjs.com/)
    * [Other frameworks](#test-frameworks)
1. Cover AJAX/CORS/JSONP ([files](https://github.com/advanced-js/deck/tree/gh-pages/demos/ajax))
    * Network tab in Developer Tools

#### Homework

* Read [Google JavaScript Style Guide](http://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml)
* Complete [OOP exercise](https://github.com/advanced-js/oop) through V4.
* [Memory V3](https://github.com/advanced-js/memory#v3)

### Class 4

1. Finish slides
1. Getting Serious example
    * Quick intro to Backbone.js
        * [Boilerplate](http://jsbin.com/IGivato/1/edit?html,js,output)
        * Click the Box [example app](http://jsbin.com/IGivato/5/edit?css,js,output)
        * TDD?
1. Multiple async
    * [Promises](https://github.com/advanced-js/deck/tree/gh-pages/demos/ajax/promises)/[jQuery.Deferred](http://api.jquery.com/jQuery.Deferred/)
    * Possibly show [async](https://github.com/caolan/async#control-flow-1) library?

#### Homework

* [Learn about AJAX](https://github.com/advanced-js/deck/tree/gh-pages/demos/ajax#readme)
* [Mashup](https://github.com/advanced-js/mashup)
* Improve your previous assignments

### Class 5

1. Present and code review Mashup projects
1. Possible topics (vote?):
    * Node.js
        * Server "Hello World" (from [Node.js homepage](http://nodejs.org/))
            * [HTTP module docs](http://nodejs.org/api/http.html)
        * HTTP requests
            * [Status codes](http://pretty-rfc.herokuapp.com/RFC2616#status.codes)
            * Headers
        * CommonJS?
    * [Regular Expressions](https://github.com/advanced-js/deck/tree/gh-pages/demos/regex.html)
        * Convert live input from a text area, e.g.
            * Link Twitter handles
            * Substitute select words for emoji, using [emoji-css](http://afeld.github.io/emoji-css/)
    * Object-Oriented design
    * [Code Retreat](http://coderetreat.org/facilitating/structure-of-a-coderetreat) – possible "problems":
        * [Game of Life](http://coderetreat.org/gol)
        * Tic Tac Toe

## Pairing Tips

* Three people is possible, but two works best
* Agree on an editor and environment that you're both comfortable with
* The person who's less experienced/comfortable should have more keyboard time
* Switch who's "driving" regularly
* Make sure to save the code and send it to both people

## Resources

### Required Reading

* [Android Studio Install](http://google-styl)
* [Android Developer](http://bonsaiden.github.com/JavaScript-Garden/)
* [Git](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript)
* [Github](http://blog.parse.com/learn/engineering/whats-so-great-about-javascript-promises/)
* h

### BEGINNER MATERIALS

This class assumes you are confident with the following, but in case you need a brush-up...

* Codecademy – [JavaScript](https://www.codecademy.com/learn/javascript) and [jQuery](https://www.codecademy.com/learn/jquery)
* [Eloquent JavaScript](http://eloquentjavascript.net/index.html) by Marijn Haverbeke, Chapters 1-5
* [Want to learn JavaScript in 2015?](https://medium.com/@_cmdv_/i-want-to-learn-javascript-in-2015-e96cd85ad225)
* see also – [Other Lists](#other-lists)

### RECOMMENDED READING

* [Functional JavaScript](http://shop.oreilly.com/product/0636920028857.do) by Michael Fogus
* [Front-end Job Interview Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions) by @darcyclarke (for testing yourself)
* [JavaScript Best Practices](http://www.thinkful.com/learn/javascript-best-practices-1/)
* [JavaScript Patterns](http://shichuan.github.io/javascript-patterns/) by @shichuan (thanks @iandrewfuchs)
* [JavaScript Patterns](http://www.amazon.com/JavaScript-Patterns-Stoyan-Stefanov/dp/0596806752) by Stoyan Stephanov
* [JavaScript Web Applications](http://www.amazon.com/JavaScript-Web-Applications-Alex-MacCaw/dp/144930351X/) by Alex MacCaw

#### SPECIFIC TOPICS

* [Classical Inheritance in JavaScript](http://www.crockford.com/javascript/inheritance.html) by Douglas Crockford
* [Partial Application in JavaScript](http://benalman.com/news/2012/09/partial-application-in-javascript/) by Ben Alman (thanks @michaelBenin)
* [HTML5 Rocks slides](http://slides.html5rocks.com/)
* [Learning JavaScript Design Patterns](http://addyosmani.com/resources/essentialjsdesignpatterns/book/) by Addy Osmani

#### OTHER LISTS

* [JS: The Right Way](http://www.jstherightway.org/) (an overview of the JS landscape)
* [Code School](https://www.codeschool.com/paths/javascript)
* Thoughtbot's [Javascript Trail Map](https://upcase.com/javascript)
* [How To Learn JavaScript Properly](http://javascriptissexy.com/how-to-learn-javascript-properly/)
* [Superhero.js](http://superherojs.com)
* [Teach Yourself to Code](http://teachyourselftocode.com/javascript)

### TOOLS

* Code Validation: [JSLint](http://jslint.com) / [JSHint](http://jshint.com)
* Debugging:
    * [Chrome Developer Tools](https://developer.chrome.com/devtools/index)
        * [Official debugging tutorial](https://developer.chrome.com/extensions/tut_debugging)
        * Tutorial: [JavaScript Diagnosis](http://www.macwright.org/2015/03/10/javascript-diagnosis.html)
    * [Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/)
* Sharing Code: [gist.github.com](https://gist.github.com/)
* Asking Questions: [Stack Overflow](http://stackoverflow.com/)

#### GITHUB

* Git and GitHub
    * [Official GitHub Help](https://help.github.com/)
    * [Recommended resources](http://hackerhours.org/resources.html#github)
* GitHub Pages
    * [Official site](https://pages.github.com/)
    * [Thinkful guide](http://www.thinkful.com/learn/a-guide-to-using-github-pages/)

#### SANDBOXES

* [Browxy](http://www.browxy.com/) (recommended)
* [rawgithub.com](http://rawgit.com/)

#### BEST PRACTICES

* [Interaction & Engagement](http://developer.android.com/training/best-ux.html)
* [Testing](https://coderwall.com/p/ntbixw)
* [User Interface](http://developer.android.com/training/best-ui.html)
* [Background Jobs](http://developer.android.com/training/best-background.html)
* [Performanc](http://developer.android.com/training/best-performance.html)
* [Security & Privacy](http://developer.android.com/training/best-security.html)


### REFERENCE

* [Pure Android](http://developer.android.com/design/patterns/pure-android.html)
* [Android Studio](http://developer.android.com/sdk/index.html)
* [Android Activity Lifecycle](http://developer.android.com/training/basics/activity-lifecycle/index.html)
* [API Guides](http://developer.android.com/guide/index.html)


### MORE EXAMPLES

* [Android App Patterns](http://www.android-app-patterns.com/)
* [Android Material Design](http://developer.android.com/design/index.html)
* [Android Training](http://developer.android.com/training/index.html)

## GRADING

* Class Participation – 30%
* Homework – 70%

## STATEMENTS ON PLAGIARISM

Plagiarism is a form of fraud.  The definition of plagiarism is as follows: "Plagiarism is presenting someone else's work as though it were one's own.  More specifically, plagiarism is to present as one's own words quoted without quotation marks from another writer; a paraphrased passage from another writer’s work; or facts or ideas gathered, organized, and reported by someone else, orally and/or in writing.  Since plagiarism is a matter of fact, not of the student's intention, it is crucial that acknowledgement of the sources be accurate and complete.  Even where there is not a conscious intention to deceive, the failure to make appropriate acknowledgement constitutes plagiarism.  Penalties for plagiarism range from failure for an assignment or course to dismissal from the course.

### INSTRUCTOR

Reuse and building on other ideas and code are major parts of modern software development. Each new generation of software engineers do build on the shoulders of current and past giants. As a professional you rarely write anything from scratch.  This class is structured so that all solutions are public.  You are encouraged to learn from the work of your peers. People who are copying-and-pasting solutions without challenging themselves & understanding the course materials are wasting their own time and money taking this course.

Please respect the terms of use and/or license of any code you find. If you reimplement or duplicate an algorithm or code from elsewhere, credit the original source with an inline comment.

## LICENSE

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This <span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" rel="dct:type">work</span> and all other materials under https://github.com/monigarrteam are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.


