---
title: "Schedule"
permalink: /schedule/
layout: single
sidebar:
  title: ""
  nav: current
---

<!-- https://forum.squarespace.com/topic/29657-how-to-embed-a-google-calendar-in-a-responsive-way/ -->
<style>
  @media (max-width: 700px) {
    .big-container {
        display: none;
    }
  }
  @media (min-width: 700px) {
    .small-container {
        display: none;
    }
  }
  /* Responsive iFrame */
  .responsive-iframe-container {
    position: relative;
    padding-bottom: 56.25%;
    padding-top: 30px;
    height: 0;
    overflow: hidden;
  }
  .responsive-iframe-container iframe,   
  .vresponsive-iframe-container object,  
  .vresponsive-iframe-container embed {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
  }
</style>

<div class="responsive-iframe-container big-container">
  <iframe src="https://calendar.google.com/calendar/embed?src=7skh1el46mbcr5lh6hacqvn9j0%40group.calendar.google.com&ctz=America%2FNew_York" style="border: 0" width="100%" height="650" frameborder="0" scrolling="no"></iframe>
</div>

<div class="responsive-iframe-container small-container">
  <iframe src="https://calendar.google.com/calendar/embed?height=600&amp;wkst=1&amp;bgcolor=%23ffffff&amp;ctz=America%2FNew_York&amp;src=N3NraDFlbDQ2bWJjcjVsaDZoYWNxdm45ajBAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ&amp;color=%23616161&amp;mode=AGENDA" style="border:solid 1px #777" width="100%" height="600" frameborder="0" scrolling="no"></iframe>
</div>
