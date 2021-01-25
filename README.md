# GEO77
This is an excercise to create a github repository and a WebMap with HTML and Leaflet.
 
<!DOCTYPE html>
<html>
<head>
 <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css"
   integrity="sha512-xodZBNTC5n17Xt2atTPuE1HxjVMSvLVW9ocqUKLsCC5CXdbqCmblAshOMAS6/keqq/sMZMZ19scR4PsZChSR7A=="
   crossorigin=""/>
 <script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"
   integrity="sha512-XQoYMqMTK8LvdxXYG3nZ448hOEQiglfqkJs1NOQV44cWnUrBc8PkAOcXy20w0vlaXaVUearIOBhiXZ5V3ynxwA=="
   crossorigin=""></script>
</head>
<body>
 <h1>This is a header</h1>
 <p>This is a paragraph of text with a <a href="https://uni-tuebingen.de/">hyperlink</a>.</p>
 <div id="mapid" style="width: 600px; height: 400px; position: relative;"></div>
 <script>
  var mymap = L.map('mapid').setView([48.524, 9.0556]).setZoom(14);
  L.tileLayer('https://{s}.tile.openstreetmap.de/tiles/osmde/{z}/{x}/{y}.png').addTo(mymap);
  var markBota = L.marker([48.523549, 9.057546]).addTo(mymap);
  markBota.bindPopup("<p>This is the Botanical Garden</p>");
 </script>
 <video src=https://www.youtube.com/watch?v=4qn9Au3s4B4&list=PL6rhz47M0x3bmZ4npIx2Dpd1e7DSs3603&index=5 autoplay>
 </video> 
</body>
</html>