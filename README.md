# ProjNet (for GeoAPI)
This library is an extended port of [ProjNet](http://projnet.codeplex.com)
## .NET Spatial Reference and Projection Engine
Proj.NET performs point-to-point coordinate conversions between geodetic coordinate systems for use in fx. Geographic Information Systems (GIS) or GPS applications. The spatial reference model used adheres to the Simple Features specification.
* Read the [Frequently Asked Questions](https://github.com/NetTopologySuite/ProjNet4GeoAPI/wiki/Frequently-Asked-Questions) for common questions.
* Popular [Well-Known Text](https://github.com/NetTopologySuite/ProjNet4GeoAPI/wiki/Popular-Well-Known-Text-representations-of-Spatial-Reference-Systems) representations for Spatial Reference Systems

### Build status
| Branch | Status |
| --- | --- |
| develop | [![Build Status](https://travis-ci.org/NetTopologySuite/ProjNet4GeoAPI.svg?branch=develop)](https://travis-ci.org/NetTopologySuite/ProjNet4GeoAPI) |
| master | [![Build Status](https://travis-ci.org/NetTopologySuite/ProjNet4GeoAPI.svg?branch=master)](https://travis-ci.org/NetTopologySuite/ProjNet4GeoAPI) |


### Get it from NuGet
* For version 1.*
  `PM> Install-Package ProjNet4GeoAPI`  
  - More information on [NuGet](https://www.nuget.org/packages/ProjNet4GeoAPI)  
* For version 2.*  
  `PM> Install-Package ProjNet`


### Talk...
Join the [![Gitter](https://img.shields.io/gitter/room/TechnologyAdvice/Stardust.svg)](https://gitter.im/NetTopologySuite/ProjNet4GeoAPI) on ProjNet (for GeoAPI).


### Projects using ProjNet(4GeoAPI)
* [SharpMap](https://github.com/SharpMap/SharpMap)

(If your project is missing, there is an edit button up-right)

### Supports:
* Datum transformations
* Geographic, Geocentric, and Projected coordinate systems
* Compatible with Microsoft .NetStandard 2.0
* Converts coordinate systems to/from Well-Known Text (WKT) and to XML

### Projection types currently supported:
* Albers
* Cassini Soldner
* Hotine Oblique Mercator
* Krovak
* Lambert Azimuthal Equal Area
* Lambert Conformal
* Mercator
* Oblique Stereographic
* Polyconic
* Transverse Mercator
