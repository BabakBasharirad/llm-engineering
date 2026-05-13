---
layout: page
title: Materials
permalink: /materials/
---

## Main References
<table>
{% for book in site.data.main_references %}
  <tr>
    <td>{{ book.ref }}<br><br><br><br></td>
    <td><img src="{{ book.cover | relative_url }}" width="100"></td>
    <td>
      <strong>{{ book.title }}</strong><br>
      {{ book.authors }}<br>
      Available on <a href="{{ book.url }}" target="_blank">{{ book.library }}</a>.<br>
      {{ book.year }}. {{ book.publisher }}.<br>
    </td>
  </tr>
{% endfor %}
</table>
<br>

## Additional References
<table>
{% for book in site.data.other_references %}
  <tr>
    <td>{{ book.ref }}<br><br><br><br></td>
    <td><img src="{{ book.cover | relative_url }}" width="100"></td>
    <td>
      <strong>{{ book.title }}</strong><br>
      {{ book.authors }}<br>
      Available on <a href="{{ book.url }}" target="_blank">{{ book.library }}</a>.<br>
      {{ book.year }}. {{ book.publisher }}.<br>
    </td>
  </tr>
{% endfor %}
</table>
<br>
