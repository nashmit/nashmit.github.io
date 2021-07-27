---
layout: post
title: Building an argument...
subtitle: Dear X...
<!--- cover-img: /assets/img/path.jpg --->
thumbnail-img: /assets/img/EKF1.png
<!--- cover-img: /assets/img/EKF1.png --->
<!--- share-img: /assets/img/path.jpg --->
tags: [personal]
published: true
---


![Painting](/assets/img/EKF1.png)


Dear X,

Thank you very much for sending me the feedback!

I&#39;ve been waiting for it impatiently for all this time but it worth it given the surprising level of completeness and attention to details, my reviewer has put into. I can&#39;t say that I had any of my past work, as a student, on this level under the spot! Thank you! 

After multiple careful readings I concluded that most of the appreciations are well connected into the reality of my work. Nevertheless, I also spot multiple conclusions to which I disagree. Since this evaluation follows the structure of a paper review, I would try to respond accordingly given that I believe that it&#39;s in my interest to clarify them as they had quite some impact with respect to my final grade.

As I was not sure whether you were the one who has evaluate my project, the last email can easily be interpreted as a general statement w.r.t. evaluation and given the fact that the evaluation pdf is not signed and some statements do not correspond to what I know from you, I thought it was safe to believe that a 3rd person has evaluated my work. As a consequence, the response is addressed to the 3rd person. If this is not true, please accept my apologies.

**Summary:**

The evaluation structure doesn&#39;t take care of the project particularities by considering missing elements that are not relevant for my project ( e.g. quantitative analysis ) as a minus and at the same time given little importance to parts of the project that represents the backbone of my work ( e.g. 2 layer architecture ). At the same time, an important part of the project is misinterpreted and by doing so, is not considered by the reviewer in the grading process ( e.g. the EKF modeling process ).

Last but not least, the evaluation process contains elements that are not in accordance with what I&#39;ve been told.

_I will start with some general comments and continue with point by point paragraph comments where I think some clarification are in order and I will point the reader back to the general comments whenever it is the case. In the end, I will add a short conclusion._

**General comments:**

**A)** The performed review closely resembles in form, tone and style that of a rebuttal for a journal submission, which, in the view of the author of the project, exceeds in terms of exigency, content, time frame and qualitative analysis depth expectations that of the intended student technical report. Thus, the review style used here may underline the expected limitations that a report of this magnitude typically has, given that, per example, the turnaround time for a journal submission is, on average, at least a few months up to a few years, also noting that a second submission is usually the norm, hence the author is obliged to iterate on these crucial differences.

**B)** The reviewer seems to frame the assignment into a classical scientific project ( where one applies direct the scientific method, e.g. : quantitative study, error measurements, repeating the experiments multiple times, comparison with other results etc. ) which unfortunately doesn&#39;t suit my project given the particular approach and the problems at hand.

To be more precise, the scientific method implies that one doesn&#39;t have a complete knowledge about the dynamical system, but it proposes a plausible hypothesis and it tries to underline how well his method is able to predict the dynamical system ( sometimes, also to control it ).

On the other hand, my project starts from modeling the dynamical system ( in a simulated environment, also modeled ) and by doing so, I know everything about it, I control the degrees of freedom the system has, the source of errors and the size of errors of the dynamical system as well as for the methods applied . So, the quantitative study/system identification is of no use given that I already know the parameters which the methods are supposed to return since I&#39;m using them as input ( for the states and the errors ) and I can make them as good as I want them to be. Given this situation, a second aspect deserves to be underline. What one can consider the &quot;correct&quot; values for the modeled system and what are the size of the errors to be used to get indeed a realistic physical model? This problem has a big impact on any results one might have, since any solution proposed is quite sensitive to any variation of the parameters. Defining those parameters and making sure that are suitable for the proposed methods is, in its own, a project subject, since it involves further research/readings/domain review regarding different levels of tolerance of different sensors and dynamical systems models which is way beyond the scope of this project. The way I understand it, the current grading system with respect to this, is not in my favor by not being adopted/suitable to the kind of project I&#39;ve done. This is particularly important since it was the reason behind multiple criticism points in the feedback. There are other ramifications of this which I will point out whenever it is the case later on.

It is important to mention that this approach should not be considered a novelty since it is the approach of multiple scientific domains where partial analysis is done in a simulation environment based on a defined model. Scientific domains where this approach can be seen are structural biochemistry / molecular dynamics/particle physics etc. Take for example results in molecular biophysics. Whenever findings based on _in silico_ are presented in an article they are always doubled by an experiment that can confirm the findings since no model is perfect. You still can publish _in silico_ results as long it is about improving methods but no respectable publication will accept practical results based only on _in silico_ analysis without multiple _in vitro_ confirmations. It is safe to say that most of the time this approach is used as a preliminary investigation, by performing qualitative analysis, in a research project to minimize future _in vitro_ tests and the quantitative study is done afterward using real data. Another use case is to try to reproduce/test corner cases that are hard to reproduce otherwise in real life for further analysis in a contained environment.

It is worth mentioning also, that I had some discussions regarding doing analyses of the obtained results with my project supervisor, but there are different ways of doing that and, in my opinion, the objective was reached, given the obvious limitations of the approach.

**C)** On another note, I must say I&#39;m surprised with the level of details of the requirements the reviewer has used for evaluation, since I wasn&#39;t aware of them in a formal manner, given that no document or other way of communication have clearly stated the requirements for us too. These would have been gratefully helpful given that the level of expertise on doing a scientific analysis and writing a paper based on the results it&#39;s something that, as a student, one must learn and it is in my opinion that shouldn&#39;t be taken for granted, even more when the reviewer has a particular list of requirements that should be followed. Furthermore, some of the feedback from the reviewer is not in accordance to what I have been told. E.g.: &quot;Is the code/implementation subject to the evaluation process?&quot; This question was asked as part of the meetings I had during the time I was working on the project and the response was &quot;no&quot;. Now I see that, for this specific subject, a maximum of 22 points have been granted which represents a significant number with respect to the total number of points. It is true, I was able to collect 19 points but, I would have preferred to be aware of this. Some of the appreciations I&#39;ve been given on this matter were accorded by means of luck, since I&#39;ve worked more on the topic for personal considerations and not because I was aware of its importance for the evaluation. I would like to mention that this is not the only example. I will point out others later on.

**D)** Another concerning aspect I was able to spot has to do with the failing of the reviewer to give credit for some important part of the work by misclassifying it. The reviewer seems to believe that in the report, Kalman Filter and the Extended Kalman Filter are introduced, when in fact, what was done is : _(i)_ to model the task at hand by walking through all the steps, from one dimensional problem through multidimensional one, _(ii) to_ identify the parameters specific to the model and sensors as part of the KF, _(iii) to_ deal with the fact that some sensors are not given direct measurements of the state system (e.g. LiDAR ) and then _(iv) to_ show how to deal with limitation of KF in a nonlinear environment, for this specific problem by linearizing ( by introducing the EKF ). All the derivations were provided in the context of this particular problem and do not represent a general EKF formulation which could have been part of the appendix, but a direct application of the method with respect to the problem. An important aspect of the project consists of the modeling part which has required some time - not graded other than for formal reasons. The reviewer seems to be under the impression that this part of the project represents theory ( results ) which should have been cited, when in fact represents part of my work. Is this part some original work? More certainly not since the problem is quite classical by now, nevertheless the approach for this problem was based on learning the fundamentals of KF and EKF and car modeling ( which were cited ) and then trying to apply them in the context of this problem. This was one of the main promises of the project.

Multiple important aspects were taken into consideration in writing the EKF modeling section. Fist, the method is not part of the lecture ( a simplified version of KF is ) in consequence, I wanted to make sure that the reviewer can follow my solution. The approach is quite involved considering the multidimensional case, the derivation, the indirect sensor information and the continuous state space of the system and it&#39;s not that obvious if the reader is not acquainted with the field. The objective was to make sure, that the reviewer has all necessarily steps to easily follow the work and to reproduce it if needed. In the process of explaining the steps I was underling the important problems one must take care of. ( e.g.: how to deal with the situation when the sensor is not given the same type of measurements as the state space for the car, etc. ) There is also a personal reason for doing that, since I&#39;ve been quite annoyed in the past with the quality of explanation of most of the articles published these days. ( lack of information, missing steps which can create ambiguities, trying to hide possible future leads considered for future articles etc. which I tried my best to avoid ) Another reason has to do with the fact that the entire process takes place into a simulated environment which might raise concerns with respect to the quality of the results, easy skewable. I wanted to make sure that no suspicions were raised and I&#39;m happy to see that they weren&#39;t.

It is worth mentioning, that this subject was part of my e-mail exchange with my project supervisor who informed me the following: _&quot;For your own algorithms a bit more detail would be helpful (depends on the clarity and complexity of the algorithm if you introduce formulas).&quot;_ This particular problem falls also, under the general comment **C** , with respect to the reviewer requirements and what I&#39;ve been told.

**Point by point comments:**

**Paragraph 1:**

&quot;– _ **Criterion** _ _Achievements of tasks - Did the students motivate a research question which their method can answer? (3 Points) Did the students complete the implementation of their method? (10 Points) Did the students come up with experiments demonstrating the advantages and disadvantages/effect of their approach? (5 Points) Can they in the end answer their research question or make suggestions how to move forward? (2 Points)_

– _ **Evaluation** __- The student&#39;s research question was to compare four different approaches for robot localization in a simulated environment. Yet, the motivation and formulation of that question is not very explicit in the report(3 Points). All four localization approaches and the simulation environment are implemented (10 Points). The student performed qualitative experiments to show how well trajectories of the simulated car can be reconstructed. He shows how effective all four methods are and explains advantages and disadvantages by doing qualitative experiments._ [1]<span style="background-color: green"> _However, a quantitative study is missing, e.g. error measurements, repeating the experiments multiple times, different levels of difficulty (4 Points)._ </span> [2]<span style="background-color: turquoise"> _There is a conclusion of the experiments but the research question is not answered there. What approach to choose? I assume the EKF worked best... but there are no numbers or statement by the author underlining this (1 Point)&quot;_ </span>

**Comment 1:**

<span style="background-color: green">1)</span> The criticism for this paragraph goes mainly under the **general comment B** regarding the qualitative study.

<span style="background-color: turquoise">2)</span> Besides that, the reviewer considered that the research question was not answered. That is true, if the research question is the one identified by the reviewer, thought, this is not the case. The scope of the project was to underline the weaknesses of each approaches with respect to different corner cases and to show how the other methods are dealing or can fix them ( that&#39;s because other analysis was prohibitive as I was showing within the **general comment B** ). This has been highlighted step by step in the &quot;Experiments&quot; section where the analysis was done starting from the most simple model ( wheel sensor only ) where the method&#39;s limitations were presented and the section continued with the other methods, at each step emphasize what the new methods add with respect to the previous one and how it influences the results. To give an answer to &quot;What approach to choose?&quot; question or to identify which method is the best, one must firstly specify some goal otherwise the response will have no meaning. No method is the best, in general, but must be considered in a specific context which was not the scope of my report.

**Paragraph 2:**

&quot;– _ **Criterion** _ _Focus on Essential Tasks - Did the students answer their research question by putting the focus on essential/dominating/important/relevant aspects of their method or experiments? 5(Points)_

– _ **Evaluation** __- The student implemented all localization approaches and the simulation environment which allows him to perform a series of meaningful experiments._ [1] <span style="background-color: green"> _The experiments, however, lack a quantitative analysis. Hence, the plausibility of his findings is limited as it lacks any underlying statistical evidence. This essential aspect was overseen. (3 Points)&quot;_ </span>

**Comment 2:**

<span style="background-color: green">1)</span> The main idea of the comment falls under the **general comment B** with respect to quantitative analysis. Moreover, the scope of the project was never to emphasis the quality of the proposed solutions ( e.g. quality of localization using ICP, etc. ) given that there are already articles for each of the methods which are doing exactly that and, considering that the project doesn&#39;t propose any novelty in that sense, nevertheless was, as I previously said, to put into evidence the weaknesses of each of the solution and see how the other methods deal with them ( in a simulated environment )

**Paragraph 3:**

&quot;– _ **Criterion** _ _Innovation and Previous Work - Has the research question be answered before? Did the students consider previous work to build up on this? Is their question trivial to answer? (4 Points)_

– _ **Evaluation** __- As I am not to familiar with the robotics community, I do not know if these four methods have been evaluated together. My guess for this simulation environment is: Probably not._ [1]<span style="background-color: green"> _The student uses previous methods for localization from literature, but does not explicitly compare his work to what has been done._ _(3 Points)&quot; </span>

**Comment 3:**

<span style="background-color: green">1)</span> By design, no comparison had been done with previous methods implemented for localization, since trying to compare my implementation with other work would have been a complicated task. Trying to compare 2 different implementations of the same algorithm implies that the simulation environment parameters would correspond more or less with the same parameters presented in other publication which is not, by no means, an easy task on its own. Any comparison done outside these assumption would have no meaning or would have been hard to interpret. This problem is a direct ramification of the **general comment B** given that I control the quality of the results of the model and the algorithms, finding the right parameters corresponding to other experiments it&#39;s beyond the scope of this project. Another approach is to implement other localization algorithms into the simulated environment and by doing so a more correct comparison would have been possible. This problem was taken into consideration from the moment I&#39;ve proposed this project and that&#39;s why currently, we have 4 localization method as part of the project.

**Paragraph 4:**

&quot;– _ **Criterion** _ _Readability, Structure and Design - Is the code readable? Is it easy to browse through the implementation and to find relevant code? (3Points) Does the project have a clean structure and design? (2 Points)_

– _ **Evaluation** __- Naming of variables, classes, functions is readable and sequences of code have short comments. It is easy to understand what is happening._ [1] <span style="background-color: green"> _Some time it is not clear where a certain method is implemented, for example, ICP is not implemented in the ICP.gd file. So, it took some time to browse the code (2 Points)._ </span> Nonetheless, the folder structure is sensible as well as the separation in several file modules and classes. The modifier logic is also well-designed (2 Points).&quot;_

**Comment 4:**

<span style="background-color: green">1)</span> The criticism of this paragraph goes under the **general comment C**. The conclusion is understandable but from different reasons. The code base of the project is written using a modified version of Python and makes use of the architecture/design of a complex game engine. For a person who is not acquainted with it, might be difficult to browse the project given the general flow of the engine and the fact that this project ( engine ) is an all-inclusive tool ( containing rendering tool/logic editor as frontend/specific even system, etc. ). As I was mentioning in the **general comment C** , no particular attention was given to the code base knowing it shouldn&#39;t have matter for the evaluation. With respect to ICP.gd file, I can point out that there is also another file EKF.gd which is in the same situation. Their use is to activate / deactivate those methods by pressing some buttons ( toggle system ) . This problem is due to unfamiliarity of the reviewer with this framework and complexity of the code base structure which is understandable. The implementation of the ICP algorithm can be found in &quot;CarICP Estimation.dg&quot; file.

It is worth mentioning that this project involves doing multiple code experiments ( and otherwise ) in the process, given the fact the way to achieve the end goal is not a direct one. Multiple number of required iterations underlines that a clear software engineering solution is not feasible in the context of a research stage of a product but is more common for software engineering projects where the scientific problem has been solved.

**Paragraph 5:**

&quot;– _ **Criterion** _ _Documentation - Did the students provide sufficient documentation on top of their code to navigate and rerun their implementation, to find all relevant components and so on? (5 Points)_

[1] <span style="background-color: green"> –_ _ **Evaluation** __- Code documentation mostly through video and within the report. It would have been nice to have a text file included in the code which briefly explains the coarse structure and where to find all important components. (4 Points)&quot;__</span>

**Comment 5:**

<span style="background-color: green">1)</span> The criticism goes under the **general comment C** , I wasn&#39;t aware that this will be part of the evaluation.

Nevertheless, I remember letting my project supervisor to know that I&#39;ll document the project in a way that the process of evaluation would be less painless. After a thorough thinking about how to do it I came to the conclusion that this is not an easy task if one wants to document the code using a text file due to the complexity of the project. Other generative approaches were taken into consideration like doxigen but none of these were possible given the fact that the language is designed project specific and the event system is tightly connected with all the main components of the framework which would have made any attempt to describe the flow in a text file a tedious and hard to follow and in consequence of less use for the reviewer. To get the highlight view of the project for the main components one can easily look over the tree structure of the 2 main scenes mentioned in the report: &quot;simulation.tscn&quot; and &quot;Viewer.tscn&quot;. For an easier evaluation it would have been useful for the reviewer to be familiar with this framework ( which is not to be expected) or a short introduction from myself in using it if the reviewer would have requested one, given the fact that in my submission e-mail I&#39;ve particularly offered my help in case of need: &quot;For any other problems/inconveniences please contact me.&quot;

Besides the documentation method mentioned by the reviewer I also tried to comment the code as much as possible and to make it as self-explanatory as possible. I also want to mention that all this work was done for consideration reasons for my reviewer and not because I knew it was required. Most of the work I&#39;ve done in this direction was considered more like a &quot;nice to have&quot;, given the context, the low priority and the time shortage.

**Paragraph 6:**

&quot;– _ **Criterion** _ _Special Efforts - Bonus points are rewarded depending on the difficulty, scope, quality and value of the implementation (2 Bonus Points)_

[1] <span style="background-color: green"> _ **Evaluation** __- He provides a very handy user interface to its simulation environment and the effort put into the implementation is clearly visible(1 Point).&quot;_ </span>

**Comment 6:**

<span style="background-color: green">1)</span> The criticism goes under the **general comment D**. An important aspect omitted here is the 2 layer architecture of my project which I can&#39;t see it mention in the report and therefor taken in consideration. First layer being the simulation and the second layer being the localization algorithms. This was problematic due to the fact that there is no straight approach in knowing whether the chose localization algorithm ( nondeterministic and online in nature ) contains design errors or the bad results are due to the error level applied to the model/sensors/localization algorithm. This makes the process of development and debugging extremely tedious and long. This was particular hard in the process of calibration of covariance matrices which is a process that require experimentation in the context of unknowing what good parameters for sensor should be considered in the first place and what good reasonable source or errors should be considered as well. This was underlined under &quot;Experiments&quot; section, subsection &quot;D. EKF&quot;.

Given this situation, my first approach was to limit the non-deterministic implication in development/debugging process given by the stochastic nature of the problem by making possible an offline analysis. For that, a second component was build, which has as main scope recording the use case test scenario and the possibility to analyze them, frame by frame. This is particular useful since the same scenarios can now be analyzed for different algorithms and see how they respond in different corner cases. This is emphasis in the report multiple times, but the clearest place can be found &quot;E. Online Localization testing&quot;.

For the covariance matrices calibration a more involved method was required. Since I couldn&#39;t know whether the parameters defining the sensors were good enough to calibrate the covariance matrices I end up with the idea of visualize the covariance matrices that defines the states of the car at each moment in time to confirm whether the algorithms converge/ for that specific set of parameters or not. This was not a straightforward process given the conditioning number of the matrices was high as a result of the unbalanced input set of parameters. ( this has made the Eigen vector/Eigen value decomposition, required for computing the drawn ellipsoid, of the covariance matrix, ill-posed w.r.t. small variation in input ) This process was not mention in the report but can be seen by running the project. Also, all this problems were mentioned to my project supervisor in one of the meetings.

**Paragraph 7:**

&quot;– _ **Criterion** _ _Structure and Completeness - Does the report have a clear structure? Does the report present all the essential parts of the students&#39; project?(4 Points)_

– _ **Evaluation** __- The report has a typical paper structure and contains all aspect the student worked on._[1] <span style="background-color: green"> _However, an overall conclusion and answer to the research question is missing._ </span> [2] <span style="background-color: turquoise"> _Also, some aspects are discussed with un-necessary detail leading to some confusion. For example, in the introduction the student provided a long explanation of sensors and why using LiDAR._ </span> [3] <span style="background-color: pink"> _Another example is the in-depth explanation of the standard Kalman-Filter which then is only used as a formal comparison when introducing the EKF__. </span> Yet, the overall structure is ok. (3 Points)&quot;_

**Comment 7:**

<span style="background-color: green">1)</span> This point was also addressed above, in **comment 1 subsection 2**.

<span style="background-color: turquoise">2)</span> The structure of &quot;INTRODUCTION AND RELATED WORK&quot; is : Defining of SLAM problem, putting the problem into context ( importance / adjoined problems / domain who have influenced or from which SLAM was derived / the main 2 approaches ) Then, the main building blocks of SLAM problems are presented ( dynamical system / 2 types of sensors which advantages and disadvantages - this is relevant since now we know what each type of sensor has and the other doesn&#39;t, since in SLAM algorithms we always underline &quot;sensor fusion&quot; process, something that I&#39;ve mention also in the beginning ) Afterwards, a justification of LiDAR sensor is introduced ( as the sensor choice ). Also, the same process is applied for the kinematic model.

This is the bear minimum to create a context in which the &quot;localization problem&quot;, as a sub problem of SLAM ( last paragraph of this section ), which is also the main theme of the technical rapport, requires, since the algorithms proposed for comparison are making use of different sensors.

In the same time, &quot;…why using LiDAR..&quot;, seems to be positively appreciated in **paragraph 8** which creates some confusion with respect to this feedback.

<span style="background-color: pink">3)</span> This goes under the **general comment D**.

**Paragraph 8:**

&quot;– _ **Criterion** _ _Introduction, Motivation and Related Work, Conclusion - Did the students introduce the reader to the field of research the project belongs to, e.g., by giving examples for applications or highlighting difficulties or short-comings of previous approaches? Does the report then state the research question or hypothesis of the student project and why it is worth dealing with it? Did the students refer to recent and related work which motivated, in-spired or influenced their own work? Did the students conclude their findings and interpret them again in the context of related work to find out possible future questions? (6 Points)_

– _ **Evaluation** __- The report contains only a short introduction sentence about SLAM but does not further motivate the project question._[1] _{_ _In particular, the two-wheel robot/car scenario, usage of landmarks, the simulation environment and the relevance of the four methods, being compared in the student&#39;s work, are not motivated by any explanation or reference._ _} However, a very thorough explanation of why using LiDAR as the preferred type of sensor is included. At the end of the introduction the student describes the goal of this project which is good__._[2] _{ Recent literature and finding from the SLAM community are not discussed. Most of the papers proposing the approaches being utilized in the projects are not quoted. Instead survey literature is quoted but not really put into context._ _}_ [3] _{_ _There is no conclusion stating the results of this project and ranking the approaches being analyzed._ _} The part which is supposed to be a conclusion only highlights difficulties to run the respective localization approach. (3 Points)&quot;_

**Comment 8:**

1)&quot; _the two-wheel robot/car scenario&quot;_ -\&gt; is motivated in the beginning, into the section &quot;I. INTRODUCTION AND RELATED WORK&quot; paragraph &quot;..We can model the dynamical system in 2 ways..&quot; (long story short, this model is in reduced coordinates)

&quot; _simulation environment&quot;_ -\&gt; I am interested into sensor fusion/SLAM and since I couldn&#39;t be in the university / in the lab ( because of this pandemic situation ) I had to &quot;create&quot; my own lab. This motivation, however it&#39;s not relevant for this project. Of course, there can be other scientific motivations (I can figure of one or two) but this was my motivation.

&quot;_relevance of the four methods&quot;_ -\&gt; This is a strange question since no one asked me to provide such an answer when I proposed the project. This goes under **general comment C** and **general comment A**. I can give a good reason but since the requirement of the project is to compare the 4 methods it feels backwards to try to justify it, nonetheless, a thorough justification it&#39;s not an easy task, and beyond the scope of the project since this need to be done before starting the project ( also read **comment 8, subsection 2** )

2) Discussions regarding current trending in the domain of SLAM requires an exhaustive research over the topic which cannot be done given the workload for this project and the resources necessary for a thorough process. This is beyond the scope of this report. The survey literature is given for the reader to get a more general perspective over the topic, as a start point.

3) This problem was addressed in **Comment 1**  **subsection**** 2**.

**Paragraph 9:**

&quot;– _ **Criterion** _ _Method - Did the students explain their method thoroughly and correctly such that all novel/important aspects are clarified? Are assumptions, made by the students correct? (6 Points)_

– _ **Evaluation** _ _Yes, the student describes the simulated environment, the car and the localization approaches considered for evaluation._[1] _{_ _However, there are drastic difference in the level of detail he provides for each of them. For example, the kinematics model is explained with some redundancy but no formalism for landmarks and LiDAR computations is used (only at the end for EKF).__}_ [2] _{_ _Similarity matching and ICP are only briefly introduced. In contrast, the KF (even though not used) and EKF are detailed over more than four pages. More details for the former two approaches would have been helpful to understand some of the arguments the student comes up with in the experiments section._ _} (4 Points)&quot;_

**Comment 9:**

1) Formalism for LiDAR is not necessary. The simulation method for LiDAR is presented in subsection &quot;LIDAR model simulation&quot;. The method of computation is based on &quot;ray cast algorithm&quot; which was mentioned. This process involves shooting rays from a position in some specific direction and checking whether intersect some object for a specified distance. This is classic collision checking, which is part of any computational geometry framework, which wasn&#39;t implemented by me but was offered by the game engine. This is one of the main reasons why I&#39;m using a game engine since it offers a collision detection submodule for free. The report presents how the ray cast is used to simulate the LiDAR.

2) I ended up with this decision after an e-mail to my project supervision :_&quot;__regarding classical algorithms ( like similarity and ICP ) which can also be found in the_ _course__, is it sufficient to name the alg. and show how I have used it?&quot;_ for which the response was _&quot;The reader should understand why and how they are used. For ICP it will be sufficient to say that you used it to merge your point estimates, for example.&quot;_ That&#39;s the reason why I didn&#39;t explain them extensively. Regarding KF and EKF, an extensive explanation can be found in **general comment D**.

**Paragraph 10:**

&quot;– _ **Criterion** _ _Experiments - Did the students explain the set of experiments they conducted, their reason/goal and their setup? Are the experiments reason-able? Did the students provide an overview of the results for each experiment? Did the students interpret the results and derive findings? Are these findings__correct? (6 Points)_

– _ **Evaluation** _[1] _{_ _The student does not introduce the reader to the set of experiments he conducted. However, one can assume that he would like to compare the reconstruction of the car&#39;s trajectory with some ground truth simulation. Still, this is never stated__! }_ [2] _{_ _Also, he does not explain what the central parameters of the experiment are, for example, number of repetitions, number of landmarks, difficulty of trajectories and so on. Furthermore, no quality measure is defined. How do we know which approach works better? Smoothness seems to be one of his criteria. Matching the ground truth is another one. He repeats the experiments for all localization approaches. Are the trajectories the same as with the other approaches? In summary, there are a some open questions regarding the setup__. } The results are interpreted visually by looking at reconstructed trajectories for each localization method. Based on these, the student describes the advantages and disadvantages of the respective method. The reasoning is plausible and seems to be correct__._ [3] _{ Yet, for ICP and similarity methods some statements are hard to follow as no notation or theory was provided in the method section }_ _._[4] _{ Finally, the promised comparison between all methods does not really happen in the end. EKF seems to perform best. But what about the other three?_ _(4 Points)&quot; }_

**Comment 10:**

1)The way to test the solutions of the localization algorithms was one of my main concerns from the beginning. For that, a way to generate possible tests was defined. The &quot;ground truth&quot; is defined from the beginning in subsection &quot;1) Car model simulation:&quot; from section &quot;II. METHODS&quot;. Afterwards, the interpretation of the tests is explain into subsection &quot;B. The overall process&quot; where the use case can be analyzed relatively to the &quot;ground truth&quot;. Also, the comparison with the &quot;ground truth&quot; is reminded afterwards.

2)This goes under the **general comment B**. The project puts into evidence the theoretical/known limitation of the algorithms in a simulated environment and doesn&#39;t try to rediscover them since it would be hard to put into evidence whether some new findings are real results or some side effects introduced by the simulation itself. E.g. In section &quot;III. EXPERIMENTS&quot;, subsection &quot;A. Wheel sensor only&quot;, drift error is discussed and 2 figures are used to put into evidence the clams. This is an expected theoretical result based on propagation of truncation error. This process is continued w.r.t. the other methods too. Second part of the question was also addressed into **comment 1, subsection 2**.

3) This problem was addressed into **comment 9, subsection 2**.

4) This problem was addressed into **comment 1, subsection 2**.

**Paragraph 11:**

&quot;– _ **Criterion** _ _Readability, Overall Form and Quality of Figures - Is the report readable? Did the students use correct grammar and spelling? Are style and language appropriate? Does the overall form comply with the guidelines from the lecture (8 pages, double-column IEEE format)? Did the students use figures, tables, equations to improve the reader&#39;s understanding? Are the figures comprehensive? (6 Points)_

– _ **Evaluation** _ _The main insights are easy to understand. Yet, there are several aspects disturbing the reading flow._[1] _{_ _1) References to specific files from the code base and explanation of the GODOT UI and parameter names. This is supposed to be code documentation and does not belong to a report.__} 2)Reappearing formatting issues (section headings becoming part of a sentence, different paragraphing styles, spaces, random characters)._[2] _{_ _3) An overwhelming number of 84 equations where some are redundant and some could have been moved to a dedicated appendix. By going through the derivations the student did not put the focus an the important parts but simply included everything._ _} 4) A noticeable number of grammar and especially spelling mistakes. Most of them could have been avoided by proof-reading. Besides, screenshots are used as figures but without cropping, i.e. it is hard to identify which part of the screen shows something relevant. Figures from the experiments section contain a lot of information which are not explained and should have been cropped, as well. For example, the trajectory is the only thing relevant but LiDAR readings are also included. [3]{_ _Finally, figures 3,5,9 do not add any information._ _} (2 Points)&quot;_

**Comment 11:**

1)Though, this is considered as the _de facto_ structure for a paper, this report doesn&#39;t have to obey any specific publication rules (since none were given) being a technical report. This goes under **general comment A**. I would like to point out that, the project contains an extensive engineering part which wasn&#39;t that easy to decuple from the scientific part. Since my report doesn&#39;t contain any supplementary code documentation those elements that would have make hard to test / reproduce / evaluate had to be added. As an extreme example for the sake of argument would be an impressive paper ( in terms of paper structure :) ) introducing a highly popular library in ML – imblearn – which despite its unconventional format has gathered, since publication (2017), no less than 700 citation. [https://jmlr.org/papers/volume18/16-365/16-365.pdf](https://jmlr.org/papers/volume18/16-365/16-365.pdf) .

2)This problem was addressed into **general comment D**.

3)Figure 5, it&#39;s a linear representation for _&quot;l = r&quot; as_ counterpart for &quot;l differ from r&quot; . Figure 9 introduces the LiDAR reference frame relative to car&#39;s frame. Also, the intention was to reinforce that the LiDAR scans are discrete since in all the other figures are creating a different perspective

**Conclusions:**

It is important to underline that the entire project was done by one person. Though, most of the projects were done by teems of multiple students (3-4 students). Also, I wasn&#39;t able to identify any point in the evaluation that takes into consideration this particular aspect. Nor the fact that extensive auxiliary tools where required and built as the backbone for debugging / development /analysis.

For this project ~2+ full months were considered given the other evaluations I had to prepare (from the same semester and some from one semester beforehand). This was particular complicated in the last 2-3 weeks when the deadline for multiple evaluations was scheduled. This has made almost useless the extra time (2 weeks) offered, given that I had no colleague in my team to offload any part of the work or to check my project in any way by that time. I know that this has little importance for the evaluator but this has minimized quite a lot my window of opportunity for which it was hard to plan in advance for a project that could have ended up badly in many points around the road.

One of the main themes of my feedback has to do with the expectations of the reviewer which, as I was underling in my previously comments, requires much more time for a project like this one than ~65 days, 16h / day which also exceeds the number of the hours corresponding to a 6CP course. Besides, the extra time required to achieve the reviewer&#39;s requirements, my report should have ended easily with more than 20+ pages. Given that the requirement was ~8 pages per team and my report already contains 13 pages for a team of one…

Based on all the previous comments, one can conclude that multiple misunderstandings originates into the bad communications which is nobody&#39;s fault, as I can strongly observe the determination of the reviewer in doing a thorough evaluation.

My project is definitely not perfect and this can easily be seen from reviewer&#39;s comments but in the lite of all this new information, I hope the reviewer will have a better perspective of my work and reconsider the grade.
