---
layout: master
title: DasCoin Viet Nam
concept: concept.md
team: team.md
contact: contact.md
events: events.md
opportunity: opportunity.md
---
<!-- Page content -->
<div class="w3-content" style="max-width:1200px">
    <!-- Concepts Section -->
    {% include {{ page.concept }} %}

    <!-- Upcoming events -->
    {% include {{ page.events }} %}

    <!-- Opportunity -->   
    {% include {{ page.opportunity }} %}


    <!-- Team Section -->
    {% include {{ page.team }} %}

    <!-- Contact Section -->

    <hr>
    {% include {{ page.contact }} %}
    <!-- End page content -->
</div>
