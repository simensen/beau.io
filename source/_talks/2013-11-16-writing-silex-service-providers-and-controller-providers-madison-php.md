---
title: Writing Silex Service Providers and Controller Providers
location: Madison PHP 2013
slides: https://speakerdeck.com/simensen/writing-silex-service-providers-and-controller-providers-madison-php
slides_embed: <script async class="speakerdeck-embed" data-id="0075720030be013117614a6663548e9a" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>
cover: assets/images/talks/2013-11-16-writing-silex-service-providers-and-controller-providers.jpg
logo: assets/images/talks/madisonphp-logo.png
logo_link: http://2013.madisonphpconference.com/schedule/view/6/writing-silex-service-providers-and-controller-providers-beau-simensen
joinedin: https://joind.in/talk/view/10056
tags:
    - conference
    - silex
    - pimple

---
{% block description %}

So you've gotten to the point in your Silex application that you want to start breaking it out into modular pieces. Silex service providers and controller providers to the rescue! These interfaces appear to be really simple but do you know which things can safely be done in each method?

Find out the intended purpose for each interface and which operations should be done (or avoided) in each of their methods. Get a quick tour of Silex and Pimple and learn about why laziness is so important when writing code for Silex. By following some best practices you can avoid headaches for both you and your users.

{% endblock %}
