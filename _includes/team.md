<div class="w3-row w3-padding-32" id="team">

    <h1 class="w3-panel w3-pale-blue w3-leftbar w3-border-red"> Leadership team </h1>
    {% for team in site.data.teams %}
      <div class="w3-col l4 w3-padding-large">
          <div class="w3-card-4 w3-center">
              <img src="{{ site.url }}{{team.image}}" alt="Person" class="w3-padding-large" style="width:70%">
              <p> <b style="font-size:20px;">{{team.name}}</b> - {{team.position}} </p>
              <p>{{team.description}}</p>
          </div>
      </div>
    {% endfor %}
</div>
