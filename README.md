# GEOG 712 Reproducible Research Workflow with GitHub and R

## School of Geography and Earth Sciences, McMaster University

## Course Description[^1]

Scientific discovery is typically a collective process, as researchers build their work on the preceding efforts of other researchers. This is certainly the case for theory, empirical evidence, and methods, as empirical researchers use analytical techniques developed by methodologists, theoreticians build on up-to-date evidence, and data collection inspires new methods of analysis. The reality is that contemporary research is not possible in isolation. A key element of the web of research relationships is the basic unit of research output, which typically takes the form of a journal paper, book chapter, or report. This unit of output, however, represents only the face of a multilayered process, and by its very nature is limited in the amount of information that it can communicate. 

Increasingly, the development of recent technologies makes it easier and less expensive to communicate with greater efficiency. From data repositories to supplementary e-content in journals, as well as data policy requirements of research funders, there is a strong incentive for research to become more open and reproducible. Reproducibility means that research results can be verified independently, including all relevant assumptions and decisions. Every figure, every table, and every result are open for inspection, including the processes used to generate them. Research reproducibility is essential to maintain trust in the process, and has numerous advantages, including accelerating discovery and reducing inequality in access to research tools and results. Furthermore, other researchers can more easily use methods and tools if they are open. Not surprisingly, as newer technologies facilitate the transfer of research findings (including open data, open software, and open publishing), there has been a growth of interest in ways of achieving openness and reproducibility.

The objective of this course is to equip students with the fundamental concepts and tools needed to develop a reproducible research workflow.  The course should be of interest to new graduate students in the sciences and social sciences, and is relevant to research involving qualitative or quantitative data. The course is also appropriate for experienced researchers who would like to update their workflow to comply with reproducibility criteria.

The course will cover the following topics:

1) Fundamentals of reproducible research
2) Basic tools for implementing a reproducible research workflow: GitHub and R 
3) Data Management Plans
4) Creating basic units of shareable code
5) Documenting the process of doing research
6) Generating reproducible research documents

By the end of the course, the students will produce a report with all the necessary components to make it a unit of reproducible research. In the spirit of the course, resources and materials will be based on mostly open resources.

## Instructors

| Antonio Paez  | Professor |
| :------       | :-----------|
|               | Office:	GSB 236 |
|               | Office Hours:	Tuesday 11:30 am – 12:30 pm |
|               | Phone:	(905) 525-9140, ext. 26099 |
|               | Email:	paezha@mcmaster.ca |

| Krysha Dukacz | GWF Data Manager |
| :------       | :-----------|
|               | Office:	GSB 218 |
|               | Office Hours:	TBD |
|               | Phone:	(905) 525-9140, ext. 20132 |
|               | Email:	dukaczka@mcmaster.ca |

## Organization

The course will be organized in weekly 2-hour meetings. The format of the meetings will be a combination of seminar-style discussion, hands-on activities, and guest speakers. The topics and readings are found in the Course Schedule.

## Readings and Resources

Students are responsible for completing the readings indicated in the Course Schedule. Any resources that are not open will be shared by the instructors. 

## Assessment

Students will be assessed based on the completion of a sequence of activities. Note that the activities are designed to combine towards one final deliverable, so it is not advisable to skip any of them.

|   |   |
|---|---|
|Activity 1: R Markdown Exercise          |	5%|
|Activity 2: Version Control Exercise     | 5%|
|Activity 3: Initial DMP                  |	10%|
|Activity 4: Updated DMP                  | 10%|
|Activity 5: Data Package                 |	15%|
|Activity 6: Data Analysis Documentation  |	15%|
|Activity 7: Peer Review Exercise         | 20%|
|Final Deliverable                        | 20%|

McMaster’s graduate grading system will be used. Note that according to section 2.5.3 of the Graduate Calendar located at http://www.mcmaster.ca/graduate/grad_calendar.pdf passing grades are A+, A, A-, B+, B and B- only.

## Academic Dishonesty

Academic dishonesty consists of misrepresentation by deception or by other fraudulent means and can result in serious consequences, e.g. the grade of zero on an assignment, loss of credit with a notation on the transcript (notation reads: “Grade of F assigned for academic dishonesty”), and/or suspension or expulsion from the university.
It is your responsibility to understand what constitutes academic dishonesty.  For information on the various kinds of academic dishonesty please refer to the Academic Integrity Policy, specifically Appendix 3, located at http://www.mcmaster.ca/univsec/policy/AcademicIntegrity.pdf

The following illustrates only three forms of academic dishonesty:

1.	Plagiarism, e.g. the submission of work that is not one’s own or for which other credit has been obtained.
2.	Improper collaboration in group work.
3.	Copying or using unauthorized aids tests and examinations.

## Course Schedule (September 2019)

**Week 1** (Sept. 11)  
_Topic_:	[Course overview and introduction: Why reproducible research?](https://github.com/paezha/Reproducible-Research-Workflow/tree/master/Session-01-Why-Reproducible-Research)    
_Readings_:	No readings this week  
_For discussion_: Principles of open science, advantages, funding and policy environment, journal policies and the publication process, roadmap for course

**Week 2** (Sept. 18)
_Topic_:	[R + RStudio + markdown](https://github.com/paezha/Reproducible-Research-Workflow/tree/master/Session-02-R-and-Markdown)     
_Suggested Readings_:	   
  [What is R?](https://www.r-project.org/about.html)  
  [R for Data Science](https://r4ds.had.co.nz/)   
  [What is Markdown](https://rmoff.net/2017/09/12/what-is-markdown-and-why-is-it-awesome/)  
_Activity 1_: 	Use markdown to create a document with basic operations in R

**Week 3** (Sept. 25)
_Topic_:	[Version Control and GitHub](https://github.com/paezha/Reproducible-Research-Workflow/tree/master/Session-03-Git-and-GitHub)  
_Readings_:  
[What is version control?](https://en.wikipedia.org/wiki/Version_control)  
[What is GitHub?](https://www.economist.com/the-economist-explains/2018/06/18/what-is-github)  
_Activity 2_: 	Post a README notice in GitHub and one document with basic operations in R

**Week 4** (Oct. 2)  
_Topic_:	[Data Management Plans (DMP): Principles](https://github.com/paezha/Reproducible-Research-Workflow/tree/master/Session-04-Research-Data-Management-Principles)  
_Readings_:	  
[10 aspects of highly effective research data](https://www.elsevier.com/connect/10-aspects-of-highly-effective-research-data)  
_Activity_:	Create a list of data that you will be creating and using as part of your project  
   
**Week 5** (Oct. 9) 
_Topic_:	[Data Management Plans (DMP): Tools](https://github.com/paezha/Reproducible-Research-Workflow/tree/master/Session-05-Data-Management-Plans)  
_Readings_:	TBD  
_Activity 3_: 	Write an initial DMP and post in GitHub

**Week 6** (Oct. 16)
_Topic_:	Reading week  
_Readings_:	N/A

**Week 7** (Oct. 23)  
_Topic_:	[Forensic issues and archiving](https://github.com/paezha/Reproducible-Research-Workflow/tree/master/Session-06-Forensic-Issues-and-Archiving)  
_Readings_:	TBD  
_Activity 4_:	Update the DMP and post in GitHub  

**Week 8** (Oct. 30)  
_Topic_:	[Creating packages in R and documenting datasets](https://github.com/paezha/Reproducible-Research-Workflow/tree/master/Session-07-Creating-R-Packages-and-Documenting-Data)  
_Readings_:  
[Writing an R package from scratch](https://hilaryparker.com/2014/04/29/writing-an-r-package-from-scratch/)  
[R Package Primer - A minimal Example](https://kbroman.org/pkg_primer/)  
[R Packages](http://r-pkgs.had.co.nz/)  
[Building R Packages](https://rstats-pkgs.readthedocs.io/en/latest/index.html)  
_Activity 5_: 	Create a small package with a dataset  

**Week 9** (Nov. 6)
_Topic_:	[Documenting data analysis and use of RMarkdown](https://github.com/paezha/Reproducible-Research-Workflow/tree/master/Session-08-Documenting-Data-Analysis-with-RMarkdown)  
_Readings_:  	 
[Ten Simple Rules for Reproducible Computational Research](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003285)  
[Best Practices for Scientific Computing](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1001745)  
_Activity 6_: 	Create an R Makdown file with documented data analysis (a vignette for your package)

**Week 10** (Nov. 13) 
_Topic_:	[Peer review and collaboration](https://github.com/paezha/Reproducible-Research-Workflow/tree/master/Session-09-Peer-Review-and-Collaboration)  
_Readings_: Review readings of Sessions 7 and 8  
_Activity 7_: 	In-class activity peer reviewing packages, vignettes, and revisions due in GitHub

**Week 11** (Nov. 20)
_Topic_:	[`Rticles` and practical issues preparing self-contained open research documents (math notation and figures)](https://github.com/paezha/Reproducible-Research-Workflow/tree/master/Session-10-Rticles-Math-and-Figures)  
_Readings_:  
[LaTeX for Beginners](http://www.docs.is.ed.ac.uk/skills/documents/3722/3722-2014.pdf)  
[`ggplot2`: A Package for a Grammar of Graphics](https://ggplot2.tidyverse.org/)  
_Activity_: 	No activity this week

**Week 12** (Nov. 27)
_Topic_:	[`Rticles` and practical issues preparing self-contained open research documents (tables and citations)](https://github.com/paezha/Reproducible-Research-Workflow/tree/master/Session-11-Rticles-Tables-and-Citations)  
_Readings_:	 
[BibTeX](http://www.bibtex.org/)  
[KableExtra for HTML](https://cran.r-project.org/web/packages/kableExtra/vignettes/awesome_table_in_html.html)  
[KableExtra for PDF](https://haozhu233.github.io/kableExtra/awesome_table_in_pdf.pdf)  
_Activity_:	Final deliverable due on DATE TBD.

**Week 13** (Dec. 4)
_Topic_:	Extras: 3D plots  
_Readings_:	No readings assigned  

[^1]:
The University reserves the right to change any aspect of this course outline.
