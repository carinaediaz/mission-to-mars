# Mission to Mars
## Overview
##### We were tasked with assiting Robin with her passion project of creating a website that will scrape the latest news, images, and data on Mars anytime anyone visits the website. We utilized Python, Splinter, DevTools, BeautifulSoup, and MongoDB to create our Flask app that will refresh the data on the page anytime a "Scrape New Data" button is clicked. 
## Results
##### One of the additional customizations we made to our index.html file was changing the button color from "primary" to "info" or a dark blue to a light blue, seen in the code below. 
```
<!-- Add a button to activate scraping script -->
<p><a class="btn btn-info btn-lg" href="/scrape" role="button">Scrape New Data</a></p>
```
##### Additionally, the table's formatting was changed to a condensed style with the edit to our code below. 
```
<div class="col-md-4">
  <!-- Mars Facts -->
    <div class="row table-condensed" id="mars-facts">
      <h4>Mars Facts</h4>
      {{ mars.facts | safe }}
    </div>
  </div>
```
##### Below are images of how the page is seen on a desktop browser and a mobile device. 
![browser_view1.PNG](https://github.com/carinaediaz/mission-to-mars/blob/main/Resources/browser_view1.PNG)
![browser_view2.PNG](https://github.com/carinaediaz/mission-to-mars/blob/main/Resources/browser_view2.PNG)
![mobile_view.PNG](https://github.com/carinaediaz/mission-to-mars/blob/main/Resources/mobile_view.PNG)
