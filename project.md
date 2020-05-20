---
layout: default
keywords:
comments: false

title: Project
description: One of CS230's main goals is to prepare you to apply machine learning algorithms to real-world tasks, or to leave you well-qualified to start machine learning or AI research. The final project is intended to start you in these directions.
buttons: [past-projects]
micro_nav: true
---

# Getting Started

## Project Starter Package

The teaching team has put together a [github repository](https://github.com/cs230-stanford/cs230-code-examples) with project code examples, including a computer vision and a natural language processing example (both in Tensorflow and Pytorch). There is also a series of [posts](https://cs230.stanford.edu/blog/) to help you familiarize yourself with the project code examples, get ideas on how to structure your deep learning project code, and to setup AWS. The code examples posted are optional and are only meant to help you with your final project. The code can be reused in your projects, but the examples presented are not complex enough to meet the expectations of a quarterly project.


## Project Topics

This quarter in CS230, you will learn about a wide range of deep learning applications. Part of the learning will be online, during in-class lectures and when completing assignments, but you will really experience hands-on work in your final project. We would like you to choose wisely a project that fits your interests. One that would be both motivating and technically challenging.

Most students do one of three kinds of projects:

 * **Application project.** This is by far the most common: Pick an application that interests you, and explore how best to apply learning algorithms to solve it.
 * **Algorithmic project.** Pick a problem or family of problems, and develop a new learning algorithm, or a novel variant of an existing algorithm, to solve it.
 * **Theoretical project.** Prove some interesting/non-trivial properties of a new or an existing learning algorithm. (This is often quite difficult, and so very few, if any, projects will be purely theoretical.)
Some projects will also combine elements of applications and algorithms.

Many fantastic class projects come from students picking either an application area that they're interested in, or picking some subfield of machine learning that they want to explore more. So, pick something that you can get excited and passionate about! Be brave rather than timid, and do feel free to propose ambitious things that you're excited about. (Just be sure to ask us for help if you're uncertain how to best get started.) Alternatively, if you're already working on a research or industry project that deep learning might apply to, then you may already have a great project idea.

## Project Hints

A very good CS230 project will be a publishable or nearly-publishable piece of work. Each year, some number of students continue working on their projects after completing CS230, submitting their work to a conferences or journals. Thus, for inspiration, you might also look at some recent deep learning research papers. Two of the main machine learning conferences are [ICML](https://icml.cc/) and [NeurIPS](https://nips.cc/). You may also want to look at class projects from previous years of CS230 ([Fall 2017](/past-projects/#fall-2017), [Winter 2018](/past-projects/#winter-2018), [Spring 2018](/past-projects/#spring-2018), [Fall 2018](/past-projects/#fall-2018)) and other machine learning/deep learning classes ([CS229](http://cs229.stanford.edu/), [CS229A](https://web.stanford.edu/class/cs229a/), [CS221](http://web.stanford.edu/class/cs221/), [CS224N](http://web.stanford.edu/class/cs224n/), [CS231N](http://cs231n.stanford.edu/)) is a good way to get ideas. Finally, we crowdsourced and curated a list of ideas that you can view [here](https://docs.google.com/spreadsheets/d/e/2PACX-1vQTET1ylqUtE0hMsuunRcIXcoHTiOND8-898qMTP62rx0vscWynxY2kseLDwpaJ5jIG9RqurncTQFOz/pubhtml?gid=1152827187&single=true) (requires Stanford login).

Once you have identified a topic of interest, it can be useful to look up existing research on relevant topics by searching related keywords on an academic search engine such as: [http://scholar.google.com](http://scholar.google.com). Another important aspect of designing your project is to identify one or several datasets suitable for your topic of interest. If that data needs considerable pre-processing  to suit your task, or that you intend to collect the needed data yourself, keep in mind that this is only one part of the expected project work, but can often take considerable time. We still expect a solid methodology and discussion of results, so pace your project accordingly.

Notes on a few specific types of projects:

 * **Computation power.** Amazon Web Services is sponsoring the CS230 projects by providing you with GPU credits to run your experiments! We will update regarding how to retrieve your GPU credits. Alternatively Google Cloud and Microsoft Azure offer free academic units which you can apply to.
 * **Preprocessed datasets.** While we don't want you to have to spend much time collecting raw data, the process of inspecting and visualizing the data, trying out different types of preprocessing, and doing error analysis is often an important part of machine learning. Hence if you choose to use preprepared datasets (e.g. from Kaggle, the UCI machine learning repository, etc.) we encourage you to do some data exploration and analysis to get familiar with the problem.
 * **Replicating results.** Replicating the results in a paper can be a good way to learn. However, we ask that instead of just replicating a paper, also try using the technique on another application, or do some analysis of how each component of the model contributes to final performance.

# Project Deliverables

This section contains the detailed instructions for the different parts of your project.

**Submission:** We will be using Gradescope for submission of all five parts of the final project. We’ll announce when submissions are open for each part. You should submit on Gradescope as a group: that is, for each part, please make one submission for your entire project group and tag your team members.

**Evaluation:** We will not be disclosing the breakdown of the 50% that the final project is worth amongst the different parts, but the video and final report will combine to be the majority of the grade. **Attendance and participation during your TA meetings will also be considered.** Projects will be evaluated based on:

 * The technical quality of the work. (I.e., Does the technical material make sense? Are the things tried reasonable? Are the proposed algorithms or applications clever and interesting? Do the authors convey novel insight about the problem and/or algorithms?)
 * Significance. (Did the authors choose an interesting or a “real" problem to work on, or only a small “toy" problem? Is this work likely to be useful and/or have impact?)
 * The novelty of the work. (Is this project applying a common technique to a well-studied problem, or is the problem or method relatively unexplored?)

In order to highlight these components, it is important you present a solid discussion regarding the learnings from the development of your method, and summarizing how your work compares to existing approaches.



## Proposal

**Deadline:** {{ site.course.project_timeline.proposal | date: site.course.project_timeline.long_date_format }}

In the project proposal, you'll pick a project idea to work on early and receive feedback from the TAs. If your proposed project will be done jointly with a different class' project, you should obtain approval from the other instructor and approval from us. Please come to the project office hours to discuss with us if you would like to do a joint project. You should submit your proposals on Gradescope. All students should already be added to the course page on Gradescope via your SUNet IDs. If you are not, please create an account with **your Stanford email** and enroll in CS230.

In the proposal, below your project title, include the project category. The category can be one of:

 * Computer Vision
 * Natural Language Processing
 * Generative Modeling
 * Speech Recognition
 * Reinforcement Learning
 * Healthcare
 * Others (Please specify!)

Your project proposal should include the following information:
 * What is the problem that you will be investigating? Why is it interesting?
 * What are the challenges of this project?
 * What dataset are you using? How do you plan to collect it?
 * What method or algorithm are you proposing? If there are existing implementations, will you use them and how? How do you plan to improve or modify such implementations?
 * What reading will you examine to provide context and background? If relevant, what papers do you refer to?
 * How will you evaluate your results? Qualitatively, what kind of results do you expect (e.g. plots or figures)? Quantitatively, what kind of analysis will you use to evaluate and/or compare your results (e.g. what performance metrics or statistical tests)?

Presenting pointers to one relevant dataset and one example of prior research on the topic are a valuable (optional) addition.
We link one past example of a good project proposal [here](/winter2020/example_project_proposal.pdf) and a [latex template](https://www.overleaf.com/read/jcqmtbqhkrxg).


| **Project mentors** | Based off of the topic you choose in your proposal, we’ll suggest a project mentor given the areas of expertise of the TAs. This is just a recommendation; feel free to speak with other TAs as well.
| **Format** | Your proposal should be a PDF document, giving the title of the project, the project category, the full names of all of your team members, the SUNet ID of your team members, and a 300-500 word description of what you plan to do.
| **Grading** | The project proposal is mainly intended to make sure you decide on a project topic and get feedback from TAs early. As long as your proposal follows the instructions above and the project seems to have been thought out with a reasonable plan, you should do well on the proposal.
| **Submission** | Submit on Gradescope (see description under deadline for instructions)

## Milestone #1

**Deadline:** {{ site.course.project_timeline.milestone1 | date: site.course.project_timeline.long_date_format }}

By the first milestone, you should have completed the following:

* Obtained at least one dataset on your preferred work environment (locally, AWS, Colab)
* Be able to access the data in Python via some dataloader
* Run a very simple end-to-end baseline model. This baseline does not have to be complicated - eg:
	* A logistic regression model that operates on simple features
	* Default models included in Tensorflow/Pytorch official packages
	* Public implementations of GANs or Wavenets

We will look for the following in the writeup:

* At least **2 pages of content, but no more than 3** (not including references)
* Thorough description of your **dataset**: basic statistics - class distributions, general data size, number of samples, as well as implications these properties will have on the project.
* Description of your overall task. Include a background section introducing previous approaches.
* Results from your **baseline**. Include hard data or results (accuracy, F1 score, generated examples etc)
* Concrete next steps for the next milestone. These could be one of the following:
	* Specific improvements to the existing baseline
	* Applying a different approach to your task in a novel way, and adapting public code to work with your project
	* Implementing a particular paper from scratch
	* Collecting new data and building a different, more useful dataset
	* Note: feel free to list multiple new directions, but please select one approach in particular to focus on. Explain why this approach was chosen, as well as specific subgoals required. Work with your Project TA to establish clear goals.

## Milestone #2

**Deadline:** {{ site.course.project_timeline.milestone2 | date: site.course.project_timeline.long_date_format }}

By the first milestone, you should have attempted an approach as described above and identified further steps. This second milestone will be an expansion of the first one. Broadly, we will be looking for the following:

* Good motivation for the project and an explanation of the problem statement
* Literature review describing task and prior approaches in detail
* A description of the dataset, describing basic statistics and their implications
* Detailed and clear explanation of the selected methodology and approach
* Working implementation (code) submitted
* Experiments or results using concrete quantitative metrics or qualitative analysis comparing your new method against preexisting baselines or previous milestone results. 
* Analysis on whether the results are as expected 
* Concrete next steps for the final report. This should be one final effort at improving your project. Explain why this approach was chosen, as well as specific subgoals required.

Think of this milestone as a slightly shorter / less comprehensive version of the final report. Please follow these guidelines:

| **Format** | The writeup should be **at least 3 pages** and **at most 4 pagees** of content (not including references). In addition, you can include an optional **appendix**. This appendix can be of **max 4 pages of content**. If you do include an appendix, it should **only** contain tables and figures and their captions, no other paragraphs. During grading we'll focus mostly on the main writeup and may or may not look at the appendix. You should include all of the most important information, figures, and tables in the main writeup.
| **Code** | Please include a link to a Github repository with the code for your final project. You do not have to include the data or additional libraries. Your code should be easily runnable without much tinkering and should show either novel implementations or substantial modifications of preexisting codebases.
| **Grading** | We'll be looking for detailed and clear descriptions for the following categories: problem statement, previous approaches, dataset, methods, results, analysis, next steps. Make sure to address the specific points mentioned above for each of these categories.
| **Submission** | Submit on Gradescope.


## Video Report

**Submission Deadline:** {{ site.course.project_timeline.poster_and_report | date: site.course.project_timeline.long_date_format }} **(No late days allowed)**

Your video is required to be a 3 minute summary of your work. Include diagrams, figures and charts to illustrate the highlights of your work. The video needs to be visually appealing, but also illustrate technical details of your project.

If possible, try to come up with creative visualizations of your project. These could include:

* System diagrams
* More detailed examples of data that don’t fit in the space of your report
* Live demonstrations for end-to-end systems

We recommend searching for conference presentation sessions (AAAI, Neurips, ECCV, ICML, ICLR etc) and following those formats.

## Final Report

**Deadline:** {{ site.course.project_timeline.poster_and_report | date: site.course.project_timeline.long_date_format }} **(No late days allowed)**

The final report should contain a comprehensive account of your project. We expect the report to be thorough, yet concise. Broadly, we will be looking for the following:

 * Good motivation for the project and an explanation of the problem statement
 * A description of the data
 * Any hyperparameter and architecture choices that were explored
 * Presentation of results
 * Analysis of results
 * Any insights and discussions relevant to the project
 * References

 After the class, we will post all the final writeups online so that you can read about each other’s work. If you do not want your write-up to be posted online, then please create a private Piazza post.

 | **Format** | Final project writeups can be **at most 5 pages** long (including appendices and figures). We will allow for extra pages containing only references. If you did this work in collaboration with someone else, or if someone else (such as another professor) had advised you on this work, your write-up must fully acknowledge their contributions. For shared projects, we also require that you submit the final report from the class you're sharing the project with. You are strongly encouraged to use this [format](/files/formatting-instructions-cs230.pdf) (here's a link to the [overleaf files](https://www.overleaf.com/read/jcqmtbqhkrxg)). If you are not using this format, make sure to include all sections given in the format. If you prefer to use Microsoft Word, you may refer to the [CVPR template](http://cvpr2019.thecvf.com/files/cvpr2019AuthorKit.zip) or the [IEEE template](https://www.ieee.org/conferences/publishing/templates.html).
 | **Contributions** | Please include a section that describes what each team member worked on and contributed to the project.
 | **Code** | Please include a link to a Github repository with the code for your final project. You do not have to include the data or additional libraries.
 | **Grading** | The final report will be judged based off of the clarity of the report, the relevance of the project to topics taught in CS230, the novelty of the problem, and the technical quality and significance of the work.
 | **Submission** | Submit on Gradescope.
