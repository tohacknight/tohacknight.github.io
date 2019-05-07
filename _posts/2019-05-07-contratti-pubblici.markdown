---
layout: post
date: 2019-05-07
title: "Ventottesima hacknight: Contratti Pubblici"
img: turin.jpg
abstract: Toolbox Coworking 29/05/2019 h. 18.30
---

<div class="row">
    <div class="col-lg-12">
	<p>Ogni anno le pubbliche amministrazioni sono obbligate a pubblicare un resoconto in formato XML dei contratti che hanno fatto nell'anno precedente. Questi resoconti vengono poi recepiti dall'ANAC, l'autorità nazionale anticorruzione. Sfortunatamente non è disponibile un validatore per questi dati e capita che alcuni di questi XML non siano validi.</p>

	<p>Il piano della serata è quello di creare un sistema di validazione sia sintattico che semantico per questo tipo di dati.</p>
        <p>
            L'evento è gratuito ma occorre <a href="https://tohacknight-contratti-pubblici-19.eventbrite.it/" target="_blank" title="Registrati all'evento tramite eventbrite">registrarsi</a>.
        </p>
        <p>Vi aspettiamo <strong>mercoledì 29 maggio</strong> presso Toolbox.</p>
    </div>
</div>

<div class="row">
    <div class="col-lg-12">
        <h4>Cos'è Torino hacknight?</h4>
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
	    <p><a href="https://synapta.it" target="_blank"><img src="/img/partners/synapta.png" alt="synapta"></a></p>
        {% endfor %}
    </div>
</div>
