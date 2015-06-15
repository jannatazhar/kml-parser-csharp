# Introduction #

0.1 version of parser supports parsing of POINT and LINE coordinates.
**ALL OTHER KML ATTRIBUTES/ELEMENTS ARE IGNORED**


# Details #
**PARSE EXAMPLE**
```
Hashtable kml = kmlparser.KMLDecode(_path_to_kml_);
//all parsed kml points
List<Hashtable> PointsCollection = (List<Hashtable>)kml["POINTS"];
//all parsed kml lines
List<Hashtable> LinesCollection = (List<Hashtable>)kml["LINES"];
```