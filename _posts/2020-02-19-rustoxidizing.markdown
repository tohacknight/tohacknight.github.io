---
layout: post
date: 2020-02-19
title: "Trentatreesima hacknight: Ossidiamo con Rust"
img: turin.jpg
abstract: Online 12/03/2020 h. 18.30
---

<div class="row">
    <div class="col-lg-12">
    <p>
	A marzo organizziamo una serata in collaborazione con il <a href="https://www.meetup.com/it-IT/Mozilla-Torino/" target="_blank">meetup Rust Torino</a> su come trasformare progetti C in Rust, in gergo ossidare. Durante la serata vedremo che strumenti possiamo usare, come farlo senza farsi male e qualche progetto open source per sperimentare con mano.
    </p>
        <p>L'evento è gratuito ma occorre <a href="https://https://tohacknight-rustoxidize.eventbrite.it/" target="_blank" title="Registrati all'evento tramite eventbrite">registrarsi</a>.</p>
        <p>Vi aspettiamo <strong>giovedì 12 marzo</strong>.</p>
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
