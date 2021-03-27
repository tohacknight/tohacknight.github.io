---
layout: post
date: 2021-03-27
title: "39esima hacknight: React Native in Microsoft"
img: turin.jpg
abstract: Online 12/04/2021 h. 18.50
---

<div class="row">
    <div class="col-lg-12">
    <p>con la primavera ritorna anche Torino Hacknight! React Native è un framework nato come soluzione per usare React in applicazioni mobile native. <a href="https://kelset.dev/">Lorenzo Sciandra</a> ci racconta come Microsoft si è avvicinata al progetto fino ad espanderlo alle piattaforme desktop e le complessità dovute alla natura Open source del progetto.</p>
        <p>L'evento è gratuito ma occorre <a href="https://tohacknight-react-native-ms.eventbrite.it" target="_blank" title="Registrati all'evento">registrarsi</a>.</p>
        <p>Vi aspettiamo <strong>lunedì 12 Aprile</strong> dalle 18.50.</p>
    </div>
</div>

<div class="row">
    <div class="col-lg-12">
        <h4>Cos'è hacknight?</h4>
        <p>Lo scopo di hacknight è quello di sensibilizzare le comunità di sviluppatori allo sviluppo di software libero.</p>
        <p>Ad una serata hacknight i partecipanti sono invitati a contribuire attivamente ad un progetto open source aiutati da contributori dello stesso.</p>
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
