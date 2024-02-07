<div align="center" id="top">
  <img src="vues/assets/img/imgAlt.png" alt="Groupie Tracker Search Bar" /><h1>GEOLOCALIZATION</h1>

  &#xa0;

</div>


<p align="center">

![Langages](https://img.shields.io/badge/Go-blue?logo=go&logoColor=white&style=flat-square&labelColor=2b3e50)
![JavaScript](https://img.shields.io/badge/JavaScript-yellow?logo=javascript&logoColor=white&style=flat-square&labelColor=f0db4f)
![CSS](https://img.shields.io/badge/CSS-blue?logo=css3&logoColor=white&style=flat-square&labelColor=1572b6)
![HTML](https://img.shields.io/badge/HTML-orange?logo=html5&logoColor=white&style=flat-square&labelColor=e34c26)
![Repository size](https://img.shields.io/badge/Repository%20size-3.3M-green)
![License](https://img.shields.io/badge/License-ZONE01-blue)

</p>

Status

<h4 align="center">
 🚧  Groupie Tracker Search Bar 🚀 Under construction...  🚧
</h4>

<hr>

<p align="center">
  <a href="#🎯objectives">🎯OBJECTIVES</a> &#xa0; | &#xa0;
  <a href="#📑description">📑DESCRIPTION</a> &#xa0; | &#xa0;
  <a href="#🛠️features">🛠️FEATURES</a> &#xa0; | &#xa0;
  <a href="#🧭how_to_run">🧭HOW_TO_RUN</a> &#xa0; | &#xa0;
  <a href="#🖥️interface">🖥️INTERFACE</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <h3 align="center">AUTEURS👤</h3>

<p align="center">
  <a href="https://learn.zone01dakar.sn/git/lodiouf" target="_blank">lodiouf</a> -
  <a href="https://learn.zone01dakar.sn/git/jgoudiab" target="_blank">jgoudiab</a> -
  <a href="https://learn.zone01dakar.sn/git/mawbdel" target="_blank">mawbdel</a>
</p>
</p>

<br>

## 🎯`OBJECTIVES:` ##
`Groupie Tracker Geolocalization` consists on mapping the different concerts locations of a certain artist/band given by the Client.

we use a process of converting addresses (ex: Germany Mainz) into geographic coordinates (ex: 49,59380 8,15052) which we use to place markers for the concerts locations of a certain artist/band on a map.

## 📑`DESCRIPTION:` ##
Our application integrates a geolocation feature that allows users to discover artists' events and concert venues with their precise location. 

### 🛠️`FEATURES:` ##

Our website integrates an advanced geolocation feature that allows users to discover concerts places. Geolocalization offers the following features:

   - `Precise Location:` Thanks to Geocoding our site can accurately determine concert coordinates from the address, offering personalized results based on their geographic location.

    - `Search place:` Users can search for specific place nearby or in other regions simply by entering the name of the venue in the search bar. The application then suggests relevant results based on the user's location.

    Intuitive navigation: The integration of geolocation into the application facilitates navigation by providing directions .

## 🧭`HOW_TO_RUN`

### 🐾`TO RUN IT:`
_Make sure you're in the right folder, and set to terminal the command below to Start the web server:_
```bash
go run .
```

_Access the web application in your browser_
```bash
🌐 http://localhost:8080
```
### 📇`Summary of Steps` :

1️⃣ Users click on see artists to see a map of all the artists on the platform.

2️⃣ once in the artist interface.

    🔢 find your artist
    🔢 When the user clicks on the button "voir":
        artist information is displayed  with the map with concert place marked.
        click on the map icon to increase the artist concert place
    🔢 The user can repeat the process with new card or a different artist.

   <!-- - 🔢 -->

### 🚷`Error Handling`
The web server handles various error scenarios (errors that have been taken into account and should be avoided ), such as:
- ⚠️ 404 Not Found: Page not found.
- ⚠️ 400 Bad Request: Invalid request.
- ⚠️ 405 Method Not Allowed: HTTP request with an unauthorized method
- ⚠️ 500 Internal Server Error: Server-side errors.

## 🖥️`INTERFACE`

| Interface Principale | Interface Principale |
|:---------------------:|:---------------------:|
| ![Main Interface](/vues/assets/img/homeinterface.png) | ![Main Interface](/vues/assets/img/homeinterface2.png) |


---


<a href="#top">Back to top ⬆️</a>
