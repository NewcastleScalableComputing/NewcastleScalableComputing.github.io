---
layout: default
title: "About"
---

<!-- You can edit this whole page, remove it, or use it as basis for any non-post pages you have. -->
<section class="content">

<!-- # {{ site.name }}

<ul class="listing">
<li>
<span>Fall 2018</span><a href="{{ site.url }}/upcoming.html">Upcoming Topics</a>
</li>
  {% assign upcoming = (site.posts | where: "category" , "upcoming") %}
  {% for post in upcoming reversed %}
    {% if forloop.first %}
    <li style="text-indent: 2em;">
	<span>{{ post.date | date: "%B %e, %Y" }}</span> Next topic: <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
	</li>
    {% endif %}
  {% endfor %}
<li>
<span>2015-2016</span><a href="{{ site.url }}/previous.html">Previous Topics</a>
</li>
</ul> -->


<section class="content">

Scalable Group Seminars
===============
This website documents the seminar series of the <a href="http://www.ncl.ac.uk/computing/research/groups/scalable/#about">Scalable Computing</a> research group at Newcastle University.

If you wish to participate, please contact <a href="mailto:matthew.forshaw@ncl.ac.uk">Matt Forshaw</a> or raise a Pull Request on Github <a href="https://github.com/NewcastleScalableComputing/NewcastleScalableComputing.github.io/pulls">here</a>.

<!-- ## Upcoming Seminars
<table>
  <thead>
    <tr>
      <th style="text-align: left">Date</th>
      <th style="text-align: left">Title</th>
      <th style="text-align: left">Speaker</th>
    </tr>
  </thead>
  <tbody>
  {% assign upcoming = (site.posts | where: "category" , "upcoming") %}
  {% if upcoming == null %}
    <p>test</p>

  {% endif %}
  {% for post in upcoming reversed %}
    <tr>
      <td style="text-align: left">{{ post.date | date: "%B %e, %Y" }}</td>
      <td style="text-align: left"><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></td>
      <td style="text-align: left">TBC</td>
    </tr>
  {% endfor %}
  </tbody>
</table> -->



## Upcomiong Seminars
<table>
  <thead>
    <tr>
      <th style="text-align: left">Date</th>
      <th style="text-align: left">Title</th>
      <th style="text-align: left">Speaker</th>
    </tr>
  </thead>
  <tbody>
  {% assign upcoming = (site.posts | where: "category" , "upcoming") %}
  {% for post in upcoming %}
    <tr>
      <td style="text-align: left">{{ post.date | date: "%B %e, %Y" }}</td>
      <td style="text-align: left"><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></td>
      <td style="text-align: left">{{ post.speaker }}</td>
    </tr>
  {% endfor %}
  </tbody>
</table>


## Previous Seminars
<table>
  <thead>
    <tr>
      <th style="text-align: left">Date</th>
      <th style="text-align: left">Title</th>
      <th style="text-align: left">Speaker</th>
    </tr>
  </thead>
  <tbody>
  {% assign past = (site.posts | where: "category" , "past") %}
  {% for post in past %}
    <tr>
      <td style="text-align: left">{{ post.date | date: "%B %e, %Y" }}</td>
      <td style="text-align: left"><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></td>
      <td style="text-align: left">{{ post.speaker }}</td>
    </tr>
  {% endfor %}
  </tbody>
</table>

</section>


</section>
