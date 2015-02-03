ats-view-wmts
=============

Abstract Test Suite for INSPIRE View Services Technical Guidance WMTS 1.0.0 Profile

*Note*: This ATS is in draft stage, none of the tests have an official INSPIRE MIG approval.

## External document references

The following abbreviations are used in the test text for referring to external documents:

Abbreviation                     | Document name
-------------------------------- | --------------------------------------------------
TG VS <a name="ref_TG_VS"></a>   | [Technical Guidance for the implementation of INSPIRE View Services 3.11](http://inspire.jrc.ec.europa.eu/documents/Network_Services/TechnicalGuidance_ViewServices_v3.11.pdf)
IR NS <a name="ref_IR_NS"></a>   | [Commission Regulation (EC) No 976/2009 of 19 October 2009 implementing Directive 2007/2/EC of the European Parliament and of the Council as regards the Network Services](http://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32009R0976&from=EN)
IR IOP <a name="ref_IR_IOP"><a/> | [COMMISSION REGULATION (EU) No 1089/2010 of 23 November 2010 implementing Directive 2007/2/EC of the European Parliament and of the Council as regards interoperability of spatial data sets and services](http://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=OJ:L:2010:323:FULL&from=EN)
WMTS <a name="ref_WMTS"></a>     | [OpenGIS® Web Map Tile Service Implementation Standard version 1.0.0](http://portal.opengeospatial.org/files/?artifact_id=35326)
TG MD <a name="ref_TG_MD"></a>   | [Technical Guidance for the implementation of INSPIRE Discovery Services 3.1](http://inspire.ec.europa.eu/documents/Network_Services/TechnicalGuidance_DiscoveryServices_v3.1.pdf)

## XML namespace prefixes <a name="namespaces"></a>

The following prefixes are used to refer to the corresponding XML namespaces in all test descriptions:

Prefix           | Namespace
---------------- | -------------------------------------------------
wmts             | http://www.opengis.net/wmts/1.0
ows              | http://www.opengis.net/ows/1.1
inspire_vs       | http://inspire.ec.europa.eu/schemas/inspire_vs/1.0
inspire_common   | http://inspire.ec.europa.eu/schemas/common/1.0
gmd              | http://www.isotc211.org/2005/gmd
xlink            | http://www.w3.org/1999/xlink


## Tests

This Conformance Class contains the tests in the table below. The test with "WMTS" prefix refer to the OGC WMTS 1.0.0 specification ATS (Annex A).

| Identifier                                                                                | Origin | Mechanical | Status   |
| ----------------------------------------------------------------------------------------- | ------ | ---------- | -------- |
| WMTS.A.3.1.2 Accept HTTP GET and POST transferred operation requests (All operations)     | OGC WMTS 1.0.0     | Yes        | Final    |
| WMTS.A.3.1.3 Handle KVP-encoded operation requests (All operations) | OGC WMTS 1.0.0     | Yes        | Final    |
| WMTS.A.3.1.4 Handle SOAP-encoded operation requests (All operations) 	        | OGC WMTS 1.0.0     | Yes        | Final    |
| WMTS.A.3.1.5 Handle HTTP GET RESTful -encoded operation requests (All operations) 	                    | OGC WMTS 1.0.0     | Yes        | Final    |
| WMTS.A.3.1.6 KVP and SOAP HTTP response status code (All operations)                  | OGC WMTS 1.0.0     | Yes        | Final    |
| WMTS.A.3.2.1 Accept HTTP GET transferred operation requests (GetCapabilities) 	                    | OGC WMTS 1.0.0     | Yes        | Final    |
| WMTS.A.3.2.2  GetCapabilities operation response (GetCapabilities)                   | OGC WMTS 1.0.0     | Yes        | Final    |
| WMTS.A.3.2.3 Version negotiation (GetCapabilities)                   | OGC WMTS 1.0.0     | Yes        | Final    |
| WMTS.A.3.2.4 Format selection (GetCapabilities)	                    | OGC WMTS 1.0.0     | Yes        | Final    |
| WMTS.A.3.2.5 Handling updateSequence parameter (GetCapabilities) 	                    | OGC WMTS 1.0.0     | Yes        | Final    |
| WMTS.A.3.2.6 Section selection (GetCapabilities)                   | OGC  WMTS 1.0.0     | Yes        | Final    |
| WMTS.A.3.3.1 Accept HTTP GET transferred operation requests (ServiceMetadata resource)	                    | OGC WMTS 1.0.0     | Yes        | Final    |
| WMTS.A.3.4.1 XML well formated (ServiceMetadata response)      | OGC WMTS 1.0.0     | Yes        | Final    |
| WMTS.A.3.4.2 XML references the normative schema (ServiceMetadata response)     | OGC WMTS 1.0.0     | Yes        | Final    |
| WMTS.A.3.4.3 XML validates against the schema (ServiceMetadata response)     | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.4.4 OnLineResource is an only resource prefix (ServiceMetadata response)     | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.4.5 XML format for GetCapabilities (ServiceMetadata response)      | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.4.6 ows:Constraint GetEncoding (ServiceMetadata response)]     | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.4.7 ows:Constraint PostEncoding (ServiceMetadata response)     | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.4.8 Layer identifiers (ServiceMetadata response)    | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.4.9 Layer LegendURL are correct resources (ServiceMetadata response)     | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.4.10 Layer LegendURL correct Format (ServiceMetadata response)      | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.4.11 Layer LegendURL correct sizes (ServiceMetadata response)      | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.4.12 Layer TileMatrixSet is valid (ServiceMetadata response)     | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.4.13 TileMatrixSet Identifier (ServiceMetadata response)     | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.4.14 TileMatrix Identifier (ServiceMetadata response)    | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.4.15 TileMatrixSet ScaleDenominators (ServiceMetadata response)      | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.4.16 TileMatrixSet WellKnownScaleSet (ServiceMetadata response)      | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.4.17 Theme LayerRef is valid (ServiceMetadata response)      | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.5.1 Layer (GetTile)      | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.5.2 ResourceURL template (GetTile)     | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.5.3 TileMatrixSet (GetTile)    | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.5.4 TileMatrix (GetTile)     | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.5.5 TileRow and TileCol (GetTile)      | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.5.6 Incorrect Style (GetTile)      | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.5.7 Tile incorrect dimension value (GetTile)     | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.5.8 Tile dimension default and current (GetTile)     | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.5.9 Incorrect Format (GetTile)     | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.5.10 Correct Format (GetTile)      | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.5.11 Size (GetTile)      | OGC WMTS 1.0.0      | Yes        | Final    |
| WMTS.A.3.5.12 Transparent color (GetTile)      | OGC WMTS 1.0.0      | Yes        | Final
| [A.01.IR77.language.param](A.01.IR77.language.param.md) | IR | Yes | Draft
| [A.02.IR79.layer.metadata.ref](A.02.IR79.layer.metadata.ref.md) | IR | Yes | Draft
| [A.03.IR82.image.format](A.03.IR82.image.format.md) | IR | Yes | Draft
| [A.04.layer.name.id](A.04.layer.name.id.md) | IR | Yes | Draft
| [A.05.IR85.layer.title](A.05.IR85.layer.title.md) | IR | Yes | Missing
| [A.06.IR86.layer.abstract](A.06.IR86.layer.abstract.md) | IR | Yes | Missing
| [A.07.IR88.layer.bbox](A.07.IR88.layer.bbox.md) | IR | Yes | Missing
| [A.08.IR90.layer.style](A.08.IR90.layer.style.md) | IR | Yes | Missing
