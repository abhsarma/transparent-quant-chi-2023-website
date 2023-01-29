---
layout: workshop      # DON'T CHANGE THIS.
# More detailed instructions (including how to fill these variables for an
# online workshop) are available at
# https://carpentries.github.io/workshop-template/customization/index.html
---

<h2 class='section-info' id="general">General Information</h2>

{% if site.topic == "open-data" %}
{% include intro/topic-intros/open-data.md %}
{% elsif site.topic == "open-code" %}
{% include intro/topic-intros/open-code.md %}
{% elsif site.topic == "open-access" %}
{% include intro/topic-intros/open-access.md %}
{% elsif site.topic == "preregistration" %} 
{% include intro/topic-intros/preregistration.md %} <!-- this file contains content under General Information -->
{% elsif site.topic == "preprints" %}
{% include intro/topic-intros/preprints.md %}
{% else %}
{% include intro/topic-intros/unknown-topic.md %}
{% endif %}



<p id="when">
  <strong>Online sessions dates:</strong>
  Wednesday, April 12
  Friday, April 14
  Monday, April 17
</p>
<p>
  <strong>Online sessions time:</strong>
    9:00–10:15 (Pacific) = 11:00–12:15 (Central) = 12:00–13:15 (Eastern) = 18:00–19:15 (Europe)
</p>
<strong>On-site/hybrid sessions dates and time:</strong> Monday, April 24 late-morning session (exact time and location will be announced in the <a href="https://chi2023.acm.org/program/">CHI program</a>)

<!-- <p>
  <strong>Calendar entries:</strong>
  <ul>
    <li>
      <a href="https://drive.google.com/file/d/19fGGn9XhkRVOPYCzuZoXvqY-xiRukE3a/view?usp=sharing" target="_blank">iCal (all)</a>
    </li>
    <li>
      Google Calendar or Outlook: 
      <a href="https://www.worldtimebuddy.com/?qm=1&lid=2657896,5391959,5128581,4335045&h=2657896&date=2022-4-18&sln=18-19.5&hf=1" target="_blank">Day 1</a>,
      <a href="https://www.worldtimebuddy.com/?qm=1&lid=2657896,5391959,5128581,4335045&h=2657896&date=2022-4-20&sln=18-19.5&hf=1" target="_blank">Day 2</a>,
      <a href="https://www.worldtimebuddy.com/?qm=1&lid=2657896,5391959,5128581,4335045&h=2657896&date=2022-4-22&sln=18-19.5&hf=1" target="_blank">Day 3</a>, and
      <a href="https://www.worldtimebuddy.com/?qm=1&lid=2657896,5391959,5128581,4335045&h=2657896&date=2022-4-29&sln=18-19.5&hf=1" target="_blank">Day 4</a>. <br/>
      <small> (Note: World Time Buddy supports 30-minute chunks, so the calendar entries download from there will be 15 minutes longer than the actual time.)</small>
    </li>
  </ul>
</p> -->




<hr/>

{% comment %}
SCHEDULE

Show the workshop's schedule.

The schedule is automatically generated from the lessons in `./_episodes` and `./episodes_rmd`, which are in turn produced by the generator tool.
{% endcomment %}

<h2 class='section-info' id="schedule">Schedule</h2> 

{% include schedule.html %}

<!-- 📅 Calendar entries for these dates are available in the <strong>General Information</strong> section above. -->
<hr/>

<h2 class='section-info' id="registration">Registration</h2> 

{% include registration.md %}
<hr/>


<h2 class='section-info' id="instructors">About instructors</h2> 

[__Chat Wacharamanotham__](https://chatchavan.github.io) is a lecturer at Swansea University and a mandated instructor at the University of Zurich. The focus of his work is on understanding and developing tools for planning, reporting, reading, and sharing quantitative research. He is also a co-organizer of the Transparent Statistics in HumanComputer Interaction group and the Dagstuhl Seminar on Transparent Quantitative Research as a User Interface Problem. He has seven years of experience teaching a research method course for graduate students. 

[__Fumeng Yang__](http://www.fmyang.com/) is a postdoctoral fellow at Northwestern University. Her recent research focuses on uncertainty visualizations for the general public and user modeling through statistical and machine learning models. She served as a Student Volunteers chair for IEEE VIS and co-instructed the precedent series of the proposed course.

[__Xiaoying Pu__](xiaoyingpu.github.io) is a postdoctoral researcher at the University of California, Merced. In her work, she takes a human-centered approach to help data workers communicate uncertainty and data analyses. She has organized a CHI 2021 SIG on visualization grammars and studied the open science practice of preregistration.

[__Abhraneel Sarma__](http://abhsarma.github.io/) is a Ph.D. candidate at Northwestern University. His research interests include studying how people make decisions using visualizations, and how visualizations can be used for improving statistical analysis or reporting statistical results. In addition, he has studied how users implement certain aspects of Bayesian models and has developed tools for conducting multiverse analysis which is an approach for more transparent statistical research.


<h2 class='section-info' id="faq">Frequently Asked Questions</h2> 

### Is there any scholarships?
[__Gary Marsden Travel Awards__](https://sigchi.submittable.com/submit/165150/gary-marsden-travel-awards) (Deadline February 9th, 11:59pm AoE). This fund prioritizes first-time attendees and presenters. You do not need to have a paper accepted to CHI to apply for this fund.

### Can I participate this course if I will only attend CHI online?
Yes. The first three sessions are online, and the last sessions is hybrid. See the information on the page of the last session above for the hybrid arrangement.



<p id="contact">
  <strong>Contact:</strong>
  <a class='contact-info' href='mailto:chat@acm.org?subject=[CHI Course]'>chat@acm.org</a>
</p>
