---
layout: thing
thing: 13
title: 'Walk the crosswalk'
short_title: 'Crosswalks'
description: |
    There are times when metadata created using one schema will need to be transformed
    or crosswalked to another schema so that metadata can been shared between systems.
overview:
 Getting started: Start walking the crosswalk
 Learn more: Hands-on with mapping to Dublin Core
 Challenge me: Hands-on with XSLT
category: "Metadata & more"
---
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
### Let's map metadata!

Mapping or crosswalking metadata fields from one schema to another enables
metadata harvesting and sharing between systems.

1. Crosswalks are viewed more easily in a table or spreadsheet format.
Take a look at this mapping of [Dublin Core to DDI](http://www.ddialliance.org/resources/ddi-profiles/dc "Dublin core example").

2. Time to get hands on! Start by choosing any existing metadata record
to work with. Here’s an [example](https://researchdata.ands.org.au/eeg-perception-microtones-information-stimuli).
This will be your “source” record. 
-  Copy the Dublin Core-DDI crosswalk [table](http://www.ddialliance.org/resources/ddi-profiles/dc "DDI crosswalk table")
from \#1 above into a blank document or spreadsheet. 
-  Can you create a high level metadata mapping from your source record to Dublin Core? This explains the [Dublin Core Metadata Element Set](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#section-3 "Dublin core set explained in more detail") in more detail. (**Hint:** Click on
“Registry View” in the bottom right-hand corner of the footer in the source RDA
record). 
-  Don’t worry if you don’t have time to complete the entire record - just
get a feel for the process.

**Consider:** the most confounding issue you encountered in mapping metadata from one schema to another. How did you overcome it?

## Challenge me
### An introduction to the technical side of crosswalks

This activity will provide an interactive introduction to XSLT using a
free online tool.

Many well-known metadata standards are expressed as XML schemas,
including MARCXML, Dublin Core, MODS, METS, EAD, RIF-CS and others. The
flexible structure of XML makes it possible to convert data from one
metadata standard to another using XSLT (Extensible Stylesheet
Language Transformations). XSLT is a language for transforming XML documents
into other XML documents (or into HTML), and XSLT files can be considered machine-readable crosswalks.

1. Start by having a look at some of the [machine-readable crosswalk XSLT files](http://www.ands.org.au/online-services/rif-cs-schema/crosswalks-transform-your-metadata "Research Data Australia crosswalks") for ingesting records into Research Data Australia.

2. Go to the free online tool [XSLT Test Tool](http://xslttest.appspot.com/ "XSLT test tool").
Follow these steps to create, edit and display XML:

-  Copy the **XML** below and paste it into the page at http://xslttest.appspot.com in the first edit box:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<books>
    <book>
        <author>Pam Jacobs</author>
        <title>The Book About Pam</title>
        <publisher>Good Books</publisher>
    </book>
    <book>
        <author>Neil Simon</author>
        <title>Neil's Book</title>
        <publisher>Books to Go</publisher>
    </book>
</books>
```

- Next, copy the **XSL** below and paste it into the second edit box:

```xml
<?xml version="1.0" encoding="UTF-8"?>

<xsl:stylesheet version="1.0"
    xmlns:xsl="http://www.w3.org/1999/XSL/Transform">
    
    <xsl:template match="/">
        <html>
            <body>
                <h2>Book Collection</h2>
                <table border="1">
                    <tr bgcolor="#FC99EF">
                        <th>Title</th>
                        <th>Author</th>
                        <th>Publisher</th>
                    </tr>
                    <xsl:for-each select="books/book">
                        <tr>
                            <td><xsl:value-of select="title"/></td>
                            <td><xsl:value-of select="author"/></td>
                            <td><xsl:value-of select="publisher"/></td>
                         </tr>
                    </xsl:for-each>
                </table>
            </body>
        </html>
    </xsl:template>
</xsl:stylesheet>
```

-  Click **Run Transformation** to generate the resultant XML, that looks like:

```xml
<html>
   <body>
      <h2>Book Collection</h2>
      <table border="1">
         <tr bgcolor="#FC99EF">
            <th>Title</th>
            <th>Author</th>
            <th>Publisher</th>
         </tr>
         <tr>
            <td>The Book About Pam</td>
            <td>Pam Jacobs</td>
            <td>Good Books</td>
         </tr>
         <tr>
            <td>Neil's Book</td>
            <td>Neil Simon</td>
            <td>Books to Go</td>
         </tr>
      </table>
   </body>
</html>
```

**Note** the above XML is in fact also **HTML** that constructs a table.

- Preview the table by clicking **Open Result**
- or save the result to a .html file and open it in a browser to see the formatted table!

**Consider:** do you think experience with XML would be useful in your
workplace?
