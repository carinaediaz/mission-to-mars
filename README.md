# Mission to Mars
## Overview
##### We are assisting Robin with her passion project of creating a website that will scrape the latest news, images, and data on Mars anytime anyone visits the website. We utilized Python, Plinter, DevTools, BeautifulSoup, and MongoDB to create our Flask app that will refresh the data on the page anytime a "Scrape New Data" button is clicked. 
## Results
##### Additional customizations that were made to our index.html file were changing the button color from "primary" to "info" or a dark blue to a light blue. This was a simple change to our line of code that creates the button, seen below. 
```
<!-- Add a button to activate scraping script -->
<p><a class="btn btn-info btn-lg" href="/scrape" role="button">Scrape New Data</a></p>
```
Additionally, the table's formatting was changed to a condensed style with the edit to our code below. 
```
<div class="col-md-4">
  <!-- Mars Facts -->
    <div class="row table-condensed" id="mars-facts">
      <h4>Mars Facts</h4>
      {{ mars.facts | safe }}
    </div>
  </div>
```
