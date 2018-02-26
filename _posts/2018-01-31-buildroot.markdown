---
layout: post
date: 2018-01-31
title: "Diciannovesima hacknight: Embedded con Buildroot"
img: turin.jpg
abstract: Toolbox Coworking 15/02/2018 h. 18.30
---

<div class="row">
    <div class="col-lg-12">
	<p>Alexjan Carraturo ci introdurrà ai sistemi embedded, sia dal punto di vista hardware che software.</p>
	<p>Faremo una panoramica degli elementi software di un sistema embedded con una introduzione ai sistemi di build.</p>
	<p>Quindi tramite Buildroot vedremo la creazione degli elementi software legati ad un sistema embedded.</p>
        <p>L'evento è gratuito ma occorre <a href="https://www.eventbrite.it/e/biglietti-torino-hacknight-embedded-con-buildroot-42633951296">registrarsi</a>.</p>
        <p>Vi aspettiamo giovedì 15 febbraio 2018 alle 18.30 presso la FabCucina di Toolbox.</p>
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
    </div>
</div>
