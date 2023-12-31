# Microsoft Purview In A Day

Microsoft Purview In A Day is a single day event which is all about Data Governance. During the day you'll participate in different presentations, inspiration sessions and hands-on challenges. It provides a good balance between state-of-the-art theory and hands-on experience. The Purview In A Day is all about 2 challenges in which you'll be enabled with relevant concepts, and go deep in a hands-on exercises.

![Mission statement](./assets/dgf-mission-statement.png)

## What is Microsoft Purview?

Microsoft Purview is a unified data governance service that helps you manage and govern your on-premises, multi-cloud and software-as-a-service (SaaS) data. Easily create a holistic, up-to-date map of your data landscape with automated data discovery, sensitive data classification and end-to-end data lineage. Empower data consumers to find valuable, trustworthy data.

## :books: Preface and introduction

To understand the relevance and need of Data Governance, you might need to read below preface, to get better acquainted with the desire and requirements of a business/organisation.

- [Preface: Introduction to Data Governance and Purview](./modules/preface.md)

### Challenge 1

During the first challenge, you'll setup the lab environment in a Azure subscription (see Azure Pass below). We will create the required resources in a `resource group` using a predefined script, and activate the Microsoft Purview service.

Once you're all set, we will create a new collection in Microsoft Purview, and connect to two resources `Microsoft SQL Database` and the `Azure Data Lake`. Once connected, we will start scanning our data sources to extract the technical metadata. We're now able to search, and further document our data model.

In the end you'll learn how to create a `glossary hierarchy`, and import an existing term set. We will assign terms to our data sets.

### Challenge 2

We will start to explore the concept of `classifications`, and we will learn how to create our own custom `scan rule set`. We will automatically classify our `metadata`. Following we wil start to explore the concept of `lineage`, and learn how to use tools like `Data factory` to track lineage.

We will explore the concept of `monitoring` and reporting to understand how purview is scanning our data sources. To finish we will learn how to build a `metamodel`, to create better insights into our data landscape.

## :thinking: Prerequisites

To complete this workshow you'll need to have access to an Azure subscription, and be able to install a custom template.

- An [Azure account](https://azure.microsoft.com/free/), we'll give you a dedicated subscription (Azure Pass) for this workshop.
- If you have no (longer a) free account, you can leverage your Azure Pass in your Azure account. Reach out to one of our coaches, and [register Azure Pass here](https://azure.microsoft.com/en-us/pricing/offers/azure-pass/).

## :books: Challenge 1

Before getting started make sure to setup the [Lab Environment](./challenge1/module00.md) and [create you Microsoft Purview Account](./challenge1/module01.md). This is a prerequisite before working on the challenges!

- [Lab Environment](./challenge1/module00.md)
- [Create a Microsoft Purview Account](./challenge1/module01.md)

Time for a coffee :coffee:? Let's go!

1. [Register & Scan: Azure Data Lake Storage Gen2 ](./challenge1/module02a.md)
2. [Register & Scan: Azure SQL Database](./challenge1/module02b.md)
3. [Search & Browse](./challenge1/module03.md)
4. [Glossary](./challenge1/module04.md)

## :books: Challenge 2

5. [Classifications](./challenge2/module05.md)
6. [Lineage](./challenge2/module06.md)
7. [Monitor](./challenge2/module08.md)
8. [Metamodel](./challenge2/module17.md)

<div align="right"><a href="#microsoft-purview-workshop">↥ back to top</a></div>

## All Modules

If you are done with challenge 1 and challenge 2, feel free to explore all modules from this Purview lab.

- [Integrate with Azure Synapse Analytics](./modules/module09.md)
- [REST API](./modules/module10.md)
- [Securely scan sources using Self-Hosted Integration Runtimes](./modules/module11.md)
- [Managed private endpoints](./modules/module12.md)
- [Process events using Atlas Kafka topics via Event Hubs and NodeJS](./modules/module13.md)
- [Data owner policies (Azure Storage)](./modules/module14.md)
- [Azure SQL Database Lineage Extraction](./modules/module15.md)
