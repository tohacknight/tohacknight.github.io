---
layout: post
date: 2018-01-01
title: "Diciottesima hacknight: OpenStreetMap"
img: turin.jpg
abstract: Toolbox Coworking 18/01/2017 h. 18.30
---

<div class="row">
    <div class="col-lg-12">
	<p>Due ore dedicate ad OpenStreeMap, il progetto per creare una mappa modificabile liberamente del mondo. Vedremo cos'è, cosa ci possiamo fare e come vi possiamo contribuire.</p>
	<p>Verranno presentati casi d'uso, strumenti di esportazione di dati e come creare visualizzazioni personalizzate.</p>
        <p>L'evento è gratuito ma occorre <a href="https://www.eventbrite.com/e/biglietti-torino-hacknight-openstreetmap-41678424289">registrarsi</a>.</p>
        <p>Vi aspettiamo giovedì 18 gennaio 2017 alle 18.30 presso la FabCucina di Toolbox.</p>
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
        <p><a href="http://www.5t.torino.it" target="_blank"><img src="http://www.5t.torino.it/wp-content/themes/5t/images/logo.png" alt="5t"></a></p>
    </div>
</div>
