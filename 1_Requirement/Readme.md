# ATM MACHINE MINI PROJECT
![ATM](https://user-images.githubusercontent.com/78212567/132479090-c5344aa0-7af6-4655-bbb3-1e98eb4990e0.jpg)

## REQUIREMENTS
## Introduction
ATM MACHINE:The ATM will communicate each transaction to the bank and obtain verification that it was allowed by the bank. In the case of a cash withdrawal or deposit, a second message will be sent after the transaction has been physically completed (cash dispensed or envelope accepted).
If the bank determines that the customer's PIN is invalid, the customer will be required to re-enter the PIN before a transaction can proceed. If the customer is unable to successfully enter the PIN after three tries, the card will be permanently retained by the machine, and the customer will have to contact the bank to get it back.
## CONDITIONS(ASSUMPTIONS)
** For simplicity, the following assumptions havebeen made. In the table CON represents Condition.
|CON-NO|CONDITION DESCRIPTION|
|------|---------------------|
|CON NO-1|The ATM only dispense multiplies of Rs.500|
|CON NO-2|The card inserted into the ATM is valid.|
|CON NO-3|Communication between the ATM and CBS is secure and valid.|
|CON NO-4|The envelope drawer dispenses one envelope at a time.|
|CON NO-5|The ATM does not handle credit cards or any other non bank cards.|
|CON NO-6|If a user has a bank card, then the user has a bank account that can be withdrawn from and deposited to.|
|CON NO-7|Any account can have only one associated bank card.|
## REQUIREMENTS:
- A thing that is necessary.
- A necessary condition.
## TYPES: 
1.FUNCTIONAL REQUIREMENTS

2.NON - FUNCTIONAL REQUIREMENTS
## FUNCTIONAL REQUIREMENTS:
These requirements are observable tasks or processes that must be performed by the system under  development. For example, a functional requirement of an automated teller machine,”must process withdrawals and dispense cash to the customer”.

Functional requirements are labeled FR-x.Where FR stands for Functional requirements and x is a unique identifying integer.
## NON - FUNCTIONAL REQUIREMENTS:
These requirements are qualities or standards that the system under development must have  or comply with, but which are not tasks that will be automated by the system.For example non-functional requirements for a system include:”system must be built for a total installed cost of $10,50,000;”system must be secured  against Trojan attacks”.

Here “ X”  is  a unique identifying integer.
## FUNCTIONAL REQUIREMENTS FOR ATM:
|ATM-FR-X|ATM FUNCTIONAL REQUIREMENTS|
|--------|---------------------------|
|ATM-FR-1|The card reader determines the account numberfrom the entered card.|
|ATM-FR-2|The ATM is in the idle state when there is no operation.|
|ATM-FR-3|The user is prompted to enter a PIN after a card is entered.|
|ATM-FR-4|A menu is displayed to the user with the following options:Withdraw, Deposit, Paybill,Account update and Exit.|
|ATM-FR-5|The cash dispenser has the ability to dispense cash.|
|ATM-FR-6|A transaction record can be printed upon demand|
|ATM-FR=7|The card is rejected when the session is completed.|
|ATM-FR-8|The envelope feeder accepts envelops.|
|ATM-FR-9|The envelope feeder is aware when an envelope has been inserted.|
|ATM-FR-10| The printer determines whether there is sufficient paper and ink.|
|ATM-FR-11|The ATM defaults to the idle state.|
|ATM-FR-12|Transactions can be canceled at any prompt by the user pressing the cancel butten.|
## NON-FUNCTIONAL REQUIREMENTS FOR ATM:
|ATM-NFR-X|ATM-NON-FUNCTIONAL REQUIREMENTS|
|---------|--------------------------------|
|ATM-NFR-1|The ATM unit consists of a display, a card reader, a cash dispenser,an envelope,drawer,an envelope slot,a keypad and a pointer.|
|ATM-NFR-2|The keypad is a set of buttons that include the following:10 Buttons labelled with numbers 0 to 9,an OKAY button, a CLEAR button,a CANCEL button and dynamic buttons that performs different actions.|
|ATM-NFR-3|A PIN must be entered with in 20 seconds.|
|ATM-NR-4|The user must enter the PIN within three attempts.|
|ATM-NFR-5|ATM suspends further access using a particular card if the associated PIN is entered incorrectly 3 times in succession.|
|ATM-NFR-6|The ATM must be secure.|
|ATM-NFR-7|The ATM can be shut down and restarted.|
|ATM-NFR-8|The envelope drawer can beopened and refilled with envelops.|
|ATM-NFR-9|The envelope feeder can beopened so many envelopsthat has been deposited can be removed.|
|ATM-NFR-10|The cash dispenser can be openedand refilled with cash.|
|ATM-NFR-11|The printer can be opened and refilled with paper.|
# 4W'S AND 1'H
## WHO
-Young adults aged 18-34 rely more on ATMs than older people.

-Heavy ATM users tend to be employed full time.

-Heavy ATM users are more likely to use their bank's ATMs regardless of location.

-Frequent ATM users are more likely to be interested in advanced ATM features.
## WHAT
An automated teller machine (ATM) is an electronic banking outlet that allows customers to complete basic transactions without the aid of a branch representative or teller.
## WHEN
ATMs are convenient, allowing consumers to perform quick self-service transactions such as deposits, cash withdrawals, bill payments, and transfers between accounts.
## WHERE
-Banks. Banks, credit unions, and other financial institutions are among the first places people look for an ATM. ...
-Nightclubs and Bars. ...
-Hotels. ...
-Grocery Stores. ...
-Gas Stations. ...
-Festivals and Events. ...
-Casinos. ...
-Cannabis Dispensaries.
anywhere you can use your cards.
## HOW
An automated teller machine (ATM) is an electronic banking outlet that allows customers to complete basic transactions without the aid of a branch representative or teller. Anyone with a credit card or debit card can access cash at most ATMs.
# Detail requirements
## High Level Requirements:
|ID|Description|Status|
|---|-----------|------|
|HR01|User must be able to generate pin number|Implemented|
|HR02|User must be able to validate pin|Implemented|
|HR03|User must be able to view the banking options|Implemented|
|HR04|User must be able to access banking options|Implemented|
|HR05|User must be able to check balance|Implemented|
|HR06|User must be able to Deposit money|Implemented|
|HR07|User must be able to withdraw money|Implemented|
## Low level Requirements:
|ID|Description|Status|
|---|-----------|-----|
|LR01|User can access any banking option multiple times|Implemented|
|LR02|Verify wheater a trasaction is successful or not|Implemented|
|LR03|Display receipt of trasaction with req details|Future|
|LR04|Make ATM PIN secure|Future|
|LR05|Backup availability|Future|
