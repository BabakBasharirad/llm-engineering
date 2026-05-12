---
layout: page
title: Materials
permalink: /materials/
---

## Refrences
<table>
{% for book in site.data.readings %}
  <tr>
    <td>{{ book.ref }}</td>
    <td><img src="{{ book.cover | relative_url }}" width="100"></td>
    <td>
      <strong>{{ book.title }}</strong><br>
      {{ book.authors }}<br>
      Available on {{ book.library }}.<br>
      {{ book.year }}. {{ book.publisher }}.<br>
    </td>
  </tr>
{% endfor %}
</table>

<br>

## Additional Course Materials

* If you are not familiar with Python programming, use any online tutorial to get a handle of it.
* [Material #1](http://www.example.com/): how a computer chess player thinks!
* [Material #2](http://www.example.com/): how a computer chess player thinks!
* [Material #3](http://www.example.com/): how a computer chess player thinks!
* [Material #4](http://www.example.com/): how a computer chess player thinks!
* [Material #5](http://www.example.com/): how a computer chess player thinks!











