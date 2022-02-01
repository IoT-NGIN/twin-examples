# IoT-NGIN Twin Document Examples

This repository contains early examples of digital twin documents to be used for the Semantic Twin solution developed in the IoT-NGIN project. The Semantic Twin solution is still under development and the examples are intended as indication of the direction of future work and not directly usable as such by others. Please ask for more information from the contact persons.


## List of Examples

### Powertrain
- Found in [powertrain](./powertrain/) folder.
- Describes a powertrain system in a smart factory.
- Written in WoT TD format.
- Contact person Kimmo?

### Roadside camera
- Found in [camera](./camera/) folder.
- Describes a roadside camera located in a sensor unit in Jätkäsaari, Finland.
- Written in Aalto DT document format.
- Contact person Juuso?


## Formats

The formats used in the examples
- W3C WoT TD (World Wide Web Consortium, Web of Things Thing Description)
  * [Link to description](https://www.w3.org/TR/wot-thing-description/)
  * Status: W3C Recommendation
  * Format: Linked Data formats, e.g. JSON-LD, RDF...
  * Well defined but has a high learning curve.
  * Focuses on describing Internet of Things devices in a machine-readable format. Can be extended with other ontologies.
- Aalto DT document
  * [Link to description](https://github.com/AaltoIIC/dt-document)
  * Status: Used by one research group at Aalto University
  * Format: YAML for human readability, JSON for machines. Compatibility with JSON-LD under development.
  * Not strictly defined => allows quick start but is not scalable as such.
  * Focuses on providing useful information for humans while preparing for machine readability through the use of ontologies. Created as an example of what twin description documents could or should look like in terms of usability. 

Other potentially useful formats
- Asset Administration Shell (AAS)
- Digital Twin Definition Language (DTDL)
