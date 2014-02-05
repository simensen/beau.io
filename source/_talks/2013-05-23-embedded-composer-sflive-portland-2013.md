---
title: Embedded Composer
location: Symfony Live Portland 2013
slides: https://speakerdeck.com/simensen/embedded-composer-sflive-portland-2013
slides_embed: <script async class="speakerdeck-embed" data-id="e30331a0a5a7013000c042db8da5a4ed" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>
audio_slides: http://www.youtube.com/watch?v=9CSovVvRwXk
cover: assets/images/talks/2013-05-23-embedded-composer.jpg
logo: assets/images/talks/sfliveportland2013-logo.png
logo_link: http://portland2013.live.symfony.com/speakers#session-825
joinedin: https://joind.in/talk/view/8667
tags:
    - conference
    - composer
    - embedded-composer

---
{% block description %}

Composer is a wonderful way to manage a project. But what happens when you need your application to be extensible at runtime? Enter Embedded Composer. Embedding Composer will ensure that the dependencies already included by your application are taken into account when adding additional dependencies at runtime. While this can be very useful for any application that may be installed globally it is critical for any application that may be distributed as a phar.

{% endblock %}
