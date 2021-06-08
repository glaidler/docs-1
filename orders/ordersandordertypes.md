# Orders #

﻿Orders are the lifeblood of Harbour Assist, they represent a request to supply one or more Services or purchase one or more Products.

Although the term Invoices and Orders can be used interchangeably, in reality an Order is the request for the Service, and an Invoice is an optional piece of paper (PDF) that describes the content of the Order.

Once the Order has been paid for, a further PDF can be generated thanking the customer for their payment - these are usually referred to as the Receipt.

-GL this is v old and needs re-writing.

Orders can be found under the "Orders" tab when viewing an Account record.  There are a number of parts of an Order, which control the Order's visibility, what data is captured, and what the invoice looks like:

## Order Types
When a user creates an Order, they must first select it's Order Type.  Each Order Type can have the following elements customised:

1. Data capture fields.

2. Validation.

3. Invoice & Acknowledgement PDF formats.

4. Tariffs available for selection.

It's probably best to start with an example.  Many Harbours sell Fuel.  There are certain elements that are specific to a Fuel Order, which is where the customisations available to Order Types come into their own:

**Data Capture**:  Capturing Pump Start reading, Pump End reading and amount of fuel delivered allows HMRC reporting obligations.

**Validation**: We have built a "Fuel Duty Calculation" Wizard which only appears on Fuel orders and makes it easy for an end user to select the right Fuel Rate (Duty and VAT rules).

**Invoice & Receipt PDFs**: On Fuel Invoices, it's common to list Fuel Duty information.  This would be unusual if this was included on all Invoices/Acknowledgements.  Each Order Type can have their own custom Invoice and Receipt templates.

**Tariffs**:  Controlling which Tarfiffs are available reduces human error.  It makes sense on a Fuel Order to only show Tariffs that are Fuel Tariffs.

## Order Status
The Status of an Order controls it's visibility to the Customer, and how much editing can be done.  The available Statuses are:

**Proposed**:  Used for Renewal Runs.  Proposed Orders do NOT appear in the customer's payment Portal and do NOT affect the Account Balance.

**Draft**: An order which is still editable, the "Tax Point" has not been set, so line items can be added, removed, costs overridden etc.  In this state, the Order will NOT appear on any Accounting package export, but WILL affect the Account Balance.

**Confirmed**:  This Status means that it is locked and cannot be edited.  An Order can be put into a Confirmed Status by an end user, or automatically goes to this state if any Payment is allocated against the Order.