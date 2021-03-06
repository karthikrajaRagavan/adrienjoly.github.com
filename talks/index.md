---
title: Talks
description: A list of talks I've given to meetups and other events.
---

## Ideas for future talks

Your feedback and suggestions are welcome!

- How to migrate a Node.js application from Heroku to Google Cloud Platform / Kubernetes
- How to have all side-projects from Github automatically attached to your personal domain name

> 📌 Also check out my [teaching](/teaching) interventions.

## Talks

{% for talk in site.data.talks %}
- [{{ talk.title }}]({{ talk.url }})<br/>
  <small style="color:gray;">{{ talk.date | date: "%b %-d, %Y" }}, {{ talk.event }}</small>
{% endfor %}

📌 Previous talks and slides: [Slideshare](https://fr.slideshare.net/adrienjoly/presentations)

<!-- inspiration: https://raw.githubusercontent.com/romsson/romain.vuillemot.net/master/talks.md -->

> Last update was August 18th, 2018. [History](https://github.com/adrienjoly/adrienjoly.github.com/commits/master/talks)
>
> Follow [@adrienjoly](https://twitter.com/adrienjoly) on Twitter.
