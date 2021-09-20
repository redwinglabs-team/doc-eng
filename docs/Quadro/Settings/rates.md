# Rates

## Rate Group

<iframe width="560" height="315" src="https://www.youtube.com/embed/qWSIYqVA-x8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Create or modify a rate group

It is recommended to group rates when they have the same cancellation policy. After creating a rate group, you can create its cancellation policy

### Create a rate group

1. From the Main Menu go to Settings> Rates
2. Click on Rate Groups
3. Click the + button
4. Choose how to regulate the rates of this group
5. Enter all other rate group details
6. Click Create

#### in-depth explanation of fields

- Name: Enter a name for the rate group
- Short Name: Enter an Short name for places where space is limited
- Description: Enter a short description of the rate group for internal use
- Settlement:
  - Automatic: Select to automatically debit payments when card information is available
  - Manual: Select whether you want employees to manually process and settle payments
- Settlement action:
  - Charge Credit card: Select if you want the payment on the credit card entered in the system to be automatic
  - Create pre-authorization: Select you wish to request a pre-authorization on the credit card entered in the system when the payment is automatic. N.B. the card will not be charged until the transaction is manually processed by an employee
- Settlement Trigger: Select the moment in which the system must carry out the settlement (in case of automatic settlement), or create a usage window for the settlement carried out by employees (in case of manual settlement) N.B. to create a usage window for settlement you must first select Create settlement task in the Options field
- Settlement Offset: Enter an optional time frame to adjust the settlement activation (eg. By entering "+1 day", settlement would take place 1 day after the expected settlement date). Only available for automatic settlement
- Settlement Value (Settlement Value): Enter the percentage of the total price you want to be charged at settlement time (available only for automatic settlement). If you need to create pre-authorizations for extra expenses in case of damage, you can enter even more than 100% as the value. During check-out, it will be possible to charge an amount equal to the sum requested in the pre-authorization.
- Settlement currency (settlement currency): Enter the currency in which you want settlements to be handled (in case of automatic settlement).
- Maximum nights for settlement (maximum nights for settlement): Enter the maximum number of nights that can be automatically charged (in case of automatic settlement)
- Extension: Select which expenses should be included in the automatic settlement system
- Options:
  - Automatic deposit clearance:
    - Deposits will automatically be placed on customer accounts
    - The account in which they are entered will be closed at the time of liquidation. If you are legally required to pay taxes at checkout, select this option
  - Create a settlement task: Automatically create a form (for the employee or their manager) to proceed with the payment at the time of settlement (if the settlement is manual) or when the settlement fails (if the settlement is manual)
- Ordering: Choose the order in which you want your rate groups to be listed
- Add translation: Enter the language for which to insert the translation of the fields visible to guests

### Modify a rate group

1. From the Main Menu go to Settings > Rates
2. Click on the rate group you want to change
3. Update the rate group details
4. Click save

## Create, delete or modify a rate

<iframe width="560" height="315" src="https://www.youtube.com/embed/ISzLYrM40t0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Before you can create a rate, you need to create a rate group

### Crate a rate

1. From the Main Menu go to Settings > Rates
2. Click on Rate
3. Click the + button
4. Check the box It is enabled to make this rate available
5. Choose whether the rate should be public or private
   - Public rates are visible to anyone and can be booked from any linked channel
   - Private rates cannot be booked via Quadro or the booking engine, unless linked to a voucher. Private rates can also be booked through some distribution channels as long as they are integrated with a channel manager
6. Enter the rate details
7. Click Save

#### In-depth explanation of fields

- Start date: set the starting date for the rate to be valid
- End date: set the validity end date of the rate
- Name: Enter a name for internal use
- Short Name: Enter an Short name that will be used in places with limited space
- Description: Enter any relevant information about this rate that will be displayed in the booking engine
- External name: Enter a name that will be displayed to customers in emails and in the booking engine
- Rate group: Select the rate group this rate belongs to
- Type: Choose whether the rate should be public or private. Note: Private rates cannot be booked through the Captain or Distributor unless linked to a voucher
- Base rate: If you want to create a rate based on an existing one, select the reference rate. If you are creating a standalone rate instead, ignore this field
- Account Category (Accounting Category): Select an accounting category for this rate
- Segment: Select the segment that will be automatically assigned to customers using this rate
- Cancellation policy: Select the cancellation policy for this rate
- Ordering: Choose the position you want this rate to occupy in a list of all rates
- Add translation: Enter the language for which to insert the translation of the fields visible to guests

### Assign the value

After creating the rate, you can change the value using some additional fields:

1. Update the new fields to determine the rate price.
2. Click Save.

#### If the rate isn't attached to a base rate

You will see the following fields:

- Currency: Choose which currency this fee will be charged in.
- Price: Enter the price that will be charged each night.
- Tax Rate: Select the tax rate that will be applied.
- Change for empty bed: Apply a price adjustment for nights when the space reserved with this rate is not fully sold out.
- Change for Extra Bed: Apply a price adjustment for overnight stays when the space booked with this rate exceeds the capacity.

#### If the rate is attached to a base rate

You will see the following fields:

- Relative adjustment: Enter a percentage amount the base rate, which will determine the nightly price of this rate. For example: If the night price of your base rate is 100, and you enter "-10", the night price of your rate will be 90.
- Absolute adjustment: Enter an amount, which will be added or subtracted from the nightly price of the base rate to determine the nightly price of this rate. For example, if the night price of your base rate is 90 and you enter "-10", the night price of your rate will be 80.

### Modify a rate

1. From the main menu go to Settings> Rates
2. Click on Rate
3. Click on the rate you want to update
4. On the General tab, update the rate details
5. Click on Save

### Delete a rate

If you do not want to permanently cancel a rate, you can only deactivate it, to make it unavailable to customers who make a reservation

1. From the main menu go to Settings> Rates
2. Click on Rate
3. Click the icon on the rate you want to remove
   - To deactivate the rate and make it temporarily unavailable to customers, click on Edit and then deselect the Enable checkbox and click on Save
   - To permanently cancel a rate, click on Delete and confirm by clicking on Delete again

## Create a rate with a product included

You can create a rate that includes a product (e.g. breakfast), by creating a rate, products and rules for the products. How to set these rates depends on whether you want to include or exclude the cost of the product from the total price of the rate.

### Exclude a product from the cost of reservations

#### Step 1: Create a rate

1. From the main menu go to Settings> Rates
2. Click on the + button
3. Select Enable
4. Enter the rest of the rate details. Under "Group", you will have to choose a rate group. Under Name, enter the name of the rate package (eg Breakfast rate)
5. Click on Save
6. Under Amount, enter the total price minus the price of the product (for example, if you want the rate + product to equal 100 euros, and the product costs 10 euros, enter "90" here).
7. Click on Save

#### Step 2: create a product

1. From the Main Menu go to Settings > Bookable Services
2. Click on the bookable service
3. Click on Products
4. Click on the + button and then on New Product
5. Fill in the relevant fields. Under Name, enter the name of the product (e.g. breakfast). Under Price, enter the total cost minus the price of the rate (eg. If rate + product = 100 and rate = 90, then Price = 10). Under Options, make sure you select Charge as package. Under Billing Options, select the method you prefer (eg Choose Per person per night if you are creating the breakfast product)
6. Under Channel manager ID, find the name of your channel manager. If your channel manager supports the Products and has a product mapping code, enter the code in the field.
7. Click on Save

#### Step 3: Create a product rule

1. From the Main Menu go to Settings> Bookable Services
2. Click on your bookable service
3. Click on Product Rules
4. Click on the + button
5. Fill in the relevant fields
6. Under Action, select Add. Under Product, select the product you want to add to the package with the rate (eg Breakfast). Under rate Conditions, select Equal. Under Rate, select the rate you want to add to the package with the product (eg Rate with Breakfast)
7. Click on Save

#### Step 4: Map the product with your channel manager

1. Go to Main Menu> Marketplace
2. Click on My Subscriptions
3. Click on Settings next to your channel manager name
4. Click on Channel Manager Rates
5. Find your rate package (eg "Rate with Breakfast" and click on its Channel Manager ID)
6. Click the + icon and then + Products of the Channel Manager
7. Under Products, select the name of the product (eg Breakfast)
8. Click on Save

### Include a product in the cost of reservations

#### Step 1: Enable 'bill as package' for the service

1. From the Main Menu go to Settings> Bookable Services
2. Click on your bookable service
3. Click on Options
4. Select the Charge as package option

#### Step 2: Create a rate

1. From the Main Menu go to Settings> Rates
2. Click on Rates
3. Click on the + button
4. Select the Enabled checkbox
5. Fill in the relevant fields. Under Group, select the rate group. Under Name, enter the name of the rate package (eg Rate with Breakfast)
6. Click on Save
7. Under Price, enter the total cost of the rate plus the product (eg. If rate + product = 100, Price = 100)
8. Click on Save

#### Step 3: Create products

Create a product to package with your rate

1. From the Main Menu go to Settings> Bookable Services
2. Click on your bookable service
3. Click on products
4. Click on the + button and then on New product
5. Fill in the relevant fields.
6. Under Name, enter the name of the product (eg "Breakfast"). Under Price, enter the price of the product (the cost of the product will be reversed with an adjustment later). Under Options, make sure Charge as package is selected. Under Billing, select the method of billing (eg Select Per person per night if you are creating breakfast)
7. Click on Save

##### Create an accommodation adjustment product

1. Go to Main Menu> Settings> Bookable Services
2. Click on your bookable service
3. Click on Products
4. Click on the + button and then on New Product
5. Fill in the relevant fields.
6. Under Name, enter Overnight Adjustment. Under Price, enter the same amount as the product you are adding to the package, but with a negative value. Under Options, make sure Charge as package is selected. Under Billing, select the method of billing (eg Select Per person per night if you are creating breakfast)
7. Click on Save

#### Step 4: Create product rules

###### Add the package product to the rate

1. From the Main Menu go to Settings> Bookable Services
2. Click on your bookable service
3. Click on Product Rules
4. Click on the + button
5. Fill in the relevant fields
6. Under Action, select Add. Under Product, select the product you want to add to the package together with the rate (eg Breakfast). Under rate Condition, select Equal. Under Rate, select the rate you want to add to the package together with the product (eg Rate with breakfast)
7. Click on Save

###### Add the price adjustment to the rate

1. From the Main Menu go to Settings> Bookable Services
2. Click on your bookable service
3. Click on Product Rules
4. Click on the + button
5. Fill in the relevant fields.
6. Under Action, select Add. Under Product, select Overnight Adjustment. Under rate Condition, select Equal. Under Rate, select the rate you want to add to the package together with the product (eg Rate with breakfast)
7. Click on Save
