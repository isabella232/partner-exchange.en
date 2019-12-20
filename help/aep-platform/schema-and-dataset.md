---
title: Create your AEP Schema and Dataset
description: Platform Integration - Create your AEP Schema and Dataset
---

# Create your AEP Schema and Dataset

## Create a Schema

### What is a Schema?

A schema is a set of rules that represent and validate the structure and format of data. At a high level, schemas provide an abstract definition of a real-world object (such as a person) and outline what data should be included in each instance of that object (such as first name, last name, birthday, and so on).

Commenting out for now. We don't currently support external links to markdown files

See [this documentation](https://www.adobe.io/apis/experienceplatform/home/xdm/xdmservices.html#!api-specification/markdown/narrative/technical_overview/schema_registry/schema_composition/schema_composition.md) for more details.

### Best practices for partners

Partner data should use a separate profile schema vs creating a mix-in for a customer's existing profile schema and experience schema. The partner should use the our classes and mix-ins where possible.

* Partners should upload their data using a separate dataset instead of trying to combine their data into an existing data set.
* Partners cannot upload their schemas to the global registry for now.

Build and test with an example schema:

* You must have access to a platform sandbox to run through the following tutorial.
* For our example, we'll use a loyalty program profile schema. 
* While the example is a profile schema, you can build event-based schemas using a similar process
* We'll start with the UI method of creating schemas so you can get a feel for it, but eventually you'll probably want to use the API.
* Run through the following tutorial: [Create a schema tutorial via the UI](https://www.adobe.io/apis/experienceplatform/home/tutorials/alltutorials.html#!api-specification/markdown/narrative/tutorials/schema_editor_tutorial/schema_editor_tutorial.md#convert-a-multi-field-object-into-a-data-type)

Learn how to build schemas using the API:

* You must have access to a platform sandbox to run through the following tutorial. 
* [Create an I/O integration](https://www.adobe.io/apis/experienceplatform/home/tutorials/alltutorials.html#!api-specification/markdown/narrative/tutorials/authenticate_to_acp_tutorial/authenticate_to_acp_tutorial.md)

  * Note that in the future, the Exchange App Manager will allow customers to pass you the authentication credentials automatically. See [this documentation](https://adobeexchangeec.zendesk.com/hc/en-us/articles/360026470931-Adobe-I-O-Console-Access-APIs-to-Integrate-with-Experience-Cloud-Products).
  * [Create a schema using the Schema Registry API](https://www.adobe.io/apis/experienceplatform/home/tutorials/alltutorials.html#!api-specification/markdown/narrative/tutorials/schema_registry_api_tutorial/schema_registry_api_tutorial.md)

## Create an AEP DataSet

### What is a dataset?

See [this documentation](https://www.adobe.io/apis/experienceplatform/home/data-ingestion/data-ingestion-services.html#!api-specification/markdown/narrative/technical_overview/ingest_architectural_overview/data-ingestion-overview.md) and this documentation

Create a dataset via the UI:

* Click create dataset
* Create from schema—select a schema that you created earlier
* Click finish
* [Create a dataset using the APIs](https://www.adobe.io/apis/experienceplatform/home/tutorials/alltutorials.html#!api-specification/markdown/narrative/tutorials/creating_a_dataset_tutorial/creating_a_dataset_tutorial.md)
* For now: you have to use the APIs if you want to check the option of "for use in profile". Check the option of for use in profile—you can't change this afterward!
