---
layout: workshop      # DON'T CHANGE THIS.
# More detailed instructions (including how to fill these variables for an
# online workshop) are available at
# https://carpentries.github.io/workshop-template/customization/index.html
---


{% comment %}
Each of the sections below can be found in an individual markdown file.
This makes it easier for people to edit the contents in the UKRN Workshop Builder.
{% endcomment %}

{% comment %}
HEADER

Edit the values in the block above to be appropriate for your workshop.
If the value is not 'true', 'false', 'null', or a number, please use
double quotation marks around the value, unless specified otherwise.
And run 'make workshop-check' *before* committing to make sure that changes are good.
{% endcomment %}

{% if site.eventbrite %}
**Some adblockers block the registration window. If you do not see the
  registration box below, please check your adblocker settings.**

<iframe
  src="https://www.eventbrite.com/tickets-external?eid={{site.eventbrite}}&ref=etckt"
  frameborder="0"
  width="100%"
  height="280px"
  scrolling="auto">
</iframe>
{% endif %}


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



<p id="contact">
  <strong>Contact:</strong>
  <a class='contact-info' href='mailto:chat@acm.org?subject=[CHI Course]'>chat@acm.org</a>
</p>

  <!-- <hr/> -->

{% comment %}
SCHEDULE

Show the workshop's schedule.

The schedule is automatically generated from the lessons in `./_episodes` and `./episodes_rmd`, which are in turn produced by the generator tool.
{% endcomment %}

{% comment %}
<h2 class='section-info' id="schedule">Schedule</h2> 

{% include schedule.html %}

<!-- 📅 Calendar entries for these dates are available in the <strong>General Information</strong> section above. -->
<hr/>

<h2 class='section-info' id="registration">Registration</h2> 

{% include registration.md %}
<hr/>
{% endcomment %}



<h2 class='section-info' id="faq">Frequently Asked Questions</h2> 

<h3>Is there any scholarships?</h3>
<a href="https://sigchi.submittable.com/submit/165150/gary-marsden-travel-awards">Gary Marsden Travel Awards</a> (Deadline February 9th, 11:59pm AoE). This fund prioritizes first-time attendees and presenters. You do not need to have a paper accepted to CHI to apply for this fund.

<h3>Can I participate this course if I will only attend CHI online?</h3>
Yes. The first three sessions are online, and the last sessions is hybrid. See the information on the page of the last session above for the hybrid arrangement.




