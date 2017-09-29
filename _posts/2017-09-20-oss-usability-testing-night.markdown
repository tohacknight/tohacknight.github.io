---
layout: post
date: 2017-09-20
title: "Sedicesima hacknight: OSS Usability Testing Night con TUX Meetup"
img: turin.jpg
abstract: Toolbox Coworking 19/10/2017 h. 18.30
---

<div class="row">
    <div class="col-lg-12">
        <p>Dopo la pausa estiva torna hacknight e torna in compagnia del <a href="https://www.meetup.com/it-IT/T-UX-Meetup">Torino User Experience Meetup</a>. Per questa serata infatti proponiamo in collaborazione una <em>usability testing night</em> per progetti open source.</p>
        <p>Durante la serata vedrete come condurre test di usabilitá sia un ottimo modo per far si che un progetto risponda alle effettive esigenze dei propri utenti.</p>
        <p>Vogliamo farvi vivere l'esperienza di utente in prima persona e raccogliere il vostro feedback.</p>
        <p>L'evento è gratuito ma occorre <a href="https://www.eventbrite.com/e/biglietti-torino-hacknight-ux-testing-38437880736">registrarsi</a>.</p>
        <p>Vi aspettiamo giovedì 19 ottobre 2017 alle 18.30 presso la FabCucina di Toolbox.</p>
    </div>
</div>

<div class="row">
    <div class="col-lg-12">
        <h4>Cos'è hacknight?</h4>
        <p>Lo scopo di hacknight è quello di sensibilizzare le comunità di sviluppatori allo sviluppo di software libero.</p>
        <p>Ad una serata hacknight i partecipanti sono invitati a contribuire attivamente ad un progetto open source aiutati da contributori dello stesso.</p>

        <h4>Cosa devo portare?</h4>
        <p>Il tuo computer e voglia di fare. Al rinfresco ci pensa <a href="https://www.ibuildings.it" target="_blank">ibuildings</a>.</p>
    </div>
</div>

<div class="row">
    <div class="col-lg-12">
        <p><br></p>
        <p>Evento organizzato in collaborazione con:</p>
        {% for partner in site.partners %}
            <p><a href="{{ partner.url }}" target="_blank">{% if partner.img %}<img src="{{ partner.img }}" alt="{{ partner.name }}">{% else %}{{ partner.name }}{% endif %}</a></p>
        {% endfor %}
        <p><a href="https://www.ibuildings.it" target="_blank"><img src="https://www.ibuildings.it/profiles/ibuildings/themes/ibuildings/images/main-logo.png" alt="Ibuildings"></a></p>
    </div>
</div>
