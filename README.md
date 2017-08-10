![alt text](https://github.com/MITA-Governance-Board/Poplin/blob/master/images/poplin@2x.png)

# Project Poplin

This project, sponsored by the MITA Governance Board created by the Centers for Medicare & Medicaid Services (CMS), seeks to create a reference architecture for Medicaid Management Information Systems (MMIS) to coordinate the mission, vision, and strategy and provide technical specifications that ensure interoperability of modules and information across multi-organization, multi-vendor, and multi-technology systems.

### Poplin - Goals

* Enable fine-grain modularity
* Promote reusability
* Promote interoperability
* Promote innovation
* Support migration path
* Establish trust framework for nationwide information exchange

### Poplin - Principles

* All data and functionality should be exposed through service-oriented APIs
* Standardize service boundaries (e.g. APIs), not internals
    * Focus on data standards and resource definitions
* All service APIs must be designed to be able to expose the interface to the outside world
    * Even if that is not the immediate intent
* Hide internal implementation details through APIs
* Keep APIs technology agnostic
    * It doesn’t matter what technology is used in the service
* Make services simple for consumers 
    * Easier to use and replace
* Must be transparent and reusable
* Must use open standards
* Public APIs shall be documented

### Poplin - Practices

* Services should strive to be small and do one thing well
* Services should be loosely coupled and have bounded contexts
* New service APIs should be RESTful and stateless
    * Migration path and schedule should be provided for legacy SOAP-based interfaces
    * Determine contract definition for RESTful data between services
* API response codes must be correct and meaningful
* Strive toward one data standard and set of resource definitions for each type of data
    * Leveraging ONC Interoperability Standards Advisory
    * Support no more than two
* Smart endpoints and dumb pipes
* Open source with permissible license (e.g. Apache 2.0)

