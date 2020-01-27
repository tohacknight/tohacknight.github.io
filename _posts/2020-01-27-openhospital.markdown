---
layout: post
date: 2020-01-27
title: "Trentaduesima hacknight: Open Hospital"
img: turin.jpg
abstract: Toolbox Coworking 26/02/2020 h. 18.30
---

<div class="row">
    <div class="col-lg-12">
    <p>
<a href="https://www.open-hospital.org/" target="_blank">Open Hospital</a> è un software <a href="https://github.com/informatici" target="_blank">open source</a> per la gestione di dati sanitari sviluppato da Informatici senza Frontiere. E` sviluppato per aiutare ospedali e ONG in paesi in via di sviluppo. Viene usato per gestire la registrazione dei pazienti e delle visite, per registrare nascite e vaccinazioni e per gestire i flussi di materiali e medicinali. Consiste in un backend scritto in Java ed un frontend scritto in React.
    </p>
        <p>L'evento è gratuito ma occorre <a href="https://tohacknight-openhospital.eventbrite.it" target="_blank" title="Registrati all'evento tramite eventbrite">registrarsi</a>.</p>
        <p>Vi aspettiamo <strong>mercoledì 26 febbraio</strong> presso Toolbox.</p>
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
