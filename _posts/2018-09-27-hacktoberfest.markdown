---
layout: post
date: 2018-09-27
title: "Ventiquattresima hacknight: Hacktoberfest"
img: turin.jpg
abstract: Toolbox Coworking 17/10/2018 h. 18.30
---

<div class="row">
    <div class="col-lg-12">
    <p>
        <a href="https://hacktoberfest.digitalocean.com/" target="_blank" title="Hacktoberfest pagina ufficiale">Hacktoberfest</a>, patrocinato da DigitalOcean in collaborazione con GitHub e 
        Twilio, è un mese dedicato al software open source. Tutte le contribuzioni sono 
        importanti: piccole modifiche, anche alla documentazione sono valide.
        Durante la serata ci sarà una breve introduzione su come contribuire a progetti 
        open source, lasciando il resto del tempo ai partecipanti per contribuire 
        attivamente.
        Chi farà 5 Pull Request durante il mese di Ottobre riceverà la maglietta 
        Hacktoberfest!
    </p>
        <p>L'evento è gratuito ma occorre <a href="https://www.eventbrite.it/e/biglietti-torino-hacknight-hacktoberfest-50746193230" target="_blank" title="Registrati all'evento tramite eventbrite">registrarsi</a>.</p>
        <p>Vi aspettiamo <strong>mercoledì 17 ottobre</strong> presso la FabCucina di Toolbox.</p>
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
