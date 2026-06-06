---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm currently a **final-year PhD. Candidate** from Hong Kong PolyU (AAE) and will be graduated within 2026. My PhD. Thesis is **Promoting Underwater Visual Intelligence: From 2D to 3D Applications**. I am supervised by [Prof. Chih-yung Wen](https://www.polyu.edu.hk/aae/people/academic-staff/ir-prof-wen-chih-yung/) and co-supervised by [Prof. Bing Wang](https://bingcs.github.io/). Before I pursuit my doctoral degree, I received a master degree with **distinction** also from PolyU supervised by [Prof. Boyang Li](https://boyangli.com/team/) in 2023, and a bachelor degree from Nanjing University of Aeronautics and Astronautics (NUAA) supervised by [Prof. Meng Yu](https://scholar.google.com/citations?user=nGZhpS4AAAAJ&hl=zh-CN) in 2019.  

Research Focus
======

My PhD. reserach **consistently locates in** how to improve the **underwater images degraded by water medium** (including color-bias, low-contrast, and blur effects that weaken the vision-based tasks) to support both 2D visual evaluation and downstream 3D reconstruction. Specifically, I've spent much effort to solve the issues of **label noise** and **multi-view inconsistency** that impair the model performance by physics-informed and learning-based strategies.

2D Evaluation-oriented Enhancement
------
- **Underwater sequential images enhancement via diffusion and physics priors fusion**

  This work focouses on:
  1. leveraging diffusion prior to achieve SOTA performance from only synthetic data;
  2. full physics-based synthesis for improving visual clarity. 

![Framework of PF-UISE](/images/PFUISE-Framework.png)
![Visual Results](/images/time_consistency.jpg)

- **Fusing Transferred Priors and Physics-based Decomposition for Underwater Image Enhancement**

  This work focuses on:
  1. transfer-learning from multiple data/model priors to avoid noisy label issue;
  2. Physics-based task decomposition to provide theoretical soundness.
   
![Framework of P2-UIE](/images/P2UIE-Framework.png)
![Visual Results](/images/LabelBiasComp.png)

3D Reconstruction-oriented Enhancement
------

- **NVS-UIE: Diffusion UIE towards Novel View Synthesis via Physics-Aligned Frequency Fusion**

  This work focuses on:
  1. frequency-fusion strategy to preserve the texture details;
  2. physics-controlled sequential image synthesis to improve the multi-view consistency.
   
![Framework of NVS-UIE](/images/NVSUIE-Framework.png)
![Visual Results](/images/Final_Visualization.png)

- **RQUL-UIE: Revitalizing Quality-Unstable Labels for Underwater Image Enhancement via In-Dataset Self-Supervision**

  This work focuses on:
  1. label quality quantization to fully utilize the quality-unstable labels;
  2. a fourier-based texture refinement to for multi-view consistent texture preservation. 
  
![Framework of RQUL-UIE](/images/RQUL-Framework.png)
![Visual Results](/images/vis_comp_exp.png)
<p align="center">
  <video src="/images/Curasao_merged.mp4" controls autoplay muted loop playsinline width="80%">
    您的浏览器不支持播放该视频。
  </video>
</p>

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
2. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
3. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
4. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
5. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
6. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

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
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
