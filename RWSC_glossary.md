---
title: RWSC Data Management & Governance Glossary
--- 
  
This glossary is meant to serve as a useful reference.  It is an evergreen document and will be updated and added to as often as necessary. 

<br>

### Table of Contents
[Calibrated Data](#calibrated-data)  
[CARE Principles](#care-principles)  
[Controlled Vocabularies](#controlled-vocabularies)  
[Data Catalog](#data-catalog)  
[Data Documentation](#data-documentation)  
[Data Governance](#data-governance)  
[Data Inventory](#data-inventory)  
[Data License](#data-license)  
[Data Literacy](#data-literacy)  
[Data Management](#data-management)  
[Data Products](#data-products)  
[Data Provenance](#data-provenance)  
[Data Repository](#data-repository)  
[Data Sharing Agreement](#data-sharing-agreement)  
[Data Stewardship](#data-stewardship)  
[Derived Data](#derived-data)  
[DOI](#doi)  
[ERDDAP](#erddap)  
[FAIR Principles](#fair-principles)  
[Knowledge Graph](#knowledge-graph)  
[Metadata](#metadata)  
[Ontology](#ontology)  
[OPeNDAP](#opendap)  
[Open Data Science](#open-data-science)  
[Raw Data](#raw-data)  
[Research Parnership](#research-partnership)  
[Schema](#schema)  
[THREDDS](#thredds)  
[Trusted Intermediary](#trusted-intermediary)  
  
[Other Similar Glossaries](#other-similar-glossaries)  
  
<br>  
  
#### Calibrated Data

Time series data that has been processed using software to apply instrument calibration (to compare acoustic measurements to a known standard). From [PAM Data Mgmt Best Practices](https://rwscollab.github.io/pam-data-mgmt/#deploy).

#### CARE Principles

The CARE Principles for Indigenous Data Governance were developed by the International Indigenous Data Sovereignty Interest Group, part of the Research Data Alliance.They were designed to complement the FAIR data principles and describe key aspects of working with Indigenous communities and cultures and their data, information, and knowledge. The CARE principles are:  Collective benefit, Authority to control, Responsibility, and Ethics.  Published in [Data Science Journal in 2020](http://doi.org/10.5334/dsj-2020-043).

#### Controlled Vocabularies

Collections of terms used to improve the consistency and effectiveness of data entry, storage, retrieval, and interoperability.  Their use removes ambiguity, makes implicit information explicit, and the increases interpretability of the data.  See [NISO Z39.19](www.doi.org/10.3789/ansi.niso.z39.19-2005R2010), and applications such as [MEDIN](https://medin.org.uk/data-standards/controlled-vocabularies).

#### Data Catalog

A persistent, findable, searchable virtual location that stores metadata but not data, and facilitates searching and finding data across multiple data repositories or data storage locations.  

#### Data Documentation

*Noun:* Metadata, READMEs, data dictionaries, and other materials that describe the data and the processes that created the data.  
*Verb:* The process of creating the information that enables the sharing, use and reuse of data and software packages.  

#### Data Governance

The legal structures and policies necessary to insure the desired management of data assets.  This includes structures for how decisions are made about data and how people and processes are expected to behave in relation to the data.

#### Data Inventory

A data inventory is a fully described record of data assets. The inventory records basic information about a data asset including its name, contents, update frequency, use license, owner/maintainer, privacy considerations, data source, and other relevant details.
References: [Bloomberg GovEx](https://summit.codeforamerica.org/breakout-sessions/), [Inventory.data.gov](https://resources.data.gov/resources/inventory-data-gov-guide/)

#### Data License

A legal framework that specifies how data can be accessed, used, and reused.

#### Data Literacy

The knowledge that enables one to understand and communicate about data in an appropriate and meaningful way.  This includes the principles, practices, and methods used throughout the data lifecycle.

#### Data Management

The tasks involved with documenting, maintaining, updating, and publishing data. 

#### Data Products

Models, maps, predictions, analysis results, visualizations and other syntheses that are produced from raw and/or derived data.

#### Data Provenance

The detailed records that keep the history about the data from creation/origin, through transformations and modifications, to products.  Data provenance is transparent, supports trust in the reliability of data, and allows reproducibility.   

#### Data Repository

A persistent, findable, searchable entity that provides infrastructure for long-term storage and access to data.  It should provide for data publication by data holders, as well as access for using/reusing data.  Datasets in a repository are described with metadata that provides essential information about the data and enables efficient search and reuse.  It should also employ unique identifiers, have redundancy, and have clear guidelines for what types of data it accepts.  May or may not be federated with other repositories.  See the [*Encyclopedia of Big Data*](https://doi.org/10.1007/978-3-319-32001-4_59-1).  

#### Data Sharing Agreement

A legal agreement between two or more parties that defines the terms and conditions for sharing non-public data.  

#### Data Stewardship

The actions involved in supporting, promoting, and guiding the use and reuse of data throughout the data lifecycle.

#### Derived Data

Data that have been processed, combined, assembled for the purposes of analysis, visualization, or publication.  Derived data often refers to data resulting from the compilation or assembly of raw data into analysis-ready data to answer a particular question.  Sometimes also referred to as processed data, though that often has more limited meaning. 

#### DOI

Digital Object Identifier.  A unique identifier for a publication, including journal articles, datasets, software packages, etc.

#### ERDDAP

A data server and broker that gives you a simple, consistent way to download subsets of scientific datasets in common file formats.  It is used by organizations around the world to expose their data online.  More information is available from [NOAA](https://coastwatch.pfeg.noaa.gov/erddap/information.html).  

#### FAIR Principles

Findable, Accessible, Interoperable, Reusable.  First published in [Scientific Data in 2016](https://doi.org/10.1038/sdata.2016.18).

#### Knowledge Graph

A digital structure that uses a graph model to formally represent entities (knowledge) and their properties, types, and relationships.  Can include an ontology that allows humans and machines to understand and reason about its contents.  Ref: [Stephen Young on Medium](https://medium.com/@stephenmdyoung/what-is-a-knowledge-graph-69861fbe09fb) 

#### Metadata

Data about the data.  The information that describes the data, both at the file-level (column headings, etc.) and the project level (data creator, geographic location, year, etc.), and enables someone to know enough about the data to be able to reuse it.
*Federal Government Definition:* Metadata is structured information that describes, explains, locates, or otherwise makes it easier to retrieve, use, or manage an information resource (NISO 2004, ISBN: 1-880124-62-9)

#### Ontology

A definition of terms and the relationships between them, often depicted as a flow chart.  Frequently used to align term definitions in order to create a common vocabulary.  Examples include the [Scientific Variables Ontology](https://scientificvariablesontology.org/new_site/index.html) and the [Linked Earth Ontology](http://linked.earth/Ontology/release/index.html).  Definition Ref: [NIH](https://www.nigms.nih.gov/education/Inside-Life-Science/Pages/what-is-an-ontology.aspx)

#### OPeNDAP

Open-source Project for a Network Data Access Protocol is a server that enables sharing data over the internet.  Serves data in ASCII, binary, or NetCDF formats.  Useful information from [NASA](https://www.earthdata.nasa.gov/engage/open-data-services-and-software/api/opendap).  

#### Open Data Science

The tools and practices enabling reproducible, transparent, and inclusive practices for data-intensive science.  Adapted from [Ileana Fenwick’s presentation](https://youtu.be/1IWFIyPzsKY).

#### Raw Data

Data from a sensor, observation, or experiment that has not been cleaned or processed.  This data may be uncalibrated, unpacked and compressed, and not QAQC’d.

#### Research Partnership

A data collaborative structure where a private-sector data holder engages directly with academic or government partners and shares private data in order to generate new analysis and knowledge.  Adapted from the [GovLab](https://raw.githubusercontent.com/GovLab/data-collaboratives/master/source/static/files/existing-practices-report.pdf).

####
Data that are formatted, documented, and shared in ways that make them understandable, interpretable, and obtainable by people other than the original data collector/holder.  See also the [FAIR definition](https://www.go-fair.org/fair-principles/).  

#### Schema

An outline, diagram, or model of the structure of different types of data.  
This can be within a relational database, where the schema describes the tables and fields contained within the database.  Another type is the XML schema, which describes the elements in the XML file using a specific structure.  This structure is frequently used for metadata.

#### THREDDS

The Thematic Real-time Environmental Distributed Data Services (THREDDS) server has features and interfaces that make it easier to explore and use data, both interactively and via automatic clients.  THREDDS services include OPeNDAP and NetCDF Subset Service (NCSS).  User guide from National Center for Environmental Information (NCEI) is [here](https://www.ncei.noaa.gov/access/thredds-user-guide).  

#### Trusted Intermediary

A data collaborative structure where a third-party actor supports collaboration between private-sector data holders and data users in the public sector, academia, NGO sector, and society.  Adapted from the [GovLab](https://raw.githubusercontent.com/GovLab/data-collaboratives/master/source/static/files/existing-practices-report.pdf).
  
  
<br>
 
  
### Other Similar Glossaries

[FAIR Island](https://fairisland.org/toolkit/glossary/)

