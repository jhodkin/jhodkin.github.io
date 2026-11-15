\---

layout: page

title: Publications

permalink: /publications/

\---



{% for pub in site.data.publications %}

\### {{ pub.title }}

{{ pub.authors }}. \*{{ pub.venue }}\*, {{ pub.year }}.

{% if pub.url %}\[Link]({{ pub.url }}){% endif %}



{% endfor %}

