# android-syllabus
Syllabus for the Android development training with MoniGarr.com 


* **Course:** [AndroidDevMoniGarrFebruary2016, MoniGarr.com](http://www.MoniGarr.com)
* **Instructor:** Monica Peters, [monigarr@yahoo.com](mailto:monigarr@yahoo.com)
* **Need help?**
    * Look through and create [issues](https://github.com/monigarrteam/android-syllabus/issues)
   * [Email](mailto:monigarr@yahoo.com) for 1-on-1 help, or to set up a time to meet

## COURSE DESCRIPTION

Learn how to develop an Android app with java and android studio in this intensive, 12 week course. Topics include software installation, best practices, android ui, material design, java programming language, debugging and . Discover some of the lesser-known useful features of android software development, such as how to improve your android app performance, security and stability provides the best end user experience available. Create Android apps for mobile phones, wearables and more using industry standard Android Studio.

## PREREQUISITES
All of the following is required from you, BEFORE your first class.

* Your Own Laptop & Android Device with Internet Service.
* Your Own Social Network Profiles Setup for Class work & to share with entire class.
	* Your profile avatar and details must be complete before your first class.
	* Facebook profile: http://www.FaceBook.com
	* Twitter profile: http://www.Twitter.com
	* LinkedIn Profile: http://www.linkedin.com
	* Google+ profile: http://plus.google.com
	* YouTube Channel: https://www.google.com/search?q=how+to+create+a+youtube+channel&ie=utf-8&oe=utf-8
* Install Github Desktop: https://desktop.github.com/ 
* Install Android Studio: http://developer.android.com/sdk/index.html
* Read Android Studio Overview http://developer.android.com/tools/studio/index.html
* Read [Android 1st App](http://developer.android.com/training/basics/firstapp/index.html)
* Read [Android Different Devices](http://developer.android.com/training/basics/supporting-devices/index.html)
* Basic computer, mobile device and internet skills: web browsing, typing, copying, pasting, saving files, downloading content, sharing content on social networks, emailing, messaging, watching youtube videos, communicating with social networks.

## COURSE OVERVIEW

Dive into Android software development. Research, practice, testing and weekly projects will create student's public online portfolios with social networks. The focus will be on developing weekly android app projects that build on the previous weeks' work while helping the student create their own online branded portfolio to help gain future work as an android developer.

## WEEKLY ANDROID HOMEWORK / PROJECTS INCLUDE:

* Week 1: Intros, Schedules, Success Plan
* Week 1: 1st App, Lifecycle, Dynamic UI, Project 1
* Week 2: Save Data, Interact, Permissions, Project 2
* Week 3: Content Sharing, Project 3
* Week 4: Multimedia, Graphics, Animation, Project 4
* Week 5: Connectivity, Cloud, Project 5
* Week 6: Location & Maps, Project 6
* Week 7: User Info & Sign-in, Project 7
* Week 8: Wearables, TV, Auto, Project 8
* Week 9: Google Services, Project 9
* Week 10: Best Practices, Project 10
* Week 11: Android Portfolio Polish, Project 11
* Week 12: Android Portfolio Publish & Promote
Final Grades & Celebration

Topics will be demonstrated through weekly live-code examples during scheduled video hangouts.

## HOMEWORK/PROJECTS

All your assignments are listed within the [Course Outline](#course-outline).

### WORKFLOW

If you're using GitHub Desktop, [these instructions](https://help.github.com/desktop/guides/contributing/) will help explain the Git/GitHub concepts. Here are the overall steps:

1. Fork the repository for the exercise/project (found under [github.com/monigarrteam](https://github.com/monigarrteam/projectname)).
1. Clone the repository to your computer.  $git clone http://www.urltoyourownrepository.com
1. Create a New Android Project in the above repository folder that is found on your own computer.
1. Work on your Android Project in Android Studio and save your work in your local computer's repository. 
1. Commit all your code. $git add -A   $git commit -m "description of your work"
1. Push/sync your code up to GitHub.   $git push origin master
1. [Create a pull request](https://help.github.com/articles/creating-a-pull-request/) on the original repository before the due date of thursday midnight. 
1. All your work is due before Thursday midnight the latest, unless otherwise specified.

When your pull request is created, you should see a message saying "the Travis CI build is in progress" – this means your solution is being automatically checked for syntax errors.  If this "build" ends up failing (which will show a red "X"), click through the "details" link and scroll to the bottom to see what the errors were.  Per the [requirements](#requirements) below, please fix your issues and push up the changes.

Feedback will be given in your pull request, so please respond with your thoughts and questions!  You are welcome to open the pull request as the work is still in-progress if you are stuck and want to ask a question – just mention `@monigarr` with the question to make sure the instructor will know to look at it sooner.

Your solution will also be live at `http://YOURUSERNAME.github.io/YOURPROJECTNAME`.  For exercises with multiple levels/versions, leave a new comment in the pull request saying "Level X finished!" before pushing commits for the next level. "BONUS" levels are for extra credit.

### REQUIREMENTS

* [Travis CI](https://docs.travis-ci.com/) build should pass.
* Must apply "good programming style" learned in class
    * Functions should be "short" (see [Sandi Metz's rules for developers](https://robots.thoughtbot.com/sandi-metz-rules-for-developers)).
    * Optimize for Readability.
        * ["Programs must be written for people to read, and only incidentally for machines to execute." -Harold Abelson](https://www.goodreads.com/quotes/9168-programs-must-be-written-for-people-to-read-and-only)
    * Avoid using anonymous callbacks within other functions, especially if the callback is more than one or two lines.
    * For projects, use Object-Oriented Programming.
* Any borrowed code must be properly [annotated](http://documentup.com/advanced-js/syllabus#statements-on-plagiarism/instructor).
* Bonus Points for:
    * [Unit Testing with 50% or more code coverage]
    * [Optimization Techniques]
    * [Creativity] as long as requirements are fulfilled

## COURSE OUTLINE

### WEEK 1 CLASS

1. Intro
    * Introduce yourselves in private online class: your name, link to your social profiles: github, facebook, twitter, linkedin, youtube and google+
    * Details about what the class is going to cover
1. Verify Students' Setups
    * Android Studio
    * Git/GitHub
    * Social Networks: github, fb, twitter, linkedin, youtube channel
1. GitHub workflow
    * Walk through [workflow](#workflow)
    * Create pull request on [students repository](https://github.com/monigarrteam/students)
1. Explain Weekly Project Expectations - how to be successful
1. Code review project 1

#### PROJECT 1 HOMEWORK

* Join [class community](https://plus.google.com/u/2/communities/108491196328338711093).
* Login [MoniGarr.com Classes](https://www.monigarr.com) page, where grades will be posted.
    * [Documentation](https://www.monigarr.com/android2016course/Student+Quick-Start)
* Android Studio Walkthrough
* Read [Android Lifecycle](http://developer.android.com/training/basics/activity-lifecycle/index.html)
* Read [Android Dynamic UI](http://developer.android.com/training/basics/fragments/index.html)
* Read [Android Design](http://developer.android.com/design/index.html)
* Finish up and submit [FirstNameLastName_AndroidProject1](https://github.com/monigarrteam/androidproject1)
* Add link, description & screenshot of your project on your:
	* facebook profile.
	* twitter profile
	* linkedin profile
	* youtube profile
	* google profile

### PROJECT 2 CLASS

1. Code review project 2
1. Look at options for saving data, interacticing with other apps and setting up app permissions
    * Show solutions for each
1. Android Studio Project Walkthrough
    * app permissions
    * interacting with other apps
    * saving data with your app

#### PROJECT 2 HOMEWORK

1. * Read [Android Saving Data](http://developer.android.com/training/basics/data-storage/index.html)
1. * Read [Android Interacting with Other Apps](http://developer.android.com/training/basics/intents/index.html)
1. * Read [Android Setting Permissions](http://developer.android.com/training/permissions/index.html)
* Finish up and submit [FirstNameLastName_AndroidProject2](https://github.com/monigarrteam/androidproject2)
* Add link, description & screenshot of your project on your:
	* facebook profile.
	* twitter profile
	* linkedin profile
	* youtube profile
	* google profile

### PROJECT 3 CLASS

1. Code review project 3
1. Look at options for android app content sharing
    * Show solutions for each
1. Android Studio Project Walkthrough
    * content sharing

#### PROJECT 3 HOMEWORK

* Read [Android Content Sharing](http://developer.android.com/training/building-content-sharing.html)
* Finish and submit [FirstNameLastName_AndroidProject3](https://github.com/monigarrteam/androidproject3)
* Add link, description & screenshot of your project on your:
	* facebook profile.
	* twitter profile
	* linkedin profile
	* youtube profile
	* google profile

### PROJECT 4 CLASS

1. Code review project 4
1. Look at options for multimedia, graphics and animation
    * Show solutions for each
1. Android Studio Project Walkthrough

#### PROJECT 4 HOMEWORK

* Read[Android Multimedia](http://developer.android.com/training/building-multimedia.html)
* Read [Android Graphics & Animation](http://developer.android.com/training/building-graphics.html)
* Improve your previous assignments
* Finish up and submit [FirstNameLastName_AndroidProject4](https://github.com/monigarrteam/androidproject4)
* Add link, description & screenshot of your project on your:
	* facebook profile.
	* twitter profile
	* linkedin profile
	* youtube profile
	* google profile

### PROJECT 5 CLASS

1. Code review project 5
1. Look at options for connectivity and cloud
    * Show solutions for each
1. Android Studio Project Walkthrough

#### PROJECT 5 HOMEWORK

* Read[Android Connectivity & Cloud](http://developer.android.com/training/building-connectivity.html)
* Improve your previous assignments
* Finish up and submit [FirstNameLastName_AndroidProject5](https://github.com/monigarrteam/androidproject5)
* Add link, description & screenshot of your project on your:
	* facebook profile.
	* twitter profile
	* linkedin profile
	* youtube profile
	* google profile

### PROJECT 6 CLASS

1. Code review project 6
1. Look at options for location and maps
    * Show solutions for each
1. Android Studio Project Walkthrough

#### PROJECT 6 HOMEWORK

* Read[Android Location & Maps](http://developer.android.com/training/building-location.html)
* Improve your previous assignments
* Finish up and submit [FirstNameLastName_AndroidProject6](https://github.com/monigarrteam/androidproject6)
* Add link, description & screenshot of your project on your:
	* facebook profile.
	* twitter profile
	* linkedin profile
	* youtube profile
	* google profile

### PROJECT 7 CLASS

1. Code review project 7
1. Look at options for user info & sign-in
    * Show solutions for each
1. Android Studio Project Walkthrough

#### PROJECT 7 HOMEWORK

* Read[Android user info & sign in](http://developer.android.com/training/building-userinfo.html)
* Improve your previous assignments
* Finish up and submit [FirstNameLastName_AndroidProject7](https://github.com/monigarrteam/androidproject7)
* Add link, description & screenshot of your project on your:
	* facebook profile.
	* twitter profile
	* linkedin profile
	* youtube profile
	* google profile

### PROJECT 8 CLASS

1. Code review project 8
1. Look at options for wearables, tv and auto
    * Show solutions for each
1. Android Studio Project Walkthrough

#### PROJECT 8 HOMEWORK

* Read[something](https://github.com/)
* Improve your previous assignments
* Finish up and submit [FirstNameLastName_AndroidProject8](https://github.com/monigarrteam/androidproject8)
* Add link, description & screenshot of your project on your:
	* facebook profile.
	* twitter profile
	* linkedin profile
	* youtube profile
	* google profile

### PROJECT 9 CLASS

1. Code review project 9
1. Look at options for google services
    * Show solutions for each
1. Android Studio Project Walkthrough

#### PROJECT 9 HOMEWORK

* Read[Android Wearables](http://developer.android.com/training/building-wearables.html)
* Read [Android TV](http://developer.android.com/training/tv/index.html)
* Read [Android Auto](http://developer.android.com/training/auto/index.html)
* Improve your previous assignments
* Finish up and submit [FirstNameLastName_AndroidProject9](https://github.com/monigarrteam/androidproject9)
* Add link, description & screenshot of your project on your:
	* facebook profile.
	* twitter profile
	* linkedin profile
	* youtube profile
	* google profile

### PROJECT 10 CLASS

1. Code review project 10
1. Look at options for Best Practices Interaction & Engagement
    * Show solutions for each
1. Android Studio Project Walkthrough

#### PROJECT 10 HOMEWORK

* Read[Interaction & Engagement](http://developer.android.com/training/best-ux.html)
* Improve your previous assignments
* Finish up and submit [FirstNameLastName_AndroidProject10](https://github.com/monigarrteam/androidprojectt10)
* Add link, description & screenshot of your project on your:
	* facebook profile.
	* twitter profile
	* linkedin profile
	* youtube profile
	* google profile

### PROJECT 11 CLASS

1. Code review project 11
1. Look at options for Best Practices User Interfaces
    * Show solutions for each
1. Android Studio Project Walkthrough

#### PROJECT 11 HOMEWORK

* Read [UI](http://developer.android.com/training/best-ui.html)
* Improve your previous assignments
* Finish up and submit [FirstNameLastName_AndroidProject11](https://github.com/monigarrteam/androidproject11)
* Add link, description & screenshot of your project on your:
	* facebook profile.
	* twitter profile
	* linkedin profile
	* youtube profile
	* google profile

### PROJECT 12 CLASS

1. Code review project 12
1. Look at options for Best Practices Background Jobs
    * Show solutions for each
1. Android Studio Project Walkthrough

#### WEEK 12 HOMEWORK

* Read [Background Jobs](http://developer.android.com/training/best-background.html)
* Finish up and submit [FirstNameLastName_AndroidProject12](https://github.com/monigarrteam/androidproject12)
* Add link, description & screenshot of your project on your:
	* facebook profile
	* twitter profile
	* linkedin profile
	* youtube profile
	* google profile

### PROJECT 13 CLASS

1. Code review project 13
1. Look at options for Best Practices Performance
    * Show solutions for each
1. Android Studio Project Walkthrough

#### PROJECT 13 HOMEWORK

* Read [Performance](http://developer.android.com/training/best-performance.html)
* Finish up and submit [FirstNameLastName_AndroidProject13](https://github.com/monigarrteam/androidproject13)
* Add link, description & screenshot of your project on your:
	* facebook profile
	* twitter profile
	* linkedin profile
	* youtube profile
	* google profile

### PROJECT 14 CLASS

1. Code review project 14
1. Look at options for Best Practices Security & Privacy
    * Show solutions for each
1. Android Studio Project Walkthrough

#### WEEK 14 HOMEWORK

* Read [Security & Privacy](http://developer.android.com/training/best-performance.html)
* Finish up and submit [FirstNameLastName_AndroidProject14](https://github.com/monigarrteam/androidproject14)
* Add link, description & screenshot of your project on your:
	* facebook profile
	* twitter profile
	* linkedin profile
	* youtube profile
	* google profile

### PROJECT 12 CLASS

1. Code review project 15
1. Look at options for Best Practices Testing
    * Show solutions for each
1. Android Studio Project Walkthrough

#### WEEK 15 HOMEWORK

* Read [Testing](http://developer.android.com/training/testing.html)* Improve your previous assignments
* Finish up and submit [FirstNameLastName_AndroidProject15](https://github.com/monigarrteam/androidproject15)
* Add link, description & screenshot of your project on your:
	* facebook profile
	* twitter profile
	* linkedin profile
	* youtube profile
	* google profile


## Resources

### Required Reading

* [Android Studio Install](http://google-styl)
* [Android Developer](http://bonsaiden.github.com/JavaScript-Garden/)
* [Git](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript)
* [Github](http://blog.parse.com/learn/engineering/whats-so-great-about-javascript-promises/)

### BEGINNER MATERIALS

This class assumes you are confident with the following, but in case you need a brush-up...

* Codecademy – [JavaScript](https://www.codecademy.com/learn/javascript) and [jQuery](https://www.codecademy.com/learn/jquery)
* [Eloquent JavaScript](http://eloquentjavascript.net/index.html) by Marijn Haverbeke, Chapters 1-5
* [Want to learn JavaScript in 2015?](https://medium.com/@_cmdv_/i-want-to-learn-javascript-in-2015-e96cd85ad225)
* see also – [Other Lists](#other-lists)

### RECOMMENDED READING

* [Functional JavaScript](http://shop.oreilly.com/product/0636920028857.do)
* [Front-end Job Interview Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions)

#### SPECIFIC TOPICS

* [Developer.Android.com](http://developer.android.com)

#### MORE ONLINE TRAINING

* [YouTube Android Training](https://www.youtube.com/user/androiddevelopers)
* [TreeHouse](http://referrals.trhou.se/monicapeters)

### TOOLS

* Debugging:
    * [Testing Tools](http://developer.android.com/tools/testing/testing-tools.html)
    * [Testing Best Practices](http://developer.android.com/training/testing.html)
* Share Code: [gist.github.com](https://gist.github.com/)
* Ask Questions: [Stack Overflow](http://stackoverflow.com/)

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
* [Performance](http://developer.android.com/training/best-performance.html)
* [Security & Privacy](http://developer.android.com/training/best-security.html)
* [Git Basics](http://git-scm.com/book/en/v2/Getting-Started-Git-Basics)

### REFERENCE

* [Pure Android](http://developer.android.com/design/patterns/pure-android.html)
* [Android Studio](http://developer.android.com/sdk/index.html)
* [Android Activity Lifecycle](http://developer.android.com/training/basics/activity-lifecycle/index.html)
* [API Guides](http://developer.android.com/guide/index.html)

### MORE EXAMPLES

* [Android App Patterns](http://www.android-app-patterns.com/)
* [Android Material Design](http://developer.android.com/design/index.html)
* [Android Training](http://developer.android.com/training/index.html)
* [Android Samples](http://developer.android.com/samples/index.html)

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


