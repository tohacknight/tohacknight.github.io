---
layout: post
date: 2016-10-19
title: "Ottava hacknight: LibreOffice"
img: turin.jpg
name: "Ottava hacknight: LibreOffice"
abstract: Toolbox Coworking 7/11/2016 h. 18.30
---

<div class="row">
    <div class="col-lg-12">
        <p>Tema di questa Hacknight sarà <a href="http://libreoffice.org">LibreOffice</a>, la suite libera per l'ufficio. Ti aspettiamo se sei curioso di sapere come è fatta una applicazione
        usata da milioni di utenti oppure come puoi usare le nuove API LibreOfficeKit per convertire e maneggiare documenti.</p>
        <p>L'evento è gratuito ma richiede la <a target="_blank" href="https://www.eventbrite.com/e/torino-hacknight-libreoffice-tickets-28694636430">registrazione</a>.</p>
        <p>Vi aspettiamo quindi lunedì 7 novembre 2016 alle 18.30 presso Toolbox.</p>
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
