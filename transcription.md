---
layout: layout
title: Transcription
subtitle: Live transcription of our talks can bring some of SRCCON:WORK to you.
section: remote
sub-section: interior
background: remote
permalink: /transcription/index.html
---

SRCCON:WORK is an intentionally small event, but we also care about getting the ideas and conversations that take place there into the wider world. The most important way this happens is when attendees return home and put their new skills and approaches to work, but we also document extensively.

## Transcription

Live transcriptions of all our talks at SRCCON:WORK are below. We also transcribed several sessions, and may publish those alongside writeups on [Source](https://source.opennews.org) in the coming weeks.

<div>
    <h3>Thursday</h3>
    <table>{% assign thursday = site.data.schedule | where:"day","Thursday" %}
{% for session in thursday %}
        {% if session.transcription != "" %}<tr><td>{{ session.time }}</td><td><a href="https://aloft.nu/srccon-work/srcconwork-2017-{{ session.id }}">{{ session.title }}</a></td></tr>{% endif %}
{% endfor %}
    </table>
</div>

<div>
    <h3>Friday</h3>
    <table>{% assign friday = site.data.schedule | where:"day","Friday" %}
{% for session in friday %}
        {% if session.transcription != "" %}<tr><td>{{ session.time }}</td><td><a href="https://aloft.nu/srccon-work/srcconwork-2017-{{ session.id }}">{{ session.title }}</a></td></tr>{% endif %}
{% endfor %}
    </table>
</div>

## Write-Ups

In the leadup to SRCCON:WORK, we’re featuring [Q&As with our conference speakers](https://source.opennews.org/articles/tags/srcconwork-q-a/). We'll be publishing session writeups, resource lists, and more [on Source](https://source.opennews.org) over the next few months—[hop on the Source newsletter](https://opennews.us5.list-manage.com/subscribe?u=71c95e9a43708843d2fdc1f09&id=996e9290cc) if you'd like a digest of those links, plus highlights from the community, as they come out.
