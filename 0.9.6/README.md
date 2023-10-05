# LRMoo

This repository keeps track of the [LRMoo](https://cidoc-crm.org/frbroo/) encodings that have been produced by the semi-automated parsing procedure of the Specification docx file for version 0.9.6

## Statistics

The CRMsci specification document for version 0.9.6 includes:
- 16 Class declarations
- 37 Property declarations

# LRMoo implementation in RDF Schema 1.1 (RDFS)

Release date: 05/10/2023

* LRMoo Class definitions in RDFS: 16 (0 interpreted as rdfs:Literal)
* LRMoo forward Property definitions in RDFS: 37
* LRMoo backwards Property definitions in RDFS: 35
* External Referecnces: 36 
  * Cidoc-CRM version 7.1.2
  
## External References

* 'http://www.cidoc-crm.org/cidoc-crm/E1_CRM_Entity' from model: 'CIDOC_CRM_v7.1.2.rdf'
* 'http://www.cidoc-crm.org/cidoc-crm/E5_Event' from model: 'CIDOC_CRM_v7.1.2.rdf'
* 'http://www.cidoc-crm.org/cidoc-crm/E7_Activity' from model: 'CIDOC_CRM_v7.1.2.rdf'
* 'http://www.cidoc-crm.org/cidoc-crm/E13_Attribute_Assignment' from model: 'CIDOC_CRM_v7.1.2.rdf'
* 'http://www.cidoc-crm.org/cidoc-crm/E18_Physical_Thing' from model: 'CIDOC_CRM_v7.1.2.rdf'
* 'http://www.cidoc-crm.org/cidoc-crm/E26_Physical_Feature' from model: 'CIDOC_CRM_v7.1.2.rdf'
* 'http://www.cidoc-crm.org/cidoc-crm/E52_Time-Span' from model: 'CIDOC_CRM_v7.1.2.rdf'
* 'http://www.cidoc-crm.org/cidoc-crm/E53_Place' from model: 'CIDOC_CRM_v7.1.2.rdf'
* 'http://www.cidoc-crm.org/cidoc-crm/E54_Dimension' from model: 'CIDOC_CRM_v7.1.2.rdf'
* 'http://www.cidoc-crm.org/cidoc-crm/E55_Type' from model: 'CIDOC_CRM_v7.1.2.rdf'
* 'http://www.cidoc-crm.org/cidoc-crm/E63_Beginning_of_Existence' from model: 'CIDOC_CRM_v7.1.2.rdf'
* 'http://www.cidoc-crm.org/cidoc-crm/E70_Thing' from model: 'CIDOC_CRM_v7.1.2.rdf'
* 'http://www.cidoc-crm.org/cidoc-crm/E92_Spacetime_Volume' from model: 'CIDOC_CRM_v7.1.2.rdf'
* 'http://www.cidoc-crm.org/cidoc-crm/P4_has_time-span' from model 'CIDOC_CRM_v7.1.2.rdf'
* 'http://www.cidoc-crm.org/cidoc-crm/P4i_is_time-span_of' from model 'CIDOC_CRM_v7.1.2.rdf'
* 'http://www.cidoc-crm.org/cidoc-crm/P140_assigned_attribute_to' from model 'CIDOC_CRM_v7.1.2.rdf'
* 'http://www.cidoc-crm.org/cidoc-crm/P140i_was_attributed_by' from model 'CIDOC_CRM_v7.1.2.rdf'
* 'http://www.cidoc-crm.org/cidoc-crm/P141_assigned' from model 'CIDOC_CRM_v7.1.2.rdf'
* 'http://www.cidoc-crm.org/cidoc-crm/P141i_was_assigned_by' from model 'CIDOC_CRM_v7.1.2.rdf'
* 'http://www.cidoc-crm.org/cidoc-crm/P177_assigned_property_of_type' from model 'CIDOC_CRM_v7.1.2.rdf'
* 'http://www.cidoc-crm.org/cidoc-crm/P177i_is_type_of_property_assigned' from model 'CIDOC_CRM_v7.1.2.rdf'

&nbsp;

## RDFS Generation Policies

&nbsp;
 
#### **A. Classes implementation in RDFS**


As specified in [A. CIDOC Classes implementation in RDFS]( https://gitlab.isl.ics.forth.gr/cidoc-crm/cidoc_crm_rdf/-/blob/master/7.1.2/README.md#a-cidoc-classes-implementation-in-rdfs), the CIDOC-CRM model defines classes, that in Triple Stores are typically implemented as primitive values.

LRMoo model does not specify any such class but includes the following references to CIDOC-CRM classes that are implemented as `rdfs:Literal` in Cidoc-CRM version 7.1.2.

- `F12 Nomen. R33 has string: E62 String`

As a result:

> A1. The following properties have defined as range the `rdfs:Literal` instead of the Class defined in the model specification.

- `F12 Nomen. R33 has string: rdfs:Literal`
