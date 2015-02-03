# A04.layer.name

**Purpose**: It must be simple and unambiguous to find out which of the layers provided by the service visualize the INSPIRE spatial data sets given in the Data Specifications for each INSPIRE theme. These layers must be named according to the INSPIRE Harmonized layer names defined in [IR IOP](README.md#ref_IR_IOP)

**Prerequisites**

* Test for the schema validity of the ServiceMetadata document has been passed.

**Test method**

For each [Layer element](#layer) provided by the service according to it's Service Metadata:

* If the [Identifier element](#identifier) starts with one of following case-sensitive strings specified for the INSPIRE themes in [IR IOP](README.md#ref_IR_IOP) (like "AU") and a dot character ".", and it's total length, after trimming white space from the start and end of it, is longer than 3 characters, do the following:
  *  Check that the trimmed string content of the [Identifier](#identifier) matches one the harmonized layer names given in [IR IOP](README.md#ref_IR_IOP) or it's amendments. If there is a match the test passes, if not the test fails.
* else the test passes.

**Reference(s)**: [IR IOP](README.md#ref_IR_IOP), [TG VS](README.md#ref_TG_VS), chapters 5.2.3.3.4.5 and 5.2.3.3.4.6

**Test type**: Automated

**Notes**

It's assumed that there may be layers providing portrayals for both the INSPIRE data sets and non-INSPIRE data sets in the same service. There is however no unambiguous method of finding out if a layer is intended to be such an INSPIRE layer of not. The requirements for using the harmonized layer names can only be imposed on the layers intended by the data provider to be INSPIRE data set portrayals as specified be the Data Specifications for each of the INSPIRE themes, so in a strict sense this requirement cannot be automatically tested.

Still, in the spirit of trying to help the data providers in finding mistakes they have made in configuring the service, it may be advisable to write a test assuming that if the layer identifier starts with one of the two-letter upper-case theme-specific harmonized layer name prefixes, the data provider has intended that the layer provides portrayal of one of the data sets specified for that INSPIRE theme.


## Contextual XPath references

The namespace prefixes used as described in [README.md](README.md#namespaces).

Abbreviation                                               |  XPath expression
---------------------------------------------------------- | -------------------------------------------------------------------------
Layer <a name="layer"></a> | /wmts:Capabilities/wmts:Contents/wmts:Layer
Identifier <a name="idenfier"></a> | /wmts:Capabilities/wmts:Contents/wmts:Layer/ows:Identifier
