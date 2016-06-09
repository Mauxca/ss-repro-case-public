---
AuthorName: Maura Lievano
Affiliation: Goldman School of Public Policy, UC Berkeley
WorkflowTitle: My future QP
WorkflowDiagramURL: https://www.draw.io/#G0B_4tcTDMtZZUd3g4ZTlzb1NhTFk
Discipline: Public Policy
Software: R
DOI_URL:
---

##### Introduction
*Please answer these introductory questions for your case study in a few sentences.*

1) Who are you and what is your research field? Include your name, affiliation, discipline, and the background or context of your overall research that is necessary specifically to introduce your specific case study.

Hi, I am Maura Lievano, graduate student at the Goldman School of Public Policy, at UC Berkeley. My research focus is on criminal justice and want to answer questions such as why people commit crime and how institutions delivered different forms of punishment. Currently, I am working on identifying applications of machine learning methods to criminology classic questions, for example, under what circumstances individuals commit crime and how can institutions control it?


2) Define what the term "reproducibility" means to you generally and/or in the particular context of your case study.

I conceptualize reproducibility as a communicable  set of steps of a research project (or "project algorithm")  that lead from the beggining stage of data collection to the end stage of publication in a research process that allow interested individuals do exactly what I did in the project and get the same results, given the same data.


##### Workflow diagram

The core of your case study is a diagrammatic workflow sketch, which depicts your the entire pipeline of your workflow. Think of this like a circuit diagram: boxes represent steps, tools, or other disjoint components, and arrows show how outputs of particular steps feed as inputs to others. This diagram will be complemented by a textual narrative.

We recommend the site [http://draw.io](http://draw.io) for creating this diagram. Please draw your diagram so that it reads from left to right, and fills no more than half a standard US letter page. Use Helvetica font with at least 10 or 11pt size.

While creating your diagram, be sure to consider:

* specialized tools and where they enter your workflow
* the "state" of the data at each stage
* collaborators
* version control repos
* products produced at various stages (graphics, summaries, etc)
* databases
* whitepapers
* customers

Each of the two example case studies include a workflow diagram you can also use for guidance.

Please save your diagram alongside this completed case study template.

##### Workflow narrative

https://www.draw.io/#G0B_4tcTDMtZZUd3g4ZTlzb1NhTFk (see pdf)

Description of workflow -very brief, to be edited-
As shown in the diagram, I expect to spent a few weeks on reviewing existing literature on machine learning applications to criminal justice policy before selecting a few algorithms to apply to the data I am interested in. The result of this will be a few pages summary of the material studied. Based on this, I will select a few algorithms to analyze the data of interest. 

Once I have the general idea of the literature and the model, I will start the data collection process in parallel with some interviews to individuals who have studied the topic. The result of this will be a summary of the methods to use and a first, unclean version of a data set. 

Then I will clean the data set and apply the models, proceed to analyze the results and write a version for review and editing. This will iterate and hopefully I will have a decent QP on machine learning applications to criminal justice.



Referring to your diagram, describe your workflow for this specific project, from soup to nuts. Imagine walking a friend or a colleague through the basic steps, paying particular attention to links between steps. Don't forget to include "messy parts", loops, aborted efforts, and failures.

It may be helpful to consider the following questions, where interesting, applicable, and non-obvious from context. For each part of your workflow:

* **Frequency:** How often does the step happen and how long does it take?
* **Who:** Which members of your team participate (or not)?
* **Manual/Automated:** Is the step automated or does it involve human intervention (if so, is it recorded)?
* **Tools:** Which software or online tools are used in the step? How are they used?

In addition to detailing the steps of the workflow, you may wish to consider the following questions about the workflow as a whole:

* **Data:** Is your raw data online? Part of the data I plan to use is publicly avaiblae
   * Is it citeable? I will probably be unable to cite all of it because it includes individual level records of incarcerated individuals.
   * Does the license allow external researchers to publish a replication/confirmation of your published work?  Not sure about this.
* **Software:** Is the software online? Yes, I plan to use R
   * Is there documentation? Yes, the packages and libraries to be used include extense documentation
   * Are there tests? Yes
   * Are there example input files alongside the code? Yes
* **Processing:** Is your data processing workflow online? Not sure
   * Are the scripts documented? Yes
   * Would an external researcher know what order to run them in? The code, if public will be properly commented and reproducible
   * Would they know what parameters to use?

*(500-800 words)*

##### Pain points
*Describe in detail the steps of a reproducible workflow which you consider to be particularly painful. How do you handle these? How do you avoid them? (200-400 words)*

Data sharing. I consider the main challenge to identify what part of the data and in what format is subject of publicity, given that I will be dealing with sensitive information.


##### Key benefits
*Discuss one or several sections of your workflow that you feel makes your approach better than the "normal" non-reproducible workflow that others might use in your field. What does your workflow do better than the one used by your lesser-skilled colleagues and students, and why? What would you want them to learn from your example? (200-400 words)*

I highly value collaborative research and have noticed that making my work and methods transparent usually leads to a colleague catching error or inneficiencies in my code and approach. In this way, transparent and reproducible workflow is an effective way to collaborate. It also forces me to have my workflow better organized.

##### Key tools
*If applicable, provide a detailed description of a particular specialized tool that plays a key role in making your workflow reproducible, if you think that the tool might be of broader interest or relevance to a general audience. (200-400 words)*

Rnw files are very useful because it allows to write and run code and include text descriptions of any manipulations of data.

##### General questions about reproducibility

*Please provide short answers (a few sentences each) to these general questions about reproducibility and scientific research. Rough ideas are appropriate here, as these will not be published with the case study. Please feel free to answer all or only some of these questions.*

1) Why do you think that reproducibility in your domain is important?
Collaboration, accountability and efficiency are key components of research in public policy, making our work flow publics increases these traits.

2) How or where did you learn the reproducible practices described in your case study? Mentors, classes, workshops, etc.
All of the above, professors, colleagues, mentors, workshops.

3) What do you see as the major pitfalls to doing reproducible research in your domain, and do you have any suggestions for working around these? Examples could include legal, logistical, human, or technical challenges.

I consider that start with small collaborative groups in the same project/interest/discipline can build up to a broader community. I think that there are negative incentives to make our workflow and data public that might be higher that the positive incentives, but it is worth to try.

4) What do you view as the major incentives for doing reproducible research?

Efficiency, organization and the opportunity of a paradigm shift in the scientific community.

5) Are there any broad reproducibility best practices that you'd recommend for researchers in your field?
Please comment your code and make it public, even if it is not at an early stage of the research process.
Compile best coding practices and use tools like Github!

6) Would you recommend any specific websites, training courses, or books for learning more about reproducibility?
I have not really gotten all my learning from a single place, but BITSS Summer Institute and DLab workshops are a great place o start.
