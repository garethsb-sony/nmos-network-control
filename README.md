# AMWA IS-06 NMOS Network Control Specification 
This repository contains details of this AMWA IS-06 NMOS Specification. This REST API can be exposed by a network controller. The specification includes APIs to create and manage network flows, and senders/receivers of the flow.

## Getting started

Readers are advised to be familiar with:
* The JT-NM Reference Architecture (http://jt-nm.org/)
* The [overview of Networked Media Open Specifications](https://github.com/AMWA-TV/nmos)

Readers should read the [documentation](docs/) in this repository, starting with the [Overview](docs/1.0.%20Overview.md), and then look at the [APIs](APIs/), which are written in RAML and JSON Schema (if a suitable tool for reading RAML is not available, then [this](APIs/generateHTML) will create HTML versions).

## Releases

It is recommended that the tagged releases are used as a reference for development as opposed to the 'master' or development branches of this repository.

Each version of the specification is available under a v&lt;#MAJOR&gt;.&lt;#MINOR&gt; tag such as 'v1.0'. Once a specification has been released, any updates to its documentation and schemas which do not modify the specification will be made available via a v&lt;#MAJOR&gt;.&lt;#MINOR&gt;.&lt;#UPDATE&gt; tag such as 'v1.0.1'.

## Contents

* README.md -- This file
* [docs/1.0. Overview.md](docs/1.0.%20Overview.md) -- Documentation targeting those implementing APIs and clients. Further topics are covered within the [docs/](docs/) directory
* [APIs/NetworkControlAPI.raml](APIs/NetworkControlAPI.raml) -- Normative specification of the NMOS Network Control API
* [APIs/schemas/](APIs/schemas/) -- JSON schemas used by API specifications
* [APIs/generateHTML](APIs/generateHTML) -- Tool to create HTML browsable version of the API specifications. Requires raml2html (https://github.com/kevinrenskers/raml2html).
* [examples/](examples/) -- Example JSON requests and responses for APIs
* [LICENSE](LICENSE) -- Licenses for software and text documents
* [NOTICE](NOTICE) -- Disclaimer
