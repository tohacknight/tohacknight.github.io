---
layout: post
date: 2022-09-28
title: "41esima hacknight: Hacktoberfest"
img: turin.jpg
abstract: Toolbox Coworking 18/10/2022 h. 18.30
---

<div class="row">
    <div class="col-lg-12">
    <p>
        <a href="https://hacktoberfest.com/" target="_blank" title="Hacktoberfest pagina ufficiale">Hacktoberfest</a>, patrocinato da Digital Ocean, è un mese dedicato alla contribuzione a progetti Open Source.</p>
<p>Nessuna contribuzione è troppo piccola e contribuire non vuol dire solo scrivere codice. Piccoli bug fix e aggiornamenti alla documentazione sono contribuzioni valide.</p>
<p>Durante la serata i partecipanti potranno contribuire attivamente ad un progetto di loro scelta. Dopo quattro contribuzioni di qualità effettuate durante il mese di ottobre è possibile richiedere di piantare un albero a proprio nome.</p>
<p>Quest'anno la serata è organizzata in collaborazione con <a href="https://t.me/torinorust">Rust Torino</a>, 
<a href="https://www.meetup.com/it-IT/golang-torino/">Go Meetup Torino</a> e <a href="https://community.cncf.io/torino/">CNCF Torino.</a></p>
        <p>L'evento è gratuito ma occorre <a href="https://tohacktoberfest22.eventbrite.it/" target="_blank" title="Registrati all'evento">registrarsi</a>.</p>
        <p>Vi aspettiamo <strong>martedì 18 ottobre</strong> alle 18.30 in Toolbox Coworking.</p>
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
