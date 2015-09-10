---
fuzzy_date: true
title: Decomposing Packages
location: "Symfony Live! San Francisco 2015"
#slides: https://speakerdeck.com/simensen/managing-dependencies-with-composer-php-world-2014
#slides_embed: <script async class="speakerdeck-embed" data-id="123f86204bf401329b467e55d489251a" data-ratio="1.77777777777778" src="//speakerdeck.com/assets/embed.js"></script>
#cover: assets/images/talks/2014-11-11-composer.jpg
logo: assets/images/talks/sfl_sanfrancisco2015.png
logo_link: http://sanfrancisco2015.live.symfony.com/
#joinedin: https://joind.in/14975
tags:
    - conference
    - composer
    - decomposer
x-meta:
    og:
        title: "Decomposing Packages &middot; Beau Simensen &middot; dflydev"
        description: "Using 3rd-party code isn't always painless."
        type: website
        image:
            url: https://beau.io/assets/images/talks/2014-11-11-composer.jpg
            width: 1920
            height: 1080
            type: image/jpg

---
{% block description %}

Using Composer and Packagist makes using 3rd-party code easier but relying on 3rd-party code can have drawbacks. Projects are abandoned. Maintainers become unresponsive. Fortunately, Composer provides tools to help make these situations a little easier to manage. Learn how to leverage Composer features like "replace" and tools like Satis to manage forks of 3rd-party packages. See pros and cons of various methods so that you can feel more confident in how you decide to move forward with decomposing other people's packages.

{% endblock %}
{% block talk_cta_no_well %}
<script src="https://app.convertkit.com/landing_pages/766.js?orient=horz&ref=beau.io-dpc-psr7"></script>
{% endblock  %}
