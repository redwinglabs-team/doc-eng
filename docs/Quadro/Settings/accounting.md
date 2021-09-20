# Accounting

## Find the accounting configuration

Customize the appearance of your accounts, choose a customized counter for your receipts and much more.

1. From the Main Menu go to Settings> Accounting
2. Click on Configuration
3. Update all relevant fields
4. Click on Save

#### in-depth explanation of fields

- Options:
  - Allow modification of closed accounts: Allows reassignment and modification of accounts after their closure
  - Show the name of the employee in the account: the accounts and invoices will show the name of the employee who issued them
  - Enable automatic closing of discounted accounts: invoices with reversed items are closed automatically. When you cancel an item that has exceeded the regulated consumption time outside the FCCM (see below), the system will automatically move the item and the corresponding item to a new open invoice, which will then be automatically - closed if balanced. On the other hand, when you cancel an item on an invoice that has already been paid, the system will automatically create a discount item and insert it in a new open invoice; however the system will not automatically close this invoice because it must first be manually balanced.
  - Optional details for credit card payment: does not require receipt identification data when sending card payments from a terminal (procedure used to streamline the check-in and check-out process)
  - Credit Tracking Enabled: Allows payment tracking for outstanding invoices and their due dates
  - Request the setting of the accounting category: requires that all products and services be linked to an accounting category at the time of creation
  - Separate Invoice Deposits: Adds a separate section on all invoices dedicated to deposits made
- Tax Accuracy: Enter the number of decimal places used for tax calculation. Depending on your accounting preferences, you can also choose a higher number for greater accuracy in tax calculations. Leave this field blank to use the default rounding precision, defined by the coins and banknotes available in your accounting currency. If - you change your tax accuracy, only calculations made after the change will be affected.
- Editable Accounting History Window (FCCM): FCCM is a setting that determines how far back in time you can change accounting entries. This window allows you to edit only the items of the invoices not yet closed. Entries on invoices that are already closed cannot be changed in any way, in fact, to correct them, it is necessary to - create a reversal for that invoice.
- External Payment Types: Choose which external payment types you want to accept at your facility
- Manual Card Types Accepted: Choose which card types you want to accept via the payment terminal
- Account closure:
  - Always allowed: allows invoices to be closed at any time, even if the invoice items have not yet been consumed (in the case of future stays)
  - Only with consumed items: allows the closing of invoices only when the items contained therein have been consumed. N.B. if you select this option, you will not be able to close an account with items purchased during your stay until the day of departure.
  - Only with items consumed in half a day: allows the closure of accounts only up to 12 hours before the consumption of the items contained therein. N.B. if you select this option, you will not be able to close an invoice with accommodation items until the day of departure.
- Billing interval: Enter the number of days after the issuance of an invoice within which it must be paid.
- Rate Codes: Enter a code for each rate to map it to your external accounting software
- Default invoice counter: Choose the counter you want to automatically apply to each invoice. N.B. you can always select a different meter when reviewing the invoice if needed
- Cash payment: Select the accounting category for cash payments
- Invoice payment: Select the accounting category for invoice payments
- Unspecified Card Payment: Select the accounting category for any card payment made via terminal
- Additional Expenses: Select the accounting categories for additional expenses, including cancellation fees and tourist tax
- Terminal payments: Select the accounting categories for payments made with certain types of cards via the terminal
- Payments from the portal: Select the accounting categories for payments made with certain types of cards through the portal (eg Stripe)
- External Payments: Select the accounting categories for each type of external payment accepted at your facility
- Account header: Enter your custom header in html, which will appear at the top of all accounts
- Account Footer: Enter your custom footer in html, which will appear at the bottom of all accounts
- Top Print Margin for Accounts: Choose how large you want the margin to be and above (in millimeters)
- Side Print Margin for Accounts: Choose how large you want the left and right margins to be (in millimeters)
- Bottom Print Margin for Accounts: Choose how large you want the bottom margin to be (in millimeters)

## Create an accounting category

Set up accounting categories to track your revenue

### If you don't use an external accounting software

If you are not using external accounting software, you do not need to set up any codes with the accounting category

1. From the main menu go to Settings> Accounting
2. Click Categories
3. Click on the + button
4. Enter the name of the accounting category
5. Under code, you can enter an identifier for internal tracking in the channel manager
6. Click Create

### If you use an external accounting software

If you have external accounting software, you can set up additional codes:
Share accounting data in the channel manager with your external accounting software (and vice versa)
Link the accounting category to a cost center
Use double-entry accounting to keep track of debits and credits

### Recommended accounting categories

The International Financial Reporting Standards (IFRS) recommend the following accounting categories for reporting revenues from tourism, hospitality and leisure:

- Accommodation:
- Proceeds from the room
- Revenue from cancellation
- Storage area
- Discount
- Late check-out
- Food and drinks:
- Cafe
- Minibar
- Shop
- Payments:
- Paid
- Cash
- Visa
- MasterCard
- American Express
- Other CC
- Wire transfer
- Various:
- Laundry service
- parking area
- Service charges
- Various
- Taxes:
- City tax

### Route products to company bills

You can decide whether the overnight stay and / or product groups should be automatically debited from the company account when a reservation is made
Example: You can debit the overnight stay and breakfast on the company account, but the guest will pay for anything else.
N.B. Items added to accounts after making a booking will not be automatically charged, but you will need to add them manually.

1. Go to Main Menu> Settings> Accounting
2. Click on Routing Rules
3. Click the + button
4. Under Select routing for ..., search for the company or travel agency for which you want to set the routing rules
5. Choose whether to charge all the cost of the stay or just a part
6. Under Product categories of stay, select the categories you want to charge. This function only applies to the products contained in that category. Any child categories (and the products they contain) will not be taken into consideration
7. Under Apply rule to, you can choose when this rule will be applied to the company
8. Click on Save

## Create or delete a cashier

Cashiers record all cash transactions in the system, including internal transactions and account payments

### Step 1: Create the cashier

1. From the main menu go to Settings> Accounting
2. Click Cashiers
3. Click the + button
4. Enter your cash register details
   - To enable cash, at least one currency must be enabled
   - To allow an employee to use a cashier, you can assign the employee when creating / updating the cashier or when creating / updating the employee profile
   - If you have more than one crate, you can enter a number in the Sort order field to determine where the crates will appear
5. Click Save

### About cashier responsibility

Each employee who performs a task related to the use of money must be assigned to at least one cash register. If an employee is not assigned to any cashier, any incoming cash payments or guest account debits will not be recorded in the history. As a result, the fund will have a deficit balance.
There are two ways to set up checkout management at your facility:

- Create a cashier for each individual employee (eg “Cassa di Emilio”) and assign only that employee to the cashier in question. In doing so, the recorded money should be divided among employees, so that each individual is responsible for a specific amount of money, as well as for reporting their own money and closing the cash at the - end of the shift.
- Create a specific cashier for a department (eg “Reception desk”) and assign each employee of that department to the same cashier. This option is certainly less secure than the previous one, in fact it should only be used in facilities with only one person present during the shift

### Delete a cashier

The cash register must be on an even balance to be canceled. The cancellation of a crate cannot be undone

1. From the Main Menu go to Settings> Accounting
2. Click Checkout
3. Click on the "" icon of the cashier you want to delete
4. Click Delete
5. Confirm by clicking Delete again

## Set bill and invoice numbering with counters

You can use counters to automatically assign numbers to invoices, proformas, and service orders

- An account counter can be assigned to both accounts and invoices
- A proforma counter can be assigned to the proforma of invoices
- A service order counter can be assigned to service orders, including reservations and service product orders. N.B. It is possible to have only one counter of service orders, so it is not possible to create a new one, but only to change the default service order counter
  N.B. Once the account or invoice has been closed, the meter value cannot be changed as the closed account or invoice is legal tax documents.

### Create a counter

One for each type of meter is created by default when you create your property, but you can still customize the meters for your accounts, invoices and pro forma so that each has its own unique number

1. From the Main Menu go to Settings> Accounting
2. Click on Counters
3. Click the + button
4. Choose the type of counter you want to create
5. Complete the fields
6. Click Save

#### in-depth explanation of fields

- Name: enter the name of the banknote counter
- Value: enter the number from which the banknote counter will start counting
- Number Format (Prefix): Set a prefix number for your bill counter, using placeholders to alert the formatting system. For example, if you want to prefix the counter number with '2000', you must enter "2000 [0: 0000]"
- Title: Enter the title of the account for your accounting exports
- Code (of account type): Enter the code of the account type, if necessary, for your accounting exports. N.B. this field is visible only when creating an account counter

### Managing counters

After creating a counter, you can:

- Make the meter the default for its type, so that it is automatically applied when creating an account or invoice
- Reset the counter value
- Update the settings
- Clear the counter
  The counters can be reset to a maximum of 1, so if you want your counters to start from a different number you have to create a new counter and set it as default. However, we do not recommend that you reset your counters, as it may cause duplication of account numbers.

## Set up your exchange rates

You can set up your property by assigning it as many exchange rates as you like, but when you configure your property's general settings, you need to choose a default currency.

1. From the main menu go to Settings> Accounting
2. Click on Exchange Rates
3. Click the + button
4. In the Currency field, select the currency you want to add
5. Click on Save
   You will be redirected to the list of your active exchange rates
   Under column A, enter the value of the currency you just added relative to your default currency.
   For example, if your current currency is "ABC", and you are adding an exchange rate for "XYZ", you could enter 2 under the ABC column entry.
6. Select the checkbox in the Accepted column to enable the currency
   Tip: Click the arrow buttons to reverse the exchange rate between the two columns

### Managing exchange rates

Once you have set up your exchange rates, you need to keep them up to date to avoid any discrepancies. You should therefore, alternatively:

- Manually update your exchange rates at least once a month
- Connect to the exchange rate provider integration, which will automatically update the exchange rates for you.
  Between the time a reservation is created and the time it is paid for, exchange rates may vary. If the rate group of the booking has automatic settlement enabled, the exchange rate will be pegged at the time of creation. Otherwise, a change will be sent to the guest's account.
