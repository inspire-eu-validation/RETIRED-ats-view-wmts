# A.01.IR77.language.param

**Purpose**: The View Service must be able to return the capabilities document in all the languages advertised as supported.

**Prerequisites**

* Test for the existence and validity of the INSPIRE [ExtendedCapabilities](#extendedCapabilities) in ServiceMetadata document has been passed.

**Test method**

For all the [SupportedLanguages](#supportedLanguages) as `language`:
* Make a GetCapabilities request using the `language` string as the value for LANGUAGE request parameter,
* Check that the value of the [ResponseLanguage](#responseLanguage) of each of the returned capabilities documents equals `language`.

**Reference(s)**: [TG VS](README.md#ref_TG_VS), Chapter 5.2.6

**Test type**: Automated

**Notes**


## Contextual XPath references

The namespace prefixes used as described in [README.md](README.md#namespaces).

Abbreviation                                               |  XPath expression
---------------------------------------------------------- | -------------------------------------------------------------------------
ExtendedCapabilities <a name="extendedCapabilities"></a>   | /wms:WMS_Capabilities/Capability/inspire_vs:ExtendedCapabilities[1]
SupportedLanguages <a name="supportedLanguages"></a>   | /wms:WMS_Capabilities/Capability/inspire_vs:ExtendedCapabilities[1]/inspire_common:SupportedLanguages/inspire_common:SupportedLanguage
ResponseLanguage <a name="responseLanguage"></a>   | /wms:WMS_Capabilities/Capability/inspire_vs:ExtendedCapabilities[1]//inspire_common:ResponseLanguage
