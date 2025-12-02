---
permalink: /
title: "Karen Shieh"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About Me
------
I am a Berkeley CS/DS undergraduate with a research focus on computer security. I am motivated by the gap between rapidly evolving software systems and the limited tools we have for reasoning about their security, and I want my work to make it easier for engineers to ship fast without shipping vulnerabilities. Right now I am especially interested in techniques that detect security flaws introduced by code changes, so that regressions and risky patches can be caught automatically during development.

Research
------
My research centers on security, automation, and machine learning for software security and systems.

- **LLM-driven fuzzing (SeedAiChemy)**: I worked on using large language models to generate higher-quality seed corpora for fuzzers, improving coverage and bug-finding effectiveness compared to traditional seed selection. This includes designing prompts that steer the model toward diverse, semantically meaningful inputs.
- **Code-change vulnerability detection**: I am studying methods for flagging security-relevant changes in code diffs, with the goal of providing reviewers with targeted warnings about potentially dangerous edits before they are merged.
- **Log rules and anomaly detection**: I am exploring rule-learning and ML-based approaches for automatically deriving invariants from system logs, then using them to surface suspicious or rare behaviors in production.
- **Robotics for surgery**: I contributed to work on autonomous double-knot tying for surgical sutures, developing perception and control pipelines so a robot can tie secure, reliable knots with minimal human supervision (IROS 2025).
- **Estuary: real-time socially interactive agents**: I helped built Estuary, a system for low-latency, socially aware agents that can converse, react, and coordinate across modalities in real time.
- **Simulation of human behavior**: I worked on simulation models of grocery-store shopper behavior, using interaction data to study how layout, congestion, and incentives affect navigation and decision making.

Publications
------
- **SeedAiChemy: LLM-driven seed corpus generation for fuzzing (LLM4SEC)** – [paper](https://people.eecs.berkeley.edu/~daw/papers/seedaichemy.pdf)
- **Autonomous double-knot tying for surgical sutures (IROS 2025)** – [paper](https://autolab.berkeley.edu/assets/publications/media/IROS2025_Knot_Tying_final.pdf)
- **Estuary: low-latency real-time socially interactive agents (CHI 2025)** – [arXiv](https://arxiv.org/abs/2504.14427)

Experience
------
- **Software Engineering Intern, ClickTime** – Developed C#/.NET backend APIs, SQL tables with triggers, and React frontend components for a time-entry heatmap dashboard; designed a reusable full-stack architecture, integrated with existing systems, and used tools like GitHub Copilot to deliver features beyond the original project scope.
- **Web Development Assistant, Safe Transportation Research and Education Center** – Built a dynamic SvelteKit site for California cities to collect and manage bicycle, pedestrian, and wheelchair traffic data for infrastructure projects, and designed database schemas and relationships using Prisma, SQL, and SSMS.
- **Academic Tutor, Data 140 (Probability for Data Science)** – Guide students through core probability concepts during labs and office hours, clarify problem-solving strategies, and provide detailed feedback on assignments to improve understanding and performance.
- **Regents & Chancellor’s Scholars Association – Corporate Relations Co-leader** – Organized partnerships and events connecting scholars with industry, managing outreach, logistics, and team coordination.
- **Team Lead in CS 162 (Operating Systems) and INFO 159 (NLP)** – Led project teams on systems and NLP projects, coordinating architecture decisions, code quality, testing, and documentation.

Skills
------
- **Systems & Security**: Docker, Linux systems, security engineering practices, log and telemetry analysis, data gathering and wrangling for security tasks.
- **Software & Frameworks**: Experience across modern web stacks (SvelteKit, React, Prisma, .NET, SQL) and tooling for experiment-heavy research.
- **Machine Learning & Security**: Background in ML, deep learning, and their applications to fuzzing, anomaly detection, and code-change analysis.
- **Ways of working**: Fast learner, comfortable ramping up on new frameworks and libraries, and effective in fast-paced, collaborative research environments.

Coursework
------
My coursework spans foundations, systems, machine learning, and security:

- Algorithms  
- Machine Structures  
- Machine Learning  
- Optimization Models  
- Computer Security  
- Deep Neural Networks  
- Operating Systems  
- Natural Language Processing  

Academics
------
I maintain a 4.0 GPA at Berkeley and actively seek out advanced, conceptually challenging courses. I am particularly drawn to classes that combine theory with hands-on systems work, where I can apply ideas to real software and data.

Research Philosophy
------
I am motivated by research that has concrete impact on the security and reliability of real systems. I am drawn toward problems where automation and ML can meaningfully augment human experts, whether by surfacing subtle vulnerabilities, prioritizing critical alerts, or generating better test inputs. Ultimately, I want my work to help make secure-by-default development practical at scale, and to bridge the gap between cutting-edge ML and trustworthy software engineering.

<!--
This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. Incidentally, these same features make it a great template for anyone that needs to show off a professional template!

 You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and Markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://karen93shieh.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://karen93shieh.github.io/talks), each [individual page](https://karen93shieh.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://karen93shieh.github.io/cv), and the [map of places you've given a talk](https://karen93shieh.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://karen93shieh.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
-->
