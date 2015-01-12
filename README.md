ats-view-wmts
=============

Abstract Test Suite for INSPIRE View Services Technical Guidance WMTS 1.0.0 Profile

References
* [Technical Guidance for the implementation of INSPIRE View Services 3.11](http://inspire.jrc.ec.europa.eu/documents/Network_Services/TechnicalGuidance_ViewServices_v3.11.pdf)
* [Commission Regulation (EC) No 976/2009 of 19 October 2009 implementing Directive 2007/2/EC of the European Parliament and of the Council as regards the Network Services](http://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32009R0976&from=EN)
* [OpenGIS® Web Map Tile Service Implementation Standard version 1.0.0](http://portal.opengeospatial.org/files/?artifact_id=35326)

*Note*: This ATS is in draft stage, none of the tests have an official INSPIRE MIG approval.

This Conformance Class contains the following tests:

| Identifier                                                                                | Origin | Mechanical | Status   |
| ----------------------------------------------------------------------------------------- | ------ | ---------- | -------- |
| [WMTS 1.0.0 All operations: A.3.1.2  Accept HTTP GET and POST transferred operation requests](OGC_07-057r7_A.3.1.2.md) 	      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 All operations: A.3.1.3  Handle KVP-encoded operation requests](OGC_07-057r7_A.3.1.3.md) | OGC     | Yes        | Final    |
| [WMTS 1.0.0 All operations: A.3.1.4  Handle SOAP-encoded operation requests](OGC_07-057r7_A.3.1.4.md) 	        | OGC     | Yes        | Final    |
| [WMTS 1.0.0 All operations: A.3.1.5  Handle HTTP GET RESTful -encoded operation requests](OGC_07-057r7_A.3.1.5.md) 	                    | OGC     | Yes        | Final    |
| [WMTS 1.0.0 All operations: A.3.1.6  KVP and SOAP HTTP response status code](OGC_07-057r7_A.3.1.6.md) 	                    | OGC     | Yes        | Final    |
| [WMTS 1.0.0 GetCapabilities: A.3.2.1  Accept HTTP GET transferred operation requests](OGC_07-057r7_A.3.2.1.md) 	                    | OGC     | Yes        | Final    |
| [WMTS 1.0.0 GetCapabilities: A.3.2.2  GetCapabilities operation response](OGC_07-057r7_A.3.2.2.md) 	                    | OGC     | Yes        | Final    |
| [WMTS 1.0.0 GetCapabilities: A.3.2.3  Version negotiation](OGC_07-057r7_A.3.2.3.md) 	                    | OGC     | Yes        | Final    |
| [WMTS 1.0.0 GetCapabilities: A.3.2.4  Format selection](OGC_07-057r7_A.3.2.4.md) 	                    | OGC     | Yes        | Final    |
| [WMTS 1.0.0 GetCapabilities: A.3.2.5  Handling updateSequence parameter](OGC_07-057r7_A.3.2.5.md) 	                    | OGC     | Yes        | Final    |
| [WMTS 1.0.0 GetCapabilities: A.3.2.6  Section selection](OGC_07-057r7_A.3.2.6.md) 	                    | OGC     | Yes        | Final    |
| [WMTS 1.0.0 ServiceMetadata resource: A.3.3.1 Accept HTTP GET transferred operation requests](OGC_07-057r7_A.3.3.1.md)	                    | OGC     | Yes        | Final    |
| [WMTS 1.0.0 ServiceMetadata response: A.3.4.1 XML well formated](OGC_07-057r7_A.3.4.1.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 ServiceMetadata response: A.3.4.2 XML references the normative schema](OGC_07-057r7_A.3.4.2.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 ServiceMetadata response: A.3.4.3 XML validates against the schema](OGC_07-057r7_A.3.4.3.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 ServiceMetadata response: A.3.4.4 OnLineResource is an only resource prefix](OGC_07-057r7_A.3.4.4.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 ServiceMetadata response: A.3.4.5 XML format for GetCapabilities](OGC_07-057r7_A.3.4.5.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 ServiceMetadata response: A.3.4.6 ows:Constraint GetEncoding](OGC_07-057r7_A.3.4.6.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 ServiceMetadata response: A.3.4.7 ows:Constraint PostEncoding](OGC_07-057r7_A.3.4.7.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 ServiceMetadata response: A.3.4.8 Layer identifiers](OGC_07-057r7_A.3.4.8.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 ServiceMetadata response: A.3.4.9 Layer LegendURL are correct resources](OGC_07-057r7_A.3.4.9.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 ServiceMetadata response: A.3.4.10 Layer LegendURL correct Format](OGC_07-057r7_A.3.4.10.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 ServiceMetadata response: A.3.4.11 Layer LegendURL correct sizes](OGC_07-057r7_A.3.4.11.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 ServiceMetadata response: A.3.4.12 Layer TileMatrixSet is valid](OGC_07-057r7_A.3.4.12.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 ServiceMetadata response: A.3.4.13 TileMatrixSet Identifier](OGC_07-057r7_A.3.4.13.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 ServiceMetadata response: A.3.4.14 TileMatrix Identifier](OGC_07-057r7_A.3.4.14.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 ServiceMetadata response: A.3.4.15 TileMatrixSet ScaleDenominators](OGC_07-057r7_A.3.4.15.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 ServiceMetadata response: A.3.4.16 TileMatrixSet WellKnownScaleSet](OGC_07-057r7_A.3.4.16.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 ServiceMetadata response: A.3.4.17 Theme LayerRef is valid](OGC_07-057r7_A.3.4.17.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 GetTile: A.3.5.1 Layer](OGC_07-057r7_A.3.5.1.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 GetTile: A.3.5.2 ResourceURL template](OGC_07-057r7_A.3.5.2.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 GetTile: A.3.5.3 TileMatrixSet](OGC_07-057r7_A.3.5.3.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 GetTile: A.3.5.4 TileMatrix](OGC_07-057r7_A.3.5.4.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 GetTile: A.3.5.5 TileRow and TileCol](OGC_07-057r7_A.3.5.5.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 GetTile: A.3.5.6 Incorrect Style](OGC_07-057r7_A.3.5.6.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 GetTile: A.3.5.7 Tile incorrect dimension value](OGC_07-057r7_A.3.5.7.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 GetTile: A.3.5.8 Tile dimension default and current](OGC_07-057r7_A.3.5.8.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 GetTile: A.3.5.9 Incorrect Format](OGC_07-057r7_A.3.5.9.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 GetTile: A.3.5.10 Correct Format](OGC_07-057r7_A.3.5.10.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 GetTile: A.3.5.11 Size](OGC_07-057r7_A.3.5.11.md)      | OGC     | Yes        | Final    |
| [WMTS 1.0.0 GetTile: A.3.5.12 Transparent color](OGC_07-057r7_A.3.5.12.md)      | OGC     | Yes        | Final
| [A.01.IR77.language.param](A.01.IR77.language.param.md) | IR | Yes | Missing
| [A.02.IR79.layer.metadata.ref](A.02.IR79.layer.metadata.ref.md) | IR | Yes | Missing
| [A.03.IR82.image.format](A.03.IR82.image.format.md) | IR | Yes | Missing
| [A.04.layer.name](A.04.layer.name.md) | | Yes | Missing
| [A.05.layer.resource.id](A.05.layer.resource.id.md) | | Yes
| [A.06.IR85.layer.title](A.06.IR85.layer.title.md) | | Yes
| [A.07.IR86.layer.abstract](A.07.IR86.layer.abstract.md) | | Yes
| [A.08.IR88.layer.bbox](A.02.IR88.layer.bbox.md) | | Yes
| [A.09.IR90.layer.style](A.02.IR82.layer.style.md) | | Yes

## XML namespace prefixes <a name="namespaces"></a>

The following prefixes are used to refer to the corresponding XML namespaces in all test descriptions:

Prefix     | Namespace
---------- | -------------------------------------------------
