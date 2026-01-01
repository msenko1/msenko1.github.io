---
layout: default
title: Home
description: "Personal website of Michael Senko, Linguistics PhD student at Stanford University."
author: "Michael Senko"
---

---

# Hey! 👋

I'm Michael, a 1st year Linguistics PhD student at [Stanford](https://linguistics.stanford.edu/ "Stanford Linguistics").

I'm interested in:

- ㊓ Sociolinguistics (performance, variation, metalinguistic awareness)
- 🧠 Cognition (control, attention, exemplar theory)
- 🎙️ Phonetics (vowel quality, speech production, chain shifts)
- 👾 Computational methods (NLP, LLMs, corpus analysis)

You can contact me at **msenko** at **stanford** dot **edu**.

{% comment %}

---

### News

<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%b %d, %Y" }}
    </li>
  {% endfor %}
</ul>

{% endcomment %}
