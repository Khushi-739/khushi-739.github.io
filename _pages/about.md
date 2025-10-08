---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a senior undergraduate pursuing a Bachelor of Engineering in Artificial Intelligence and Data Science at the University of Mumbai. I have also completed a Technical High School Diploma in Computer Engineering from K. J. Somaiya Polytechnic, Mumbai.

My research interests lie at the intersection of Machine Learning, Computer Vision, and Medical AI, with a growing focus on AI-driven automation and scientific computing. I have previously collaborated, advised by Prof. Min Xu at Carnegie Mellon University, in Xu Lab, working under the guidance of Xiangrui (Taylor) Zeng on segmentation map registration for MRI images. Additionally, I collaborated with Dr. Clément Coïc (Siemens Healthineers) on modeling robotic systems using Julia SciML.

My goal is to contribute to research that bridges AI theory and real-world impact through interdisciplinary collaboration. <span style="color:blue;">I am always open to research discussions and collaborative opportunities, feel free to reach out via email if our interests align.</span>

<span style="color:red;">I am on the job market this year and also considering direct PhD positions. I would be happy to discuss any opportunities that may be a good fit.</span>

News
------
**June 2025**: My 1st research paper is published in arXiv, “SLRNet: A Real-Time LSTM-Based Sign Language Recognition System” code and paper is available <span style="color:blue;"><a href="https://arxiv.org/abs/2506.11154" target="_blank">here</a></span>.

**March 2025**: Started a research collaboration with Dr. Clément Coïc on Julia SciML open-source contributions.

2025 Publications
------
![Editing a Markdown file for a talk](/images/methodology_flowchart.png)
<a href="https://arxiv.org/abs/2506.11154">SLRNet: A Real-Time LSTM-Based Sign Language Recognition System</a><br>
arXiv 2025<br>
Author: Sharvari Kamble\\
\\

A real-time webcam-based ASL recognition system using MediaPipe Holistic and LSTM networks achieves 86.7% validation accuracy for letters and functional words, demonstrating feasible, hardware-independent sign language recognition.


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
