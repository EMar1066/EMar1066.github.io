---
layout: post
title: "Core Area 1: Operational Issues"
date: 2025-07-30
categories: blog
image: PunchCardbw.jpg
---

<p style="font-size: 1.5em; text-align: center;">
<em> “Technological change is not additive; it is ecological.”</em>
</p>

<p style="text-align: right;">
<em>–Neil Postman </em>
</p>

## Preface 

## Core Area 1a: Understanding Constraints and Benefits of different technologies
<h2 id="Core_Area_1"></h2>

<h2 id="Core_Area_1_a"></h2>


***Core Area 1a - Case i: PowerPoint vs. Sway vs. Mentimeter***

In my teaching practice, I rely primarily on PowerPoint for lecture delivery, supplemented selectively by other tools depending on pedagogical need. While many of my CPD courses have been delivered using Mentimeter, which is often praised for its interactivity through quizzes and polls, I have found it unsuitable as a core presentation platform. My lectures often involve animated diagrams, flowline sequences, and real-time annotation to highlight fluid behaviours or trace conceptual relationships. This visual and spatial interactivity, often accompanied by verbal walkthroughs and student note-taking, is central to how I scaffold complex engineering content. Mentimeter, by contrast, limits interactivity to polls and short-form input, without support for animated content, inline editing, or fluid visual pacing. It is also time-consuming to build, lacks accessibility features, and does not accommodate the kind of real-time responsiveness that my subjects demand. For this reason, I use it sparingly, typically for standalone quiz rounds or checkpoint questions, before returning to PowerPoint, which supports the layered, media-rich delivery style that best suits my material. These decisions reflect not only practical constraints, but a deeper consideration of what types of engagement best support understanding. This distinction is explored by Kirkwood and Price (2014), who argue that technology should be judged by how well it supports specific educational goals.

***Core Area 1a - Case ii: : Moodle vs. D2l vs. Canvas***
I have worked extensively with Moodle, D2L (Desire2Learn), and Canvas across different institutions, and each has presented its own strengths and limitations. I first encountered Moodle in its early days, and while its modular design allowed for flexibility, it often required manual structuring and lacked polish in interface design. D2L offered more consistency in navigation and grading tools, particularly for scaffolded assessment structures, but tended to be inflexible when trying to embed external content or apply complex workflows. Canvas, by contrast, felt modern and lightweight, with cleaner integration of multimedia, straightforward assignment creation, and better cross-platform accessibility. However, it could feel restrictive when customisation was needed or when managing large numbers of files and resources.

Returning to Moodle in my current role has meant revisiting a platform that, while widely adopted, still carries some of its earlier inefficiencies. Navigation can feel fragmented, and many features (such as assignment feedback and gradebook tools) require multiple layers of configuration to work as intended. Despite this, I have structured my Moodle pages carefully to reduce cognitive load, using collapsible sections, visual flowcharts, and labelled downloads to guide students through each week’s materials. I also supplement Moodle’s limitations by embedding interactive tools like Jupyter Notebooks. While no platform has offered a perfect solution, my experience across systems has allowed me to identify what is worth customising and what requires workarounds. The goal remains the same: to ensure that the learning environment supports clarity, progression, and meaningful engagement with the course content.

***Core Area 1a - Case iii: Numerical and Analytical Solvers***
Engineering is a science of data, and every value that we calculate (estimate) is a mean, with an associated variance. In supporting students' application of analytical and numerical theory, I routinely use Excel, OrangeML, and Python, each selected according to the complexity of the task and the experience level of the cohort. Excel remains the most immediately accessible platform. It allows students to explore finite difference models, basic stochastic processes, and parameter-driven simulations using cell-based logic. The learning curve is low, which makes it well suited for early-stage undergraduate tasks where the goal is to visualise theory rather than build software. However, its scalability is limited, and its suitability declines rapidly for high-dimensional or data-intensive applications.

For MSc students who are less coding-inclined, I have introduced GUI tools such as OrangeML. It provides a node-based machine learning interface that allows MSc students to work with clustering, regression, and time-series classification techniques without needing to script models from scratch. This bridges the gap between concept and implementation. Students can construct pipelines, adjust model parameters, and visualise outputs, all while gaining intuition for how algorithms behave under different conditions. However, its customisability is limited, and it serves more as an educational stepping stone than a research tool.

MSc students who have prowess in both using and creating technology soluation are directed towards Python, which by contrast, offers full control, extensibility, and integration with numerical libraries such as NumPy, SciPy, and Scikit-learn. It is my primary environment for teaching finite difference models, environmental data processing, and ML workflows involving µCT or time-series data. The trade-off, of course, is that it has a steep learning curve. For students who are not from a programming background, this can present a barrier. To support them, I structure scaffolded notebooks with commented code, embedded visual outputs, and real-world datasets, allowing them to engage with the methods at a depth that matches their ability. Across all platforms, the key decision is not what the tool can do, but what it enables the student to understand and build from. The goal is always to match power with usability and support learning without overwhelming it.

***Reflections***

***Evidence***

***References***

Kirkwood, A. & Price, L. (2014). Technology-enhanced learning and teaching in higher education: what is ‘enhanced’ and how do we know? A critical literature review. Learning, Media and Technology, 39(1), 6–36.  https://doi.org/10.1080/17439884.2013.770404

## Core Area 1b: Technical knowledge and ability in the use of learning technology

 work fluently across a range of technical environments, including Python, MATLAB, FORTRAN, C++, SQL, and HTML. I use GitHub for collaborative version control, Jupyter for interactive analysis, and tools such as TauFactor, PoreSpy, and Palabos for numerical and pore-network modelling. My experience includes building machine learning classifiers, scripting time-series analysis routines, and deploying image-processing pipelines. I have written simulation code for groundwater transport, trained neural networks for geospatial classification, and developed technical visualisations to support both teaching and research.

My formal design and writing background also informs how I structure educational material. Before returning to engineering, I worked as a professional editor and graphic designer—skills I now use to build clear, visually coherent lectures and guides that maintain narrative focus across complex topics.

In the undergraduate curriculum, I apply these skills to design problem-solving environments using Python and Excel. Students use pre-built notebooks and models to explore environmental time series, implement Mann–Kendall trend detection, run parameter sweeps on finite difference models, and interpret real hydrological datasets. These tools are scaffolded to their level, allowing them to engage with technical content without being blocked by syntax.

At the MSc level, I co-develop machine learning and modelling pipelines with students. One current project involves permeability estimation from µCT image data using random forests. We work via shared GitHub repositories, where I support the codebase and integrate advanced simulation tools. In past work, I’ve supervised students through the full development of environmental classification models and advised on adapting research code for industrial application.

Beyond the classroom, I serve as Principal Investigator and technical lead for national-level data challenges run by The Alan Turing Institute. I have facilitated or led three Data Study Group projects, including thin-section image segmentation, seismic scan OCR, and SAR time-series spill detection. These roles require high-level technical judgement, fast deployment of working pipelines, and team mentoring across diverse specialisms.

While I have deep experience coding from scratch, I also work pragmatically within institutional platforms. I’ve used Moodle since 2009, and previously taught with D2L and Canvas. My Moodle shells are structured for clarity and include embedded materials, labelled blocks, and integrated tools. I use PowerPoint as my primary delivery tool for its precise pacing and support for animated diagrams; I use Mentimeter sparingly when it adds value for rapid polling or diagnostics. Each platform is assessed on what it affords—not how it markets itself.

***Reflections***

***Evidence***

***References***





## c) Supporting the deployment of learning technologies

***Case i: Jupyter Notebooks for Engineering Education: Supporting Conceptual Mastery***

As part of my module redevelopment for Contaminant Hydrogeology and Groundwater Remediation and Hydrosystems Engineering and Management, I have integrated interactive Jupyter notebooks developed by TU Dresden through the iNUX Europe initiative and <a href="https://gw-project.org/interactive-education/">The Groundwater Project – Interactive Education</a>. These notebooks shift traditionally lecture-based content into exploratory, browser-accessible environments where students can interact directly with groundwater models, parameterise scenarios, and visualise results.

To enable seamless deployment, I configured Moodle shell links through Binder and JupyterHub pipelines, removing the need for local installation or advanced setup. This scaffolding supports digital equity and accessibility across diverse student hardware and skill levels. The aim is to increase engagement while aligning learning activities with Bloom’s higher-order skills: application, analysis, and evaluation.

The notebooks replace multi-step pen-and-paper tasks with responsive tools that allow full control of key variables. By doing so, they preserve cognitive rigour while reducing procedural friction, supporting a deeper conceptual grasp of transient flow, sorption, and transport processes. Although student-facing use begins in 2025–2026, internal testing has confirmed full compatibility, and I have produced draft screencasts and tutorial guides in preparation for launch.

These materials form part of a broader effort to reorient groundwater teaching around open-source tools and reproducible science, with colleagues across the faculty already expressing interest in adaptation for their modules.


***Case ii: SYMPLE and INUX Europe: Leading Collaborative EdTech Deployment***

As a curriculum developer and trainer for SYMPLE, I collaborate with colleagues from TU Dresden and Sapienza University of Rome to produce applied hydrogeology materials for
use in under-resourced regions. This work foregrounds scalable, decision-focused education in groundwater systems and expands my own practice in adapting teaching to diverse technical
and environmental settings. Part of my work with SYMPLE included the development of adn online learning platform, the <a href="https://tu-dresden.de/bu/umwelt/hydro/inux/projekt/ueberblick?set_language=en">iNUX project (Interactive understanding of groundwater hydrogeology and groundwater management)</a>, which is an Erasmus+ funded initiative (2022–2025), led by a collaboration between institutions including the Technical University of Dresden, University of Gothenburg and Universidad Politécnica de Cataluña.

The goal of the project is to produce open‑source teaching materials such as interactive videos, Jupyter Notebooks and self‑assessment tasks designed to support educators and students in teaching groundwater science at a European and global level. The materials are <a href="https://github.com/gw-inux"> freely available via GitHub</a> and include instructions for contributing and adapting content to local contexts. My role in the development of this open-access Hydrogeological question bank which required data-wranging, classification by Bloom's Taxonomy, subject matter and difficulty,testing and deployment of subject matter.  

-Asynchronoous classroom
-Numerical Modeling and Uncertainty Estimation
-Global South
-Question Bank Data wranglig  - TU Dresden and Others.

<a href="https://www.onyx-editor.com/onyxeditor/editor;jsessionid=CBA16C0C2A0F56DCAB4198AFC18A1BED?0">Onyx Editor</a>

<a href="https://tu-dresden.de/studium/im-studium/studienorganisation/lehrangebot/lernplattform-opal?set_language=en))">OPAL (Online Platform for Academic Teaching and Learning at the TU Dresden</a>

https://gw-inux.github.io/iNUX-Handbook/?utm_source=chatgpt.com
### Reflection
### Evidence
### References




This is a test post to check if posts render.
