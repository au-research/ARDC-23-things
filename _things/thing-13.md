---
thing: 13
title: 'Walk the crosswalk'
short_title: 'Crosswalks'
description: |
    There are times when metadata created using one standard will need to be transformed
    or crosswalked to another standard so that metadata can been shared between systems.
overview:
 Getting started: start walking the crosswalks for metadata
 Learn more: Hands on with crosswalking Dublin Core
 Challenge me: Hands-on with XSLT
category: "Metadata & more"
---
## Getting started
### Why do we need crosswalks?

We learned in Thing 11 that lots of metadata schemas exist to support
different data types and disciplines. There are times when metadata
created in one schema will need to be transformed or crosswalked to
another so that metadata can been shared between systems and is more
discoverable.

1\. Read the Wikipedia [introduction to
crosswalks.](https://en.wikipedia.org/wiki/Schema_crosswalk)

2.  Now we’ll look at an example of a metadata record that has been
crosswalked to comply with different metadata standards so it can be
found in various repositories. In separate windows in your browser, take
a look at how the metadata for the same record has been transformed (or
crosswalked) so it complies with different metadata standards and
systems.

-   First look at this CSIRO
    [record](http://www.marine.csiro.au/marq/edd_search.Browse_Citation?txtSession=8603)
    in MarLIN. It was created to comply with the ISO19115 standard for
    describing geospatial data
-   This is the same record as it appears in the [CSIRO Data Access
    Portal](http://doi.org/10.4225/08/50F624A9E6D5C "CSIRO data access portal - record")
-   And the same record again as it was crosswalked to the RIF-CS schema
    for [Research Data
    Australia](https://researchdata.ands.org.au/wamsi-node-11-2007-2008/444960/ "Research data Australia record")

**Consider:** What do you notice about these schemas? Do all three
records provide exactly the same information? Or are there differences?
Why can’t we have one metadata schema to rule them all, and not worry
about having to crosswalk?

## Learn more
### Try your hand at a crosswalk

Let’s map schema!

Mapping and crosswalking metadata from one schema to another enables
metadata harvesting and sharing between systems.

1\. Crosswalks are viewed more easily in a table or spreadsheet format.
Take a look at [this
example](http://www.ddialliance.org/resources/ddi-profiles/dc "Dublin core example")
of a Dublin Core&lt;-&gt;DDI crosswalk table.

2\. Time to get hands on! Start by choosing any existing metadata record
to work with. Here’s an
[example](https://researchdata.ands.org.au/eeg-perception-microtones-information-stimuli).
This will be your “source” record. Copy the Dublin Core&lt;-&gt;DDI
crosswalk
[table](http://www.ddialliance.org/resources/ddi-profiles/dc "DDI crosswalk table")
from \#1 above into Word or Excel. Can you create a high level metadata
mapping from your source record to Dublin Core? (Hint: Click on
“Registry View” in the bottom right-hand corner of the example source
record). The Dublin Core Metadata Element Set [explained in more
detail](http://dublincore.org/documents/dces/ "Dublin core set explained in more details").
Don’t worry if you don’t have time to complete the entire record - just
get a feel for the process.

**Consider:** the most confounding issue you encountered in make your
Crosswalk. How did you overcome it?

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
