ats-view-wmts
=============

Abstract Test Suite for INSPIRE View Services Technical Guidance WMTS 1.0.0 Profile

## External document references

The following abbreviations are used in the test text for referring to external documents

Abbreviation                     | Document name
-------------------------------- | --------------------------------------------------
TG VS <a name="ref_TG_VS"></a>   | [Technical Guidance for the implementation of INSPIRE View Services 3.11](http://inspire.jrc.ec.europa.eu/documents/Network_Services/TechnicalGuidance_ViewServices_v3.11.pdf)
IR NS <a name="ref_IR_NS"></a>   | [Commission Regulation (EC) No 976/2009 of 19 October 2009 implementing Directive 2007/2/EC of the European Parliament and of the Council as regards the Network Services](http://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32009R0976&from=EN)
WMTS <a name="ref_WMTS"></a>     | [OpenGIS® Web Map Tile Service Implementation Standard version 1.0.0](http://portal.opengeospatial.org/files/?artifact_id=35326)

*Note*: This ATS is in draft stage, none of the tests have an official INSPIRE MIG approval.

This Conformance Class contains the following tests:

| Identifier                                                                                | Origin | Mechanical | Status   |
| ----------------------------------------------------------------------------------------- | ------ | ---------- | -------- |
| [WMTS.A.3.1.2 Accept HTTP GET and POST transferred operation requests (All operations)](OGC_07-057r7_A.3.1.2.md) 	      | OGC WMTS 1.0.0     | Yes        | Final    |
| [WMTS.A.3.1.3 Handle KVP-encoded operation requests (All operations)](OGC_07-057r7_A.3.1.3.md) | OGC WMTS 1.0.0     | Yes        | Final    |
| [WMTS.A.3.1.4 Handle SOAP-encoded operation requests (All operations)](OGC_07-057r7_A.3.1.4.md) 	        | OGC WMTS 1.0.0     | Yes        | Final    |
| [WMTS.A.3.1.5 Handle HTTP GET RESTful -encoded operation requests (All operations)](OGC_07-057r7_A.3.1.5.md) 	                    | OGC WMTS 1.0.0     | Yes        | Final    |
| [WMTS.A.3.1.6 KVP and SOAP HTTP response status code (All operations)](OGC_07-057r7_A.3.1.6.md) 	                    | OGC WMTS 1.0.0     | Yes        | Final    |
| [WMTS.A.3.2.1 Accept HTTP GET transferred operation requests (GetCapabilities)](OGC_07-057r7_A.3.2.1.md) 	                    | OGC WMTS 1.0.0     | Yes        | Final    |
| [WMTS.A.3.2.2  GetCapabilities operation response (GetCapabilities)](OGC_07-057r7_A.3.2.2.md) 	                    | OGC WMTS 1.0.0     | Yes        | Final    |
| [WMTS.A.3.2.3 Version negotiation (GetCapabilities)](OGC_07-057r7_A.3.2.3.md) 	                    | OGC WMTS 1.0.0     | Yes        | Final    |
| [WMTS.A.3.2.4 Format selection (GetCapabilities)](OGC_07-057r7_A.3.2.4.md) 	                    | OGC WMTS 1.0.0     | Yes        | Final    |
| [WMTS.A.3.2.5 Handling updateSequence parameter (GetCapabilities)](OGC_07-057r7_A.3.2.5.md) 	                    | OGC WMTS 1.0.0     | Yes        | Final    |
| [WMTS.A.3.2.6 Section selection (GetCapabilities)](OGC_07-057r7_A.3.2.6.md) 	                    | OGC  WMTS 1.0.0     | Yes        | Final    |
| [WMTS.A.3.3.1 Accept HTTP GET transferred operation requests (ServiceMetadata resource)](OGC_07-057r7_A.3.3.1.md)	                    | OGC WMTS 1.0.0     | Yes        | Final    |
| [WMTS.A.3.4.1 XML well formated (ServiceMetadata response)](OGC_07-057r7_A.3.4.1.md)      | OGC WMTS 1.0.0     | Yes        | Final    |
| [WMTS.A.3.4.2 XML references the normative schema (ServiceMetadata response)](OGC_07-057r7_A.3.4.2.md)      | OGC WMTS 1.0.0     | Yes        | Final    |
| [WMTS.A.3.4.3 XML validates against the schema (ServiceMetadata response)](OGC_07-057r7_A.3.4.3.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.4.4 OnLineResource is an only resource prefix (ServiceMetadata response)](OGC_07-057r7_A.3.4.4.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.4.5 XML format for GetCapabilities (ServiceMetadata response)](OGC_07-057r7_A.3.4.5.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.4.6 ows:Constraint GetEncoding (ServiceMetadata response)](OGC_07-057r7_A.3.4.6.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.4.7 ows:Constraint PostEncoding (ServiceMetadata response)](OGC_07-057r7_A.3.4.7.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.4.8 Layer identifiers (ServiceMetadata response)](OGC_07-057r7_A.3.4.8.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.4.9 Layer LegendURL are correct resources (ServiceMetadata response)](OGC_07-057r7_A.3.4.9.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.4.10 Layer LegendURL correct Format (ServiceMetadata response)](OGC_07-057r7_A.3.4.10.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.4.11 Layer LegendURL correct sizes (ServiceMetadata response)](OGC_07-057r7_A.3.4.11.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.4.12 Layer TileMatrixSet is valid (ServiceMetadata response)](OGC_07-057r7_A.3.4.12.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.4.13 TileMatrixSet Identifier (ServiceMetadata response)](OGC_07-057r7_A.3.4.13.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.4.14 TileMatrix Identifier (ServiceMetadata response)](OGC_07-057r7_A.3.4.14.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.4.15 TileMatrixSet ScaleDenominators (ServiceMetadata response)](OGC_07-057r7_A.3.4.15.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.4.16 TileMatrixSet WellKnownScaleSet (ServiceMetadata response)](OGC_07-057r7_A.3.4.16.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.4.17 Theme LayerRef is valid (ServiceMetadata response)](OGC_07-057r7_A.3.4.17.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.5.1 Layer (GetTile)](OGC_07-057r7_A.3.5.1.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.5.2 ResourceURL template (GetTile)](OGC_07-057r7_A.3.5.2.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.5.3 TileMatrixSet (GetTile)](OGC_07-057r7_A.3.5.3.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.5.4 TileMatrix (GetTile)](OGC_07-057r7_A.3.5.4.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.5.5 TileRow and TileCol (GetTile)](OGC_07-057r7_A.3.5.5.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.5.6 Incorrect Style (GetTile)](OGC_07-057r7_A.3.5.6.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.5.7 Tile incorrect dimension value (GetTile)](OGC_07-057r7_A.3.5.7.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.5.8 Tile dimension default and current (GetTile)](OGC_07-057r7_A.3.5.8.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.5.9 Incorrect Format (GetTile)](OGC_07-057r7_A.3.5.9.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.5.10 Correct Format (GetTile)](OGC_07-057r7_A.3.5.10.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.5.11 Size (GetTile)](OGC_07-057r7_A.3.5.11.md)      | OGC WMTS 1.0.0      | Yes        | Final    |
| [WMTS.A.3.5.12 Transparent color (GetTile)](OGC_07-057r7_A.3.5.12.md)      | OGC WMTS 1.0.0      | Yes        | Final
| [A.01.IR77.language.param](A.01.IR77.language.param.md) | IR | Yes | Draft
| [A.02.IR79.layer.metadata.ref](A.02.IR79.layer.metadata.ref.md) | IR | Yes | Missing
| [A.03.IR82.image.format](A.03.IR82.image.format.md) | IR | Yes | Missing
| [A.04.layer.name](A.04.layer.name.md) | | Yes | Missing
| [A.05.layer.resource.id](A.05.layer.resource.id.md) | | Yes | Missing
| [A.06.IR85.layer.title](A.06.IR85.layer.title.md) | IR | Yes | Missing
| [A.07.IR86.layer.abstract](A.07.IR86.layer.abstract.md) | IR | Yes | Missing
| [A.08.IR88.layer.bbox](A.02.IR88.layer.bbox.md) | IR | Yes | Missing
| [A.09.IR90.layer.style](A.02.IR82.layer.style.md) | IR | Yes | Missing

## XML namespace prefixes <a name="namespaces"></a>

The following prefixes are used to refer to the corresponding XML namespaces in all test descriptions:

Prefix           | Namespace
---------------- | -------------------------------------------------
inspire_vs       | http://inspire.ec.europa.eu/schemas/inspire_vs/1.0
inspire_common   | http://inspire.ec.europa.eu/schemas/common/1.0
