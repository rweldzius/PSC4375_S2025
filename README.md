# PSC 4375-01: Quantitative Social Science (Spring 2025)

## Table of Contents

  * [Course Description](#course-description)
  * [Expectations](#expectations)
  * [Course Objectives](#course-objectives)
  * [Prerequisites](#prerequisites)
  * [Grading](#grading)
  * [Collaboration](#collaboration)
  * [Tutorials](#tutorials)
  * [Problem Sets](#problem-sets)
  * [Exams](#exams)
  * [Final Project](#final-project)
  * [Flow of the Course](#flow-of-the-course)
  * [Required Applications](#required-applications)
  * [Course Policies](#course-policies)
  * [Office Hours](#office-hours)
  * [Schedule](#schedule)
  * [Helpful Resources](#helpful-resources)
  * [Acknowledgements](#acknowledgements)
    
## Course Description

How does class size affect educational outcomes? What changes individuals' attitudes on gay marriage?  What is the best way to predict election outcomes? What drives the onset of civil wars? Social scientists have tackled these questions (and numerous others!) using quantitative data and...**quantitative methods**. This course will equip students with essential analytical tools for conducting similar social science research, including causal inference, measurement techniques, and prediction models. Mastery of these methods is crucial for understanding complex social phenomena, enabling students to produce robust, reliable research and make informed decisions in their respective fields.

Beyond academia, leaders in government, private firms, and non-profits continue to invest heavily in data scientists to learn about their clients, users, and platforms. Data scientists employed at these respective institutions are essentially applied social scientists and utilize many of the same methods you will learn in this course.

So, you might be asking yourself, how is this course different from PSC 4175 "Intro to Data Science" or ECON 3137 "Intro to Econometrics" or STAT 1230 "Intro to Statistics"? Great question! There is certainly plenty of overlap. In the latter two courses, you might receive more attention to the mathematics that underpin the theory. In the former (taught by Prof. Weldzius), the focus is more on predictive models of data science. Similar to these courses, you will have some exposure to both theory and prediction; but throughout the course we will apply these methods to important research in the social sciences. If you learned one of these theories or methods in a previous course, use this time to perfect your understanding and seek new insights from its research applications.

**Required Book**: Imai, Kosuke and Nora Webb Williams. 2022. *Quantitative Social Science: An Introduction in Tidyverse.* Princeton University Press. [[Supplementary Material](https://github.com/kosukeimai/qss/tree/master)].

**Class time and location**: M/W/F 12:50-13:40 in Bartley Hall 032.

[Back to ToC](#table-of-contents)

## Expectations

In this course, you will be expected to

 * complete four problem sets,
 * complete ten weekly tutorials,
 * take two take-home, open-book exams, and
 * write one final data analysis .

## Course Objectives

In this course, you will learn to:

 * Evaluate claims about causality
 * Summarize and visualize data
 * Be able to use linear regression to analyze data
 * Understand uncertainty in data analysis and how to quantify it
 * Use professional tools for data analysis such as R and RStudio

[Back to ToC](#table-of-contents)

## Prerequisites 

Most students will take PSC 1900, which provides a general overview of research methods in the social sciences, but probably little exposure to quantitative methods. Students with previous statistics exposure (e.g., AP Statistics or similar) or a solid background in high-school level math should also be prepared for the course.

We will assume a basic familiarity with high-school algebra and a working knowledge of computers. If you are unfamiliar with downloading and installing software programs on your Mac or PC, you may want to allocate additional time to make sure those aspects of the course go smoothly. In particular, I have developed Problem Set 0 to guide you through installing R and  to give you a sense of the tools we will be using. Previous experience with statistical methods and computing (Stata, R, SAS, SPSS) is helpful, but not required. You can always get in touch with me for additional help on these issues.

No matter your background, you should be prepared to engage the class material on a regular, almost daily basis even beyond the time dedicated to assignments and exam review. Furthermore, you should feel comfortable with engaging in real-life data analysis using statistical software. I will guide you through that process, but it may be unfamiliar and therefore challenging. You should especially take this course if you plan to use quantitative data at all in a senior thesis project.

[Back to ToC](#table-of-contents)

## Grading

You (the student) and I (the instructor) should care the most about what you learn, not what numerical/letter summary of that learning you get at the end of the semester. So I would love to not have grades at all, but unfortunately we humans are very good at procrastinating on our good intentions when there is no incentive not to. Thus, we have grades to help solve this commitment problem and to encourage you to put effort into learning the course material.

Here is how each portion of the course contributes to the overall grade:

| Category | Percent of final grade | 
|:-----|:-----:|
| R Tutorials | 10% |
| Four Problem Sets | 40% |
| Exams | 30% |
| Final Project | 20% |

You will use Blackboard for submission of the various assignments throughout the semester. 

**Bump-up policy**: I reserve the right to “bump up” the grades of students who have made valuable contributions to the course in the lecture, tutorials, and/or discussion/CampusWire. This also applies to students who show tremendous progress and growth over the semester.

Letter grades are determined as per the standard Villanova grading system:

  * A: 94+
  * A-: 90-93
  * B+: 87-89
  * B: 84-86
  * B-: 80-83
  * C+: 77-79
  * C: 74-76
  * C-: 70-73
  * D+: 67-69
  * D: 64-66
  * D-: 60-63
  * F: <60

**Blackboard Gradebook**: although your grade for each assignment will appear on Blackboard, I will not use Blackboard to estimate your final grade. Blackboard will not calculate your final grade or estimate your final grade. I will calculate your final grade according to the percentages I highlight above, which you can also do using a simple Excel spreadsheet. 

[Back to ToC](#table-of-contents)

## Collaboration

You are effectively learning a new language in this course. You should not assume that you can do this all on your own. Thus, for every problem set cycle (there will be five cycles) I will split you into equally-sized groups. You will sit with your group for each class and will do any in-class activities with these classmates. You will be each other's primary contacts for issues relating to the problem set. I recommend you setup your own channel in Campuswire to chat with each other or exchange emails/phone numbers. I also recommend you arrange a time to meet before the problem set is due to check your answers with each other and troubleshoot any problems with R code. I will announce the groups and a seating chart at the start of each cycle (e.g., Monday 1/20 for Pset 1). 

[Back to ToC](#table-of-contents)

## Tutorials

I will assign short weekly tutorials to assess your knowledge of the material covered in the reading and lectures that week. You will complete these in RStudio. While you are expected to complete them on time, they will be graded based on completion not on how correct the answers are. They will be due Tuesdays by 11:59PM ET. Late submissions will be marked as incomplete; **no exceptions**.

**NOTE**: For tutorial 1-6 you should scroll down and find the "QSS Tidyverse Tutorial" version. For tutorials 7-10, you can use the "QSS Tutorial" version.  

At the beginning of the term, these tutorials will focus on getting up to speed in R and over the course of the term, they will focus more on the theoretical aspects of data analysis.

Use [these instructions](https://rweldzius.github.io/PSC4375_S2025/tutorials/psc4375_tutorial_setup.html) for getting the tutorials setup in RStudio. 

[Back to ToC](#table-of-contents)

## Problem Sets

Only reading about data science is about as instructive as reading a lot about hammers or watching someone else wield a hammer. You need to get your hands on a hammer or two. Thus, in this course, you will have 4 problem sets to complete throughout the semester that will give you an opportunity to apply the statistical techniques you are learning. They will usually be focused on data analysis in general and will often involve a real dataset.

I encourage students to rely on peer working groups as they work on these problem sets, but each student will submit their own work individually.

The schedule for the problem sets will be:

| Problem Set | Topic | Release Date | Due Date | 
|:-----|:-----|:-----|:-----|
|  1 | Randomized Experiments | Fri (01/24) 12:00PM ET | Fri (01/31) 11:59PM ET|
| PSet 2 | Summarizing Data | Fri (02/07) 12:00PM ET | Fri (02/14) 11:59PM ET ❤️|
| PSet 3 | Regression | Fri (03/14) 12:00PM ET  | Fri (03/28) 11:59PM ET |
| PSet 4 | Inference | Fri (04/04) 12:00PM ET | Wed (04/16) 11:59PM ET |

**Late submissions**: For each day your submission is late, your score will drop by one entire letter grade. After three days you will receive a zero. There will be no exceptions. You have one week to complete the problem set so do not wait until the last minute to begin. 

**Grace policy**: When calculating the final problem set portion of the overall grade, I will drop the lowest of the four scores and use the remaining scores. Thus, if you have an emergency that forces you to miss one problem set, your grade will not be severely affected.

[Back to ToC](#table-of-contents)

## Exams

There will be two take-home exams during the course. These exams will be similar to a problem set in format and in the sense that it will be open book and open internet, but you **will not** be allowed to collaborate with other students or be able to communicate with any humans about the exam. You will be given several days to complete the exam. I will provide more information about the exam as it approaches.

| Exam | Release Date | Due Date | 
|:-----|:-----|:-----|
| Exam 1 | Fri (02/21) 12:00pm ET | Fri (02/28) 11:59pm ET|
| Exam 2 | Fri (04/25) 12:00pm ET | Fri (04/25) 11:59pm ET|

**Late submissions**: For each day your submission is late, your score will drop by one entire letter grade. After three days you will receive a zero. There will be no exceptions.

[Back to ToC](#table-of-contents)

## Final Project

The final project for the course will be a data analysis project where students will find a dataset of interest, state an interesting research question about that data, and answer this question using that data. Students may work individually, or can work in groups of up to 3 students.

| Milestone | Due Date | 
|:-----|:-----|
| Proposal | Wed (03/12) by 11:59PM ET |
| Draft Analyses | Mon (04/28) by 11:59AM ET |
| In-class Presentations | 04/28, 04/30 |
| Final Report | Fri (05/09) by 11:59PM ET | 

**Late submissions**: For each day your submission is late, your score will drop by one entire letter grade. After three days you will receive a zero. There will be no exceptions.

[Back to ToC](#table-of-contents)

## Flow of the Course

The course will follow a basic flow each week, with small differences if a homework or problem set is due or not.

 * Monday: Lecture 1 and discussion
 * Tuesday: Complete R tutorial
 * Wednesday: Lecture 2 and discussion
 * Friday: In-class practice with R. Note that Exams/Problem Sets are due on Fridays.

[Back to ToC](#table-of-contents)

## Required Applications

### R and RStudio

See pp. 8-9 in QSS for directions on how to download R and RStudio. More details follow:

 1. Download and install the most recent version of [R](https://cloud.r-project.org/). There are versions available for the Windows, Mac, and Linux operating systems. On a Windows machine, you will want to install using the `R-x.y.z-win.exe` file where `x.y.z` is a version number. On a Mac, you will want to install using the `R-x.y.z.pkg` file that is notarized and signed.
 2. With R installed, download and install [RStudio](https://rstudio.com/). RStudio is a type of "integrated development environment" or IDE designed for R. It makes working with R considerably easier and is available for most platforms. It is also free.
 3. Install the packages we will use throughout the semester. To do this, either type or copy and paste each of the following lines of code into the "Console" in RStudio (lower left panel by default). Make sure you do this separately for each line. If you are asked if you want to install any packages from source, type "no". Note that the symbols next to `my_package` are a less than sign `<` followed by a minus sign `-` with no space between them.

```
my_packages <- c("tidyverse", "usethis", "devtools", "learnr", "tinytex")
install.packages(my_packages, repos = "http://cran.rstudio.com")
remotes::install_github("kosukeimai/qss-package", build_vignettes = TRUE)
```
 
 4. For some things in the course, we'll need produce PDFs from R and that requires something called LaTeX. If you've never heard of that, it's completely fine and you should just run the following two lines of R code:

```
install.packages('tinytex')
tinytex::install_tinytex()  # install TinyTeX
```

### Blackboard

This is the course management software used at Villanova University to support course learning. It is clunky, not user-friendly, and is thankfully on its way out soon. For these reasons, I will only utilize Blackboard for you to submit your assignments and to see your grades/feedback. NB: Blackboard will show your grade for each assignment but will note calculate your final grade. 

### Campuswire

I have set up a Campuswire workspace for our use this semester to help us better communicate with each other. You will need to create an account and join our workspace by following [this link](https://campuswire.com/p/GD7AC473D). The secret PIN can be found on the first announcement on Blackboard. You are encouraged to adopt these [Slack etiquette tips](https://slack.com/blog/collaboration/etiquette-tips-in-slack). Most likely, you will utilize a similar communication system at a future job, so use this time wisely as you adopt best practices. 

Here are the channels you should see upon joining the Campuswire workspace and that we will most often utilize:

  * Class feed: A space to post questions and respond to other posts. When leaving a post on the class feed, be sure to choose the appropriate category (e.g., Problem Set 1). 
  * #announcements: a space for all course announcements from Prof. Weldzius
  * #class-chat: a space for students to engage in conversation


### GitHub

I have created a [GitHub](https://github.com/rweldzius/PSC4375_S2025/tree/main) repository to prepare and share all course-related content. This very syllabus is available as the repository's README and all links are connected to the appropriate folders, sub-folders, and files in this repository.

### Microsoft Copilot

Villanova has an enterprise site license for Microsoft’s Copilot chat application, which is built off of Open A.I.  Copilot is available to all faculty, staff, and students [here](https://copilot.microsoft.com).



[Back to ToC](#table-of-contents)

## Course Policies

### Attendance

Students are entitled to one excused absence for any reason that may contribute to their personal wellness. Students must advise the instructor by email before class of their intent to utilize a Personal Day as the reason for their absence. A Personal Day will not be approved retroactively. Students may, but are not required, to provide additional information regarding their absence. Additionally, a Personal Day may not:

  * be used immediately preceding or following a University holiday or break period;
  * be used on days when exams, presentations or other major assignments are scheduled.

A Personal Day does not grant an automatic extension for items due. Students remain responsible for all assignments, exams, presentations, etc. due on that date. It is in the instructor’s discretion to determine whether any extension is appropriate given individual circumstances.


### Late Assignments

Every problem set and exam is assigned on a Friday and due on Blackboard by **11:59pm Villanova time on the following Friday**. Problem sets and exams should be submitted via Blackboard. Late submissions will be **penalized 1 full letter grade for each day late**. After three days, problem sets and exams will no longer be accepted and will be scored 0.

### Cell Phones, Laptops, Tablets, etc.

You are expected to bring your laptop to class in order to take notes and work through the problems along with Prof. Weldzius. You are asked to silence your cell phone / tablet / smart watch before class begins.

### Academic Honor Code

All students are expected to uphold Villanova’s Academic Integrity Policy and Code. Any incident of academic dishonesty will be reported to the Dean of the College of Liberal Arts and Sciences for disciplinary action. You may view the [University’s Academic Integrity Policy and Code](https://www1.villanova.edu/villanova/provost/resources/student/policies/integrity/code.html) for a detailed description.

If a student is found responsible for an academic integrity violation, which results in a grade penalty, they may not WX the course unless they are approved to WX for significant medical reasons. Students applying for a WX based on significant medical reasons, must submit documentation and their request for an exception will be considered.

Collaboration is the heart of data science, but your work on your assignments should be your own. Please be careful not to plagiarize. The above link is a very helpful guide to understanding plagiarism. In particular, while students are invited to work on problem sets together, collaboration is prohibited on the midterm and final exams.

AI (e.g., ChatGPT, Copilot) is an essential tool in the data scientist's toolkit, and acceptable resources for completing the assignments and learning concepts at a deeper level. However, there are specific ways in which its use is allowed:
 * Always include a log of your AI use (print the output or include a link if using ChatGPT)
 * You may use AI to help troubleshoot an error in your R code.
 * You may **not** use AI to solve the problem. This will result in an automatic zero and an academic integrity investigation. This is a **zero tolerance** policy.
 * If you use AI to hlep troubleshoot an error but do not include your log file or link to ChatGPT (ie, no citation is included) you will also receive a zero and an academic integrity investitation. 


### Office for Access & Disability Services (ADS) and Learning Support Services (LSS)

It is the policy of Villanova to make reasonable academic accommodations for qualified individuals with disabilities. All students who need accommodations should go to Clockwork for Students via myNOVA to complete the Online Intake or to send accommodation letters to professors. Go to the LSS website http://learningsupportservices.villanova.edu or the ADS website https://www1.villanova.edu/university/student-life/ods.html for registration guidelines and instructions. If you have any questions please contact LSS at 610-519-5176 or learning.support.services@villanova.edu, or ADS at 610-519-3209 or ods@villanova.edu.

### Absences for Religious Holidays

Villanova University makes every reasonable effort to allow members of the community to observe their religious holidays, consistent with the University’s obligations, responsibilities, and policies. Students who expect to miss a class or assignment due to the observance of a religious holiday should discuss the matter with their professors as soon as possible, normally at least two weeks in advance. Absence from classes or examinations for religious reasons does not relieve students from responsibility for any part of the course work required during the absence. https://www1.villanova.edu/villanova/provost/resources/student/policies/religiousholidays.html.

[Back to ToC](#table-of-contents)

## Office Hours

  * Wednesdays 2-4pm in SAC 257
  * You must make an appointment for Wednesday office hours here: https://calendly.com/weldzius/officehours

[Back to ToC](#table-of-contents)

## Schedule

| Week | Date | Topic | Assignment Due |
|:----|:-----|:------|:------|
| [0](#week-0) | 01/13 | Introduction to QSS | F: [PSet 0](https://github.com/rweldzius/PSC4375_S2025/blob/main/psets/psc4375_s25_pset0.Rmd) |
| [1](#week-1) | 01/20 | Causality: Randomized Experiments | T: QSS Tutorial 1 |
| [2](#week-2) | 01/27 | Causality:  Observational Studies | T: QSS Tutorial 2 <br /> F: [PSet 1](https://github.com/rweldzius/PSC4375_S2025/blob/main/psets/psc4375_s25_pset1.Rmd)  |
| [3](#week-3) | 02/03 | Measurement: Descriptive Statistics  | T: QSS Tutorial 3  |
| [4](#week-4) | 02/10 | Measurement: Sampling & Bivariate Statistics | T: QSS Tutorial 4 <br /> F: [PSet 2](https://github.com/rweldzius/PSC4375_S2025/blob/main/psets/psc4375_s25_pset2.Rmd) |
| [5](#week-5) | 02/17 | Prediction: Elections & Regression  | T: QSS Tutorial 5  |
| [6](#week-6) | 02/24 | Prediction: More Regression |  F: [Exam 1](https://github.com/rweldzius/PSC4375_S2025/blob/main/exams/psc4375_s25_exam.Rmd) |
| [7](#week-7) | 03/03 | Spring Break |  |
| [8](#week-8) | 03/10 | Prediction: Interactions & Nonlinearities  | T: QSS Tutorial 6   <br /> W: Final project proposal|
| [9](#week-9) | 03/17 | Probability: Basics | T: QSS Tutorial 7 |
| [10](#week-10) | 03/24 | Probability: Random Variables & Large Samples | T: QSS Tutorial 8 <br /> F: [PSet 3](https://github.com/rweldzius/PSC4375_S2025/blob/main/psets/psc4375_s25_pset3.Rmd)   |
| [11](#week-11) | 03/31 | Inference: Estimation | T: QSS Tutorial 9   |
| [12](#week-12) | 04/07 | Inference: Hypothesis Testing  |  T: QSS Tutorial 10  |
| [13](#week-13) | 04/14 | Inference: Uncertainty in Regression | W: [PSet 4](https://github.com/rweldzius/PSC4375_S2025/blob/main/psets/psc4375_s25_pset4.Rmd)  |
| [14](#week-14) | 04/21 | Class Presentations  |    |
| [15](#week-15) | 04/28 | Class Presentations  | M: Final project draft  |
| [16](#week-16) | 05/05 | Final project/Exam 2 due Friday (05/09) by 11:59PM ET | F: [Exam 2](https://github.com/rweldzius/PSC4375_S2025/blob/main/exams/psc4375_s25_exam2.Rmd) <br /> F: Final project  |

[Back to ToC](#table-of-contents)

## Week 0

**Topic**: Course overview and introduction

**Dates**: 01/13 - 01/17

**Readings**:
 * M: Syllabus
 * W: QSS 1.1-1.4
 * F: [R Markdown, 2.1-2.6](https://bookdown.org/yihui/rmarkdown/)

**Assignments**:
 * By Wednesday (01/15) before class: Setup R and RStudio. See instructions [here](#required-applications). Initiate Campuswire account (see [Required Applications](#required-applications) above). 
 * [Problem Set 0](https://github.com/rweldzius/PSC4375_S2025/blob/main/psets/psc4375_s25_pset0.Rmd) due Friday (01/17) by 11:59PM ET

**Clas Materials**:
 * [Week 0: in-class practice R script](https://github.com/rweldzius/PSC4375_S2025/blob/main/lectures/Week0_R_practice.R)

[Back to schedule](#schedule)

## Week 1

**Topic**: Causality: Randomized Experiments

**Dates**: 01/20 - 01/24

**Readings**:
 * M: No Class (MLK, Jr. Day)
 * W: QSS 2.1-2.4

**Slides**:
 * W: [Lecture 1](https://rweldzius.github.io/PSC4375_S2025/lectures/psc4375_lecture_1_slides_handout.pdf)
 * F: [Lecture 2](https://rweldzius.github.io/PSC4375_S2025/lectures/psc4375_lecture_2_slides_handout.pdf)

**Assignments**:
 * QSS Tidyverse Tutorial 1 due Tuesday (01/21) by 11:59PM ET
 * [Problem Set 1](https://github.com/rweldzius/PSC4375_S2025/blob/main/psets/psc4375_s25_pset1.Rmd) posted (due next week)

[Back to schedule](#schedule)

## Week 2

**Topic**: Causality:  Observational Studies

**Dates**: 01/27 - 01/31

**Readings**:
 * M: QSS 2.5-2.6

**Slides**:
 * M: [Lecture 3](https://rweldzius.github.io/PSC4375_S2025/lectures/psc4375_lecture_3_slides_handout.pdf)
 * W: [Lecture 4](https://rweldzius.github.io/PSC4375_S2025/lectures/psc4375_lecture_4_slides_handout.pdf)
 * F: [Lecture 5](https://rweldzius.github.io/PSC4375_S2025/lectures/psc4375_lecture_5_slides_handout.pdf)

**Assignments**:
 * QSS Tidyverse Tutorial 2 due Tuesday (01/28) by 11:59PM ET
 * [Problem Set 1](https://github.com/rweldzius/PSC4375_S2025/blob/main/psets/psc4375_s25_pset1.Rmd) due Friday (01/31) by 11:59PM ET

[Back to schedule](#schedule)

## Week 3

**Topic**: Measurement: Descriptive Statistics

**Dates**: 02/03 - 02/07

**Readings**:
 * M: QSS 3.1-3.3

**Slides**:
 * M: [Lecture 5](https://rweldzius.github.io/PSC4375_S2025/lectures/psc4375_lecture_5_slides_handout.pdf)
 * W: [Lecture 6](https://rweldzius.github.io/PSC4375_S2025/lectures/psc4375_lecture_6_slides_handout.pdf)

**Assignments**:
 * QSS Tidyverse Tutorial 3 due Tuesday (02/04) by 11:59PM ET
 * [Problem Set 2](https://github.com/rweldzius/PSC4375_S2025/blob/main/psets/psc4375_s25_pset2.Rmd) posted; due next week

[Back to schedule](#schedule)

## Week 4

**Topic**: Measurement: Sampling & Bivariate Statistics

**Dates**: 02/10 - 02/14 💝

**Readings**:
 * M: QSS 3.4-3.7

**Slides**:
 * M: [Lecture 7](https://rweldzius.github.io/PSC4375_S2025/lectures/psc4375_lecture_7_slides_handout.pdf)
 * W: [Lecture 8](https://rweldzius.github.io/PSC4375_S2025/lectures/psc4375_lecture_8_slides_handout.pdf)
 * F: None. Work on problem sets in class. 

**Assignments**:
 * QSS Tidyverse Tutorial 4 due Tuesday (02/11) by 11:59PM ET
 * [Problem Set 2](https://github.com/rweldzius/PSC4375_S2025/blob/main/psets/psc4375_s25_pset2.Rmd) due Friday (02/14) by 11:59PM ET

[Back to schedule](#schedule)

## Week 5

**Topic**: Prediction & Regression

**Dates**: 02/17 - 02/21

**Readings**:
 * M: QSS 4.1-4.2.3

**Slides**:
 * M: [Lecture 9](https://rweldzius.github.io/PSC4375_S2025/lectures/psc4375_lecture_9_slides_handout.pdf)
 * W: [Lecture 10/11](https://rweldzius.github.io/PSC4375_S2025/lectures/psc4375_lecture_10_slides_handout.pdf)
 * F: See above. We will start where we left off on Wednesday. 

**Assignments**:
 * QSS Tidyverse Tutorial 5 due Tuesday (02/18) by 11:59PM ET
 * [Exam 1](https://github.com/rweldzius/PSC4375_S2025/blob/main/exams/psc4375_s25_exam.Rmd) posted on Friday

[Back to schedule](#schedule)

## Week 6

**Topic**: Prediction: More Regression!

**Dates**: 02/24 - 02/28 (**No class meeting on Friday**)

**Readings**:
 * M: QSS 4.2.4 - 4.2.6
 * F: NO CLASS

**Slides**:
 * M/W: [Lecture 12](https://rweldzius.github.io/PSC4375_S2025/lectures/psc4375_lecture_12_slides_handout.pdf)

**Assignments**:
 * No tutorial this week! Woo!
 * [Exam 1](https://github.com/rweldzius/PSC4375_S2025/blob/main/exams/psc4375_s25_exam.Rmd) due Friday (02/28) by 11:59PM ET

[Back to schedule](#schedule)

## Week 7

**Spring Break!**

<img src="./lectures/figs/springbreak.gif" width="30%" height="30%"/>

[Back to schedule](#schedule)

## Week 8

**Topic**: Interactions & Nonlinearities in Regression 

**Dates**: 03/10 - 03/14

**Readings**:
 * M: QSS 4.3-4.5

**Slides**:
 * M: [Lecture 13-14](https://rweldzius.github.io/PSC4375_S2025/lectures/psc4375_lecture_14_slides_handout.pdf)

**Assignments**:
 * QSS Tidyverse Tutorial 6 due Tuesday (03/11) by 11:59PM ET
 * Final Project proposal due Wednesday (03/12) by 11:59PM ET


[Back to schedule](#schedule)

## Week 9

**Topic**: Probability: Basics

**Dates**: 03/17 - 03/21

**Readings**:
 * M: QSS 6.1-6.2

**Slides**:
 * [Lecture 15](https://rweldzius.github.io/PSC4375_S2025/lectures/psc4375_lecture_15_slides_handout.pdf)
 * [Lecture 15 (Bayes Rule)](https://rweldzius.github.io/PSC4375_S2025/lectures/psc4375_lecture_15_slides_bayes.pdf)

**Assignments**
 * QSS Tutorial 7 due Thursday (03/20) by 11:59PM ET
 * [Problem Set 3](https://github.com/rweldzius/PSC4375_S2025/blob/main/psets/psc4375_s25_pset3.Rmd) posted

[Back to schedule](#schedule)

## Week 10

**Topic**: Probability: Random Variables & Large Samples

**Dates**: 03/24 - 03/28

**Readings**:
 * M: QSS 6.3-6.5

**Slides**:
 * [Lecture 16](https://rweldzius.github.io/PSC4375_S2025/lectures/psc4375_lecture_16_slides_handout.pdf)

**Assignments**:
 * QSS Tutorial 8 due Tuesday (03/25) by 11:59PM ET
 * [Problem Set 3](https://github.com/rweldzius/PSC4375_S2025/blob/main/psets/psc4375_s25_pset3.Rmd) due by Friday (03/28) by 11:59PM ET
  
[Back to schedule](#schedule)

## Week 11

**Topic**: Inference: Estimation

**Dates**: 03/31 - 04/04

**Readings**:
 * M: QSS  7.1

**Slides**:
 * [Lecture 17](https://rweldzius.github.io/PSC4375_S2025/lectures/psc4375_lecture_17_slides_handout.pdf)

**Assignments**:
 * QSS Tutorial 9 due Tuesday (04/01) by 11:59PM ET
 * [Problem Set 4](https://github.com/rweldzius/PSC4375_S2025/blob/main/psets/psc4375_s25_pset4.Rmd) posted

[Back to schedule](#schedule)

## Week 12

**Topic**: Inference: Hypothesis Testing

**Dates**: 04/07 - 04/11
 * **No class on Friday 4/11!**
   
**Readings**:
 * M: QSS 7.2

**Slides**:
 * [Lecture 18](https://rweldzius.github.io/PSC4375_S2025/lectures/psc4375_lecture_18_slides_handout.pdf)

**Assignments**:
 * QSS Tutorial 10 due Tuesday (04/08) by 11:59PM ET

[Back to schedule](#schedule)

## Week 13

**Topic**: Inference: Uncertainty in Regression

**Dates**: 04/14 - 04/18  (No class on Friday 04/18 for Easter Recess)

**Readings**:
 * QSS 7.3

**Assignments**:
 * No more tutorials! Let's goooo!
 * [Problem Set 4](https://github.com/rweldzius/PSC4375_S2025/blob/main/psets/psc4375_s25_pset4.Rmd) due Friday (04/25) by 11:59PM ET

[Back to schedule](#schedule)

## Week 14

**Topic**: Class Presentations

**Dates**: 04/21 - 04/25 (No class on Monday 04/21 for Easter Recess)

**Assignments**:
 * Exam 2 due Friday (05/09) by 11:59PM ET

[Back to schedule](#schedule)

## Week 15

**Topic**: Class Presentations

**Dates**: 04/28 & 04/30

**Assignments**:
 * Final Project *draft* analysis due Monday (04/30) by 11:59AM ET

[Back to schedule](#schedule)

## Week 16

**Topic**: Final projects Due

**Dates**: 05/09

**Assignments**:
 * Final project write-up due Friday (05/09) by 11:59PM ET

[Back to schedule](#schedule)


## Helpful Resources

[Rstudio Cheat Sheet: Data Wrangling](https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf)

[Rstudio Cheat Sheet: ggplot2](https://hbctraining.github.io/Intro-to-R-flipped/cheatsheets/data-visualization-2.1.pdf)

[R-graphics Cookbook](http://www.cookbook-r.com/Graphs/)

[... And the full list of Rstudio cheat sheets](https://posit.co/resources/cheatsheets/)

[Tidymodels Resources](https://www.tidymodels.org/learn/)

[Back to ToC](#table-of-contents)

## Acknowledgements

The contents of this course are influenced by and often come directly from Dr. Matthew Blackwell at Harvard University where he teaches a similar undergraduate course. I am grateful to Matt for making his course materials public with a [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
