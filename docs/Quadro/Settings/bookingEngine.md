# Booking engine

## Set up the booking engine

Configure the booking engine from the system and add it to your website, so that customers can make their booking directly with you.

### Step 1: Set up your T&Cs

Before starting to use the booking engine, you need to determine what the terms and conditions of your property are, in accordance with the standards of your payment portal provider (eg Stripe).

1. From the Main Menu go to Settings> Stay
2. Click on the Stay service
3. Under Options, enter an address or HTML for the Terms and Conditions. It is necessary to fill in only one of these two fields.
4. Click on Save

### Step 2: Configure your booking engine

You can create multiple configurations of your booking engine

1. From the Main Menu go to Settings> Booking Engine
2. Click on the + button
3. Enter the configuration name and click Create
4. Complete all relevant fields
5. Click on Save

#### in-depth explanation of fields

- Name: if you want to change the name entered previously, enter it here (internal use only)
- Card payment insertion: choose how the payment cards will be managed in the booking engine.
  - Not required: does not require card information for payment (there will be no field to enter the payment card)
  - Required: Includes a field to allow customers to enter their card details, but you do not want the card details to be validated (if the details entered are incorrect, the reservation will still be created)
  - Required: Includes a field to allow customers to enter their card details, validating it before the booking can be confirmed
- Language: Choose the default language for the booking engine
- Currency: Choose the currency in which the payment will be charged to the customer (if no currency is selected, the default will be used)
- Clearing Start: Choose a number of days after the day the customer is booking that will be selected as the default start date. If you leave this field blank, the default will be 0.
- Compensation End: Choose a number of days after the day the customer is booking that will be selected as the default end date. If you leave this field blank, the default will be 2
- Number of adults: Choose the number of adults to be selected as the default
- Number of children: choose the number of children to be selected as the default
- Voucher Code: Enter one of your voucher codes to use in the Promotions field as default
- Show Voucher Code: Choose if your voucher codes should be listed in the booking engine
- Show special requests: Choose whether or not to include a field that allows guests to add special requests to their reservation
  - Once filled in, this information will be listed in the booking notes (special request field is included by default)
- Show rate comparison: Choose whether to display a rate comparison banner under your space categories. The banner will show your rate, the URL of each travel agency that you enter in the appropriate field, and the rate of that travel agency. The rate comparison banner will not be included by default
- Show availability: Choose whether to show your property's availability alongside the maximum occupancy in each space category
- Child selection enabled: choose whether to include the option to add children to bookings (children are accepted in bookings by default)
- Online travel agencies: if you selected Yes in the Show rate comparison field, enter the URL of the travel agencies you want to show in the rate comparison banner
- Competitor rate description: Enter the characteristics that differentiate your competitor's online booking (eg Breakfast included). Make sure you create a new line for each feature
- Relative change of competitor price: enter the percentage with which to show your competitor's prices (listed in the rate comparison banner if you selected Yes in the "show rate comparison" field) with respect to your BAR.
- Intro video URL: Enter the URL of a video to be shown when a customer opens the booking engine (this must link to a video in MP $ format on a cloud-based webpage, and cannot link to videos from YouTube, Vimeo or other video sharing platforms)
- Google Tag Manager Id: enter the GTM container ID to which you want all the booking engine events to be sent. GTM allows you to connect the booking engine of the booking engine to a tracking system, such as Google Analytics. Once set, you can use the preview mode to help view the data collected on user activity during the booking - process
- Theme: Choose the color combination you want in the Distributor
- Required fields: choose if the telephone field is required or optional
- Primary color: choose the main color that will be shown in the booking engine (this must be formatted in a hexadecimal code)

### Step 3: Map your space categories

All space categories are listed by default in the booking engine, so you only need to map space categories if there are some you don't want to list
N.B. when creating new space categories in the channel manager, don't forget to map them. Otherwise they will not be listed in your booking engine)

1. In the booking engine configuration, click on Category Mappings
2. Click on the + button
3. Under Category, select the category of space you want to map in the booking engine
4. In the Order field, choose the Order in which you want your space categories to be listed in the booking engine
5. Click on Save

### Get the most of Distributor

All the information listed in the Booking engine is taken from the channel manager, so it is important that every aspect of your Stay service is fully configured with customer-facing details, in particular:

#### Space categories

Make sure that the following fields are filled in for each space category listed in the booking engine:

- Ordinary bed count
- Extra capacity
- Description
- Image
- Order email template

#### Rates

Make sure the following fields are published for each public rate:

- First name
- Description
- External name
  N.B. Only the cheapest rates of each rate group are listed in the booking engine

#### Products

Only the products connected to your Stay service are listed in the booking engine. Make sure the following fields are filled in for each product attached to your Stay service:

- First name
- Description
- External name
