---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computer Science and Engineering, Nanyang Technological University, Aug. 2023 - Present
* M.S. in Computational Mathematics, Beijing Normal University, Sep. 2021 - Jun. 2023 (Early Graduation with Honor)
* B.S. in Mathematics and Applied Mathematics, Beijing Normal University, Sep. 2016 - Jul.2020
  * Summer Scholar in Math and Economics, Duke University, Jul. 2018 – Aug. 2018
  * Exchange Student in Mathematics, Rutgers University, Jan. 2019 – May. 2019



Work experience
======
* Jun. 2019 – Sep. 2019: Data Analyst Intern
  * LiCaiMoFang, Beijing KouDaiCaiFu In-Tech. Co. Ltd.
  * Duties includes: 
    + Analyzed time series of user purchase behavior and visualization;
    + Predicted price index trend in stock market using multi-dimensional macro-economic data under the framework of ‘xgboost’ (a supervised learning algorithm);
    + Implemented macro-economic index model to compute risk-premium return;
    + Implemented multi-factor model using ‘Fama-Macbeth Regression’ to compute risk-premium return;
  * Supervisor: Yongan Ma

* Aug. 2020 – Jan. 2021: Research Assistant
  * ISCAS – Institute of Software Chinese Academy of Sciences
  * Duties included: 
    + Deployed state-of-art fuzzing tools like Vuzzer, Memlock, AFL and analyzed their performance;
    + Run large-scale fuzzing jobs on some open-source softwares like base64, uniq, asn1c, etc and submit possible vulnerability report to NVD;
    + Designed and implemented large-scale knowledge graph model Vulgraph, using state-of-art graph database Neo4j and logistic regression model to make prediction;
    + Designed and implemented an automated fuzzing platform Autofuzz, including front-end page design, data-flow model and Restful API design;
    + Acquired Two Software Patents for Autofuzz project;
  * Supervisor: [Jingzheng Wu](https://people.ucas.ac.cn/~jingzheng)

* Feb. 2021 – Sep. 2021: Software Development Engineer
  * Baidu Inc.
  * Duties included: 
    + Large-scale (a few Terabytes) log pipeline modeling using Hadoop;
    + Backend development support for vertical search project Aladdin;
    + Building coupon recommendation system for impending service center in Baidu App;
  * Supervisor: Aowei Li
  


Skills
======
+ Environments/Tools: Linux, Git, Docker, Vim, SSH
+ Programming languages: C/C++, Python, SQL, bash, Java, tcl, PHP
+ Databases: MySQL, PostgreSQL, sqlite3, Neo4j, MongoDB, Redis
+ Frontend: HTML/CSS/Javascript, Node.js, React
+ Languages: Mandarin (native), English (TOFEL 108, GRE 325 + 4.0), Spanish
+ Hobbies: badminton, basketball, swimming

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Reviewers for UAI 2024, UAI 2025, UAI 2026, AISTATS 2026

