---
title: Labs & Lectures
permalink: list/labs.html
---
**Fall 2021 Python and Raspberry Pi Labs**

{% for lab in site.labs %}
- [{{ lab.title }}]({{ site.baseurl }}{{ lab.url }})
{% endfor %}

**Archived Fall 2020 App building Labs**

{% for lab in site.fall2020_labs %}
- [{{ lab.title }}]({{ site.baseurl }}{{ lab.url }})
{% endfor %}
