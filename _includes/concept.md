<div class="w3-row w3-center" id="home">
    <div class="w3-col m9">
      {% for concept in site.data.concepts %}
        <div class="w3-col m5 border w3-center" style="margin:5px;">
            <div class="w3-col s7 {{concept.alignment}}">
                <img src="{{ site.url }}{{concept.image}}" class="w3-round w3-image w3-padding-small" alt="about us" width="250" height="250">
            </div>
            <div class="w3-col s5 ">
                <h3> <i class="fa fa-star-o" aria-hidden="true" style="color:#00BFFF"></i>  </h3>
                <h4 class="w3-padding-16"> {{concept.name}}</h4>
                <a href="{{concep.url}}" class="w3-button w3-white w3-border w3-border-blue w3-round-large w3-padding-small" style="cursor:pointer">Learn more</a>
            </div>
        </div>
      {% endfor %}
    </div>  

    <div id="bitcoin_widget_container" class="w3-col m3" style="padding-top:5%"></div>
    <script src="https://cryptocoinsnews.com/widget/bitcoin_widget.js.php" type="text/javascript"></script>
</div>
