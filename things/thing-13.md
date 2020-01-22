---
author: ARDC
description: |
    There are times when metadata created using one standard will need to be transformed
    or crosswalked to another standard so that metadata can been shared between systems.
keywords: 'data, research, research data, australia'
title: 'Walk the crosswalk'
short_title: 'Crosswalks'
thing: 13
categories:
    - "Metadata & more"
---

There are times when metadata created using one schema will need to be
transformed or crosswalked to another schema so that metadata can been
shared between systems.

-   **Getting started:** Start walking the crosswalk for metadata
-   **Learn more:** Hands on with crosswalking Dublin Core
-   **Challenge me:** Hands-on with XSLT


## Getting started
### Why do we need crosswalks?

We learned in Thing 11 that lots of metadata schemas exist to support
different data types and disciplines. There are times when metadata
created in one schema will need to be mapped, transformed, or "crosswalked" to
another so that metadata can been shared between systems.

1. Read the Wikipedia [introduction to
crosswalks](https://en.wikipedia.org/wiki/Schema_crosswalk).

2.  Now we’ll look at an example of a CSIRO metadata record that has been
crosswalked to comply with different metadata standards so it can be
found in various repositories. In separate windows in your browser, take
a look at how the metadata for the 'WAMSI Node 1.1 - Marmion Lagoon CTD and Mooring Measurement Program (July 2007 to May 2008)' has been transformed (or crosswalked) so it complies with different metadata standards and
systems:

-   in [marlin](http://www.marine.csiro.au/marq/edd_search.Browse_Citation?txtSession=8603)
    This record was created to comply with the ISO19115 standard for
    describing geospatial data
-   in the [CSIRO Data Access Portal](http://doi.org/10.4225/08/50F624A9E6D5C "CSIRO data access portal - record")
-   in [Research Data Australia](https://researchdata.ands.org.au/wamsi-node-11-2007-2008/444960/ "Research data Australia record") where it has been cross-walked to [RIF-CS](https://documentation.ands.org.au/display/DOC/About+RIF-CS).

**Consider:** What do you notice about these schemas? Do all three
records provide exactly the same information? Or are there differences?
Why can’t we have one metadata schema to rule them all, and not worry
about having to crosswalk?

## Learn more
### Try your hand at a crosswalk

Let’s map schemas!

Mapping and crosswalking metadata from one schema to another enables
metadata harvesting and sharing between systems.

1. Crosswalks are viewed more easily in a table or spreadsheet format.
Take a look at this mapping of [Dublin Core to DDI](http://www.ddialliance.org/resources/ddi-profiles/dc "Dublin core example").

2. Time to get hands on! Start by choosing any existing metadata record
to work with. Here’s an [example](https://researchdata.ands.org.au/eeg-perception-microtones-information-stimuli).
This will be your “source” record. 
-  Copy the Dublin Core-DDI crosswalk [table](http://www.ddialliance.org/resources/ddi-profiles/dc "DDI crosswalk table")
from \#1 above into a blank document or spreadsheet. 
Can you create a high level metadata mapping from your source record to Dublin Core? (**Hint:** Click on
“Registry View” in the bottom right-hand corner of the footer in the source RDA
record). The Dublin Core Metadata Element Set [explained in more
detail](http://dublincore.org/documents/dces/ "Dublin core set explained in more details").
Don’t worry if you don’t have time to complete the entire record - just
get a feel for the process.

**Consider:** the most confounding issue you encountered in make your
Crosswalk. How did you overcome it?

Do you have a question?  Want to share a resource?
- Post to the [Data Librarians Slack group](https://tiny.cc/data-librarians) to connect with the community.
- Tweet to [@ardc_au](https://twitter.com/ARDC_AU) using \#23things

Go to [Thing 14](thing-14.md) Identifiers and linked data or [All
Things](index.md)

## Challenge me
### An introduction to XSL for crosswalks

Hands on with XML!

This activity will provide an interactive introduction to XSLT using a
free online tool.

Many well-known metadata standards are expressed as XML schemas,
including MARCXML, Dublin Core, MODS, METS, EAD, RIF-CS and others. The
flexible structure of XML makes it possible to convert data from one
metadata standard to another using an XSLT. XSLT (Extensible Stylesheet
Language Transformations) is a language for transforming XML documents
into other XML documents.

1\. Start by having a look at some of the
[crosswalks](http://www.ands.org.au/online-services/rif-cs-schema/crosswalks-transform-your-metadata "Research Data Australia crosswalks")
developed for ingesting records into Research Data Australia.

2\. Go to the free online tool [XSLT Test
Tool](http://xslttest.appspot.com/ "XSLT test tool") free online tool.
Follow the steps in [this
exercise](https://www.ands.org.au/working-with-data/skills/23-research-data-things/all23/thing-13/technical-crosswalk-exercise "23 things crosswalk exercise")
to create, edit and display XML.

**Consider:** do you think experience with XML would be useful in your
workplace?

Do you have a question?  Want to share a resource?
- Post to the [Data Librarians Slack group](https://tiny.cc/data-librarians) to connect with the community.
- Tweet to [@ardc_au](https://twitter.com/ARDC_AU) using \#23things

Go to [Thing 14](thing-14.md) Identifiers and linked data or [All
Things](index.md)

### Metadata & more

    Data is only as valuable as the metadata which describes and
    connects it.

-   [Thing 11](thing-11.md): Metadata
-   [Thing 12](thing-12.md): Vocabularies
-   [Thing 13](thing-13.md): Crosswalks
-   [Thing 14](thing-14.md): Identifiers
