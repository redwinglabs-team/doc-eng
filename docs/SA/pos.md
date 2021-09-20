# Point of sale

Quadro's Point-of-Sale (POS) integration adds several properties for managing transactions that are carried out through its external outlets, such as restaurants or spas. 

Set up your services, outlets and accounting categories to connect Quadro to the Staff App POS. Only the strictly necessary information is exchanged between Quadro and the POS, in order to guarantee the security of guest data.

## Services

Before you can connect the POS system to Quadro, you must first create the related services (such as Restaurant or Bar). when the POS sends the items to Quadro to add them to a guest's account, it groups them by that service, by the accounting category and links them to the guest's account and invoices, but they are not strictly connected to specific products (therefore the products present in POS it is not necessary that they correspond to those in Quadro).

## Outlets

Before your POS service connects to Quadro, you need to create reference outlets. 

The outlets are used to record all transactions that take place outside the Framework; for example, if someone orders a drink at the bar and pays it immediately with cash or card, rather than choosing to debit the account, the transaction will be reported under the specific outlet under Accounting Report.

## How information is exchanged between the Framework and the POS

The exchange of information between the POS and the Panel is designed in such a way as to guarantee the security of the data processed.

### Items sold immediately

1. The guest orders an item
2. He asks to be able to pay immediately by cash or card
3. The employee completes the transaction
4. Then he sends the articles to Quadro, according to his accounting category
5. The transaction will be listed in the accounting report under the corresponding outlet

### Items charged to the guest's account

1. The guest orders an item
2. He asks to be charged to his account
3. The employee inquires about his name or room number in order to look for it on the POS
4. Only guests who are part of a Quadro reservation, or who have a registered and open Paymaster account are listed in the POS
5. Quadro confirms whether the guest is home and has ratings that would prevent them from having charges added to the bill
6. The articles are sent to Quadro with their associated accounting category

If no accounting category is associated with an item, the category associated with the service is applied to it.

In the Framework, the charge will be listed in the guest profile and in the accounting report
