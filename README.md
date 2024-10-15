# Introduction to research

15th October 2024
S. Coffey

This document is to provide some starting points for those beginning in clinical research, particularly focused on cardiology, using online resources. This is primarily for summer students and BMedSci students, where time is short, but hopefully the broad brushes of the project have already been mapped out. Not included are all the other parts of protocol development, obtaining ethical and locality approval, patient information sheets and consent forms, data governance, etc.

Avoid non-open source software where possible - do not use Stata, SPSS, GraphPad Prism, Endnote etc. You will not have access to these when you graduate. Use the open-source alternative. The only exception to this is Microsoft Word, while I have used Latex, Github, etc, at the end of the day, clinicians are only going to use Word documents, so you are stuck with them outside of the rare occasion when you won't have any clinical collaborators.

The best course for thinking about research is Richard McElreath's Statistical Rethinking course and book (the 2024 version can be found here: [Statistical Rethinking 2024](https://github.com/rmcelreath/stat_rethinking_2024)). This is not an introductory course, so I would recommend in order:

1. First learn about **causal inference**. Thinking about your research project using a causal inference framework will ensure that you look for the important things in the literature review, collect the right data, analyse the data correctly, and then present your results appropriately - in short, it will allow you to develop a protocol to answer your research question as accurately as possible. This online course is excellent, and will take you from the basics to a useable level, and there is an associated textbook if you want more details. You don't need to be familiar with R for the course.
   
[Causal Diagrams: Draw your assumptions before your conclusions](https://www.edx.org/learn/data-analysis/harvard-university-causal-diagrams-draw-your-assumptions-before-your-conclusions)

2. While you are doing this course, develop a **a running project document**, the equivalent of a lab notebook for a laboratory based project. At this draft stage, just put down what you know about the subject background in a few paragraphs, then start writing your outline of methods, and what the results should roughly look like. Do not stop to make this look good at this stage, do not put in citations, and do not look things up - all of that comes later, and will only interrupt the flow at this stage.  Hopefully before you have started the research, some of this will already have been done in your project proposal. You should have a first draft done by the first week of the project. Draw a rough directed acyclic graph (DAG) of your main research question - you can update this later as you become more familiar with DAGs from the Causal Diagrams course, and as you complete your literature review. Develop an outline Gantt chart for how you will spend your time during your project. You can add any notes or plans for future projects or substudies to this document.
3. Now that you are developing project specific information, it is time to create a **project folder**. If you are working with me, I will probably already have one of these created. If not, or you want to have your own away from prying eyes, you can look at the document here in this repo. Hopefully I will do a template here on Github at some point. 

4. While still doing Prof Hernán's course, start your **literature review**. Do not use Endnote as it costs money - use Zotero. 
The University of Otago library has some excellent pages on doing a literature review [Reviewing Literature](https://otago.libguides.com/thesisinformation/reviewing_literature) . It is very worthwhile speaking to the subject librarian - you can find contact details for the Medicine librarian [here](https://otago.libguides.com/medicine). Keep a database of search terms and papers reviewed (more information on this is available at the preceding websites). Your main aims with a literature review are to help inform a causal scientific model, and, ideally, inform priors for your statistical analysis. At the very least, it is worthwile identifying bounds on likely causal and confounding associations. As you go through your literature review, update your running project document with the main points (i.e. those that directly affect your scientific model), with the details kept in your review database. 

   If there are no appropriate recent published reviews, and you do the literature review well enough, it can often be published separately. If you are planning on doing an intercalated MB PhD, you should aim to do this, as otherwise the literature review often seems quite out of date by the time you get to the time of thesis submission four or five years later. Regardless of whether you are publishing it separately or not, you will need to write up the literature review as a chapter in your thesis.

5. You should not have collected or looked at any real data by this point. Before you do this, it's time to **finalise the proposed research plan**. I recommend now writing out a publication style document, with background, methods, and results. The background just needs to be a couple of paragraphs long, and then a paragraph stating the aim of the research.

   The methods should have the following sections, as appropriate: Study overview (this is very important, and the place where you state the primary study estimand), study participants (include inclusion and exclusion criteria as appropriate), outcomes assessed, other study variable collected, and proposed statistical analysis. If this is really detailed, then you can have a separate Statistical Analysis Plan, but in general this won't be needed for projects of this size. If you are going to be collecting data yourself, make the outcomes and other study variables detailed - use the [Cardiovascular and Stroke Endpoint Definitions](https://www.ahajournals.org/doi/10.1161/CIRCULATIONAHA.117.033502) if possible, or define other variables specifically (e.g. does history of cardiovascular disease only include acute or chronic coronary syndromes, or can it include asymptomatic coronary disease seen on CT?). The type of each variable should be described (e.g. Categorical - Yes/No/Unknown/NA; Continuous - positive real number; etc.) 
  
   The results should have placeholders for the actual results (e.g. "The mean age of participants was XX years. XX% had type 2 diabetes.") Put in ghost tables and figures at this point (that is, show a blank figure but with labelled x and y axes).

   Check the [Equator network](https://www.equator-network.org) for checklists for reporting so that everything will be covered when you get to it later.

6. **Collect data** if needed. Do not, under any circumstances, use Excel to collect or analyse. Use [Redcap](https://redcap.otago.ac.nz). You will need to send an email to Ask Otago to get access to Redcap.

7. If you have not learned **R** before, do not worry. Install R by going to [The R Project for Statistical Computing](https://www.r-project.org) and clicking on CRAN to download the latest version. There is a mirror in [Auckland](https://cran.stat.auckland.ac.nz/). Then download RStudio, which makes using R much easier: [RStudio IDE](https://posit.co/downloads/). 

   This course is an excellent starting point for learning R:
[Statistical Analysis with R for Public Health Specialization on Coursera](https://www.coursera.org/specializations/statistical-analysis-r-public-health)
Don't worry if it feels like you never master R, I don't think anyone ever does. Ideally when you are using R, you should have two monitors - one for RStudio, the other for a search engine for you to look up whatever it is you are trying to get R to do.

8. Now you're ready for the **data analysis** - make sure the folders are ready, and follow the methods you have already described.

9. Once this is done, it's time to **finish writing** the manuscript. You can fill in the blanks in the Results section in your manuscript and then write the Discussion. This should be short - first paragraph is summarising the results of your research, then two paragraphs putting this into context of previous results (which you will have from your literature review), then limitations of the research, and then a future research paragraph (what are the main unanswered questions? What is the next question to be answered?). Finally, a single paragraph conclusion to wrap everything up. After this, you can write the abstract using the main manuscript to guide you.




