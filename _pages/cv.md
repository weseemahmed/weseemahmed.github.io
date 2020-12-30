---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
{% capture written_label %}'None'{% endcapture %}

<u><a style="line-height: 1.5;" href="http://weseemahmed.github.io/files/Weseem-Ahmed-Resume.pdf"><span style="color: #333333;"><span>Also available in PDF format.</span></span></a></u>

<h1 class="western" align="center"><b>Weseem H. Ahmed</b></h1>
<p style="line-height: 1.5;" align="center"><span><b>Curriculum Vitae</b> </span></p>

<h2>Employment</h2>
<ul style="line-height: 1.5; margin: 10px 0;">
  <li><span><b>Research Associate</b>, Canadian Institute for Climate Choices (Sept 2019 to present)</span></li>
  <li><span><b>Ad-hoc Consultant</b> (May 2019 to June 2020)</span></li>
  <li><span><b>Policy Analyst and Clusters Specialist</b>, Institute for Competitiveness and Prosperity (Mar 2018 to May 2019)</span></li>
</ul>

<h2>Education</h2>
* <b>M.A. Economics</b>, Toulouse School of Economics (2014-2016)
  Masters Thesis: <i>Estimating Effects of Democratic Institutions on Climate Change with a Logistic Regression</i>
 
* <b>B.A. Economics</b>, Western University (2010-2014)

<h2>Skills:</h2>
* Graduate-level statistics
* Machine Learning
* Python
* R programming

<a name="publications"><h2 id="publications-">Publications:</h2></a>
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<h2>Talks and Presentations</h2>
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
