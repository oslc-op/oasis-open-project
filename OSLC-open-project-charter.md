<img src="graphics/oslc-logo.png" width="50">

# OSLC Open Project Charter

## 1. Project Name
### 1.1 Full Name
Open Services for Lifecycle Collaboration (OSLC) Open Project


### 1.2 Familiar Name
oslc-op

## 2. Abstract
The Open Services for Lifecycle Collaboration Open Project  (OSLC-OP) is dedicated to the creation of open standards, reference implementations, and test suites for an open and extensible framework that enables loosely coupled integration between independently developed tools. OSLC builds on the WWW Architecture and supporting standards to define a minimal set of capabilities that support integration scenarios though standard services for resource and capability discovery and UI enablement.

## 3. Purpose and Scope
Poorly integrated development tools lead to inefficiencies in solution delivery and lifecycle management processes because of the inability to utilize shared information across supporting tools. Approaches to integration in the past have resulted in brittle, point-to-point integrations that are very difficult to build, scale and maintain. As a result developers and systems engineers are either limited to a single suite of tools from a single vendor, or have to resort to costly manual import/export and data transform mechanisms to share information across tools. 

OSLC-OP is motivated by domain scenarios such as change management, configuration management, embedded systems, requirements management, performance monitoring, quality management, estimation and measurement, asset management, automation, reporting, and reconciliation. It supports core enterprise integrations exemplified by cross-domain scenarios such as Application Lifecycle Management (ALM), Product Lifecycle Management (PLM), and Integrated Service Management (ISM). 

Each domain defines a specific domain ontology that specifies the types of resources in the domain, and their relationships to resources in other domains, along with the standard integration services that are provided by servers and utilized by clients.

These services build on the World Wide Web and Linked Data principles, such as those defined in the W3C Linked Data Platform (LDP), to create a cohesive set of specifications, reference implementations and test suites that can enable products, services and other distributed network resources to interoperate successfully. 


## 4. Business Benefits
OSLC-OP will develop standards, frameworks and test suites for capabilities that enable the development of integrated toolchains supporting development and life-cycle management methods. These capabilities are defined using standard interfaces based on the proven and ubiquitously adopted World Wide Web architecture. They enable minimally coupled integrations of multi-vendor tools into a pipeline supporting loosely organized, distributed teams. Tool vendors develop their tools independently, at different times, on different technical architectures, using different persistence mechanisms and different data formats. At the same time, tool vendors enable integration with their tools through standard capabilities accessed through standard interfaces and data formats that decouple tools and provide users with flexible tool choice.

## 5. Relationship to Other Projects
OSLC-OP builds on the IETF and W3C World Wide Web recommendations. 

HTTP addresses complexity through the REST architecture and methods as the standard mechanism for distributed, loosely coupled APIs for resource operations.

W3C Linked Data Platform (LDP) Reduces variability through Self-describing, semantically rich, linked data resources leveraging HATEOAS  (Hypertext As The Engine Of Application State).

OSLC Core supports adaptive integration through Minimal, discoverable, self-describing capabilities to enable application integration while the OSLC-OP domains define common vocabularies and services that maintain separation of concerns and establish collaborative value streams through integration. 

The OSLC-OP is a reorganization of the existing OSLC Core and Domains Technical Committees that were responsible for developing the OASIS OSLC Standards. The intent of the OSLC-OP is to ground the development of the standards in reference implementations and test suites that help in the development of the standards, and accelerate their adoption and effective use.

## 6. Repositories and Licenses
https://github.com/eclipse/oslc-op (with issues, wiki and project management)

Attribution 4.0 International (CC BY 4.0) for the specifications.

Apache License 2.0 for the source code.


## 7. Initial Contributions from Existing Work

Existing projects, specifications, or repositories that may be contributed to the project:

* OSLC Core Version 3.0. Part 1: Overview (this document). http://docs.oasis-open.org/oslc-core/oslc-core/v3.0/csprd03/part1-overview/oslc-core-v3.0-csprd03-part1-overview.html
* OSLC Core Version 3.0. Part 2: Discovery. http://docs.oasis-open.org/oslc-core/oslc-core/v3.0/csprd03/part2-discovery/* oslc-core-v3.0-csprd03-part2-discovery.html
* OSLC Core Version 3.0. Part 3: Resource Preview. http://docs.oasis-open.org/oslc-core/oslc-core/v3.0/csprd03/part3-resource-preview/oslc-core-v3.0-csprd03-part3-resource-preview.html
* OSLC Core Version 3.0. Part 4: Delegated Dialogs. http://docs.oasis-open.org/oslc-core/oslc-core/v3.0/csprd03/part4-delegated-dialogs/oslc-core-v3.0-csprd03-part4-delegated-dialogs.html
* OSLC Core Version 3.0. Part 5: Attachments. http://docs.oasis-open.org/oslc-core/oslc-core/v3.0/csprd03/part5-attachments/oslc-core-v3.0-csprd03-part5-attachments.html
* OSLC Core Version 3.0. Part 6: Resource Shape. http://docs.oasis-open.org/oslc-core/oslc-core/v3.0/csprd03/part6-resource-shape/oslc-core-v3.0-csprd03-part6-resource-shape.html
* OSLC Core Version 3.0. Part 7: Vocabulary. http://docs.oasis-open.org/oslc-core/oslc-core/v3.0/csprd03/part7-core-vocabulary/oslc-core-v3.0-csprd03-part7-core-vocabulary.html
* OSLC Configuration Management 1.0 Part 1: Overview (this document). oslc-config-mgt.html
* OSLC Configuration Management 1.0 Part 2: Versioned Resources. versioned-resources.html
* OSLC Configuration Management 1.0 Part 3: Configuration Specification. config-resources.html
* OSLC Configuration Management 1.0 Part 4: RDF Vocabulary. config-vocab.html
* OSLC Tracked Resource Set Version 3.0
* OSLC Query Version 3.0
* OSLC Architecture Management Specification 2.1
* OSLC Change Management Version 3.0
* OSLC Requirements Management Version 2.1
* OSLC Asset Management Version 2.1
* OSLC Automation Version 2.1
* OSLC Performance Monitoring Version 2.0
* OSLC Quality Management Version 2.1
* OSLC Reconciliation
* OSLC Estimation and Measurement


## 8. Project Leadership
### 8.1 Project Governing Board

Preliminary:

* IBM - Jim Amsden
* Koneksys - Axel Reichwein
* KTH Royal Institute of Technology - Andrew Berezovskyi
* Siemens AG - Bill Chown

### 8.2 Technical Steering Committee

Preliminary:

* IBM - Jim Amsden
* Koneksys - Axel Reichwein
* KTH Royal Institute of Technology - Andrii Berezovskyi, Jad El-khoury
* Siemens AG - Bill Chown
