---
layout: default
permalink: /spec-calendars.html
title: JMAP Calendars Specification
---

# JMAP Calendars

This document specifies a data model for synchronising calendar data with a server using [JMAP](spec-core.html).

{% capture x %}{% include spec/calendars/intro.mdown %}{% endcapture %}
{{ x | replace: "# ", "## " | markdownify }}
{% capture x %}{% include spec/calendars/calendar.mdown %}{% endcapture %}
{{ x | replace: "# ", "## " | markdownify }}
{% capture x %}{% include spec/calendars/calendarevent.mdown %}{% endcapture %}
{{ x | replace: "# ", "## " | markdownify }}
