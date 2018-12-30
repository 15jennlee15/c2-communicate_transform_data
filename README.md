# Course 2: Communicating and Transforming Data
This repository will house all the materials for the third course in the data science specialization using R, developed for the UO COE.

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

# Syllabus
## EDLD 610: Communicating and Transforming Data (CRN: 27553; 3 credit hours)
* **Term:** Winter 2019
* **Time:** M/W, 10-11:20
* **Classroom:** Lokey 115
* **Instructor:** Daniel Anderson, PhD
	+ *email:* (preferred contact method) [daniela@uoregon.edu](mailto:daniela@uoregon.edu)
	+ *phone:* 541-346-3317
	+ *office:* 175 Lokey
	+ *office hours*: By appointment

# Course Overview
This is the second course in a sequence of courses that will eventually lead to a *data science in educational research* specialization. This course will be taught through [R](https://cran.r-project.org), a free and open-source statistical computing environment. This course, in particular, will rely heavily on building on the first course using RStudio. This course will give students a foundation in the principles and practice of data visualization, particularly as applied to scientific and technical data. We will have weekly lectures, covering a wide variety of topics including human perception, color theory, principles of visual design, etc. We will also have weekly hands-on laboratory sessions in which students will have the opportunity to put the lecture material into practice. Often when creating effective data visualizations, it is necessary to combine and transform different data sources, and this will be a considerable focus of the course as well.


## Student Learning objectives
By the end of this course, students should be able to:

* Transform data in a variety of ways to create effective data visualizations
* Understand and fluently apply different types of data joins
* Customize ggplot2 graphics by reordering factors, creating themes, and applying ggthemes
* Create reproducible slides using ioslides/xaringan
* Create a blog using blogdown to summarize key learnings throughout the first two courses

# Course Reading List And Other Resources
All course readings are freely available online or will be provided by the
instructor. 

## Books (required)
* 	Kieran Healy, [Data Visualization: A Practical Introduction.](http://socviz.co/) Forthcoming. Princeton University Press.
* Claus Wilke, [Fundamentals of Data Visualization.](https://serialmentor.com/dataviz/) Forthcoming. O'Reilly.



# Weekly Schedule (Topics, Assignments, and Readings)

| **Week** | **Date** | **Theme**                                        | **Topics**                                     			| **Assignment Assigned** | **Assignment Due**     | **Reading**                                                                                                                                                                                                                                                          |
| :------: | :------: | :----------------------------------------------- | :----------------------------------------------------| :---------------------- | :--------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1a       | 1/7/19   | Intro to the course                              | Overview, syllabus, integrating groups         			| Final Project           | -                      | -                                                                                                                                                                                                                                                                    |
| 1b       | 1/9/19   | GitHub group project                             |                                                			| Lab 1                   | -                      | Bryan 4-8 (9 optional)                                                                                                                                                                                                                                               |
| 2a       | 1/14/19  | **Guest Lecture** Introduction to visualizations | graphs, charts, maps, diagrams, infographics   			| -                       | Lab 1                  | [Healy 4 (Show the right numbers)](https://socviz.co/groupfacettx.html#groupfacettx), [R4DS 28 (Graphics for communication)](https://r4ds.had.co.nz/graphics-for-communication.html), [Wilke 5 (Directory of visualizations)](https://serialmentor.com/dataviz/directory-of-visualizations.html)|
| 2b       | 1/16/19  | **No Class** Take-home lab                       | Babynames                          									| Lab 2                   | -                      | If needed: [Healy 2 (Get started)](https://socviz.co/gettingstarted.html#gettingstarted), [Healy 3 (Make a plot)](https://socviz.co/makeplot.html#makeplot)                                                                                                          |
| 3a       | 1/21/19  | Joins 1                                          | Keys, mutating joins, relational data 		      			| -                       | Lab 2                  | [R4DS 13 (Relational data)](https://r4ds.had.co.nz/relational-data.html)                                                                                                                                                                                             |
| 3b       | 1/23/19  | Joins 2                                          | Filtering joins                                      | Homework 1              | -                      | -                                                                                                                                                                                        						                                                                |
| 4a       | 1/28/19  | Visual perception                                | shapes, saturation. etc.                       			| -                       | -                      | [Healy 1 (Look at data)](https://socviz.co/lookatdata.html#lookatdata)                                                                                                                                                                                               |
| 4b       | 1/30/19  | Hands-on lab                                     | Nathans                                        			| Lab 3                   | Homework 1             | [Wilke 2 (Visualizing data: Mapping data onto aesthetics)](https://serialmentor.com/dataviz/aesthetic-mapping.html)                                                                                                                                                  |
| 5a       | 2/4/19   | Color                                            | color!                                         			| -                       | Lab 3                  | [Wilke 4 (Color scales)](https://serialmentor.com/dataviz/color-basics.html), [Wilke 16 (Common pitfalls of color use)](https://serialmentor.com/dataviz/color-pitfalls.html)                                                                                        |
| 5b       | 2/6/19   | **No Class/Guest Lecture** Hands-on lab          | visualizing amounts 					                  			| Lab 4			              | Final Project Proposal | [Wilke 6 (Visualizing amounts)](https://serialmentor.com/dataviz/visualizing-amounts.html)                                                                                                                                                                           |
| 6a       | 2/11/19  | Communication                                    |                                                			| -                       | Lab 4                  | [Wilke 24 (Image file formats for exporting)](https://serialmentor.com/dataviz/image-file-formats.html), [Wilke 26 (Telling a story)](https://serialmentor.com/dataviz/telling-a-story.html)                                                                         |
| 6b       | 2/13/19  | Choices and cycles                               | Take a sad plot and make it better             			| Homework 2              | - 				             | [Healy 8 (Refine your plots)](https://socviz.co/refineplots.html#refineplots), [Wilke 17 (Redundant coding)](https://serialmentor.com/dataviz/redundant-coding.html), [Wilke 20 (Balance data-to-ink ratio)](https://serialmentor.com/dataviz/balance-data-ink.html) |
| 7a       | 2/18/19  | Visualizing uncertainty													 | Probabilities as frequencies; bootstrap SEs 	        | -                       | -                      | [Wilke 16 (Visualizing Uncertainty)](https://serialmentor.com/dataviz/visualizing-uncertainty.html)                                                                                                                                                                  |
| 7b       | 2/20/19  | Tables & fonts                                   | tables (`kableExtra`, `gt`) + fonts (`extrafont`)    | Lab 5                   | Homework 2             | [Healy 5 (Tables, labels, and notes)](https://socviz.co/workgeoms.html#workgeoms), [gt tables](https://gt.rstudio.com/articles/intro-creating-gt-tables.html)                                                                                                        |
| 8a       | 2/25/19  | Websites in R Markdown                           | Rmd sites, Radix	                              			| -                       | Lab 5                  | [RMD Sites](https://bookdown.org/yihui/rmarkdown/rmarkdown-site.html), [blogdown](https://bookdown.org/yihui/blogdown/), [radix](https://rstudio.github.io/radix/)                                                                                                   |
| 8b       | 2/27/19  | Dashboards                                       |                                                			| Peer Review; Lab 6      | Portfolio Draft        | [RMD Dashboards](https://bookdown.org/yihui/rmarkdown/dashboards.html)                                                                                                                                                                                               |
| 9a       | 3/4/19   | Slides 									              		       | xaringan                              								| -                       | Lab 6                  | [Healy: Making Slides](https://kieranhealy.org/blog/archives/2018/03/24/making-slides/), [customization](https://github.com/yihui/xaringan/wiki) 					                                                                                                          |
| 9b       | 3/6/19   | Work day                               					 | 		                  																| -                       | Peer Review            | -                                                                                                                                                      																								                                                              |
| 10a      | 3/11/19  | Presentations                                    |                                                			|                         | Presentation           | -                                                                                                                                                                                                                                                                    |
| 10b      | 3/13/19  | Presentations                                    |                                                			| -                       | Presentation           | -                                                                                                                                                                                                                                                                    |
| 11       | 3/20/19  | Final Projects                                   |                                                			|                         | Final Project          | -                                                                                                                                                                                                                                                                    |

# Assignments and Grading
Your final grade will be composed of five components: 
* 6 labs at 5 points each (30 points) 
* 2 homework assignments at 10 points each (20 points) 
* 4 DataCamp modules at 5 points each (20 points) 
* five-minute data visualization "in the wild" presentation (10 points) 
* Final Project (120 points)
	+ Proposal (10 points)
	+ Peer review (30 points)
	+ Presentation (20 points)
	+ Product (60 points)

## Labs (30 points; 15%)
There are 6 labs during the course, scored at 5 points each, which must be
submitted within one week of being assigned. Labs will include designated
in-class time, but any work not completed during in-class time must be completed
on your own. Labs will be scored on a "best honest effort" basis, which
generally implies zero or full credit (i.e.,the assignment was or was not fully 
completed). However, many of the labs require students complete specific
portions before moving on to the next sections. If you find yourself stuck and
unable to proceed, **please contact the instructor for help rather than
submitting incomplete work**. Contacting the instructor is part of the "best 
honest effort", and can result in full credit for an assignment even if the the 
work is not fully complete. **If the assignment is not complete, and the student 
has not contacted the instructor for help, it is likely to result is a score of 
zero**.

## Homework (20 points; 10%)
Homework assignments are essentially extended labs, with two exceptions: (1) No
time will be designated during class to homework completion, and (2) homework
will be scored on a correct/incorrect basis. Two homework will be assigned, each
worth up to 10 points.

## DataCamp modules (20 points; 10%)
Four DataCamp modules are required to be completed, with two being assigned, and
two additional modules of your choosing. Once you have completed the modules, 
please upload a screenshot of the completion certificate to Canvas.

The following three modules are required:
* [Data Visualization with ggplot2 (Part 1)](https://www.datacamp.com/courses/data-visualization-with-ggplot2-1) (**Due before class, January 14th**)
* [Visualization Best Practices in R](https://www.datacamp.com/courses/visualization-best-practices-in-r) (**Due before class, January 21st**)

Additionally, before the end of the term (**Due before midnight, March 20**) you 
are required to complete **any two** of the following modules, of your choosing:
* [Data Visualization with ggplot2 (Part 2)](https://www.datacamp.com/courses/data-visualization-with-ggplot2-2)
* [Data Visualization with ggplot2 (Part 3)](https://www.datacamp.com/courses/data-visualization-with-ggplot2-3) 
* [Data Visualization in R](https://www.datacamp.com/courses/data-visualization-in-r)
	+ Base plotting functions
* [Data Visualization in R with ggvis](https://www.datacamp.com/courses/ggvis-data-visualization-r-tutorial)
	+ Interactive grammar of graphics
* [Interactive Data Visualization with plotly in R](https://www.datacamp.com/courses/interactive-data-visualization-with-plotly-in-r)
	+ An alternative interactive graphics package - probably more developed overall than {ggvis}
* [Interactive Data Visualization with rbokeh](https://www.datacamp.com/courses/interactive-data-visualization-with-rbokeh)
	+ Yet another interactive plotting option
* [Working with Geospatial Data in R](https://www.datacamp.com/courses/working-with-geospatial-data-in-r)
	+ Produce static maps with {ggplot2}
* [Interactive Maps with leaflet in R](https://www.datacamp.com/courses/interactive-maps-with-leaflet-in-r)
	+ Leverage the [leaflet](https://leafletjs.com) JavaScript library in R 
* [Visualizing Time Series Data in R](https://www.datacamp.com/courses/visualizing-time-series-data-in-r)
	+ Univariate and multivariate time series data visualizations
* [Communicating with Data in the Tidyverse](https://www.datacamp.com/courses/communicating-with-data-in-the-tidyverse)
	+ Customize themes, more R Markdown
* [Network Science in R - A Tidy Approach](https://www.datacamp.com/courses/network-science-in-r-a-tidy-approach)
	+ Work with and visualize network data using tidy data principles
* [Visualizing Big Data with Trelliscope](https://www.datacamp.com/courses/visualizing-big-data-with-trelliscope)
	+ Uses {ggplot2} with the {trelliscopejs} package to visualize data at scale. See [here](https://hafen.github.io/trelliscopejs/#trelliscope)

## Data visualizations "in the wild" presentation (10 points; 5%)
On the first day of the class you will be randomly assigned a date for a 
presentation. 

Presentations will start with the second class meeting. The assignment requires:
* Identifying two data visualizations intended for different audiences (e.g.,
	scientific community, popular culture, data users [teachers/educators, etc.])
* Sharing the data visualizations with the class, and discussing the following:
		+ What is trying to be communicated?
		+ How effective do you judge the visualization at communicating the content?
		  Why?
		+ At least one area of strength.
		+ At least one potential area for improvement.

Note that this project is aimed at identifying a range of data visualizations.
It would be ideal if both model data visualizations and poor data visualizations
were presented from a variety of sources. Your two visualizations **must** be
aimed at separate audiences. 

## Final Project (120 points; 60%)
The final project will include a portfolio of your data visualizations. At least
**three** different data visualizations must be included, as well as the 
history of how the visualization changed over time. Among these three 
visualizations, at least one continuous variable and one categorical variable
must be included. The portfolios must be housed on *GitHub* and be 
reproducible. In occasional situations, it can be helpful to make final 
modifications to your plot through systems outside of R (e.g., Adobe 
Illustrator, Inkscape). If you choose to make these modifications (not required)
they are the one (and only) acceptable exception to full reproducibility. 

### Proposal (10 points; 5%; **Due February 6**)
At the end of Week 5, you must include a proposal of your data visualization
portfolio that includes the following:
* Description of the data source (must be publicly available)
* Preliminary ideas (even hand sketches) of different visualizations
* Identification of the intended audience for each visualization 
		+ Note, you might consider displaying the same data/relations more than 
			once, with each plot displayed for a different audience.
* The intended message to be communicated for each plot. 


### Portfolio draft (15 points; 7.5%; **Due February 27**)
By the end of Week 8, you should have a fairly complete draft of the data 
visualizations you will be sharing in your portfolio. These should be housed
on GitHub and ready to receive feedback from your peers.

### Peer review (15 points; 7.5%; **Due March 6**)
You will be assigned to three of your peers code for their data visualizations. 
The purpose of this exercise is to learn from each other. Programming is an 
immensely open-ended enterprise and there are lots of winding paths that all 
ultimately end up at the same destination. In terms of visualization, there
is certainly plenty of room for artistic license, but certain design decisions
(as we will learn) can lead to more interpretable and better data 
communications. Thus, peer review is a chance to not only learn from others, but
get feedback on your (expected to be in-progress) design decisions.

During your peer review, you must note (a) at least three areas of strength, 
(b) at least one thing you learned from reviewing their script, and (c) at least 
one and no more than three areas for improvement for each visualization. **The
peer review should include comments on both the code leading up to the 
visualization, and the visualization itself**.

Making your code publicly available can feel daunting. The purpose of this 
portion of the final project is to help us all learn from each other, not to 
denigrate. **Under no circumstances will negative comments be tolerated**. Any 
comments that could be perceived as negative, and outside the scope of the 
code, will result in an immediate score of zero. Be constructive in your 
feedback. Be kind. We are all learning.

### Presentation (20 points; 10%)
Week 10 will include each student sharing his or her portfolio with the class.
We have 28 people in the class and only two class sessions (160 minutes total) 
to present. 

Presentation must be presented from a published 
[xaringan](https://github.com/yihui/xaringan) slide deck. 

**Prior to the start of Week 10** please send me a link to your 
published presentation. I will then pre-load all the presentations in different 
tabs on my computer.

You will have **five minutes** to share your portfolio. Please cover the 
following:
* Briefly show each visualization
* Pick 1-2 to go more in-depth, and discuss
	+ Intended audience
	+ Design choices, e.g. 
			- Colors
			- Layout
			- Choice of specific type of plot
	+ Prior version(s) and how the changes helped clarity, communication, beauty,
		etc.
	+ At least 1 major challenge encountered along the way
	+ At least 1 major victory

### Product (60 points; 30%)
The final project must include a deployed website (either an R Markdown website, 
a `flexdashboard`, or a `blogdown` site for the brave) showing your #dataviz 
portfolio, with each plot accompanied by a strong narrative/story. You are 
encouraged to show iterations of your plots, highlighting how your plot evolved 
over time. If you go the website route, a blog post showing your visualizations 
and their evolution would work great. 

The final product will be graded on the following three criteria:
* At least three different visualizations (30 points; 10 points each)
	+ Design choices
	+ Plot appropriate for given audience
	+ Evolution of the plot is clear
* Reproducibility (20 points)
	+ Should be housed on GitHub
	+ I'll clone and try to reproduce
* Deployment (10 points)
	+ Should be shareable via a link

## Extra Credit
There are two opportunities for extra credit. The first is worth up to 10 
points, and is to do an in-depth self-study of a topic not explicitly covered 
in the class and then provide a 10 minute presentation on the topic to the 
class (presentations are likely to occur on lab days). For example, 
interactive and animated graphics are not explicitly covered, but newer packages 
like [gganimate](https://gganimate.com/index.html) are powerful and fun. We also 
will not spend much time on geographic mapping, or networks. Any of these topics 
would be excellent choices for a presentation. You could also choose an area
that is covered in the class, but provide greater depth (e.g., color). It is
also important to keep in mind that this course is about communicating **and** 
transforming data, and so topics on data transformations would also be 
appropriate. For example, you may choose to present on integrating R with SQL
databases. If you are interested in giving a 10 minute talk on a topic of your
choice, please contact the instructor as soon as possible to obtain approval on
the topic and set a date for the presentation.

The second opportunity for extra credit is worth up to 5 points. You may 
complete up to one additional DataCamp module from the list above. Other modules 
that you are interested in may also be counted toward extra credit, but require 
prior approval from the instructor. 

You may combine both extra credit opportunities by, for example, going through
Charlotte Wickham's [Working with Geospatial Data in R](https://www.datacamp.com/courses/working-with-geospatial-data-in-r)
and then presenting on what you learned. Again, however, this needs to be 
approved by the instructor.

# Grading Components (200 points possible)
|  **Lower percent** |**Lower point range**  | **Grade** | **Upper point range**  | **Upper percent**|
|  :------: | :------   | :-:| :-------: | ----:|
|  0.97     | (194 pts) | A+ |           |      |
|  0.93     | (186 pts) | A  | (194 pts) | 0.97 |
|  0.90     | (180 pts) | A- | (186 pts) | 0.93 |
|  0.87     | (174 pts) | B+ | (180 pts) | 0.90 |
|  0.83     | (166 pts) | B  | (174 pts) | 0.87 |
|  0.80     | (160 pts) | B- | (166 pts) | 0.83 |
|  0.77     | (154 pts) | C+ | (160 pts) | 0.80 |
|  0.73     | (146 pts) | C  | (154 pts) | 0.77 |
|  0.70     | (140 pts) | C- | (146 pts) | 0.73 |
|           |           | F  | (140 pts) | 0.70 |

# Student Engagement Inventory
Graduate: 1 credit hour = 40 hours of student engagement (3 credit hours = 120 hours of student engagement) 

| **Educational activity** | **Hours student engaged** | **Explanatory comments (if any):**                                                                               |
| :----------------------- | :-----------------------: | :--------------------------------------------------------------------------------------------------------------- |
| Course attendance        |            26.5           | 20 meetings, at 80 minutes per meeting                                                                           |
| Assigned readings        |            26.5           | Weekly readings are assigned, and are expected to take roughly as long to complete as the in-seat time per week. |
| Projects                 |            30             | Final project, as described above                                                                                |
| Homework                 |            37             | 6 Labs, at approximately one hour per lab spent out of class (6 hours), plus 4 DataCamp modules at approximately 5 hours per module, plus two homework assignments at approximately 5 hours each |
| Total hours:             |            120            |                                                                                                                  |

# Attendance and Absence Guidelines
Attendance at all class and discussion groups is expected and required, as described above.

Students must contact the instructor in case of illness or emergencies that preclude attending class sessions. Messages can be left on the instructor's voice mail or e-mail at any time of the day or night, prior to class. If no prior arrangements have been made before class time, the absence will be unexcused. Excused absences will involve make-up assignments, with make-up assignment procedures to be discussed in class on the first day. 

If you are unable to complete an assignment due to a personal and/or family emergency, you should contact your instructor or discussion leader as soon as possible. On a case-by-case basis, the instructor will determine whether the emergency qualifies as an excused absence. 

# Expected Classroom Behavior
Students are expected to participate in classroom activities. If use of digital devices or engagement in other non-class activities during class for purposes not regarding classroom activities is critically necessary, the student should engage in these activities while on break, or check with the instructor to arrange for a 10-minute break for unusual circumstances, but only if critically necessary. 

# Course Policies 
## Diversity, Equity and Inclusion
It is the policy of the University of Oregon to support and value equity and diversity and to provide inclusive learning environments for all students.  To do so requires that we: 

* respect the dignity and essential worth of all individuals. 
* promote a culture of respect throughout the University community. 
* respect the privacy, property, and freedom of others. 
* reject bigotry, discrimination, violence, or intimidation of any kind. 
* practice personal and academic integrity and expect it from others. 
* promote the diversity of opinions, ideas and backgrounds which is the lifeblood of the university.

In this course, class discussions, projects/activities and assignments will challenge students to think critically about and be sensitive to the influence, and intersections, of race, ethnicity, nationality, documentation status, language, religion, gender, socioeconomic background, physical and cognitive ability, sexual orientation, and other cultural identities and experiences. Students will be encouraged to develop or expand their respect and understanding of such differences.

Maintaining an inclusive classroom environment where all students feel able to talk about their cultural identities and experiences, ideas, beliefs, and values will not only be my responsibility, but the responsibility of each class member as well. Behavior that disregards or diminishes another student will not be permitted for any reason. This means that no racist, ableist, transphobic, xenophobic, chauvinistic or otherwise derogatory comments will be allowed. It also means that students must pay attention and listen respectfully to each other’s comments.

## Documented Disability
Appropriate accommodations will be provided for students with documented disabilities. If you have a documented disability and require accommodation, arrange to meet with the course instructor within the first two weeks of the term. The documentation of your disability must come in writing from the Accessible Education Center in the Office of Academic Advising and Student Services.  Disabilities may include (but are not limited to) neurological impairment, orthopedic impairment, traumatic brain injury, visual impairment, chronic medical conditions, emotional/psychological disabilities, hearing impairment, and learning disabilities. For more information on Accessible Education Center, please see http://aec.uoregon.edu 

## Mandatory Reporting of Child Abuse
UO employees, including faculty, staff, and GEs, are mandatory reporters of child abuse. This statement is to advise you that that your disclosure of information about child abuse to a UO employee may trigger the UO employee’s duty to report that information to the designated authorities. Please refer to the following links for detailed information about mandatory reporting:
http://hr.uoregon.edu/policies-leaves/general-information/mandatory-reporting-child-abuse-and-neglect

## Reporting Title IX Experiences
Any student who has experienced sexual assault, relationship violence, sex or gender-based bullying, stalking, and/or sexual harassment may seek resources and help at safe.uoregon.edu. To get help by phone, a student can also call either the UO’s 24-hour hotline at 541-346-7244 [SAFE], or the non-confidential Title IX Coordinator at 541-346-8136. From the SAFE website, students may also connect to Callisto, a confidential, third-party reporting site that is not a part of the university. 

Students experiencing any other form of prohibited discrimination or harassment can find information at aaeo.uoregon.edu or contact the non-confidential AAEO office at 541-346-3123 or the Dean of Students Office at 541-346-3216 for help. As UO policy has different reporting requirements based on the nature of the reported harassment or discrimination, additional information about reporting requirements for discrimination or harassment unrelated to sexual assault, relationship violence, sex or gender based bullying, stalking, and/or sexual harassment is available at http://aaeo.uoregon.edu/content/discrimination-harassment 

Specific details about confidentiality of information and reporting obligations of employees can be found at https://titleix.uoregon.edu. 

## Academic Misconduct Policy
All students are subject to the regulations stipulated in the UO Student Conduct Code http://conduct.uoregon.edu). This code represents a compilation of important regulations, policies, and procedures pertaining to student life. It is intended to inform students of their rights and responsibilities during their association with this institution, and to provide general guidance for enforcing those regulations and policies essential to the educational and research missions of the University.  

## Conflict Resolution 
Several options, both informal and formal, are available to resolve conflicts for students who believe they have been subjected to or have witnessed bias, unfairness, or other improper treatment. 

It is important to exhaust the administrative remedies available to you including discussing the conflict with the specific individual, contacting the Department Head, or within the College of Education, you can contact the Associate Dean for Academic Affairs and Equity (Krista Chronister, 346-2415, kmg@uoregon.edu). Outside the College, you can contact: 
* UO Bias Response Team: 346-3216 http://bias.uoregon.edu/whatbrt.htm 
* Affirmative Action and Equal Opportunity: 346-3123 http://aaeo.uoregon.edu/

## Grievance Policy
A student or group of students of the College of Education may appeal decisions or actions pertaining to admissions, programs, evaluation of performance and program retention and completion. Students who decide to file a grievance should follow the student grievance procedure, or alternative ways to file a grievance outlined in the Student Grievance Policy (https://education.uoregon.edu/academics/student-grievance) or enter search: student grievance.

## In Case of Inclement Weather 
In the event the University operates on a curtailed schedule or closes, UO media relations will notify the Eugene-Springfield area radio and television stations as quickly as possible. In addition, a notice regarding the university’s schedule will be posted on the UO main home page (in the “News” section) at http://www.uoregon.edu. Additional information is available at http://hr.uoregon.edu/policy/weather.html.

If an individual class must be canceled due to inclement weather, illness, or other reason, a notice will be posted on Canvas or via email. During periods of inclement weather, please check Canvas and your email rather than contact department personnel. Due to unsafe travel conditions, departmental staff may be limited and unable to handle the volume of calls from you and others.

## Course Incomplete Policy
Students are expected to be familiar with university policy regarding grades of “incomplete” and the time line for completion. For details on the policy and procedures regarding incompletes, Please see: https://education.uoregon.edu/academics/incompletes-courses
