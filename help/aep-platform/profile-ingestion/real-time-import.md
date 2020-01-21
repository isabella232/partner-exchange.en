---
title: Real-time Import
description: Import data to AEP in real-time
---

# Streaming Data to AEP

## Overview

Adobe Experience Platform allows for both profile and experience events to be streamed and available in near real-time. All data sent to AEP via streaming is persisted in the data lake. Data can be streamed to existing data sets or to entirely new data sets via APIs or using Adobe Launch. 

This article will cover the following:

* Streaming to the XDM Individual Profile
* Streaming to the XDM ExperienceEvent
* Using AEP the Launch extension to stream

## Reference Articles

* [Data Ingestion APIs](https://www.adobe.io/apis/experienceplatform/home/api-reference.html#/acpdr/swagger-specs)
* [Streaming Ingestion Overview](https://www.adobe.io/apis/experienceplatform/home/data-ingestion/data-ingestion-services.html#!api-specification/markdown/narrative/technical_overview/streaming_ingest/streaming_ingest_overview.md)
* [Streaming Ingestion Developer Guide](https://www.adobe.io/apis/experienceplatform/home/data-ingestion/data-ingestion-services.html#!api-specification/markdown/narrative/technical_overview/streaming_ingest/getting_started_with_platform_streaming_ingestion.md)
* [Using the AEP Launch Extension](https://docs.adobe.com/content/help/en/launch/using/extensions-ref/adobe-extension/aep-extension/overview.html)


## Create a Data Inlet

In order to stream to AEP you must first create a data inlet. Data inlets will contain attributes such as the source of streaming data and whether or not you are sending in records that belong to the Experience Data Model (XDM) schemas. After creating a data inlet you will be given a unique URL which will be used to stream data into AEP.

Go [here](https://www.adobe.io/apis/experienceplatform/home/data-ingestion/data-ingestion-services.html#!api-specification/markdown/narrative/technical_overview/streaming_ingest/getting_started_with_platform_streaming_ingestion.md#create-a-data-inlet) for instructions on how to create a data inlet via API.

## Stream Profile Data to AEP

Steps:

1. Create an XDM Individual Profile Schema
2. Set the Primary Identity Descriptor for XDM Individual Profile (primary key)
3. Create a dataset for XDM Individual Profile Records
4. Call the Streaming Ingestion APIs to create an XDM Individual Profile Record
5. Retrieve the newly created profile

## Stream Experience Events to AEP

1. Create an XDM ExperienceEvent Schema
2. Set the Primary Identity Descriptor for XDM ExperienceEvent (primary key)
3. Create a dataset for XDM ExperienceEvents
4. Call the Streaming Ingestion APIs to create an XDM ExperienceEvent
5. Retrieve the newly created event

## Using Adobe Launch to Stream to AEP

The Adobe Experience Platform Launch extension provides a way to stream to AEP via Launch. To learn more, see [this guide](https://docs.adobe.com/content/help/en/launch/using/extensions-ref/adobe-extension/aep-extension/overview.html).