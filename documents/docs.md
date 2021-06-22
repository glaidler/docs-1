# Documents

## Overview

To allow HA to categorise documents that are uploaded against an Account, there are now the concept of Document Types. An example of a Document Type could be _Insurance Certificate_. Account Document Types are configurable via the Administration area. Each Document Type can have an expiry duration configured against it consisting of a number of days, weeks, months or years.

When a document is uploaded, its Expiry Date is calculated & this is then flagged as and when it becomes expired.

When a user uploads a new Document, you can opt to replace the previous version, allowing you to quickly see the current version of a given Document Type as well as historical versions.

We've also integrated this into the ability to send docs to a docs tracking mailbox. By specifying a "Mailbox suffix" to the Document Type, you can set up different mailboxes for each Document Type. For instance setting up a Document Type of "Insurance Certificate" with a mailbox suffix of _insurance_ would mean that any attachments sent to **docs-insurance@xxxxxxxx.harbourassist.com** will be attached to the account with a Document Type of _Insurance_.

## Creating a Document Type

From the _Home_ page select _Administration_.

![image-20200817151505465](../.gitbook/assets/image-20200817151505465.png)

Then select _Document Types_.

![image-20200817151608535](../.gitbook/assets/image-20200817151608535.png)

Click to create a _New_ Document Type.

![image-20200817151854260](../.gitbook/assets/image-20200817151854260.png)

Give the Document Type a name and complete the _Expiry Units_ \(using the dropdown options\) and _Interval_ if these are required. Then click _Save_.

![image-20200817152151695](../.gitbook/assets/image-20200817152151695.png)

Now you can add the _Mailbox Suffix_ if you wish \(see Overview above for details\).

![image-20200817155204848](../.gitbook/assets/image-20200817155204848.png)

## Uploading a Document to an Account

To upload a _Document_ to an Account, select the _Docs_ tab.

![image-20200817160905960](../.gitbook/assets/image-20200817160905960.png)

Then click _New_.

![image-20200817162449055](../.gitbook/assets/image-20200817162449055.png)

Complete the following details on the pop-up screen:-

* Document Name \(leave blank if you wish it to default to the file name of the document you are uploading\),
* Document Type - select from the dropdown options,
* Expiry Date - if relevant for this Document Type
* Current Version - should this show on the Docs page as the current document of this Document Type?
* Replace Old Version - if ticked all previous versions of this Document Type will be marked as _Replaced_ and fall out of Expiry Reporting.
* Upload - select the file to be uploaded.
* Notes - \(optional\) add any relevant notes.

Then click on _Save_.

![image-20200817162806178](../.gitbook/assets/image-20200817162806178.png)

The new Document will now show at the top of the list \(they display in _Created On_ order with the most recent at the top\) and the if you have selected to _Replace Old Versions_ they will be marked up accordingly.

![image-20200817163613260](../.gitbook/assets/image-20200817163613260.png)

## Document Expiry Reporting

A list of expired or expiring documents can be viewed in the _Document Expiration Report_. From the _Home_ page click on _Reporting_.

![image-20200817164650365](../.gitbook/assets/image-20200817164650365.png)

Then select \*Document Expiration.

![image-20200817164811199](../.gitbook/assets/image-20200817164811199.png)

Add filters to your report to drill down to the information you require.

?&gt; NB. Details for any Documents that have already expired will show in Red.

![image-20200817165015305](../.gitbook/assets/image-20200817165015305.png)

