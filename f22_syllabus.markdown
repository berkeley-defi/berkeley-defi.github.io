---
layout: blank
title: "Decentralized Finance"
permalink: /f22_syllabus
---

<table style="table-layout: fixed; font-size: 88%;">
  <thead>
      <th style="width: 10%;">Date</th>
      <th style="width: 10%;"> Quiz </th>
      <th style="width: 50%;"> Topic </th>
      <th style="width: 30%;"> Recommended reading </th>
  </thead>
  <tbody>
    {% for row in site.data.f22syllabus %}
    <tr>
      <td> {{ row.date }} </td>
      <td>
        {% if row.quiz %}
          <a target="_parent" href="{{row.quiz.link}}" style="text-decoration: underline;">{{row.quiz.name}}</a>
        {% else %}
          TBD
        {% endif %}
      </td>
      <td> {{ row.topic }}
        <br>
        {% if row.youtube_premiere %}
          [<a target="_parent" href="{{row.youtube_premiere}}" style="font-size: 80%;text-decoration: underline;">Premiere</a>]
        {% endif %}
        {% if row.youtube_playlist %}
          [<a target="_parent" href="{{row.youtube_playlist}}" style="font-size: 80%;text-decoration: underline;">Playlist</a>]
        {% endif %}
        {% if row.slides %}
        <ul style="margin-bottom: 0;">
          {% for s in row.slides %}
          <li> <a target="_parent" href="https://berkeley-defi.github.io/assets/material/{{s.file}}" style="font-size: 80%;"> Slides: {{ s.name }} </a> </li>
          {% endfor %}
        </ul>
        {% endif %}
      </td>
      <td>
        {% if row.reading %}
        <ul style="margin-bottom: 0;">
          {% for r in row.reading %}
            {% if r.file %}
              {% assign reading_link = 'https://berkeley-defi.github.io/assets/material/' | append: r.file %}
            {% endif %}
            {% if r.link %}
              {% assign reading_link = r.link %}
            {% endif %}
          <li> <a target="_parent" href="{{reading_link}}"> {{ r.name }} </a> </li>
          {% endfor %}
        </ul>
        {% endif %}
      </td>
    </tr>
    {% endfor %}
  </tbody>
</table>
