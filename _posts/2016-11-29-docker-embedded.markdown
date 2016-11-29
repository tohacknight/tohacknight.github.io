---
layout: post
date: 2016-11-29
title: "Nona hacknight: Docker per IoT"
img: turin.jpg
name: "Nona hacknight: Docker per IoT"
abstract: Toolbox Coworking 15/12/2016 h. 18.30
---

<div class="row">
    <div class="col-lg-12">
        <p>Tema di questa Hacknight è l'uso di <a href="http://docker.io">Docker</a> in ambito embedded su piattaforme ARM. Per farci cosa? per lo sviluppo di microservizi, cloud and distributed computing, IoT, etc.</p>
        <p>L'evento è gratuito ma richiede la <a target="_blank" href="https://www.eventbrite.com/e/biglietti-torino-hacknight-docker-per-iot-29796192213">registrazione</a>.</p>
        <p>Vi aspettiamo giovedì 15 dicembre 2016 alle 18.30 presso Toolbox.</p>
    </div>
</div>

<div class="row">
    <div class="col-lg-12">
        <h4>Cos'è hacknight?</h4>
        <p>Lo scopo di hacknight è quello di sensibilizzare le comunità di sviluppatori allo sviluppo di software libero.</p>
        <p>Ad una serata hacknight i partecipanti sono invitati a contribuire attivamente ad un progetto open source aiutati da contributori dello stesso.</p>

        <h4>Cosa devo portare?</h4>
        <p>Il tuo computer e voglia di fare.</p>
    </div>
</div>

<div class="row">
    <div class="col-lg-12">
        <p><br></p>
        <p>Evento organizzato in collaborazione con:</p>
        {% for partner in site.partners %}
            <p><a href="{{ partner.url }}" target="_blank">{% if partner.img %}<img src="{{ partner.img }}" alt="{{ partner.name }}">{% else %}{{ partner.name }}{% endif %}</a></p>
        {% endfor %}
        <p><a href="http://trampolineup.com" target="_blank"><img width="200px" src="http://i.imgur.com/7qftAxD.png" alt="Trampoline"></a></p>
    </div>
</div>
