
# Account Upload

We provide the a tool that allows you to upload Account and Boat information yourselves, there are some limitations to how this works, but will be sufficient in most scenarios.

The tool can be found under Administration > DataTools > Account Upload

There are 2 parts:

* A button to download a template excel file with the right columns for successful uploading.
* A file upload button.

Please use the supplied template; this will maximise the chances of your upload being successful.

When uploading a file, the file is processed as a single unit; if any rows fail, then the entire file is rejected and no new Accounts/Boats are created.  This avoids you having to keep track of which records have/haven't been uploaded and gives you a chance to fix data and re-supply the same file.

When you upload a file, you are shown details of any failing rows so you can go to the right row in the Excel sheet to fix it.

When uploading the file, there are 2 tickboxes that adjust how the upload behaves:

**Dedupe against Account & Boat**
When ticked, existing Account and Boat records are checked against each record found in the file.  If the new record matches based on Postcode and Boat and has a "similar" first line of the Address, the row is rejected.  

---

*NB: Due to the endless possibilities of how end-users capture addresses & names, deduping is not an exact science.  When this is ticked, potentially duplicate rows will cause the entire file to be rejected.  This is to allow you to validate whether they are actually dupes and adjust the file or existing records as necessary.*

---

**Test Only**
This allows you to do a "what if" upload to check any problems with the file safe in the knowledge that even if there are *No* problems with the file, it won't be uploaded.



