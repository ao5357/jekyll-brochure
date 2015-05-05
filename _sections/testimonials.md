---
title: Testimonials
classes: "divided"
---

{% for testimonial in site.testimonials %}
{% include testimonial_brief.html testimonial=testimonial %}
{% endfor %}
