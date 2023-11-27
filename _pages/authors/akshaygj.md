---
layout: page
title: ಅಕ್ಷಯ್ ಜೋಗಿಹಳ್ಳಿ
permalink: /author/akshaygj
author: akshaygj
comments: false
---

<div class="row justify-content-between">
<div class="col-md-8 pr-5">
    {% assign author = site.authors[page.author] %}
    <div class="row post-top-meta">
        <div class="col-xs-12 col-md-3 col-lg-2 text-center text-md-left mb-4 mb-md-0">
            {% if author.avatar %}
            <img class="author-thumb" src="{{site.baseurl}}/{{ author.avatar }}" alt="{{ author.display_name }}">
            {% else %}
            <img class="author-thumb" src="https://www.gravatar.com/avatar/{{ author.gravatar }}?s=250&d=mm&r=x" alt="{{ author.display_name }}">
            {% endif %}
        </div>
        <div class="col-xs-12 col-md-9 col-lg-10 text-center text-md-left">
            <!-- <a target="_blank" class="link-dark" href="{{ author.web }}">{{ author.display_name }}</a><a target="_blank" href="{{ author.twitter }}" class="btn follow">Follow</a> -->
            <br>
            <span class="author-description">{{ author.description }}</span>
        </div>
    </div>
    
<!-- 
<h4>Documentation</h4>

<p>Please, read the docs <a href="https://bootstrapstarter.com/bootstrap-templates/template-mediumish-bootstrap-jekyll/">here</a>.</p> -->

</div>

<div class="col-md-4">

<div class="sticky-top sticky-top-80">
<!-- <h5>Buy me a coffee</h5> -->

<!-- <p>Thank you for your support! Your donation helps me to maintain and improve <a target="_blank" href="https://github.com/wowthemesnet/mediumish-theme-jekyll">Mediumish <i class="fab fa-github"></i></a>.</p> -->

<!-- <a target="_blank" href="https://www.wowthemes.net/donate/" class="btn btn-danger">Buy me a coffee</a> <a target="_blank" href="https://bootstrapstarter.com/bootstrap-templates/template-mediumish-bootstrap-jekyll/" class="btn btn-warning">Documentation</a> -->

</div>
</div>
</div>
