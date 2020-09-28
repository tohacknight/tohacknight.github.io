---
layout: post
date: 2020-09-28
title: "Trentaseiesima hacknight: Hacktoberfest"
img: turin.jpg
abstract: Online 06/10/2020 h. 18.30
---

<div class="row">
    <div class="col-lg-12">
    <p>
        <a href="https://hacktoberfest.digitalocean.com/" target="_blank" title="Hacktoberfest pagina ufficiale">Hacktoberfest</a>, patrocinato da DigitalOcean in collaborazione con DEV ed Intel
        è un mese dedicato al software open source.
    </p>
    <p>
        Nessuna contribuzioni è troppo piccola, bug fix e aggiornamento alla documentazione
        sono contribuzioni valide.
        Durante la serata ci sarà una breve introduzione su come contribuire a progetti 
        open source, lasciando il resto del tempo ai partecipanti per contribuire 
        attivamente.
    </p>
        <p>L'evento è gratuito ma occorre <a href="https://organize.mlh.io/participants/events/4650-torino-hacknight-hacktoberfest" target="_blank" title="Registrati all'evento">registrarsi</a>.</p>
        <p>Vi aspettiamo <strong>martedì 6 ottobre</strong> in <a href="https://matrix.to/#/!vXfeXqRqgEQsOFBFfa:matrix.org?via=matrix.org">chat</a>.</p>
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
