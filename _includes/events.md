<div class="w3-row w3-padding-32 events" id="opportunity">

    <h1 class="w3-panel w3-pale-blue w3-leftbar w3-border-red"> Upcoming events </h1>
    {% for event in site.data.events %}
      <div class="w3-row w3-margin-xlarge w3-padding-xlarge">
          <div class="w3-col m6">
          <img src="{{ site.url }}{{event.image}}" class="w3-round w3-image w3-padding-small" alt="{{event.id}}" width="500" height="500">
          </div>
          <div class="w3-col m6">
          <h1> {{event.name}} </h1>
          <h6> {{event.description}} </h6>
          <h5 class="w3-padding-32"> <a href="{{event.url}}" class="w3-right">read more ...</a></h5>
          </div>
      </div>
      <hr>
    {% endfor %}

</div>
