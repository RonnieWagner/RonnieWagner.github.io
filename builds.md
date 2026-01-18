---
layout: default
title: Builds
permalink: /builds.html
---

## Current & Past Builds

{% for build in site.builds %}
### {{ build.title }}

- **Price:** {{ build.price }}
- **Status:** {{ build.status }}

[View build details →]({{ build.url }})

---
{% endfor %}

