# Creating Letter Templates #

Most businesses have a set of standard letters that are used for communicating with Account holders - whether it be chasing for debt, or inviting them to renew their mooring contract. 

These templates can be held in Harbour Assist for all users to access and use.

The first stage of creating a letter template is to create a 'Letterhead' Word document.  This template can then be used as a basis for most other templates.

## Creating a Word Template ##

Using Headers and Footers in Word create a document that fits with your company brand.  

Insert a table into the Header and within the table add the merge fields so that your relevant site information is merged into the Header and in the position that fits with your brand.

?> NB: When inserting merge fields you are best to display them in their 'raw' format - to see this when creating your template in Word press Alt + F9.

Ensure when adding the company Logo that you place this within a text box in the table - this will mean you can control the size that your logo appears on the template

![image-20200326150931095](image-20200326150931095.png)

Outside of the table (but within the header) insert the merge fields of TableStart:Accounts and TableEnd:Accounts.

![image-20200326150545590](image-20200326150545590.png)

Design the Footer (if required) in the same way, ensuring that if your are inserting any merge fields, rather than just text, you use the TableStart:Accounts and TableEnd:Accounts to 'surround' them.

Now you can insert the merge fields in the body of the template so that the standard information required for every letter to a customer is automatically populated in the letter.

Again you need to use the TableStart:Accounts merge field at the beginning and TableEnd:Accounts at the end for detail such as *Name, Address, Account Number and Date* to be shown in the template.

 ![image-20200326162409110](image-20200326162409110.png)

This is how the above template will ultimately look when created in Harbour Assist.

![image-20200326162734306](image-20200326162734306.png) 

Now you can save your template in Harbour Assist.

From the *Home* page select *Administration*.  

![image-20200304172928268](image-20200304172928268.png)

Now select *Document Library* which is found in *Communication & Document Tools*.

![image-20200326163024058](image-20200326163024058.png)

Click on *New Word Template*

![image-20200326163419512](image-20200326163419512.png)

Complete the information required on the lift hand side of the screen, giving your template a name, setting the Template Type (please see explanations under each type) and selecting what data to include.  

For a standard Letterhead Template you would select the Template Type of Letterhead.

The data to include for a standard letter would be *AccountWithBoats*, for more complex templates you would use other data, ie. for a Statement or Debt Letter you would use *OutstandingConfirmedOrders*.

Then click *Save*.

![image-20200326163638170](image-20200326163638170.png)

You can now upload your word template by clicking on *Choose Files*.

![image-20200326164150035](image-20200326164150035.png)

Select the file that you created in Word and click *Open*.

![image-20200326164428316](image-20200326164428316.png)

Your file has now been uploaded as a Template.

![image-20200326164536245](image-20200326164536245.png)

## Creating a Template ##

From the *Home* page select *Administration*.  

![image-20200304172928268](image-20200304172928268.png)

Now select *Email/SMS/Letter Templates* which is found in *Communication & Document Tools*.

![image-20200406162557146](image-20200406162557146.png)

Click on *New Template*.

![image-20200406162715280](image-20200406162715280.png)

Give your template a name and select *Letter* in the Channel drop down box.  

Give your template a Subject name - this will appear in the Account Comms tab, so it needs to be something that will help users identify what the letter was about without having to open the letter to see.

Then select which Word Template you want to use.

![image-20200406162940366](image-20200406162940366.png)

If you do not want your Template to be available for use straight away, remember to uncheck the *Enabled* box.  For templates that you do not want other users to be able to edit you can also uncheck the Allow Body Editing box, however this should only be done if you are certain end users will not need to edit the letter in any way.

![image-20200406163244472](image-20200406163244472.png)



You can now add any standard text that you wish to appear in the letter - for a Standard Letter Template this will normally be instruction to add text, however for other templates you can write the full body of the letter.

When you have done this, click *Save*.

![image-20200406164335464](image-20200406164335464.png)

The template is now ready for use through the Comms tab on the Account page.

![image-20200406164504391](image-20200406164504391.png)

You will note that you do not see the Word template in this screen, just the detail you added to the Communication template.  When you have added your text (if it is a blank template) or made any edits to the template wording you can preview the letter.

![image-20200406164534843](image-20200406164534843.png)

Now you can see what the letter will look like when you print it.

![image-20200406164220820](image-20200406164220820.png)





## Templates Suitable for Mail Merge ##

If you are planning on using a Template for a mail merge you will want a signature to automatically appear on the letter - the last thing you want to be doing is manually signing a large amount of letters!

Signatures need to be added to the Word Template as you are not able to add them to a Communication Template.

Create a Word Template by following the instructions in *Creating a Word Template*, ensuring you add a signature at the bottom of the template.

![Query Editor](img/Lettertemplates22.png)

Now use this Template to create a Communication Template by following the instructions in *Creating a Template*.  Ensure you give the template a name that indicates it contains a particular persons signature ie. *Letter template with NG signature*.

