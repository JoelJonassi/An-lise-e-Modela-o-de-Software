# Implementation Doc

This document presents the project design artifacts developed to support the software development of sprint 03.

## Interface mockups
THe interface mockups help to to better understand the features to be created.

### Mockup for UC1.01

The next figure presents the mockup for the "Purchase ticket" use case. The user will access the canteen tickets system through the web. The menu will update if any change to the date, canteen or meal type (lunch / dinner).

![Mockup01](images/Mockup01.png)


### Mockup for UC2.01

The next figure presents the mockup for the "Purchase ticket" use case. The cashier will access the canteen tickets system using a windows desktop application.

![Mockup02](images/Mockup02.png)


## Class model

Based on the domain model, we need to develop a detailed class diagram. The diagram does not need to be complete, but should comprise the all the classes involved in the sprint.
The class diagram includes also the boundary and control classes for both use cases.

![ClassD](images/ClassDiagram.png)

When the user loads money to the system, his/her account balance in that instant is calculated and stored with the money load data.
We assume that the account balance is calculated based on the last money load, from which the tickets purchased after that moment are subtracted.

## Purchase ticket (UC1.01) Sequence Diagram

The following sequence diagram do not represent all possible interactions, just the basic flow and A1&A2 alternative flows.

![Sequence01](images/SequencePurchase.png)

## Validate ticket (UC2.01) Sequence Diagram
The following sequence diagram do not represent all possible interactions, but the basic flow.

![Sequence02](images/SequenceValidate.png)

## State diagrama for the Ticket

The ticket can have different states according to the following diagram. An open ticket can be cancelled according to the conditions referred in BR04.
The price of the meal ticket is charged even when the user do not get the meal (ticket not used), so we assume the composite state "Charged" for both cases.

![StatesD](images/CanteenStates.png)

[Back Home](Home)
