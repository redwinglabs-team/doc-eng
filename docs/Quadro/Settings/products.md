# Products

## Create or delete a product

<iframe width="560" height="315" src="https://www.youtube.com/embed/2MMGh7HVoWA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

A product can be purchased or not by the customer at the time of booking based on the type of service to which it is connected.

In fact, if you attach a product to the Stay service, it can be purchased when a guest makes a reservation; if you attach a product to an additional service created manually, it can only be purchased on site and manually added to the customer's account

### Create a product

1. From the Main Menu go to Settings > Services and Products
2. Click on the service to which you want to link the product
   - If you want guests to be able to purchase the product at the time of booking, choose the Stay service
   - If you don't want guests to be able to purchase the product at the time of booking, choose one of the manually created additional services
3. Click Products
4. Click on the + button
5. Click on New Product
6. Enter the name of the product
7. Enter the price of the product and select the tax rate that should be applied. When you set up a price, you must also set up the currency.
8. Enter all other product details
9. Click Save

#### In-depth explanation of fields

General

- Name: Enter the product name for internal use
- Short Name: Enter an Short name for places where space is limited
- Description: Enter a description of the product
- External Name: Enter the product name as you want it to be seen by the customer
- Category: Select the product category to assign this product to
- Ordering: Choose the position that this product will occupy within a list of products
- Currency: Enter the price currency of this product
- Amount: Enter the price of the product, excluding currency symbols
- Tax Rate: Select the tax rate to be applied to the product price
- Relative Price: If you want the price of the product to be relative to the total cost of nights in a booking, enter a percentage
- Charging: Choose how you want this product to be charged
- Translation: Choose the language in which to translate the fields displayed by customers and fill out the form below
- Images: Insert a reference image for internal use of the software. For best results, use an image with a resolution of at least 1920x1080
  - Under Pictures, click Choose File
  - Select the image file on your computer. Only JPEG and PNG file formats are supported
  - Click Change
  - N.B. It is not possible to delete the background image once it has been loaded; it can only be replaced. To change this logo, follow the same steps listed above

Options:

- Source: Select the options you want to apply to this product

Accounting:

- Accounting Category: Select an accounting category for this product
- Rebate Accounting Category: Select an accounting category for discounts related to this product
- Cancelled item category: Set an accounting category for this product if it is canceled

### Delete a product

Deleting a product does not affect the data already collected for that product

1. From the Main Menu go to Settings > Services and Products
2. Click on the service to which the product is connected
3. Click on products
4. Click on the product you wish to delete
5. Click Delete
6. Confirm by clicking Delete

## Create or delete a product category

<iframe width="560" height="315" src="https://www.youtube.com/embed/R42enkvlFlc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Use product categories to organize the products offered with your service.

### Create a product category

1. From the Main Menu go to Settings > Services and Products
2. Click on the service you want to create a product category for
3. Click on products
4. Click the + button, and then click New Product Category
5. Enter the product category name and any other relevant details
6. Click create

#### In-depth explanation of fields

- Name: Enter the name of the product category for internal use
- Short Name: Enter a short name for places where space is limited
- Description: Enter a description of the product category
- Parent Category: If you want to create a subcategory, please select one of the existing product categories
- Ordering: Choose the position you want the product category to occupy in a list of categories
- Add translation: Enter the language for which to insert the translation of the fields visible to guests
- Images: Insert a reference image for internal use of the software. For best results, use an image with a resolution of at least 1920x1080
  - Under Pictures, click Choose File
  - Select the image file on your computer. Only JPEG and PNG file formats are supported
  - Click Change
  - N.B. It is not possible to delete the background image once it has been loaded; it can only be replaced. To change this logo, follow the same steps listed above

### Delete a product category

Before you can delete a product category, make sure you have cleared it first by deleting all the products it contains or by moving them to another product category.

1. From the Main Menu go to Settings> Products and Services
2. Click on the service to which the product category is linked
3. Click Products
4. Click on the icon corresponding to the category of products you wish to delete
5. Click Delete and confirm by clicking Delete again

## Add products to bookings

You can use the Product Rules to create packages (where products are automatically added to bookings) or to automatically remove certain products from bookings.

You can apply the Product Rules to bookings with different segments, rates, rate groups, space categories or space types.

### Step 1: create a product rule

Choose which bookings to apply the Product Rule to

1. Go to Main Menu> Settings> Bookable Services
2. Click on your bookable service
3. From the top menu, click on Product Rules
4. Click the + button
5. Choose his Priority. If two contradicting product rules apply to the same booking, the more important of the two will apply
6. Choose a Segment, a rate, a rate Group, a Space Category, a Space Type or an Origin.
   The Product Rule will be applied to bookings in which the previously completed field is present.
7. In the field just above the one you just filled in, choose the Condition to apply to it.

- You can further limit which bookings the Product Rule applies to by using the Minimum Number of Nights or Maximum Number of Nights fields
- Select Equals to apply the rule to the selected field entry (eg Apply the rule to the selected Rate)
- Select Not Equal to apply the rule to all the other items in the selected field, excluding the one chosen (eg Apply the rule to all rates except the selected one)

8. Click on Save. If you wish that the same Product Rule can add or remove products, click on the + button to the right of Actions

### Step 2: create an Action

At the bottom of the screen, in the Actions section, you can decide what the Product Rule can add or remove from the reservations involved. You can add multiple Actions and each action adds or removes a product.

1. Click on the + button to the right of Actions
2. Choose a product and decide whether it should be added or removed from bookings that fall under the Product Rule
3. Click on Save

N.B. You cannot add the same product more than once with a Product Rule

### Example

If a property has a rate called "Breakfast Rate", and wants it packaged with breakfast, you can create a Product Rule that automatically applies breakfast to every booking made with the "Breakfast Rate"

1. Go to Main Menu> Settings > Bookable Services
2. Click on your bookable service
3. From the top menu click Product Rules
4. Click on the + button
5. Under rate Condition, select Equal
6. Under Rate, select "Breakfast rate"
7. Click on the + button to the right of Actions
8. Under Action, select Add
9. Under Product, select "Breakfast"
10. Click on Save
