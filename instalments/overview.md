# Instalments Overview \#

Harbour Assist allows you split berthing fees \(or any other charge\) across any number of months. We do this by splitting the fees into the appropiately-costed Orders which only become due at specific times. There are 2 terms which are important to understand:

## Instalment Plans

An Instalment Plan is a a _template_ consisting of a number of month numbers with a corresponding percentage split to be applied on each Month. Instalment Plans create off-the-shelf scenarios such as:

* Monthly over 12 months
* Monthly over 6 months
* Quarterly over 12 months
* Quarterly over 24 months
* Evenly over first 10 month of year

Instalment Plans are only set up when a new pattern of payments is created.

?&gt; There are no financial values nor dates in an Instalment Plan, just month numbers and percentages. This is because the dates will depend on when the Schedule is generated, and the financial value will depend on the Site / Pricebook used.

?&gt; More documentation [here](https://github.com/glaidler/docs-1/tree/a9b2fde53025657e319d99966ea9a02a32cbd61d/Instalments/Instalments/InstalmentPlans/README.md).

## Instalment Schedules

An Instalment Schedule is simply an Instalment Plan that has been applied to a specific Account with specific dates and amounts. It represents a set of Monthly Orders belonging to a single Account, each of which having the tax-point dates for the correct due-dates and amounts that they will be owing you money \(or paying you\). The table below explains the difference between Instalment Plans and Instalment Schedules.

| Concept | Instalment Plan | Instalment Schedule |
| :--- | :--- | :--- |
| Months | Month Numbers | Specific Payment due dates |
| Value split | Percentages | Specific Instalment values |
| Relates to a specific Account? | N | Y |
| Has a financial value? | N | Y |

?&gt; More documentation [here](https://github.com/glaidler/docs-1/tree/a9b2fde53025657e319d99966ea9a02a32cbd61d/Instalments/Instalments/CreatingAnInstalmentSchedule/README.md).

## Payment Schemes

With the ability to create instalment-based debt, we need the ability to get the money; this is usually done in 1 of several ways and is defined against each Account.

* **Manual** - they just get emailed an Invoice each month and they pay online or over the phone. _Supported_
* **Direct Debit** - The money is automatically debited from their account at the appropriate time. _Supported in the UK using BottomLine_
* **Card Drawdown** - Using PaySafe's Card-Vault, when the instalment becomes due, the correct amount is drawn down automatically from the customer's stored card. _Coming soon_.

?&gt; More documentation [here](https://github.com/glaidler/docs-1/tree/a9b2fde53025657e319d99966ea9a02a32cbd61d/Instalments/Instalments/PaymentSchemes.md).

