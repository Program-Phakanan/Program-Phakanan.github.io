---
layout: default
title: Certificates
permalink: /certificates/
---

# Certificates

## Professional Certifications

{% for cert in site.certificate %}
### {{ cert.name }}

**Issuer:** {{ cert.issuer }}

[📜 View Certificate (PDF)]({{ site.baseurl }}/{{ cert.file }}){:target="_blank"}

---
{% endfor %}

[← Back to Portfolio]({{ site.baseurl }}/)
