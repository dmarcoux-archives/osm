# <a href="https://github.com/dmarcoux/osm">dmarcoux/osm</a>

Experimenting with OpenStreetMap and Open Data.

### Live Demo

- Verschenken statt Wegwerfen with
  [OpenLayers](https://dmarcoux.github.io/osm/verschenken_statt_wegwerfen_openlayers/) or
  [Leaflet](https://dmarcoux.github.io/osm/verschenken_statt_wegwerfen_leaflet/)
  from [Berlin Open Data](http://daten.berlin.de/datensaetze/verschenken-statt-wegwerfen)
- [Berliner
  Weihnachtsmärkte](https://dmarcoux.github.io/osm/berliner_weihnachtsmaerkte/)
  from [Berlin Open Data](https://daten.berlin.de/datensaetze/berliner-weihnachtsm%C3%A4rkte-0)

### Development

Run a simple HTTP web server:

```
# Ruby 1.9.2+
ruby -run -e httpd . -p 8080

# Python 3
python -m http.server 8080
```

Go to [http://localhost:8080](http://localhost:8080)

Refresh with `CTRL+F5` if the web server caches files.
