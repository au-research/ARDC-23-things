---
layout: thing
thing: 11
title: "What's my metadata schema?"
description: |
    **Metadata** is the lifeblood for finding and reusing research
    data. Data is only as valuable as the metadata which describes and
    connects it.
overview:
 - Getting started: What is metadata and what sort of metadata is critical for research data?
 - Learn more: Metadata schemas go formal and become standards
 - Challenge me: Hands on with ANZLIC or XML - You choose!
category: Metadata & more
---
## Getting started
### Metadata: describing research data

Metadata is your best data friend. Metadata is structured information
about a resource that describes characteristics such as content,
quality, format, location and contact information. Creating metadata to
describe research data is very similar to the process for descriptive
cataloguing of library resources.

A metadata schema is a set of metadata elements (or fields) for describing
a particular type of information resource. Numerous metadata schemas
exist for describing research data across different disciplines.
Probably our most familiar metadata schemas are those commonly used in
library catalogues and publication repositories such as MARC and Dublin
Core.

1. Start by reading the ARDC [Metadata](https://ardc.edu.au/resources/working-with-data/metadata/) page to
understand what metadata is and why it is the lifeblood of research data
sharing.

2. Now look closely at this good quality metadata record for research
data: [Long-term variation of surface phytoplankton chlorophyll a in the Southern Ocean during 1965-2002](http://dx.doi.org/doi:10.4225/15/5a384270f2b61). Why
do you think this record is considered ‘high quality’? **Hint:**
consider both the type and quality of information provided. What
metadata included in this record help discovery and reuse of the data?
Look back at the ARDC Metadata page for ideas and think about
previous Things such as licensing and sensitive data.

3. **If you have time:** Sadly, it’s not hard to find examples of low
quality metadata describing research data. Read this short two page
article [Avoiding Data Dumpsters - Toward Equitable and Useful Data
Sharing](https://doi.org/10.1056/NEJMp1605148)(Merson, L., Gaye, O., & Guerin, P. J. (2016). New England Journal of Medicine, 374(25). doi:10.1056/nejmp1605148) on the power
of good quality, schema-compliant metadata.

**Consider:** Why, if metadata is the lifeblood of data discoverability
and reuse, is it often neglected or not richly done when data is
published?

## Learn more
### Metadata schemas and standards

A metadata standard is a schema that has been formally approved and
published, with governance procedures in place to maintain and update
the standard. Examples include [ANZLIC](https://www.anzlic.gov.au) (Australia and New Zealand Spatial
Information Council) and [DDI](https://ddialliance.org) (Document, Discover and Interoperate).

Numerous metadata standards exist and the one chosen to describe
resources such as research data should be appropriate to the project or
discipline.

1. Start by reading this short guide to [Selecting a metadata
standard](https://marinemetadata.org/guides/mdatastandards/standardselect).
Keep this Guide open.

2. Choose one disciplinary standard which sparks your interest from the
UK Digital Curation Centre’s [Directory of Disciplinary
Metadata](http://www.dcc.ac.uk/resources/metadata-standards "DCC Directory of Disciplinary metadata").
Use the Guide above to critique your chosen standard.

**Consider:** other reasons to recommend (or not) the particular
standard you explored in detail.

## Challenge me
### Tools for creating metadata

We couldn't decide on a single activity for Thing 11, so you get to
choose between two!

**Option 1: Hands on with ANZLIC**

-   requires you to install open source ANZMet Lite metadata entry tool
-   Is a hands-on experience in creating an ANZLIC compliant metadata
    record

Various tools exist to support the creation of standards-based metadata. For this activity, we will download the freely available ANZMet Lite metadata entry tool and create an ANZLIC compliant metadata record.

The ANZLIC Metadata Profile is most commonly used to describe geographic (or spatial) resources. It was first published in 2007 and is based on an the International Standard: ISO 19115:2005.

1. **Start by installing** the [ANZMet Lite metadata collection tool](https://www.anzlic.gov.au/resources/metadata#ANZMetLiteTool) (Windows only). Information about the tool, including user guides are also available on this page.

- To install the software click on the link and choose to open or save the file (we chose open)
- Click on setup.exe and ‘run’
- A wizard will guide you through the installation process.

2. Now open your installation of ANZMet Lite and follow the prompts to **create a compliant ANZLIC record**. Start by giving your file a name and browse to the location you wish to save your file to.

3. Create a “New Unlinked Metadata” record - you can either make up the metadata or reuse metadata from a record in Research Data Australia. Stick with the default ‘No’ when asked whether the resource is part of a package and ‘dataset’ as the hierarchy level.

4. **See if you can complete and save a valid ANZLIC record**. The mandatory elements are highlighted and ‘tips’ are available on screen - look for the orange icon.

**Reflect** on your experience using the ANZMet Lite Tool. Are you aware of other free or open source tools for creating for metadata?

**Option 2: Hands on with XML**

-   does not require you to install software
-   Is a hands-on experience with XML and may help prepare you for Thing
    13 (Crosswalks)
    
XML is the language most commonly used for machine to machine transfer of metadata. An understanding of XML is valuable for anyone working ‘under the hood’ with metadata: for example, harvesting or crosswalking metadata.

For this activity we will use Dublin Core. It is a well-used metadata standard across domains and resource types and it forms the basis of many other metadata standards. Let's get started!

1. **Start by creating a ‘simple’ metadata record** in Dublin Core using the free [Dublin Core Generator online tool](http://nsteffel.github.io/dublin_core_generator/) (use the [Simple Generator](http://nsteffel.github.io/dublin_core_generator/generator_nq.html)). Provide some content for at least the first 5 of the 15 Dublin Core elements - you can either make up the metadata or reuse metadata from a record in Research Data Australia. Once you’ve created the metadata record:

-  tick all the output options
-  display the output as XML
-  click 'Generate Metadata!' and
-  copy the XML text

2. Paste the XML text into the left hand pane of the [Online XML Editor](http://www.tutorialspoint.com/online_xml_editor.htm) noting the tree display on the right hand side. Spend a few moments checking out the features of this tool before manually editing your XML to change the author name, add a subject term and add a few other metadata elements. Does the metadata look correct in the tree display?

**Reflect** on XML as a metadata tool.


**Consider** the metadata creation tools we have explored in Thing 11 -
what needs to happen for these tools to have much wider uptake?
