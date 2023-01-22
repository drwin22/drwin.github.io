Math 0910: Introduction Algebra
================
Prof. Francois Nguyen
Spring 2023

# Overview:

This course is Introduction to Algebra Online course. The topics include
real numbers, methods of solving equations and inequalities and their
applications, exponents and polynomials, factoring polynomials, solving
quadratic equations and their applications, rational expressions,
rational exponents and radicals, and graphing functions (linear and
quadratic).

``` r
# Define the cars vector with 5 values
hist(cars$speed)
```

![](index_files/figure-gfm/unnamed-chunk-2-1.png)<!-- -->

``` r
# Graph cars using blue points overlayed by a line 
plot(cars, type="o", col="blue")

# Create a title with a red, bold/italic font
title(main="Autos", col.main="red", font.main=4)
```

![](index_files/figure-gfm/unnamed-chunk-2-2.png)<!-- -->

# Course Requirements

A minimum grade of C is required in this course to progress to COURSE.

# Course Objectives:

At the completion of this course, students will be able to:

- Identify and understand the basic concepts of algebraic expressions.
- Perform operations on polynomial and rational expressions.
- Apply the definition of absolute value to solve inequalities and
  equations involving absolute values.
- Find solutions to and graph systems of linear equations and
  inequalities.
- Solve equations involving first and second-degree polynomials and
  rational expressions.
- Manipulate radical expressions using laws of exponents.
- Understand basic properties of functions.
- Apply properties of rational and radical expressions, polynomials, and
  absolute value in the context of real-life

# Course Policies:

## General:

– Computers, Calculators are not to be used unless instructed to do so.
– Quizzes and exams are closed book, closed notes.

## Grade:

makeup quizzes or exams will be given.

– Grades in the C range represent performance that meets expectations;
Grades in the B range represent performance that is substantially better
than the expectations; Grades in the A range represent work that is
excellent.

– Grades will be maintained in the LMS course shell. Students are
responsible for tracking their progress by referring to the online
gradebook.

# Assignments

– Students are expected to work independently. Offering and accepting
solutions from others is an act of plagiarism, which is a serious
offense and all involved parties will be penalized according to the
Academic Honesty Policy.

– Discussion among students is encouraged, but when in doubt, direct
your questions to the professor, tutor, or lab assistant.

– No late assignments will be accepted under any circumstances.

# Attendance and Absences

    ## `geom_smooth()` using formula = 'y ~ x'

![A Scatterplot of the Relationship between Class Attendance and Final
Grade](index_files/figure-gfm/attendplot-1.png)

– Attendance is expected and will be taken each class. You are allowed
to miss 1 class during the semester without penalty. Any further
absences will result in point and/or grade deductions.

– Students are responsible for all missed work, regardless of the reason
for absence. It is also the absentee’s responsibility to get all missing
notes or materials.

# Academic Honesty Policy Summary:

In addition to skills and knowledge, Saint Paul College aims to teach
students appropriate Ethical and Professional Standards of Conduct. The
Academic Honesty Policy exists to inform students and Faculty of their
obligations in upholding the highest standards of professional and
ethical integrity. All student work is subject to the Academic Honesty
Policy. Professional and Academic practice provides guidance about how
to properly cite, reference, and attribute the intellectual property of
others. Any attempt to deceive a faculty member or to help another
student to do so will be considered a violation of this standard.

# College Policy

The College’s academic honesty policies can be found in the catalog.
Please be assured that there will be absolutely no tolerance for
cheating in any way. All your quizzes and exams must be done
independently with no help from anyone. Make sure you copy the code of
honor statement below and send me an email with your name and date of
the time to confirm you adhere to this course policy: “I will register
for only one account on Mymathlab.com. My answers to homework, quizzes
and exams will be my own work (except for assignments that explicitly
permit collaboration).

I will not make solutions to homework, quizzes or exams available to
anyone else. This includes both solutions written by me, as well as any
official solutions provided by the course instructor. I will not engage
in any other activities that will dishonestly improve my results or
dishonestly improve/hurt the results of others. Your name. Dated on
Jan/…/2023.

# Special Services and Math Tutoring

Special Accommodations: It is college policy to provide reasonable
accommodations to students with disabilities. Please contact the office
of Disability Resources and Access if you wish to discuss this policy.
The Math Center (MC) will be open for drop-in tutoring in room 3125.
This tutoring is FREE and no appointment is necessary.

# Online coursework Integrity Declaration

Online submission of, or placing one’s name on an exam, assignment, or
any course document is a statement of academic honor that the student
has not received or given inappropriate assistance in completing it and
that the student has complied with the Academic Honesty Policy in that
work.

# Consequences

An instructor may impose a sanction on the student that varies depending
upon the instructor’s evaluation of the nature and gravity of the
offense. Possible sanctions include but are not limited to, the
following: (1) Require the student to redo the assignment; (2) Require
the student to complete another assignment; (3) Assign a grade of zero
to the assignment; (4) Assign a final grade of “F” for the course. A
student may appeal these decisions according to the Academic Grievance
Procedure. (See the relevant section in the Student Handbook.) Multiple
violations of this policy will result in a referral to the Conduct
Review Board for possible additional sanctions.

The full text of the Academic Honesty Policy is in the Student Handbook.

# Course Schedule

(See the addedum)

## Week 1, January 9: Introduction to the Course

*Assignment*:

1.  [Bryan, Jennifer. 2016. Chapters 1-16.](http://happygitwithr.com)
    Read this carefully and follow its instructions to get set up with ,
    RStudio, Git, and GitHub on your laptop before we meet.

## Week 2, January 16: The Replication Crisis and Reproducibility

*Readings*:

1.  [Aschwanden, Christie, and Maggie Koerth-Baker. 2016. “How Two Grad
    Students Uncovered an Apparent Fraud—and a Way to Change Opinions on
    Transgender Rights.” *FiveThirtyEight*, April
    7](http://fivethirtyeight.com/features/how-two-grad-students-uncovered-michael-lacour-fraud-and-a-way-to-change-opinions-on-transgender-rights/),
    and [Dimitrova, Velichka. 2013. “Reinhart-Rogoff Revisited: Coding
    Errors Happen—Key Problem Was in Not Making the Data Openly
    Available from the Start.” *LSE: The Impact Blog*, April
    24.](http://blogs.lse.ac.uk/impactofsocialsciences/2013/04/24/reinhart-rogoff-revisited-why-we-need-open-data-in-economics/)
2.  [Data Access and Research Transparency (DA-RT): A Joint Statement by
    Political Science Journal
    Editors.](http://journals.cambridge.org/action/displayAbstract?fromPage=online&aid=9911378&fulltextType=LT&fileId=S2049847015000448)
3.  [*AJPS* Replication and Verification
    Policy](https://ajps.org/ajps-replication-policy/) and [*American
    Journal of Political Science* Guidelines for Preparing Replication
    Files.](https://ajpsblogging.files.wordpress.com/2015/03/ajps-guide-for-replic-materials-1-0.pdf)
4.  [Gelman, Andrew, and Eric Loken. 2013. “The Garden of Forking Paths:
    Why Multiple Comparisons Can Be a Problem, Even When There Is No
    ‘Fishing Expedition’ or ‘*p*-Hacking’ and the Research Hypothesis
    Was Posited Ahead of
    Time.”](http://www.stat.columbia.edu/~gelman/research/unpublished/p_hacking.pdf)
5.  [Leek, Jeffrey T., and Roger D. Peng. 2015. “Opinion: Reproducibile
    Research Can Still Be Wrong: Adopting a Prevention Approach.”
    *Proceedings of the National Academy of Sciences*
    112(6):1645-1646](http://www.pnas.org.proxy.lib.uiowa.edu/content/112/6/1645)
    and [Patil, Prasad, Roger D. Peng, and Jeffrey T. Leek. 2016. “A
    Statistical Definition for Reproducibility and Replicability.”
    *bioRxiv*, July
    29.](http://biorxiv.org/content/biorxiv/early/2016/07/29/066803.full.pdf)

## Week 3, January 23: Chapter-03

*Assignment*:

1.  [Bryan, Jennifer. 2016. Chapters 1-16.](http://happygitwithr.com)
    Read this carefully and follow its instructions to get set up with ,
    RStudio, Git, and GitHub on your laptop before we meet.

## Week 4, January 30: Chapter-04

*Readings*:

1.  [Bryan, Jennifer. 2016. Chapters 1-16.](http://happygitwithr.com)
    Read this carefully and follow its instructions to get set up with ,
    RStudio, Git, and GitHub on your laptop before we meet.
2.  [Bryan, Jennifer. 2016. Chapters 1-16.](http://happygitwithr.com)
    Read this carefully and follow its instructions to get set up with ,
    RStudio, Git, and GitHub on your laptop before we meet.

## Week 5, February 6: Chapter-05

*Readings*:

1.  [Bryan, Jennifer. 2016. Chapters 1-16.](http://happygitwithr.com)
    Read this carefully and follow its instructions to get set up with ,
    RStudio, Git, and GitHub on your laptop before we meet.

## Week 6, February 13: Chapter-06

*Readings*: [Bryan, Jennifer. 2016. Chapters
1-16.](http://happygitwithr.com) Read this carefully and follow its
instructions to get set up with , RStudio, Git, and GitHub on your
laptop before we meet.

## Week 7, February 20: Chapter-07

*Readings*: [Bryan, Jennifer. 2016. Chapters
1-16.](http://happygitwithr.com) Read this carefully and follow its
instructions to get set up with , RStudio, Git, and GitHub on your
laptop before we meet.

## Week 8, February 27: Chapter-08

*Readings*: [Bryan, Jennifer. 2016. Chapters
1-16.](http://happygitwithr.com) Read this carefully and follow its
instructions to get set up with , RStudio, Git, and GitHub on your
laptop before we meet.

## Week 9, March 6: Chapter-09

## Week 10, March 13: Chapter-10

## Week 11, March 20: Chapter-11

## Week 12, March 27: Chapter-12

## Week 13, April 3: Chapter-13

## Week 14, April 10: Chapter-14

## Week 15, April 17: Chapter-15

## Week 16, April 24: Chapter-16

<center>
<img src="https://media.glassdoor.com/l/468324/dunwoody-college-office.jpg">
</center>

``` r
# devtools::install_github("rstudio/gt")
library(gt)
head(mtcars)
```

    ##                    mpg cyl disp  hp drat    wt  qsec vs am gear carb
    ## Mazda RX4         21.0   6  160 110 3.90 2.620 16.46  0  1    4    4
    ## Mazda RX4 Wag     21.0   6  160 110 3.90 2.875 17.02  0  1    4    4
    ## Datsun 710        22.8   4  108  93 3.85 2.320 18.61  1  1    4    1
    ## Hornet 4 Drive    21.4   6  258 110 3.08 3.215 19.44  1  0    3    1
    ## Hornet Sportabout 18.7   8  360 175 3.15 3.440 17.02  0  0    3    2
    ## Valiant           18.1   6  225 105 2.76 3.460 20.22  1  0    3    1

``` r
df=mtcars
df %>%gt()
```

<div id="egxbfzyivz" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>html {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', 'Fira Sans', 'Droid Sans', Arial, sans-serif;
}

#egxbfzyivz .gt_table {
  display: table;
  border-collapse: collapse;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#egxbfzyivz .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#egxbfzyivz .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#egxbfzyivz .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#egxbfzyivz .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 0;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#egxbfzyivz .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#egxbfzyivz .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#egxbfzyivz .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#egxbfzyivz .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#egxbfzyivz .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#egxbfzyivz .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#egxbfzyivz .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#egxbfzyivz .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#egxbfzyivz .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}

#egxbfzyivz .gt_from_md > :first-child {
  margin-top: 0;
}

#egxbfzyivz .gt_from_md > :last-child {
  margin-bottom: 0;
}

#egxbfzyivz .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#egxbfzyivz .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}

#egxbfzyivz .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#egxbfzyivz .gt_row_group_first td {
  border-top-width: 2px;
}

#egxbfzyivz .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#egxbfzyivz .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#egxbfzyivz .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#egxbfzyivz .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#egxbfzyivz .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#egxbfzyivz .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#egxbfzyivz .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#egxbfzyivz .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#egxbfzyivz .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#egxbfzyivz .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-left: 4px;
  padding-right: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#egxbfzyivz .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#egxbfzyivz .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#egxbfzyivz .gt_left {
  text-align: left;
}

#egxbfzyivz .gt_center {
  text-align: center;
}

#egxbfzyivz .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#egxbfzyivz .gt_font_normal {
  font-weight: normal;
}

#egxbfzyivz .gt_font_bold {
  font-weight: bold;
}

#egxbfzyivz .gt_font_italic {
  font-style: italic;
}

#egxbfzyivz .gt_super {
  font-size: 65%;
}

#egxbfzyivz .gt_footnote_marks {
  font-style: italic;
  font-weight: normal;
  font-size: 75%;
  vertical-align: 0.4em;
}

#egxbfzyivz .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#egxbfzyivz .gt_indent_1 {
  text-indent: 5px;
}

#egxbfzyivz .gt_indent_2 {
  text-indent: 10px;
}

#egxbfzyivz .gt_indent_3 {
  text-indent: 15px;
}

#egxbfzyivz .gt_indent_4 {
  text-indent: 20px;
}

#egxbfzyivz .gt_indent_5 {
  text-indent: 25px;
}
</style>
<table class="gt_table">
  
  <thead class="gt_col_headings">
    <tr>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="mpg">mpg</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="cyl">cyl</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="disp">disp</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="hp">hp</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="drat">drat</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="wt">wt</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="qsec">qsec</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="vs">vs</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="am">am</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="gear">gear</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="carb">carb</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="mpg" class="gt_row gt_right">21.0</td>
<td headers="cyl" class="gt_row gt_right">6</td>
<td headers="disp" class="gt_row gt_right">160.0</td>
<td headers="hp" class="gt_row gt_right">110</td>
<td headers="drat" class="gt_row gt_right">3.90</td>
<td headers="wt" class="gt_row gt_right">2.620</td>
<td headers="qsec" class="gt_row gt_right">16.46</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">4</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">21.0</td>
<td headers="cyl" class="gt_row gt_right">6</td>
<td headers="disp" class="gt_row gt_right">160.0</td>
<td headers="hp" class="gt_row gt_right">110</td>
<td headers="drat" class="gt_row gt_right">3.90</td>
<td headers="wt" class="gt_row gt_right">2.875</td>
<td headers="qsec" class="gt_row gt_right">17.02</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">4</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">22.8</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">108.0</td>
<td headers="hp" class="gt_row gt_right">93</td>
<td headers="drat" class="gt_row gt_right">3.85</td>
<td headers="wt" class="gt_row gt_right">2.320</td>
<td headers="qsec" class="gt_row gt_right">18.61</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">1</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">21.4</td>
<td headers="cyl" class="gt_row gt_right">6</td>
<td headers="disp" class="gt_row gt_right">258.0</td>
<td headers="hp" class="gt_row gt_right">110</td>
<td headers="drat" class="gt_row gt_right">3.08</td>
<td headers="wt" class="gt_row gt_right">3.215</td>
<td headers="qsec" class="gt_row gt_right">19.44</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">1</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">18.7</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">360.0</td>
<td headers="hp" class="gt_row gt_right">175</td>
<td headers="drat" class="gt_row gt_right">3.15</td>
<td headers="wt" class="gt_row gt_right">3.440</td>
<td headers="qsec" class="gt_row gt_right">17.02</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">2</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">18.1</td>
<td headers="cyl" class="gt_row gt_right">6</td>
<td headers="disp" class="gt_row gt_right">225.0</td>
<td headers="hp" class="gt_row gt_right">105</td>
<td headers="drat" class="gt_row gt_right">2.76</td>
<td headers="wt" class="gt_row gt_right">3.460</td>
<td headers="qsec" class="gt_row gt_right">20.22</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">1</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">14.3</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">360.0</td>
<td headers="hp" class="gt_row gt_right">245</td>
<td headers="drat" class="gt_row gt_right">3.21</td>
<td headers="wt" class="gt_row gt_right">3.570</td>
<td headers="qsec" class="gt_row gt_right">15.84</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">4</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">24.4</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">146.7</td>
<td headers="hp" class="gt_row gt_right">62</td>
<td headers="drat" class="gt_row gt_right">3.69</td>
<td headers="wt" class="gt_row gt_right">3.190</td>
<td headers="qsec" class="gt_row gt_right">20.00</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">2</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">22.8</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">140.8</td>
<td headers="hp" class="gt_row gt_right">95</td>
<td headers="drat" class="gt_row gt_right">3.92</td>
<td headers="wt" class="gt_row gt_right">3.150</td>
<td headers="qsec" class="gt_row gt_right">22.90</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">2</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">19.2</td>
<td headers="cyl" class="gt_row gt_right">6</td>
<td headers="disp" class="gt_row gt_right">167.6</td>
<td headers="hp" class="gt_row gt_right">123</td>
<td headers="drat" class="gt_row gt_right">3.92</td>
<td headers="wt" class="gt_row gt_right">3.440</td>
<td headers="qsec" class="gt_row gt_right">18.30</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">4</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">17.8</td>
<td headers="cyl" class="gt_row gt_right">6</td>
<td headers="disp" class="gt_row gt_right">167.6</td>
<td headers="hp" class="gt_row gt_right">123</td>
<td headers="drat" class="gt_row gt_right">3.92</td>
<td headers="wt" class="gt_row gt_right">3.440</td>
<td headers="qsec" class="gt_row gt_right">18.90</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">4</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">16.4</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">275.8</td>
<td headers="hp" class="gt_row gt_right">180</td>
<td headers="drat" class="gt_row gt_right">3.07</td>
<td headers="wt" class="gt_row gt_right">4.070</td>
<td headers="qsec" class="gt_row gt_right">17.40</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">3</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">17.3</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">275.8</td>
<td headers="hp" class="gt_row gt_right">180</td>
<td headers="drat" class="gt_row gt_right">3.07</td>
<td headers="wt" class="gt_row gt_right">3.730</td>
<td headers="qsec" class="gt_row gt_right">17.60</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">3</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">15.2</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">275.8</td>
<td headers="hp" class="gt_row gt_right">180</td>
<td headers="drat" class="gt_row gt_right">3.07</td>
<td headers="wt" class="gt_row gt_right">3.780</td>
<td headers="qsec" class="gt_row gt_right">18.00</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">3</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">10.4</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">472.0</td>
<td headers="hp" class="gt_row gt_right">205</td>
<td headers="drat" class="gt_row gt_right">2.93</td>
<td headers="wt" class="gt_row gt_right">5.250</td>
<td headers="qsec" class="gt_row gt_right">17.98</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">4</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">10.4</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">460.0</td>
<td headers="hp" class="gt_row gt_right">215</td>
<td headers="drat" class="gt_row gt_right">3.00</td>
<td headers="wt" class="gt_row gt_right">5.424</td>
<td headers="qsec" class="gt_row gt_right">17.82</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">4</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">14.7</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">440.0</td>
<td headers="hp" class="gt_row gt_right">230</td>
<td headers="drat" class="gt_row gt_right">3.23</td>
<td headers="wt" class="gt_row gt_right">5.345</td>
<td headers="qsec" class="gt_row gt_right">17.42</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">4</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">32.4</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">78.7</td>
<td headers="hp" class="gt_row gt_right">66</td>
<td headers="drat" class="gt_row gt_right">4.08</td>
<td headers="wt" class="gt_row gt_right">2.200</td>
<td headers="qsec" class="gt_row gt_right">19.47</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">1</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">30.4</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">75.7</td>
<td headers="hp" class="gt_row gt_right">52</td>
<td headers="drat" class="gt_row gt_right">4.93</td>
<td headers="wt" class="gt_row gt_right">1.615</td>
<td headers="qsec" class="gt_row gt_right">18.52</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">2</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">33.9</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">71.1</td>
<td headers="hp" class="gt_row gt_right">65</td>
<td headers="drat" class="gt_row gt_right">4.22</td>
<td headers="wt" class="gt_row gt_right">1.835</td>
<td headers="qsec" class="gt_row gt_right">19.90</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">1</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">21.5</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">120.1</td>
<td headers="hp" class="gt_row gt_right">97</td>
<td headers="drat" class="gt_row gt_right">3.70</td>
<td headers="wt" class="gt_row gt_right">2.465</td>
<td headers="qsec" class="gt_row gt_right">20.01</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">1</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">15.5</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">318.0</td>
<td headers="hp" class="gt_row gt_right">150</td>
<td headers="drat" class="gt_row gt_right">2.76</td>
<td headers="wt" class="gt_row gt_right">3.520</td>
<td headers="qsec" class="gt_row gt_right">16.87</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">2</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">15.2</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">304.0</td>
<td headers="hp" class="gt_row gt_right">150</td>
<td headers="drat" class="gt_row gt_right">3.15</td>
<td headers="wt" class="gt_row gt_right">3.435</td>
<td headers="qsec" class="gt_row gt_right">17.30</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">2</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">13.3</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">350.0</td>
<td headers="hp" class="gt_row gt_right">245</td>
<td headers="drat" class="gt_row gt_right">3.73</td>
<td headers="wt" class="gt_row gt_right">3.840</td>
<td headers="qsec" class="gt_row gt_right">15.41</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">4</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">19.2</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">400.0</td>
<td headers="hp" class="gt_row gt_right">175</td>
<td headers="drat" class="gt_row gt_right">3.08</td>
<td headers="wt" class="gt_row gt_right">3.845</td>
<td headers="qsec" class="gt_row gt_right">17.05</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">2</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">27.3</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">79.0</td>
<td headers="hp" class="gt_row gt_right">66</td>
<td headers="drat" class="gt_row gt_right">4.08</td>
<td headers="wt" class="gt_row gt_right">1.935</td>
<td headers="qsec" class="gt_row gt_right">18.90</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">1</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">26.0</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">120.3</td>
<td headers="hp" class="gt_row gt_right">91</td>
<td headers="drat" class="gt_row gt_right">4.43</td>
<td headers="wt" class="gt_row gt_right">2.140</td>
<td headers="qsec" class="gt_row gt_right">16.70</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">5</td>
<td headers="carb" class="gt_row gt_right">2</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">30.4</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">95.1</td>
<td headers="hp" class="gt_row gt_right">113</td>
<td headers="drat" class="gt_row gt_right">3.77</td>
<td headers="wt" class="gt_row gt_right">1.513</td>
<td headers="qsec" class="gt_row gt_right">16.90</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">5</td>
<td headers="carb" class="gt_row gt_right">2</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">15.8</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">351.0</td>
<td headers="hp" class="gt_row gt_right">264</td>
<td headers="drat" class="gt_row gt_right">4.22</td>
<td headers="wt" class="gt_row gt_right">3.170</td>
<td headers="qsec" class="gt_row gt_right">14.50</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">5</td>
<td headers="carb" class="gt_row gt_right">4</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">19.7</td>
<td headers="cyl" class="gt_row gt_right">6</td>
<td headers="disp" class="gt_row gt_right">145.0</td>
<td headers="hp" class="gt_row gt_right">175</td>
<td headers="drat" class="gt_row gt_right">3.62</td>
<td headers="wt" class="gt_row gt_right">2.770</td>
<td headers="qsec" class="gt_row gt_right">15.50</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">5</td>
<td headers="carb" class="gt_row gt_right">6</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">15.0</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">301.0</td>
<td headers="hp" class="gt_row gt_right">335</td>
<td headers="drat" class="gt_row gt_right">3.54</td>
<td headers="wt" class="gt_row gt_right">3.570</td>
<td headers="qsec" class="gt_row gt_right">14.60</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">5</td>
<td headers="carb" class="gt_row gt_right">8</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right">21.4</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">121.0</td>
<td headers="hp" class="gt_row gt_right">109</td>
<td headers="drat" class="gt_row gt_right">4.11</td>
<td headers="wt" class="gt_row gt_right">2.780</td>
<td headers="qsec" class="gt_row gt_right">18.60</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">2</td></tr>
  </tbody>
  
  
</table>
</div>

``` r
df %>%gt() %>%
tab_header(title = "mtcars dataset") %>%
tab_style(
style = list(cell_fill(color = "#b2f7ef"),
cell_text(weight = "bold")),
locations = cells_body(columns = mpg))%>%
tab_style(
style = list(cell_fill(color = "#ffefb5"),
cell_text(weight = "bold")), 
locations = cells_body(columns = hp))
```

<div id="pfuumatqep" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>html {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', 'Fira Sans', 'Droid Sans', Arial, sans-serif;
}

#pfuumatqep .gt_table {
  display: table;
  border-collapse: collapse;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#pfuumatqep .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#pfuumatqep .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#pfuumatqep .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#pfuumatqep .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 0;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#pfuumatqep .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#pfuumatqep .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#pfuumatqep .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#pfuumatqep .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#pfuumatqep .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#pfuumatqep .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#pfuumatqep .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#pfuumatqep .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#pfuumatqep .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}

#pfuumatqep .gt_from_md > :first-child {
  margin-top: 0;
}

#pfuumatqep .gt_from_md > :last-child {
  margin-bottom: 0;
}

#pfuumatqep .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#pfuumatqep .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}

#pfuumatqep .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#pfuumatqep .gt_row_group_first td {
  border-top-width: 2px;
}

#pfuumatqep .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#pfuumatqep .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#pfuumatqep .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#pfuumatqep .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#pfuumatqep .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#pfuumatqep .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#pfuumatqep .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#pfuumatqep .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#pfuumatqep .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#pfuumatqep .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-left: 4px;
  padding-right: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#pfuumatqep .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#pfuumatqep .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#pfuumatqep .gt_left {
  text-align: left;
}

#pfuumatqep .gt_center {
  text-align: center;
}

#pfuumatqep .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#pfuumatqep .gt_font_normal {
  font-weight: normal;
}

#pfuumatqep .gt_font_bold {
  font-weight: bold;
}

#pfuumatqep .gt_font_italic {
  font-style: italic;
}

#pfuumatqep .gt_super {
  font-size: 65%;
}

#pfuumatqep .gt_footnote_marks {
  font-style: italic;
  font-weight: normal;
  font-size: 75%;
  vertical-align: 0.4em;
}

#pfuumatqep .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#pfuumatqep .gt_indent_1 {
  text-indent: 5px;
}

#pfuumatqep .gt_indent_2 {
  text-indent: 10px;
}

#pfuumatqep .gt_indent_3 {
  text-indent: 15px;
}

#pfuumatqep .gt_indent_4 {
  text-indent: 20px;
}

#pfuumatqep .gt_indent_5 {
  text-indent: 25px;
}
</style>
<table class="gt_table">
  <thead class="gt_header">
    <tr>
      <td colspan="11" class="gt_heading gt_title gt_font_normal gt_bottom_border" style>mtcars dataset</td>
    </tr>
    
  </thead>
  <thead class="gt_col_headings">
    <tr>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="mpg">mpg</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="cyl">cyl</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="disp">disp</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="hp">hp</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="drat">drat</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="wt">wt</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="qsec">qsec</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="vs">vs</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="am">am</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="gear">gear</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="carb">carb</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">21.0</td>
<td headers="cyl" class="gt_row gt_right">6</td>
<td headers="disp" class="gt_row gt_right">160.0</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">110</td>
<td headers="drat" class="gt_row gt_right">3.90</td>
<td headers="wt" class="gt_row gt_right">2.620</td>
<td headers="qsec" class="gt_row gt_right">16.46</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">4</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">21.0</td>
<td headers="cyl" class="gt_row gt_right">6</td>
<td headers="disp" class="gt_row gt_right">160.0</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">110</td>
<td headers="drat" class="gt_row gt_right">3.90</td>
<td headers="wt" class="gt_row gt_right">2.875</td>
<td headers="qsec" class="gt_row gt_right">17.02</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">4</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">22.8</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">108.0</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">93</td>
<td headers="drat" class="gt_row gt_right">3.85</td>
<td headers="wt" class="gt_row gt_right">2.320</td>
<td headers="qsec" class="gt_row gt_right">18.61</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">1</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">21.4</td>
<td headers="cyl" class="gt_row gt_right">6</td>
<td headers="disp" class="gt_row gt_right">258.0</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">110</td>
<td headers="drat" class="gt_row gt_right">3.08</td>
<td headers="wt" class="gt_row gt_right">3.215</td>
<td headers="qsec" class="gt_row gt_right">19.44</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">1</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">18.7</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">360.0</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">175</td>
<td headers="drat" class="gt_row gt_right">3.15</td>
<td headers="wt" class="gt_row gt_right">3.440</td>
<td headers="qsec" class="gt_row gt_right">17.02</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">2</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">18.1</td>
<td headers="cyl" class="gt_row gt_right">6</td>
<td headers="disp" class="gt_row gt_right">225.0</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">105</td>
<td headers="drat" class="gt_row gt_right">2.76</td>
<td headers="wt" class="gt_row gt_right">3.460</td>
<td headers="qsec" class="gt_row gt_right">20.22</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">1</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">14.3</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">360.0</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">245</td>
<td headers="drat" class="gt_row gt_right">3.21</td>
<td headers="wt" class="gt_row gt_right">3.570</td>
<td headers="qsec" class="gt_row gt_right">15.84</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">4</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">24.4</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">146.7</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">62</td>
<td headers="drat" class="gt_row gt_right">3.69</td>
<td headers="wt" class="gt_row gt_right">3.190</td>
<td headers="qsec" class="gt_row gt_right">20.00</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">2</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">22.8</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">140.8</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">95</td>
<td headers="drat" class="gt_row gt_right">3.92</td>
<td headers="wt" class="gt_row gt_right">3.150</td>
<td headers="qsec" class="gt_row gt_right">22.90</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">2</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">19.2</td>
<td headers="cyl" class="gt_row gt_right">6</td>
<td headers="disp" class="gt_row gt_right">167.6</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">123</td>
<td headers="drat" class="gt_row gt_right">3.92</td>
<td headers="wt" class="gt_row gt_right">3.440</td>
<td headers="qsec" class="gt_row gt_right">18.30</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">4</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">17.8</td>
<td headers="cyl" class="gt_row gt_right">6</td>
<td headers="disp" class="gt_row gt_right">167.6</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">123</td>
<td headers="drat" class="gt_row gt_right">3.92</td>
<td headers="wt" class="gt_row gt_right">3.440</td>
<td headers="qsec" class="gt_row gt_right">18.90</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">4</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">16.4</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">275.8</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">180</td>
<td headers="drat" class="gt_row gt_right">3.07</td>
<td headers="wt" class="gt_row gt_right">4.070</td>
<td headers="qsec" class="gt_row gt_right">17.40</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">3</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">17.3</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">275.8</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">180</td>
<td headers="drat" class="gt_row gt_right">3.07</td>
<td headers="wt" class="gt_row gt_right">3.730</td>
<td headers="qsec" class="gt_row gt_right">17.60</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">3</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">15.2</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">275.8</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">180</td>
<td headers="drat" class="gt_row gt_right">3.07</td>
<td headers="wt" class="gt_row gt_right">3.780</td>
<td headers="qsec" class="gt_row gt_right">18.00</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">3</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">10.4</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">472.0</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">205</td>
<td headers="drat" class="gt_row gt_right">2.93</td>
<td headers="wt" class="gt_row gt_right">5.250</td>
<td headers="qsec" class="gt_row gt_right">17.98</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">4</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">10.4</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">460.0</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">215</td>
<td headers="drat" class="gt_row gt_right">3.00</td>
<td headers="wt" class="gt_row gt_right">5.424</td>
<td headers="qsec" class="gt_row gt_right">17.82</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">4</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">14.7</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">440.0</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">230</td>
<td headers="drat" class="gt_row gt_right">3.23</td>
<td headers="wt" class="gt_row gt_right">5.345</td>
<td headers="qsec" class="gt_row gt_right">17.42</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">4</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">32.4</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">78.7</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">66</td>
<td headers="drat" class="gt_row gt_right">4.08</td>
<td headers="wt" class="gt_row gt_right">2.200</td>
<td headers="qsec" class="gt_row gt_right">19.47</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">1</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">30.4</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">75.7</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">52</td>
<td headers="drat" class="gt_row gt_right">4.93</td>
<td headers="wt" class="gt_row gt_right">1.615</td>
<td headers="qsec" class="gt_row gt_right">18.52</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">2</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">33.9</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">71.1</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">65</td>
<td headers="drat" class="gt_row gt_right">4.22</td>
<td headers="wt" class="gt_row gt_right">1.835</td>
<td headers="qsec" class="gt_row gt_right">19.90</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">1</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">21.5</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">120.1</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">97</td>
<td headers="drat" class="gt_row gt_right">3.70</td>
<td headers="wt" class="gt_row gt_right">2.465</td>
<td headers="qsec" class="gt_row gt_right">20.01</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">1</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">15.5</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">318.0</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">150</td>
<td headers="drat" class="gt_row gt_right">2.76</td>
<td headers="wt" class="gt_row gt_right">3.520</td>
<td headers="qsec" class="gt_row gt_right">16.87</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">2</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">15.2</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">304.0</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">150</td>
<td headers="drat" class="gt_row gt_right">3.15</td>
<td headers="wt" class="gt_row gt_right">3.435</td>
<td headers="qsec" class="gt_row gt_right">17.30</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">2</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">13.3</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">350.0</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">245</td>
<td headers="drat" class="gt_row gt_right">3.73</td>
<td headers="wt" class="gt_row gt_right">3.840</td>
<td headers="qsec" class="gt_row gt_right">15.41</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">4</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">19.2</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">400.0</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">175</td>
<td headers="drat" class="gt_row gt_right">3.08</td>
<td headers="wt" class="gt_row gt_right">3.845</td>
<td headers="qsec" class="gt_row gt_right">17.05</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">0</td>
<td headers="gear" class="gt_row gt_right">3</td>
<td headers="carb" class="gt_row gt_right">2</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">27.3</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">79.0</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">66</td>
<td headers="drat" class="gt_row gt_right">4.08</td>
<td headers="wt" class="gt_row gt_right">1.935</td>
<td headers="qsec" class="gt_row gt_right">18.90</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">1</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">26.0</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">120.3</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">91</td>
<td headers="drat" class="gt_row gt_right">4.43</td>
<td headers="wt" class="gt_row gt_right">2.140</td>
<td headers="qsec" class="gt_row gt_right">16.70</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">5</td>
<td headers="carb" class="gt_row gt_right">2</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">30.4</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">95.1</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">113</td>
<td headers="drat" class="gt_row gt_right">3.77</td>
<td headers="wt" class="gt_row gt_right">1.513</td>
<td headers="qsec" class="gt_row gt_right">16.90</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">5</td>
<td headers="carb" class="gt_row gt_right">2</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">15.8</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">351.0</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">264</td>
<td headers="drat" class="gt_row gt_right">4.22</td>
<td headers="wt" class="gt_row gt_right">3.170</td>
<td headers="qsec" class="gt_row gt_right">14.50</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">5</td>
<td headers="carb" class="gt_row gt_right">4</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">19.7</td>
<td headers="cyl" class="gt_row gt_right">6</td>
<td headers="disp" class="gt_row gt_right">145.0</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">175</td>
<td headers="drat" class="gt_row gt_right">3.62</td>
<td headers="wt" class="gt_row gt_right">2.770</td>
<td headers="qsec" class="gt_row gt_right">15.50</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">5</td>
<td headers="carb" class="gt_row gt_right">6</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">15.0</td>
<td headers="cyl" class="gt_row gt_right">8</td>
<td headers="disp" class="gt_row gt_right">301.0</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">335</td>
<td headers="drat" class="gt_row gt_right">3.54</td>
<td headers="wt" class="gt_row gt_right">3.570</td>
<td headers="qsec" class="gt_row gt_right">14.60</td>
<td headers="vs" class="gt_row gt_right">0</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">5</td>
<td headers="carb" class="gt_row gt_right">8</td></tr>
    <tr><td headers="mpg" class="gt_row gt_right" style="background-color: #B2F7EF; font-weight: bold;">21.4</td>
<td headers="cyl" class="gt_row gt_right">4</td>
<td headers="disp" class="gt_row gt_right">121.0</td>
<td headers="hp" class="gt_row gt_right" style="background-color: #FFEFB5; font-weight: bold;">109</td>
<td headers="drat" class="gt_row gt_right">4.11</td>
<td headers="wt" class="gt_row gt_right">2.780</td>
<td headers="qsec" class="gt_row gt_right">18.60</td>
<td headers="vs" class="gt_row gt_right">1</td>
<td headers="am" class="gt_row gt_right">1</td>
<td headers="gear" class="gt_row gt_right">4</td>
<td headers="carb" class="gt_row gt_right">2</td></tr>
  </tbody>
  
  
</table>
</div>
