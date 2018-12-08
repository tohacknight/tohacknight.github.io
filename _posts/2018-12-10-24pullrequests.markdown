---
layout: post
date: 2018-12-06
title: "Venticinquesima hacknight: 24Pullrequests"
img: turin.jpg
abstract: Toolbox Coworking 10/12/2018 h. 18.30
---

<div class="row">
    <div class="col-lg-12">
        <p>
            Questo mese Torino Hacknight partecipa ad una serata <a href="https://www.meetup.com/it-IT/turn-into-coders/" target="_blank" title="Coding for everyone meetup">Coding for everyone!</a> <br />
            Durante la serata faremo una presentazione su due pilastri dello sviluppo di 
            codice Open Source: riportare bug e contribuire codice. Due temi fondamentali 
            sia per gli sviluppatori alle prime armi che a quelli più navigati.
        </p>
        <p>
            Al termine della presentazione si programma assieme su <a href="https://24pullrequests.com/" target="_blank" title="24pullrequests.com">24pullrequests.com</a>
            <br />
            Gadget per tutti e premi per chi parteciperà con più profitto alla serata e ai 
            reduci di Hacktoberfest!
            <br />
            Iscrizioni qua: <a href="https://www.meetup.com/it-IT/turn-into-coders/events/fxjxspyxqbnb/" target="_blank" title="Registrati all'evento tramite eventbrite">meetup.com/it-IT/turn-into-coders/events/fxjxspyxqbn</a>.
            Vi aspettiamo <strong>lunedì 10 dicembre</strong> presso la FabCucina di Toolbox.
        </p>
    </div>
</div>

<div class="row">
    <div class="col-lg-12">
        <h4>Cos'è Coding for everyone?</h4>
        <p>Incontri settimanali organizzati per chi vuole programmare in Javascript o Python, anche partendo da zero.</p>
    </div>
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
        {% endfor %}
    </div>
</div>
