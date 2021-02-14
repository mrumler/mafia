---
layout: default
title: Home
include-social-icons: true
base_url: ""
---

<h1 class="banner">Mafia</h1>

Hallo und herzlich willkommen auf der Mafia-Seite!

### Was ist Mafia?

Mafia ist ein Gesellschaftsspiel, bei dem jeder Spieler eine Rolle bekommt, die jeweils verschiedene Fähigkeiten hat.
Diese Rollen sind grob in zwei Fraktionen eingeteilt: Die Guten (oft auf "Town" genannt) und die Bösen (oft auf "Mafiosi" genannt).

### Was ist der Zweck dieser Seite?

Der Zweck dieser Seite ist ein nachschlagbares Regelwerk für alle Spieler zu bieten, da es eine gewisse Komplexität hat.

### Wie kann ich mitspielen?

Wir probieren jeden Freitag Abend zu spielen. Du kannst einfach [ins Teamspeak kommen](ts3server://arrestia.de?port=9987) und mitspielen oder auch erst einmal zuhören. 

### Kann ich helfen, das Regelwerk auszubauen?

Sehr gerne, wir freuen uns immer, wenn jemand Fehler findet, die wir beheben können oder Leute sogar komplett neue Rollen (er)finden. Entweder du kommst einfach ins Teamspeak, eröffnest ein Ticket im [GitHub Bug Tracker](https://github.com/mrumler/mafia/), oder schreibst Endstille eine [E-Mail](mailto:admin@arrestia.de).

---

## Changelogs
{: #changelogs}

<ul class="posts">
  {% for post in site.posts %}
    <li class="post">
      <h3 class="post-heading">{{post.title}} {{post.version}}<span class="post-date">vom {{post.datum}}</span></h3>

      {{ post.content }}

      {% if post.reddit %}
        <a class="post-reddit icon" href="{{post.reddit}}">
          {% include icon.html icon="reddit" %}
          <span>Auf Reddit diskutieren</span>
        </a>
      {% endif %}
    </li>
  {% endfor %}
</ul>