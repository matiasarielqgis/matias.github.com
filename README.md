<!doctype html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="initial-scale=1,user-scalable=no,maximum-scale=1,width=device-width">
        <meta name="mobile-web-app-capable" content="yes">
        <meta name="apple-mobile-web-app-capable" content="yes">
        <link rel="stylesheet" href="./resources/ol.css">
        <link rel="stylesheet" href="resources/fontawesome-all.min.css">
        <link rel="stylesheet" href="./resources/ol-layerswitcher.css">
        <link rel="stylesheet" href="./resources/qgis2web.css">
<style>
.search-layer {
  top: 100px;
  left: .5em;
}
.ol-touch .search-layer {
  top: 130px;
}
</style>
        <style>
        html, body {
            background-color: #ffffff;
        }
        .ol-control button {
            background-color: #f8f8f8 !important;
            color: #da047a !important;
            border-radius: 0px !important;
        }
        .ol-zoom, .geolocate, .gcd-gl-control .ol-control {
            background-color: rgba(255,255,255,.4) !important;
            padding: 3px !important;
        }
        .ol-scale-line {
            background: none !important;
        }
        .ol-scale-line-inner {
            border: 2px solid #f8f8f8 !important;
            border-top: none !important;
            background: rgba(255, 255, 255, 0.5) !important;
            color: black !important;
        }
        </style>
<style>
.tooltip {
  position: relative;
  background: rgba(0, 0, 0, 0.5);
  border-radius: 4px;
  color: white;
  padding: 4px 8px;
  opacity: 0.7;
  white-space: nowrap;
}
.tooltip-measure {
  opacity: 1;
  font-weight: bold;
}
.tooltip-static {
  background-color: #ffcc33;
  color: black;
  border: 1px solid white;
}
.tooltip-measure:before,
.tooltip-static:before {
  border-top: 6px solid rgba(0, 0, 0, 0.5);
  border-right: 6px solid transparent;
  border-left: 6px solid transparent;
  content: "";
  position: absolute;
  bottom: -6px;
  margin-left: -7px;
  left: 50%;
}
.tooltip-static:before {
  border-top-color: #ffcc33;
}
.measure-control {
  top: 65px;
  left: .5em;
}
.ol-touch .measure-control {
  top: 80px;
}
</style>
        <style>
        #map {
            width: 1006px;
            height: 501px;
        }
        </style>
        <title></title>
    </head>
    <body>
        <div id="map">
            <div id="popup" class="ol-popup">
                <a href="#" id="popup-closer" class="ol-popup-closer"></a>
                <div id="popup-content"></div>
            </div>
        </div>
        <script src="resources/qgis2web_expressions.js"></script>
        <script src="resources/polyfills.js"></script>
        <script src="./resources/functions.js"></script>
        <script src="./resources/ol.js"></script>
        <script src="./resources/ol-layerswitcher.js"></script>
        <script src="layers/DatosPoblacional_1.js"></script><script src="layers/LimitesdeLocalidades_2.js"></script><script src="layers/Peajes_3.js"></script><script src="layers/AutopistaBsAsLaPlata2019_4.js"></script><script src="layers/AutopistaBsAsLaPlata2007_5.js"></script><script src="layers/AutopistaBsAsLaPlata_6.js"></script><script src="layers/Puntosdemedicion_7.js"></script>
        <script src="styles/DatosPoblacional_1_style.js"></script><script src="styles/LimitesdeLocalidades_2_style.js"></script><script src="styles/Peajes_3_style.js"></script><script src="styles/AutopistaBsAsLaPlata2019_4_style.js"></script><script src="styles/AutopistaBsAsLaPlata2007_5_style.js"></script><script src="styles/AutopistaBsAsLaPlata_6_style.js"></script><script src="styles/Puntosdemedicion_7_style.js"></script>
        <script src="./layers/layers.js" type="text/javascript"></script> 
        <script src="./resources/Autolinker.min.js"></script>
        <script src="./resources/qgis2web.js"></script>
    </body>
</html>
