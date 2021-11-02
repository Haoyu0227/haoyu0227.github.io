---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I’m Haoyu Wang, a graduate student in CS at UIUC. I have a handsome boyfriend Daniel =)


I have a strong background in full stack development. For backend techniques, I’m skilled in Express.js, Flask, ASP.NET Core, Hadoop and so on. For frontend, I’m adept at React.js, Vue.js, CSS. I have experience in databases such as MongoDB, PostgreSQL and Elasticsearch. I conducted extensive internships and projects. I was a software engineer intern at NetEase in 2020 and Xiaomi in 2021. I’m now actively seeking Summer 2022 SWE Intern opportunities.

Education
------
<!-- ### Education -->
  * **University of Illinois at Urbana-Champaign**
    * Master of Computer Science, Aug 2021 - Dec 2022
    * GPA: 4.0/4.0
  * **University of Illinois at Urbana-Champaign**
    * Bachelor of Science in Statistics & Computer Science, Aug 2019 - May 2021
    * GPA: 3.94/4.0
    * graduated with Highest Distinction
    * Key Courses: Algorithms, Web Programming, Database Systems, Communication Networks, Applied Parallel Programming, System Programming, Programming Studio, CS Team Project, Programming Languages & Compilers, Artificial Intelligence, Deep Learning, Numerical Methods

Experience
------
  * **06/2020 - 08/2020, [NetEase, Inc.]**
    * Designed querying system for user records of NetEase CC Live Broadcast, currently used by 200+ operations managers
    * Used Hive to query data stored in HDFS to realize searches among billions of records older than a week
    * Queued Hadoop search tasks with Redis Queue and visualized each task’s position in queue
    * Created function using Elasticsearch for searching user records among tens of millions of records within one week, time of searching reduced from half hour to seconds
    * Developed RESTful APIs and responsive interface of querying system with Python, Flask, Vue.js, AJAX, CSS
  * **06/2021 - 08/2021, [Xiaomi Corporation]**
    * Built MIUI (Android Open Source Project of Xiaomi phone, over 100 million users) with Ninja; extracted and indexed compilations with Kythe tools in shell scripts
    * Applied Java API, processes and mutex to write over 30 TB indexer’s output to HDFS
    * Visualized cross-references of MIUI with Kythe tools on web UI, assisting 3000+ developers of Xiaomi mobile phone
    department in navigation of code
  * **08/2020 - 12/2020, [ClassTranscribe -- open-source video lecture platform of UIUC](https://classtranscribe.illinois.edu/)**
    * Implemented Google-like search engine based on Elasticsearch for ClassTranscribe, benefitting 1000+ UIUC students
    * Created indexes by importing data from PostgreSQL to Elasticsearch using Logstash and visualized data with Kibana
    * Developed search engine feature supporting incremental, fuzzy and full-text search for captions within course videos
    using NEST with ASP.NET Core


Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
