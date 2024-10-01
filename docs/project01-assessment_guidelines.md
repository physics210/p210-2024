# Project 01 assessment guidelines
**Last update:** Sept 30, 2024

## *Overview*

The project report does not need to follow a specific structure, but you should use section titles to help orient and guide the reader.

As described in the [syllabus](https://physics210.github.io/p210-2024/syllabus.html), projects are given feedback by the graders and an overall Editorial Decision, such as Major Revisions or Accepted for Publication (aka Publish). Projects that have been accepted for publication can earn one ("Notable") or two ("Exemplary") distinction points by going above and beyond expectations and producing work that warrants sharing with the entire class. The process to apply to be considered for distinction points is detailed in the [Project 01 Distinction Proposal Form](https://canvas.ubc.ca/courses/146757/assignments/1982054?module_item_id=7358568) on Canvas and distinction points are awarded by Joss (the "editor"), as opposed to the graders (the "referees").

Much like what happens when practicing scientists submit their work to academic journals, even a relatively high-quality first submission is likely to receive an Editorial Decision of minor or Major Revisions because the grader (referee) will inevitably have many suggestions to improve the overall quality of your project and its report.

## *Feedback categories*

This section details the feedback categories that we will consider when reviewing your projects, which also provide a useful framework in which you can assess if your project is complete and ready to submit.

When looking at the way you have incorporated new physics, expanded the code in other ways or conducted your investigation, we want to consider multiple dimensions. We will look at ambition in terms of implementation difficulty and sophistication. We will also look at ambition in terms of breadth, meaning the number of different ways you expanded the simulation or the number of dimensions along which you performed your investigation. Finally, we will also look at the overall creativity of your investigation, of how you expanded the provided physics and code, and of how effectively you communicated your findings using visualizations and the written word. All of this will be placed in the context of how much you needed to extend yourself in completing this project, as communicated in the answers to your reflection questions.

The feedback you receive from the referees will fall into the following categories and sub-categories:

| Project 01 feedback categories | |
| :--- | :--- |
| **Simulation and simulation physics** | **Ambition and correctness:** How did you extend yourself to incorporate the physics used in your simulation (considerations include creativity, translating physics into code and new physics you learned or developed a more thorough understanding of)? Was your physics implemented correctly in the simulation? |
|  | **Communication of assumptions and context:** Is the simulation context sufficiently described such that the relevance of all incorporated physics ideas can be understood? Are relevant assumptions clearly stated and justified? Are references cited from within the text, as appropriate?
| **Coding** | **Ambition and application:** How well did you apply the coding techniques learned in this course or extend yourslef to learn new-to-you techniques? Does the code run properly?
| | **Effective coding practices:** Was an appropriate effort made to make the code efficient, readable, concise and/or final (further details below)? |
| **Communication of investigation** | **Written:** Was a clear research question asked? Was the research question answered effectively via a conclusion? Was the conclusion supported by the built-up evidence presented in the body of the report? Are limitations and next steps discussed in sufficient detail to provide an accurate picture of the results and actionable next steps? Is the overall report structured effectively, with section titles as needed? |
| | **Visualizations:** Is there a visualization that provides the main information used to answer the research question? Is there a static multi-panel graph that provides insight into the behaviour of the simulation? Is each visualization in the body of the project report important for and incorporated effectively into the overall communication of the investigation? E.g., redundant graphs are not included, graphs used for diagnostics and trouble-shooting are found only in the appendices. Is each individual visualization effective and efficient at communicating its intended information? |
| **Quality of investigation** | **Scope and thoroughness:** Is the investigation some reasonable combination of ambitious in scope and thorough? This recognizes that one will typically place more emphasis on one or the other. Thoroughness refers to a combination of exploring phase spaces thoroughly and giving careful attention to interesting features. |
|  | **Validation of code:** Was an appropriate effort made to ensure that the code behaves as intended? Were the key steps of these validations communicated effectively in the project report appendix? |
| **Reflection** | **Reflection questions:** Do the answers to the reflection questions suggest a good faith effort to engage with them? Are the reflection questions answered to a sufficient level of detail as to provide the context needed to understand how efforful the various aspects of the completed project were? |

The sub-category of Effective coding practices (making code efficient, readable concise and/or final) includes, but is not limited to, the following:
* Making variable names descriptive,
* Providing clear communication of the purpose of each chunk of code,
* Ensuring that any output provided by the code has its purpose described,
* Ensuring that diagnostic output from the code has been removed from the body of the project,
* Ensuring that diagnostic output included in the appendices is only when needed for a specific validation task?,
* Minimizing the need for repeating code,
* Using efficient coding practices (e.g., using a dynamic print statement in the Homework 03 motion diagram instead of a long if/elif conditional with individualized print statements for every possible case),
* Providing a level of commenting such that somebody else in this course could easily read your code and undestand what was going on.


## *Meeting expectations vs earning distinction points by exceeding expectations*

Earning distinction points:
To earn distinction points for an aspect of your report, you need to have clearly gone above and beyond expectations in terms of the creativity, complexity, effectiveness and/or thoroughness of your work. The ways in which you expand and extend your simulation should make sense in the context of your research question and not be included only to increase complexity. The expectation for a project to earn distinction points is that it should have a key element that has exceeded expectations to the point that the project warrants being used as an exemplar in a future year.

The following table provides some examples of project elements expected to earn Accepted for Publication (meeting expectations) and how those elements could be further extended to be considered for distinction points (exceeding expectations).

| Examples of meeting expectations | Examples of exceeding expectations |
| :--- | :--- |
| 2D collisions as the only additional physics | 2D or 3D collisions with some additional physics. The use of 2D/3D should enhance or be motivated by the research question, not be included only to increase complexity. |
| Incorporating a common textbook style physics effect, such as: making the collisions not perfectly elastic, adding an incline, incorporating friction, adding acceleration panels, connecting the balls with a spring, etc. | Bringing multiple physics effects together and having some of them use variable parameters such a research question can be built around exploring the phase space created by varying multiple of these parameters. |
| Incorporating a novel context that motivates the research question and additional physics. | Choosing a novel context and research question such that the addition of significant complexity is required. An example context from last year was a dying star with an expanding radius getting hit by a planet. |
| A multi-panel plot demonstrating different aspects of the simulation function, such as kinematic quantities vs time, histograms, motion diagrams, trajectories in 2D space. | A multi-panel plot making use of creative and novel visualizations that provide clear and deep insight into the behaviour of the simulation. An example last year of a novel visualization was one that showed the effects of object deformation during the collision. |



