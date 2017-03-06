<div class="w3-row w3-padding-32" id="events">

    <h1 class="w3-panel w3-pale-blue w3-rightbar w3-border-red" style="text-align:right;"> Endless Opportunities </h1>
    <div class="w3-row">
        {% for opportunity in site.data.opportunities %}
          <div class="w3-col l6 w3-padding-large">
            <div class="w3-col l6 w3-padding-large">
              <img src="{{ site.url }}{{opportunity.image}}" class="w3-round w3-image w3-padding-small" alt="{{opportunity.id}}" width="300" height="200">
            </div>
            <div class="w3-col l6 w3-padding-large">  
              <h4> {{opportunity.name}} </h4>
              {{opportunity.description}}
              <a href="{{opportunity.url}}" class="w3-right" style="float: right;">read more ...</a>
            </div>
          </div>
        {% endfor %}

    </div>

</div>
