<h1>Black Door</h1>
<h3>What is it? </h3>
Black Door is an open-source directory for things to to in your city. 
<h3>Stack </h3>
React
Mapbox API
Bootstrap
<h3>What does it do?</h3>
Black Door presents users with a host of things to do in their city, from restaurants to hikes to art galleries and museums.
<h3>Contributions</h3>
Adding a place to the library is super simple. All the different locations are loaded and rendered from a single locations.json file in the root.
<br>

To add your location, fork this repository, add the locations name, address, a brief description, its category (see category breakdown) and a website link( if applicable) to the end of the json file and submit a pull request. 
<br>
 Don't forget the commas!
 <h4>Category Breakdown:</h4>
 <ul>
    <li>Arts & Culture: Museums, Art galleries, Theatres, Shows</li>
    <li>Beaches</li>
    <li>Dining: Restaurants, Food Trucks,</li>
    <li>Festivals</li>
    <li>Nature & Hiking:  Hiking trails, Nature and Game Reserves</li>
    <li>Parks & Recreation: Parks, Physical activities eg; Rollerblading, Cycling</li>
    <li>Shopping</li>
</ul>
<br>
<pre>
    <code>
        [
            {
            "name": "Iziko Museum",
            "address": "71 Wale Street, Cape Town, Western Cape",
            "type": "Arts & Culture",
            "description": "The Iziko Museums of Cape Town — an amalgamation of 12 national museums located near the Cape Town city centre. Iziko museums spheres – natural history, social history and arts.",
            "website": "https://www.iziko.org.za/",
            },
         ]

</code>
</pre>



NOTE - Please keep location submissions and bug fixes in separate PRs.
