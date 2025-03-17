---
layout: page
permalink: /
title: about
nav: About
description: <a href="https://elviswxy.github.io/" class="page-description" target="_blank">Ph.D. Candidate</a> , <a href="https://www.scu.edu/engineering/" class="page-description" target="_blank">Computer Science</a> , <a href="https://www.scu.edu" class="page-description" target="_blank">Santa Clara Universtity</a> <p></p> <p>elviswu0306 [at] gmail [dot] com</p>
---

<div class="col p-0 pt-4 pb-4">
  <h1 class="pb-3 title text-left font-weight-bold">Xuyang Wu</h1>
  <h6 class="m-0 mb-2" style="font-size: 0.83em;">{{ page.description }}</h6>
  <!-- {% if page.address %}
      <h6 class="m-0 mb-2" style="font-size: 0.83em;">{{ page.address }}</h6>
  {% endif %} -->
</div>

<!-- Introduction -->

<div style="display: flex; flex-wrap: wrap;">
    <div class="text-justify p-0">
        <div class="col-xs-12 col-sm-6 p-0 pt-2 pb-sm-2 pb-4 pl-sm-4 text-center" style="float: right;">
          <img class="profile-img img-responsive" src="{{ 'prof_pic.jpg' | prepend: '/assets/img/' | prepend: site.baseurl | prepend: site.url }}">
        </div>

        <p> I am a computer scientist and researcher specializing in deep learning, information retrieval, search and ranking algorithms, recommendation systems, and responsible AI. Currently, I am pursuing a Ph.D. in Computer Science at <a href="https://www.scu.edu" target="_blank">Santa Clara University</a>, where my research focuses on enhancing search engine ranking through multi-task learning and ensuring fairness in AI systems. I also hold an M.Sc. in Web Science and Big Data Analytics from <a href="https://www.ucl.ac.uk" target="_blank">University College London</a> and a B.Sc. in Computer Science from <a href="https://www.coventry.ac.uk" target="_blank">Coventry University</a>, providing me with a strong international academic foundation. </p> 
        
        <p> My research aims to improve the accuracy, efficiency, and fairness of search and ranking systems while addressing bias in large language models (LLMs). I have developed multi-task learning frameworks that enhance product ranking, significantly improving click-through rate predictions, with my work published in the ACM Web Conference (WWW 2022) and ACM Transactions on Information Systems (TOIS). </p> 
        
        <p> I am also deeply committed to AI fairness and responsible AI, ensuring that large language models—the backbone of modern chatbots and virtual assistants—operate equitably across diverse user groups. My research on LLM fairness, including evaluating bias in Retrieval-Augmented Generation (RAG) and LLM-based ranking models, has been featured in NAACL 2024 and COLING 2025. </p> 
        
        <p> Beyond academia, I have gained industry experience as a Data Science Intern at <a href="https://tech.walmart.com/content/walmart-global-tech/en_us.html" target="_blank">Walmart Global Tech</a>, where I optimized search and ranking models, and as a Visiting Researcher at <a href="https://www.docomoinnovations.com" target="_blank">NTT DOCOMO Innovations</a>, developing deep learning applications for real-world challenges. Before embarking on my Ph.D., I co-founded and led a technology startup in Beijing, where I designed and deployed large-scale news recommendation and online advertising systems, serving millions of users. This entrepreneurial experience provided me with deep insights into real-world AI applications and further fueled my passion for advancing responsible AI research. </p> 
        
        <p> Feel free to connect with me on <a href="https://www.linkedin.com/in/xuyang-wu/" target="_blank">LinkedIn</a> to discuss research, AI fairness, and more! </p>

    </div>
</div>


<!-- News -->
<div class="news mt-3 p-0">
  <h3 class="title mb-4 p-0">News</h3>
  {% assign news = site.news | reverse %}
  {% for item in news limit: site.news_limit %}
    <div class="row p-0">
      <div class="col-sm-2 p-0">
        <span class="badge danger-color-dark darken-1 font-weight-bold text-uppercase align-middle date ml-3">
          {{ item.date | date: "%b %-d, %Y" }}
        </span>
      </div>
      <div class="col-sm-10 mt-2 mt-sm-0 ml-3 ml-md-0 p-0 font-weight-light text">
        <p>{{ item.content | remove: '<p>' | remove: '</p>' | emojify }}</p>
      </div>
    </div>
  {% endfor %}
</div>

<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=gLhjh2d4hwhINEV6kPNJecQUgV-F-a1h0DB02LxJ_8w&cl=ffffff&w=a"></script>
