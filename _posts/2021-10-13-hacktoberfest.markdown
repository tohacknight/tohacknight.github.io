---
layout: post
date: 2021-10-13
title: "Quarantesima hacknight: Hacktoberfest"
img: turin.jpg
abstract: Toolbox Coworking 13/10/2021 h. 18.30
---

<div class="row">
    <div class="col-lg-12">
    <p>
        <a href="https://hacktoberfest.digitalocean.com/" target="_blank" title="Hacktoberfest pagina ufficiale">Hacktoberfest</a>, patrocinato da DigitalOcean in collaborazione con Appwrite, Intel e Deepsource
        è un mese dedicato al software open source.
    </p>
    <p>
        Nessuna contribuzioni è troppo piccola, bug fix e aggiornamento alla documentazione
        sono contribuzioni valide.
        Durante la serata i partecipanti potranno contribuire attivamente ad un
	progetto di loro scelta.
    </p>
        <p>L'evento è gratuito ma occorre <a href="https://tohacknight-hacktoberfest-2021.eventbrite.it/" target="_blank" title="Registrati all'evento">registrarsi</a>.</p>
        <p>Vi aspettiamo <strong>mercoledì 13 ottobre</strong> alle 18.30 in Toolbox Coworking.</p>
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
