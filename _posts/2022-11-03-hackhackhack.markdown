---
layout: post
date: 2022-11-03
title: "42esima hacknight: Hack hack hack"
img: turin.jpg
abstract: Toolbox Coworking 23/11/2022 h. 18.30
---

<div class="row">
    <div class="col-lg-12">
    <p>Vuoi contribuire ad un progetto open source ma non sei ancora riuscito a farlo? Sei uno sviluppatore che vuole condividere le sue conoscenze con gli altri? Sei uno sviluppatore di free software e cerchi aiuto per il tuo progetto? Sei il benvenuto ad una serata hacknight!</p>
<p>Fai un pitch del tuo progetto open source o del progetto a cui vuoi contribuire per trovare qualcuno con cui collaborare. Ogni partecipante può lavorare al progetto che preferisce e può approfittare della presenza degli altri per condividere le sue conoscenze o reperire qualcuno con le conoscenze che gli mancano.</p>
<p>La serata è organizzata in collaborazione con <a href="https://t.me/torinorust">Rust Torino</a>, 
<a href="https://www.meetup.com/it-IT/golang-torino/">Go Meetup Torino</a> e <a href="https://community.cncf.io/torino/">CNCF Torino.</a></p>
        <p>L'evento è gratuito ma occorre <a href="https://tohacknight-2211.eventbrite.it/" target="_blank" title="Registrati all'evento">registrarsi</a>.</p>
        <p>Vi aspettiamo <strong>mercoledì 23 novembre</strong> alle 18.30 in Toolbox Coworking.</p>
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
