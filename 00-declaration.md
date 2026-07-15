# Key Information {-}

<div class="alert alert-danger" role="alert">
<span><strong>**Please read this page carefully as it contains important information about the course structure, delivery, and assessment.**</strong></span>
</div>

Please note that we do not print this course guide for a few reasons:

 1. we can make updates to the course guide during semester when hosted online like it is,
 2. printing it loses some of the functionality of the course guide with the way the code is presented once printed, and
 3. we are also keen to save some trees from unnecessary printing! 
 
However, if you want to print it, you’re more than welcome to do so. The easiest way to do this is *printing to PDF* from your browser. 

## Course outline {-}

Living systems are the most complex systems in science, and biology is naturally variable and noisy due to its many internal and external influences. For these reasons, it is difficult to make inferences from and predictions about biological systems. Understanding biology requires computational skills to effectively analyse and interpret data, and multidisciplinary research approaches are becoming more common as a critical key to solving many of the complex problems of studying life and living organisms in today’s world. So, contrary to the popular undergrad biology student beliefs, statistics, mathematics and computational skills are essential in a biologist’s toolkit.

To understand modern biological research and findings, and to participate in this research (and get jobs!), skills in working with and visualizing data, learning from data using models, and generating data using simulations of models are crucial. These might be classic statistical models, mathematical models, or inference with process-based models. Biologists also need to be careful and critical thinkers about data and how it is acquired, as well as think critically about the models that we use to try to simplify, and thereby understand, the incredible complexity of biology.

**BIOSCI 220: Quantitative Biology** will introduce you to the programming language R to develop the aforementioned skills, with no coding experience assumed or expected. The aim is to give beginners the confidence to continue learning R and not be afraid of statistics and mathematics! 


##  Installing `R` and `RStudio` {-}

<div class="alert alert-danger" role="alert"> 
<span><strong>Throughout this course, you will be learning how to program using `R` and `RStudio` weekly.</strong></span> You are expected to install and familiarize yourself with these environments before or during the first week of the course. We provide help sessions during week 1 and easy-to-follow instructions for this, please see CANVAS and/or [Installing R and RStudio] to get started.
</div>

Note that lab computers will already have `R` and`RStudio` installed; however, if you plan to use your personal computer then you will need to install both `R` and `RStudio` yourself. Follow the directions in [Installing R and RStudio] to do so (or come along to a dedicated help session).

Another option available is to use [RStudio Cloud](https://rstudio.cloud/) where, everything is run in a web browser (on a remote server) and doesn't require you to download the software onto your personal computer.


## Your teaching team {-}

**Semester 2, 2026**




 Module Number                  Module Content                   Weeks taught               Lecturer            
---------------  ---------------------------------------------  --------------  --------------------------------
       1              R programming and data exploration            1 - 3          Assoc. Prof. Beatrix Jones   
       1                     Statistical inference                  4 - 6        Jenn Jury (course coordinator) 
       2               Mathematical modelling in biology            7 - 9              Dr Nobuto Takeuchi       
       3          Model-based inference and critical thinking      10 - 12         Assoc. Prof. Dave Aguirre    


## Lectures {-}

<div class="alert alert-danger" role="alert">

<span><strong>Lectures are every week, either:</strong></span>
 <ul>
  <li>IN-PERSON (L01C) **Mondays 9-10am** in MLT1 (303-G23) and **Thursdays 9-10 am** in FPAA (260-115), or </li>
  <li>ONLINE (L02C) Delivered using **lecture recordings (via Panopto Video)** from in-person lectures. Scheduled for Mondays and Thursdays 7-8pm, but **can be viewed as soon as available** </li>
</ul>
</div>

You should stay on top of lectures as this will assist you with your learning. Please attend lectures if in L01C, but lecture recordings will also be available in CANVAS via the Panopto Video tab after the lecture has been delivered (within 24 hours, usually earlier than this).


## Assessment {-}

### Assessment structure {-}


```
## Loading required package: tidyverse
```

```
## ── Attaching core tidyverse packages ──────────────────────── tidyverse 2.0.0 ──
## ✔ dplyr     1.2.1     ✔ readr     2.2.0
## ✔ forcats   1.0.1     ✔ stringr   1.6.0
## ✔ ggplot2   4.0.3     ✔ tibble    3.3.1
## ✔ lubridate 1.9.5     ✔ tidyr     1.3.2
## ✔ purrr     1.2.2     
## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
## ✖ dplyr::filter() masks stats::filter()
## ✖ dplyr::lag()    masks stats::lag()
## ℹ Use the conflicted package (<http://conflicted.r-lib.org/>) to force all conflicts to become errors
## Loading required package: knitr
```

        Week                                                                         Laboratories                                                                                                                                    Quizzes                                                                                                                                       Inspera                                                                   
--------------------  -------------------------------------------------------------------------------------------------------------------------------------------  --------------------------------------------------------------------------------------------------------------------------------------------  --------------------------------------------------------------------------------------------------------------------------------------------
         1                  <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" >R help sessions</span>                      <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" ></span>                              <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" ></span>              
         2             <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(255, 179, 138, 1) !important;" >lab</span>    <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(173, 216, 230, 1) !important;" >quiz</span>                 <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" ></span>              
         3             <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(255, 179, 138, 1) !important;" >lab</span>    <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(173, 216, 230, 1) !important;" >quiz</span>                 <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" ></span>              
         4                         <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" ></span>                 <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(173, 216, 230, 1) !important;" >quiz</span>                 <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" ></span>              
         5             <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(255, 179, 138, 1) !important;" >lab</span>    <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(173, 216, 230, 1) !important;" >quiz</span>                 <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" ></span>              
         6             <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(255, 179, 138, 1) !important;" >lab</span>    <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(173, 216, 230, 1) !important;" >quiz</span>                 <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" ></span>              
 Mid-semester break                <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" ></span>                              <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" ></span>                              <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" ></span>              
         7                         <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" ></span>                 <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(173, 216, 230, 1) !important;" >quiz</span>    <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(203, 195, 227, 1) !important;" >Test</span> 
         8             <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(255, 179, 138, 1) !important;" >lab</span>    <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(173, 216, 230, 1) !important;" >quiz</span>                 <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" ></span>              
         9             <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(255, 179, 138, 1) !important;" >lab</span>    <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(173, 216, 230, 1) !important;" >quiz</span>                 <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" ></span>              
         10                        <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" ></span>                 <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(173, 216, 230, 1) !important;" >quiz</span>                 <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" ></span>              
         11            <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(255, 179, 138, 1) !important;" >lab</span>    <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(173, 216, 230, 1) !important;" >quiz</span>                 <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" ></span>              
         12            <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(255, 179, 138, 1) !important;" >lab</span>    <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(173, 216, 230, 1) !important;" >quiz</span>                 <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" ></span>              
    Exam Period                    <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" ></span>                              <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color:  !important;" ></span>                 <span style="border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(203, 195, 227, 1) !important;" >Exam</span> 

### Assessment summary {-}



                   Week of semester        Weighting per assessment (%)    Total weighting (%) 
------------  --------------------------  ------------------------------  ---------------------
Laboratory     2, 3, 5, 6, 8, 9, 11, 12                 5                          40          
Weekly quiz        2 - 12 inclusive                     1                          10          
Test                      7                             20                         20          
Exam                 Exam period                        30                         30          

<div class="alert alert-danger" role="alert">
The test will be held on **Wednesday 16th September 6.30-8.15pm. The test will cover all of Module 1 taught material only. The exam will cover both Module 2 & 3 taught material only.**
The delivery mode for the test and the exam is an on-campus, invigilated closed-book Inspera assessment.
</div>


### Laboratories {-}

<div class="alert alert-danger" role="alert">
There are **eight** labs in total held in weeks 2, 3, 5, 6, 8, 9, 11 and 12 (i.e., in each three week lecture block there are labs in the last two weeks). Each lab is worth **5%** of your final grade (40% in total).

Labs will be held in 106-014 (Biology Building, Room 014) during your scheduled SSO lab time, which will be **one of** 
<ul>
<li>Monday 2-5pm, or</li>
<li>Tuesday 2-5pm, or</li>
<li>Wednesday 10am-1pm, or</li>
<li>Wednesday 2-5pm, or</li>
<li>Thursday 10am-1pm, or</li>
<li>Thursday 2-5pm, or</li>
<li>Friday 10am-1pm, or</li>
<li>Friday 2-5pm.</li>
</ul>

</div>

Labs are three (3) hours and the material is designed to be completed in this time. 

You are scheduled into a lab stream in SSO. While lab attendance is not compulsory, it is highly recommended you attend your scheduled lab stream. There will be an assessed in-class discussion in the week 6 lab, so attendance and a preparatory worksheet for that lab will be required to gain the grades for that part of the assessment. There is teaching staff to support you through the tasks and answer your course-related questions.


### Weekly quizzes {-}

<div class="alert alert-danger" role="alert"> There are **eleven** weekly quizzes in total. Each quiz is worth **1%** and (if you have completed all quizzes) your one (1) quiz that has the lowest mark will be dropped from your final grade. Therefore your weekly quizzes will total **10%** towards final grade.
</div>

The weekly quizzes are due at the end of each week from week 2 - week 12 (due Sunday at 10pm). These are designed for you to solidify concepts and practice skills taught each week and thereby keep up with the material.

There are practice quizzes for you to attempt prior to sitting the weekly quiz, these are not assessed. There is also a practice quiz for week 1.


## `RStudio` Accessibility {-}

`RStudio` has many features and options to help you work the way that best suits your needs.
Here is a great [article outlining RStudio accessibility features](https://support.posit.co/hc/en-us/articles/360044226673-RStudio-Accessibility-Features).
If you need further support, please reach out to the BIOSCI 220 teaching staff.
