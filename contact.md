---
layout: page
title: Contact
subtitle: Classes, collaborations, or just to say hello
permalink: /contact/
---

I'd love to hear from you — whether you want to join a class, collaborate on a piece,
or ask a question.

{% if site.email_public %}
**Email:** [{{ site.email_public }}](mailto:{{ site.email_public }})
{% else %}
**Email:** *add a contact email in `_config.yml`*
{% endif %}

{% if site.instagram %}
**Instagram:** [@{{ site.instagram }}](https://instagram.com/{{ site.instagram }})
{% endif %}

{% if site.booking_url %}
**Book a class:** [{{ site.booking_url }}]({{ site.booking_url }})
{% endif %}

---

*Prefer a form? A simple contact form can be added later (Formspree, Google Forms, or
similar) — just ask.*
