# Data-envelopes concept
The concept of data-envelopes was first introduced in the 2024 paper ["Data-Envelopes for Cultural Heritage: Going beyond Datasheets"](https://aclanthology.org/2024.legal-1.9/) by Mrinalini Luthra and Maria Eskevich.

A data-envelope has a modular structure to make it easier to find relevant information. This structure consists of five levels:

![Data-envelope levels](data-envelopes-levels.png)

## Level 1: Basic information
Level One of a data-envelope is intended to identify the data-envelope and make it easy to find out more information.

Contents:
* Envelope Title
* Contact person
* Email address
* Creation and publication dates

## Level 2: Basic dataset metadata
Level Two provides basic metadata about the dataset, telling you what the dataset comprises, who made it, where you can find it and under which conditions you can use it. This level makes the data-envelope compatible with the DCAT3 standard.

Contents:
* Snapshot - what is in the dataset?
  * Dataset Title
  * Version
  * Dataset URL
  * Description
  * Topic and genres
  * Geographical and temporal coverage
* Dates - when was the dataset made/published?
  * Creation and publication dates
* Contributors - who was involved in producing the dataset?
  * Publishers
  * Contributors
  * Funding sources
* Distribution - where can you find the dataset?
  * Dataset link
  * DOI
  * Repository
  * Download information
  * Citation information
* Access/licenses - Under what conditions can you use this dataset?
  * Licensing information
  * Access level
  * Access controls
* Dataset version and maintenance - What is the status of the dataset?
  * Version details
  * Maintenance status
  * Maintenance plan
  * Next planned updates
