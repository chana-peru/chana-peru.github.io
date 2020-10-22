---
layout: default
title: Members
permalink: /members/
---

<div id="portfolio" class="portfolio row grid-container gutter-20" data-layout="fitRows">
    {% for member in site.data.members %}
    <article class="portfolio-item col-lg-3 col-md-4 col-sm-6 col-12 pf-media pf-icons">
        <div class="grid-inner">
            <div class="portfolio-image">
                <a href="portfolio-single.html">
                    <img src="/images/members/{{member.photo}}" alt="Member">
                </a>
                <div class="bg-overlay">
                    <div class="bg-overlay-content dark" data-hover-animate="fadeIn">
                        <a href="#" class="overlay-trigger-icon bg-light text-dark" data-hover-animate="fadeInDownSmall" data-hover-animate-out="fadeOutUpSmall" data-hover-speed="350"><i class="icon-line-ellipsis"></i></a>
                    </div>
                    <div class="bg-overlay-bg dark" data-hover-animate="fadeIn"></div>
                </div>
            </div>
            <div class="portfolio-desc">
                <h3><a href="portfolio-single.html">{{member.full_name}}</a></h3>
                <span>{{member.topics}}</span>
                <span>{{member.email}}</span>
            </div>
        </div>
    </article>
    {% endfor %}
</div>