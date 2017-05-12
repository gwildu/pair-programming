# pair programming

## setup

* github?
* node.js?
* other?
* access the network

## server

* create a simple server application to deliver 2 simple pages
  * first page url is /{de/fr}/s
  * second page url is /{de/fr}/auto/s
  
## images

* For a search result page we want to add per each item a thumbnail image
  * on the first page we need to display the image in 180px x 180 on tablets and desktops and 100px x 100px on mobile devices
  * on the auto page 240px x 180px for tablet / desktop and 100px x 100px for mobile
  * first create the markup for those images
  * Questions:
    * what formats of the images will you need?
    * where would you store the images?

## api

* get the url templates from the api (https://assets-domain-api-svc.ricardo-dev.ch/assets/744883552,800533060,636326908/templates) 
and render the markup with the templates (and some transformations that you will get from me)


## if there is time left

* localize the page
* dockerize the application
* create a setup for CI

## cleanup

* delete the network settings