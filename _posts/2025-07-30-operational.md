---
layout: post
title: "Core Area 1: Operational Issues"
date: 2025-07-30
categories: blog
image: PunchCardbw.jpg
---
## Preface 

<p style="font-size: 1.5em; text-align: center;">
<em> “Technological change is not additive; it is ecological.”</em>
</p>

<p style="text-align: right;">
<em>–Neil Postman </em>
</p>


**Guide**

* <a href="Core_Area_1_a" target="_blank" style="text-decoration: underline; color: #004080;">Core Area 1a</a>


The field of engineering requires adaptablity and rapid uptake of new tools and working environments.


## Core Area 1a: Understanding Constraints and Benefits of different technologies
<h2 id="Core_Area_1"></h2>




***Core Area 1a - Case i: PowerPoint vs. Sway vs. Mentimeter***

I began teaching in the early 2010s and started leading modules from 2017. My teaching methods have evolved with the tools available. PowerPoint has remained a staple for lecture delivery, supplemented selectively by other tools depending on pedagogical need. My lectures often involve animated diagrams, flowline sequences, and real-time annotation to highlight fluid behaviours or trace conceptual relationships. This visual and spatial interactivity, paired with verbal walkthroughs and guided note-taking, is central to how I scaffold complex engineering content.

Mentimeter’s standout feature is its polling function, which I use selectively to run in-lecture quizzes and diagnostic questions. These can be useful for pacing, gauging understanding, or inviting participation in large groups. But the platform fails when used beyond that narrow scope. It lacks animation, inline editing, and visual pacing control, but more seriously, it is structurally inaccessible. Slides are rendered as images with no alternative text. Screen readers cannot parse question content or student responses. Keyboard navigation is restricted. The platform assumes full visual and motor access, excluding disabled students by default. For this reason, I use Mentimeter only for standalone polls, Alt+Tabbing to it when useful and returning immediately to PowerPoint, which supports layered, accessible, and pedagogically aligned delivery. 

***Core Area 1a - Case ii: : Moodle vs. D2l vs. Canvas***

I have worked extensively with Moodle, D2L (Desire2Learn), and Canvas across different institutions, and each has presented its own strengths and limitations. I first encountered Moodle in its early days, and while its modular design allowed for flexibility, it often required manual structuring and lacked polish in interface design. D2L offered more consistency in navigation and grading tools, particularly for scaffolded assessment structures, but tended to be inflexible when trying to embed external content or apply complex workflows. Canvas, by contrast, felt modern and lightweight, with cleaner integration of multimedia, straightforward assignment creation, and better cross-platform accessibility. However, it could feel restrictive when customisation was needed or when managing large numbers of files and resources.

Returning to Moodle in my current role has meant revisiting a platform that, while widely adopted, still carries some of its earlier inefficiencies. Navigation can feel fragmented, and many features (such as assignment feedback and gradebook tools) require multiple layers of configuration to work as intended. Despite this, I have structured my Moodle pages carefully to reduce cognitive load, using collapsible sections, visual flowcharts, and labelled downloads to guide students through each week’s materials. I also supplement Moodle’s limitations by embedding interactive tools like <a href="https://jupyter.org/" target="_blank" style="text-decoration: underline; color: #004080;">Jupyter Notebooks</a>. While no platform has offered a perfect solution, my experience across systems has allowed me to identify what is worth customising and what requires workarounds. The goal remains the same: to ensure that the learning environment supports clarity, progression, and meaningful engagement with the course content.





***Core Area 1a - Case iii: Numerical and Analytical Solvers***

Engineering is a science of data. Every value we calculate is an estimate, with uncertainty built in. To support students in applying analytical and numerical theory, I use a range of tools: Primarily Excel,  <a href="https://orangedatamining.com/" target="_blank" style="text-decoration: underline; color: #004080;">Orange</a>, and Python—selected according to task complexity and student experience.

For my current students, Excel is the most immediately accessible (in the past it has been  <a href="https://www.mathworks.com/products/matlab.html" target="_blank" style="text-decoration: underline; color: #004080;">MATLAB</a>). I use it to introduce finite difference models, stochastic processes, and parameter-driven simulations using cell-based logic. Its low barrier to entry makes it ideal for early undergraduates who are learning to visualise theory rather than build software. However, Excel’s scalability is limited, and it becomes inefficient for high-dimensional or data-heavy work.

For MSc students that I mentor who are less comfortable with coding, I use  <a href="https://orangedatamining.com/" target="_blank" style="text-decoration: underline; color: #004080;">Orange</a>. This GUI-based machine learning environment allows students to build classification or regression pipelines, adjust model parameters, and visualise outputs without writing code. It helps bridge the gap between abstract concepts and practical workflows. While not customisable enough for research use, it works well as an educational stepping stone.

For graduate students with stronger technical ability, I shift to Python. It offers full control, rich numerical libraries (NumPy, SciPy, Scikit-learn), and flexibility for modelling and data analysis. I use it to teach finite difference methods, environmental simulations, and machine learning pipelines for µCT and time-series datasets. To support learners new to coding, I provide scaffolded notebooks with commented code, embedded visuals, and real-world data. This structure allows students to engage with the tools at a depth that suits their confidence and background.





***Evidence***
-Moodle shell screenshot

-Assignment Ogata Banks

-Solution to Ogata Banks

-Old PP vs. New?

***Core Area 1a Reflections***

Before I finished my PhD, I was already teaching as a TA, mainly using blackboards, whiteboards, even acetates. This was before TEL had momentum, and tools were mostly analogue. That didn’t last long. As digital platforms became more accessible, I adapted quickly. PowerPoint started as a static slide deck, but when tablets and smartboards came in, it became something else entirely: layered, animated, and capable of real-time interaction. I embraced those changes, not because they were new, but because they made better teaching possible.
Today, Microsoft Office remains the digital backbone of most universities. It is broadly effective, but far from seamless. While the suite presents as integrated, its components often behave like competing siblings: shortcuts shift between apps, formatting collapses when slides are shared across platforms, and we’ve all gained white hairs from trying to convince Excel that a number is indeed not a date, or tried to write text that wraps around pictures in Word that results in a wild goose chase in hot pursuit of an image on the run. These issues are not just anecdotal; usability studies, including those by Lu et al. (2022), have documented persistent friction points in Office-based teaching environments, particularly around content portability and interface predictability. Even so, the usefulness of a universal platform like PowerPoint for structuring material, enabling visual engagement, and supporting accessibility, still makes it a flawed but central character in my pedagogical repertoire.

Mentimeter is often praised for driving engagement, but the problems are difficult to ignore. Unless a session is built entirely within the platform, accessibility collapses: animations vanish, edits lock, results disappear with a browser refresh. I’ve watched phones freeze mid-poll. These are patterns I now plan around. While studies report increased enjoyment and perceived engagement (Cutri & Mikkonen, 2021; Dervan, 2014), engagement is not the same as learning. As Selwyn (2016) warns, many digital tools prioritise participation metrics over cognitive depth. In my own teaching, I’ve seen students light up briefly during a poll, then fade just as quickly. The burst of activity doesn’t translate into conceptual development. Over time, I’ve shifted away from polling as a centrepiece. Now I use it sparingly, pairing it with problem-based discussion that sustains attention through reasoning over novelty. 

I still use Mentimeter, but only for what it does well: quick polling. I Alt+Tab to it when the moment fits, then return immediately to my main lecture flow. I don’t regard it as a fully formed teaching platform, but more as a disembodied, yet useful feature. This distinction is explored by Kirkwood and Price (2014), who argue that technology should be judged by how well it supports specific educational goals. Tools like this, along with legacy systems like Microsoft Office, reflect a broader trend: much of the educational software in use today is designed around institutional convenience, not pedagogical value (Castañeda & Selwyn, 2018). That misalignment leads to compromises in usability, flexibility, and ultimately in learning. My approach now is shaped by experience: test tools critically, use them selectively, and always design around the thinking I want students to do rather than the features a platform wants me to use.

Platforms like Moodle, D2L, and Canvas are chosen institutionally, not pedagogically.  Often, the selection isn’t based less on what’s innovative than what doesn’t break anything that’s already in place.  Their adoption is shaped by procurement structures and IT policy, not teaching need. Empirical studies have documented persistent usability issues in these systems, including interface complexity and poor user experience (Vlachogianni & Tselios, 2023; Lu et al., 2022). But despite their limitations, it is possible to make them work, if one takes the time. I’ve used these platforms effectively as distribution systems for readings, worked examples, and video lectures. More importantly, they have enabled me to deliver learning tools that were once impractical, such as embedding <a href="https://jupyter.org/" target="_blank" style="text-decoration: underline; color: #004080;">Jupyter Notebooks</a>
 for hands-on simulation and data analysis.

In selecting and deploying educational software, I’ve found the balance between power and learning curve to be critical. A tool that’s too simplistic teaches little; one that’s too complex alienates before it enlightens. This principle underpins my platform choices: Excel for conceptual grounding,  <a href="https://orangedatamining.com/" target="_blank" style="text-decoration: underline; color: #004080;">Orange</a> for model intuition, and Python for scalable depth. The aim is always to create conditions where students can explore, build, and iterate, without being overwhelmed. As Laurillard (2013) argues, effective digital learning environments must scaffold conceptual development while allowing room for authentic practice. I’ve come to see tool choice not as a technical decision, but as a pedagogical one anchored in how students learn, and what they’re ready to take on next.

***Core Area 1a References***

* Castañeda, L. and Selwyn, N., 2018. More than tools? Making sense of the ongoing digitizations of higher education. International Journal of Educational Technology in Higher Education, 15(1), p.22. https://doi.org/10.1186/s41239-018-0109-y

* Cutri, R.M. and Mikkonen, J., 2021. Student perceptions of using Mentimeter as a student response system in higher education. Education and Information Technologies, 26, pp.6557–6573. https://doi.org/10.1007/s10639-021-10589-5

* Dervan, P., 2014. Increasing in-class student engagement using Mentimeter, an interactive presentation software. AISHE-J: The All Ireland Journal of Teaching and Learning in Higher Education, 6(3), pp.1801–1815.

* Kirkwood, A. & Price, L. (2014). Technology-enhanced learning and teaching in higher education: what is ‘enhanced’ and how do we know? A critical literature review. Learning, Media and Technology, 39(1), 6–36.  https://doi.org/10.1080/17439884.2013.770404

* Laurillard, D., 2013. Teaching as a Design Science: Building Pedagogical Patterns for Learning and Technology. New York: Routledge.

* Lu, J., Schmidt, M., Lee, M. and Huang, R., 2022. Usability research in educational technology: A state-of-the-art systematic review. Educational Technology Research and Development, 70(6), pp.1951–1992. https://doi.org/10.1007/s11423-022-10152-6

* Selwyn, N., 2016. Is Technology Good for Education? Cambridge: Polity Press.

* Vlachogianni, P. and Tselios, N., 2023. Perceived usability evaluation of educational technology using the post-study system usability questionnaire (PSSUQ): a systematic review. Sustainability, 15(17), p.12954.


## Core Area 1b: Technical Knowledge and Ability in the use of Learning Technology

**Core Area 1b Case i: Technological Proficiency**

While completing concurrent undergraduate degrees in Chemical Engineering and Comparative English Literature, I spent five years as a staff writer, artist and editor for a university newspaper. That parallel training continues to inform my approach to technical work. I try to prioritise clarity, structure, and communicative precision wherever possible when writing simulation code, designing a notebook, or building instructional materials. Tools are never just functional; they are rhetorical. How they present information matters as much as what they compute.

Over two decades in research, regulation, and teaching, I have developed fluency across a range of technical environments. My work spans Python, Julia,  <a href="https://www.mathworks.com/products/matlab.html" target="_blank" style="text-decoration: underline; color: #004080;">MATLAB</a>, <a href="https://www.maplesoft.com/products/maple/index.aspx" target="_blank" style="text-decoration: underline; color: #004080;">Maple</a>, Visual Basic, FORTRAN, C++, SQL, HTML, and others, deployed across Windows and Linux systems. I use GitHub for version control, Jupyter for interactive analysis, and tools such as TauFactor, PoreSpy, and Palabos for pore-network and Lattice Boltzmann modelling—typically run within sandboxed virtual environments.

My technical scope includes numerical simulation, image and time-series analysis, and machine learning pipelines. I have written simulation code for groundwater transport, trained neural networks for geospatial classification, and developed visualisations to support both teaching and research. I also have a formal background in design and editorial work, which continues to shape how I structure learning materials: Building coherent, visual explanations that support conceptual development across complex topics.

In undergraduate teaching, I design Python- and Excel-based environments that allow students to engage with environmental datasets and models. These include pre-built notebooks for time-series exploration, Mann–Kendall trend detection, and parameter sweeps on finite difference models. Tools are scaffolded to student level, balancing technical depth with accessibility.

At MSc level, I co-develop classification and modelling pipelines with students. One current project involves permeability estimation from µCT image data using random forests, supported through shared GitHub repositories and Python-based simulation workflows. I have also supervised MSc work on environmental classifiers and advised students adapting their research code for industry.

Beyond the classroom, I serve as Principal Investigator and technical lead for national data challenges hosted by The Alan Turing Institute. I have facilitated or led three Data Study Group projects, including segmentation of thin-section geological images, OCR of seismic scans, and time-series detection of oil spills in SAR data. These roles require fast, effective pipeline deployment, interdisciplinary team support, and high-level technical judgement under short timelines.

***Core Area 1b Evidence***

<a href="/assets/img/DSG_PI_Criteria.pdf" target="_blank" style="text-decoration: underline; color: #004080;">-Requirements (including techonogical ability) for Primary Investigator Position at The Alan Turing Institute as Affirmation of Skillset</a>

<a href="/assets/img/representativecode.jpg" target="_blank" style="text-decoration: underline; color: #004080;">-Representative Code Snippet for Rock Flow Properties Analysis (MSc mentorship project)</a>


-Code Snippet for long term analysis with seasonal variation
-Code Snippet for nc file slicing
-MSc project Descriptions


***Core Area 1b Reflections***

My relationship with technology began long before teaching. I was ten when I started coding on an Apple IIe. By thirteen, I was learning BASIC at summer camp. In high school, the focus shifted to HTML and object-oriented programming. When I began teaching in Canada, years before my PhD, I was already using code to solve problems, explain concepts, and build structures that made sense to others. That habit has remained. What’s changed is the precision of the tools.

Like a carpenter with access to power tools, I’ve expanded what I can build. But the skill is in the joins. Technology allows me to plan more clearly, structure more tightly, and shape how learning unfolds. Whether I’m constructing a simulation workflow or a scaffolded spreadsheet, the aim is the same: build environments that hold together. As Laurillard (2012) argues, technology in teaching must be a matter of deliberate design, tools used to shape conceptual progress.

This principle guides my choices. Some students co-develop machine learning models with me. Others use spreadsheet environments to explore systems and test assumptions. Biggs and Tang (2011) emphasise that method must align with outcome. Beetham and Sharpe (2007) remind us that digital platforms gain value only through pedagogical purpose.

Structure matters. Kirschner, Sweller, and Clark (2006) show that students benefit most from guided, well-sequenced instruction. A polished tool doesn’t teach on its own. A scaffolded, logical progression does. I’ve seen students learn more from a notebook that builds one idea at a time than from a fast-paced lecture filled with features.

These are not purely technical decisions; they are pedagogical. The aim is to help students build something meaningful, whether it’s a model or an idea that holds under pressure.

***Core Area 1b References***

* Beetham, H. and Sharpe, R., 2007. Rethinking pedagogy for a digital age: Designing and delivering e-learning. London: Routledge.

* Biggs, J., Tang, C. and Kennedy, G., 2022. Teaching for quality learning at university. 5th ed. Maidenhead: McGraw-Hill Education (UK).

* Kirschner, P.A., Sweller, J. and Clark, R.E., 2006. Why minimal guidance during instruction does not work: An analysis of the failure of constructivist, discovery, problem-based, experiential, and inquiry-based teaching. Educational Psychologist, 41(2), pp.75–86. https://doi.org/10.1207/s15326985ep4102_1

* Laurillard, D., 2013. Teaching as a design science: Building pedagogical patterns for learning and technology. Abingdon: Routledge.


## Core Area 1c Supporting the deployment of learning technologies

***Core Area 1c Case i: Jupyter Notebooks for Engineering Education: Supporting Conceptual Mastery***

As part of my module redevelopment for Contaminant Hydrogeology and Groundwater Remediation and Hydrosystems Engineering and Management, I have integrated interactive Jupyter notebooks developed by TU Dresden through the iNUX Europe initiative and <a href="https://gw-project.org/interactive-education/">The Groundwater Project – Interactive Education</a>. These notebooks shift traditionally lecture-based content into exploratory, browser-accessible environments where students can interact directly with groundwater models, parameterise scenarios, and visualise results.

To enable seamless deployment, I initially configured Moodle shell links through Binder and JupyterHub pipelines, removing the need for local installation or advanced setup. This scaffolding supports digital equity and accessibility across diverse student hardware and skill levels, while aiming to increase engagement and align learning activities with Bloom’s higher-order skills: application, analysis, and evaluation.

However, Binder introduces its own usability issues for students. Launch times can be slow, and the use of temporary codespaces exposes notebook code by default—often disorienting for students unfamiliar with Jupyter or uninterested in programming structure. Students would have to access the menu, collapse all code windows and run all script, which adds uneccsary steps to the intention of the tehcnology: To teach groundwater science. The experience lacks the polish needed for performance-focused or non-technical audiences. 

As an altertive I opted to deploy Streamlit versions of the same iNUX models. These apps offer faster load times, automatic execution, and a cleaner interface—closer to a scientific calculator than a notebook shell. For many students, this format reduces friction and keeps focus on conceptual reasoning rather than tool navigation.

The notebooks replace multi-step pen-and-paper tasks with responsive tools that allow full control of key variables. By doing so, they preserve cognitive rigour while reducing procedural friction, supporting a deeper conceptual grasp of transient flow, sorption, and transport processes. Although student-facing use begins in 2025–2026, internal testing has confirmed full compatibility, and I have produced draft screencasts and tutorial guides in preparation for launch.

These materials form part of a broader effort to reorient groundwater teaching around open-source tools and reproducible science, with colleagues across the faculty already expressing interest in adaptation for their modules.

***Core Area 1c Case i Evidence***

MAKE EXAMPLES MATCH!!!!

<a href="/assets/img/MoodleJupyterIntegration.png" target="_blank" style="text-decoration: underline; color: #004080;">-Screenshot: Moodle-Integrated Jupyter Worksheet </a>

<a href="https://mybinder.org/v2/gh/EMar1066/HydroG-Jupyter-Notebooks/HEAD?filepath=04_Basic_hydrogeology/GWF_1D_unconf_analytic_BC3.ipynb"
   target="_blank" 
   rel="noopener" 
   style="text-decoration: underline; color: #004080;">
– Launch Interactive Notebook via Binder: Analytical solution for 1D unconfined flow with two defined head boundaries
</a> (Useful for demonstrating or modifying coded solutions to presented theory, code can be run by 'view'->'collapse all cells' then 'run'->'run all cells')


<a href="https://gwf-1d-unconf-analytic.streamlit.app/" target="_blank" style="text-decoration: underline; color: #004080;">– Launch Interactive Notebook via Streamlit: Analytical solution for 1D unconfined flow with two defined head boundaries </a> (Useful for drawing focus to theory without distraction. No run controls required.)


***Core Area 1c Case ii: SYMPLE and INUX Europe: Leading Collaborative EdTech Deployment***

As a curriculum developer and trainer for <a href="https://hydrosymple.com/en/" target="_blank" rel="noopener" style="text-decoration: underline; color: #004080;">the School of Hydrogeological Modeling & Project-Related Strategies (SYMPLE)</a>, I collaborate with colleagues from industry,TU Dresden and Sapienza University of Rome to produce applied hydrogeology material for environmental and water resource professionals.  Typically, learners have foundational theory in place but wish to extend their numerical modleing and uncertainty estimation abilities. They are glolbablly diverse, with majority representaiton from the global south and under-resourced regions (<a href="https://hydrosymple.com/en/trainers/" target="_blank" rel="noopener" style="text-decoration: underline; color: #004080;">Evidence)</a>.

This work foregrounds scalable, decision-focused education in groundwater systems and expands my own practice in adapting teaching to diverse technical and environmental settings. Part of my work with SYMPLE included the development of an online learning platform, the <a href="https://tu-dresden.de/bu/umwelt/hydro/inux/projekt/ueberblick?set_language=en">iNUX project (Interactive understanding of groundwater hydrogeology and groundwater management)</a>, which is an Erasmus+ funded initiative (2022–2025), led by a collaboration between institutions including the Technical University of Dresden, University of Gothenburg and Universidad Politécnica de Cataluña.

The goal of the project is to produce open‑source teaching materials such as interactive videos, <a href="https://jupyter.org/" target="_blank" style="text-decoration: underline; color: #004080;">Jupyter Notebooks</a> and self‑assessment tasks designed to support educators and students in teaching groundwater science at a European and global level. The materials are <a href="https://github.com/gw-inux"> freely available via GitHub</a> and include instructions for contributing and adapting content to local contexts. My role in the development of this open-access Hydrogeological question bank which required data-wranging, classification by Bloom's Taxonomy of Cognitive Objectives (1956), subject matter and difficulty,testing and deployment of subject matter.  


***Core Area 1c Case ii Evidence***

<a href="https://hydrosymple.com/en/" target="_blank" rel="noopener" style="text-decoration: underline; color: #004080;">– School of Hydrogeological Modeling & Project-Related Strategies (SYMPLE)</a>

<a href="https://hydrosymple.com/en/about-us/" target="_blank" rel="noopener" style="text-decoration: underline; color: #004080;"> – Scientific Committee (Symple)</a>

<a href="https://hydrosymple.com/en/trainers/" target="_blank" rel="noopener" style="text-decoration: underline; color: #004080;">– Instructor (Symple)</a>

-ADD FRANCESCA EMAIL DEMONSTRATING COLLABORATION


***Core Area 1c Reflections***

Integrating <a href="https://jupyter.org/" target="_blank" style="text-decoration: underline; color: #004080;">Jupyter Notebooks</a> into my groundwater modules changed how students interacted with the subject matter. Real-time parameter controls and visual outputs gave them a clearer understanding of fluid behaviour than static examples or manual calculations typically allow. The notebooks helped students test assumptions, see relationships, and build intuition for how groundwater systems respond under varying conditions.

I configured deployment through Binder and JupyterHub to avoid installation issues and simplify access via Moodle. This allowed students to focus on the models themselves rather than setup or troubleshooting. The interface was designed to be accessible and logically structured, helping students engage with core ideas without added complexity.

Class feedback from the initial integration Module (ENVI-1195 Contaminant Hydrogeology and Groundwater Remediation) was positive. Students found the models approachable, especially the ability to experiment and revisit key concepts between lectures. Based on this reception, the notebooks now have a regular presence across the module, supporting independent study and problem-solving outside of scheduled contact hours. This iterative use reinforces understanding and aligns with Bruner’s (1960) principle of revisiting foundational ideas at increasing levels of complexity. It also reflects Sweller et al.’s (2011) work on reducing cognitive load to support deeper conceptual development.

SYMPLE and iNUX are related projects with shared leadership and a shared philosophy: open-source tools for open-access education. Both are led by TU Dresden, and both focus on groundwater modelling and decision-making in diverse, global contexts. My role bridged the pedagogical and technical: I handled the structuring, cleaning, and classification of a large dataset of hydrogeology questions to ready them for deployment across institutions.

This was not just a content exercise. It required thinking about modularity, clarity, and reuse—how to make learning artefacts that would hold up in different languages, curricular settings, and delivery modes (Conole, 2013). Classifying questions by Bloom’s taxonomy gave the bank internal structure; hosting through GitHub gave it longevity and adaptability (Beetham et al., 2012).

These resources now serve multiple universities and training programmes. More than that, they reflect a scalable model for collaborative content development—one that doesn’t just deliver learning, but distributes the means to teach. Working on these projects reinforced for me that educational technology, when built for openness and reuse, can expand access without lowering rigour (Hilton, 2016; Beetham et al., 2012).



***Core Area 1c References***

* Beetham, H., Falconer, I., McGill, L. and Littlejohn, A., 2012. Open practices: Briefing paper.
 
* Bloom, B., 1956. A taxonomy of cognitive objectives. New York: McKay.
  
* Bruner, J.S., 1960. The Process of Education, Harvard, Univ. Press, Cambridge, Mass.

* Conole, G., 2012. Designing for learning in an open world (Vol. 4). Springer Science & Business Media.

* Hilton III, J., 2016. Open educational resources and college textbook choices: A review of research on efficacy and perceptions. Educational technology research and development, 64(4), pp.573-590.

* Sweller, J., Ayres, P. and Kalyuga, S., 2011. Emerging themes in cognitive load theory: the transient information and the collective working memory effects. In Cognitive load theory (pp. 219-233). New York, NY: Springer New York.
