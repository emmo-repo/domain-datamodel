Datamodel ontology
==================
An ontological description of a simple data model aimed to make
application specific data semantic interoperabel.

The basic idea is that the data model should stay very close to the
way the application repesents its data.  At the same time, the data
model allows easy mapping the elements in the data model (entities,
dimensions and properties) to a globally shared ontology and thereby
enable semantic interoperability.

This ontology only describes the data model.  A set of accompanying
tools is needed in order to achieve actual interoperability in real
applications.


Short description of the data model
-----------------------------------
The data model is shown in the figure below. The basic entity is
called _Entity_, which can represent any self-contained piece of data.
An Entity has an identity as well as a human description and a set of
named _Dimensions_ and _Properties_.

A _Dimension_ simply has a label and a description.

A _Property_ has a label, type, shape, unit and description.

![The data model.](doc/datamodel.png)


References
----------
1. A Practical Approach to Ontology-Based Data Modelling for Semantic Interoperability, https://www.scipedia.com/public/Hagelien_et_al_2021a



Short description of the provided turtle files
----------------------------------------------
- [entity.ttl](entity.ttl) defines the basic datamodel as a standalone turtle file.
- [datamodel.ttl](datamodel.ttl) imports [entity.ttl](entity.ttl) and links it to EMMO.
- [dlitemodel.ttl](dlitemodel.ttl) imports [datamodel.ttl](datamodel.ttl) and adds a few specialisations that are specific to the dlite implementation, like that entities are actually subclasses of objects, etc.


Attributions and credits
------------------------

### Contribruting projects

- [MarketPlace](https://www.the-marketplace-project.eu/);
  Grant Agreement No: 760173
  <img src="https://www.the-marketplace-project.eu/content/dam/iwm/the-marketplace-project/images/MARKETPLACE_LOGO_300dpi.png" width="120">
- [OntoTrans](https://ontotrans.eu/project/);
  Grant Agreement No: 862136
  <img src="https://ontotrans.eu/wp-content/uploads/2020/05/ot_logo_rosa_gro%C3%9F.svg" height="50">
- [OpenModel](https://openmodel.eu/project/);
  Grant Agreement No: 862136
- [VIPCOAT](https://cordis.europa.eu/project/id/952903)
  Grant Agreement No: 952903



### Contributors and contacts

- Thomas Hagelien (Thomas.F.Hagelien(at)sintef.no)
- Jesper Friis (jesper.friis(at)sintef.no)



License
-------
The datamodel ontology is released under the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode) license (CC BY 4.0).
