Datamodel ontology
==================
An ontological description of a simple SOFT data model.

TODO: add description of the data model here + fig + ref to ECCOMAS paper

This folder contain three turtle files:
- [entity-soft7.ttl](entity-soft7.ttl) defines the basic datamodel as a standalone turtle file.
- [datamodel.ttl](datamodel.ttl) imports [entity-soft7.ttl](entity-soft7.ttl) and links it to EMMO.
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
