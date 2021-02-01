---
title: Submitting Data Collections
layout: page
---
<a href="{{ site.baseurl }}/assets/pdf/Submitting-Data-Collections.pdf" target="_blank">PDF version</a>

This page provides instructions for citing data by submitting Data Collections to the GUDMAP/RBK Data Explorer.

If you have any questions or feedback, please send them to your consortium's help email: [help@gudmap.org](mailto:help@gudmap.org) or [help@rebuildingakidney.org](mailto:help@rebuildingakidney.org)

We also have the following training materials available:
* [Webinar Slides]({{ site.baseurl }}/assets/slides/GUDMAP-RBK-02082018-data_submission_workshop-collections.pptx)
* [Webinar Replay 02/08/2018 (17:06)](https://youtu.be/OCHq4GwzEFc)
* Tutorial Videos (Coming Soon)

<a name="overview"/>

## Overview

Adding data Collections involves the following steps:

* Make sure you are in the correct Globus authentication group, [kidney-writers]({{ site.baseurl }}/docs/submitting/Submitting-Protocols#1-join-the-kidney-writers-group), and that you are logged in.
* Create the base Collection record.
* For each type of data you would like to include, scroll down to the appropriate section and link the data records.

## What is a Collection for?

* An upcoming publication
    * A collection can be properly cited in the paper
    * Data set citation (based on the [Nature scientific data citation format](http://blogs.nature.com/scientificdata/2016/07/14/data-citations-at-scientific-data))
    
    Example: **McMahon, A. GUDMAP Consortium. https://doi.org/10.25548/BURB-6P44  (2017)**

    * Readers can unambiguously obtain data referred in the paper → **repeatable experiments!** 
* A published publication
    * A collection can refer to the published paper in its description.
    * Readers can unambiguously obtain data referred in the paper → **repeatable experiments!** 
* Collaboration
    * Create a specific set of data to be used for further discussion or collaboration.
<!--
## Permanent ID (DOI)

* Digital Object Identifier (DOI)
    * DOI: 10.25548/BURB-6P44
    * DOI URL: https://doi.org/10.25548/BURB-6P44
* DOI issuance process 
    * The collection metadata (Title, Description, PI, Consortium) is registered with the DOI registry which  means your data set is searchable no matter if the website URL changes.
    * The collection URL (our permalink URL) is registered with the DOI.   
* When is a DOI issued? When 
    * _Require DOI?_ field equals "true"; and 
    * _Curation Status_ field equals "Released"
    -->

<div class="page-break"></div>

## 1. Create the base Collections record

* From the navigation bar, click _Create > Collections_. 

    The `Create Collection Record` form appears in a new browser tab.

    ![Screenshot of the Create Collection Record form]({{ site.baseurl }}/images/submitting-data/create-collection.png)
    
    For a screenshot of the entire form, [click here]({{ site.baseurl }}/images/submitting-data/create-collection-full.png).

* Select the values for each relevant field. The required fields are:
  * _Title_
  * _Description_: Try to give a good description of what the data is related to (ie, "This collection includes the original images for figures in XYZ paper") 
  * _Require DOI?_: Set this to **true** in order to generate a permanent identifier for this collection (Please set this to true for collections related to publications).
  * _Curation Status_: Choose either
    * _In Preparation_ (still drafting), 
    * _PI Review_ (ready for internal approval), or 
    * _Submitted_ (ready for Hub review). Your data will **not** be viewable publicly until approved for _Release_ by the Hub. [For a complete description of the Curation Process, click here.](https://github.com/informatics-isi-edu/gudmap-rbk/wiki/Curation-Workflow)
  * _Principal Investigator_: Choose the name of your project's contact PI.
  * _Data Provider_: Choose your institution.
  * _Consortium_: Make sure you indicate whether this is from the RBK or GUDMAP consortium.
* Click _Submit Data_ (scroll to the top of the page) to save the record. You can come back at any time and click "Edit" in the record header to modify this record.

<div class="page-break"></div>

## 2. Link your data records

Once the base Collection record is created, now you can link the related data. To the right, you'll see links that will take you further down the page to sections for each type of data you can link. 

**If you don't see a section for data you want to include, email [help@gudmap.org](help@gudmap.org) or [help@rebuildingakidney.org](help@rebuildingakidney.org).**

![Screenshot of the Create Collection Record form]({{ site.baseurl }}/images/submitting-data/collections-record-blank.png)

For the full length image of the screen, [click here]({{ site.baseurl }}/images/submitting-data/collection-record-blank-full.png).

* In each relevant section, click `Add` to the right of the section header.

![Screenshot of the Create Collection Record form]({{ site.baseurl }}/images/submitting-data/collection-record-blank-add-if.png)

* Browse or search for the records you want to add and then click the checkbox to select them.

![Screenshot of the Create Collection Record form]({{ site.baseurl }}/images/submitting-data/collection-record-blank-select-if.png)

* Click _Submit_ to link them to the Collection record.

![Screenshot of the Create Collection Record form]({{ site.baseurl }}/images/submitting-data/collection-record-linked-record.png)

* Once you're ready for internal review, change _Curation Status_ to _PI Review_.


<div class="page-break"></div>

## 3. Reviewing and Submitting Data Collections

Here is how a project's PI or designated reviewer can find their project's data with a Curation Status of "In Preparation" or "PI Review"**

* Make sure you are logged in.

* From the navigation bar, click _Search > Collections_.
    
* In the faceting sidebar on the left, scroll to **Curation Status** and choose _PI Review_ and _In Preparation_. Note: Keep in mind that the data submitter may have forgotten to set the Curation Status field, in which case the status would still be _In Preparation_.

* In the faceting sidebar, scroll to **Principal Investigator** and choose your project's PI. Now you should see the data you need to review.

* When your record is approved internally, change _Curation Status_ to _Submitted_ to send it to the Hub (click here for the full [Curation Workflow](https://github.com/informatics-isi-edu/gudmap-rbk/wiki/Curation-Workflow)).


<div class="page-break"></div>

## 4. Deleting Data Collections

Before you can delete the base Collection record, you need to unlink (delete) any data records associated with it.

To delete a data collection record:

* Scroll down the record to the sections for the different data types.

* In each of these sections, unlink the entries by clicking the 'x' icon in the _Actions_ columns.

* Once all of the related records have been unlinked (deleted), then scroll up to the top of the record and click _Delete_.

![Delete button]({{ site.baseurl }}/images/submitting-data/chaise-delete-option.png)