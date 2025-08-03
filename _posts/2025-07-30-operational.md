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

The field of engineering requires adaptablity and rapid uptake of new tools and working environments.






**Guide**

* <a href="#Core_Area_1a">Jump to Core Area 1a: Understanding the Constraints and Benefits of Different technologies</a>
* <a href="#Core_Area_1b">Jump to Core Area 1b: Technical Knowledge and Ability in the use of Learning Technology</a>
* <a href="#Core_Area_1c">Jump to Core Area 1c Supporting the Deployment of Learning Technologies</a>




<h2 id="Core_Area_1a"></h2>

## Core Area 1a Preface 

## Core Area 1a: Understanding Constraints and Benefits of different technologies

Engineering education is built on problem-solving, and effective tool use is part of that discipline. The technologies I use, whether for delivery, interaction, or modelling, are selected based on what they enable my students to do, not how they appear in a catalogue. I have taught across analogue and digital settings: in classrooms with chalkboards and acetates, and in institutions adopting successive generations of VLEs and software. Each tool brings trade-offs. Some offer accessibility but little depth; others enable rigour but demand steep onboarding. Across lecture platforms, learning environments, and analytical systems, my approach has remained consistent. I choose technologies that extend students’ capacity to engage with structure, test logic, and explore models they could not build by hand. The cases below illustrate how I have applied that principle in practice.

***Core Area 1a - Case i: PowerPoint vs. Mentimeter***

In my large-group engineering lectures, I use PowerPoint as my primary delivery platform due to its control over sequencing, animation, and on-the-fly annotation. These features are essential for communicating spatial or time-dependent processes in fluid mechanics and contaminant transport. I structure content around staged visual builds and prompt note-taking, which allows students to follow complex derivations or flow behaviours with clarity. When I need a quick check of student understanding, I use Mentimeter for single-question polls or live diagnostics. However, it has clear limitations. Unlike PowerPoint, it lacks animation, inline editing, and visual control. More critically, it fails accessibility standards: slides render as images without alt text, requires all students to have a mobile device and navigation for screen readers or keyboard-only users is restricted. Because of these constraints, I use Mentimeter only in brief, standalone instances and return immediately to PowerPoint, which offers a more coherent and inclusive experience for structured delivery.

***Core Area 1a - Case ii: : Moodle vs. D2l vs. Canvas***

Through institutions I have taught at, I've use Moodle, D2L (Desire2Learn), and Canvas, all of which were institutionally selected as primary learning platforms. Each presented distinct trade-offs in usability, structure, and customisation. Moodle’s modular design supports flexibility, but its interface remains cluttered and many core features, such as assignment feedback, gradebook configuration, and resource upload, require multiple configuration steps. D2L offers a more consistent experience for structured assessments and navigation but is less flexible when embedding external content or building non-linear workflows. Canvas is streamlined, with cleaner multimedia integration and simplified assignment creation, but becomes restrictive when handling large resource libraries or custom layouts. In my current role I use Moodle, and have adapted it to reduce cognitive load by implementing collapsible topic sections, labelled resource flows, captioned Panopto recordings of lecture material and embedded tools such as Jupyter Notebooks. These adaptations help offset structural clutter and guide students clearly through weekly materials. Each platform requires workarounds, but familiarity with their affordances has allowed me to design around limitations and maintain course coherence.

***Core Area 1a - Case iii: Analytical and Numerical Tools***

Engineering sits at the intersection of science and technology and is inherently dependent on data-driven modelling. To support students in applying numerical and analytical theory, I use a sequence of platforms tailored to their technical background and the complexity of the task. Excel provides an accessible entry point <a href="/assets/img/ENVI1195CMALTPOST.pdf" target="_blank" style="text-decoration: underline; color: #004080;">(Evidence XX)</a> for students to build finite difference models, run parameter-driven simulations, and explore system sensitivity using cell-based logic. It is ideal for conceptual grounding, though limited in handling high-dimensional or computationally intensive tasks. For MSc students less familiar with coding, I use Orange, AutoML or XLMiner, GUI-based machine learning environments that enables pipeline construction and parameter adjustment through visual interfaces <a href="/assets/img/msc_gui_examples.png" target="_blank" style="text-decoration: underline; color: #004080;">(Evidence XX)</a>. They offer a low barrier to entry but lack the flexibility needed for research-level work. For advanced students, I use Python with scaffolded notebooks and real datasets to build simulations and machine learning pipelines <a href="/assets/img/msc_ai_slices.png" target="_blank" style="text-decoration: underline; color: #004080;">(Evidence XX)</a>. These tools are powerful and adaptable, but carry a steeper learning curve and demand more prerequisite knowledge. Each platform brings trade-offs in control, accessibility, and scalability. I select and sequence them deliberately to match student readiness and learning goals.

***Evidence***

-Moodle shell screenshot ???

-Old PP vs. New??? 

***Core Area 1a Reflections***

I began teaching with blackboards, acetates, and printed handouts. Technology was optional. That changed quickly. As digital platforms became more accessible, I adapted—not because the tools were novel, but because they made better teaching possible. PowerPoint, once static, became a layered, animated workspace. Tablets enabled real-time sketching; screen recording made walkthroughs replayable. These shifts weren’t cosmetic. They reshaped how I structured concepts and how students interacted with them. But no tool is seamless. Microsoft Office remains central across most institutions, yet its components often conflict: formatting breaks between apps, accessibility features are inconsistent, and Excel still mistakes model inputs for calendar dates. As Lu et al. (2022) show, these usability flaws are common and persistent. I’ve come to accept Office as flawed but essential infrastructure—stable enough to build around, but never to be trusted blindly.

Mentimeter, by contrast, is often praised for engagement but fails in pedagogical depth. Unless a session is built entirely within the platform, accessibility collapses. I’ve seen it break mid-poll. Edits freeze. Data vanish. While studies highlight perceived enjoyment (Cutri & Mikkonen, 2021; Dervan, 2014), short-term activation is not long-term understanding. Selwyn (2016) reminds us that digital tools often reward visibility, not cognition. I’ve seen that pattern. A flash of activity, then a return to passivity, which I have also seen occur in my classes that incorporate frequent Mentimeter quizzes, often referred to a poll-fatigue. As I result, I now only use polling only when it serves a specific diagnostic or pacing function, never as the spine of a session. That distinction aligns with Kirkwood and Price (2014), who argue that digital tools should be judged by how well they support clearly defined educational goals.

With platforms like Moodle, D2L, and Canvas, the constraint is structural. These systems are chosen institutionally, not pedagogically. Adoption reflects procurement logic and legacy compatibility more than teaching need. Usability studies (Vlachogianni & Tselios, 2023; Lu et al., 2022) confirm what most staff already know: these tools require time, patience, and a great deal of manual configuration. Still, they can be made to work. I’ve used them to deliver simulations, structured readings, and scaffolded assignments. But doing so requires treating the VLE as a shell to be retrofitted, not a pedagogical system in itself.

This challenge becomes clearest in technical teaching. In engineering, a tool that’s too simple teaches little; too complex, and it alienates. That trade-off shapes my platform choices. Excel works well for early-stage exploration but fails under complexity. Orange provides visual workflows for students still building confidence, though it lacks depth. Python delivers scale and flexibility but demands fluency. I sequence these deliberately, not for convenience, but to support a learning arc: from intuition to abstraction to implementation. Laurillard (2013) argues that effective TEL environments must scaffold conceptual development while supporting authentic practice. That’s the standard I apply. I don’t adopt tools based on availability or trend. I test them against what my students need to understand next.

***Core Area 1a References***

* Castañeda, L. and Selwyn, N., 2018. More than tools? Making sense of the ongoing digitizations of higher education. International Journal of Educational Technology in Higher Education, 15(1), p.22. https://doi.org/10.1186/s41239-018-0109-y

* Cutri, R.M. and Mikkonen, J., 2021. Student perceptions of using Mentimeter as a student response system in higher education. Education and Information Technologies, 26, pp.6557–6573. https://doi.org/10.1007/s10639-021-10589-5

* Dervan, P., 2014. Increasing in-class student engagement using Mentimeter, an interactive presentation software. AISHE-J: The All Ireland Journal of Teaching and Learning in Higher Education, 6(3), pp.1801–1815. https://doi.org/10.62707/aishej.v6i3.180 

* Kirkwood, A. & Price, L. (2014). Technology-enhanced learning and teaching in higher education: what is ‘enhanced’ and how do we know? A critical literature review. Learning, Media and Technology, 39(1), 6–36.  https://doi.org/10.1080/17439884.2013.770404

* Laurillard, D., 2013. Teaching as a Design Science: Building Pedagogical Patterns for Learning and Technology. New York: Routledge.

* Lu, J., Schmidt, M., Lee, M. and Huang, R., 2022. Usability research in educational technology: A state-of-the-art systematic review. Educational Technology Research and Development, 70(6), pp.1951–1992. https://doi.org/10.1007/s11423-022-10152-6

* Selwyn, N., 2016. Is Technology Good for Education? Cambridge: Polity Press.

* Vlachogianni, P. and Tselios, N., 2023. Perceived usability evaluation of educational technology using the post-study system usability questionnaire (PSSUQ): a systematic review. Sustainability, 15(17), p.12954.

<h2 id="Core_Area_1b"></h2>

## Core Area 1b: Technical Knowledge and Ability in the use of Learning Technology

My technical proficiency has developed over more than two decades of applied work in research, regulation, and higher education. I have no formal certifications in learning technology, nor do I seek them. My fluency has grown through necessity: modelling groundwater transport, supervising MScs in environmental machine learning, building simulation pipelines, and supporting student research. These skills are not peripheral. They underpin my teaching, enable my supervision, and have led to external roles where technical depth is essential. As Principal Investigator for a national research sprint with The Alan Turing Institute, I was selected on the strength of my applied programming, data science, and collaborative leadership. Their requirements form part of my evidence for this section.

My work spans Python, Julia, MATLAB, Maple, Visual Basic, FORTRAN, C++, SQL, HTML, and other environments, deployed across both Windows and Linux systems. I use GitHub for version control, Jupyter for interactive teaching and research, and tools such as TauFactor, PoreSpy, and Palabos for pore-network and flow modelling. These are not extracurricular tools—they are embedded in my teaching, research, and student supervision.

In undergraduate teaching, I design scaffolded Python and Excel environments that let students explore real datasets and environmental models. These include pre-built notebooks for Mann–Kendall trend detection, time-series exploration, and finite difference simulations. At MSc level, I support more complex work. One recent project involved permeability estimation from µCT image data using random forests, supported through shared GitHub repositories and Python-based workflows. I have also supervised MSc projects on environmental classifiers and advised students adapting code for industry.

Beyond the classroom, I lead national-scale technical projects for the Alan Turing Institute. These have included segmentation of thin-section geological imagery, OCR of seismic scans, and time-series detection of oil spills in SAR data. These projects are team-based, time-limited, and high-stakes. They demand fast deployment of robust pipelines, clear technical communication, and support for researchers from diverse disciplinary backgrounds.

Alongside this technical experience, I bring a background in design and editorial work. During my undergraduate studies in Chemical Engineering and Comparative Literature, I worked for five years as a newspaper editor and illustrator. That parallel training continues to inform how I present information, whether through a visual model, a coded interface, or a written explanation. Tools are not just functional; they are rhetorical. How they present information matters as much as what they compute.

***Core Area 1b Evidence***

<a href="/assets/img/DSG_PI_Criteria.pdf" target="_blank" style="text-decoration: underline; color: #004080;">-Requirements (including techonogical ability) for Primary Investigator Position at The Alan Turing Institute as Affirmation of Skillset</a>

<a href="/assets/img/representativecode.jpg" target="_blank" style="text-decoration: underline; color: #004080;">-Representative Code Snippet for Rock Flow Properties Analysis (MSc mentorship project)</a>


-Code Snippet for long term analysis with seasonal variation
-Code Snippet for nc file slicing
-MSc project Descriptions


***Core Area 1b Reflections***

My relationship with learning technology predates my teaching. I started coding on an Apple IIe at ten, moved to BASIC and HTML in my teens, and was already using code to explain ideas when I began teaching in Canada, years before my PhD. That early habit persists. What has changed is the scale and precision of the tools: I now build environments that visualise, simulate, and guide learning in ways once out of reach.

Like a carpenter with access to power tools, I’ve expanded what I can build, but like carpentry, the skill is in the joins. Technology lets me plan more clearly, structure more tightly, and shape how learning unfolds. Whether I’m constructing a simulation workflow, tutorial session, classroom lecture or a scaffolded spreadsheet exercise, the goal is the same: to build environments that hold together and that shape conceptual progress in my audience (more examples are detailed in greather depth in Core Area 1c). And like any good engineer, I have aquired these technical skills throughout my career. As Laurillard (2012) notes, effective technology use demands deliberate design. 

This principle shapes how I teach. Some students co-develop machine learning models with me; others work in spreadsheet environments to test system dynamics and explore assumptions. Biggs and Tang (2011) argue that methods must align with learning outcomes, and Beetham and Sharpe (2007) remind us that platforms only gain value when guided by clear pedagogical purpose.

Structure matters. Kirschner, Sweller, and Clark (2006) show that students benefit most from guided, well-sequenced instruction. A polished tool doesn’t teach on its own: A scaffolded, logical progression does. I’ve seen students learn more from a notebook that builds one idea at a time than from a feature-heavy lecture that overwhelms without clarity.

These are not purely technical decisions; they are pedagogical. The aim is to help students build something meaningful, whether it’s a model or an idea that holds under scrutiny.

***Core Area 1b References***

* Beetham, H. and Sharpe, R., 2007. Rethinking pedagogy for a digital age: Designing and delivering e-learning. London: Routledge.

* Biggs, J., Tang, C. and Kennedy, G., 2022. Teaching for quality learning at university. 5th ed. Maidenhead: McGraw-Hill Education (UK).

* Kirschner, P.A., Sweller, J. and Clark, R.E., 2006. Why minimal guidance during instruction does not work: An analysis of the failure of constructivist, discovery, problem-based, experiential, and inquiry-based teaching. Educational Psychologist, 41(2), pp.75–86. https://doi.org/10.1207/s15326985ep4102_1

* Laurillard, D., 2013. Teaching as a design science: Building pedagogical patterns for learning and technology. Abingdon: Routledge.


<h2 id="Core_Area_1c"></h2>

## Core Area 1c Supporting the deployment of learning technologies

***Core Area 1c Case i: Jupyter Notebooks for Engineering Education: Supporting Conceptual Mastery***

As part of my module redevelopment for MSc-level Contaminant Hydrogeology and Groundwater Remediation and Hydrosystems Engineering and Management, I have integrated interactive <a href="https://docs.jupyter.org/en/latest/" target="_blank" style="text-decoration: underline; color: #004080;">Jupyter notebooks</a>. These are browser-based environments that combine code, equations, and visual outputs in a single, dynamic document, allowing students to explore models directly, adjust parameters, and visualise responses in real time.  The students, then after learning theroy used the notebooks to analyse engineering cases numerically. The specific notebooks I deployed were produced by TU Dresden through the iNUX Europe initiative and <a href="https://gw-project.org/interactive-education/" target="_blank" style="text-decoration: underline; color: #004080;">The Groundwater Project – Interactive Education</a>. These resources are open-access, modifiable, and forkable from their GitHub repository <a href="/assets/img/Binder_Github_Source.jpg" target="_blank" style="text-decoration: underline; color: #004080;">(Evidence)</a>, making them adaptable to specific teaching goals and responsive to student needs.

To ensure broad accessibility, I initially deployed the notebooks using  <a href="https://mybinder.org/" target="_blank" style="text-decoration: underline; color: #004080;">Binder</a> and JupyterHub pipelines, linked through our Moodle shell. This avoided the need for students to perform local installation of the tools, supporting digital equity across student devices and skill levels. However, Binder introduces delays and usability issues: long launch times, exposed code blocks, and unfamiliar controls create friction for students new to programming. While transparency can benefit advanced users, for many students, these extra steps distract from the conceptual focus. Accessing menus, collapsing code cells, and running entire scripts became an obstacle to my teaching goal: to clarify the science, not foreground the tool.

To address this, I re-evaluated my student needs and redeployed the models using <a href="https://streamlit.io/"> Streamlit target="_blank" style="text-decoration: underline; color: #004080;"</a>, which launches more quickly, runs automatically, and presents a clean, minimal interface. This version behaves more like a scientific calculator.  It allows students to focus on the intent of the calculations using a tool that is responsive and distraction-free. For many students, this lowers the barrier to entry and shifts attention to system behaviour and conceptual reasoning.

These applications replace multi-step, pen-and-paper exercises with dynamic interfaces that give students direct control over key variables while reducing procedural overhead. Once core theory is mastered, the tools enable exploration of more complex and engineering-relevant scenarios: Problems that would be too time-consuming or error-prone to tackle by hand. This shift supports deeper engagement with course content, allowing students to focus on conceptual understanding rather than mechanical repetition. Incresed integration of Jupyter Notebooks will continue in 2025–2026.

This deployment forms part of a broader push within my teaching to support open-source, reproducible science in groundwater education. Colleagues have expressed interest in adapting the Streamlit notebooks for use in related environmental modules.

***Core Area 1c Case i Evidence***

<a href="/assets/img/MoodleJupyterIntegration.png" target="_blank" style="text-decoration: underline; color: #004080;">-(Evidence) Screenshot: Moodle-Integrated Jupyter Worksheet Links as Deployed </a>

<a href="https://mybinder.org/v2/gh/EMar1066/HydroG-Jupyter-Notebooks/HEAD?filepath=04_Basic_hydrogeology/GWF_1D_unconf_analytic_BC3.ipynb"
   target="_blank" 
   rel="noopener" 
   style="text-decoration: underline; color: #004080;">
(Evidence) Launch Interactive Notebook via Binder: Analytical solution for 1D unconfined flow with two defined head boundaries
</a> (Useful for demonstrating or modifying coded solutions to presented theory, but code must be run by 'view'->'collapse all cells' then 'run'->'run all cells')


<a href="https://gwf-1d-unconf-analytic.streamlit.app/" target="_blank" style="text-decoration: underline; color: #004080;">(Evidence) Launch Interactive Notebook via Streamlit: Analytical solution for 1D unconfined flow with two defined head boundaries </a> (Useful for drawing focus to theory without distraction. No run controls required.)


***Core Area 1c Case ii: SYMPLE and INUX Europe: Leading Collaborative EdTech Deployment***

As a curriculum developer and trainer for <a href="https://hydrosymple.com/en/" target="_blank" rel="noopener" style="text-decoration: underline; color: #004080;">the School of Hydrogeological Modeling & Project-Related Strategies (SYMPLE)</a>, I collaborate with colleagues from industry,TU Dresden and Sapienza University of Rome to produce applied hydrogeology material for environmental and water resource professionals.  Typically, learners have foundational theory in place but wish to extend their numerical modleing and uncertainty estimation abilities. They are glolbablly diverse, with majority representaiton from the global south and under-resourced regions (<a href="https://hydrosymple.com/en/trainers/" target="_blank" rel="noopener" style="text-decoration: underline; color: #004080;">Evidence</a>).

This work foregrounds scalable, decision-focused education in groundwater systems and expands my own practice in adapting teaching to diverse technical and environmental settings. Part of my work with SYMPLE included the development of an online learning platform, the <a href="https://tu-dresden.de/bu/umwelt/hydro/inux/projekt/ueberblick?set_language=en" target="_blank" style="text-decoration: underline; color: #004080;">iNUX project (Interactive understanding of groundwater hydrogeology and groundwater management)</a>, which is an <a href="https://erasmus-plus.ec.europa.eu/" target="_blank" style="text-decoration: underline; color: #004080;">Erasmus+ </a> funded initiative (2022–2025), that supports open-source, interactive education in groundwater science. Led by TU Dresden, Gothenburg, and Universidad Politécnica de Cataluña, the same project that developed the Jupyter-based tutorials mentioned in Case i, as well as <a href="https://jupyter.org/" target="_blank" style="text-decoration: underline; color: #004080;">, and assessment banks designed for international adaptation.

My contribution focused on the development of a hydrogeological question bank: curating and classifying problems by Bloom’s Taxonomy of Cognitive Objectives (1956), technical domain, and difficulty level. This involved both data-wrangling and subject-specific content development. I also supported testing and early deployment of the materials, which are now <a href="https://github.com/gw-inux" target="_blank" style="text-decoration: underline; color: #004080;"> freely available via GitHub</a> and licensed for reuse by educators globally.

***Core Area 1c Case ii Evidence***

<a href="https://hydrosymple.com/en/" target="_blank" rel="noopener" style="text-decoration: underline; color: #004080;">– School of Hydrogeological Modeling & Project-Related Strategies (SYMPLE)</a>

<a href="https://hydrosymple.com/en/about-us/" target="_blank" rel="noopener" style="text-decoration: underline; color: #004080;"> – Scientific Committee (Symple)</a>

<a href="https://hydrosymple.com/en/trainers/" target="_blank" rel="noopener" style="text-decoration: underline; color: #004080;">– Instructor (Symple)</a>

-ADD FRANCESCA EMAIL DEMONSTRATING COLLABORATION

***Core Area 1c Reflections***

Integrating Jupyter Notebooks into my groundwater modules reshaped how I approached conceptual teaching. Rather than rely on static examples, lengthy,sometimes iterative calculations, or manually plotted function curves, I could now offer students interactive models where changes to parameters yielded immediate, visual consequences. This was both engaging for the students and clarified dynamics that are often abstract when taught through slides or equations.

Setting up deployment through Binder and JupyterHub eliminated the trial and error setup that usually comes with new tools. But what I hadn’t anticipated was how much this mattered. For students with limited programming experience, bypassing installation meant the difference between participation and disengagement. I began thinking of accessibility not only in terms of hardware or screen readers, but also in terms of workflow design. It imporessed on me the importance of removing barriers to entry without lowering intellectual expectations.

The shift to interactive models allowed students to explore groundwater processes with a level of immediacy that static methods rarely permit. When they adjusted parameters and saw effects unfold in real time, it anchored abstract concepts in visual logic. I observed higher levels of engagement and even excitement during exercises and tutorials which in the past have been passive interest, particularly among students who had previously struggled with the abstractions of flow and transport. To me, this suggested that interactive tools, when well scaffolded, can serve as cognitive footholds and more than simple novelties.  Based on this reception, the notebooks now have a regular presence across the module, supporting independent study and problem-solving outside of scheduled contact hours. This iterative use reinforces understanding and aligns with Bruner’s (1960) principle of revisiting foundational ideas at increasing levels of complexity. It also reflects Sweller et al.’s (2011) work on reducing cognitive load to support deeper conceptual development.

My involvement with SYMPLE and iNUX cemented this thinking. Supporting the design and deployment of open-access tools as led by senior academics and global partners required a different type thinking regarding technology deployment that centred on modularity, clarity, and reuse: How to make learning artefacts that would hold up in different languages, curricular settings, and delivery modes (Conole, 2013).  Working on the question bank in particular pushed me to think more systematically about how learning artefacts can travel and how their structure, language, and cognitive demands can be adapted while preserving their integrity. Classifying questions by Bloom’s taxonomy gave the bank internal structure; hosting through GitHub gave it longevity and adaptability (Beetham et al., 2012).

More than anything, these projects I've been fortunate enought to have been involved with have reinforced something foundational in my practice: That good educational technology is not built for the classroom alone. When well-designed, it can effectively work across time zones, platforms, and pedagogies.  Working on these projects taught me that educational technology, when built for openness and reuse, can expand access without lowering its educational value (Hilton, 2016; Beetham et al., 2012).

***Core Area 1c References***

* Beetham, H., Falconer, I., McGill, L. and Littlejohn, A., 2012. Open practices: Briefing paper.
 
* Bloom, B., 1956. A taxonomy of cognitive objectives. New York: McKay.
  
* Bruner, J.S., 1960. The Process of Education, Harvard, Univ. Press, Cambridge, Mass.

* Conole, G., 2012. Designing for learning in an open world (Vol. 4). Springer Science & Business Media.

* Hilton III, J., 2016. Open educational resources and college textbook choices: A review of research on efficacy and perceptions. Educational technology research and development, 64(4), pp.573-590.

* Sweller, J., Ayres, P. and Kalyuga, S., 2011. Emerging themes in cognitive load theory: the transient information and the collective working memory effects. In Cognitive load theory (pp. 219-233). New York, NY: Springer New York.
