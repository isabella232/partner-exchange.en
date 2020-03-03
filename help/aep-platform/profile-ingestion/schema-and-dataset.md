---
title: Create AEP Schema and Dataset
description: Create AEP Schema and Dataset
---

# Create AEP Schema and Dataset

## Create a Schema

### What is a Schema?

A schema is a set of rules that represent and validate the structure and format of data. At a high level, schemas provide an abstract definition of a real-world object (such as a person) and outline what data should be included in each instance of that object (such as first name, last name, birthday, and so on).

See [this documentation](https://www.adobe.io/apis/experienceplatform/home/xdm/xdmservices.html#!api-specification/markdown/narrative/technical_overview/schema_registry/schema_composition/schema_composition.md) for more details.

### Best practices for partners

Partner data should use a separate profile schema vs creating a mix-in for a customer's existing profile schema and experience schema. Partners should use Adobe classes and mix-ins where possible.

* Partners should upload their data using a separate dataset instead of trying to combine their data into an existing data set.
* Partners cannot upload their schemas to the global registry for now.

Build and test with an example schema:

* This example will use the loyalty program profile schema. 
* While the example is a profile schema, event-based schemas can be used using a similar process.
* Schemas can be created in the UI or using the API.
* Run through the following tutorial: [Create a schema tutorial via the UI](https://adobe.ly/38AmxLF)

Learn how to build schemas using the API:

* [Create an I/O integration](https://www.adobe.io/apis/experienceplatform/home/tutorials/alltutorials.html#!api-specification/markdown/narrative/tutorials/authenticate_to_acp_tutorial/authenticate_to_acp_tutorial.md)

* [Create a schema using the Schema Registry API](https://www.adobe.io/apis/experienceplatform/home/tutorials/alltutorials.html#!api-specification/markdown/narrative/tutorials/schema_registry_api_tutorial/schema_registry_api_tutorial.md)

## Create an AEP DataSet

### What is a dataset?

See [this documentation](https://www.adobe.io/apis/experienceplatform/home/data-ingestion/data-ingestion-services.html#!api-specification/markdown/narrative/technical_overview/ingest_architectural_overview/data-ingestion-overview.md) and [this documentation](https://adobe.ly/38kmT8H)

Create a dataset via the UI:

* Click create dataset
* Create from schema
* Click finish
* [Create a dataset using the APIs](https://www.adobe.io/apis/experienceplatform/home/tutorials/alltutorials.html#!api-specification/markdown/narrative/tutorials/creating_a_dataset_tutorial/creating_a_dataset_tutorial.md)

