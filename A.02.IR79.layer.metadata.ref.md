# A.02.IR79.layer.metadata.ref

**Purpose**: Each View Service layer must refer to a unambiguous metadata record describing the INSPIRE data set visualised in that layer.

**Prerequisites**

* Test for the schema validity of the ServiceMetadata document has been passed.

**Test method**

This test is based in following the link to the data set metadata record, and from within this record finding a back-link pointing to the validated ServiceMetadata document containing the validated layer.

For each [Metadata element](#metadata) for each [Layer](#layer) in the ServiceMetadata document as `metadata`:
* Check that `metadata` contains a non-empty [href attribute](#href_attr) and that it's a valid URL and fetch the document it refers to. Let the value be `href`.
* Check that the fetched document contains is a valid INSPIRE metadata record for a data set at it's root.
* For each [transfer URL](#transfer_url) as `tURL`:
  * Check that `tURL` is a valid URL and fetch the document it refers to.
  * If the returned document is a valid WMTS 1.0.0 ServiceMetadata document, then
    * Check that this document contains a [Layer](#layer) definition with the same [Identifier](#identifier) as the layer being validated
    * Check that the found [Layer](#layer) contains a [Metadata element](#metadata) with a [href attribute](#href_attr) value which equals `href`. Any possible Language URL request parameters must be ignored in the comparison.

At least one matching `href` must be found for each layer.

**Reference(s)**: [TG VS](README.md#ref_TG_VS), Chapter 5.2.3.1

**Test type**: Automated

**Notes**

## Contextual XPath references

The namespace prefixes used as described in [README.md](README.md#namespaces).

Abbreviation                                               |  XPath expression
---------------------------------------------------------- | -------------------------------------------------------------------------
Metadata element <a name="metadata"></a>| ./ows:Metadata
href attribute <a name="href_attr"></a> | @xlink:href
transfer URL <a name="transfer_url"></a> | ./gmd:MD_Metadata/gmd:distributionInfo/gmd:MD_Distribution/gmd:transferOptions/gmd:MD_DigitalTransferOptions/gmd:onLine/gmd:CI_OnlineResource/gmd:linkage/gmd:URL
Layer <a name="layer"></a> | /wmts:Capabilities/wmts:Contents/wmts:Layer
Identifier <a name="identifier"></a> | /wmts:Capabilities/wmts:Contents/wmts:Layer/ows:Identifier
