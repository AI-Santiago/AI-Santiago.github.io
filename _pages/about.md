---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD student in the Department of Computer Science and Engineering at the Chinese University of Hong Kong. Prior to that, I received my Bachelor of Engineering degree in Artificial Intelligence from Xi'an Jiaotong University.
I am particularly interested in knowledge representation and reasoning, recommender systems.


I'm still working on something that I can present, and for now, I may just share a quote that I really like.

"Why do we have to listen to our hearts?" the boy asked.

"Because, wherever your heart is, that is where you will find your treasure."

Any discussion, co-operation, mentoring and being mentored are very welcome, and I can be reached at liyifan@link.cuhk.edu.hk.

Thanks for reading!

---

## Publications

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---

## Teaching

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}

---

## CV

{% include base_path %}

### Education
* B.S. in GitHub, GitHub University, 2012
* M.S. in Jekyll, GitHub University, 2014
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)

### Work experience
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  
### Skills
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

### Publications
<ul>{% for post in site.publications %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
  
### Talks
<ul>{% for post in site.talks %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>
  
### Teaching
<ul>{% for post in site.teaching %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
  
### Service and leadership
* Currently signed in to 43 different slack teams

---

## Portfolio

{% include base_path %}

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

---

## Talks and Presentations

{% if site.talkmap_link == true %}
<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>
{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
