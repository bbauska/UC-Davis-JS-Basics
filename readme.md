---
title: |
  University of California @Davis JavaScript Basics
  by William Mead, Lecturer - UC-Davis
author: "bbauska"
date last editted: "1/30/2024 6+pm"
output: 
  markdown:
    with some style
---

<h1 align="center">JavaScript Basics</h1>

<h6 align="center">(by William Mead, Lecturer - University of California @Davis)</h6>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~ readme.md of UC-Davis-JS-Basics in bbauska.github.io ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~ 01/02. javascript (coffee cup) logo / UC Davis log (01) ~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image001.jpeg?raw=true"
  width="20%"
  alt="JavaScript coffee cup logo version." />
<img src="./images/image002.png?raw=true"
  width="20%"
  alt="UC Davis logo." />
</p>
<!-- {width="2.0in" height="1.773685476815398in"}![](./images/image002.png){width="2.0995866141732282in" height="1.77in"} -->

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ about javascript basics ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="#about">About this Course</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>This course introduces the programming language JavaScript and shows the
websites that include the type of interactions students will eventually
be able to develop. Learners will understand the importance of how
JavaScript was developed and why such history impacts the way JavaScript
is currently written and in future releases. Learners will write their
first scripts, have their HTML and CSS skills assessed, create variables
and arrays and assign values to them. If student's skills are lacking,
resources and recommendations are provided to improve these skills.
There is ample opportunity for students to practice these first, core
skills.</p>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ table of contents ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2><a href="#table-of-contents">Table of Contents</a></h2>

### [**Week 1: Getting Started; Intro to JavaScript Variables and Arrays**](#ch1)
>	- #### [**1.00 A Note from UC Davis**](#ch1-00-note)
>	- #### [**1.00 Learning Objectives**](#ch1-00-obj)
>	- #### [**1.00 Welcome to JavaScript Basics**](#ch1-00-welcome)
>	- #### [**1.00 Module 1 Introduction; JavaScript Variables &amp; Arrays**](#ch1-00-intro)
>#### [**1.01 Intro to JavaScript - Part 1**](#ch1-01)
>#### [**1.02 Intro to JavaScript - Part 2**](#ch1-02)
>#### [**1.03 Intro to JavaScript - Part 3**](#ch1-03)
>#### [**1.04 Tools Needed for Success**](#ch1-04)
>#### [**1.05 Skills Needed for Success**](#ch1-05)
>	- #### [**1.05.Assessing Your Skills in HTML &amp; CSS**](#ch1-05-assess)
>	- #### [**1.05.Additional Resources (awwwards.com &amp; software)**](#ch1-05-add)
>#### [**1.06 JavaScript Variables**](#ch1-06)
>#### [**1.07 JavaScript Variables Practice - Part 1**](#ch1-07)
>#### [**1.08 JavaScript Variables Practice - Part 2**](#ch1-08)
>#### [**1.09 JavaScript Variables Practice - Part 3**](#ch1-09)
>#### [**1.10 JavaScript Arrays - Part 1**](#ch1-10)
>#### [**1.11 JavaScript Arrays - Part 2**](#ch1-11)
>#### [**1.12 JavaScript Arrays Practice**](#ch1-12)
>	- #### [**1.12.Reserved Words**](#ch1-12-res)
>	- #### [**1.12.Array Methods**](#ch1-12-array)

### [**Week 2: Controlling Logical Flow in JavaScript**](#ch2)
>	- #### [**2.00 Learning Objectives**](#ch2-00-obj)
>	- #### [**2.00 Module 2 Introduction; Controlling Logical Flow in JavaScript**](#ch2-00-intro)
>#### [**2.01 Visual Studio - Part 1**](#ch2-01)
>#### [**2.02 Visual Studio - Part 2**](#ch2-02)
>#### [**2.03 Visual Studio - Part 3**](#ch2-03)
>#### [**2.04 Operators, Boolean &amp; Selection in JavaScript**](#ch2-04)
>#### [**2.05 Try This!**](#ch2-05)
>#### [**2.06 Comparing Values**](#ch2-06)
>#### [**2.07 Else If**](#ch2-07)
>#### [**2.08 Switch Statements**](#ch2-08)
>#### [**2.09 Using &amp;&amp;**](#ch2-09)
>	- #### [**2.09.JavaScript Operators**](#ch2-09-oper)
>	- #### [**2.09.JavaScript Booleans**](#ch2-09-bool)
>#### [**2.10 Loops in JavaScript**](#ch2-10)
>#### [**2.11 Working With Arrays**](#ch2-11)
>#### [**2.12 The For...Of Loop**](#ch2-12)
>#### [**2.13 While Loops**](#ch2-13)
>	- #### [**2.13.JavaScript Loops**](#ch2-13-loop)
>#### [**2.14 Structured Programming, Sequence - Part 1**](#ch2-14)
>#### [**2.15 Sequence - Part 2**](#ch2-15)
>#### [**2.16 Sequence - Part 3, Loop**](#ch2-16)
>#### [**2.17 Loop + Selection**](#ch2-17)
>	- #### [**2.17.JavaScript Basic Challenges Introduction 1-9**](#ch2-17-1thru9)
>#### [**2.18 JavaScript Basic Challenges**](#ch2-18)
>#### [**2.19 JavaScript Basic Challenges**](#ch2-19)
>#### [**2.20 JavaScript Basic Challenges**](#ch2-20)
>#### [**2.21 Useful Example - Step 1**](#ch2-21)
>#### [**2.22 Useful Example - Steps 2-4**](#ch2-22)
>#### [**2.23 Useful Example - Step 5**](#ch2-23)
>#### [**2.24 More on Functions**](#ch2-24)
>	- #### [**2.24.JavaScript Functions**](#ch2-24-func)
>	- #### [**2.24.JavaScript Function Challenges 10-16**](#ch2-24-10thru16)

### [**Week 3: Using JavaScript in the Web Browser**](#ch3)
>	- #### [**3.00 Learning Objectives**](#ch3-00-obj)
>	- #### [**3.00 Module 3 Introduction; Using JavaScript in the Web Browser**](#ch3-00-intro)
>#### [**3.01 JavaScript and the DOM**](#ch3-01)
>#### [**3.02 Dot Syntax and Methods**](#ch3-02)
>#### [**3.03 DOM; getElementsByTagName();**](#ch3-03)
>#### [**3.04 DOM; getElementsByClassName();**](#ch3-04)
>#### [**3.05 DOM; querySelector()**](#ch3-05)
>#### [**3.06 DOM; querySelectorAll();**](#ch3-06)
>#### [**3.07 innerHTML**](#ch3-07)
>#### [**3.08 className**](#ch3-08)
>#### [**3.09 Creating Elements and Text Nodes**](#ch3-09)
>#### [**3.10 Removing Elements**](#ch3-10)
>	- #### [**3.10.JavaScript and the DOM**](#ch3-10-dom)
>	- #### [**3.10.JavaScript DOM Challenges 17-21**](#ch3-10-17thru21)
>#### [**3.12 Event Listeners**](#ch3-12)
>#### [**3.13 The Event Object**](#ch3-13)
>#### [**3.14 More On Events**](#ch3-14)
>#### [**3.15 Mouseover, Mouseover Events: HTML**](#ch3-15)
>#### [**3.16 Scroll Events: HTML**](#ch3-10)
>#### [**3.17 deo: Window Resizing**](#ch3-17)
>#### [**3.18 Key Down Event**](#ch3-18)
>	- #### [**3.18.Intro to Events in JS**](#ch3-18-ev1)
>	- #### [**3.18.Event Reference**](#ch3-18-ev2)
>	- #### [**3.18.JavaScript Event Challenges 22-30**](#ch3-18-22thru30)
>#### [**3.19 Scope in JavaScript**](#ch3-19)
>#### [**3.20 Strategy 1: Never Use Global Scope**](#ch3-20)
>#### [**3.21 Strategy 2: 'use strict;'**](#ch3-21)
>#### [**3.22 Strategy 3: const and let**](#ch3-22)
>#### [**3.23 Scope in JavaScript Summary**](#ch3-23)
>	- #### [**3.23.Additional Resources**](ch#3-23-add)
>	- #### [**3.23.Simple Slide Show START Files**](#ch3-23-start)
>#### [**3.24 Simple JS Slideshow - Part 1**](#ch3-24)
>#### [**3.25 Simple JS Slideshow - Part 2**](#ch3-25)
>#### [**3.26 Simple JS Slideshow - Part 3**](#ch3-26)
>#### [**3.27 Simple JS Slideshow - Part 4**](#ch3-27)
>#### [**3.28 Simple JS Slideshow - Part 5**](#ch3-28)
>	- #### [**3.28.Advanced Slide Show START Files**](#ch3-28-start)
>#### [**3.29 Slideshow with Cross Fade Effect - Part 1**](#ch3-29)
>#### [**3.30 Slideshow with Cross Fade Effect - Part 2**](#ch3-30)
>#### [**3.31 Slideshow with Cross Fade Effect - Part 3**](#ch3-31)
>#### [**3.32 Slideshow with Cross Fade Effect - Part 4**](#ch3-32)
>#### [**3.33 Slideshow with Cross Fade Effect - Part 5**](#ch3-33)
>#### [**3.34 Slideshow with Cross Fade Effect - Part 6**](#ch3-34)
>#### [**3.35 Slideshow with Cross Fade Effect - Part 7**](#ch3-35)

### [**Week 4: Basic JavaScript Application Projects**](#ch4)
>	- #### [**4.00 Learning Objectives**](#ch4-00-obj)
>	- #### [**4.00 Module 4 Introduction; Basic JavaScript Application Projects**](#ch4-00-intro)
>	- #### [**4.00 Basic Distance Converter START Files**](#ch4-00-start)
>#### [**4.01 Basic Distance Converter Project - Part 1**](#ch4-01)
>#### [**4.02 Basic Distance Converter Project - Part 2**](#ch4-02)
>#### [**4.03 Basic Distance Converter Project - Part 3**](#ch4-03)
>#### [**4.04 Basic Distance Converter Project - Part 4**](#ch4-04)
>#### [**4.05 Basic Distance Converter Project - Part 5**](#ch4-05)
>	- #### [**4.05 Advanced Distance Converter START Files**](#ch4-05-start)
>#### [**4.06 Advanced Distance Converter Project - Part 1**](#ch4-06)
>#### [**4.07 Advanced Distance Converter Project - Part 2**](#ch4-07)
>#### [**4.08 Advanced Distance Converter Project - Part 3**](#ch4-08)
>#### [**4.09 Advanced Distance Converter Project - Part 4**](#ch4-09)
>#### [**4.10 Advanced Distance Converter Project - Part 5**](#ch4-10)
>	- #### [**4.10 Vacation Destination Project - Part 1 START Files**](#ch4-10-start)
>#### [**4.11 Vacation Destination Project: HTML & CSS - Part 1**](#ch4-11)
>#### [**4.12 Vacation Destination Project: HTML & CSS - Part 2**](#ch4-12)
>#### [**4.13 Vacation Destination Project: HTML & CSS - Part 3**](#ch4-13)
>#### [**4.14 Vacation Destination Project: HTML & CSS - Part 4**](#ch4-14)
>#### [**4.15 Vacation Destination Project: HTML & CSS - Part 5**](#ch4-15)
>#### [**4.16 Vacation Destination Project: HTML & CSS - Part 6**](#ch4-16)
>	- #### [**4.16 Vacation Destination Project - Part 2 START Files**](#ch4-16-start)
>#### [**4.17 Vacation Destination Project: JavaScript - Part 1**](#ch4-17)
>#### [**4.18 Vacation Destination Project: JavaScript - Part 2**](#ch4-18)
>#### [**4.19 Vacation Destination Project: JavaScript - Part 3**](#ch4-19)
>#### [**4.20 Vacation Destination Project: JavaScript - Part 4**](#ch4-20)
>#### [**4.21 Vacation Destination Project: JavaScript - Part 5**](#ch4-21)
>#### [**4.22 Vacation Destination Project: JavaScript - Part 6**](#ch4-22)
>#### [**4.23 Vacation Destination Project: JavaScript - Part 7**](#ch4-23)
>#### [**4.24 Vacation Destination Project: JavaScript - Part 8**](#ch4-24)
>#### [**4.25 Course Summary - JavaScript Basics**](#ch4-25)
>	- #### [**4.25 Self-Reflection - What Next?**](#ch4-25-refl)

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ syllabus for javascript basics ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2><a href="#syllabus">Syllabus - what's in store?</a></h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Week 1</h3>
<h3>Getting Started, Introduction to JavaScript, Variables, and Arrays</h3>

<p>In this module, you will be introduced to JavaScript and what it can do. You will be 
able to identify websites that include the types of interactions you will be able to 
produce at the end of the entire Specialization. You will also be able to discuss the 
history of JavaScript and explore why this history impacts how we write JavaScript.</p>

<p>On the web, JavaScript is used to manipulate the HTML and CSS of a webpage, after it 
has loaded from the server. You will be able to assess your understanding of HTML and 
CSS and have the opportunity through resources and recommendations for improving your 
skills in this area, if necessary. You will write simple JavaScript statements in the 
web browser console and be able to create variables and arrays. You will be able to assign 
values to these variables and arrays and be able to read values from them.</p>

<h4>12 videos, 5 readings</h4>

<ul>
  <li>1.00.A Note From UC Davis</li>
  <li>1.00.Learning Objectives</li>
  <li><a href="https://www.coursera.org/lecture/javascript-basics/welcome-to-this-course-EGMim">1.00.Welcome/Intro to this Course!</a></li>
</ul>

<ol type="1">
  <li>Introduction to JavaScript - Part 1</li>
  <li>Introduction to JavaScript - Part 2</li>
  <li>Introduction to JavaScript - Part 3</li>
  <li>Tools Needed for Success</li>
  <li>Skills Needed for Success</li>
</ol>

<ul>
  <li>1.05.Assessing Your Skills</li>
  <li>1.05.Additional Resources (awwwards.com &amp; software)</li>
</ul>

<ol type="1" start="6">
  <li>JavaScript Variables</li>
  <li>JavaScript Variables Practice - Part 1</li>
  <li>JavaScript Variables Practice - Part 2</li>
  <li>JavaScript Variables Practice - Part 3</li>
  <li>JavaScript Arrays - Part 1</li>
  <li>JavaScript Arrays - Part 2</li>
  <li>JavaScript Arrays Practice</li>
</ol>

<ul>
  <li>1.12.Reserved Words</li>
  <li>1.12.Array Methods</li>
</ul>

<h3>Week 2</h3>

<h3>Controlling Logical Flow in JavaScript</h3>

<p>In this module, you will be able to download, install and use of a code editor as 
a tool for writing code, and properly save and manage their files. You will be introduced 
to the selection control structure. This basic control structure allows programs to follow 
a path based on conditions, and is one of the three major logic and flow control structures 
found in any modern programming language.</p>

<p>You will be able to identify, write, and troubleshoot scripts using this basic control 
structure. You will be able to correctly identify loop structures and practice using some 
of the syntax available in JavaScript to create loops. You will then be able to put all 
three logical flow control structures (<b><i>sequence, selection, and loop</i></b>) together 
to create basic JavaScript programs that can be tested.</p>

<p>Finally you will be able to combine sets of program instructions into named functions 
and create custom functions that can be called to complete the instructions they contain.</p>

<h4>24 lessons/videos, 8 readings</h4>

<ul>
  <li>2.00.Learning Objectives</li>
  <li><a href="https://www.coursera.org/lecture/javascript-basics/module-2-introduction-8y2ue">2.00.Module 2 Introduction</a></li>
</ul>

<ol>
  <li>Visual Studio - Part 1</li>
  <li>Visual Studio - Part 2</li>
  <li>Visual Studio - Part 3</li>
  <li>Operators, Booleans & Selection in JavaScript</li>
  <li>Try This!</li>
  <li>Comparing Values</li>
  <li>Else If</li>
  <li>Switch Statements</li>
  <li>Using &&</li>
</ol>

<ul>
  <li>2.09.Operators</li>
  <li>2.09.Booleans</li>
</ul>

<ol type="1" start="11">
  <li>Loops in JavaScript</li>
  <li>Working With Arrays</li>
  <li>The For..Of Loop</li>
  <li>While Loops</li>
</ol>

<ul>
  <li>2.13.JavaScript Loops</li>
</ul>

<ol type="1" start="15">
  <li>Structured Programming, Sequence - Part 1</li>
  <li>Sequence - Part 2</li>
  <li>Sequence - Part 3, Loop</li>
  <li>Loop + Selection</li>
</ol>

<ul>
  <li>2.17.JavaScript Basic Challenges Introduction 01-09</li>
</ul>

<ol type="1" start="20">
  <li>Functions in JavaScript</li>
  <li>Passing In and Returning Data</li>
  <li>Useful Example - Step 1</li>
  <li>Useful Example - Steps 2-4</li>
  <li>Useful Example - Step 5</li>
  <li>More On Functions</li>
</ol>

<ul>
  <li>2.24.JavaScript Functions</li>
  <li>2.24.JavaScript Function Challengs 10-16</li>
</ul>


<h3>Week 3</h3>

<h3>Using JavaScript in the Web Browser</h3>

<p>In this module, you will be introduced to the methods built into
JavaScript for accessing and manipulating DOM elements in the web
browser. You will be able to capture user events with JavaScript and use
those events to trigger changes to the DOM using the document methods
and element properties. You will be able to identify how scope works in
JavaScript and be introduced to best practices for working with
variables in JavaScript so that scope does not become a problem. You
will be able to practice all the skills and techniques learned so far in
the course by putting together a simple slideshow on a web page.</p>

<h4>36 lessons/videos, 10+ readings</h4>

<ul>
  <li>3.00.Learning Objectives</li>
  <li><a href="https://www.coursera.org/lecture/javascript-basics/module-3-introduction-xK7aE">3.00.Module 3 Introduction</a></li>
</ul>

<ol type="1">
  <li>JavaScript and the DOM</li>
  <li>Dot Syntax and Methods</li>
  <li>DOM: getElementsByTagName();</li>
  <li>DOM: getElementsByClassName();</li>
  <li>DOM: querySelector();</li>
  <li>DOM: querySelectorAll();</li>
  <li>innerHTML</li>
  <li>className</li>
  <li>Creating Elements and Text Nodes</li>
  <li>Removing Elements</li>
</ol>

<ul>
  <li>3.10.JavaScript and the DOM</li>
  <li>3.10.JavaScript DOM Challenges 17-21</li>
</ul>

<ol type="1" start="11">
  <li>Capturing Events with JavaScript</li>
  <li>Event Listeners</li>
  <li>The Event Object</li>
  <li>More On Events</li>
  <li>Mouseover, Mouseover Events: HTML</li>
  <li>Scroll Events: HTML</li>
  <li>deo: Window Resizing</li>
  <li>Key Down Event</li>
</ol>

<ul>
  <li>3.18.Intro to Events in JavaScript</li>
  <li>3.18.Event Reference</li>
  <li>3.18.JavaScript Event Challenges 22-30</li>
</ul>

<ol type="1" start="19">
  <li>Scope in JavaScript</li>
  <li>Strategy 1: Never Use Global Scope</li>
  <li>Strategy 2: &ldquo;use strict;&rdquo;</li>
  <li>Strategy 3: const and let</li>
  <li>Scope in JavaScript Summary</li>
</ol>

<ul>
  <li>3.24.Additional Resources</li>
  <li>3.24.Simple Slide Show START Files</li>
</ul>

<ol type="1" start="25">
  <li>Simple JS Slideshow - Part 1</li>
  <li>Simple JS Slideshow - Part 2</li>
  <li>Simple JS Slideshow - Part 3</li>
  <li>Simple JS Slideshow - Part 4</li>
  <li>Simple JS Slideshow - Part 5</li>
</ol>

<ul>
  <li>3.29.Advanced Slide Show START Files</li>
</ul>

<ol type="1" start="30">
  <li>Slideshow with Cross Fade Effect - Part 1</li>
  <li>Slideshow with Cross Fade Effect - Part 2</li>
  <li>Slideshow with Cross Fade Effect - Part 3</li>
  <li>Slideshow with Cross Fade Effect - Part 4</li>
  <li>Slideshow with Cross Fade Effect - Part 5</li>
  <li>Slideshow with Cross Fade Effect - Part 6</li>
  <li>Slideshow with Cross Fade Effect - Part 7</li>
</ol>

<ul>
  <li>3.36.Prompt: Module 3 Reflection</li>
</ul>

<h3>Week 4</h3>

<h3>Basic JavaScript Application Projects</h3>

<p>In this module, you will be able to apply and practice the skills and
techniques you have learned in the course by building a basic and a more
advanced distance converter. You will be able to further apply and
practice to extend your skills and techniques by building a simple
vacation destination list application.</p>

<h4>25 lessons/videos, 4 readings, 4 zip uploadable files</h4>

<ul>
  <li>4.00.Learning Objectives</li>
  <li><a href="https://www.coursera.org/lecture/javascript-basics/module-4-introduction-FqHR0">4.00.Module 4 - Intro to Basic JS Application Projects</a></li>
  <li>4.00.Basic Distance Converter START Files</li>
</ul>

<ol type="1" start="1">
  <li>Basic Distance Converter Project - Part 1</li>
  <li>Basic Distance Converter Project - Part 2</li>
  <li>Basic Distance Converter Project - Part 3</li>
  <li>Basic Distance Converter Project - Part 4</li>
  <li>Basic Distance Converter Project - Part 5</li>
</ol>

<ul>
  <li>4.05.Advanced Distance Converter START Files</li>
</ul>

<ol type="1" start="6">
  <li>Advanced Distance Converter Project - Part 1</li>
  <li>Advanced Distance Converter Project - Part 2</li>
  <li>Advanced Distance Converter Project - Part 3</li>
  <li>Advanced Distance Converter Project - Part 4</li>
  <li>Advanced Distance Converter Project - Part 5</li>
</ol>

<ul>
  <li>4.10.Vacation Destination Project - Part 1 START Files</li>
</ul>

<ol type="1" start="11">
  <li>Vacation Destination Project: HTML & CSS - Part 1</li>
  <li>Vacation Destination Project: HTML & CSS - Part 2</li>
  <li>Vacation Destination Project: HTML & CSS - Part 3</li>
  <li>Vacation Destination Project: HTML & CSS - Part 4</li>
  <li>Vacation Destination Project: HTML & CSS - Part 5</li>
  <li>Vacation Destination Project: HTML & CSS - Part 6</li>
</ol>

<ul>
  <li>4.16.Vacation Destination Project - Part 2 START Files</li>
</ul>

<ol type="1" start="17">
  <li>Vacation Destination Project: JavaScript - Part 1</li>
  <li>Vacation Destination Project: JavaScript - Part 2</li>
  <li>Vacation Destination Project: JavaScript - Part 3</li>
  <li>Vacation Destination Project: JavaScript - Part 4</li>
  <li>Vacation Destination Project: JavaScript - Part 5</li>
  <li>Vacation Destination Project: JavaScript - Part 6</li>
  <li>Vacation Destination Project: JavaScript - Part 7</li>
  <li>Vacation Destination Project: JavaScript - Part 8</li>
</ol>

<ul>
  <li>4.24.Module 4 Reflection - Basic Application Projects</li>
</ul>

<ol type="1" start="25">
  <li>Course Summary: JavaScript Basics</li>
</ol>

<ul>
  <li>4.25.Self-Reflection - What Next?</li>
</ul>
<!--~~~~~~~~~~~~~~~~~~~~~~ start of course: uc-davis - javascript basics ~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~ week 1 - getting started, introduction to javascript, variables and arrays (09) ~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h1 id="ch1">Week 1</h1>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-00-note">1.00. A Note From UC Davis</h2>

<h3>Welcome to this course!</h3>

<p>We are delighted to be a part of your continuing education. This course will provide you 
with a variety of tools and learning opportunities, to include video lectures, readings, 
assessments, peer reviews, and an opportunity to contribute to the Coursera learning 
community in the discussion forums.</p>

<p>In each of the lesson sections, you'll find learning objectives, lecture videos, readings, 
activities, and an opportunity to test your knowledge in quiz format. In some of the module 
sections you'll also work on assignments and grade the work of your peers. A peer-review 
assignment, is one where you and your fellow learners have an opportunity to review and 
grade each other's work. We'll dive more into peer reviews later on in this course.</p>

<p>When navigating the course, you can find available <b>course resources</b> under each of 
the lecture videos in a section labeled "[Downloads]" -- here you can download the lecture 
video, view transcripts, PDFs of the lecture slides, and <b>find additional readings or 
files</b>.</p>

<p>If you run into any issues during this course, <b>learner support</b> is available to all 
Coursera students. The link for Coursera's Learner support is included below. The 
<a href="https://learner.coursera.help/hc/en-us">Help Center/Learner Support</a> includes 
topics such as account setup, payments, enrollment questions, and troubleshooting common problems.</p>

<p>If you find any content issues, be sure to let the course staff know by <b>flagging the 
lecture</b>, assignment, reading, or quiz and this will inform us of where these issues occur. 
Here is the link for more information on how to 
<a href="https://learner.coursera.help/hc/en-us/articles/208280106-Report-a-problem-with-a-course">
Flag an Issue</a> &minus; it is also listed below.</p>

<p>One of the great things about Coursera courses is that they are
self-paced. The course dates are based on the average time it takes to
complete a course. However, if you need additional time to complete a
course you can <b>reset your deadlines</b> with no penalties. More
information on resetting deadlines can be found here: 
<a href="https://learner.coursera.help/hc/en-us/articles/208279866-Assignment-deadlines">
Assignment Deadlines</a>.</p>

<p>Need additional help during your course session? Be sure to utilize the
<b>discussion forums</b> and interact with your fellow peers. In this area,
you can ask questions or search for similar issues that have already
been posted in the forums. Learner support is also a great place to find
answers, but specific course content questions can typically be found
and answered in the discussion forums. This is also a great place to
post your assignment if additional peer reviews are needed. Here is a
link with more information on the discussion forums: 
<a href="https://learner.coursera.help/hc/en-us/articles/208279996-Get-help-with-course-content-in-the-discussion-forums">
Discussion Forums</a>.</p>

<p>Because of the self-paced nature of Coursera courses, this is an excellent opportunity 
to show your commitment to your work and the work of your peers through academic integrity. 
Be sure to read the Coursera guidelines and the <b>Coursera Honor Code</b> here: 
<a href="https://learner.coursera.help/hc/en-us/articles/209818863-Coursera-Honor-Code">
Coursera Honor Code</a>.</p>

<p>We look forward to having you in this course. Happy learning!<br>
<b><i>UC Davis Coursera Team</i></b></p>

<h3>Additional Links:</h3>

<ul>
  <li><a href="https://learner.coursera.help/hc/en-us">1.00.Coursera's Learner Support/Help Center:</a></li>
</ul>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h1 id="ch1">Week One:</h1>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-00-obj">1.00 Learning Objectives</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<ul>
  <li>Identify interactions on web pages created with JavaScript.</li>
  <li>Articulate, in general terms, the importance of how JavaScript was developed and how that impacts the way JavaScript is written.</li>
  <li>Identify properly formed semantic HTML.</li>
  <li>Articulate major concepts in CSS.</li>
  <li>Identify properly formed CSS syntax.</li>
  <li>Write simple JavaScript statements in the web browser console.</li>
  <li>Assign and retrieve values from variables and arrays in JavaScript.</li>
</ul>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-00-welcome">1.00 Welcome to JavaScript Basics (1:01)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 03. module 1 welcome to js basics (09) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image003.png?raw=true"
  width="40%"
  alt="1.00. Welcome to JavaScript Basics." />
</p>

<p>Hello, and welcome to our course on JavaScript. My name is Bill Mead,
and I&apos;ve been teaching and learning about JavaScript for many years.
Here I am in California, outside on this beautiful day not that many
miles away from where JavaScript was invented over 25 years ago. It&apos;s a
fun programming language, I think you&apos;ll enjoy learning it. It can be
frustrating and maddening at times when you can&apos;t get it to work, but
when you do get things to work the way you want them to work, it&apos;s
super satisfying. It&apos;s become one of the most popular programming
languages in the planet.</p>

<p>As we go through this course and through this specialization, I think
you&apos;ll start to understand why it&apos;s satisfying and easy to get started
with and if you&apos;re new to programming, don&apos;t worry, we&apos;re going to
start at the very beginning and get you going all on the right track.
Buckle in and let&apos;s get started learning JavaScript.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-00-intro">1.00. Introduction to JavaScript Variables &amp; Arrays (0:57)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>Welcome to the first module on JavaScript. In this module we&apos;ll get
into the basics of the language. We&apos;ll talk about variables and arrays
and these kinds of things that you see in a lot of programming
languages. But we&apos;ll also talk about the history of JavaScript and do a
real introduction to the language. And the history of JavaScript is
super interesting because it has an impact on how we write JavaScript.
And that&apos;s really interesting to see how a language has evolved and
developed and how that affects the way you write modern, up to date
JavaScript. And I think you&apos;ll learn a lot from this and you&apos;ll be
able to do some interesting things with JavaScript as you go along. So
stick with me and we will have a lot of fun in this first module
learning about JavaScript in the basics of the language.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-01">1.01. Intro to JavaScript -- Part 1 (3:13)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 04. intro to javascript - part 1 (3:13) (10) ~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image004.png?raw=true"
  width="40%"
  alt="Introduction to JavaScript - Part 1." />
</p>

<p>Unlike a pillbox which really can&apos;t hold much more than just pills, you can put 
anything into an array in JavaScript.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 05. arrays in javascript (11) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image005.png?raw=true"
  width="50%"
  alt="Arrays in JavaScript." />
</p>

<p>You can even put in an array and an array. You think about a pillbox with a sub-container 
with even smaller divisions in it.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 06. inspect console arrays (11) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image006.png?raw=true"
  width="50%"
  alt="Inspect console and arrays." />
</p>

<p>Let&apos;s take a look at what that looks like. Let me switch back over to
my tab here. I&apos;m just going to paste this in, but you might want to
type it. It&apos;s a little bit hard to type and get right, but it&apos;s worth
trying if you can. I&apos;m going to paste this vehicle&apos;s array in here.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 07/08. console inspect array elements (12) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image007.png?raw=true"
  width="45%"
  alt="Inspect console with array elements, #1." />
<img src="./images/image008.png?raw=true"
  width="45%"
  alt="Inspect console with array elements, #2." />
</p>

<p>Now if I do, if I want to access an element from this array, I could do
vehicles, square bracket one. That&apos;s going to go and get the line that
starts with which element. There we go. Then, it&apos;s going to give me
this because this is zero, and now this is one. Right? It&apos;s going to
get me that into that sub-array. You can see it&apos;s sort of showing up
down there. Then if I do square bracket two, that&apos;s going to get me the
explorer elements in that sub-array. You can do things like that with
arrays.</p>

<p>That&apos;s kind of complicated and you&apos;re not probably going to be doing
arrays inside of arrays to start off with. But it&apos;s an important thing
to understand about arrays is that they&apos;re very flexible tools that you
can use to hold groups of data, and that&apos;s very useful.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 09. console inspect array elements, #3 (12) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image009.png?raw=true"
  width="50%"
  alt="Inspect console array element, #3." />
</p>

<p>Another thing that&apos;s interesting is that a regular variable holding a string can 
be treated as an array in JavaScript. If I make a variable var joke equals the chicken 
crossed the road, now I&apos;ve got a variable called joke, but I can actually treat 
it as an array. I could do. Joke square bracket four, and that&apos;s going to get me 
the C in chicken. Because zero, one, two, three, four is going to get me that C in
chicken. Or I could do, joke dot length, and it will tell me that there are 28 characters 
in that string. That&apos;s kind of an interesting thing to understand about arrays as well.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-02">1.02. Intro to JavaScript -- Part 2</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 10. inro to javascript - part 2 (13) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image010.png?raw=true"
  width="40%"
  alt="1.02. Introduction to JavaScript - Part 2." />
</p>

<p>A great place to go to find some websites that will show you the way JavaScript can 
interact with the website is this Awwwards website with the extra w&apos;s in here.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 11. javascript interaction: awwwards.com (14) ~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image011.png?raw=true"
  width="50%"
  alt="JavaScript Interaction: awwwards.com website." />
</p>

<p>I have that website pulled up over here. You can come here and look through some of 
the different sites that have won awards on <a href="https://www.awwwards.com/">
awwwards.com.</a>. They tend to be pretty innovative and interesting sites.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 12. taptaro example in awwwards.com (14) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image012.png?raw=true"
  width="50%"
  alt="TapTaro example from awwwards.com website." />
</p>

<p>I have <a href="https://www.awwwards.com/sites/taptaro">this one</a>. Whether you&apos;re 
talking about following the mouse, or coming over here and the animation around the circle, 
or the way these images pop in, this is all being done with JavaScript, this kind of thing.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 13. javascript example, no longer there (15) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image013.png?raw=true"
  width="50%"
  alt="NASA example from awwwards.com website.  No longer active." />
</p>

<p>Then here we are in one of the NASA spacecraft website here (no longer active). Click 
on one of these things it will come up and show you the different pictures and give you 
some other interactions including some sounds as you work around it.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 14. boyntonyards.com - awwwards.com (15) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image014.png?raw=true"
  width="50%"
  alt="Boyntonyards.com website from awwwards.com." />
</p>

<p>Or <a href="https://boyntonyards.com/">this website</a> which has some interesting 
interactions as you&apos;re scrolling through the website.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 15. boyntonyards.com, cont'd (16) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image015.png?raw=true"
  width="50%"
  alt="Boyntonyards website from awwwards.com, cont'd." />
</p>

<p>Yeah, look around on the web and wherever you see interactions happening, whether it&apos;s 
a map like this or all kinds of interactions are being created by JavaScript. You&apos;ve 
seen some interactions and websites and you&apos;ve probably seen plenty of others in other 
websites or you&apos;ve gone off and found your own.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 16. why learn javascript? (17) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image016.png?raw=true"
  width="50%"
  alt="Why Learn JavaScript?" />
</p>

<p>But let&apos;s talk about some other reasons why we should learn JavaScript.
First of all, it&apos;s the most popular programming language in the world.</p>

<p>There&apos;s also a low barrier of entry to the field. Whereas if you&apos;re
learning Java, or C, or C++, you&apos;re going to need a lot of experience
before you can get to a really good paying job. But JavaScript in the
web is the gateway to programming into the tech industry in this way.
It&apos;s really good to learn JavaScript for that reason.</p>

<p>Then finally, it is the language of the web. Now it goes well beyond the
web. We have Raspberry Pi and other devices that can all be programmed
with JavaScript robots and all kinds of things where JavaScript exists.
The Unity gaming engine uses JavaScript as well as C#. There are lots of
places where you can use JavaScript, but it is ultimately the language
of the web. It is the programming, the scripting language for the web
browser, and it&apos;s native to the web browser. That&apos;s a really great
place to start with programming.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 17. 1995 - beginnings of javascript (18) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image017.png?raw=true"
  width="50%"
  alt="1995 - The Beginnings of JavaScript." />
</p>

<p>The story of JavaScript is really interesting. It really is the story of
an underdog who became king. JavaScript didn&apos;t start off as the most
popular programming language. It&apos;s really important to understand this
path that JavaScript has taken through history because it has a big
impact on how we write JavaScript. JavaScript was written by this
gentleman here, Brendan Eich, in 1995 over the course of 10 days while
he was working at Netscape. I&apos;m not going to go into great detail on
the history here, but it&apos;s a really good thing to look up. It&apos;s a very
interesting story in and of itself. But he wrote the language in a very
short amount of time and that&apos;s an important thing to understand about
this language.</p>

<p>Another important thing to understand about the JavaScript programming
language is it&apos;s not the same language as Java. It was originally a
language called Mocha and they changed the name to JavaScript, really as
a marketing ploy. But it&apos;s not actually the same language as Java,
they&apos;re two completely different languages. It&apos;s easy as a beginner to
get confused between Java and JavaScript.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 18. javascript rough beginnings (19) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image018.png?raw=true"
  width="50%"
  alt="JavaScript's rough beginnings." />
</p>

<p>As I said before, JavaScript had some rough beginnings. The early years
of JavaScript were plagued by bad implementations, developers who just
despised the language mostly due to poor documentation and it was
greatly misunderstood as a language. This gentleman, Douglas Crockford,
did a lot to help people understand the incredible value of JavaScript
as a language and its strengths as well as its weaknesses.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 19. javascript - the good and the bad  (19) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image019.png?raw=true"
  width="50%"
  alt="JavaScript - The Good and the Bad." />
</p>

<p>He wrote a book called JavaScript: The Good Parts. It&apos;s a legendary
book because in this book he really talks about how JavaScript has some
of the best features any programming language has ever had right
alongside some of the worst features. Becoming a good JavaScript
developer is about understanding how to leverage the best parts of the
language while minimizing the worst parts of the language. We&apos;ll be
seeing some examples of some parts of the language that are good and
not-so-good right off the bat, and I&apos;ll be pointing those out.</p>

<p>You&apos;ll see that as we go along, we write JavaScript in ways to minimize
the bad features of the language. When I say bad features, what I mean
are features that can lead to more errors, lead to confusion in the
programming, and so on and so forth. But it&apos;s also a very expressive
language, it&apos;s a very powerful language. Some of the ideas behind it
are very interesting and very powerful, even though they&apos;re different
from other languages, which was behind some of the frustration that
people had with it initially is they just didn&apos;t understand it because
it was different.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-03">1.03. Intro to JavaScript -- Part 3 (5:33)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 20. intro to javascript - part 3 (20) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image020.png?raw=true"
  width="40%"
  alt="Intro to JavaScript - Part 3." />
</p>

<p>It&apos;s really important to understand the development of JavaScript over
the years, and this is because the way JavaScript is developed has
really impacted the way that we write JavaScript.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 21. javascript versions (21) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image021.png?raw=true"
  width="50%"
  alt="JavaScript Versions." />
</p>

<p>So having a little bit of understanding of this history is really important as you 
learn the language. Again, I&apos;m just going to cover just the very basics, but 
there&apos;s a lot of this history. It&apos;s a fascinating history and worth looking 
into if you&apos;re interested in that kind of thing and you can find out about it by 
looking it up on the web where there&apos;s plenty of books about it and that kind of 
stuff.</p>

<p>We know that JavaScript was originally written in 1995 in 10 days by Brendan Eich and 
his team at Netscape. Then in 1997, the first version of the standard was released, and 
the standard is created by the European Computer Manufacturers Association. Essentially 
the people in California went to Europe to this association to get this language rubber-
stamped. It didn&apos;t turn out to be quite that easy, but that&apos;s a longer story. 
But in 1997, the first version, <b>ECMAScript 1,</b> was standardized and released, and 
then a third version.</p>

<p>The second version never really quite happened, but the third version came out in 1999 
with some minor changes and fixes. The fourth version is an interesting story and one 
that I won&apos;t go into great depth on, but again, you can look it up for yourself. But 
essentially, if you&apos;ll recall, I had said earlier that there was a lot of arguing 
about the direction of JavaScript and there were a lot of developers that didn&apos;t
really understand it. There was some push to make JavaScript more like other programming 
languages that we&apos;re already familiar with and comfortable with. Douglas Crockford 
really stepped in and said,&quot; Wait, look, JavaScript is its own language and it has 
its own powerful features in its own right and if you understand it and make use of that
power then it really is valuable to keep it the way it is&quot;. It took a while for him 
to convince people of that.</p>

<p>But in 2009, they released <b>ECMAScript 5</b>, and <b>ECMAScript 4</b> was scrapped. 
They started to go a different direction entirely and then they scrapped that direction 
entirely. They released <b>ECMAScript 5</b> in 2009. This is the version that when it was 
released, everybody had kind of come together around the table and said, &quot;JavaScript 
is going to be the scripting language for the web&quot;. Because everybody had agreed with
that, this is when JavaScript really took off and made it past its troubled beginnings and 
its difficult beginnings was here in 2009. In 2009 is when JavaScript became King of the 
web because all of the major players agreed that this is going to be the scripting language, 
the programming language of the web. They built in a lot of features. There&apos;s a lot 
that&apos;s built into <b>ECMAScript 5</b> that we&apos;ll be using throughout this course.</p>

<p>Over the next 10 years, there was a lot of work on JavaScript. They really wanted to move 
it from being a scripting language to a general all-purpose language, something that was very 
powerful. In 2015, <b>ES6</b>, what is commonly referred to as <b>ES6</b>, was released,
sometimes it&apos;s called <b>ECMAScript 2015</b>. These two terms are interchangeable, but 
<b>ES6</b> was released and it&apos;s a big release, a lot changed and a lot was added, and a 
lot of JavaScript has been made more powerful and turned into a more general all purpose 
programming language. A lot of what you&apos;ll be learning in this course are pieces from 
the <b>2009 ECMAScript 5</b> standard and pieces from the <b>ECMAScript 2015 ES6</b> standard 
together, which really make up the major part of JavaScript.</p>

<p>Since 2015, the standardizing body has been in a nice cadence of
releasing new versions each year. From then on, instead of calling it
<b>ES7</b> and <b>ES8</b> and that kind of stuff, they stuck with the year.
They came out with <b>ECMAScript 2016, ECMAScript 2017</b>, and so on and
so forth. In each year there are smaller new additions added, but on the
whole, these additions are fairly small and they are being more advanced
pieces that we won&apos;t see nearly as much of in this course because this
is a beginner&apos;s course, but we will be doing a lot with <b>ECMAScript
5</b> and <b>ES6</b> or <b>ECMAScript 2015</b>. Dive in and I hope you enjoy
learning about JavaScript as we go along here.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-04">1.04 Tools Needed for Success</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~ 22. tools needed for success in learning javascript (23) ~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image022.png?raw=true"
  width="40%"
  alt="Tools needed for success in learning JavaScript." />
</p>

<p>Tools and skills needed for success for learning JavaScript.</p>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 23. tools and skills needed for success (23) ~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image023.png?raw=true"
  width="40%"
  alt="Tools and Skills Needed for Success." />
</p>

<p>First, we&apos;ll talk about software and then we&apos;ll talk a little bit about hardware.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 24/25. code editor (24) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image024.png?raw=true"
  width="40%"
  alt="Code editor." />
<img src="./images/image025.png?raw=true"
  width="40%"
  alt="Visual Studio Code editor." />
</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 26. visual studio code editor (24) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image026.png?raw=true"
  width="50%"
  alt="Visual Studio Code." />
</p>

<p>The first thing you&apos;re going to need in order to work with JavaScript and write 
JavaScript is a good code editor, and I recommend using Visual Studio Code. Not to be 
confused with Visual Studio product, but Visual Studio Code, and I have that in this 
browser tab here. You can download that for Mac or for Windows, or I believe also for 
Linux you can get Visual Studio Code. It&apos;s a really good code editor. It&apos;s 
very popular these days. There are plenty of other code editors out there.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 27/28. atom and sublime (25) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image027.png?raw=true"
  width="45%"
  alt="Atom web editor." />
<img src="./images/image028.png?raw=true"
  width="45%"
  alt="Sublime web text editor." />
</p>

<p>You could use Atom, you could use Sublime Text, even if you have Dreamweaver, you could 
use that as a code editor.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 29. adobe dreamweaver (25) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image029.png?raw=true"
  width="50%"
  alt="Adobe's Dreamweaver Web Editor." />

<p>Dreamweaver has a lot of other stuff built into it that you don&apos;t need, but it works 
perfectly fine as code editor if you want to use that as well.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 30. web browser (26) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image030.png?raw=true"
  width="40%"
  alt="Web Browser; Chrome Preferred. Also, Brave, Safari and Firefox." />

<p>The second thing you&apos;re going to need is a web browser, and I&apos;m going
to recommend that you use <b>Chrome</b>. <b>Chrome</b> has a lot of the
developer tools that developers use. They&apos;re built right into
<b>Chrome</b> and they&apos;re easy to access. You can also use <b>Safari</b> or
<b>Firefox</b> or <b>Microsoft Edge</b> or <b>Brave</b>. There are other browsers
out there as well and many of them also have developer tools, but most
developers use <b>Chrome</b> and get comfortable with the <b>Chrome</b>
developer tools. So I recommend that you download <b>Chrome</b> and use
that browser. Do NOT use <b>IE</b> or <b>Edge</b> developed by Microsoft.
Unless you LOVE advertisements and poor coding techniques.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 31. image editor - nice to have (26) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image031.png?raw=true"
  width="40%"
  alt="Image Editor: Would be nice to have - photoshop, GIMP, or IrfanView." />

<p>You&apos;re also going to need an image editor. If you have access to
Photoshop, that&apos;s great. Photoshop is fantastic for this kind of thing,
but if you don&apos;t have access to Photoshop, there&apos;s another one called
GIMP, which is free.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 32. gimp (27) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image032.png?raw=true"
  width="50%"
  alt="GIMP (GNU Image Manipulation Program) image editor." />

<p>You can go download <b>GIMP</b> and I have that pulled up here. You can actually download 
<b>GIMP</b> for Mac or for Windows and that kind of stuff. <b>IrfanView</b> is even better 
&amp; easier. There are also online tools, webpages that will allow you to upload your image 
and optimize it for the web and do some different kinds of image editing right through your 
browser. You might find some of those types of tools as well, but you will need some image 
editor to help you working with images. That&apos;s a nice to have. It&apos;s not absolutely 
necessary, but it&apos;s really nice to have.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 33. computer and internet access (27) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image033.png?raw=true"
  width="40%"
  alt="A Computer and Internet Access." />

<p>Next, you&apos;re going to need a computer and internet access. It may sound
obvious that you&apos;re going to need internet access to do an internet
class, but you are going to need that and you will need a computer,
whether it&apos;s a laptop or desktop.</p>

<p>What&apos;s not going to work very well is either a Chromebook or a tablet
or a phone. You&apos;re really going to need something that you can write
code on and save files to. iOS you can make it work, but it&apos;s not
really up to the task. You&apos;ll be fighting it every step along the way.
You want to be working with <b>Mac OS X</b> or <b>Windows 10</b> on a computer
in order to really make this work.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-05">1.05 Skills Needed for Success (5:38)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~ 34. skills needed for success with javascript (28) ~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image034.png?raw=true"
  width="40%"
  alt="Skills needed for success with JavaScript." />
</p>

<p>Let&apos;s talk about some of the skills you need in order to be successful learning 
JavaScript.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 35. keyboarding skills (28) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image035.png?raw=true"
  width="40%"
  alt="Keyboarding Skills." />

<p><b>First and foremost</b>, you need to be able to type. I mean typing with 10 fingers 
without looking at your fingers, touch typing. And it will really help you to be able to 
do this. If you&apos;re somebody who hunts in packs with one finger or two fingers, you 
may be pretty fast at it. But it really will slow you down for programming. And so I 
recommend that you do some online typing programs. There&apos;s plenty of places online
where you can learn how to type. You don&apos;t have to be terribly fast at typing. But 
you do need to be accurate. Or if you&apos;re not accurate with typing, you have to at 
least stop and go back and fix every single error. And I have known a lot of students 
over the years that struggle a lot with typing. And it really impedes their ability to 
learn something like JavaScript. So I recommend that you get those keyboarding skills 
if you don&apos;t have them already.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 36. file management (29) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image036.png?raw=true"
  width="40%"
  alt="File Management." />

<p>The <b>second</b> thing that you need is you need to be able to manage your
files. That means when you save a file on your computer, you know where
it is. Not just going into the file menu and choosing the most recent
files thing. If that&apos;s what you do to find your files, then you need to
get good at file management. And if your desktop looks like the picture
here, then you&apos;re going to be in trouble.</p>
<p>Make sure you&apos;re comfortable
with saving files into folders. And you know how to do that and where
those folders are on the web, everything is linked. So if a file cannot
be found, if a file is not in the right place, then your project will
break. And we don&apos;t want that to happen. So make sure you clean up all
of your files. And work with a clean desktop. And for every project, you
should have a folder and all the files you need for that project should
be in that folder.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 37. persistence (30) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image037.png?raw=true"
  width="40%"
  alt="Persistence." />

<p>The <b>third</b> thing that you need is persistence. Learning JavaScript is
not easy. It&apos;s challenging and maybe that&apos;s true for every programming
language. But JavaScript in particular it&apos;s got some quirks to it and
it takes some getting used to. And there will be times when you&apos;re
frustrated when things aren&apos;t working the way you think they should.
And you just need to take a break, step away from it and then come back
to it. But come back to it, because it&apos;s worth learning. And even
though it&apos;s hard, it&apos;s definitely worth putting in the effort and
being persistent to get there.</p>

<p>I&apos;ve told many students over the years
if you&apos;re not banging your head against the wall, you&apos;re not learning
JavaScript. All my students will tell you that I say that over and over
and over again. And it&apos;s frustrating especially in that moment when you
realize you just left that one character or semi colon or something like
that, and that broke the entire script. But stick with it, keep working
at it, stay calm, keep pushing forward. And you&apos;ll make a lot of
progress with it, I promise.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 38. logic (not math) (30) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image038.png?raw=true"
  width="40%"
  alt="Logic (not math)." />

<p>The <b>fourth</b> skill that you need is to be good with logic. And logic
is a learned skill. Some people are naturally very logical but it&apos;s
something that you can practice and develop. And there are lots of tools
and games out there that will help you build your logic skills. Sudoku
is a great place to go for puzzles that will help you build your ability
to use logic. Programmers often use math as well. But math is not that
important to begin with. It&apos;s really the logic skills that you need.
You might need some basic arithmetic. But I don&apos;t do a lot of
programming that involves very sophisticated math and a lot of
programmers don&apos;t. There are programmers that do. But we don&apos;t need
that in order to get good at JavaScript. But you do need to be good with
logic.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 39. html and css (31) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image039.png?raw=true"
  width="40%"
  alt="HTML and CSS." />

<p>The next thing is, you really should know HTML and CSS as well as you
can. JavaScript manipulates the HTML and CSS that makes up the page.
That&apos;s how it works, that&apos;s what it does. And if you don&apos;t know HTML
and CSS, you don&apos;t really know what you&apos;re manipulating. So I
recommend building some skills with HTML and CSS if you don&apos;t already
have them.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ 40. interneting is hard: great place for learning (31) ~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image040.png?raw=true"
  width="40%"
  alt="Interneting is hard: a Great Place for Learning HTML &amp; CSS." />

<p>And a good place to go is this <a href="https://internetishard.com">
Interneting Is Hard website</a>. This is a really great tutorial. They&apos;ve got 
a lot of really great, it&apos;s very simple the way they&apos;ve explained things. 
And they&apos;ve got a lot of great examples and tutorials here that will help you 
with learning HTML and CSS, and it&apos;s free. So I recommend going and looking 
through the Interneting Is Hard website if you need to get caught up I need you to 
know in CSS. Well, if you&apos;ve never done any HTML and CSS at all, then maybe 
take a course in HTML and CSS before diving into JavaScript.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 41. summary: learn javascript for free (32) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image041.png?raw=true"
  width="40%"
  alt="Summary: Learning JavaScript for Free." />

<p>In summary, there&apos;s a low barrier for entry to this class. The software
is free. You don&apos;t need a super fast, or super fancy computer. And
getting good at JavaScript can be a ticket to a high paying job, and a
good life. But it&apos;s not easy. You&apos;re going to have to work hard to get
there. But it really is worth it if you keep working at it. And I hope
that you continue with us and see all the cool things that you can do
with JavaScript.</p>

<!-- <h4>Here are resources related to these lessons:</h4> -->
<ul>
  <li><h3 id="ch1-05-assess">
  <a href="https://www.coursera.org/learn/javascript-basics/quiz/Ff15D/assessing-your-skills-in-html-css">
  1.05.Assessing your Skills in HTML & CSS</a></h3></li>
  <li><h3 id="ch1-05-add">1.05.Additional Resources;</a></h3>
    <ul>
      <li><a href="https://www.awwwards.com/">Awwwards website</a></li>
      <li><a href="https://code.visualstudio.com/">Visual Studio Code</a></li>
      <li><a href="https://www.google.com/chrome/">Google Chrome</a></li>
      <li><a href="https://www.adobe.com/products/photoshop.html">Adobe Photoshop</a></li>
      <li><a href="https://www.gimp.org/) https://www.gimp.org/">GNU Gimp</a></li>
    </ul>
  </li>
</ul>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-06">1.06 JavaScript Variables (6:27)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 42. javascript variables (33) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image042.png?raw=true"
  width="40%"
  alt="1.06. JavaScript Variables." />

<p>JavaScript variables.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 43. javascript variables (33) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image043.png?raw=true"
  width="40%"
  alt="JavaScript variables." />

<p>It&apos;s good practice when programming to write code that is as
generalizable as possible. It allows the code to be reused and helps
limit the effort of writing and maintaining redundant code. Imagine
somebody gave you a robot as a gift to do chores around your house. You
have to teach it how to do your chores.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 44. washing the dishes (34) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image044.png?raw=true"
  width="40%"
  alt="Washing the dishes." />

<p>What if you wanted to teach it to wash the dishes? That would be great.
It will be really helpful to have a robot wash the dishes for you. But
what if you had to write different instructions for each dish in your
house? That would be a lot of dishes and perhaps a lot of instructions.
That wouldn&apos;t be so great.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 45. using a variable (34) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image045.png?raw=true"
  width="40%"
  alt="Using a Variable." />

<p>What we can do with a variable is that we can treat it as like a
container, and then we can write a set of directions and pass each item
through that set of directions. Here in this diagram, currently, we&apos;re
going to rinse the food off the silverware and then wash the silverware
with soap and water, and then dry the silverware with towel and then
move on to the next thing which perhaps might be a cup. The red box that
you see here is really the variable. It&apos;s a temporary container that we
can pass these items through, and we can teach our robot to wash all of
the items one at a time using this container. That will make your
instructions more modular and more reusable and that&apos;s really helpful.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 46. declaring a variable in javascript (35) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image046.png?raw=true"
  width="40%"
  alt="Declaring a variable in JavaScript." />

<p>There are many ways of declaring a variable in JavaScript. We&apos;ll start
with one of the most basic ways which is using the <b>var</b> keyword
<b>V-A-R</b>. Here I have a variable called <b>x</b>, I&apos;m creating and
JavaScript will then recognize <b>x</b> as a variable and I&apos;m assigning it
an empty string, two sets of quote marks there followed by a semicolon.
That means that variable x holds an empty string.</p>

<p>On the next example, I have a variable called <b>cheese</b> that I&apos;ve
created, and it&apos;s holding a string called yummy. The equal sign here is
an assignment operator, it means assigned. So yummy is assigned to
<b>cheese</b>. It&apos;s easy to use the word equals because we&apos;re used to
seeing the symbol in association with math, where we see 2 plus 2 equals
4 and we say equals but in programming, we want to say assigned. Yummy
is assigned to <b>cheese</b>.</p>

<p>Then the next example we have a variable called <b>age</b> and it&apos;s
assigned a value of 25. Twenty-five is a number. It doesn&apos;t need to go
inside quotes because JavaScript knows what a 25 is.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 47. variables are case sensitive (35) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image047.png?raw=true"
  width="40%"
  alt="Variables are case sensitive." />

<p>In JavaScript, variables are case-sensitive. They have to follow certain
rules. For example, a variable has to start with a letter, you can&apos;t
start with a number.</p>

<p>This variable over here that says <b>1cat</b> is not going to work because
it starts with a number. Also, you should not start variables with
something like a dollar sign. They&apos;re used a lot by libraries, so you
should not do that as well. The third example, <b>my-cat</b> is not going
to work because JavaScript sees the dash as a minus sign. It thinks your
just trying to subtract cat from my which is not going to work it all
either.</p>

<p>Also, you can&apos;t have a space in a variable name because <b>var</b> my
might be a variable, but then it doesn&apos;t know what to do with cat
because it sees that as a separate thing because there&apos;s a space in
there.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 48. reserved keywords in javascript (36) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image048.png?raw=true"
  width="50%"
  alt="Keywords in JavaScript." />

<p>Finally, there are certain keywords in JavaScript that you can use as
names of variables like <b>new</b> is a keyword. Up here I have some of the
keywords pulled up on the W3Schools website. W3Schools is one of the
places you can go to get a lot of information about JavaScript, basic
information. We&apos;ll also look a lot at the MDN, the Mozilla Developer
Network, which is really the most authoritative place to get information
about JavaScript, but it can be a little bit overwhelming at first as
well. The W3Schools is a little bit easier to understand.</p>

<p>You can see here that there are a bunch of keywords. You&apos;ll notice that
some of them have an asterisk in here. Words marked with an asterisk are
new in <b>ECMAScript 5 and 6</b>. Remember, we talked about the versions of
JavaScript, so now when you see <b>ECMAScript 5 and 6,</b> you know that
we&apos;re talking about <b>ECMAScript 5</b> which was released in 2009, that
was the big release then, and <b>ECMAScript 6</b> or <b>ES6</b> was the
version that was released in 2015. These are all keywords that you can
use as names for variables in JavaScript.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 49. variable rules and examples (37) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image049.png?raw=true"
  width="40%"
  alt="Variable rules and examples." />

<p>Over on the right in this image here you&apos;ll see we have variable cat
with lowercase c, variable cat all in uppercase letters, and variable
Cat with a capital C. These are three different variables that hold
three different values. It&apos;s generally better practice to use lowercase
letters when creating variables or to do what&apos;s called camel casing
like we have done at the bottom here; myCat with a capital C in the
middle, so it&apos;s like a hump in the middle. We like camels in
JavaScript. That&apos;s called camel casing. That&apos;s not specific to
JavaScript but it&apos;s something that is in a lot of programming
languages. But we use that frequently in JavaScript. You&apos;ll frequently
see variables that are using camel casing.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-07">1.07. JavaScript Variables Practice -- Part 1 (7:12)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 50. javascript variables practice - part 1 (38) ~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image050.png?raw=true"
  width="40%"
  alt="1.07. JavaScript Variables Practice - Part 1." />

<p>We&apos;ve been talking long enough about JavaScript. So now it&apos;s time to
actually get down and write some. And I hope you&apos;re ready to do that
because it&apos;s pretty exciting to start seeing you come alive on web
pages. And it&apos;ll be a little while before we start making really
interesting things, but we&apos;ll be working with the basics now. So let&apos;s
get started with that.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 51. practice chrome inspect console (38) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image051.png?raw=true"
  width="50%"
  alt="Practice chrome inspect console." />

<p>And what we can do with our browser is we can actually open just a new
browser tab and use the console to write some JavaScript. Because
JavaScript is native to the browser, we can write it right into the
browser and it&apos;ll actually do stuff in the browser. I have a new tab
over here and you can create a new tab for yourself. And I&apos;m just going
to right click and choose <b>inspect</b>.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 52. google chrome inspect console (39) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image052.png?raw=true"
  width="50%"
  alt="Google chrome inspect console." />

<p>And you have to right click on the white area, you can&apos;t right click on
an element.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 53. inspect console right side (39) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image053.png?raw=true"
  width="50%"
  alt="Inspect console right side of screen." />

<p>Right click on the white area and choose inspect. And that&apos;ll bring up
the inspector in Chrome. And again, I&apos;m in Chrome. And when I do that,
it might put the inspector over here it might do some different kinds of
things. Some different buttons might be selected. But what you can do is
you can use these buttons here. You can arrange this thing, make it
bigger or smaller. You can use these buttons to move this inspector
around. So this button here will allow me to choose where I want it to
display.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 54. inspect console docking button (40) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image054.png?raw=true"
  width="50%"
  alt="Inspect console docking button to bottom of screen." />

<p>Right now, it&apos;s on the right but I could put it on the left or I could
put it on the bottom. I want it on the bottom in this case.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 55. inspect console dock to bottom (40) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image055.png?raw=true"
  width="50%"
  alt="Inspect console dock to bottom." />

<p>Sometimes, it&apos;s helpful to tear it off entirely into a different
window, which is this icon, but I&apos;m going to leave it down here on the
bottom. And then I want to close this thing down here because that&apos;s
just giving me some information. And I&apos;m going to make this come up
here.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 56. select elements tab to highlight (41) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image056.png?raw=true"
  width="50%"
  alt="Select elements tab for HTML and CSS highlight." />

<p>And right now and on the elements tab, and I can see the HTML that is
making up this page. And you can actually drag around on here and
you&apos;ll see different elements of the page will get highlighted.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 57. select console tab to write js (41) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image057.png?raw=true"
  width="50%"
  alt="Select console tab to write JavaScript." />

<p>But what I really want to do to write some JavaScript is the console. So
click on the console. And click the garbage can to clear console screen.
And now I can do things like create a variable, var cheese = &quot;yummy&quot;.
And again, yummy is assigned to cheese, the variable cheese here, put a
semi colon and press Enter.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 58. var cheese = "yummy"; (42) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image058.png?raw=true"
  width="50%"
  alt="var cheese = 'yummy';." />

<p>Now before I do this, another thing that&apos;s useful is if this is seeming
very small in your screen, you can use Ctrl on Windows or Cmd at Mac and
the plus key to make the text larger or the minus key to make it
smaller. Plus and minus or you can do command zero to put it back to the
default size. So, a lot of times when I&apos;m working with students, they
have trouble seeing the syntax and I recommend making the actual code
larger so that you can see it better. So I&apos;m going to make it larger
like that. So var cheese = &quot;yummy&quot;. Great, undefined is sort of the
return value. This doesn&apos;t have a return value. I&apos;m just assigning a
variable here so don&apos;t worry factor that says undefined here. Now that
I&apos;ve defined this variable, if I type cheese, you&apos;ll see that I get
yummy. That comes back. That&apos;s the return value for that variable, for
that variable name.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 59. practice chrome inspect console (43) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image059.png?raw=true"
  width="50%"
  alt="myNum = 5; (no var)." />

<p>I&apos;m going to make a new variable. Line and assign it a value of 5. And
I get a 5 back. That returns the value of 5. So I could make another
variable. When I created my num, you&apos;ll notice I forgot to use the var
keyword. And that&apos;s fine. JavaScript will adjust for that in this case
and we&apos;ll talk later about what happens when you don&apos;t use the var
keyword. But in this case, it&apos;s fine. It actually created a variable
called <b>myNum</b> and assigned it 5.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 60/61. without var, value is undefined (43) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image060.png?raw=true"
  width="45%"
  alt="Defining variables with/without var command." />
<img src="./images/image061.png?raw=true"
  width="45%"
  alt="Without the var command, value is undefined." />
</p>

<p>But it would be better to use the var keyword for <b>myOtherNum</b> = 6,
that comes back undefined. And this came back with 5 because of the fact
that I didn&apos;t use the var keyword. But if I do <b>myNum</b>, you&apos;ll see
I&apos;ll still get 5. If I do <b>myOtherNum</b>, and you&apos;ll notice that in
Chrome, it&apos;s predicting what I&apos;m going to type. And if I press tab on
the keyboard, I don&apos;t even have to type that whole thing. I can do
something like, Var sum = myNum Plus myOtherNum, I can even pick it from
the list using my keyboard here. So I don&apos;t even have to type it. Now
if I do sum, you&apos;ll notice I get an 11 because it&apos;s doing basic
arithmetic.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 62. examples utilizing console.log (44) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image062.png?raw=true"
  width="50%"
  alt="Example variables utilizing console.log." />

<p>I can also use a method called <b>console.log</b>. <b>Console.log</b>, and I
could do <b>myNum, Times, MyOtherNum</b>. Semi colon, and you&apos;ll notice
that I get 30 because it&apos;s taken 5 and multiplied it by 6. Now we&apos;re
in the console, so we don&apos;t have to use the <b>console.log</b> statement
here. The <b>console.log</b> method, but because I can just do <b>myNum</b>
times <b>myOtherNum</b>. And you&apos;ll see I still get 30. But I&apos;m showing
you the <b>console.log</b> method because when we start working with files,
we&apos;ll use this method a lot to send things to this console. While I&apos;m
in the console, I don&apos;t actually need to use it.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-08">1.08 JavaScript Variables Practice -- Part 2</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ 63. javascript variables practice - part 2 (1.08) (45) ~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image063.png?raw=true"
  width="40%"
  alt="1.08. JavaScript Variables Practice - Part 2." />

<p>Here you can see a cleared out the console by clicking this clear thing here.</p>

<p>That won&apos;t actually forget any of the code that you&apos;ve put.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 64. click refresh to forget variable (45) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image064.png?raw=true"
  width="50%"
  alt="In console.log click refresh to clear console & forget variables." />
<!-- ![](./images/media/image64.png){width="5.0in" height="3.053418635170604in"} -->

<p>If you do want to actually forget the variables, you can click the
Refresh button up here that will actually forget everything.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 65. add number to string = string (46) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image065.png?raw=true"
  width="50%"
  alt="newNum + notNum = concatinated string." />

<p>Now I&apos;m getting the error that came back just with the Google page, but
I can clear that here. I can actually create variables fresh that way.
But let&apos;s do this, I&apos;m going to make a variable <b>var notNum</b>, I&apos;m
going to assign it a value of five. But I&apos;m putting it in quotes
because it&apos;s not really a number. It&apos;s a string with a number in it. I
can make another <b>var newNum</b>, I&apos;m going to assign it a value of ten.
That&apos;s actually a number. Now watch this. If I do <b>newNum</b> plus
<b>notNum</b>, it gives me 105 inside quotes.</p>

<p>Now, JavaScript is loosely typed. You do not have to specify what type
of data a variable&apos;s going to hold when you create the variable. A lot
of people don&apos;t like that about JavaScript. Way back in the day when
they were working on ECMAScript 4, you&apos;ll remember that version was
never released. They were thinking seriously about switching JavaScript
to being a more strongly typed language. Like other languages, where you
have to declare what type of data a particular variable will hold when
you create the variable. But in JavaScript, you don&apos;t have to do that.</p>

<p>Douglas Crockford, who we mentioned earlier, made a strong argument that
the loosely-typed nature of JavaScript is actually very expressive and
very powerful in its own way if you know how to use it properly. But it
can lead to confusion. Here&apos;s a good example of that, where we might
get something that we don&apos;t expect. Perhaps we expected to add 10 to 5
and get 15, but instead, we got 105 in a string. So that&apos;s an important
distinction and something important to understand about the way
JavaScript works.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 66. plus operator to add or concatinate (47) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image066.png?raw=true"
  width="50%"
  alt="." />

<p>Another thing to know is that the plus operator in JavaScript does
double duty. It will add numbers together, so we can make another
variable, var newNum 2, and assign it a value of six. Then I could do
newNum plus newnum2 and it&apos;ll give me 16. So it&apos;ll add numbers
together, but it will also <b>concatenate</b> strings. Here we were seeing
the plus sign actually doing some <b>concatenating</b> because one of those
elements was a string. So it can <b>concatenate</b> it together and I got
105. Then here, when we use the plus sign, it&apos;s actually adding. This
is a problem in JavaScript and they&apos;ve done some things in the language
to help mitigate the fact that the plus sign does both things. We&apos;ll
look at what we can do to deal with that. We&apos;ll look at some better
ways of putting strings together other than using the plus sign. But
these features of JavaScript that were built in from the beginning,
persists to this day.</p>

<p>The plus signs still does two things, it <b>concatenates</b> and it adds.
Here we&apos;re seeing already, very much at the beginning of the course,
things about JavaScript that are a little bit different. We&apos;re seeing
that it is a loosely typed language and that&apos;s unusual. We&apos;re also
seeing that the plus sign does double duty. That&apos;s not only unusual but
a little bit problematic. Already you&apos;re learning a little bit about
why we use JavaScript in certain ways or why we type in certain ways.
We&apos;ll get into more detail about that as we go along.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-09">1.09. JavaScript Variables Practice -- Part 3 (5:21)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ 67. javascript variables practice - part 3 (1.09) (48) ~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image067.png?raw=true"
  width="40%"
  alt="1.09. JavaScript Variables Practice - Part 3." />

<p>I&apos;m going to clear out my console here, press the clear button there,
and then I&apos;m going to create a new variable, var myNum equals 10,
We&apos;ll put that in there.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~ 68. differentiating between num and string (48) ~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image068.png?raw=true"
  width="50%"
  alt="Differentiating between numbers and string characters." />

<p>Then I&apos;m going to make another variable, var, myNumAsString. I&apos;m going
to make a variable there and we&apos;ll call it five. But that variable
again is a string. Now it&apos;s important to note that even though
JavaScript is loosely typed, it doesn&apos;t mean that variables don&apos;t have
a type. If I do typed, which is a method that allows me to pass in a
variable like myNum. It&apos;ll tell me that it is in fact a number. Whereas
if I do typeof myNumAsString, I can actually pick it from the list here
so I don&apos;t have to type the whole thing. It&apos;ll tell me that&apos;s a
string. If I make a variable, var undefinedvariable, and leave it empty,
so there&apos;s nothing in here. I could do typeof undefinedvariable to get
my variable here. You&apos;ll see that I get undefined. Or I could do var
nothingAtAll and assign it null, and I could do typeof nothingAtAll, and
I get object, so that&apos;s kind of interesting. These are all very
different variables with different values. That&apos;s an important thing to
understand about JavaScript, but they do have type associated with them.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 69. var empty string (49) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image069.png?raw=true"
  width="50%"
  alt="var empty string." />

<p>Let&apos;s try one more. I&apos;m going to make another variable var
emptyString. I&apos;m going to assign it a couple of quotes, and if I do
typeof emptyString, you&apos;ll see even though there&apos;s nothing in there,
there&apos;s nothing really assigned to this variable. The fact that I put a
pair of quotes there means that it is in fact a string. It&apos;s also kind
of important to note that I could use single quotes or double quotes in
JavaScript.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 70/71. mdn & w3schools.com (50) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image070.png?raw=true"
  width="45%"
  alt="MDN - Mozilla Developer Network." />
<img src="./images/image071.png?raw=true"
  width="45%"
  alt="W3Schools.com - for learning HTML and CSS." />
</p>

<p>Now if you want to find out more about the type of method, you could
come over here and just Google JavaScript typeof. The MDN will come up
very quickly, if not the first, sometimes you&apos;ll get W3Schools. The
MDN, which is the Mozilla Developer Network, is the definitive resource
for web technologies such as HTML and CSS and will give you a lot of
information about different methods and different things you can use.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 72. console.log(typeof x) (50) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image072.png?raw=true"
  width="50%"
  alt="console.log(typeof x); where x is string, number, bigint, boolean, 
    undefined, null, symbol or object.  Object is object, array or date." />

<p>We&apos;ll be referring a lot to the MDN throughout this course, sometimes
the W3Schools website as well, but the MDN really is sort of the
definitive resource, but it can be a little bit confusing at first.
Sometimes the W3Schools website is a little bit easier to understand,
but the MDN is very thorough. That gives us a very basic start at
creating some variables that can hold different pieces of data. At this
point, you&apos;re probably wondering yeah, so what? But remember that as
we&apos;re learning a language, right now we&apos;re just learning the alphabet
and the letters by themselves don&apos;t really do all that much. It&apos;s not
until you start putting them together to form words they can start to
have meaning.</p>

<p>We&apos;ll be working on some more of these very basic elements of
JavaScript, but then pretty quickly we&apos;re going to be getting into more
interesting aspects of the language, and you&apos;ll be creating more
interesting little programs that will actually do things on web pages
and on websites.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-10">1.10. JavaScript Arrays -- Part 1 (5:27)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 73. javascript arrays - part 1 (1.10) (51) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image073.png?raw=true"
  width="40%"
  alt="1.10. JavaScript Arrays - Part 1." />

<p>JavaScript arrays.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~ 74. an array is a container with sub-containers (51) ~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image074.png?raw=true"
  width="40%"
  alt="An Array is a Container with Sub-containers." />

<p>An array is really just a container with sub-containers and it&apos;s the
next piece of the puzzle that we need to talk about in terms of
JavaScript. We talked about variables, and an array is just another type
of variable. But instead of holding one piece of data, it can hold
multiple pieces of data. Think of it like a pillbox. Perhaps you or a
friend or relative has to take medications each day and perhaps they
have a box that looks like the image here on your screen where you have
different containers that are going to hold different pills for the
week. Frequently in JavaScript, we have to deal with groups of things.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 75. working with groups (52) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image075.png?raw=true"
  width="40%"
  alt="Working with Groups." />

<p>If we go back to our robot analogy, if we&apos;re teaching our robot how to
wash the dishes, perhaps glasses need to be handled in a certain way or
perhaps plates need to be handled in a certain way. Then when it comes
to working with the silverware, the silverware needs to be handled in a
certain way, but then we&apos;ve got a subgroup of spoons, and knives, and
forks, and maybe other pieces of silverware. That&apos;s a group within a
group. The analogy that works best for that is thinking about groups of
things with arrays.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 76. creating an array in javascript (53) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image076.png?raw=true"
  width="40%"
  alt="Creating an array in JavaScript." />

<p>Let&apos;s take a look at what that looks like. In JavaScript, we can create
a new array in a couple of different ways. We can use the new keyword
with array and parentheses as shown here or we can create it more
explicitly using the square brackets as shown below on the right here.
Let&apos;s actually do this over the console. I think it&apos;s helpful to
actually see us create these elements.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 77. inspect, console.log new array example (53) ~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image077.png?raw=true"
  width="50%"
  alt="Example variable array in console.log." />

<p>I&apos;m going to come over here and make a new tab, and choose Inspect,
right-click and choose Inspect. Then I&apos;m going to run the console here,
clear out this area. Then I&apos;m going to make an array, var. I&apos;m going
to call it colors one equals new array. Then in here, in quotes, I&apos;m
going to put some colors, &quot;red,&quot; &quot;green,&quot; &quot;blue.&quot; Now I&apos;ve
created that array. I can access those colors by typing
<b>colors1&lbrack;0&rbrack;.</b> That will get me the first color in that array.
That&apos;ll give me the red or I could make an array more explicitly. This
is the more common way that you&apos;ll see it done is var colors 2 equals
square bracket and then &quot;yellow,&quot; &quot;orange,&quot; &quot;purple,&quot; square
bracket, semicolon. Now I&apos;ve created a second array and I could do
colors 2 square bracket 2. That will get me the third element in the
array.</p>

<p>Now, square bracket two gets me the third element. Arrays are
zero-indexed. The length of the array is 3, <b>colors2.length</b>. Because
there are three elements in the array. It&apos;s just they&apos;re numbered 0,
1, and 2. Normally, we start counting with 1 first, 1, 2, 3. But in
programming, frequently we start counting with 0 first, 0, 1, 2, but the
length of the array is 3. That&apos;s an important distinction and something
to be aware of.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-11">1.11. JavaScript Arrays -- Part 2 (3:17)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 78. javascript arrays - part 2 (1.11) (54) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image078.png?raw=true"
  width="40%"
  alt="1.11. JavaScript Arrays - Part 2." />

<p>Unlike a pill box, which really can&apos;t hold much more than just pills,
you can put anything into an array in JavaScript.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 79. you can put anything in an array (55) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image079.png?raw=true"
  width="50%"
  alt="You can put an array within an array." />

<p>You can even put in an array in array. So you think about a pillbox with
a sub container with even smaller divisions in it. So let&apos;s take a look
at what that looks like.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~ 80. example array; vehicles, make and model (55) ~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image080.png?raw=true"
  width="50%"
  alt="Example array of vehicles by make and model." />

<p>Let me switch back over to my tab here. And I&apos;m going to clear out this
tab by clicking the clear button there. And I&apos;m just going to paste
this in but you might want to type it, it&apos;s a little bit hard to type
and get right but it&apos;s worth trying if you can, but I&apos;m going to paste
this vehicles array in here. And now if I do, if I want to access an
element from this array I could do vehicles &lbrack;1&rbrack;. That&apos;s going to go
and get the line that starts with which element, there we go. And then
so it&apos;s going to give me this because this is zero, and then this is
one, right? So that&apos;s going to get me that into that sub array. You can
see it sort of showing up down there. And then if I do &lbrack;2&rbrack;, that&apos;s
going to get me the Explorer element in that sub array. So you can do
things like that with arrays. That&apos;s kind of complicated. And you&apos;re
not probably going to be doing arrays inside of arrays to start off
with. But it&apos;s an important thing to understand about arrays is
they&apos;re very flexible tools for you can use to hold groups of data, and
that&apos;s very useful.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 81. example string variable as an array (56) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image081.png?raw=true"
  width="50%"
  alt="A string variable can be treated like an array." />

<p>Another thing that&apos;s interesting is that a regular variable holding a
string can be treated like an array in JavaScript. So if I make a
variable, var joke = &quot;The chicken crossed the road&quot;. Now I&apos;ve got a
variable called joke, but I can actually treat it like an array. I can
do joke &lbrack;4&rbrack;, and that&apos;s going to get me the c in chicken because
zero, one, two, three, four is going to give me that c in chicken. Or I
could do joke.length and it&apos;ll tell me that there are 28 characters in
that string. So that&apos;s kind of an interesting thing to understand about
arrays as well.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-12">1.12. JavaScript Arrays Practice (6:16)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 82. javascript arrays practice (1.12) (57) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image082.png?raw=true"
  width="40%"
  alt="1.12. JavaScript Arrays Practice." />

<p>Let&apos;s do a little bit of practice with arrays, so I can make a new
variable bar Animals and assign an array.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~ 83. define var animals = ['cat', 'dog', 'chicken']; (57) ~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image083.png?raw=true"
  width="50%"
  alt="Define array; var animals = ['cat', 'dog', 'chicken'];." />

<p>Cat, dog, chicken and all of those animals will be in the array. So if I
just do animals. You&apos;ll see that I get back an array with three
elements, cat, dog and chicken. Now, arrays come with certain array
methods that you can do to arrays specifically, so if I do animals.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 84. animals.push('llama'); to array (58) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image084.png?raw=true"
  width="50%"
  alt="Add llama with animals.push('llama');." />

<p>That push llama, now there are four elements in the animals array. The
cat, dog, chicken and the llama are all in the array.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 85. push array method (58) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image085.png?raw=true"
  width="50%"
  alt="Example push array method." />

Remember, we can use the console log method we don&apos;t really need to
hear in the console, but we will when we go to using file shortly. So
it&apos;s worth remembering that we can do console dot log. Parentheses,
that&apos;s a parentheses, animals. Square bracket, one or two. Let&apos;s do
two since I put a two in their square bracket, and then the parentheses,
console log animals square bracket two. And then if I press return
there, it&apos;ll give me the chicken. I don&apos;t really need to use the
console log method here in the console. But you can, and it&apos;s worth
remembering that you can do that.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 86. splice array method to remove (59) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image086.png?raw=true"
  width="50%"
  alt="Example splice array method." />

Now, what if I wanted to remove an element from the array or we could do
animals that splice (1, 1) and that will take the dog out of the array.
So now, if I do animals, you can see it&apos;s got the cat, chicken, and the
lama,but not the dog.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 87. push and sort array methods (59) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image087.png?raw=true"
  width="50%"
  alt="Example push and sort array methods." />

And I could do push and push the dog back into the array. Let&apos;s do
that, animals don&apos;t push, dog and now the dog is back in the array.
Another array method is sort, animals. dot sort. And notice now that the
order of the animals in the array has changed slightly, so that the dog
is in the third position based on alphabetical order. So there are a lot
of array methods that you can use.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 88. w3schools javascript arrays methods (60) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image088.png?raw=true"
  width="50%"
  alt="W3schools JS array methods; toString." />
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 89. basic array methods (60) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image089.png?raw=true"
  width="50%"
  alt="List of Basic Array Methods; length, toString, at, join, pop & push." />

<p>And a really good place to go look at them would be the <b>W3schools.com</b> website or the 
MDN JavaScript arrays. And here it is here and then they&apos;ll have array methods here. 
There are all kinds of examples of array methods that you can use. You can join, we can 
do all kinds of things. And it&apos;s worth exploring some of the different methods and 
trying them out on your own with just messing around with arrays. And just working in the 
console and getting used to how this works, because that&apos;s a really great way of 
learning sort of the basics of JavaScript.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 90. array of four animals (61) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image090.png?raw=true"
  width="50%"
  alt="Array of four animals." />

<p>Here&apos;s a challenge for you, we have an array for animals here, and we
can see that the length of the array is four but you could also find out
by doing animals dot length and you&apos;ll get four. Now, what if you
didn&apos;t know how long the array was? How could you always get the last
element in the array? What would be the code that I could type in here
that would always give me the final element in the array no matter how
long it is. <b>animals&lbrack;animals.length-1&rbrack;;</b> Here&apos;s what I would do. I
would do animals, then square bracket, then I want to get the length,
animals dot length but I need to subtract one because the length of the
array is four. Actually the last element is element number three and
you&apos;ll see that that will in fact get me the Llama at the very end.</p>

<p>So I&apos;m going into my animals array and what I&apos;m passing in is
<b>animals&lbrack;animals.length-1&rbrack;;</b> animals dot length, which will be a 4-
1 which gets me this element here. Zero, one, two three and that may
seem a little counterintuitive to begin with, but you&apos;ll get used to
working with arrays and with the lengths of arrays and with different
ways of getting elements out of arrays.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Additional Resources</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>Here are resources related to these lessons:</p>

<ul>
  <li id="ch1-12-res"><a href="https://www.w3schools.com/js/js_reserved.asp">
    1.12.Reserved Words</a></li>
  <li id="ch1-12-array"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array">
    1.12.Array Methods</a></li>
</ul>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h1 id="ch2">Week Two:</h1>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-00-obj">2.00 Learning Objectives</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
  <ul>
    <li>Download and install a code editor.</li>
    <li>Use the code editor to create HTML files.</li>
    <li>Manage files and folders.</li>
    <li>Use the explorer in Visual Studio Code to organize and link to files.</li>
    <li>Identify selection structures within programs.</li>
    <li>Identify expressions that evaluate to true or false in JavaScript.</li>
    <li>Write the syntax necessary for creating selection structures in JavaScript.</li>
    <li>Troubleshoot scripts when they have errors.</li>
    <li>Use a code editor to write scripts.</li>
    <li>Correctly identify loop structures in programming.</li>
    <li>Use correct syntax to write loops in JavaScript.</li>
    <li>Identify and fix errors in the program when they occur.</li>
    <li>Write basic JavaScript programs in a code editor and run them in the browser.</li>
    <li>Combine logic flow control structures within simple programs.</li>
    <li>Output program results to the console window.</li>
    <li>Create custom functions that can be called to complete the instructions they contain.</li>
    <li>Practice working with combining control structures (<b><i>sequence, selection</i></b> and <b><i>loop</i></b>) and creating functions to create
	  basic programs that output to the browser console.</li>
</ul>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-00-intro">2.00 Module 2 - Controlling Logical Flow in JS (0:51)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 91. module 2 introduction (63) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image091.png?raw=true"
  width="40%"
  alt="2.00. Module 2 introduction." />
</p>

<p>Welcome to the second module. In this module, we'll get further into the basics of the 
JavaScript language. There are certain things that you'll find in many modern programming 
languages, such as control structures, such as being able to figure out if something is 
true or how to handle something in a <b><i>loop</i></b> and these kinds of things. We'll be doing that 
sort of work in this second module. There's a lot of practice and there's a lot of 
opportunities along the way to get used to the JavaScript syntax. I encourage you to do 
as much of that as you possibly can.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 92. visual studio - part 1 (2.01) (63) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-01">2.01 Visual Studio – Part 1 (4:39)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image092.png?raw=true"
  width="40%"
  alt="2.01. Visual Studio - Part 1." />
</p>
 
<p>In this lesson, we're going to be talking about working with the code editor and I'm 
going to be specifically looking at Visual Studio Code, which I have pictured here 
on this slide (see below). But I also have it open over here in this tab and you 
can go down the download Visual Studio Code for Mac or Windows for free and it's a 
great code editor if you prefer to use a different code editor such as Atom or Sublime 
Text or something else. That's fine too. As long as it's got great features for editing 
code and it's not a word processor like Microsoft Word. But I'll be using Visual Studio 
Code throughout this course, so it might be helpful for you to use that as well.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 93. visual studio editor on startup (64) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image093.png?raw=true"
  width="50%"
  alt="VS Editor on startup." />
</p>
 
<p>Sometimes when you open Visual Studio Code, you'll get these tabs open with the Welcome 
or with new release notes if they've come out with a new version and you can just close 
those tabs by clicking on the "X". You'll notice I have Visual Studio Code open in running 
here, but I don't have any of those editors open and I can make a new file by just going 
and choosing a new file, and that creates a new file here.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 94. visual studio startup screen (65) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image094.png?raw=true"
  width="50%"
  alt="Visual Studio startup screen." />
</p>
 
<p>It's important with Visual Studio Code that before you do anything else, you save your 
file. That way it knows what type of file you're working with. I'm going to choose file 
save as, and I'm going to just save this as "myfile.hml". I'm going to save an HTML file, 
to begin with on my desktop. Once I have an HTML file, then I can get the basic HTML 
structure by holding down "Shift", pressing an exclamation point, and then pressing "Tab" 
and that will give me the basic structure for my page.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 95. visual studio startup screen (65) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image095.png?raw=true"
  width="50%"
  alt="Visual Studio startup screen." />
</p>

<p>If you take an HTML class, you'll learn to type the doctype and to type all these tags, 
we can use the shortcut. Again, what you did to get it, I'll just type exclamation point 
and then press "Tab" and then you can come in here and give your document a name, "My File". 
The title shows up in the tab in the browser. That's important. Great. I can save that.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 96. visual studio startup screen (66) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->

<img src="./images/image096.png?raw=true"
  width="50%"
  alt="Visual Studio startup screen." />
</p>

<p>Now, one thing to notice really quickly while we're here, see this dot up here, 
that means this file has changed and it has not yet been saved. One of the frequent 
mistakes I see at the beginning with users getting started with, working with HTML 
and CSS and JavaScript is they'll add things to the file and then they'll forget to 
save them, and then they're going to run the file and they realize their changes 
aren't showing up, so watch out for that little dot. You can get that to go away by 
doing "File", "Save" over here or "Command S", "Control S" in windows, and then it'll 
go back to just the X, which you would use to close that tab and close that window app, 
and then I can open this back up again by dropping it here and that will open that file 
back up again. That gets me some basics of getting files opened and working here in 
Visual Studio Code.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 97. windows users: show file extensions (67) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image097.png?raw=true"
  width="50%"
  alt="Windows users: Show file extensions." />
</p>

<p>A important note, if you're on Windows is, open up any Explorer Window. Click on the 
"View" tab and then go over and verify box is checked in "File name extensions". That 
way when you save your files, you'll see the ".html" file extension, and that's important. 
But here I have a screenshot of it so please make sure you do that. Also. Make sure that 
when you save files, make sure that the filename is always lowercase and never has a 
space in it so I have "myfile" all as one word here. Do not put spaces in filenames, 
they cannot be more explicit about that.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-02">2.02 Visual Studio – Part 2 (5:48)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 98. visual studio - part 2 (2.02) (67) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image098.png?raw=true"
  width="50%"
  alt="2.02. Visual Studio - Part 2." />
</p>

<p>I'm back in my code editor. And now, I'm ready to add a script. So let's add a script 
to this file. And we can see some JavaScript actually happened here.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 99. add 'my first script' as an h1 (68) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image099.png?raw=true"
  width="50%"
  alt="Add 'My First Script' as an h1." />
</p>
 
<p>First, I'm going to put some HTML on the page, My First Script. And then you can 
actually put scripts really anywhere inside this file. Sometimes they go in the head 
of the page here inside the head tag. Frequently, you'll see them down here just 
before the closing body tag. So I'm going to make a script tag. And then it puts 
the cursor between the two, and I can move that down.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 100. add new variable var hello (69) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image100.png?raw=true"
  width="50%"
  alt="Add a new variable; var hello." />
</p>

<p>And here I can make a variable, var hello = “Good Morning Bill!”;. And then in order 
to get it to do something currently what we have to work with is the console. because 
that's what I've shown you so far in the other videos, we'll get to other things later. 
And really pretty soon, but for right now we just have the console. So I can use 
console.log, remember, we talked about this method before. (hello) to put that variable 
or really the string associated with that variable into the console. So I can save this 
file and there's the data up here, I have to save it. I can save the file and then I can 
go over to Chrome over here.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 101. file open, my first script (69) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image101.png?raw=true"
  width="50%"
  alt="File open, My First Script." />
</p>
 
<p>And I can go to File and open, or on Windows, you can do Cmd+O. And then here I am on my 
desktop and I can open this file. And it comes up and it doesn't really look like much, 
it's just a webpage and we're not even seeing the script run.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 102. test, inspect, my first script (70) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image102.png?raw=true"
  width="50%"
  alt="Test, inspect, My First Script." />
</p>

<p>But if we go and choose Inspect and then click on the Console, you'll see that it comes 
up here. And my JavaScript is actually running. We've gotten our first script to run. 
The next thing to talk about is how we can make some comments in JavaScript in case we 
want to remind ourselves exactly what we're doing. It's always good practice to add 
comments to your scripts so that when you come back to them later, you know what's going on.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ 103. comments with slash slash or slash, asterisk (70) ~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image103.png?raw=true"
  width="50%"
  alt="Make Comments with two slashes or with slash, asterisk." />
</p>

<p>There are two ways of making comments in JavaScript. I can use the slash twice, two 
slashes, and I can type the variable is below, something like that, or the variable 
below, I don't know we could say something else about it. But putting two slashes //, 
two forward slashes here, will keep JavaScript from trying to do anything with this 
line here. If you want to have a longer comment, you can use the slash and a star /* 
and then end comment with a star and a slash */. And then I can put a longer comment 
about anything that I want and it can go multiple lines. See example in image.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 104. make code larger with shift + (71) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image104.png?raw=true"
  width="50%"
  alt="Make code larger with shift +." />
</p>

<p>While we're here, another thing that's important is I can actually make the code in the 
browser larger or smaller by pressing the Cmd plus or Ctrl plus in Windows on my keyboard 
here, let's click on that. And that will make the code larger or smaller. And I can make 
this window over here smaller too if the code is getting squished in there, you can close 
it all together. This thing opens and closes that Explorer. But I can make the code 
larger or smaller. And depending on how good your eyes are, you might want the code to be 
larger or smaller, Cmd+0 will put it at its default size, but command minus will make it 
smaller. So make sure you're setting your code to a size that's comfortable for you to read.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-03">2.03 Visual Studio – Part 3 (9:48)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 105. visual studio - part 3 (2.03) (72) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image105.png?raw=true"
  width="40%"
  alt="2.03. Visual Studio - Part 3." />
</p>

<p>The next thing to talk about is folders and working with folders for projects.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 106. myfile.html (72) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image106.png?raw=true"
  width="50%"
  alt="myfile.html." />
</p>

<p>This file, myfile.html, this file here is just sitting on my desktop. That's fine for a 
single file, but usually, if I'm working on a project, I'm going to have a folder with a 
bunch of related files. I might have an HTML file. I might have a CSS file, I might have 
multiple JavaScript files as we get going here. But for right now this is just a single 
file. That's not really very useful by itself.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 107/108. make folder and file (73) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image107.png?raw=true"
  width="45%"
  alt="Make a folder." />
<img src="./images/image108.png?raw=true"
  width="45%"
  alt="Make a file." />
</p>

<p>Over here I'm going to make a folder, and I'm going to give the folder a name, myProject. 
Notice there are no spaces in that folder name. Also all the letters or lowercase. It doesn't 
have to be, so myProject. Then over here, close this file, and open up the sidebar here, 
and no folder opened. I can actually open that folder, myProject.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 109. visual studio welcome menu (73) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image109.png?raw=true"
  width="50%"
  alt="Visual Studio welcome menu." />
</p>

<p>Now you can see I've got my welcome screen again and I've got MYPROJECT here. There's 
no files in this folder currently. I just made a folder and it's empty, but I can put 
a file in that folder and close that welcome screen.</p>

<p>If I make a new file, suppose I make a file and call it index.html. That's going to be 
an HTML file. I can put that in my folder.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 110. myfolder and index.hmtl (74) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image110.png?raw=true"
  width="50%"
  alt="Myfolder and index.html." />
</p>
 
<p>Now you'll notice it's created the index file. Not only that, but if I look in 
myProject folder over here, you can see that index.html has been created in that 
folder. I can manage my whole project from here.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 111. blank index.html (74) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image111.png?raw=true"
  width="50%"
  alt="." />
</p>

<p>Perhaps I have another file in here. I'm going to have styles.css. Maybe that's going 
to have some styles for my webpage, and it's going to go into that file.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 112. files in myproject (75) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image112.png?raw=true"
  width="50%"
  alt="Files in myProject." />
</p>
<p>Now that file is in the folder over here. In this way, I can control and keep track 
of all the files for myProject and they're all in one place. Remember I said earlier, 
you have to get really good at file management and you have to make sure that all the 
files for a project stay in the folder. You might have other folders in the folder.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 113. empty visual studio screen (75) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image113.png?raw=true"
  width="50%"
  alt="Empty visual studio screen." />
</p>

<p>If I come back here, I might make a folder for images. Now this is a folder, and currently 
there's nothing in the folder, but if I look in this folder over here, you can see that the 
folder images is here, and I can put images in there. Be careful when you're creating files, 
not to accidentally put the file inside the folder if you don't mean to. If I click "New File" 
here, it's going to create this file inside of Images, oops.html. This file is actually inside 
the Images folder here, and I can see it over here as well. If I decide I don't want that file, 
I can right-click here and choose "Delete". It will ask me, do I really want to move it to the 
trash? and sure enough, from over here, that file is now not inside that folder and folder is 
empty again. By working with this Explorer, we can create files and manage files for our 
projects and make sure that the files are in the correct places at all times.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~ 114. empty visual studio menu screen, again (76) ~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image114.png?raw=true"
  width="50%"
  alt="Describe how Visual Studio is customizable." />
</p>

<p>The last new thing that I have for this lesson is I just want to show you that Visual 
Studio Code is very customizable. You can add all extensions to it. If I click on this 
Gear icon down here, I can get into the Settings. I can do all things in here with 
extensions and other things.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 115. visual studio extensions and settings (76) ~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image115.png?raw=true"
  width="50%"
  alt="Visual Studio extensions and settings." />
</p>

<p>For example, you can search for Settings or Extensions. You can do all fun things 
to make Visual Studio Code more personalized. Maybe you like this black look for 
your code editor, or perhaps you prefer a lighter theme.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 116/117. atom one light theme (77) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image116.png?raw=true"
  width="45%"
  alt="Atom One Light Theme, #1." />
<img src="./images/image117.png?raw=true"
  width="45%"
  alt="Atom One Light Theme, #2." />
</p>

<p>I installed this Extension here called Atom One Light Theme. You can click on that, 
and currently it's disabled, but I can enable this theme.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 118. color theme editor (77) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image118.png?raw=true"
  width="50%"
  alt="Color Theme Editor." />
</p>
<p>Select Color Theme. There we go. Here I've got the Color Themes and I can select 
that. Sometimes you have to mess around with Extensions in the Theme Editor, in the 
Settings to really figure it out. There's all themes that you can get for Visual 
Studio Code to customize it and make it look the way you want it to look. I go back 
to my files and here I am.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 119. new menu screen theme (78) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image119.png?raw=true"
  width="50%"
  alt="Display new menu screen theme in Visual Studio." />
</p>

<p>Now you'll notice that my files will look a little bit different because I'm using 
the Atom one light theme. Just to remember here, we've done quite a lot to make this 
page. You can see here I am in myProject again for my Index file. I come over here 
and click.</p>
 <!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 120. type exclamation, then tab (78) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image120.png?raw=true"
  width="50%"
  alt="For html template, type exclamation followed by [tab]." />
</p>

<p>Just to review what we did in this lesson, I can type an exclamation point press 
tab (![tab]) to get the basic structure of a page. I can add a title for my document 
that will show up on my page. I can add some HTML. I'm just going to add an h1. Here 
is a heading. Then I can add some script tags, and I can add a script to my page. I 
could do something like var myVariable and set it to "hello". Then I could cancel 
logout console.log myVariable. Notice it pops up here. I can even just press carriage 
return, don't even have to type the whole thing. I can just press return to get it to 
pop that in place so I make sure I don't spell it wrong. Then a semicolon. Semicolons 
are used in JavaScript at the ends of statements. I can save that file, and then I 
can come back to the browser and test it.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 121. test, here is a heading (79) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image121.png?raw=true"
  width="50%"
  alt="Test, myProject, here is a heading." />
</p>

<p>Let's do that real quick. Comeback here to Chrome. This is the other file. I'm going 
to open this file. I could do Command All, there we go myProject index, and there it 
is. It's doing Hello there. The Hello came up in the Console lock there. That's a 
review of everything we learned in this lesson. Your now able to work with files 
and get those files to output content into the console that you can then test in 
your browser. That's a great way of working.</p>

<p>Another way of opening your file is to right-click on the file and choose "Open 
With" and I want to open with the browser, you could even try a different browser. 
Brave is a great browser to try. Brave is using the same rendering engine as Chrome. 
It actually works the same way as Chrome generally. What's interesting about Brave is 
that the CEO of Brave is actually that Brendan Eich guy who invented JavaScript. It's 
interesting to note that the guy invented Java Script is now in the business of 
creating a browser. That's interesting. Great. This will get you started and I look 
forward to seeing you in the next lesson where we can start writing some interesting 
scripts.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-04">2.04 Operators, Booleans & Selection in JavaScript (8:11)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~ 122. operators, booleans & selection in javascript (2.04) (80) ~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image122.png?raw=true"
  width="40%"
  alt="2.04. Operators, Booleans & Selection in JavaScript." />
</p>

<p>Operators, Booleans and Selection in JavaScript.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 123. javascript operators (80) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image123.png?raw=true"
  width="50%"
  alt="JavaScript Operators." />
</p>

<p>Operators in JavaScript are the symbols that will allow us to create different 
expressions in JavaScript. And here are just a few of them. We've already seen the 
plus sign and the equal sign, which remember, equals is an assignment operator. 
There's also minus and the asterisk is used to multiply and forward slashes used 
to divide and the percent is a modules operator.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~ 124/125. comparison operators/bitwise operators (81) ~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image124.png?raw=true"
  width="45%"
  alt="Comparison operators." />
<img src="./images/image125.png?raw=true"
  width="45%"
  alt="Bitwise operators." />
</p>

<p>If you want to find out more about operators you can come over to the W3schools.com 
website and look at the different operators though. Get all listed here comparison 
operators, logical operators, all kinds of stuff here. So you can come through and 
find all the details about all of the different operators if you want to there. But 
we're just going to start with a few of them so it's not too overwhelming and most 
of the operators are very similar to what you would find in other C-based programming 
languages. C, C++, C sharp, Objective C, and so forth.<p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 126. booleans in javascript (81) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image126.png?raw=true"
  width="50%"
  alt="Booleans in JavaScript." />
</p>

<p>Okay, so there's also Booleans in JavaScript. And it's very nice to know that a 
Boolean can have two values true or false. And that's it. So here I'm making a 
variable called happy. And I've set I've assigned it the value of true. Notice 
that true is not inside quotes. JavaScript knows what true means true is a key 
word that means that something is true. And false is a key word that means that 
something is false.</p>

<p>So I have a variable here sad, that's false. I can use an if statement to check 
to see if something is true. So if happy, now happy has assigned true to it, so 
it's going to do something here. If I were to replace happy with sad. Then the else 
would fire it instead of they have and we would do something down here if happy was 
false. Or if I change the value here from true to false, then happy would be false. 
And it would do this down here. So that gets us started with a little bit of that.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 127. vs code editor customize (82) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image127.png?raw=true"
  width="50%"
  alt="Customize the Visual Studio editor theme." />
</p>

<p>So next we're going to move to our code editor and make a file and try working with 
some selections and Booleans and that kind of fun stuff.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 128. vs code editor, make file (82) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image128.png?raw=true"
  width="50%"
  alt="Make a file in Visual Studio editor; selections.html." />
</p>

<p>Here I am in my code editor, and I'm going to make a new file. And I'm going to make 
a file and before I do anything, I'm going to save the file. Save an image, just save 
it on the desktop, and I'm going to call it selections.html. Notice all lowercase no 
spaces in the dot html extension. I'm going to save that on the desktop.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 129. exclamation/tab for basic structure (83) ~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image129.png?raw=true"
  width="50%"
  alt="Type exclamation [tab] for basic html structure." />
</p>

<p>Exclamation point will allow me to press tab, which gives me kind of my basic 
structure for an HTML page. And then I'm going to type in here. Testing selections 
and there we go. And then in here I'm just going to add an h1 testing selections.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 130. add script & two variables (83) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image130.png?raw=true"
  width="50%"
  alt="Add script and two variables." />
</p>

<p>Now, I'm going to add a script tag. So we'll go ahead and add a script in here. And 
then what are we going to put in the script? Well, let's make some bullets I'm going 
to have Var red and I'm going to set that to value true. Then we have var blue and 
I'm going to set that to value of false. There we go. So I've got two values here. 
One is set to true and the other one is set to false.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 131. if red, then do something (84) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image131.png?raw=true"
  width="50%"
  alt="If red, then do statement in function." />
</p>

<p>Now if I were to make an if statement if parentheses, and I were to check the value 
of those red. I'm going to check the value of red. If red is true, which is it is, 
then something's going to happen here. Red is going to evaluate to true because I 
have true assigned to the red variable here. If I were to put blue in here, then 
this would not be true, in which case something else would happen.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 132. add else statement for false (84) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image132.png?raw=true"
  width="50%"
  alt="Add an else statement for false." />
</p>

<p>I'm going to come down here and add else, which is exectued when false. Therefore,
console.log states false.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 133. test, inspect console boolean (85) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image133.png?raw=true"
  width="50%"
  alt="Test, inspect console boolean." />
</p>

<p>Now we can try this out and come over here to our browser. I'm going to make a new 
tab here and open this file selections. Open, and I've got my testing selections. If I 
right click and choose inspect, I can go to the console and sure enough, the statement 
is true.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 134. if blue (false) else statement (85) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image134.png?raw=true"
  width="50%"
  alt="Add else statement." />
</p>

<p>I'm going to come down here and add else is executed when false. Therefore, 
console.log states false.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ 135/136. testing selections; red=true, blue=false (86) ~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image135.png?raw=true"
  width="45%"
  alt="Testing Selections; new vars; red=true, blue=false." />
<img src="./images/image136.png?raw=true"
  width="45%"
  alt="Testing Selections; new vars; red=true, blue=false." />
</p>

<p>Usually you'll see more like this, I just add the extra space in there just to make it a little bit easier to read and a little bit easier to evaluate. So red is either blue false or true. And blue is either false or true because I've used these Boolean 's here.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-05">2.05 Try This! (3:10)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 137. try this! (2.05) (86) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image137.png?raw=true"
  width="40%"
  alt="2.05. Try This!" />
</p>

<p>This is interesting. Let&apos;s try this.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 138/139. types of boolean = false (87) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image138.png?raw=true"
  width="45%"
  alt="Test, null is false, undefined is false, zero & false are also false." />
<img src="./images/image139.png?raw=true"
  width="45%"
  alt="Undefined, zero, null, and false are all false." />
</p>

<p>I&apos;m going to make a variable called green and then see what happens if
I pass green in here. Notice green doesn&apos;t have a value here. So let&apos;s
take a look at that. I&apos;m going to make a variable green, and just put a
semicolon. And then down here, I&apos;m going to test green. Is green true
or false? What do you think? This can happen here.</p>

<p>Let&apos;s test that. The statement is <b>false</b>. This is an important thing to 
understand about JavaScript. Green is essentially undefined. It&apos;s an undefined 
variable. Undefined resolves to false in JavaScript. JavaScript has a concept of truthy 
and falsy. So things are either true ish or false ish. And they could be explicitly true 
or false like red and blue out here, but they could false ish. And JavaScript treats 
variables that are undefined as false.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~ 140/141. green = null, green = 0 are both false (87) ~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image140.png?raw=true"
  width="45%"
  alt="var green = null, equates to false. " />
<img src="./images/image141.png?raw=true"
  width="45%"
  alt="var green = 0, equates to false." />
</p>

<p>Also, green equals null, that would be false. So that comes up false.
Green equals 0, 0 is false. But if I put any other number in there
except 0, any other real number like a 1. 1 is true. What about 100?
That&apos;ll be true too. What about minus 100? That&apos;s true as well.</p>

<p>So, numbers are true except for zero, zero is <b>falsy</b>. It&apos;s false
ish. So, zero comes up as false, which is kind of an interesting thing.
So things that we know are false or <b>undefined</b> is false, <b>null</b> is
false, <b>zero</b> is false. <b>False</b> is false. Other things are true.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 142/143. green = "cheese" is true (88) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image142.png?raw=true"
  width="45%"
  alt="var green = 'cheese' is true. " />
<img src="./images/image143.png?raw=true"
  width="45%"
  alt="Test, var green = 'cheese' is true." />
</p>

<p>But if I put Cheese Cheese is true. So that&apos;s an interesting thing
about JavaScript.</p>

<h2 id="ch2-06">2.06 Comparing Values (8:16)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 144. comparing values (2.06) (88) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image144.png?raw=true"
  width="40%"
  alt="2.06. Comparing Values." />
</p>

<p>Let&apos;s look at comparing values.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 145. double equal comparison (89) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image145.png?raw=true"
  width="50%"
  alt="Comparison with double equal sign." />
</p>

<p>This is something we&apos;ll do a lot in JavaScript. We often want to find
out if the value here is the same as the value somewhere else.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 146. test, mynum to othernum (89) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image146.png?raw=true"
  width="50%"
  alt="Test, myNum == otherNum." />
</p>

<p>I&apos;m going to go back and leave green here is undefined, like so. Then
I&apos;m going to make a new variable, var myNum and assign it the value
five and var otherNum and assign it value of five. Then down here I can
check to see if myNum is the same as equals otherNum. It&apos;s really
important to read this as the same as. This is assigns, five is assigned
to otherNum and five is assigned to myNum. But here what I&apos;m checking
to see is myNum the same as the otherNum. In this case it is.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 147. does mynum equal othernum? true (90) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image147.png?raw=true"
  width="50%"
  alt="Test, myNum == otherNum is true." />
</p>

<p>So if I save this and test this, you&apos;ll see the statement is true
because myNum is the same as the otherNum.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~ 148/149. change number, now statement is false (90) ~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image148.png?raw=true"
  width="45%"
  alt="Change to 6.  Now one is 5, other is 6." />
<img src="./images/image149.png?raw=true"
  width="45%"
  alt="Test, statement is now false." />
</p>

<p>If I change this to a different number, then I&apos;m obviously going to get
false. That&apos;s not true. So the statement is false, they&apos;re not the
same as.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 150/151. test, exclamation equal for false (91) ~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image150.png?raw=true"
  width="45%"
  alt="Use exclamation and equal for NOT." />
<img src="./images/image151.png?raw=true"
  width="45%"
  alt="Test, not equal with exclamation + equal sign." />
</p>

<p>Instead of equals equals, I could use exclamation point equals. That
will be not the same answer. Is that true? Is <b>myNum</b> not the same as
<b>otherNum</b>? Yes, that&apos;s true. We can also check for greater than or
less than so we could say, is <b>myNum</b> less than my <b>otherNum</b>? That
should be true because <b>myNum</b> is less than the <b>otherNum</b>, let&apos;s
see, and that statement is true. I could try is it greater than. Is
<b>myNum</b> greater than the <b>otherNum</b>. Is that true? That&apos;s not going
to be true because five is not greater than six. But we can test for
these different kinds of scenarios, <b>myNum</b> and <b>otherNum</b>. We can
use less than and greater than and check to see if that&apos;s true.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 152/153. more testing of not equal & false (91) ~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image152.png?raw=true"
  width="45%"
  alt="More test of not equal and false." />
<img src="./images/image153.png?raw=true"
  width="45%"
  alt="Test, not equal as false." />
</p>

<p>We're going to try a little mix. var <b>notNum</b> equals five. So this
five is a string with the number five in it. Now can I check to see if
<b>myNum</b> is the same as <b>notNum</b>? Do you think I&apos;m going to get
there if I save that and try that? The statement is true. Well, that&apos;s
interesting. How can a five be the same as five inside quotes?</p>

<p>Remember, JavaScript is loosely typed and it allows for something called type
<b>coercion</b>. What&apos;s going on here is that JavaScript is saying we&apos;ve
got a five here and we&apos;ve got a five in a string and they&apos;re basically
the same, so I&apos;m going to call that true. So that&apos;s <b>truthy</b>. It&apos;s
truish. You can think of it that way, which is very interesting. Now,
again, this is the kind of thing that can drive programmers crazy
because you could end up making a mistake in your programming or having
something unexpected happening. You don&apos;t want unexpected things to
happen in your programs, that&apos;s never a good thing.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 154/155. triple equal testing (92) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image154.png?raw=true"
  width="45%"
  alt="Triple equal testing." />
<img src="./images/image155.png?raw=true"
  width="45%"
  alt="Must be exactly the same to match as true." />
</p>

<p>I believe it was ES5 in 2009, they introduced the triple equals
operator, which is exactly the same as and that won&apos;t do type
<b>coercion</b>. Remember, this is the kind of thing that we&apos;re working
with in JavaScript. They don&apos;t want to just get rid of the
double-equals or change what it does because that would break other
programs. That will break programs that have been happening in the past.
But they can add another operator which is the triple equals and that
one will not do type coercion. So you&apos;ll notice this one will come up
false. That statement is false because it won&apos;t do the type
<b>coercion</b>.</p>

<p>There is also the same thing with the exclamation point so you can say
that&apos;s not exactly the same as. You can read this as is <b>myNum</b>
exactly the same as <b>notNum</b> and the answer is no. Generally, it&apos;s
considered better programming to use the triple equals sign everywhere.
Often in our shorter scripts, it doesn&apos;t really matter and you&apos;ll see
me equals equals over time. But really if you want to get into really
good habits, always use the triple equals sign so that you don&apos;t ever
have any type <b>coercion</b> unless you really want it for some reason.
Again, this is an odd thing about JavaScript that you can do this.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 156. explain undefined variables (93) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image156.png?raw=true"
  width="50%"
  alt="Explain undefined or null variables as false." />
</p>

<p>One more thing I want to check out here really quickly while we&apos;re
here, I&apos;m going to change this five to something like chicken and then
I&apos;m going to make a new variable, var <b>myValue</b> equals <b>notNum</b>
minus <b>myNum</b>. I&apos;m going to take chicken and subtract five. That
doesn&apos;t make any sense. What happens if I put my value in here? You
probably won&apos;t be surprised to see that that comes up <b>false</b>.
That&apos;s <b>false</b>.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 157/158. test, not a number is false (93) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image157.png?raw=true"
  width="45%"
  alt="Test, if not a number then statement is false." />
<img src="./images/image158.png?raw=true"
  width="45%"
  alt="Test, not a number (NaN) is false." />
</p>

<p>More than, if I come down here and just console.log my value, just to
see what&apos;s actually in that my value when I try to take a chicken and
subtract five from it, what do I get over here? Num not a number,
<b>NaN</b>. Num is another thing in JavaScript that is falsy. So in our
list of things that are false are zero, false, undefined, null and not a
number (<b>NaN</b>). Those things all come up false in JavaScript and
that&apos;s an important thing to keep in mind as we move forward with
working with JavaScript and working with Booleans, and when we&apos;re
testing values.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-07">2.07 Else If (5:56)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 159. else if (94) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image159.png?raw=true"
  width="40%"
  alt="2.07. Else If." />
</p>

<p>JavaScript has an Else If.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 160. else if examples (94) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image160.png?raw=true"
  width="50%"
  alt="Examples of Else If." />
</p>

<p>We can run through a series of selection checkers to see which one is
true. Practice this stuff as much as you can and get used to the syntax.
By just writing the stuff and making mistakes and forgetting to put in
the semicolon and the curly braces or the square brackets and seeing
what happens when you get in here. Let's type this in.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 161/162. example of else if with test (95) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image161.png?raw=true"
  width="45%"
  alt="Example else if." />
<img src="./images/image162.png?raw=true"
  width="45%"
  alt="Test, example else if." />
</p>

<p>I&apos;m going to come back here and I&apos;m going to add, <b>Windows Alt Shift
A</b>. And that will comment that. It&apos;ll put a comment around something
that I&apos;ve selected. Down here I&apos;m going to make a variable for colors
equals square bracket, quote, red. Green Blue Yellow I&apos;m going to make
a variable var selected color Equals colors, square bracket and we&apos;ll
do three. Red is zero, one, two, three. Now, over here, so I&apos;ve got
that, and that&apos;s great. Now I can do an if else statement. So I could
do if, selected color is the same as equals red or yeah, let&apos;s do red.
Red in quotes, red. If it&apos;s the same as red, then I can console log
something out console dot log. The color is red.</p>
<p>Now I can do an else
if. And again I can put else if on this line here like so. I think it&apos;s
a little bit easier to read if you move it down like this else if
selected colour in here I&apos;m going to cheat by copying and pasting. Else
if selected colour is blue. And again, I&apos;m just adding these extra
spaces because I think it&apos;s a little bit easier to read. But it&apos;s not
really common practice but that&apos;s okay. If the selected colour is blue,
then I&apos;m going to console log out. Blue actually should do green, green
snacks, it doesn&apos;t matter. I can go whichever order I want. In this
I&apos;m just going to go to read because that sort of makes sense and then
I can copy and paste the else if. Select the colour is change this one
to blue, and if it&apos;s not red, green or blue, then it must be yellow.
Okay, great. So with this script in place, we can test this.</p>

<p>We come over here and refresh this and you can see the color is yellow
it went through that list of items and chose the correct color. Whereas,
if I come up here and change this to a one to zero one and this. You can
see I get the color is green. Now, what happens if I make a mistake?
Suppose I put four, zero, one, two, three, oops, there&apos;s no four.
Let&apos;s see what I get over here. You&apos;re going to get mistakes. You&apos;re
going to have errors and this said, the color is yellow because the else
ran. Which is not really what I wanted. But it is sort of doing that
kind of thing or let&apos;s see what happens if we do what happens if I make
a mistake and I forget to put commas in here.</p>

<p>This is a common mistake
that I see from students is they&apos;ll forget to put the commas in the
array, what happens if I do that? Uncaught Syntax Error: Unexpected
string on line 29. So that gives you a notion that you should come back
and take a look at line 29 and see what&apos;s going on in there. And
hopefully, with this stuff in here this little red underline stuff going
on here. You&apos;ll see that something&apos;s wrong there, and you&apos;ll put the
comments back in very common mistake. When we&apos;re starting with this
thing, okay, so you can try these different, try these different scripts
and see how they work and what they do. It&apos;s really helpful to do that.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-08">2.08 Switch Statements (5:06)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 163. switch statements (2.08) (96) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image163.png?raw=true"
  width="40%"
  alt="2.08. Switch Statements." />
</p>

<p>JavaScript also has a switch statement which will take a value like
selected color and run it through a bunch of cases.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 164. switch statement with examples (96) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image164.png?raw=true"
  width="50%"
  alt="Switch statement Examples." />
</p>

<p>In case it&apos;s red, it&apos;ll do this, in case it&apos;s blue, it&apos;ll do that,
in case it&apos;s green, it&apos;ll do that, and then at the bottom there&apos;s a
default, you can add a default and it&apos;ll do this if none of these other
ones are true. It&apos;s important with selection that you add this break in
here as well. The break will bump out of this switch when one of these
true statements comes up.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~ 165/166. example, switch and case statement (97) ~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image165.png?raw=true"
  width="45%"
  alt="Example, switch/case statements." />
<img src="./images/image166.png?raw=true"
  width="45%"
  alt="Example, switch/case statements." />
</p>

<p>Let&apos;s take a look at this really quickly and see what we get over here.
I&apos;m going to go in here, I&apos;m going to comment out these if-else
statements. Again, I&apos;m going to &quot;Select&quot; them and then do &quot;Option&quot;
or &quot;Alt Shift&quot; A in Visual Studio Code to quickly just comment this
out, so I&apos;m not running that anymore. Then down here, we can run a
switch statement, switch parentheses and I&apos;m going to put in here the
value in checking its selected color. Then the switch statement, I&apos;m
just going to paste it in here because it&apos;s a little bit tedious to
watch me type it all. But I&apos;m going to paste it in here, but I
recommend that you type it.</p>
<p>Type out, case, red:console.log. The color
is red and then a semicolon, so that&apos;s the statement that is going to
run and then break and it can be on the same line on the slide I have it
on the next line, but you can put it on the same line here, rather than
watch me type all of these, I&apos;m going to just paste them in here. But
you should type it in because learning the syntax, you&apos;ll learn it by
typing it, not by watching me do it. Go ahead and make these files and
type these in here so we can test it out. Then notice I&apos;ve got red,
green, blue, and yellow, and up here, if I set select the color to
three, I should get 0,1, 2, 3, I should get yellow. Let&apos;s see if I get
that if I come over here and test this. Ensure enough the color is
yellow, that&apos;s coming up great.</p>

<p>I could change the <b>selectedColor&lbrack;0&rbrack;</b> to zero, which will get me the
first one. Now I&apos;ve got red and that break is bumping me out of there.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 167. test, there was an error (98) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image167.png?raw=true"
  width="50%"
  alt="Test, there was an error.  If outside of array, then gives error." />
</p>

<p>But if I were to set it to something past the end of my array, so 0, 1,
2, 3, if I set it to have four, the default will run and I get there was
an error because I&apos;m outside of my array, so the default option ran
down here.</p>

<p>Sometimes say &quot;I&apos;m forgetting a semi-colon, &quot; will really set it off
as well. Unexpected token break and line 47. These syntax error,
unexpected token, what does that mean? It&apos;s really expecting a
semicolon token here and it seemed break instead, so it&apos;s confused by
that. But these syntax errors, these error messages are sometimes a
little bit cryptic and they take a little time to get used to them. But
the switch statement is a great alternative for the else, if and it
takes up less space and it can help you be very concise and specific
with your code in a way that&apos;s helpful and useful.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-09">2.09 Using &amp;&amp; (6:24)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 168. using &amp; &amp; (98) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image168.png?raw=true"
  width="40%"
  alt="2.09. Using &amp;&amp;." />
</p>

<p>In JavaScript, we can check to see if multiple things are true by using
the ampersand operator, or the pipe operator.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 169. examples, using &amp;&amp; (99) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image169.png?raw=true"
  width="50%"
  alt="Examples, using &amp;&amp;." />
</p>

<p>We&apos;ll look at the pipe operator next, but here we&apos;re using the
ampersand operator, and we use two of them together here.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 170. example, booleans with &amp;&amp; (99) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image170.png?raw=true"
  width="50%"
  alt="Example, boolean with &amp;&amp;." />
</p>

<p>And what we do is, we check to see if this statement is true, and if
this statement is true. And for this whole thing to be true, when you
use the AND operator, both of these must be true in order for this to
run. So I have to be in a good mood and have gotten sleep, in order for
today to be a good day. If either one of these is false, then I&apos;m going
to be grumpy.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 171. test, booleans with &amp;&amp; (100) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image171.png?raw=true"
  width="50%"
  alt="Test, booleans with &amp;&amp;." />
</p>

<p>Let&apos;s just test this one really quickly, because I think it&apos;s just a
good idea to practice typing these.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~ 172/173. more test, booleans with &amp;&amp; (100) ~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image172.png?raw=true"
  width="45%"
  alt="More test, booleans with &amp;&amp;." />
<img src="./images/image173.png?raw=true"
  width="45%"
  alt="More test, booleans with &amp;&amp;." />
</p>

<p>Next, I&apos;m going to come in here, I&apos;m going to turn this one off.
Again, Option or Alt+Shift+A comments it out. And then I&apos;m going to do
var goodMood, and set that to true, var gotSleep, and set that to true.
And then I&apos;m going to say if, whoops, if(goodMood && gotSleep), if both
of those are true, then I can console.log, Today is a good day, else,
console.log(&quot;I am grumpy!&quot;).</p>
<p>Now, we can test this, and we can see that
because both of these are set to true, the if statement is going to run.
Today is a good day. However, if I were to go in and change it so that
one of these was false, it doesn&apos;t matter which one, then this whole
statement will come back false. And I&apos;m grumpy, so that&apos;s kind of an
important tool in our tool kit, is we can check to see if two things are
true. If two things are true, then we can do something. If either one of
them is false, then something else is going to have to happen.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 174. booleans with double pipe (or) (101) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image174.png?raw=true"
  width="50%"
  alt="." />
</p>

<p>Now, we can also use the double pipe. The pipe is the key on the
American keyboard above the Return key, Shift, and that key up there.
It&apos;s also got the backslash on it. The pipe is an OR statement. So
here, <b>gotBreakfast</b> is true, <b>gotLunch</b> is true, but <b>gotDinner</b>
is false. But if any one of these is true, then the if statement rings
as true. So they would all have to be false for me to be starving.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 175. add boolean and double pipe example (101) ~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image175.png?raw=true"
  width="50%"
  alt="Add boolean and double pipe example." />
</p>

<p>var <b>gotBreakfast</b> =
true, var <b>gotLunch</b> = true, var <b>gotDinner</b> = false.
<b>If(gotBreakfast &vert;&vert; gotLunch &vert;&vert; gotDinner)</b>, if any of those is
true, then <b>console.log(&quot;things are ok!&quot;</b>). Then down here, else
<b>console.log(&quot;I am STARVING&quot;)</b>.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~ 176. 1 or more false, therefore things are ok (102) ~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image176.png?raw=true"
  width="50%"
  alt="One or more variables are false, therefore things are ok." />
</p>

<p>And there we go, so I can test this over here. And you could see, things
are ok, even though one of those would be false. I would have to make
all of these false, to be starving, and there we go.</p>

<p>You&apos;ve learned about Booleans in this lesson, what&apos;s true and what&apos;s
false. And that some things are <b>true-ish</b>, and some things are
<b>false-ish</b>, or <b>falsy</b> and <b>truthy</b>. <b>0</b> is considered false in
JavaScript, or <b>undefined</b>, or <b>null</b>, or <b>not a number</b> (<b>NaN</b>)
is false. These are all considered false in JavaScript.</p>
<p>And you&apos;ve already learned a lot of the basics of JavaScript, and we&apos;re going to
keep going with these basics.</p>

<p>And I know that these scripts don&apos;t seem
particularly interesting yet. But I promise, if you hang in there and
keep working on this, then we will start making some interesting things
pretty quickly. And we&apos;ll start manipulating content on web pages,
doing all kinds of interesting stuff, so hang in there, keep going. And
if you haven&apos;t had breakfast, lunch, or dinner, you&apos;re probably
starving, so you should go eat something.</p>

<ul>
  <li id="ch2-09-oper"><a href="https://www.w3schools.com/js/js_operators.asp">
    2.09.JavaScript Operators (shortcut)</a></li>
  <li id="ch2-09-bool><a href="https://www.w3schools.com/js/js_booleans.asp">
    2.09.JavaScript Booleans (shortcut)</a></li>
</ul>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-10">2.10 Loops (6:23)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 177. loops (2.10) (104) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image177.png?raw=true"
  width="40%"
  alt="2.10. Loops." />

<p>Loops in JavaScript.</p>

<p>We&apos;ve already done quite a bit of JavaScript already. We&apos;ve looked at
variables and we&apos;ve looked at arrays, and we&apos;ve looked at how to use
selections to choose if something is true or not, Booleans. The next
piece of the puzzle is <b><i>loops</i></b>. Frequently, you need to iterate through a
number of values and do something with them when you&apos;re programming.
And JavaScript, like many programming languages, will allow you to do
<b><i>loops</i></b>.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 178. for loop (104) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image178.png?raw=true"
  width="50%"
  alt="For loop." />
</p>

<p>The most basic <b><i>loop</i></b> is a <b><i>for loop</i></b>. And you&apos;ll see here 
that in the for <b><i>loop</i></b>, we start out with an initialized value. And then we check if the
value is less than some number. And then each time through the <b><i>loop</i></b>, we
increment that value. The best way to explore this is to actually try it
out. So I recommend opening up your code editor and following along with
me.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~ 179/180. loops.html - add incrementor to loop (105) ~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image179.png?raw=true"
  width="45%"
  alt="Create loops.html and add incrementor." />
<img src="./images/image180.png?raw=true"
  width="45%"
  alt="Create a loop with incrementor." />
</p>

<p>Here, I have just a file called loop study HTML saved on my desktop, and
I&apos;m going to add a loop in this script down here. There we go, and I&apos;m
going to add a for loop. I&apos;m going to make a variable var i. And i can
be anything. It could be X, it could be Y, it could be J, it could be
the word counter. It&apos;s just a variable. i is fairly common to use
because it can stand for <b>incrementer</b>. I don&apos;t know, it&apos;s a fairly
common one to use but it doesn&apos;t have to be that it could be something
else if you want. But I&apos;m going to start i at 0. And then I&apos;m going to
check while i is less than, say 10. And then each time through the loop,
I&apos;m going to increment i, i++. i++ is a shortcut for i = i+1 one, like
so. So we could take i, add 1 to it and then assign it back to i. So if
i starts at 0, the next time to the loop will take 0, add one to it,
which gives us 1 and assign it back to i. So now i is 1 and then the
next into the loop will take 1, add 1 to it, assign it back to i so now
it&apos;s 2, so on and so forth. But a shortcut for that is i++. That&apos;s
called an <b>incrementer</b>. And then here we have, let&apos;s just do
<b>console.log(i).</b></p>

<p>And so what this is going to do is we&apos;re going to set i to 0. The
console log will run. And it will say, it&apos;ll give us a 0. And then we
come back and we increment i. So that we take 0 and we add 1 to it. So
now it&apos;s 1. Is 1 less than 10? Yes, it is. Since 1 is less than 10, it
will <b>console.log(i)</b> again, which is now 1, and then it&apos;ll increment
1 again. So i will go from 1 to 2 and then is 2 less than 10? Yes it is.
So we&apos;ll console log out a 2. And then we&apos;ll increment i again, we&apos;ll
take 2 and we&apos;ll increment it to 3. Is 3 less than 10? Yes it is.
We&apos;ll console log out a 3, and so on and so forth until we get to 9. We
get to 9, we&apos;ll console log out the 9 and then i gets incremented to
10. Is 10 less than 10? No, it&apos;s not. So then the loop will stop and
we&apos;ll bust out of the loop at that point. But let&apos;s give this a try.
I&apos;m going to save this. And then I&apos;m going to go to the browser, okay,
I have over here.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 181. test, incrementor loop (106) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image181.png?raw=true"
  width="50%"
  alt="Test, incrementor loop." />
</p>

<p>And I have this file loaded here. And I can just run it and you&apos;ll see
that my loop ran. Line 13 ran ten times starting with 0, 0 through 9.</p>

<p>Now, I don&apos;t have to start with 0. If I wanted to go from if I wanted
to count from 1 to 10, I could start with 1. I could even say, well, I
want it to be less than or equal to 10. So then that&apos;ll actually work
as well.</p>

<p>You also don&apos;t have to start i at 1 or 0, you can start out anywhere.
If I wanted to, I could start at 37 and go till I&apos;m at 63. I want to
i++. And then if I go back and do that, you&apos;ll see that the loop we&apos;ll
do those numbers. So, there are a lot of different ways of creating
loops in JavaScript and we&apos;ll be looking at a few different methods
throughout this course. But the for loop with these three expressions is
really your most basic loop. And as we go through the loop, we evaluate
these expressions and that determines whether the loop runs or not.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-11">2.11 Working with Arrays (4:13)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 182. working with arrays (2.11) (107) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image182.png?raw=true"
  width="40%"
  alt="2.11. Working with Arrays." />
</p>

<p>One of the places you&apos;re very likely to come across using loops is if
you have an array of items, you have a group of items and you need to
iterate over that group of items to do something to them.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 183. example, working with arrays (107) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image183.png?raw=true"
  width="50%"
  alt="Examples, working with arrays." />
</p>

<p>Let&apos;s take a look at what that looks like. Here I have a variable
called <b>colors</b>, which is an array. It&apos;s got red, blue, yellow, and
green in it. I&apos;m going to loop through each of the colors in the array.
If you&apos;re wondering with this + &apos;/n&apos; is that&apos;s to create a new line
in the console. Actually I don&apos;t really need to do that because in fact
the console creates new line for each call anyway. I shouldn&apos;t have put
this on my slide here, but I forgot to take it off but you can just
ignore it. We can just do it without that, and it&apos;ll work just fine.
Remember, arrays are zero-indexed.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 184. add array with colors (108) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image184.png?raw=true"
  width="50%"
  alt="Create an array of colors." />
</p>

<p>Here I am in the same file I had before. I didn&apos;t update my loop, but I
added the array with the colors in here. What we would do down here is
we would set i to 0 first, so we get red. While i is less than four,
we&apos;re going to increment i cause we&apos;re going to do it for red, blue,
yellow, and green. Down here, I&apos;m just going to console log out,
colors, square bracket i. The first time through the loop i is 0. Colors
square bracket 0 gives me a red and then i gets incremented to one. The
second time through the loop, i is a one. I go to my colors array here.
Colors square bracket one gives me a blue, i gets incremented to two. I
go up to colors here and I go 0,1, 2. Now colors, square brackets two is
going to give me yellow. I get incremented to three. Colors three is 0,
1, 2, 3, it&apos;s going to be a green. I get incremented to four. Four is
no longer less than four and my loop breaks out.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 185. test, looping array (109) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image185.png?raw=true"
  width="50%"
  alt="Test, looping array." />
</p>

<p>Let&apos;s give this a try and see if it works. Sure enough, I get my four
colors out in the array. It&apos;s looping through and doing line 15 four
times there. That&apos;s really useful. Now, generally, this is fine, this
works.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 186. looping using length (109) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image186.png?raw=true"
  width="50%"
  alt="." />
</p>

<p>But generally we don&apos;t want to have to put in a number here. What&apos;s
better is to keep this more general. If I do colors.length, that&apos;s also
a four, <b>colors.length</b> is four. Now I could add more colors into my
array, and this code will still run. No matter how many colors I have in
my array. I could add in here orange and purple into the array. This
will continue to work because now the length of my array is six. I
don&apos;t have to update this number every time. Colors.length will help me
make my code more general and allow me to do that thing more easily.
Okay, so we can do that really nicely and loop through all the colors in
the array that way.</p>

<p>Another example;</p>

<pre><code>
  const fruits = &lbrack;&apos;apple&apos;, &apos;banana&apos;, &apos;orange&apos;&rbrack;;

  for (const fruit of fruits) {

    console.log(fruit);

}
</code></pre>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-12">2.12 The For..Of Loop (6:06)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 187. the for..of loop (110) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image187.png?raw=true"
  width="40%"
  alt="2.12. The For..Of Loop." />
</p>

<p>It&apos;s important to note that the for&hellip;of loop cannot be used with
objects directly, as objects are not iterable by default. However, you
can iterate over the keys or values of an object using Object.keys(),
Object.values(), or Object.entries() in combination with the for&hellip;of
loop.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 188. example of the for..of loop (110) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image188.png?raw=true"
  width="50%"
  alt="Example, for..of loop." />
</p>

<p>The basic for loop is a good place to start with loops. There&apos;s also a
loop that is specifically for working with arrays and it&apos;s called the
<b>for of loop</b>. Here I have an array of food. You can see there are
four items in here, four foods. I can use for, and I can create a
temporary variable, and I&apos;m calling it each item, but you could call it
X, you could call it Y you call it I, you call it whatever you want.
Each item of food. Each item with this loop is going to do is it&apos;s
going to go through this array until the end of the array. Each item the
first time to the loop is going to be grapes. I&apos;ll cancel out the
grapes, and then since the array is not reached the end yet, it&apos;ll run
again and each item will become cheese, and then it&apos;ll become bread,
and then it&apos;ll become olives. Let&apos;s give this a try really quickly in
our code over here.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 189/190. example/test of for..of looping (111) ~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image189.png?raw=true"
  width="45%"
  alt="Example for..of loop colors." />
<img src="./images/image190.png?raw=true"
  width="45%"
  alt="Test, output of for ..of loop colors." />
</p>

<p>I&apos;m going to just leave the array with colors, but instead of this for
loop, I&apos;m going to do for var each color of colors. It knows what
colors is because that&apos;s been defined here. Each color is putting var
here because I&apos;m creating a new variable there. Then down here I can do
<b>console.log</b> each color. You&apos;ll see that when this runs over here, I
get each color. There are other methods used for looping that we'll talk
about later. Basically, there is; <b>for of, for in</b>, and <b>for Each</b>
methods of looping in JavaScript.</p>

<p>Right now, I just want to get you started with the basics so you can see
how to do this. The basic for-loop is a good place to start for working
with arrays.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 191. example, strings as arrays (112) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image191.png?raw=true"
  width="50%"
  alt="." />
</p>

<p>We can also do something with strings. Remember strings can be treated
like an array. I can actually make a string and then loop through the
length of this thing and actually alert out each letter one at a time in
my <b>console.log</b> there. I can do that thing.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 192/193. example, test for using length (112) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image192.png?raw=true"
  width="45%"
  alt="Example for loop with string length." />
<img src="./images/image193.png?raw=true"
  width="45%"
  alt="Test, output of example loop." />
</p>
<p>In fact, let&apos;s give this a try really quickly here and change this to
myString equals here is a text. There we go. I could do it. I can do it
this way, for var i equals 0, log i is less than myString.length i plus,
plus <b>console.log</b> <b>myString</b> square bracket i. I can do it this
way. Let&apos;s see if I did it right. Sure enough, each line has a letter.
I could do it that way, or I could even use the for of loop.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 194. another example of for..of loop (113) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image194.png?raw=true"
  width="50%"
  alt="Another example of for..of loop." />
</p>

<p>Here&apos;s an example, like above, but using the "for of" loop as well.
This will give the <b>myString</b> twice.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-13">2.13 While Loops (13:08)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 195. while loops (2.13) (113) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image195.png?raw=true"
  width="40%"
  alt="2.13. While Loops." />
</p>

<p>JavaScript also has a <b>while loop</b> and we don&apos;t see them as often
while we&apos;re programming with JavaScript, but they are worth knowing
about.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 196. example, while loops (114) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image196.png?raw=true"
  width="50%"
  alt="Example, while loops." />
</p>

<p>Let&apos;s take a look at them really quickly. Here we can see the way the
<b>while loop</b> works is we start off, we have an <b>incrementor</b>, and
then I&apos;m making a variable that starts as an empty string. That&apos;s
maybe not quite as necessary but you have to have the <b>incrementor</b>
outside of the <b>while loop</b> when you&apos;re using a <b>while loop</b>. Then
while the <b>while loop</b> is less than 10, I&apos;m going to do this stuff
and then <b>increment</b> the <b>incrementor</b> at the bottom of the <b>while
loop.</b> This is going to run, <b>incrementor</b> gets set to one, one is
less than 10, so this runs again. <b>Incrementor</b> gets set to two, two
is less than 10, so this runs again, so on and so forth. Then notice
when the loop is done, once this increments up to 10, 10 is no longer
less than 10, so I&apos;ll bump out of the while loop. This console log is
going to run text.</p>

<p>What I&apos;d like you to notice here is this <b>plus equals</b>, this text is
starting out as empty and <b>plus equals</b> is saying each time this thing
runs, add to what was there before. The first time through the loop,
there&apos;s nothing in there. It&apos;s going to add the <b>incrementor</b> has
gone up to plus <b>incrementor</b>, so that&apos;s going to be a zero, and then
a new line, and then the <b>incrementor</b> gets incremented to one, and
then the next time through the loop, we&apos;re going to add to that. It&apos;s
going to add a new line that says the <b>incrementor</b> has gone up to
one. Then it&apos;s getting increment again then we&apos;ll say the
<b>incrementor</b> has gone up to two, so on and so forth.</p>

<p>Let&apos;s do this one in the code editor because I think it&apos;s really worth
seeing this. I&apos;ve got my for loop so I&apos;m just going to comment that
stuff out. I don&apos;t really need that now.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 197/198. example/test while loops in js (115) ~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image197.png?raw=true"
  width="45%"
  alt="Example while loop." />
<img src="./images/image198.png?raw=true"
  width="45%"
  alt="Test, inspect incrementor." />
</p>

<p>Come down here. I&apos;m going to make a variable var incrementor equals
zero. Again, it doesn&apos;t have to be incrementor. You could leave it out
if you wanted to, that would be fine. Then I&apos;m going to make var text
equals quote, quote. That&apos;s an empty string. Notice I&apos;m using just the
single quotes here, but you could do the double-quotes if you want on my
image there. But you could use single quotes or double quotes. I&apos;ll put
it in double-quotes right now. There we go. It&apos;s just an empty string
there. Then while incrementor is less than 10, I&apos;m going to do
something. What I&apos;m going to do is I&apos;m going to say text plus equals,
add to what was already there, quote, the incrementor. What did I put
over here? I forget now, has gone up to, that&apos;s right. Then I need to
have a space there. I&apos;m going to use a plus to concatenate in the
incrementor variable. It&apos;s gone up to whatever that number is and then
I&apos;m going to add a plus and another set of quotes. Now I need to add
the new line. In this case, I actually need the new line because this is
not going to get printed out. It&apos;s only going to get printed out once
after the loop is done. Incrementor plus. Then down here I&apos;m going to
print the console log once with all the text in it.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~ 199/200. example/test while loop using text (116) ~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image199.png?raw=true"
  width="45%"
  alt="Example while loop." />
<img src="./images/image200.png?raw=true"
  width="45%"
  alt="Test, inspect incrementor." />
</p>

<p>There&apos;s one print to the console log. Let&apos;s give that a try. If I
didn&apos;t mess anything up here, let&apos;s see. There we go; 0, 1, 2, 3, 4,
5, 6, 7, 8, 9. If I didn&apos;t put the slash n on the end here, let&apos;s see
if this does, but I think it&apos;ll do. There we go. I don&apos;t get the new
lines. The slash n is adding new lines over here after each one of
these, because this is just getting printed out once. That&apos;s really
important to understand about the way this incremented and the way the
while loop works here.</p>p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 201. same example, while loops (116) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image201.png?raw=true"
  width="50%"
  alt="Same example, while loops." />
</p>

<p>When we look at this image here, we&apos;re using the plus sign to concatenate 
the string together with the variable. We talked about this before. The plus sign 
in JavaScript does double duty. It&apos;s used to add numbers together the way 
you would normally expect the plus sign to work, but it&apos;s also used to 
concatenate strings and things together. Here we&apos;ve got a string of text 
and then we&apos;re concatenating in the variable and then another string of 
text concatenated onto the
end of that. It gets complicated to work this way. It&apos;s not very
intuitive. We can&apos;t just leave incrementor inside the quotes because
then the string would just say the incrementor is gone up to
incrementor. JavaScript would know that this is a variable if we just
put this inside the quotes.</p>
<p>With ES6, which you&apos;ll remember is the
version of JavaScript that was released in 2015. They introduced
something called template literals that will allow us to work with
variables inside strings a little bit more easily.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 202. example, template literals (117) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image202.png?raw=true"
  width="50%"
  alt="Example, template literals." />
</p>

<p>Let&apos;s take a look at
how to do that. Here we have the template literal, and what the template
literal the way it works is we put a tick mark on either end. The tick
mark is not a quote. The tick mark is a separate character on your
keyboard. On the American keyboard, it is the character with the tilde
just above the Tab key. That&apos;s a tick mark there and a tick mark there.
Then we can just put the variable inside curly braces with a dollar sign
and JavaScript will know to treat that as a variable. This is a much
more readable way of working with strings, with variables in them.</p>
<p>This particular string is not terribly complicated or complex in any way. But
sometimes if you&apos;re constructing a piece of HTML and you&apos;ve got tags
and tags have their attributes in them, which have quotes and equals
signs it can get really confusing really quickly. This will really help
you out and we&apos;ll be using the template literals throughout the rest of
this course quite a lot.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 203. example, while incrementor (118) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image203.png?raw=true"
  width="50%"
  alt="Example, template literals." />
</p>

<p>Let&apos;s switch our codes that we&apos;re using this
over here.</p>
<p>The way we do this is, I&apos;m going to put in a tick mark there
and at the end I&apos;m going to put in a tick mark and then I can get rid
of these quotes and pluses. Then because this is a variable, I&apos;m going
to put a dollar sign, a curly brace, and another curly brace.</p>
<p>By the way, if you&apos;re constructing a string that has variables, this is how I
recommend that you do it, rather than just typing from left to right,
type it like this. The incrementor has gone up to incrementor and then
go in and add the dollar sign and the curly braces. You&apos;ll find it
easier to understand what you&apos;re doing and to not make mistakes and do
all that stuff if you do it this way.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 204. test, while incrementor (119) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image204.png?raw=true"
  width="50%"
  alt="Example, template literals." />
</p>

<p>But you&apos;ll notice if I do this
and save it and then go back and run the page over here. I mean, I just
ran it, but it looks exactly the same and I am getting my variables over
here. That is actually working.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~ 205/206. example/test while incrementor using text (119) ~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image205.png?raw=true"
  width="45%"
  alt="Example while loop." />
<img src="./images/image206.png?raw=true"
  width="45%"
  alt="Test, inspect incrementor." />
</p>

<p>If you wanted to see if it was actually
doing something different, we could start here with 1 and go to 11. See
what that looks like. There we go, 1-10, very nice. That&apos;s great.
We&apos;ve got the template literals.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 207. another example, while loop (120) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image207.png?raw=true"
  width="50%"
  alt="Example, another while loop." />
</p>

<p>We&apos;re going to take a look at one more example. What&apos;s interesting 
here is we can actually do expressions inside our curly braces here. Rather 
than just sticking a variable in there, we can actually perform JavaScript
operations right in line with our string.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~ 208/209. example/test while incrementor using text (120) ~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image208.png?raw=true"
  width="45%"
  alt="Example while loop." />
<img src="./images/image209.png?raw=true"
  width="45%"
  alt="Test, inspect incrementor." />
</p>

<p>Let&apos;s give this a try. I set
the incrementor to i to keep it shorter here. Let&apos;s do that. Over here
I&apos;m going to set this to just i, i is one word, we&apos;ll start it at 0.
I&apos;m sure we&apos;ll leave it at one. Do it like this. The incrementor is i
and the incrementor squared is i times i. But this is going to be a
variable and so is this. This is going to be an expression. Maybe I want
some spaces in there make that a little bit more readable. Let&apos;s go see 
what that does. I&apos;m getting my squares over here as well.</p>
<p>Loops are one of the fundamental building blocks in JavaScript. It&apos;s
important to get comfortable with the syntax needed to create them. I
recommend just sitting down and getting to the point where you can type
out a for loop. I know that it looks a little weird at first, but you
have to just keep working at it so you can get to the point where you
could sit down and say, I&apos;m just going to write out a for loop and when
you get there, then you&apos;ll know that you have the loops really down
pat. Great, we&apos;re going to a move on to the next thing.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Additional Resource</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Here is a resource related to these lessons:

<ul id="ch2-13-loop">
  <li><a href="https://www.w3schools.com/js/js_loop_for.asp">
    2.13.JavaScript Loops (shortcut)</a></li>
</ul>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-14">2.14 Structured Programming, Sequence - Part 1 (4:43)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~ 210. structured programming, sequence - part 1 (2.14) (121) ~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image210.png?raw=true"
  width="40%"
  alt="2.14. Structured Programming, Sequence - Part 1." />
</p>

<p>Sequence, selection and loop.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 211. definition: structured programming (122) ~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image211.png?raw=true"
  width="50%"
  alt="Definition Structured Programming; Sequence, selection &amp; loop." />
</p>

<p>In this lesson, we're going to put together some of what you've already learned and 
what you've already been doing and see if we can make some sense out of it. In 
Structured Programming, we make use of these three structures we've already started 
working with. <b><i>Sequence</i></b>, 1st, you do this, then you do that, finally, you do this 
over here. With JavaScript, you start at the top of the script and you work your 
way down the script and JavaScript does everything in the script one thing at a 
time in a <b><i>sequence</i></b>.</p>

<p>With <b><i>selections</i></b>, we're checking to see if some condition is met. If this is 
true, do this, otherwise, do that. Then with <b><i>loops</i></b>, while a condition is true, 
we're going to continue to do something. With the scripts that we have next, 
we're going to learn a little bit about JavaScript string methods, while also 
practicing some of these techniques you've already learned a little bit about 
with <b><i>loops</i></b> and <b><i>selections</i></b> and these kinds of things. Hopefully, you'll start 
to see the expressive power of JavaScript. </p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 212. methods of text/string manipulation (123) ~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image212.png?raw=true"
  width="50%"
  alt="Converting to Upper or Lower case and other text manipulations." />
</p>

Over here I have some of the different string methods you can do. To
start with, we&apos;re going to work with the <b>toUpperCase()</b> method here.
We can actually take a string of text, assign it to a variable, and then
take that variable and do.<b>toUpperCase</b>, and that&apos;s a method that
will take that string and convert it into an uppercase string. Or you
can convert it to lowercase.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 213. example substr() text manipulation (123) ~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image213.png?raw=true"
  width="50%"
  alt="Example substr() text manipulation." />
</p>

<p>If you come to this page, you&apos;ll notice and further down the page here,
but there&apos;s all different things we can do with strings; to replace
content, to find content, to do all kinds of things with strings. We can
take pieces of strings out of strings, we can perform string surgery.
This page is very useful to explain some of the different things that we
can do with strings of text. You might be wondering, well, why would I
want to do anything with a string of text? Why would I want to do this
stuff?</p>

<h5><a href="W3schools.com/js/js_string_methods.asp">JS String Methods</a></h5>

But if you think about it, a web page from the very first character of
the web page to the very last character of a web page is nothing but a
string of text. If I were to right-click on this page and do the page
source, you can see it starts with a character, and down at the bottom,
way, way down at the bottom, it ends with a character. This is one long
string of text. From that perspective, every web page is really just a
string. If we can do things with strings, we can affect web pages. Not
that we&apos;re going to do it that way very often, but you actually can do
it that way, which is pretty cool.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 214. example, sequence part 1 (124) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image214.png?raw=true"
  width="50%"
  alt="Sequence Part 1, example." />
</p>

Let&apos;s go forward with this and see what we&apos;re doing here. The first
thing we&apos;re going to do is create a variable called <b>myString</b> and
assign it the following string, &quot;I&apos;m really hungry for some&quot; and then
use the <b>console.log</b> to print out that string. Then make a new
variable called <b>myUpperString</b> and use the string method to
capitalize all the text in the first string and then print out the
capitalized version in the console. Can you do that on your own? Try to
do it using this <b>toUpperCase</b> string method here. You can pause the
video and come back and see how I did it. When you&apos;re ready, unpause
the video, and let&apos;s see if you got the same thing I got.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 215. sequence part 1, result (125) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image215.png?raw=true"
  width="50%"
  alt="Sequence Part 1, result." />
</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 216. sequence part 1, result in script (125) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image216.png?raw=true"
  width="50%"
  alt="Sequence Part 1, result in script." />
</p>

<p>Did you get something like this? I have the same thing over here in my
Visual Studio Code. I left out the spaces, but this is the same thing
here. Created a variable myString, assigned some text to it, I&apos;m
console logging that out, then make a new variable called myUpperString,
which is my string toUpperCase with the parenthesis. This is a string
method. We&apos;re going to talk about <b>methods</b> and <b>functions</b> and all
that in a little bit, but for right now, understand that <b>method</b> has
these parenthesis at the end. It&apos;ll take <b>myString</b> and convert it
into uppercase, and then I can <b>console.log</b> that out and assign it to
this and <b>console.log</b> that out. That works really great.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 217. test, sequence part 1 (126) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image217.png?raw=true"
  width="50%"
  alt="Test, Sequence Part 1." />
</p>

I can come over here and see that that actually runs, and I&apos;ve got both
of my strings. One of them is lowercase, and one of them is uppercase.
That works great. Let&apos;s see, what should we do next.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-15">2.15 Sequence -- Part 2 (5:42)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 218. sequence - part 2 (2.15) (126) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image218.png?raw=true"
  width="50%"
  alt="2.15. Sequence - Part 2." />
</p>
 
<p>Next, we'll do some more surgery on our strengths.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 219. example, sequence part 2 (126) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image219.png?raw=true"
  width="50%"
  alt="." />
</p>

What, we're going to do first here is we're going to pull out the word ''really''. 
So I'm going to make a variable called reallyLocation, and I'm going to use the search 
method to find out where this word ''really'' in my string starts.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 220/221. test, output - sequence part 2 (126) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image220.png?raw=true"
  width="45%"
  alt="Answer test, sequence part 2." />
<img src="./images/image221.png?raw=true"
  width="45%"
  alt="Output test, sequence part 2." />
</p>

<p>What this is going to return is a number of that location. So let's do that first. Var 
reallyLocation equals myString.search really. Then I'm just going to console log out 
reallyLocation just so you see you can see exactly what that's getting. Assuming I 
did that right and I did. That's getting a five. What that means is that if I count 
from here 0, 1, 2, 3, 4, 5, this is character Number 5. It starting at a five. How 
many characters do I want to get? I'm going to get six characters.</p>

<p>So I'm going to use the substring function or method here, and I'm going to pass in 
reallyLocation which is location five, and I'm going to get six characters. What that's 
going to do is it's going to pull out into this variable, special word, the word 
''really''. It's going to start at five from myString and get six characters.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ 222/223.  (127) ~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image222.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/image223.png?raw=true"
  width="45%"
  alt="." />
</p>

So let's do that. Var specialWord equals string.substring, and I'm going to start 
with reallyLocation and get six characters. If I console log special word, you'll 
see that what that's getting for me. It's myString.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ 224/225.  (127) ~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image224.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/image225.png?raw=true"
  width="45%"
  alt="." />
</p>

So I've got that, now I'm going to take specialWord and assign it back to itself, 
but uppercased. I'm going to say specialWord, I'm going to assign it 
specialWord.toUpperCase. So now it's going to be uppercase, and then what I'm 
going to do is I'm going to make a newString and I'm going to replace ''really'' 
with specialWord into the original myString here, and then I'll console log out 
newString. So let's do that. Var newString equals myString.replace. Which order 
does it go in? I'm going to replace ''really'' with specialWord. SpecialWord like 
so and then I'll console. console.log newString. What I should get is I am really 
hungry for some, so I'm getting the capital word ''really'' there. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 226.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>

But this is a sequence, JavaScript is doing a sequence of things, one thing after 
another, we're just doing a sequence of things here. JavaScript goes through the 
script one step at a time, and we're just learning about some string methods along 
the way. We've learned about a few of them already, uppercase and replace and 
search and substring, and there's a lot more here that you can go through and 
learn. But that'll get you started to begin with the various string methods that 
are available in JavaScript for doing string surgery.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-16">2.16 Sequence - Part 3, Loop (5:42)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 227. sequence - part 3, loop (2.16) (129) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image227.png?raw=true"
  width="50%"
  alt="2.16. Sequence, Part 3, Loop." />
</p>
For the next step in our sequence, make an array called foods and put four foods 
in the array. Then use the string literal syntax. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 228. sequence, part 3 (130) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image228.png?raw=true"
  width="50%"
  alt="Sequence, Part 3." />
</p>

So we can practice that to print out a sentence that prints to the console the 
variable myString, which we declared earlier, and follow that with a space and 
then the first element in the foods array. See if you can do that. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 229. sequence, part 3 results (130) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image229.png?raw=true"
  width="50%"
  alt="Example, Sequence 3 Result." />
</p>

Pause the video and see if you can do that without looking at the answer that I have 
next and when you're done, unpause the video and come back and we'll see how I did it. 
Did you get something like this? I have myString in here again, but you shouldn't need 
that because we already have that on our file but you should have an array and then 
the console.log with the template literal, takes a little getting used to the template 
literal thing. Let's do that part together. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 230. array of foods in script (131) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image230.png?raw=true"
  width="50%"
  alt="Create array of foods in script." />
</p>

So over here you can see I've added the array and then here I need to add the template 
literal. And the best way to do this is to just type the variables myString. Then I 
want a space and I want foods square bracket 0. But these are variables. So I'm going 
to come in here and add a dollar sign and a curly brace, and a curly brace. Then a 
dollar sign and a curly brace and the curly brace around it. If you do it that way, 
you'll understand it better if you always work from the inside out or the outside in, 
in this case, we're working from the inside out. But if you work that way, it'll make 
it easier for you to understand. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 231. for loop (132) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image231.png?raw=true"
  width="50%"
  alt="For loop." />
</p>

Then over here I can actually run that and I should be getting, "I am really hungry 
for some cheese". So that works perfectly well. The next thing to do is to see if you 
can use a loop and loop through all of the elements in the array. I'm really hungry 
for some cheese, for some pie, for some lunch, for some breakfast. All of these elements. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 232. for i=0; loop i++ (132) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image232.png?raw=true"
  width="50%"
  alt="For i=0; loop i++." />
</p>

I'm going to say var i equals 0. So I'm going to start at 0. For i is less than 
foods.length. Now I could stick in here a four instead of foods.length, but this 
is better practice. Foods.length i plus, plus. Then I'm going to console.log out 
this line here. We're just going to stick that in there. But instead of food 0, 
I'm going put an i in there because i is going to get each one of these. In fact, 
just so you don't get confused, I'm going to comment that line out there just so 
I can see that this is really working. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 233. test, loop (133) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image233.png?raw=true"
  width="50%"
  alt="Test, loop." />
</p>

First time through the loop, i is 0, so it's going to print out, I'm really hungry for 
some space food square bracket 0 because i is 0, i gets incremented to one. So the second 
time through the loop, one is less than four because remember this is going to be a four. 
So it'll go through again and you'll get pie. Then the third time through the loop it's 
going to get breakfast, and the fourth time through the loop it's going to get lunch. 
Then i gets incremented to four because it's 0, 1, 2, 3. So i is going to get incremented 
to four, four is not less than four. So the loop will bust out. Let's see if that works. 
There we go. We're getting all of it there. That's great. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 234. for var each loop (134) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image234.png?raw=true"
  width="50%"
  alt="For var each loop." />
</p>

Now, what if you wanted to use the for-of loop? I'm going to just comment that out. For var, 
eachFood of foods, something like that will work. It doesn't have to be eachFood, you could 
do i if you wanted to. Then in here, we're going to do the same thing. We're just going to 
basically take this and stick it here, but now instead of foods, this foods i, this is going 
to be eachFood. I'm still going to print out myString, but now this is going to be eachFood. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 235. test, for var each loop (134) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image235.png?raw=true"
  width="50%"
  alt="Test, for var each loop." />
</p>

The first time through the loop, eachFood is going to be cheese. Then the second time through 
the loop it's going to be pie and then it's going to be breakfast, and then it's going to be 
lunch. We should get exactly the same results so let's go test it out to be sure. Sure enough, 
I get the same results.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-17">2.17 Loop + Selection (8:20)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 236. loop + selection (2.17) (135) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image236.png?raw=true"
  width="50%"
  alt="2.17. Loop + Selection." />
</p>

Next we'll bring selection into the mix. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 237. example, loop + selection (135) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image237.png?raw=true"
  width="50%"
  alt="Example, Loop + Selection." />
</p>

Now, inside our loop, we're going to check to see if the element in the loop is 
even or odd. If it's even, we're going to make the word for the food that we're 
getting out of the array all uppercase like this over here. This should be your 
results. I am hungry for some CHEESE, all capital letters there, and I am hungry 
for some pie and that one's normal, and then LUNCH is going to be uppercase. Now 
you might be wondering, well, wait a minute, that's not even. But remember we're 
starting with zero so this is zero, this is one, this is two, this is three. 
These two really are the even ones. 
In JavaScript, you can determine if something is even or odd by using the modulus 
operator, which is the percent sign. We can figure out when we divide something 
and use the percent sign if the remainder is zero, then it's even if you divide 
something by two. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 238. for var i=0 length array i++ (136) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image238.png?raw=true"
  width="50%"
  alt="For var i=0, length of array, i++." />
</p>

Let's do this together. Here I am with my loop and I got rid of the for of loop. 
This one's really going to work better because we already have i working as an 
incrementor with numbers. So we can just work with i to do this. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 239. example to console.log (136) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image239.png?raw=true"
  width="50%"
  alt="Example to console.log." />
</p>

Initially, I'm going to add this var remainder i percent two. Now, what that's going to 
do is each time through the loop, it's going to take i and divide it by two and see what 
the remainder is. The first time through the loop, I take zero. Zero divided by two is 
zero. That's going to be a zero, that's even. One divided by two is not zero. Two 
divided by two is zero, so on and so forth. If remainder is exactly the same as zero, 
we could do same as, but just to be absolutely sure, exactly the same as zero. If it's 
exactly the same as zero, then what we're going to do is we're going to make a variable 
var foodUpper and assign it foods [ i ]. That's going to get that first food, whatever 
is there and due toUpperCase. Then I'm going to print out basically this. But instead 
of foods i down there, I can print out this one here. I think that'll work. Else we'll 
just do this. Save that. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 240. test, loop + selection (137) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image240.png?raw=true"
  width="40%"
  alt="Test, loop + selection." />
</p>

Did I do it right? Let's see. Refresh my page here and look at that it's working. 
That's great. Did you get something like that? That's great. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 241. example, refacturing code (138) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image241.png?raw=true"
  width="50%"
  alt="Example, Refacturing Code." />
</p>

The next thing I want to talk about is refactoring code. Often we will write code the 
first time and then look at it later and realize that could be a little bit simpler. 
I could simplify that a little bit. Refactoring code is the process of taking your 
code and not changing its functionality at all, but making it simpler, finding ways 
of making it shorter and making it more concise, making it more readable. Sometimes 
those things don't all go together. Sometimes making it more concise, makes it less 
readable. But really you're looking for the right balance of conciseness and 
readability when you're refactoring your code. We could take that same piece that 
we wrote and refactor it a little bit so that we could get rid of that extra 
variable here. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~ 242. example, sequence, selection & loop (138) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image242.png?raw=true"
  width="50%"
  alt="Example test, Sequence, Selection & Loop." />
</p>

Let's do that really quickly over here. Frequently, students will tell me when 
they're working through my examples they'll say, "Oh, wow, I tried it and I 
ended up with way more code than you did. Yours is much more concise." Well, 
that's because I've refactored mine down quite a bit. Nobody writes it perfectly 
the first time so don't feel bad about that. Always just keep working at it, 
look for ways of taking your code and saying, you know what, this could be a 
little bit simpler. I'm going to take that, I'm going to save it and I'm going 
to just make sure that it still runs exactly the same way. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 243. test, sequence, selection & loop (139) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image243.png?raw=true"
  width="50%"
  alt="Test, Sequence, Selection and Loop." />
</p>

Make sure I did that right, and I did, so that's fine. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 244. example, make comments (139) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image244.png?raw=true"
  width="50%"
  alt="Example, Make Comments." />
</p>
 
Another thing you can do that's really helpful is make comments. If you're not really 
sure that you can refactor something down, but then it can become less readable and it 
can be helpful to put comments in there to help you make sure when you come back to it 
later that you know what you did and that it will make sense to your future self. You 
can go ahead and come in here and add comments. I'll put it up here. Checking to see 
if the incrementor is even. Something like that will be helpful later perhaps and you 
could add more comments in here. As you refactoring, be sure to do that as well. 
Once you've added your comments and refactored your code, you've done a great job at 
working with sequence selection and loops. We're going to get more practice with those 
as pretty much every script that we write will have some combination of them as we go 
along. Great, see you in the next lesson.

<ul>
  <li><a href="https://www.coursera.org/learn/javascript-basics/supplement/9clcg/javascript-basic-challenges-01-09">
    2.17.JS-BasicChallenges-01thru09.pdf (download)</a></li>
</ul>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-18">2.18 JavaScript Basic Challenges Introduction (5:02)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~ 245. javascript basic challenges introduction (140) ~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image245.png?raw=true"
  width="50%"
  alt="2.18. JavaScript Basic Challenges Introduction." />
</p>

JavaScript basic challenges. This course includes a number of challenges, and these 
challenges will help you become better at writing JavaScript and becoming a JavaScript 
programmer. I encourage you to take the time you need to, to get good at working 
through these challenges and to be able to do the challenges and get the correct 
results. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 246. example, challenge 1 (141) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image246.png?raw=true"
  width="50%"
  alt="Example, Challenge 1." />
</p>

The way the challenges work is, I'll give you a challenge. This first one is fairly 
simple. Write a script that prints out your first name on one line, your last name 
on the next line. Very basic challenge. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 247.  (141) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image247.png?raw=true"
  width="50%"
  alt="." />
</p>

But what you should do is set up your file. I have a file set up here, and then you'll 
come in here, and it's very normal to be, "Okay, what do I do first?" I don't even know 
what the first thing is to do, and that's fine. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 248. example, challenge 1 answer (142) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image248.png?raw=true"
  width="50%"
  alt="Example, Challenge 1 Answer." />
</p>

You can always come over and look at the answer for the challenge will be on the next 
slide, and you can look at that and go, "Okay, yeah, that makes sense. We did that in 
the other lesson, I know how to do that." Then, come back and actually write that, var 
firstName equals, "Bill", and I've forgotten what to do next, and that's normal. Go and 
look again, if you have to. Look again and see what you need to do next, and then go 
back and actually type it without looking at the slide. What this will do, this will 
do a few things to really help you get good at JavaScript. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 249. camel with 2 humps (142) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image249.png?raw=true"
  width="50%"
  alt="Camel with 2 humps." />
</p>

First, what it'll do is it'll help you with the syntax of the language. Remember we need 
to get over this first hump of the camel. We need to get over that first hump, which is 
learning the syntax of the language. The way to learn the syntax of the language is to 
type it. When you're working on this, even if you're looking at the answer and then 
having to come in here and just remember it for a few seconds, that will help you learn 
the syntax and get better at it over time, and I promise it will help. Over time, you'll 
really start to be able to do these without having to look at the slides if you keep 
working at it. Look at the answers if you have to, they're here, and then type it 
without looking at the answer. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 250. example, challenge 2 (143) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image250.png?raw=true"
  width="50%"
  alt="Example, Challenge 2." />
</p>

The second thing that I'll do for you is these challenges build on each other. The second 
challenge is a little bit of a baby step beyond the first challenge. I've designed these 
challenges such that they build up in small baby steps like this so that over time, 
you're taking an idea and expanding it into a larger, more complex script as you go 
along, and that will help you with this second hump on the camel. Learning how to solve 
problems with JavaScript. You get good at learning how to solve problems first by 
solving very small problems in making baby steps, and these challenges, we'll help 
you do that. 

I recommend you do these challenges to the point where you can do them without looking 
at the answers because that will really help you with the syntax and meanwhile, you're 
building up some skill for how to take a small thing and then build on it. Now, there's 
nothing magical about these challenges. I also recommend you come up with your own 
challenges. Try things out. See if you can make a small thing work. If you can make that 
small thing work, then build on it and see what other ideas you have and see if you can 
build on those. That is a great way to learn JavaScript, and it's fun. It's fun to see 
if you can do that kind of thing. By doing these challenges, by working through these 
examples and by getting really good at them, you will build your skills with JavaScript.
 
If you don't, you don't have to. You can continue to watch the videos and do the quizzes 
in the videos, and you'll learn about JavaScript. But in order to actually become a 
JavaScript programmer, you have to write JavaScript. You have to take the time to really 
sit down and write it. Even if you're coming to JavaScript from another language like C 
plus plus or Java, or Python or some other language and you might be thinking, oh yeah, 
I know what loops are, and I know what if statements are, and those kinds of things. 
I recommend you sit down and write JavaScript because it's a little bit different 
and it takes practice. Great. Keep working on these and get really good at the challenges 
and I promise, you'll be on the road to becoming a good JavaScript developer.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-19">2.19 Functions in JavaScript (5:29)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 251. functions in javascript (2.19) (144) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image251.png?raw=true"
  width="50%"
  alt="2.19. Functions in JavaScript." />
</p>

Functions in JavaScript. Functions are reusable sets of instructions. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~ 252. example reusable sets of instructions (145) ~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image252.png?raw=true"
  width="50%"
  alt="Example, Reusable Sets of Instructions." />
</p>

For example, in the sequence selection and loop exercise, you're adding a bunch of script 
to the page and it was getting messy. There's a lot of single lines of code all piling up 
without a lot of order, organization to them. What we can do with functions is we can 
take that stuff, stick it inside of something that has a name, and then run that function 
when we want to run that set of instructions. We can make functions so that they're 
reusable, so that you can use them in multiple places within your programs, and that's 
where functions can become very powerful. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 253.  (145) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image253.png?raw=true"
  width="50%"
  alt="." />
</p>

Here, I have a function called doStuff, which is going to run something similar to what 
we did in the sequence selection and loop exercise. Let's give this a try real quick. 
I'm going to switch over to my code editor over here. You can see, I've already set up a 
file and I recommend you do the same. It just needs to notify within each one, and I've 
got a script here, and I've got some of the script from our sequence selection and loop 
exercise. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 254.  (146) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image254.png?raw=true"
  width="50%"
  alt="." />
</p>

Now, I'm going to add a function. To do that, I would just define a function here. 
Function is the function keyword doStuff, parentheses and curly braces. Now, this stuff 
can just go inside the curly braces, like that. Then you have to run the function 
doStuff. We define the function which tells it what it does, then we invoke or call or 
run the function. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 255.  (147) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image255.png?raw=true"
  width="50%"
  alt="." />
</p>

Any of those verbs will do: invoke, call or run. I can save that and I can come over to 
my pagers, and this is that same page, and I can run this, and you can see that the 
function runs and it does its thing. It's very normal when you start doing this, and 
sometimes I still do it to forget to call the function, which will mean that you'll get 
nothing, because it'll be defined but it won't actually run. I have to run doStuff. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ 256/257.  (147) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image256.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/image257.png?raw=true"
  width="45%"
  alt="." />
</p>

We'll run that function. I went and got challenge number 7 and I have it over here, so 
here's challenge number 7. How would I take that and turn it into a function? Well, I 
could do it like this; I could take all of this stuff and I can come over here, and I 
can go ahead and just paste it right on my page here, right in my file down here at the 
bottom. I'm going to just paste it on in there. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 258.  (148) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image258.png?raw=true"
  width="50%"
  alt="." />
</p>

But I'm going to make a new function. What is this thing doing? Well, it's checking a 
number. I'm going to make a function called checkNum, parentheses, curly braces, like 
so. Then I'm going to take this stuff, I'm going to stick it inside of checkNum, tab 
that in. It's clear that this curly brace is ending that curly brace and everything 
is inside. It's always good to be clear about your indenting if you possibly can, it 
really does help. Then down here, I'm going to run checkNum, and let's see what happens. 
Over here when I run my script, it says enter a whole number, 54, and then you entered 
a really big number. My function is running, it's functioning, it's doing what it's 
supposed to do, and all that code is now inside of a function.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-20">2.20 Passing In and Returning Data (8:01)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 259. passing in and returning data (2.20) (149) ~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image259.png?raw=true"
  width="50%"
  alt="2.20. Passing In and Returning Data." />
</p>

Functions are even more useful if you can pass data into them, so they can do something 
with that data. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 260. example, passing in data (149) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image260.png?raw=true"
  width="50%"
  alt="Example, Passing in Data." />
</p>

So for example, our first do something message, the first do something function wasn't 
really useful because it was just taking that string, and making it uppercase, and then 
spitting it back out again. But we could make it more useful by passing in a message 
variable, a parameter, this function has a parameter called message. We could pass in 
a messages and argument to this function, and it will take any message, and make it 
uppercase, and console log it out. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 261. function uppermessage (150) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image261.png?raw=true"
  width="50%"
  alt="function upperMessage()." />
</p>
So let's give that a try and see what that does. I'm going to make a function, function 
upperMessage, let's do that then, upperMessage, that doesn't matter really what you 
call it. And then I'm going to take message and I'm going to say, var upperMessage = 
message.toUpperCase. And then I'm just going to console log out, upperMessage. 	

Now when I run this, I run upperMessage, but I pass in, here is a message. I can pass 
any message in that I want and it will make it uppercase. Still not super interesting, 
but it's something that shows us how this actually works.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 262. test, here  is a message (151) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image262.png?raw=true"
  width="50%"
  alt="Test, HERE IS A MESSAGE." />
</p>

So over here when I run this, my message is turned into uppercase because that's what 
that function does. It takes some data and does something to it. And beyond that, we 
could do something like add numbers together. Again, not super exciting, but we could 
pass in two parameters here. On number one and on number two, we could add them together 
and then console log them out. And you would run this by using addNums, and you would 
pass in whatever two numbers you want to add there. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 263/264. function addnums, test addnums (151) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image263.png?raw=true"
  width="45%"
  alt="Function addNums." />
<img src="./images/image264.png?raw=true"
  width="45%"
  alt="Test, addNums." />
</p>

Let's give it a try real quick. Function addNums. We're going to pass in num1 and num2. 
I like putting these extra spaces in here even though that's kind of not the standard, 
but I think it makes it easier to read for me. All right, so I'm going to make var sum = 
num1 + num2. In here, we're using the plus sign to actually do addition, that's what we 
want it to do. And then I'm going to console.log sum. 

Meanwhile, I'm going to comment that out so we don't get that running as well. And then 
down here, I just need to run it with whatever numbers I want to add, addNums, 329, 419. 
Sure, you could  probably do that in your head fairly quickly. But why bother? We can 
have JavaScript do it for us, right? So, if we're going to learn how to do this 

JavaScript stuff, it might as well do something useful, like add those numbers together 
to get 728. Maybe not super useful, but you get the idea. And that's a really powerful 
thing about JavaScript is we can pass in the passing data through these variables here, 
that we can then work with within our function. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 265. example, returning data (152) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image265.png?raw=true"
  width="50%"
  alt="Example, Returning Data." />
</p>

The next thing to talk about is returning data. So far our functions have just done one 
thing, they've printed out to the console log, because that's really all we have for 
right now. We will be doing more interesting things, I promise. But for right now, what 
we have is to print out to the console log. 

But we can make functions that return something. And that in this case, it looks subtle. 
The difference is subtle because in the end, what we have is the console. So we're 
printing to the console. But here I've updated my function, I'm calling it return sum. 
And instead of just printing to the console, and returning the sum of these two numbers, 
and then I can console log that out. Again, it's just going to the console, so the end 
result isn't all that different. But there is a subtle but important difference between 
these two things. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 266.  (153) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image266.png?raw=true"
  width="50%"
  alt="." />
</p>

Let's do this quickly. I'm going to come over here and I'm going to copy my addNumbs 
function, and paste it, comment that previous code out for a moment. And instead call 
this, returnSum, num1, num2. But instead of console logging it out, I'm going to return 
it as a variable, sum. So its going to return the value here. And then it's just going 
to the console log because that's all I've got access to at the moment. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ 267/268.  (153) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image267.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/image268.png?raw=true"
  width="45%"
  alt="." />
</p>

We'll be doing more stuff later. And I can run inside the console.log, returnSum and I 
can put a 3 and a, 5 in there, whatever. And you'll see, when I run this, Over here, 
assuming I typed that all right. Then, in fact, they get an eight, and it's still going 
to the console. 

So you might wonder, well, what's the big deal here? What's the difference here between 
returning the sum and just having it print out the finished thing here? The analogy that 

I like to use is one, where you're washing your clothes. If you happen to have a washer 
and a dryer, you have two machines and those machines work together. So you put your 
dirty clothes in the washing machine. So you're feeding it in dirty clothes, dirty 
laundry, and you're putting in soap and you're putting in water in the washing machine, 
agitates it all, and runs it all together. And what it returns to you are clean, wet 
clothes, which you then put into a dryer, and the dryer will then do its function which 
will tumble the clothes with air, hot air maybe, and then returned to you clean, dry 
clothes. So you can think of returning as a machine doing something and processing 
something, doing something to it, and then returning the result to you so that you can 
then turn it over to another machine that has its special features and does what it 
needs to do.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-21">2.21 Useful Example – Step 1 (6:21)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 269. useful example - step 1 (2.21) (154) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image269.png?raw=true"
  width="50%"
  alt="2.21. Useful Example - Step 1." />
</p>

Let's take a look at a useful example. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ 270. a useful example - generating random numbers (155) ~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image270.png?raw=true"
  width="50%"
  alt="A Useful Example - Generating Random Numbers." />
</p>

This will show us something that a function can do for us in JavaScript right now, and 
that we could use in some programs that we write. That is for generating random numbers. 
Try this out. JavaScript has a random number generator, and I'm going to just give this 
a try over here on my file. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ 271/272.  (155) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image271.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/image272.png?raw=true"
  width="45%"
  alt="." />
</p>

I'm just going to console.log math with a capital M dot random (Math.random). We'll talk 
more about what that means in a little bit. But math random is going to generate a random 
number. If I go over to my browser and run it, you see that I get a number, I can keep 
refreshing my screen and I'll keep getting numbers. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 273. test, functions in js (156) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image273.png?raw=true"
  width="50%"
  alt="." />
</p>

The numbers that I get will be from zero all the way down to 0.00000000, all the way up 
to almost one. You saw a minute ago I got a 9.9 something or other. It won't go all the 
way to one. It'll go to up to 0.999999999. But it won't go all the way to one. It could 
go all the way to zero, but it won't go all the way to one. But it's somewhere in there. 
What if I wanted random integers? What if I wanted to get a random number between say, 
10 and 52 or something like that, how would I do that? I need to write a function to do 
that in JavaScript because the random number generator in JavaScript generates random 
numbers between zero and almost one. Zero inclusive, one exclusive. But if I was 
playing a game of cards and I had numbered my cards one through 52, and I wanted to make 
sure I could pick a random card, I would need to be able to pull out a 26, not as 
0.35979558399127143. That's not very helpful. I need to figure that out. 

Before we go forward with this, I should mention that the random number generator in 
JavaScript is not truly random. It's using an algorithm to generate the random number 
and it's random enough for our purposes, but it's not a truly random number. And if 
you're making a game that was making a program that really needed to be random, like 
a lottery generator or something like that, you would want to use something other 
than the built-in random number generator. But for our purposes is random enough. 
That's worth mentioning as well. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 274. example, useful example - step 1 (157) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image274.png?raw=true"
  width="50%"
  alt="Example, Useful Example - Step 1." />
</p>

Here's our first step in creating our random integer generator, is we're going to make 
a function called randomInt, and we're going to pass in a minimum number that we want 
to get, and a maximum number that we want to get in our random integer generator. 

To start with, we need to know how many values we think we should be able to get. I'm 
going to make a variable called number of values (numOfValues) and it's going to take 
max and it's going to subtract min, and it's going to add 1 to it. Think of it like 
this; if I were to run this function with five and 10, if I wanted to get a random 
number that was between five and 10 and included five and 10, the numbers I could get 
are 5,6,7,8,9,10. That's six possible values. If I take the maximum which is 10, and 
subtract 5, that gives me 5 plus 1, that would give me 6 possible values. That's how 
this actually works. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ 275/276.  (157) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image275.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/image276.png?raw=true"
  width="45%"
  alt="." />
</p>

Let's go ahead and go over to our code editor and start writing this function. I'm going 
to make a function called randomInt, and it's going to take a min and a max. I'm going 
to have a variable here, var numOfValues. That's going to be the max minus the min plus 
1. Then I can just console.log out this number of values just to make sure it's working 
right. console.log. 

When you're working with programming, you want to do this. You want to just check 
everything as many places as you possibly can just to make sure you're getting what you 
think you're getting. NumOfValues. I'm going to console.log that out. Then down here I'm 
going to run this function, randomInt. Then put in a five. I'm going to put in 10. We'll 
see, we should get a six. That's what we should get. Let's go over and check that. Sure 
enough, I'm getting a six because the possible values, if I'm going to include, I'm 
going to say I want random numbers from 5-10. I want to include five and 10, so I could 
get a 5, a 6, a 7, an 8, a 9 or 10, that's six possible values. Step 1 of this is 
correct. Then, we'll go on from there to the next step.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-22">2.22 Useful Example – Steps 2-4 (6:05)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 277. useful example - steps 2-4 (2.22) (158) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image277.png?raw=true"
  width="50%"
  alt="2.22. Useful Example 2-4." />
</p>
In the second step for a random integer generator, I'm going to actually generate my random number. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 278. useful example - step 2 (158) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image278.png?raw=true"
  width="50%"
  alt="Useful Example - Step 2." />
</p>
RandomNum here is going to be between zero and one. I'm going to take that and multiply it by the number of values and see what I get. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ 279/280.  (159) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image279.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/image280.png?raw=true"
  width="45%"
  alt="." />
</p>
Let's go ahead and add this to our function over here. We've got that in there, we can get rid of this. We know that that's working, so we know that's all good. But now I'm going to get var randomNum and have that equal Math.random. That's going to generate my random number. Then I'm going to say randomVal. I'm going to take var randomVal and have that equal randomNum times number of values. Let's just see what that gets us. console.log (randomVal).
Let's go over here and run that. Now, that's getting me numbers that are between zero and six. It won't go all the way up to six. It will get me to five point something other, but it won't go all the way up to six, and that's interesting. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ 281/282.  (159) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image281.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/image282.png?raw=true"
  width="45%"
  alt="." />
</p>
Let's see what we need to do next. Next, I'm going to use the Math.floor method to round down my random number. Now, that should get me a whole number between zero and five. I'm going to use the Math.floor and pass in this random value here. This is my number with all the decimal points. 

Let's give that a try over here. I'm going to get rid of this console.log, I don't really need that one anymore. But instead, I'm going to do var roundedRandomVal. A long variable name, you can make it shorter. I'm going to do Math.floor. Floor is a method and ceil is a method, ceil for ceiling. Floor will round it down, ceil, C-E-I-L, will round it up, short for ceiling, if that makes sense. Then I'm going to pass in their randomVal. Once again, just to see what my progress is, I'm going to console.log (roundedRandomVal). You saw I didn't have to actually type that, I just press tab because it came up in Visual Studio code. That will prevent me from getting these long variable names wrong. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 283. useful example - step 4 (160) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image283.png?raw=true"
  width="50%"
  alt="Useful Example - Step 4." />
</p>
Now when I run this, I get a two.  Now, I'm getting whole numbers, but they're not from 5-10, they're between zero and 5. Now, what we can do next is we can get our final number, and we're going to take the min and add it to that randomVal. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ 284/285.  (160) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image284.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/image285.png?raw=true"
  width="45%"
  alt="." />
</p>
For example, if our random number gave us a zero and we add five to it, we'll get a five. If we got a one and we add five to it, we'll get a six, all the way up to 10. So that will give us our random numbers between five and 10 if we add the min value to this final number here. Let's go ahead and add that in there and see what we get. Var finalNum equals min plus roundedRandomVal, and we can console.log that out. Come back and check it, and you can see now I'm getting random numbers that can go as high as 10 and as low as five, and our random number generator is actually working, which is great.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
2.23 Useful Example – Step 5
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 286. useful example - step 5 (2.23) (161) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image286.png?raw=true"
  width="50%"
  alt="2.23. Useful Example - Step 5." />
</p>
In the next step, we're going to make our random number generator, our random integer generator a little bit more useful. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 287. useful example - step 5 (161) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image287.png?raw=true"
  width="50%"
  alt="." />
</p>
We can generate random numbers, but the only thing we can do with these random numbers is see them pop up in the console, which is really not very useful. If I wanted to actually take this generated number and do something with it, I can't. All this function does currently is print out to the console. What we could do instead, is we could return the final number. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ 288/289.  (162) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image288.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/image289.png?raw=true"
  width="45%"
  alt="." />
</p>
Here, now we can return the final number and we could actually use this function somewhere useful. For example, if I had an array var foods equals square bracket cheese, chicken, grapes, hamburgers, whatever you want to put in there is fine. We could add more things to the list. But if I wanted to randomly get an element from this array, because randomInt returns a number, I know this starts with zero, 0, 1, 2, 3, so I want a random number from 0-3 in this case. 
So I could come down here and I could say console.log. Let's say foods square brackets, and in here I'm going to pass in randomInt 0, 3. Now, because this randomInt 0, 3 is going to be, because it returns final number, it's going to be a zero, a one, a two, or a three. So console.log foods randomInt, 0, 3 is going to go into the array and get me either a cheese, a chicken, or grapes, or hamburgers. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 290.  (162) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image289.png?raw=true"
  width="50%"
  alt="." />
</p>
Let's see if that works, if I typed it right. Sure enough, I got hamburgers, and then I got grapes, and then I got chicken.. I can actually use my random number generator to actually do something with another program. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
You can think of this randomInt, because this thing returns a random number, I can use that within my tool here to get something out of this array. 
Going back to the washing machine and dryer example, this is my washing machine. It's returning to me a processed number that I can then use with foods to do something. I don't know. It's not that interesting, but it's a little bit more interesting than what we've been doing so far. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
 
One last thing to look at and think about for this is that this function is pretty long. We could refactor it. What we want to return is really this Math.floor randomVal. I'm going to take that, I'm going to stick it down here. Did I select that right? There we go. I'm going to return ran, I'm going to do that. I'm going to put that in its own set of parentheses, max-min times my Math.random. I'm going to do that, and then outside of this, I'm going to add plus min. I'm going to take Math.floor. I'm going to take my max, subtract my min, and add 1. Multiply that by Math.random. I'm going to round that down and add min. Let's see if I did that right. Over here, if I run this again, I am still getting my items here. This is a shortened version of all of this stuff. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
Now, you might look at this and go, "Well, I don't really understand what's going on here." That's a great place for a comment. Here you could say something like, "Creating a random integer from min and max." Or you can put a more explicit statement in here. Sometimes taking a big chunk of code and reducing it down to one line can be difficult to understand exactly what it's doing later. But in this case, I like it. Because if you were to go looking around on the web for a random integer generator for JavaScript, you'll get functions that look like this. You'll find them on Stack Overflow and other places. Sometimes these one-line statements where everything is reduced down become very difficult to read and understand exactly what they're doing. That allows us to create a random integer generator that we then refactor down into one line of code. But by walking through the steps, you could see each step along the way and how that actually worked.
2.24 More on Functions (10:00)
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
We have a few more things to talk about in terms of functions before we're done with this lesson. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
The next thing is, that functions in JavaScript can be anonymous. One of the important things to understand about the way functions work in JavaScript, is that, functions are first-class citizens in JavaScript. Which means, you can assign a function to a variable, the way you could assign a string to a variable or a number to a variable. In fact, you can use a function wherever you can use data in JavaScript, and it's one of the very powerful features of JavaScript. 
If you'll recall, we talked earlier about the fact that JavaScript has some features that are really best in class features, for any programming language, and this is one of them. This is really a very powerful feature of JavaScript. You can actually assign a function to a variable, and that function doesn't have to have a name. It can be nameless, it can be anonymous. There are times when this is very useful, especially if you're making a function that's really only going to be used once or in one context. Then, there's really not a reason to create a named function if you're not going to use that name over and over and over again are in different places in your script. Function expressions are useful for that. They're useful for other things as we get into more sophisticated JavaScript. For right now, I just want you to be aware of what they are. We won't be using them much for a while, but eventually, you'll be using function expressions if you keep working with JavaScript. 

var greetings = function(){
console.log(“Hello from the function!”);
}

	greeting();

Produces this anonomous unnamed function assigned to the variable greeting. 

Let's actually see what this looks like in our code over here. I'm going to come over to my editor here and I'm going to leave that, that's all fine. I'm going to make a variable called "greeting" and I'm going to assign it a function. You'll see that this function doesn't have a name, it's just an anonymous function, and we could do whatever we want in here. I'm going to just for right now, just do console.log " hello from the function". My slide has something a little bit more sophisticated down there, but for right now, this will just do for us, just to see what this does. 
Then, in order to call this function again, remember we have to invoke the function, we have to call it or run it. I run "greeting" as if it were a function, which seems weird, but that's the way it works in JavaScript. Greeting parentheses. We run that like a function. 
Now, if I come over to my console over here and run this, I'm getting "hamburgers" again, then I'm getting "Hello from the function". That function is actually running. That's important to understand. Again, this is called a function expression, and it's because functions are first-class citizens in JavaScript that we're able to assign a function to a variable just as if it were data. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
The next thing to understand about functions in JavaScript, and I'm not going to demonstrate this now, but I just want to call your attention to it, because if you're looking on stack overflow, if you're looking up scripts online and seeing other kinds of things, you will see arrow functions. This is again part of ESX or ES 2015. It brought this new syntax and we'll come to it, not in this course, but in the third course, we'll actually start working with arrow functions. I want to mention them now because you'll see them around and when you look at them, you'll look at them and go, what's this? We haven't done this in JavaScript yet. I just want you to be aware that it's just a slightly different syntax for writing functions. 

Here, I have a function that should look fairly familiar. I've got a greeting, "Hello, and Good Morning". Then I've got function "capitalized" and I'm passing in a string, and then I take that string and uppercase it, and then I return in a string. This function is going to return the string upper cased. This should be fairly familiar from doing this lesson. So far we've seen this kind of thing and that's not too different from what we've seen. Whereas here, we're using the function expression, I have a variable called "Capitalized Expression". That has an anonymous function that takes a string and then it takes that string and makes it uppercase and returns it. So this variable will become the uppercase string that gets passed in when it's run. That's the function expression that we saw just a few minutes ago. 
Now, when we use the arrow functions, the arrow functions is a different syntax for a function expression. In fact, sometimes they're officially called arrow function expressions. We can make a variable capitalize arrow in any string, and then instead of the word function, we can just put in this equal sign and the greater than sign to make an arrow. We can take anyString and uppercase and return that. This becomes one line, which is one of the reasons why these arrow functions have become popular, is they really do lead to shorter code and less syntax to have to deal with. Although when you look at them, it can be a little bit harder to understand exactly what's going on here. 
But all three of these functions are actually doing the same thing. They will all return the exact same data. Again, we'll get to the arrow functions later in the third course, but for right now, I just want you to be aware that they exist and that really they're just a different syntax for writing functions. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>

The last thing that we need to talk about in terms of our lesson today on functions is 
the difference between functions and methods in JavaScript. It can be a little bit 
confusing because these two terms are basically interchangeable in JavaScript, and you've 
already heard me use the term method sometimes and functions other times. It's helpful 
to know a little bit about what the two terms mean and why they're interchangeable.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>

Essentially in JavaScript, when you have a function that belongs to an object, it's 
called a method. For example, we have the string object and there are functions that 
belong to string objects like toUpperCase or toLowerCase, and when we have a function 
like that that belongs to the string object, it's called the toUpperCase method, because 
it belongs to the string object. Or another example, with arrays we have the push method, 
which is a function that belongs to the array object. So when we push something into 
array, we're using the push method and we use the term method for that. 

Now, in reality in JavaScript, everything is an object so in that sense, every function 
belongs to an object of one sort or another. In fact, earlier on in this lesson, we 
wrote a function called doStuff. But doStuff, since it doesn't explicitly belong to 
some other object, it does belong to the window, and you could actually write 
window.doStuff and that will actually work. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ xxx/xxx.  (###) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
</p>
If we go back to our code here, and I come in here and put window.doStuff, you'll see 
if I save that and come back and test it over here, it actually functions. Because 
ultimately my doStuff function belongs to the window object. 

Now, if a function belongs to the window object, we don't often do this. Occasionally 
we do, but very rarely will we put window.doStuff in there, we'll just call doStuff. 
In that case, we'll call it a function. But when a function more explicitly is set to 
work with a particular object, we're more likely to call it a method. So that's where 
the difference in terminology comes from. But in reality, in JavaScript all functions 
are methods. So the two terms really are interchangeable. If you hear the term method 
and you're confused by that, just think, Oh yeah, that's a function, and that's fine. 
We've learned a lot about functions in this lesson, and you've already learned a lot 
of JavaScript. 

Along with the challenges, you'll get good at the JavaScript syntax and you'll get good 
at being able to make simple programs function. From here we get to start doing some 
much more interesting things where we start working with content on web pages and 
manipulating web pages. So this course only gets more fun from here. So stick with 
it and keep working on the lessons, and I can't wait to see you in the next one.

<ul>
  <li>2.24.JS-Functions (shortcut)  https://www.w3schools.com/js/js_functions.asp</li>
  <li>2.24.JS-FunctionChallenges-10thru16.pdf (download)  https://www.w3schools.com/js/js_functions.asp

<h2 id="ch3">Week Three: </h2>

<h2 id="ch3-00">3.00 Learning Objectives</h2>

<ul>
•	Identify the DOM and the relationships between elements on a web page.
•	Use document methods to access and change the DOM.
•	Use element properties to change the DOM.
•	Use the inspector in the browser to identify changes and troubleshoot problems.
•	Use event listeners and event properties to capture events.
•	Modify the DOM based on events captured.
•	Use the inspector to identify effects the program has on the web page.
•	Recognize and identify variable scope in JavaScript.
•	Develop coding best practices to keep score from creating programming errors.
•	Capture user events.
•	Change the DOM based on user events.
•	Employ appropriate logical flow control structures necessary to make the program function properly.
•	Use array and variables to manage program data.
•	Apply best practices to manage variable scope.
•	Identify and fix errors in programs, when they are not running properly.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
3.00 Module 3 Introduction
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>

Welcome to the third module on JavaScript. In this module, we'll be doing some really 
exciting stuff. We'll be digging in and learning how to actually affect elements on web 
pages. When we do that, we'll also be looking at events, will look at what happens when 
you want to capture a click or a scroll or the submission of a form or something like 
that. When we capture these events, we can then make different things happen on web 
pages. This is where the real magic is in JavaScript, and it's also the reason why 
JavaScript exists, is because it's so tightly tied into the browser. 

Now we can find JavaScript in other places other than the browser. But its main reason 
to exist is the fact that it is so tightly connected into the browser, and we'll really 
get into that, in this part of this course during this module. So I hope you have fun 
with it, and by the end you'll have learned quite a lot of JavaScript.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
3.01 JavaScript and the DOM (4:34)
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ xxx. javascript and the dom (3.01) (172) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="3.01. JavaScript and the DOM." />
</p>

JavaScript and the DOM. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ xxx. example, the web page is an object (172) ~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="Example, The Web Page is an Object." />
</p>

The DOM stands for Document Object Model. JavaScript sees the web doc ument as an 
object, and it understands it from the hierarchical perspective. The root object that 
JavaScript sees is the window itself. The window, our browser window is the root object. 
Then that has three sub-objects. The document, the location of that document, and the 
history. We're really concerned with the document, and the document breaks down into 
an HTML tag. We've seen that certainly on our documents and within the HTML tag there's 
a body tag. Then we could have whatever HTML is making up the page.

Here, I'm showing an article with a header and a paragraph and a footer, and that 
matches the HTML that's in the image here on the left. If you look at the markup on 
the left, you can see how that matches the article here, in the diagram. JavaScript 
sees the article as an object that has children. One child would be the header, and 
the header itself has a child which would be the h1. Then another child of the article 
is a paragraph. Another child of the article is the footer, which also has a child 
which is a paragraph. We can see that represented in the diagram over here.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx. example, nodes (173) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="Example, Nodes." />
</p>
These elements on the page are nodes, and JavaScript understands the relationships 
between the nodes. And we can use methods and properties to do what's called traversing 
the document and getting from one node to another so that we could affect it with 
JavaScript. 

For example, if NodeA was that article, and it has three children, you could say 
NodeA.firstChild is Node-A1, and NodeA.lastChild Is Node-A3. You can look through the 
descriptions to the left here and understand the relationships between these different 
elements. So Node-A1.parentNode, for example, would be NodeA, or we can look at the 
children of NodeA as an array, and we could say NodeA.childNodes[0] would be Node-A1. 
So on and so forth, right down through this entire list. 

We can actually use this relationship to work our way around HTML document using 
JavaScript and be able to get elements and do things with them. Now, if you're coming 
to JavaScript from another language like C++ or Java or Python or something like that, 
this is a little weird. This is strange, but really, when you think about it, 
JavaScript's tight integration in with the browser and with what happens on our document 
is really JavaScript's reason for being. Certainly we're seeing JavaScript now outside 
the browser and in other places. 

But JavaScript's main reason for being is the fact that it can do this stuff, and other 
scripting languages can't, where other programming languages can't. In 2009, when they 
decided that JavaScript was going to be the programming language for the web, it was 
going to be native to the browser, that's when this stuff really got solidified and 
everybody wanted to follow the exact same specification, and even if they were doing 
slightly different implementations of it, they were following the specification so that 
this would work with JavaScript in whichever browser you're in. It's taken a while to 
get to compatibility across browsers with JavaScript, but we're pretty close to there 
these days.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
3.02 Dot Syntax and Methods (5:21)
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx. dot syntax and methods (174) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="3.02. Dot Syntax and Methods." />
</p>
The dot syntax and methods. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
Notice we use dots or periods to separate objects from their properties or their methods in JavaScript. On the right here, you can see that we have a number of methods that are related to being able to traverse the DOM or affect the DOM. insertBefore(), we can create an element and insert it before another element. We can replace a child. We could say, "Take this child out of here." Remove a child. Append a child. We can add a new paragraph to the end of a div or something like that. Clone and node. 
We could take an entire div with all its contents and clone it and add it to the page somewhere else. We can create an element, we can create attributes, we can create a text node. These are all methods that JavaScript has built into it that will allow us to do things to the Document Object Model; to the document itself and will affect the document there. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
One of the document methods you'll use most frequently and is a good one to learn first is getElementById. getElementById is a document method or a function that belongs to the document object. Remember that's how we define methods. What we can use with getElementById, is we can pass in a particular ID, and then we can do things to that element, that will go into our document, into our DOM or Document Object Model and find that particular element and do something with it. 
We could set the style property and the color sub-property to red, for example, for this paragraph that has an ID of one. Remember, in HTML, when you have an ID, it must be unique. It must be a unique ID on the page. This is something I see as a mistake a lot of times with students learning to create webpages. They'll use an ID and the page multiple times. But the whole point of an ID is that it's unique, just like you have a student ID or a driver's license ID or some other ID with a unique ID number on it. The whole purpose of having an ID is that it is unique. Let's give this a try. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
I'm going to come over to my code editor here and you can see I've set up a page and I guarantee you it's a good idea for you to do this as well. I strongly suggest it, but I'm going to come in here and I'm going to add, I'm going to say document if I could type document.getElementById. You can see as I start typing, that it even comes right up here and I can actually select it from the list to make sure I get it right. Because you have to get the capitalization right. It's CamelCased. The get is lowercase, but E is uppercase, B is uppercase and I uppercase, but the d is lowercase. You have to get that right, otherwise, it won't work. I'm going to pass in one because it's going to match this ID here, and I can set the style.color to red. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
If I save that, and then I come back over here and you can see I have this webpage loaded up here, and it's black here. But as soon as I refresh the page, you'll see that it's turned red. Now, I don't have any code in my HTML that's doing that. It's the script that's doing that after the fact. It's really important to understand this. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
As I come down here, notice paragraph ID1 and then style color red is added here. But I didn't add that. That's not in the HTML that I added. Over here, the HTML that I have, I have the ID1, but I don't have a style attribute on here at all. When the page loaded, JavaScript loaded the paragraph the way I wrote it, and then what the scripted is it went in and found that element with the ID of one, and it added the style attribute here and set its color property to red. JavaScript is doing that on the fly after the page has been retrieved. 
Right now we're just loading it from our desktop. But you could be getting it off of the webserver, you'd be getting it from anywhere. That page, when it gets to the browser, it gets rendered by the browser and then the script runs down at the bottom of the page and affects the page after that paragraph has already been rendered. It happens so fast, you don't even really see it. But this is a really great example of a document method, getElementById, which is allowing us to go into our document, find that ID, and then effect it on the page.
3.03 DOM: getElementsByTagName(); (7:56)
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
Here's another document method that allows us to get elements on the page and do something with them. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
It's called getElementsByTagName, and I have the S and elements highlighted because a common mistake is to leave it off because it's getElementByID, but this is getElements, so this is going to get more than one element, it's going to get a collection of elements, and then we can do something with that collection of elements. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ xxx/xxx.  (###) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
</p>
Let's give this a try. Here I have my page, I have some paragraphs on the page, and I can write a script here, document.getElementsByTagName. Then I can pass in, say, a P for paragraphs. What this is going to do is it's going to go in and get all of these elements, and I can assign that to a variable, var myParagraphs equals. Now, myParagraphs is going to hold a collection of paragraphs, and if I console log that out, console.log(my Paragraphs). 
If I console log that out, let's see what I get. I'm going to come back over here to my page and refresh, and we don't see any difference here, but if I go to the console, you'll see I get an HTMLCollection of three things; paragraph, paragraph, and paragraph, and that's what's in here, and I could even fold this down and see what the different paragraphs are, it gives me some information about them, but it's giving me the collection of the paragraphs here. 
That's important to understand about this particular method. Whereas getElementByID gives me always just one thing. It'll always give me one because IDs are unique. Whereas getElementsByTagName will give me an HTMLCollection of elements that I need to then do something else with. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
If I wanted to set the color of these paragraphs to red, then I would need to use a loop because I can't apply the style color to a collection of things all at once. I have to apply them to each item in that collection. I need to use a loop to loop through each of the elements in that collection, so I'm going to use a for Loop here, and let's go ahead and do this over here rather than console log this out. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ xxx/xxx.  (###) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
</p>
I'm going to use a shorter variable here. MyParagraphs is long, I'm guaranteed to type that wrong at some point, so I'm just going to call it ps, something like that. That's fine for paragraphs. I'm going to make a for Loop, and again, remember, if you've been doing the challenges and really getting used to the syntax, you should be able to just write a for Loop. For var i equals 0 or i is less than ps.length; i plus plus and then we've got our curly braces, and in here I'm going to take each paragraph, so I'm going to say ps [i].style.color equals red. Now, if I just do this, you'll see it'll work. It'll actually go through this entire Loop. The first time through the Loop, this thing has three paragraphs and it's going to get paragraph 0. Let's give that a try. Let's run that over here. If I refresh this, you can see all my paragraphs generate. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ xxx/xxx.  (###) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
</p>
I'm going to come in here and I'm going to add alert. I'm going to use my backticks here showing where I graph, and then don't forget since that's going to be variable in dollar sign, curly brace, curly brace. To show this in Firefox.  Firefox does things a little bit differently, uses the Mozilla rendering engine, and so it renders things a little bit differently. I'm going to go ahead and open our page here in Firefox, and there's my DOM HTML, and notice the difference here. 
This one actually shows the first paragraph turns red, and then I get the alert, and then we see the second paragraph turn red and I get the alert, and then I get the third paragraph turning red, so you can actually see the Loop actually running, and usually these Loops run so fast, you don't even see them. But with the alert in there, you can actually see that that loop is running and turning the paragraphs red one at a time in the collection.
3.04 DOM: getElementsByClassName(); (5:09)
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
The next document method that we're going to look at is getElementsByClassName. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
This method will do exactly what you think it will do. It will allow us to go into our document, and get elements that have a particular class name, and put them into an HTMLCollection. So that's very useful as well. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ xxx/xxx.  (###) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
</p>
Let's give it a try real quick. Here, you can see I've added class equals special on my image over there it was blue, but whatever class you want to put is fine. It doesn't really matter as long as you set up a variable per myClass equals document.getElementsByClassName, this one here That will take all of these elements. In this case, it's just two and stick them into a collection. Then the same as before, we are going to need to use our loop to go through and change these items. For var i equals 0, while i is less than myClass.length. 
First-time to the loop, that's going to be zero. Second time to the loop, it's going to be a one, and then it'll finish.style.color equals red and that should work just fine. Let's go test it out. It turned those two classes red. Now, one more point of interest while we're here. Even if I just had one element on the page to add this class, I could give it an ID. But if I am going to use getElementsByClassName, even if there's only one, it still is going to return a collection of elements and that collection is only going to have one element in it and I still need to use a loop or some other way of getting to the element inside that collection, even though there's only one. You'll see the loop will still work. It'll just run only one time. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ xxx/xxx.  (###) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
</p>
A little bit easier way of doing this, I don't really need a loop here because I know that there's only one element in this collection, so I know it's going to be element zero. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ xxx/xxx.  (###) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
</p>
So I don't need a loop, I can just make this zero and get rid of the loop, like so. Clean that up a little bit. Now, myClass is getting elements by class name special and myClass zero, since I know there's only one, it's going to be myClass zero. It's going to be that one in the collection. I can access it through because it's treated like an array there. It's not actually an array, it's a collection of HTML elements, but I can treat it like an array to go and get element zero out of there and you'll see that will work just as well. 
But the important thing here to understand is that if you're using getElementsByClassName or getElementsByTagName or anything else that gives you a collection of elements, you have to go in and treat it as if it's a collection because that's what it is, and not just as an individual element. That's easy to forget, especially if you have only one. You're like, "Why can't I just change that one? Why can't I just use my class style color red?" Because there's only one element with that class in there. But JavaScript is getting a collection of elements even if the collection only has one element or even if it has zero elements in it, it'll still be a collection of elements. So that's an important thing to understand about getElementsByClassName and getElementsByTagName.
3.05 DOM: querySelector(); (4:58)
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
The next document method that we're going to look at is querySelector. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
Now, the history here is a little bit interesting. Because in 2009 as we said before, ES5 became the de facto standard for scripting for the web. But there was the rise of a have a library called jQuery that became popular and it remains popular to this day. Less now than it was, but it's still a popular library that made it getting elements in the DOM and doing things with them  easier. An API that allows us to use querySelector and querySelectorAll which we'll also look at to get elements from the DOM. And it's a little bit more convenient but it works a little bit differently than the older get element by ID, get element by tag name, get element by class name methods. 
So these are newer methods, and they're very useful, but they work a little bit differently. And because of the introduction of these methods, jQuery is not nearly as necessary as it used to be. And what we'll still learn jQuery, we'll be learning that in the second course in specialization. But now we can actually get elements into our DOM a little bit easier than we could just with the older methods. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ xxx/xxx.  (###) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
</p>
Okay, so let's take a look at querySelector and the way that works. So over here I have a document, and I have a div with an id on it, and then inside there I've got a paragraph for the class. Well, I could do something like this. var myText = document.querySelector. And then what I would pass in is actually instead of just some class, I would put either dots or I could put .someclass. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
So what's different here is before we didn't use the CSS syntax. Now we have to use the CSS syntax with querySelector. Or I could even be more specific and I could say go find #special.someclass. So get to someclass inside the id="special". And what's nice about this is that query selector will always return the first element that it finds that matches what you pass in here. So even if I had another paragraph with some class on it, this will always only return one thing to my text. myText.style.color = "red". And if I go over and test this document, and again I recommend, that you give this a try yourself. You can see that it's trying that paragraph red. 
Now if I were to go in here and add my class, “someclass” to another element, you'll see it still only affect the first paragraph. When you pass stuff in, you're passing in the CSS syntax #special instead of just special. Or .someclass, instead of just someclass, that's important with querySelector. Okay, great. Let's take a look at the querySelectorAll method in the next lesson.
3.06 DOM: QuerySelectorAll(); (6:10)
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
The querySelectorAll method does what you would think it would do, is that it allows you to grab a group of elements again, but this time using the newer, more updated DOM API querySelectorAll. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
Let's give that a try really quickly here. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ xxx/xxx.  (###) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
</p>
Over here, I've got my div id special and I've got some paragraphs in here, and I can do something like var myText equals document.querySelectorAll and with that querySelectorAll. I could pass in here in quotes, I could pass in pounds special p, and that's going to get me all of the paragraphs that are inside this div special. 
So I can go into my document and find a particular group of elements somewhere in my document. But again, with this, we're going to need a for loop. For var i equals 0, where i is less than myText. Length; i++. Then I can do myText square bracket i.style.color equals red. Here we go. Save that and then we should be able to test it over here and see, when I refresh the page, it is turning all those paragraphs red. Just one more time to just drive this home, noticing here when I go look in that div, it's added style color red to each one of these paragraphs. That's what it's doing, it's going into special and finding the paragraphs and affecting the DOM after the page, after the HTML initially loaded. It's really important to understand that. 
So querySelectorAll will allow us to get groups of elements and then we would loop through them to affect them one at a time. So far we've talked about five document methods. Three of them are older, Document getElementById we still use that quite a lot. Document getElementsByTagName and document getElementsByClassName you might use this less often now because now we have the newer methods, querySelector and querySelectorAll. But these are just some of the document elements that allow us to add elements to the page. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
Next, I want to talk about working with properties. We've already seen this a little bit. We've seen element.style.color. So we're going in and we're getting that element, whatever the element is, we've got that element, whether it's paragraphs or whether it's a div; whatever it is, we're getting that element with our document methods, we're getting those elements and then we can apply the style property. 
We can get the style property and the color sub-property and set it to whatever color name we want. There are other properties that we can use. There are a number of them. Some of the more popular ones are ones that we use more frequently are innerHTML. We'll be seeing that one quite a bit and className is really useful so that you can actually take an element and apply a class to it. This is useful in modern JavaScript because CSS has become so powerful. 
Now, we can put animations in CSS, and then when we want to animate something, we can use JavaScript to add that class in CSS that has the innovation and the innovation will take place on the screen. That's a really great way to create interactive for animated elements on a web page. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
So we have the document methods, and now we have element properties that allow us to work with the properties of certain elements. But there are also element methods or element functions and those are also useful. For example, .setAttribute, we can pass in an attribute name and then set its value. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ xxx/xxx.  (###) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
</p>
Back here we could set the className by using the className property. Here we could set the className by passing in class and then passing in a value. But we can pass in the value there or we could do something else; we could use an anchor tag, we could set the href attribute and set its value. Or we can remove an attribute or we could get an attribute and do things with it. Notice that methods are distinguished by the fact that they have parentheses. 
So when you're using a method or a function, it has parentheses, whereas the properties don't have parentheses, they have an equal sign and then the value. So that's how you can tell the difference between a property and a method. Let's see what else we can do with this. This may be a little bit confusing at the moment, but I promise that as we practice this stuff, it'll start to make more sense. But it does take a little bit of getting used to, all of these methods in properties for working with our document to affect our web pages.
3.07 innerHTML (4:56)
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
Next, we'll take a look at one of the element properties that we just talked about in the previous video and see how powerful it is. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
And that's innerHTML. And if you look at this image here, you can see I have a div with an id="special", and I can use any of my document methods to go in and get that div. And then I could use innerHTML to actually change the contents in that div. I can replace these contents with something else entirely, completely new, completely different. And that's something else could have HTML in it. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ xxx/xxx.  (###) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
</p>
So let's see what that looks like. Over here, I have my div id="special", and I have these three paragraphs in here. But down here I could say, var myDiv = document.getElementById. With this version, we're not using the pound here. We're using the older getElementById. We can switch that in a minute just to see what that looks like. But then I can say, okay, I've got that element, myDiv.innerHTML =. This is an element property, so we use the equal sign, and then inside quotes, I can create a completely new piece of content to stick in there. That's my </p> there. 
Okay, great, so now when I run this, you'll see over here, It's still red from before, but that's okay. Those paragraphs are going to get removed and replaced with the new paragraph. Look at that. 
And if I come down here and look inspect in my body, and look at div id="special", there's only one paragraph in here in my inspector. Whereas if I were to do View Page Source, you'd see three paragraphs in there. Because when the page loaded, it had three paragraphs, and then the script ran and it removed those three paragraphs and put this one in instead. And that's what JavaScript is doing. Now, here, I'm using getElementById('special').

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ xxx/xxx.  (###) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
</p>
I could also do querySelector. But if I use this one, then I would pass in #special. You see the difference there? This is the newer method, and it uses the CSS syntax to get to that element. But this will work just the same. If I go back and refresh this page, you'll see it'll do exactly the same thing. It'll get my new paragraph and put it in there. So you could use whichever document method you want. Once you get that element, then you can use your element properties to affect the element here. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
Now, I'm putting this all inside of this div here, but I don't need to use the variable. I could just do document.getElementById('special') and then put this, Here, it just makes for a very long line. So it's kind of helpful, and that'll work. It's kind of helpful to have the variable, but you don't have to have it. I can just go, document.querySelector('#special').innerHTML, and then set my property right there. And that'll work just as well. There's my new paragraph. So that's using the innerHTML. We could use this in lots and lots of places to get elements on our page and then replace those elements with completely new elements. And you can put more HTML in there. We could put an entire document of HTML inside this div. Not just one paragraph, but you could put articles, you can do all kinds of stuff, images. All kinds of things can go in there using innerHTML.
3.08 className (6:13)
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
The next element property that I want to show you, which is extremely useful is the class name element property. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
So let's take a look at how this one works. Here I have a div with some paragraphs in here, and I'm using my query selector to get the first paragraph. Because remember, instead of returning a collection, query selector returns the first one that it finds. So it's going to go in here and look for first paragraph. And then I'm going to take that first paragraph and I'm going to use the class name, element property to set the class to blue. And up here I've added style and I've added a class blue here to my document. So let's see how this works. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
I'm going to go over to my page over here and you can see I've added up here, a rule here to set for anything that has the class blue here. So let's come down here. I'm going to call this Var firstPara equals document.querySelector. And remember, we have to use the CSS syntax. In this case, it's just a " p" because it's just a tag selector, but I'm going to go get that first paragraph. Now I've got three paragraphs, but remember querrySelector just returns the first one. And then I'm going to say, okay, firstPara, Set the class name. And you can see here there's one called classList. I'm just showing you a few of the document, select the document properties that are super useful, but there are plenty of other ones that you can look up and work with as well. Class name equals blue. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ xxx/xxx.  (###) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
</p>
So now when I run this, come back here, click on My document here. I've got my three paragraphs, but when I refresh the page, it turns the first paragraph blue. And if I come down here and look at this, what is it actually done there, but it's added class equals blue on to that paragraph. Sure, I could have set the style color property to blue. But adding the class blue is even more powerful, because even though in both cases and just setting the color. I could have a lot more declarations in this class up here, that would do all kinds of things that could be adding an animation. I could be doing all kinds of really cool stuff, and we'll get to do some of those things in this course. So, hold on to your hat, because it's coming. 
But first I just want to introduce the basic concepts to begin with. And this is a super useful one, using the class name property to set a class that already exists on the page. It's just really, really powerful. Back to our slides here, we've looked at a few of the element properties that we can set, the style property with its sub properties for our different CSS features. We can use that one, we can use the inner HTML property, that's extremely powerful for replacing HTML inside of any element. And then there is the class name property that allows us to put a class name on things. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
The next thing I want to look at really quickly is some of the element methods. Remember these are properties because they've got the equal sign and then a value, but we also have element methods. And the first one we'll look at is setAttribute. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
So here I have a form and let's just do this one really quickly here. I have a form and I'm going to say var myCheckbox equals document.get element or I can do a querySelector. QuerySelector input. And then I'll get my first input fields here. And then I could do okay, myCheckbox.setAttribute, and set attribute takes two parameters. I'm going to say what is the attribute that I want to set? In this case it's checked, and I'm going to set the value which is also checked. Checked, checked, and that's the way. What that will do is it'll come in here and it's going to set a checked attribute and set it to checked, which will make the check box checked by default. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ xxx/xxx.  (###) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
</p>
So if we go over and view the page, currently, without having set that checkbox, you can see I've got a checkbox here but it's not checked. When I refresh the page, it comes up as checked by default. And if I come down here and look at this, You can see checked equals check that added that attribute into my HTML here. 
Set attribute can be used for any number of attributes. You want to set an image source on an element. You could use this you want to change the HREF on a link. You could use this any attribute can be accessed with set attribute. And you could set it to whatever value you want to set it to. And that is another very powerful tool that allows us to change content on our webpages.
3.09 Creating Elements and Text Nodes (5:04)
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
I have shown you a few of the document methods, the element methods and the element properties in this lesson and there are lots more. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
There are many more that you can use to do all kinds of interesting things to your pages. But I think it's helpful to see just a few to begin with, to see how those work and to experiment with those in a limited way and then add more features and methods and all that stuff as you go along. I do want to show you just a few more in this lesson just because I think it's helpful to just see that there are different ways of doing things in JavaScript. This one I want to show you is a way of creating elements and text nodes in JavaScript and then adding them to the page. It's an interesting process. Again, we've used innnerHTML and we can use that to also change content on the page, but this is just a different way of doing it. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
Here I'm going to make a variable var myTag and I'm going to say document.createElement. What am I going to create? I'm going to create a paragraph. This makes a new paragraph and puts it into myTag. Create element is a document property that makes a new element. Then I'm going to make a new text node, var myText equals document.createTextNode, here's a new paragraph. I'm going to make the text node. JavaScript creates a text node, we create the paragraph, we create the text node and then we're going to say myTag.appendChild, myText. That takes the paragraph that we just created, the text node, this text and sticks it into the paragraph tag that we created. All of this is just happening in memory in JavaScript. Then we have to actually put it on the page. I'm going to get my div here, var myDiv equals document.querySelector div. That's going to go find the first div on the page. Then I can say myDiv.appendChild, myTag. We're doing a multi-step process here, where we're creating a paragraph, we're creating some text, putting the text in the paragraph and then going and getting our div and appending it to the end of the paragraph here. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
Let's see if I did this right. If I come back and do this over here and refresh, you can see that my first paragraph is here and a new paragraph has been appended inside the div. It's been added to the div here and JavaScript is doing that through this process. Could I have just used innerHTML and added and changed the contents of this div so that it had these two paragraphs? Sure, I could have done it that way. But sometimes it's useful, this seems like a convoluted, complicated way, but sometimes it's useful to actually create the elements using the document method, create element, to create content, to stick in those elements, and then to append them to the page in particular places. Sometimes it's useful, and sometimes a better way to go than using innerHTML in certain circumstances.
3.10 Removing Elements (3:18)
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
One last method that I want to show you in this lesson is how to remove an element from another element. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
Again, we could use innerHTML and just replace all the contents all at once, but sometimes removing elements is useful. Let's take a look at this example really quickly. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
Here I have a div with two paragraphs in it, and I'm going to go ahead and get that div and put it into a variable, var myDiv, and assign a document.querySelector('div'). So that'll go get the first div on the page, which there's only one, so that's nice and easy. Then I could do myDiv.removeChild, that method. Which child am I going to remove? Well, I'm going to say myDiv.children[1]. What that's going to do is it's going to go into myDiv, look at its children, and find child number 1. Remember, this is child number 0 here. That's zero, this is one. That will actually go and remove this second paragraph from this div. Put a semicolon there, save that, and then let's go over to our browser here. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
You could see I've got the two paragraphs there, when I refresh the page, that second one is gone. Down here you'll see it's not in here anymore. It's been taken out. JavaScript removed it. Removing elements using the remove child method is a really useful tool for removing elements from the page, if you need to do that. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
Here we've seen a lot of different methods that we can use on our webpages to do all kinds of things. We've talked about some of the document methods, some of the element methods, and some of the element properties that we can use to go in and affect content on our page. 
Remember, JavaScript sees the page as this tree of objects, starting with the window, and building down from there. We can traverse that document and find elements on there, and then affect them using these different methods and properties, and that's how we're going to create all kinds of interactive elements in our webpages.
•	3.10.JavaScript-and-the-DOM.html
https://www.coursera.org/learn/javascript-basics/supplement/DCOHD/additional-resource
https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction
•	3.10.JavaScript-DOM-Challenges.pdf
https://www.coursera.org/learn/javascript-basics/supplement/Jjf7e/javascript-dom-challenges-17-21
3.11 Capturing Events with JavaScript (5:16)
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
Capturing Events with JavaScript. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
Events happen. Users will click on something, they'll scroll the page, they'll submit a form. Events happen on webpages. And when events happen, JavaScript can capture them and then they can do something with those events. When we combine this with manipulating the document, like we saw in the previous lesson, this is where a lot of the power of JavaScript really happens. Once we've talked about how to capture events and handle them, you have all of the basic pieces of the puzzle to make interactive webpages. Because we can use our logic float structures, sequence, selection, loop, along with our document methods and our element methods and properties to change elements on the page when events happen. And that's how we can get interactive webpages. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
Let's take a look at this very basic example. Here I have a webpage with a button on it. And when you click the button, it's going to pop up an alert saying that you clicked the button, something that shows that you actually clicked the button. 

So let's go over and do this and try this out. Here you can see I have a webpage, I have a button on the webpage, it says Don't Press Me. And I'm going to grab that button using my document element methods. So I'm going to make a variable var btn, and I'm going to assign it document.querySelector, Button. And that'll get that button. There's only one button on the page, so it's easy to get that one button. And it's going to assign it to button, to btn there. 
And then I'm going to make a function. Remember, we talked about functions. I'm going to make a function called ouch, And all that function's going to do is do an alert, I told you not to press me. You can put whatever you want in there, that's fine. And then I'm going to say, okay, btn.onclick run this function ouch. So that's going to actually run the function using on the button. And we're using here a special property that will capture the click event. So let's do that really quickly, let's see if this works. 

If I come over here and refresh the page, if I click Don't Press Me, I get an alert that says I told you not to press me. So I'm capturing that event of the clicking of the button. And the way I'm capturing that event is with the onclick property. One thing to notice is that I define this function, and when I assign the function to that property, notice I didn't put the parentheses at the end here. If I did, then that function would run right away, it would run immediately. So if I put parentheses here, you'll notice that it's not going to wait for me to click. Instead, it's going to run right away. 

So if I come over here and refresh this page, you'll see I get the alert without even clicking the button. So when I use the event property with the function that I've created this way, I do not add the parentheses for the function there. I just reference that function by name, ouch. And it will then run that function when the event runs. Now, you don't have to define a function here. We can actually just use an anonymous function here. 

So I could say function, parentheses, curly braces, and just stick the alert in here, And get rid of this altogether. And frequently, when you're using something like this, you're only going to run this on this particular button in this circumstance. So there's not really a reason to create a named function that you could use over and over again in this case if you're only going to run this in this one case here. But let's see if this works. Refresh, Don't Press Me, and I'm getting the alert. So I can use the anonymous function to do that.
3.12 Event Listeners (5:09)
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>





the end.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ xxx/xxx.  (###) ~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
<img src="./images/imageXXX.png?raw=true"
  width="45%"
  alt="." />
</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xxx.  (###) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p align="center" width="100%">
<img src="./images/imageXXX.png?raw=true"
  width="50%"
  alt="." />
</p>
-->
<!-- 1-21-2024 11:45am -->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ xx.  (##) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!-- TO ADD A VIDEO LINK WITH HEIGHT, WIDTH & BORDER
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
-->
<!-- GITHUB MARKDOWN - CHEATSHEET
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#links
-->
