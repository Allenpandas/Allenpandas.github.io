---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}



<span class='anchor' id='About-Me'></span>

Hi! I am Aaron Wu (吴亚伦 in Chinese). I am a third-year Ph.D. student in the School of Cyberspace Science and Techonology  at Beijing Jiaotong University ([BJTU](https://bjtu.edu.cn/)), and affiliated with the Laboratory of Thorough Evaluation of Threats in the Artificial Intelligence ([THETA Lab](http://jxd308.cn/)) and the Beijing Key Laboratory of Security and Privacy in Intelligent Transportation. I supervised by Prof. [Zhen Han](http://faculty.bjtu.edu.cn/5608/), [Wenjia Niu](http://faculty.bjtu.edu.cn/9120/) and Assistant Prof. [Endong Tong](http://faculty.bjtu.edu.cn/9306/). Prior to my Ph.D. career, I received the M.S. degree at School of Computer Science and Technology from BJTU. 📮 I'm open to any kind of collaboration. If you are interested to chat with me, please feel free to contact me through <a href="mailto:wuyalun1@bjtu.edu.cn" target="_blank">email</a>.



<!-- 

My research interests focuses on the intersection of artificial intelligence and security. I have authored or co-authored about 20 academic papers in international conferences and journals, including TGCN, TST, ICICS, HPCC, ADMA, KSEM, etc. I'm open to any kind of collaboration. Please feel free to contact me through email.

-->



{% include_relative includes/Research.md %}



{% include_relative includes/News.md %}



{% include_relative includes/Publications.md %}



{% include_relative includes/Honors.md %}



{% include_relative includes/Educations.md %}



{% include_relative includes/Projects.md %}
