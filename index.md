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

<!-- {% comment %}
LOCATION

This block displays the address and links to maps showing directions
if the latitude and longitude of the workshop have been set.  You
can use https://itouchmap.com/latlong.html to find the lat/long of an
address.
{% endcomment %}

{% comment %}
{% assign begin_address = site.address | slice: 0, 4 | downcase  %}
{% if site.address == "online" %}
{% assign online = "true_private" %}
{% elsif begin_address contains "http" %}
{% assign online = "true_public" %}
{% else %}
{% assign online = "false" %}
{% endif %}
{% if site.latitude and site.longitude and online == "false" %}
<p id="where">
  <strong>Where:</strong>
  {{site.address}}.
  Get directions with
  <a href="//www.openstreetmap.org/?mlat={{site.latitude}}&mlon={{site.longitude}}&zoom=16">OpenStreetMap</a>
  or
  <a href="//maps.google.com/maps?q={{site.latitude}},{{site.longitude}}">Google Maps</a>.
</p>
{% elsif online == "true_public" %}
<p id="where">
  <strong>Where:</strong>
  online at <a href="{{site.address}}">{{site.address}}</a>.
  If you need a password or other information to access the training,
  the instructor will pass it on to you before the workshop.
</p>
{% elsif online == "true_private" %}
<p id="where">
  <strong>Where:</strong> This training will take place online.
  The instructors will provide you with the information you will need to connect to this meeting.
</p>
{% endif %}
{% endcomment %}

{% comment %}
DATE

This block displays the date and links to Google Calendar.
{% endcomment %}

{% comment %}
{% if site.start_date %}
<p id="when">
  <strong>Dates:</strong>
  18, 20, 22, and 29 April 2022
</p>
<p>
  <strong>Time:</strong>
    9:00–10:15 (Pacific) = 11:00–12:15 (Central) = 12:00–13:15 (Eastern) = 18:00–19:15 (Europe)
</p>
<p>
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
</p>
{% endif %}
{% endcomment %} -->

<!-- {% comment %}
CONTACT EMAIL ADDRESS

Display the contact email address set in the configuration file.
{% endcomment %} -->

<p id="contact">
  <strong>Contact:</strong>
  <a class='contact-info' href='mailto:chat@ifi.uzh.ch?subject=[CHI Course]'>chat@ifi.uzh.ch</a>
</p>

  <!-- <hr/> -->

<!-- {% comment %}
SCHEDULE

Show the workshop's schedule.

The schedule is automatically generated from the lessons in `./_episodes` and `./episodes_rmd`, which are in turn produced by the generator tool.
{% endcomment %}

{% comment %}
<h2 class='section-info' id="schedule">Schedule</h2> 

{% include schedule.html %}

📅 Calendar entries for these dates are available in the <strong>General Information</strong> section above.
<hr/>

<h2 class='section-info' id="registration">Registration</h2> 

{% include registration.md %}
<hr/>
{% endcomment %} -->



