---
layout: post
date: 2017-04-02
title: "Tredicesima hacknight: Zend Framework"
img: turin.jpg
abstract: Toolbox Coworking 20/04/2017 h. 18.30
---

<div class="row">
    <div class="col-lg-12">
        <p>Tema di questa Hacknight è <a href="https://framework.zend.com/">Zend Framework</a>, un framework open source per lo sviluppo di applicazioni PHP. Enrico Zimuel ci mostrerà come funziona e come contribuire al progetto.</p>
        <p>L'evento è gratuito ma richiede la <a target="_blank" href="https://www.eventbrite.com/e/biglietti-torino-hacknight-zend-framework-33378097789">registrazione</a>.</p>
        <p>Vi aspettiamo giovedì 20 aprile 2017 alle 18.30 presso Toolbox.</p>
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
