# Instalments Overview #

Harbour Assist allows you split berthing fees (or any other charge) across any number of months.  We do this by splitting the fees into the appropiately-costed Orders which only become due at specific times.  There are 2 terms which are important to understand:

## Instalment Plans

An Instalment Plan is a a *template* consisting of a number of month numbers with a corresponding percentage split to be applied on each Month.  Instalment Plans create off-the-shelf scenarios such as:

- Monthly over 12 months
- Monthly over 6 months
- Quarterly over 12 months
- Quarterly over 24 months
- Evenly over first 10 month of year

Instalment Plans are only set up when a new pattern of payments is created.  

?> There are no financial values nor dates in an Instalment Plan, just month numbers and percentages.  This is because the dates will depend on when the Schedule is generated, and the financial value will depend on the Site / Pricebook used.

?> More documentation [here](Instalments/InstalmentPlans).

## Instalment Schedules

An Instalment Schedule is simply an Instalment Plan that has been applied to a specific Account with specific dates and amounts.  It represents a set of Monthly Orders belonging to a single Account, each of which having the tax-point dates for the correct due-dates and amounts that they will be owing you money (or paying you).  The table below explains the difference between Instalment Plans and Instalment Schedules.


| Concept                        | Instalment Plan | Instalment Schedule        |
| ------------------------------ | --------------- | -------------------------- |
| Months                         | Month Numbers   | Specific Payment due dates |
| Value split                    | Percentages     | Specific Instalment values |
| Relates to a specific Account? | N               | Y                          |
| Has a financial value?         | N               | Y                          |

?> More documentation [here](Instalments/CreatingAnInstalmentSchedule).

## Payment Schemes

With the ability to create instalment-based debt, we need the ability to get the money; this is usually done in 1 of several ways and is defined against each Account.

- **Manual** - they just get emailed an Invoice each month and they pay online or over the phone. *Supported*
- **Direct Debit** - The money is automatically debited from their account at the appropriate time. *Supported in the UK using BottomLine*
- **Card Drawdown** - Using PaySafe's Card-Vault, when the instalment becomes due, the correct amount is drawn down automatically from the customer's stored card. *Coming soon*.

?> More documentation [here](Instalments/PaymentSchemes.md).