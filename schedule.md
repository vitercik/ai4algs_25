---
layout: page
title: Schedule
description: Listing of course modules and topics.
---

# Schedule

All discussion classes center around a required reading. The schedule also includes relevant papers not cited by those papers (since the Archeologist's job is to uncover relevant papers cited by the required reading, and we don't want to make their job too easy!) as well as some relevant papers by myself that I'm always happy to discuss during office hours or after class.

{% for module in site.modules %}
{{ module }}
{% endfor %}
