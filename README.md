<!-- ATTENTION! This file is auto-generated. Do not edit this file directly.
Instead, edit `data.yaml` and re-generate this file as per the README's
instructions -->

# Awesome JSON Schema [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Join Slack](https://img.shields.io/badge/Slack-Join%20Slack-blue.svg?style=flat-square)](https://json-schema.slack.com)
[![OpenCollective](https://img.shields.io/opencollective/all/json-schema?label=OpenCollective&style=flat-square)](https://opencollective.com/json-schema)

> A curated list of awesome JSON Schema resources, tutorials, tools, and more.

JSON Schema is a JSON-based format to annotate and validate JSON documents with
a vibrant community. JSON Schema is defined by a set of IETF specifications and
it is the industry-standard for defining the structure and meaning of JSON
documents.

## Contributing

If you know of a resource discussing JSON Schema or have created a tool or
website about JSON Schema, [open a GitHub
issue](https://github.com/jviotti/awesome-jsonschema/issues/new?assignees=&labels=awesome-link&template=link.md&title=)
or add it directly to
[`data.yaml`](https://github.com/jviotti/awesome-jsonschema/blob/master/data.yaml)
and send a pull request. The README is auto-generated from `data.yaml`. You can
locally render the README as follows:

```sh
npm install
npm start
```

## Table of Contents

- [Official](#official)
- [Getting Started](#getting-started)
- [Vocabularies](#vocabularies)
- [Adoption](#adoption)
- [Articles](#articles)
- [Specifications](#specifications)
- [Books](#books)
- [Courses](#courses)
- [Videos](#videos)
- [Papers](#papers)
- [Tools](#tools)
- [Libraries](#libraries)

## Official

- [GitHub](https://github.com/json-schema-org) - The official GitHub organization of the JSON Schema project
- [GitHub Discussions](https://github.com/json-schema-org/community/discussions) - The discussions page of JSON Schema
- [OpenCollective](https://opencollective.com/json-schema) - The official OpenCollective account of JSON Schema
- [Slack](https://json-schema.org/slack) - The official Slack workspace of JSON Schema
- [StackOverflow](https://stackoverflow.com/questions/tagged/jsonschema) - The JSON Schema tag in StackOverflow
- [Test Suite](https://github.com/json-schema-org/JSON-Schema-Test-Suite) - The official test suite for JSON Schema implementations
- [Twitter](https://twitter.com/jsonschema) - The Twitter account of the JSON Schema project
- [Website](https://json-schema.org) - The official website of the JSON Schema project

## Getting Started

- (2021) [Understanding JSON Schema](https://json-schema.org/understanding-json-schema/) - An in-depth guide to JSON Schema
- (2021) [JSON Schema: Getting Started Step-By-Step](https://json-schema.org/learn/getting-started-step-by-step.html) - A comprehensive introduction to JSON Schema
- (2021) [Introduction to JSON Schema in Java](https://www.baeldung.com/introduction-to-json-schema-in-java) - A short introduction to validating JSON documents with JSON Schema in Java
- (2020) [Validating and documenting JSON with JSON Schema](https://www.mscharhag.com/api-design/json-schema) - An introduction to JSON Schema by example by showing an annotated JSON Schema that validates an example document
- (2020) [JSON Schema Tutorial](https://www.w3resource.com/JSON/JSON-Schema.php) - A tutorial of JSON Schema that discusses validation, documentation and hyperlinking
- (2020) [An introduction to JSON Schema](https://medium.com/swlh/an-introduction-to-json-schema-8eaea643fcda) - An introduction to JSON Schema covering its history, common keywords and how to use the AJV validator
- (2019) [REST API Tutorial: JSON Schema](https://restfulapi.net/json-schema/) - An short introduction to JSON Schema validation
- (2017) [Getting started with JSON Hyper-Schema](https://apisyouwonthate.com/blog/getting-started-with-json-hyper-schema) - An introduction to the Hyper-Schema JSON Schema vocabulary
- (2013) [TutorialsPoint: JSON Schema](https://www.tutorialspoint.com/json/json_schema.htm) - A short introduction to JSON Schema Draft4 validation

## Vocabularies

- [Hyper-Schema 2019-09](https://json-schema.org/draft/2019-09/vocab/hyper-schema) - Keywords to annotate JSON documents with hyperlinks. These hyperlinks include attributes describing how to manipulate and interact with remote resources through hypermedia environments such as HTTP, as well as determining whether the link is usable based on the instance value
- [JSON Schema 2020-12 Applicator](https://json-schema.org/draft/2020-12/vocab/applicator) - Applicator keywords that are recommended for use as the basis of other vocabularies
- [JSON Schema 2020-12 Content](https://json-schema.org/draft/2020-12/vocab/content) - Annotations keywords that indicate that an instance contains non-JSON data encoded in a JSON string
- [JSON Schema 2020-12 Core](https://json-schema.org/draft/2020-12/vocab/core) - Keywords that are either required in order to process any schema or meta-schema, including those split across multiple documents, or exist to reserve keywords for purposes that require guaranteed interoperability
- [JSON Schema 2020-12 Format Annotation](https://json-schema.org/draft/2020-12/vocab/format-annotation) - An annotation keyword defined to allow schema authors to convey semantic information for a fixed subset of values which are accurately described by authoritative resources
- [JSON Schema 2020-12 Format Assertion](https://json-schema.org/draft/2020-12/vocab/format-assertion) - An assertion keyword defined to allow schema authors to convey semantic information for a fixed subset of values which are accurately described by authoritative resources
- [JSON Schema 2020-12 Meta-Data](https://json-schema.org/draft/2020-12/vocab/meta-data) - These general-purpose annotation keywords provide commonly used information for documentation and user interface display purposes
- [JSON Schema 2020-12 Unevaluated](https://json-schema.org/draft/2020-12/vocab/unevaluated) - Keywords that enable schema authors to apply subschemas to array items or object properties that have not been successfully evaluated against any dynamic-scope subschema of any adjacent keywords
- [JSON Schema 2020-12 Validation](https://json-schema.org/draft/2020-12/vocab/validation) - Validation keywords in a schema impose requirements for successful validation of an instance. These keywords are all assertions without any annotation behavior

## Adoption

*Awesome products and companies that adopted JSON Schema. Did we miss any? [Let
us
know!](https://github.com/jviotti/awesome-jsonschema/issues/new?assignees=&labels=awesome-link&template=link.md&title=)*

- [Adobe Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-65/forms/adaptive-forms-advanced-authoring/adaptive-form-json-schema-form-model.html?lang=en) - The Adobe Experience Manager content management solution for building websites, mobile apps and forms supports creating adaptative forms using JSON Schema
- [Amazon EventBridge Schema Registry](https://aws.amazon.com/about-aws/whats-new/2020/09/amazon-eventbridge-schema-registry-announces-support-for-json-schema/) - Amazon EventBridge Schema Registry has support for JSON Schema, allowing customers to validate, annotate, and manipulate JSON documents conforming to JSON Schema Draft 4 specification
- [Apiary](https://help.apiary.io/api_101/json-schema/) - Apiary&#x27;s interactive documentation is able to render JSON Schema documents associated with payloads
- [Assertible](https://assertible.com/json-schema-validation) - Assertible provides a free-to-use API to validate a JSON document against a JSON Schema and a service to test and monitor web services using JSON Schema
- [Axway API Gateway](https://docs.axway.com/bundle/APIGateway_762_PolicyDevFilterReference_allOS_en_HTML5/page/Content/PolicyDevTopics/content_schema_json.htm) - The API Gateway can check that JavaScript Object Notation (JSON) messages conform to the format expected by a web service by validating requests against a specified JSON schema
- [Cloudflare](https://blog.cloudflare.com/cloudflares-json-powered-documentation-generator/) - The Cloudflare makes use of JSON Schema and Hyper Schema to keep track of their API endpoints
- [Cloudflare Terraform](https://www.infoq.com/news/2021/04/cloudflare-terraform/) - The Cloudflare Terraform provider comes with a tool to generate Terraform configuration from existing Cloudflare resources that uses JSON Schema to map data between both technologies
- [Confluent Schema Registry](https://docs.confluent.io/platform/current/schema-registry/serdes-develop/serdes-json.html) - JSON Schema can be configured with the Apache Kafka Java client and console tools to fail if the payload is not valid for the given schema
- [Contentstack](https://www.contentstack.com/docs/developers/create-content-types/json-schema-for-creating-a-content-type/) - The Contentstack CMS platform supports creating content types using JSON Schema
- [Decisions](https://documentation.decisions.com/docs/create-types-json-schema) - The Decisions rules-driven business process automation platform support using JSON Schema to generate JSON deserializers
- [DocSpring](https://docspring.com/docs/api/get_template_schema.html) - The DocSpring service to automatically fill out PDF forms supports generating JSON Schema definitions for user-created templates
- [Drupal Patternkit](https://www.drupal.org/project/patternkit) - The Drupal Patternkit module uses JSON Schema to define pattern templates
- [Form.io](https://www.form.io/article/angular-json-schema-form-builder) - The Form.io online web form generator supports generating Angular.js forms using JSON Schema
- [Genomic Data Commons](https://gdc.cancer.gov/developers/gdc-data-model) - The Genomic Data Commons data model is defined using JSON Schema
- [Hackolade](https://hackolade.com/help/JSONSchema.html) - The Hackolade data modelling service supports defining entities using JSON Schema
- [Heroku](https://blog.heroku.com/json_schema_for_heroku_platform_api) - Heroku makes use of JSON Schema to publish machine-readable schema definitions for their public APIs
- [Human Cell Atlas](https://data.humancellatlas.org/metadata/structure) - The open data generated by the Human Cell Atlas describes metadata structure using JSON Schema
- [IBM App Connect](https://www.ibm.com/docs/en/app-connect/11.0.0?topic=schema-json-requirements-message-maps) - The Graphical Data Mapping editor can be used to create and transform JSON messages with the data model defined from a JSON schema
- [Informatica](https://docs.informatica.com/data-integration/b2b-data-transformation/10-2-2/user-guide/wizard-input-and-output-formats/json/sample-json-schema.html) - The Informatica data management platform supports creating auto-generated data processor transformations using JSON Schema
- [JSON:API](https://github.com/json-api/json-api/blob/a0296352b6eb57a4ea3eb08a1332e311f78adafa/schema) - The JSON:API 1.0 and later specifications for building APIs in JSON use JSON Schema to define JSON:API responses
- [JamF](https://docs.jamf.com/technical-papers/jamf-pro/json-schema/10.26.0/Understanding_the_Structure_of_a_JSON_Schema_Manifest.html) - The JamF Apple enterprise management service supports creating app manifests using JSON Schema
- [JetBrains](https://www.jetbrains.com/help/objc/json.html) - The suite of JetBrains programming editors supports JSON code-completion based on JSON Schema
- [KrakenD](https://www.krakend.io/docs/endpoints/json-schema/) - KrakenD endpoints receiving a JSON object in its body can apply automatic validations using the JSON Schema vocabulary before the content passes to the backends
- [Lightblue.io](https://docs.lightblue.io/standards/json_schema.html) - The Lightblue document based data access layer framework uses JSON Schema to define certain file resources in the project
- [Linux](https://www.kernel.org/doc/html/latest/devicetree/bindings/writing-schema.html) - The Linux kernel uses JSON Schema to define Devicetree bindings
- [MongoDB](https://docs.mongodb.com/manual/reference/operator/query/jsonSchema/) - MongoDB 3.6 and later support JSON Schema for querying data and defining collection constraints
- [Mozilla Data Pipeline](https://docs.telemetry.mozilla.org/concepts/pipeline/schemas.html) - Mozilla Data Pipeline uses JSON Schema to define telemetry data ingested from Mozilla products and logs from various services
- [MuleSoft](https://docs.mulesoft.com/json-module/2.1/json-schema-validation) - The MuleSoft integration framework supports validating a JSON document against a JSON Schema
- [MySQL](https://dev.mysql.com/doc/refman/8.0/en/json-validation-functions.html) - MySQL 8.0.17 and later support table constraints to validate a JSON document against a JSON Schema
- [Nakadi](https://nakadi.io) - The Nakadi open-source distributed event bus supports defining event types with JSON Schema
- [Open Policy Agent (OPA)](https://blog.openpolicyagent.org/enhanced-type-checking-for-opa-with-json-schema-annotations-826acb0f575) - The OPA policy-based control platform 0.27.0 and newer support statically type-checking Rego policy code using JSON Schema
- [Ory Kratos](https://www.ory.sh/kratos/docs/reference/json-schema-json-paths/) - The Ory Kratos identity &amp; user management product relies on JSON Schema from configuration validation, documentation generation for defining identity schemas
- [Postman](https://learning.postman.com/docs/writing-scripts/script-references/test-examples/) - The Postman API platform supports running JSON Schema validation in API tests
- [RESTHeart](https://restheart.org/docs/json-schema-validation/) - RESTHeart supports MongoDB schema validation to enforce a format to documents: rules-based validation from MongoDB 3.2 and Json Schema validation from MongoDB 3.6
- [Retool](https://docs.retool.com/docs/working-with-json-schema-form) - The Retool no-code platform supports generating web forms using JSON Schema
- [Serverless](https://www.serverless.com/framework/docs/configuration-validation/) - The Serverless framework validates service configuration files using JSON Schema
- [Smart Data Models](https://github.com/smart-data-models) - The Smart Data Models GitHub organization makes use of JSON Schema to describe harmonized Data Models for different Smart Domains
- [Snowplow](https://docs.snowplowanalytics.com/docs/understanding-tracking-design/understanding-schemas-and-validation/) - The Snowplow analytics platform support using JSON Schema to define the structure of the data to collect
- [SpreadJS](https://www.grapecity.com/spreadjs/docs/v13/online/jsonschema.html) - The SpreadJS JavaScript spreadsheet library uses JSON Schema to describe the SpreadJS JSON data format
- [Walmart eCommerce](https://developer.walmart.com/documentation/item-object-v4-0/) - Walmart publishes JSON Schema documents for certain resources that developers can make use of when integratting with the Walmart eCommerce platform
- [nf-core](https://nf-co.re/tools/#pipeline-schema) - The nf-core Nextflow analysis pipelines collection uses JSON Schema to define the parameters used by Nextflow workflows

## Articles

- (2021) [Modeling a file system with JSON Schema](https://json-schema.org/learn/file-system.html) - This example shows a possible JSON Schema representation of file system mount points as represented in an /etc/fstab file
- (2021) [JSON Schema bundling finally formalised](https://json-schema.org/blog/posts/bundling-json-schema-compound-documents) - A close look at bundling and de-referencing JSON Schema documents
- (2020) [Using the JSON Schema standard for scientific applications?](https://cerfacs.fr/coop/json-schema-for-sci-apps) - A discussion on how to use JSON Schema to validate input, add precise documentation, auto-fill missing parts, and create graphical user interfaces in the context of scientific applications
- (2020) [How to Integrate &quot;React JSON Schema Form&quot; into a Redux and Typescript Project](https://www.xtivia.com/blog/how-to-integrate-react-json-schema-form-into-a-redux-and-typescript-project/) - Adding a form using &quot;React JSON Schema Form&quot; and integrating it with Redux and Typescript
- (2020) [Building a No-Code JSON Schema Form Builder with ReactJS](https://www.ginkgobioworks.com/2020/10/08/building-a-no-code-json-schema-form-builder/) - An update on the additional features implemented in the react-json-schema-form-builder open-source JSON Schema form builder project
- (2020) [Azure Pipelines autocomplete in PyCharm, IntelliJ, WebStorm, CLion, and Rider](https://tonybaloney.github.io/posts/azure-pipelines-autocomplete-in-pycharm.html) - Setting up PyCharm, IntelliJ, WebStorm, CLion and Rider to have auto-complete, syntax highlighting and validation support of Azure Pipelines workflows
- (2019) [Saved by the Schema: Using JSON Schema to Document, Test, and Debug APIs](https://blog.heroku.com/json-schema-document-debug-apis) - Learn how Heroku uses JSON Schema to test and document their Platform API, and how it helped them uncover an unexpected bug, rooted in the way the Oj gem parses Big Decimals.
- (2019) [PHP With MySQL](https://elephantdolphin.blogspot.com/2019/07/json-schema-validation-with-mysql-8017.html) - A practical tutorial on expressing JSON Schema table constraints on MySQL
- (2018) [JSON Schema Validator, Generator &amp; Editor Guide](https://stoplight.io/json-guide/) - How the JSON and JSON Schema standards are defined and how to put them to use in your code and in your APIs
- (2018) [JSON Schema Validation &amp; Expressive Query Syntax in MongoDB 3.6](https://www.sitepoint.com/json-schema-validation-expressive-query-syntax-in-mongodb-3-6/) - An in-depth discussion about using JSON Schema to define collection validation on MongoDB
- (2018) [Definitions for filtering properties in JSON schema](https://gist.github.com/LucianBuzzo/5ff9106ce3ae12fb58e4def572b9344d) - An introduction to the problem of using JSON Schema for data filtering and querying purposes

## Specifications

- (2021) [JSON Schema in RDF](https://www.w3.org/2019/wot/json-schema) - This document introduces an RDF vocabulary for JSON schema definitions. This vocabulary provides a stable namespace IRI for JSON schema keywords, as well as simple axioms, defined against schema.org&#x27;s meta-model. Various examples on how to use the vocabulary are also introduced, e.g. to annotate schemas with JSON-LD metadata or to embed schema annotations inside RDF graphs
- (2020) [JSON Schema Core 2020-12](https://json-schema.org/draft/2020-12/json-schema-core.html) - JSON Schema defines the media type &quot;application/schema+json&quot;, a JSON-based format for describing the structure of JSON data. JSON Schema asserts what a JSON document must look like, ways to extract information from it, and how to interact with it. The &quot;application/schema-instance+json&quot; media type provides additional feature-rich integration with &quot;application/schema+json&quot; beyond what can be offered for &quot;application/json&quot; documents
- (2020) [JSON Schema Validation 2020-12](https://json-schema.org/draft/2020-12/json-schema-validation.html) - JSON Schema (application/schema+json) has several purposes, one of which is JSON instance validation. This document specifies a vocabulary for JSON Schema to describe the meaning of JSON documents, provide hints for user interfaces working with JSON data, and to make assertions about what a valid document must look like
- (2020) [Relative JSON Pointers](https://json-schema.org/draft/2020-12/relative-json-pointer.html) - JSON Pointer is a syntax for specifying locations in a JSON document, starting from the document root. This document defines an extension to the JSON Pointer syntax, allowing relative locations from within the document
- (2019) [JSON Hyper-Schema](https://datatracker.ietf.org/doc/html/draft-handrews-json-schema-hyperschema-02) - JSON Schema is a JSON-based format for describing JSON data using various vocabularies.  This document specifies a vocabulary for annotating JSON documents with hyperlinks.  These hyperlinks include attributes describing how to manipulate and interact with remote resources through hypermedia environments such as HTTP, as well as determining whether the link is usable based on the instance value

## Books

- (2017) [JSON at Work](https://www.oreilly.com/library/view/json-at-work/9781491982389/) - A comprehensive overview of the JSON ecosystem, including JSON Schema
- (2014) [Using JSON Schema](https://books.apple.com/us/book/using-json-schema/id903248630) - Learn and Apply JSON Schema by Example, with Javascript (Node.js) and Python Programs

## Courses

- (2017) [JSON Schema - Crash Course for Beginners](https://www.udemy.com/course/json-schema-crash-course-for-beginners/) - Learn JSON &amp; JSON Schema in a Quick 30-40 minutes &amp; use it for the rest of your life for complex projects
- (2017) [Processing and Interchanging JSON Data](https://www.linkedin.com/learning/processing-and-interchanging-json-data) - An in-depth guide to working with JSON and the JSON ecosystem including using JSON Schema for validation purposes

## Videos

- (2021) [JSON Schema Validation in Postman](https://www.youtube.com/watch?v=8BfshV5n6ac) - An tutorial of performing JSON Schema validation in Postman in API tests
- (2021) [Configuring Umbraco on .NET Core - JSON Schema](https://www.youtube.com/watch?v=rpUg-oySw8g) - Configuring Umbraco on .NET Core with JSON Schema-powered autocompletions for appsettings.json using SchemaStore
- (2020) [What is JSON Schema](https://www.youtube.com/watch?v=kK-_gL7Vsc0) - A basic introduction to JSON Schema showing how to auto-generate JSON Schema document from an existing JSON document
- (2019) [What is a JSON Schema? Generate, Modify, and Understand a JSON Schema: Example](https://www.youtube.com/watch?v=hGXxXyJmaUo) - An in-depth introduction to JSON Schema including auto-generating JSON Schema documents using QuickType.io
- (2019) [JSON Schema Validation: How to Validate JSON Schema with Postman?](https://www.youtube.com/watch?v=X072eKtOIio) - An introduction to JSON Schema and how to use it in Postman

## Papers

- (2020) [Challenges in Checking JSON Schema Containment over Evolving Real-World Schemas](https://link.springer.com/chapter/10.1007/978-3-030-65847-2_20) - This paper presents the results of an empirical study of the first generation of tools for checking JSON Schema containment which is applied to a diverse collection of over 230 real-world schemas and their altogether 1k historic versions
- (2020) [JSON Schema Inference Approaches](https://link.springer.com/chapter/10.1007/978-3-030-65847-2_16) - In the context of document NoSQL databases, namely those assuming the JSON data format, this paper focuses on several representatives of the existing inference approaches and provide their thorough comparison
- (2020) [Type Safety with JSON Subschema](https://arxiv.org/abs/1911.12651) - Deciding whether one schema is a subschema of another is non-trivial because of the richness of the JSON Schema specification language. Given a pair of schemas, our approach first canonicalizes and simplifies both schemas, then decides the subschema question on the canonical forms, dispatching simpler subschema queries to type-specific checkers
- (2019) [What Are Real JSON Schemas Like?](https://link.springer.com/chapter/10.1007/978-3-030-34146-6_9) - A first empirical analysis of a curated collection of real-world JSON Schemas. Knowing what real JSON Schemas are like (to borrow from a title of a related study on DTDs) helps practitioners and researchers in making realistic assumptions when building tools for JSON Schema processing
- (2018) [Top-Down Model-Driven Engineering of Web Services from Extended OpenAPI Models](https://ieeexplore.ieee.org/abstract/document/9000020) - Shows how OpenAPI can be extended to add implementation details inside models. These extensions link services to assemblies of components that describe computations. Hence a top-down development process that keeps model and implementation aligned

## Tools

- [JSONSchema.dev](https://jsonschema.dev) - An online JSON Schema validator created by the JSON Schema specification lead

## Libraries

*A collection of open-source libraries to work with JSON Schema official and
third-party vocabularies. Did we miss any? Did you build a JSON Schema tool?
[Let us
know!](https://github.com/jviotti/awesome-jsonschema/issues/new?assignees=&labels=awesome-link&template=link.md&title=)*

- (C++) [RapidJSON](https://rapidjson.org/md_doc_schema.html) - The RapidJSON C++ JSON implementation includes a built-in JSON Schema validator for JSON Schema Draft v4
- (Java) [Eclipse Vert.x](https://vertx.io/docs/vertx-json-schema/java/) - The Eclipse Vert.x JVM reactive application library provides an extendable and asynchronous JSON Schema implementation
- (JavaScript) [Cambria](https://www.inkandswitch.com/cambria.html) - Cambria is a library for implementing schema evolution for JSON and JSON Schema in the context of local-first distributed systems
- (JavaScript) [Formly](https://formly.dev) - The Formly Angular form generator supports generating forms using JSON Schema
- (JavaScript) [chai-json-schema](https://www.chaijs.com/plugins/chai-json-schema/) - Chai plugin with assertions to validate values against JSON Schema v4
- (JavaScript) [json-schema-tools](https://github.com/cloudflare/json-schema-tools) - A collection of utilities created by Cloudflare to work with JSON Schema and Hyper Schema including validation, dereferencing, and documentation generation
- (PHP) [Opis JSON Schema](https://github.com/opis/json-schema) - A JSON Schema validator for PHP
- (Rust) [jsonschema](https://docs.rs/jsonschema/0.8.0/jsonschema/) - A crate for performing fast JSON Schema validation. It is fast due to schema compilation into a validation tree, which reduces runtime costs for working with schema parameters

## Credits

Special thanks to [@kinlane](https://github.com/kinlane) for curating the
initial version of this list.
