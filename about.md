---
layout: page
title: O stronie
permalink: /about/
---

## Strona poświęcona starszym modelom telefonów komórkowych

![Odnośnik](http://tse1.mm.bing.net/th?id=OIP.M1d3270d058398fd62d9c75cf4557d22cH0)


### ***Między cegłą, a dachówką***


Strona została poświęcona tzw. klasycznym komórkom, które miały być praktyczne i wygodne w użyciu. Ich zakres funkcjonalności ograniczał się do dzwonienia, smsowania czy też w nowszych modelach ~~(hehe)~~ odtwarzania plików muzycznych itp...

##Nagłówek

<ul>
{% for item in site.data.dane %}
  <li><strong>{{ item['klucz']}}</strong>:
  {for anotherItem in item['innyklucz']%}
  {{ anotherItem }}
  {% endfor %}
  </li>
{%endfor%}
</ul>
