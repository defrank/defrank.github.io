---
title: About Me
layout: default
---

## Formalities

<dl>
    <dt>Occupation</dt>
    <dd>Software Engineer</dd>

    <dt>Location</dt>
    <dd>Chatsworth, CA (Greater Los Angeles)</dd>

    <dt>Education</dt>
    <dd>UCSC: Computer Science, Bachelor of Science</dd>
    <dd>Venice High School</dd>
</dl>

## Hobbies

* Learning
* Reading and listening to audiobooks
* Snowboarding
* Powerlifting (PRs in lbs: deadlift=420, squat=360, bench=325,
  press=205)
* Dog training.

## Favorites

<dl>
    <dt>Color</dt>
    <dd>Green (even though I'm blue-green colorblind...)</dd>

    <dt>Book (leisure)</dt>
    <dd>Harry Potter (my SO and I continue to re-listen to the Stephen Fry audiobooks)</dd>

    <dt>Book (educational)</dt>
    <dd>Pragmatic Programmer (I have a need to keep improving myself)</dd>

    <dt>Manga</dt>
    <dd>Dragon Ball (I'm obsessed)</dd>

    <dt>Lift</dt>
    <dd>Sumo deadlift</dd>
</dl>

----

## Pets

{% assign image = site.static_files | where: "basename", "kira-rolling-eyes-dee-and-dino" | first %}
{% assign timestamp = image.modified_time | date: "%s" %}

I have two crazy, smart, and silly blue heelers, Kira and Dino.
![{{ image.basename | split: "-" | join: " " }}]({{ image.path }}?v={{ timestamp }})
