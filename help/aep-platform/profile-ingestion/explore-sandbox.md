---
title: Access and Explore the AEP Sandbox
description: Access and Explore the AEP Sandbox
---

# Overview

In this article you will learn about:

* The differences between your existing Adobe Exchange Partner sandbox Organization and the shared AEP sandbox.
* Requesting access to the AEP shared sandbox.
* Receiving an email invitation to the AEP shared sandbox.
* Inviting new users in the adminconsole.
* Navigating the AEP UI.

## The Shared AEP Sandbox

* You may have previously been given access to an Adobe Experience Cloud sandbox Org
  * this Org would have your company name in it, for example, if your company is AcmeTech - then you would have an Adobe Experience Cloud sandbox Org named something like "AcmeTech (Exchange Partner)"
  * This Org  would have been provisioned for you to access Adobe solutions such as Adobe Analytics, Adobe Target, Adobe Launch, etc.
  * You, or someone at your company, will have system administration privileges to this Org (the highest level of administration capabilities)
* Your access to AEP will NOT be through your company's Adobe Experience Cloud sandbox Org.
* Your access to AEP will be through a shared Adobe Exchange Org.
* Many other Adobe Exchange companies will be accessing AEP using the same Org
  * Through the AEP Sandbox feature, your data and activities within this shared Org can not be seen or modified by the other companies; each company will have access to a different Sandbox within the shared Org.
* Your administration rights within this shared Org are very limited.
* When you sign into the Adobe Experience Cloud you will see two Orgs within the Org menu - your own sandbox Org and the shared Org.
* When you sign into the AEP UI you should only see the shared Org within the Org menu.

## How to Request Access to the Shared AEP Sandbox

* Submit a [support request](https://adobeexchangeec.zendesk.com/hc/en-us/requests/new) 
* Fill out the form...
  * Your email address
  * Subject:  AEP sandbox request
  * Product: General Provisioning / Sandbox
  * Ticket Type:  Program Support - Exchange Program / Provisioning Request Questions
  * Description: Provide a brief description of the integration use case(s) that require the use of an AEP sandbox
* The invite will be sent to the email address given in the form.
* The invite should be received within 3-X business days after submitting the form.

## Receiving the Email Invitation 

* If you are the primary contact that requested the AEP sandbox access, you will receive an automated email inviting them to "Get Started" with the Adobe Experience Platform.
* You will have some administrative privileges which we'll cover in the next section
* Instead of clicking the Get Started button navigate directly to https://platform.adobe.com (it's faster)
* You'll need to sign in with the Adobe ID that is associated with the email address that received the invite; if this email address is not associated with an Adobe ID you'll need to quickly create one -- see Creating an Adobe ID

## Inviting Additional Users

## Navigating the AEP UI

There are 12 primary areas within the AEP UI. You can navigate to them using the left navigation panel.

* Home - the landing screen
  * Suggests some getting started activities
  * Provides some links to learning content
  * Gives a dashboard view for some of the main AEP objects, such as Schemas, DataSets and Profiles
* Workflows - launch into common workflows for bringing data into your AEP account
* Connections / Sources - manage your sources of data coming into your account
* Connections / Destinations - manage the connections to send data to external systems
* Profiles - view and manage individual customer profiles
* Segments - browse, create and modify customer segments
* Identities - browse, create and modify identity namespaces; these are the types of primary IDs you'll use to uniquely identify a customer
* Models (Data Science) - engage in Data Science activities, including the use of an embedded Jupyter Notebooks environment
* Services (Data Science) - publish data science recipes as services
* Schemas - browse, create and modify schemas; these are the detailed data definitions used to keep your data organized
* DataSets - browse, create and manage DataSets; a DataSet is defined by a Schema and is where your data resides within your AEP account
* Queries - browse, create, modify and use a repository of queries for gaining insights from the data within your DataSets
* Monitoring - view the status of all of the data moving in and out(?) of your account for both Batch and Streaming