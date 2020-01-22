---
title: Query the Unified Profile 
description: Use APIs to query the unified profile
---

# Query the Unified Profile using the Profile API

## Overview

In addition to populating the Customer Profile via real-time and batch ingestion services, partners can access data in the Customer Profile using the Real-time Customer Profile API. Real-time Customer Profile is a generic lookup entity store that merges data across various enterprise data assets and provides access to that data in the form of unified customer profiles and related time series events. 

The Real-time Customer Profile API allows you to programmatically integrate Profile's various functionalities into your service, providing RESTful endpoints for segmentation, edge projections, and more.

This guide contains the steps needed to utilize the Profile API in your integrations with AEP.

General overview of the Real-time Customer Profile can be found [here].(https://www.adobe.io/apis/experienceplatform/home/profile-identity-segmentation/profile-identity-segmentation-services.html#!api-specification/markdown/narrative/technical_overview/unified_profile_architectural_overview/unified_profile_architectural_overview.md)


## Using the API

Be sure to read over the Authenticate to Adobe I/O (help/general/io-integration.md) guide before proceeding. 

### Accessing Profile Data

Profile data can be accessed by making a POST request to the /access/entities endpoint and providing the "entityId" and "entityIdNS" values. 

### Accessing Time Series Events


