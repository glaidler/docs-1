# Tariffs & Pricebooks #

Tariffs & Pricebooks are a key element of the system and are used when creating an Order of any type.

## What is a Tariff ##

A Tariff is how we refer to a product or service sold.  Each Tariff will have a name, price, calculation type and will be put into a category - this will help you to find the correct Tariff when creating an Order.

?> More documentation [here](Administration/OrderTypes)

## Calculation Types ##

Each Tariff has a *Calculation Type* - these are there to avoid end-users having to perform manual calculations and therefore reduce the risk of human error.  There are many Calculation Types, but the most commonly used are - Single, Length Overall (LOA), Per Night, LOA Per Night - these are explained below.

- **Single** - This should be used for Tariffs which have a price per item i.e. Laundry tokens, gas bottles etc. or if a berth/mooring is sold at a set price and is not dependent on the length of a craft.  When raising an order the quantity should be set for the number of items being purchased i.e. if 6 laundry tokens @ £2.80 each are required, the quantity of 6 should be selected and the price will be calculated 6 x £2.80 = £16.80.  Likewise for a berth/mooring with a set price of £5,500, the quantity of 1 should be selected and the price will be calculated 1 x £5,500 = £5,500.  

![image-20191218145908428](image-20191218145908428.png)



![image-20191218145723705](image-20191218145723705.png)

?> NB. Some Tariffs can have variable prices and are therefore set at £0 - for these Tariffs the *Single* Calculation Type should be used - the quantity selected when raising an order should be 1 and this will then enable you to manually type in the total price to be charged.

- **Length Overall (LOA)** - This calculation is used for Tariffs that are chargeable by the length of a craft i.e. the price of an annual Leisure Mooring is £239 per metre and the craft the order is being raised for is 15.6 metres in length - when raising the order the quantity of 1 should be selected, the system will automatically calculate the price of the mooring £239 x 15.6m = £3,728.40.  

 ![image-20191218151656346](image-20191218151656346.png)

- **Per Night** - Mainly used for visiting craft - the Tariff is a per night cost i.e. it is £30 per night for a visitor mooring.  When raising an Order the dates for the period of the stay should be selected from the calendar - this will show the number of nights that will be charged for - then the quantity of 1 should be selected.  The system will automatically calculate the price from the number of nights.


 ![image-20191219131552663](image-20191219131552663.png)

- **LOA Per Night** - Again this is mainly used for visiting craft, but the Tariff is calculated per night x the length of the craft.  When raising an Order the dates for the period of the stay should be selected from the calendar - this will show the number of nights that will be charged for - then the quantity of 1 should be selected.  The system will automatically calculate the price from the number of nights x the length of the craft.

![image-20191218154116618](image-20191218154116618.png)



## Creating a New Tariff

The ability to create a new *Tariff* is permission based; the *Permission* required for this is *AdministrationTariffs*.

From the *Home* page select *Administration*.

![image-20191218154746722](image-20191218154746722.png)

Then select *Tariffs*.

![image-20200820142417044](image-20200820142417044.png)

Click on *New Tariff*.

![image-20200820142601852](image-20200820142601852.png)

Complete the information required; the following tips will help:-

- **Name** - give the Tariff a name that will make sense to users and customers as this will appear on their order.
- **Code** - give the Tariff a code - this can be anything you wish - it is often just an abbreviation of the tariff name.

?> NB: Each Tariff Name and Code should be unique to that Tariff.

- **Category** - use the drop down list to select a Category or the + button to create a new one.
- **Decimal Places** - enter the number of decimal places, so for a tariff to appear as £1.99 the decimal places should be set to 2.
- **VAT Rate** - this should be entered as a decimal; 20% is 0.2, 5% is 0.05 etc.  Where VAT should not be charged enter 0.
- **Calculation Type** - select from the drop down list.

Completion of all the other cells is optional.

![image-20200820142737485](image-20200820142737485.png)

When the information has been entered, click on *Save*.

![image-20200820142931831](image-20200820142931831.png)

The next stage is to add the *Tariff* to the relevant *Pricebooks* and *Order Types*.

?> For guidance about Adding a Tariff to a Pricebook click [here](AccountsOrdersPayments/TariffsPricebooks?id=adding-and-removing-tariffs-from-pricebooks.md).

?> For more information about Order Types click [here](Administration/OrderTypes?id=adding-and-removing-a-tariff-on-an-order-type.md).



## Explaining Pricebooks ##

Pricebooks exist in order to allow different Sites to have different prices for the same Tariff i.e. the price of an annual residential mooring at one site could be £5,500, but another site could charge £6,500.  By using Pricebooks the same Tariff can be used -  for instance 'Residential - 1 payment' but by selecting the Pricebook for the site the order is being raised for, the correct price will be charged.  This takes away the need for multiple Tariffs for the same product being created.

The Pricebook you wish to use should be selected from the Tariff Selection page when raising an Order.

![image-20191218154557027](image-20191218154557027.png) 

Pricebooks can also be set for a period of time i.e. the Pricebook for the calendar year of 2019 should be used for Orders during that period.  A new Pricebook can be created, by Cloning the existing one, for the calendar year of 2020 with revised prices - this could be an across board increase of 2% for instance. This enables annual pricing changes to be released in a controlled manner.

?> For more information about Cloning a Pricebook click [here](AccountsOrdersPayments/TariffsPricebooks?id=cloning-a-pricebook.md).

Pricebooks for previous years can be archived, but will still be held on the system so that they can be referred to if necessary.

?> For more information about Managing Pricebooks click [here](AccountsOrdersPayments/TariffsPricebooks?id=managing-pricebooks.md).

## Creating a New Pricebook

To create a new *Pricebook* from the *Home* page select *Administration*.

![image-20191218154746722](image-20191218154746722.png)

Then select *Pricebooks*.

![image-20191218154839926](image-20191218154839926.png)

Click on *New*.

![image-20200820164031071](image-20200820164031071.png)

Give the *Pricebook* a name and click *Add*.

![image-20200820164125755](image-20200820164125755.png)

Your *Pricebook* has now been created in *Draft*.

The next step is to add the *Tariffs* to the *Pricebook*.

?> For guidance about Adding a Tariff to a Pricebook click [here](AccountsOrdersPayments/TariffsPricebooks?id=adding-and-removing-tariffs-from-pricebooks.md).

![image-20200820164334240](image-20200820164334240.png)

Once the *Tariffs* have been added the *Pricebook* can be left in *Draft* and then at the relevant time (if the Pricebook is seasonal for instance) you can change the *Status* of the *Pricebook* from draft to *Published* and *Enable* it for the *Site(s)* where it should be available for selection.

![image-20200820164441069](image-20200820164441069.png)



## Cloning a Pricebook

The easiest way to create a *Pricebook* to apply any increases year on year is to *Clone* an existing *Pricebook*.  The new *Pricebook* can still be amended; prices adjusted, tariffs added and removed etc, before you publish it.

To clone a *Pricebook* from the *Home* page select *Administration*.

![image-20191218154746722](image-20191218154746722.png)

The click on *Pricebooks*.

![image-20191218154839926](image-20191218154839926.png)

Click on the *Actions* button of the *Pricebook* you want to clone and select *Clone* from the dropdown list.

![image-20200821104815485](image-20200821104815485.png)

Give the new *Pricebook* a name and enter the % increase that you wish to apply to the *Tariffs*.

?> NB: The % increase will be applied to all tariffs, so some manual adjustment is inevitable.  Enter the % increase that applies to the majority of the tariffs so that fewer adjustments are necessary.  If the majority of the tariffs are staying the same enter 0.

![image-20200821104959076](image-20200821104959076.png)

The *Pricebook* will be created in Draft; click on the *Draft* button to view the *Pricebook*.

?> NB: You may need to refresh your page for it to appear.

![image-20200821105555201](image-20200821105555201.png)

To *View/Edit* the *Pricebook* click on the *Name* or use the *View/Edit* option from the *Actions* dropdown list. 

![image-20200821110251044](image-20200821110251044.png)

Now you can review your Tariffs and make any necessary adjustments to the prices - sometimes companies prefer to round prices up/down to the nearest £1 for example.

Click on the *Tariffs* tab.

![image-20200821110546097](image-20200821110546097.png)

Click on the Gross cost to amend.

?> NB: The prices displayed are the Gross cost, so include the VAT at the rate set against the Tariff.

![image-20200821143927448](image-20200821143927448.png)



## Managing Pricebooks

Pricebooks can be managed so that they appear to Users for selection at the appropriate time.  They can be prepared in advance and left in a Draft status, then changed to Published when they are in use and then Archived when they are no longer required.

Access your Pricebooks by clicking on *Pricebooks* within *Administration*.

![image-20191218154839926](image-20191218154839926.png)

By default, this page will display just the Published Pricebooks, but you can select to see Pricebooks with a different status by clicking on the blue tiles.

?> NB:  The tile will show in a darker blue if selected.

![image-20200821151457190](image-20200821151457190.png)

You can change the status of a Pricebook by clicking on the *Actions* button and selecting from the dropdown list.

![image-20200821151809234](image-20200821151809234.png)

Or you can open the Pricebook (by clicking on its name) to manage it in more detail.  Here you can change the status and also enable/disable it for different Sites and make it the Default Pricebook for a site(s).

?> NB: If a Pricebook is enabled for a Site it will appear for selection, but the system will always show the Default Pricebook initially, so make sure the Default one is the one that is most used (ie. the one for the current year etc).

![image-20200821151937474](image-20200821151937474.png)

You can also manage which Pricebooks are available for which Sites from within the Site details.

?> For more information about Sites click [here](Administration/Sites.md).

![image-20200821152435815](image-20200821152435815.png)



## Adding and Removing Tariffs from Pricebooks ##

Tariffs can the added and removed from Pricebooks easily - this may be necessary if a new Tariff becomes available at a site or an existing Tariff is no longer available.

To add or remove a Tariff, from the *Home* page select *Administration*.

![image-20191218154746722](image-20191218154746722.png)

Then select *Pricebooks*

![image-20191218154839926](image-20191218154839926.png)

On the line of the Pricebook you wish to edit, from the *Actions* key select *View/Edit*.

 ![image-20191218162838010](image-20191218162838010.png)

Then click on the *Tariffs* tab.

![image-20191218162939655](image-20191218162939655.png) 

Select the appropriate Tariff category from the drop down list.

![image-20191218163138771](image-20191218163138771.png)

 This will show all the Tariffs within that category.

![image-20191218163919002](image-20191218163919002.png)

If a Tariff is already included in the Pricebook it will show a red icon next to it - to remove this Tariff from the Pricebook click on this icon.

![image-20191218163952712](image-20191218163952712.png)

To add a new Tariff click on the green + icon.

![image-20191218164027083](image-20191218164027083.png)

Enter the Gross cost of the Tariff and click *Save*.

 ![Query Editor](img/Tariffs&pricebooks16.png)

The Tariff will now show in the Included Pricebook Entries list on the right hand side of the page.

![image-20191218164326824](image-20191218164326824.png)
