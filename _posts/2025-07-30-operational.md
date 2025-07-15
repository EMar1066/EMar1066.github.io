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



The field of engineering requires adaptablity and rapid uptake of new tools and working environments.


## Core Area 1a: Understanding Constraints and Benefits of different technologies
<h2 id="Core_Area_1"></h2>

<h2 id="Core_Area_1_a"></h2>


***Core Area 1a - Case i: PowerPoint vs. Sway vs. Mentimeter***

I began teaching in the early 2010s and started leading modules from 2017. My teaching methods have evolved with the tools available. PowerPoint has remained a staple for lecture delivery, supplemented selectively by other tools depending on pedagogical need. My lectures often involve animated diagrams, flowline sequences, and real-time annotation to highlight fluid behaviours or trace conceptual relationships. This visual and spatial interactivity, paired with verbal walkthroughs and guided note-taking, is central to how I scaffold complex engineering content.

Mentimeter’s standout feature is its polling function, which I use selectively to run in-lecture quizzes and diagnostic questions. These can be useful for pacing, gauging understanding, or inviting participation in large groups. But the platform fails when used beyond that narrow scope. It lacks animation, inline editing, and visual pacing control, but more seriously, it is structurally inaccessible. Slides are rendered as images with no alternative text. Screen readers cannot parse question content or student responses. Keyboard navigation is restricted. The platform assumes full visual and motor access, excluding disabled students by default. For this reason, I use Mentimeter only for standalone polls, Alt+Tabbing to it when useful and returning immediately to PowerPoint, which supports layered, accessible, and pedagogically aligned delivery. 

***Core Area 1a - Case ii: : Moodle vs. D2l vs. Canvas***

I have worked extensively with Moodle, D2L (Desire2Learn), and Canvas across different institutions, and each has presented its own strengths and limitations. I first encountered Moodle in its early days, and while its modular design allowed for flexibility, it often required manual structuring and lacked polish in interface design. D2L offered more consistency in navigation and grading tools, particularly for scaffolded assessment structures, but tended to be inflexible when trying to embed external content or apply complex workflows. Canvas, by contrast, felt modern and lightweight, with cleaner integration of multimedia, straightforward assignment creation, and better cross-platform accessibility. However, it could feel restrictive when customisation was needed or when managing large numbers of files and resources.

Returning to Moodle in my current role has meant revisiting a platform that, while widely adopted, still carries some of its earlier inefficiencies. Navigation can feel fragmented, and many features (such as assignment feedback and gradebook tools) require multiple layers of configuration to work as intended. Despite this, I have structured my Moodle pages carefully to reduce cognitive load, using collapsible sections, visual flowcharts, and labelled downloads to guide students through each week’s materials. I also supplement Moodle’s limitations by embedding interactive tools like Jupyter Notebooks. While no platform has offered a perfect solution, my experience across systems has allowed me to identify what is worth customising and what requires workarounds. The goal remains the same: to ensure that the learning environment supports clarity, progression, and meaningful engagement with the course content.

***Core Area 1a - Case iii: Numerical and Analytical Solvers***

Engineering is a science of data. Every value we calculate is an estimate, with uncertainty built in. To support students in applying analytical and numerical theory, I use a range of tools: Primarily Excel, OrangeML, and Python—selected according to task complexity and student experience.

For my current students, Excel is the most immediately accessible (in the past it has been MATLAB). I use it to introduce finite difference models, stochastic processes, and parameter-driven simulations using cell-based logic. Its low barrier to entry makes it ideal for early undergraduates who are learning to visualise theory rather than build software. However, Excel’s scalability is limited, and it becomes inefficient for high-dimensional or data-heavy work.

For MSc students that I mentor who are less comfortable with coding, I use OrangeML. This GUI-based machine learning environment allows students to build classification or regression pipelines, adjust model parameters, and visualise outputs without writing code. It helps bridge the gap between abstract concepts and practical workflows. While not customisable enough for research use, it works well as an educational stepping stone.

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

Platforms like Moodle, D2L, and Canvas are chosen institutionally, not pedagogically.  Often, the selection isn’t based less on what’s innovative than what doesn’t break anything that’s already in place.  Their adoption is shaped by procurement structures and IT policy, not teaching need. Empirical studies have documented persistent usability issues in these systems, including interface complexity and poor user experience (Vlachogianni & Tselios, 2023; Lu et al., 2022). But despite their limitations, it is possible to make them work, if one takes the time. I’ve used these platforms effectively as distribution systems for readings, worked examples, and video lectures. More importantly, they have enabled me to deliver learning tools that were once impractical, such as embedding Jupyter notebooks for hands-on simulation and data analysis.

In selecting and deploying educational software, I’ve found the balance between power and learning curve to be critical. A tool that’s too simplistic teaches little; one that’s too complex alienates before it enlightens. This principle underpins my platform choices: Excel for conceptual grounding, OrangeML for model intuition, and Python for scalable depth. The aim is always to create conditions where students can explore, build, and iterate, without being overwhelmed. As Laurillard (2013) argues, effective digital learning environments must scaffold conceptual development while allowing room for authentic practice. I’ve come to see tool choice not as a technical decision, but as a pedagogical one anchored in how students learn, and what they’re ready to take on next.

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

Over my two decades of research, regulatory and teaching experience I have beocme fluent across a range of technical environments, including Python, Julia, MATLAB, Maple, Visual Basic, FORTRAN, C++, SQL, HTML and others. I use GitHub for collaborative version control, Jupyter for interactive analysis, and tools such as TauFactor, PoreSpy, and Palabos for numerical and pore-network modelling which may be implemented in either Windows or Linux envronments, but are gerneraly sandboxed within virtual environments. Communications and course dleivery skills include LaTeX, 
 
 My experience includes numerical modeling, image and time-series analysis as well as machine learning segmenters and classification pipelines. I have written simulation code for groundwater transport, trained neural networks for geospatial classification, and developed technical visualisations to support both teaching and research.

My formal design and writing background also informs how I structure educational material. Before returning to engineering, I worked as a professional editor and graphic designer—skills I now use to build clear, visually coherent lectures and guides that maintain narrative focus across complex topics.

In the undergraduate curriculum, I apply these skills to design problem-solving environments using Python and Excel. Students use pre-built notebooks and models to explore environmental time series, implement Mann–Kendall trend detection, run parameter sweeps on finite difference models, and interpret real hydrological datasets. These tools are scaffolded to their level, allowing them to engage with technical content without being blocked by syntax.

At the MSc level, I co-develop machine learning and modelling pipelines with students. One current project involves permeability estimation from µCT image data using random forests. We work via shared GitHub repositories, where I support the codebase and integrate advanced simulation tools. In past work, I’ve supervised students through the full development of environmental classification models and advised on adapting research code for industrial application.

Outside of the clasroom, I serve as Principal Investigator and technical lead for national-level data challenges run by The Alan Turing Institute. I have facilitated or led three Data Study Group projects, including thin-section image segmentation, seismic scan OCR, and SAR time-series spill detection. These roles require high-level technical judgement, fast deployment of working pipelines, and team mentoring across diverse specialisms.


**Core Area 1b Case ii: Usage of Appropriately-Scaled Learning Technological**






***Core Area 1b Evidence***

<a href="/assets/img/DSG_PI_Criteria.pdf" target="_blank" style="text-decoration: underline; color: #004080;">-Requirements (including techonogical ability) for Primary Investigator Position at The Alan Turing Institute as Affirmation of Skillset</a>

<a href="/assets/img/representativecode.jpg" target="_blank" style="text-decoration: underline; color: #004080;">-Representative Code Snippet for Rock Flow Properties Analysis (MSc mentorship project)</a>


-Code Snippet for long term analysis with seasonal variation
-Code Snippet for nc file slicing
-MSc project Descriptions


***Core Area 1b References***





## Core Area 1c Supporting the deployment of learning technologies

***Core Area 1c Case i: Jupyter Notebooks for Engineering Education: Supporting Conceptual Mastery***

As part of my module redevelopment for Contaminant Hydrogeology and Groundwater Remediation and Hydrosystems Engineering and Management, I have integrated interactive Jupyter notebooks developed by TU Dresden through the iNUX Europe initiative and <a href="https://gw-project.org/interactive-education/">The Groundwater Project – Interactive Education</a>. These notebooks shift traditionally lecture-based content into exploratory, browser-accessible environments where students can interact directly with groundwater models, parameterise scenarios, and visualise results.

To enable seamless deployment, I configured Moodle shell links through Binder and JupyterHub pipelines, removing the need for local installation or advanced setup. This scaffolding supports digital equity and accessibility across diverse student hardware and skill levels. The aim is to increase engagement while aligning learning activities with Bloom’s higher-order skills: application, analysis, and evaluation.

The notebooks replace multi-step pen-and-paper tasks with responsive tools that allow full control of key variables. By doing so, they preserve cognitive rigour while reducing procedural friction, supporting a deeper conceptual grasp of transient flow, sorption, and transport processes. Although student-facing use begins in 2025–2026, internal testing has confirmed full compatibility, and I have produced draft screencasts and tutorial guides in preparation for launch.

These materials form part of a broader effort to reorient groundwater teaching around open-source tools and reproducible science, with colleagues across the faculty already expressing interest in adaptation for their modules.

***Core Area 1c Case i Evidence***

<a href="/assets/img/MoodleJupyterIntegration.png" target="_blank" style="text-decoration: underline; color: #004080;">-Screenshot: Moodle-Integrated Jupyter Worksheet </a>


<a href="https://hub.2i2c.mybinder.org/user/gw-inux-jupyter-notebooks-2mkl91ue/notebooks/04_Basic_hydrogeology/GWF_1D_unconf_analytic_v01.ipynb"
   target="_blank" 
   rel="noopener" 
   style="text-decoration: underline; color: #004080;">
  -Live Jupyter Notebook running on Binder (analytical solutions to unconfined aquifer analysis)
</a>

***Core Area 1c Case ii: SYMPLE and INUX Europe: Leading Collaborative EdTech Deployment***

As a curriculum developer and trainer for <a href="https://hydrosymple.com/en/" target="_blank" rel="noopener" style="text-decoration: underline; color: #004080;">the School of Hydrogeological Modeling & Project-Related Strategies (SYMPLE)</a>, I collaborate with colleagues from industry,TU Dresden and Sapienza University of Rome to produce applied hydrogeology material for environmental and water resource professionals.  Typically, learners have foundational theory in place but wish to extend their numerical modleing and uncertainty estimation abilities. They are glolbablly diverse, with majority representaiton from the global south and under-resourced regions (<a href="https://hydrosymple.com/en/trainers/" target="_blank" rel="noopener" style="text-decoration: underline; color: #004080;">Evidence)</a>.

This work foregrounds scalable, decision-focused education in groundwater systems and expands my own practice in adapting teaching to diverse technical and environmental settings. Part of my work with SYMPLE included the development of an online learning platform, the <a href="https://tu-dresden.de/bu/umwelt/hydro/inux/projekt/ueberblick?set_language=en">iNUX project (Interactive understanding of groundwater hydrogeology and groundwater management)</a>, which is an Erasmus+ funded initiative (2022–2025), led by a collaboration between institutions including the Technical University of Dresden, University of Gothenburg and Universidad Politécnica de Cataluña.

The goal of the project is to produce open‑source teaching materials such as interactive videos, Jupyter Notebooks and self‑assessment tasks designed to support educators and students in teaching groundwater science at a European and global level. The materials are <a href="https://github.com/gw-inux"> freely available via GitHub</a> and include instructions for contributing and adapting content to local contexts. My role in the development of this open-access Hydrogeological question bank which required data-wranging, classification by Bloom's Taxonomy, subject matter and difficulty,testing and deployment of subject matter.  


***Core Area 1c Case ii Evidence***

<a href="https://hydrosymple.com/en/" target="_blank" rel="noopener" style="text-decoration: underline; color: #004080;">– School of Hydrogeological Modeling & Project-Related Strategies (SYMPLE)</a>

<a href="https://hydrosymple.com/en/about-us/" target="_blank" rel="noopener" style="text-decoration: underline; color: #004080;"> – Scientific Committee (Symple)</a>

<a href="https://hydrosymple.com/en/trainers/" target="_blank" rel="noopener" style="text-decoration: underline; color: #004080;">– Instructor (Symple)</a>

-ADD FRANCESCA EMAIL DEMONSTRATING COLLABORATION


***Core Area 1c Reflections***


** Core Area 1c References***




This is a test post to check if posts render.
