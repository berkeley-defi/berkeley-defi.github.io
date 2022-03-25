---
layout: blank
title: "Fireside Chat - Decentralized Finance"
permalink: /f21_fireside
---

<table style="table-layout: fixed; font-size: 88%;">
  <thead>
      <th style="width: 20%;">Guest Speaker</th>
      <th style="width: 80%;">Topic </th>
  </thead>
  <tbody>
    {% for row in site.data.f21fireside %}
    <tr>
      <td>
        {% if row.speaker %}
          {{row.speaker}}
        {% else %}
          TBD
        {% endif %}
      </td>
      <td>
        <p>
        {{row.description}}
        </p>
        [<a target="_parent" href="{{row.link}}" style="text-decoration: underline;">link</a>]
      </td>
    </tr>
    {% endfor %}
  </tbody>
</table>
