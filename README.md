# black-door
<h3>What is it? </h3>
Black Door is an open-source directory for things to to in your city. 
<h3>Stack </h3>
React
Mapbox API
CSS
<h3>What does it do?</h3>
Black Door presents users with a host of things to do in their city, from restaurants to hikes to art galleries and museums.
<h3>Contributing</h3>
Adding a place to the library is super simple. All the different locations are loaded and rendered from a single locations.json file in the root.

To add your location, fork this repository, add the locations name, address, a brief description, its category(see category breakdown) and a website link(if applicable) to the end of the json file and submit a pull request. 
Don't forget the commas!

[
    {
        …
    },
    {
      "name": "Iziko Museum",
      "address": "71 Wale Street, Cape Town, Western Cape",
      "type": "Arts & Culture",
      "description": "The Iziko Museums of Cape Town — an amalgamation of 12 national museums located near the Cape Town city centre. Iziko museums spheres – natural history, social history and arts.",
      "website": "https://www.iziko.org.za/"
    }
]
NOTE - Please keep location submissions and bug fixes in separate PRs.
