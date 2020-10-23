---
layout: default
title: Meetings
permalink: /meetings/
---

<div class="parallax header-stick bottommargin-lg dark"
    style="padding: 60px 0; background-image: url('{{ '/images/parallax/calendar.jpg' | prepend: site.baseurl | prepend: site.url}}'); height: auto;"
    data-bottom-top="background-position:0px 0px;" data-top-bottom="background-position:0px -500px;">
    <div class="container clearfix">
        <div class="events-calendar">
            <div class="events-calendar-header clearfix">
                <h2>Events Overview</h2>
                <h3 class="calendar-month-year">
                    <span id="calendar-month" class="calendar-month"></span>
                    <span id="calendar-year" class="calendar-year"></span>
                    <nav>
                        <span id="calendar-prev" class="calendar-prev"><i class="icon-chevron-left"></i></span>
                        <span id="calendar-next" class="calendar-next"><i class="icon-chevron-right"></i></span>
                        <span id="calendar-current" class="calendar-current" title="Got to current date"><i
                                class="icon-reload"></i></span>
                    </nav>
                </h3>
            </div>
            <div id="calendar" class="fc-calendar-container"></div>
        </div>
    </div>
</div>