---
layout: default
title: Members
permalink: /members/
---
<div class="container clearfix">
<div class="row col-mb-50">
<div class="col-12">
{% if site.data.members %}
<div id="section-features" class="heading-block text-center page-section">
    <h2>Members</h2>
    <span>Some of the people that are gonna blow your mind off</span>
</div>

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
                <span>{{member.university}}</span>
            </div>
        </div>
    </article>
    {% endfor %}
</div>
{% else %}
<div id="section-features" class="heading-block text-center page-section">
    <h2>Researchers</h2>
    <span>Some of the people that are gonna blow your mind off</span>
</div>

<div id="portfolio" class="portfolio row grid-container gutter-20" data-layout="fitRows">
    {% for member in site.data.researchers %}
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

<div class="divider divider-sm divider-center"><i class="icon-circle"></i></div>

<div id="section-features" class="heading-block text-center page-section">
    <h2>Assistants & Students</h2>
    <span>Some of the people that are gonna blow your mind off</span>
</div>

<div id="portfolio" class="portfolio row grid-container gutter-20" data-layout="fitRows">
    {% for member in site.data.assistants %}
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

<div class="divider divider-sm divider-center"><i class="icon-circle"></i></div>

<div id="section-features" class="heading-block text-center page-section">
    <h2>External Collaborators</h2>
    <span>Some of the people that are gonna blow your mind off</span>
</div>

<div id="portfolio" class="portfolio row grid-container gutter-20" data-layout="fitRows">
    {% for member in site.data.externals %}
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

{% endif %}
</div>
</div>
</div>