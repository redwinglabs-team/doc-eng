# Set up travel agencies

After setting up a travel agency by creating a profile and a contract, Quadro is able to automatically identify new bookings from that particular travel agency and manage them exactly as you prefer.

!!! Note
      Some channel managers send reservations to both the company (the guest's workplace) and the travel agency connected to it. Check first if your channel supports this feature.

### Step 1: Create a travel agency profile

1. From the Main Menu go to Profiles> Travel Agencies
2. Click on the + button
3. Enter the name of the travel agency
4. Fill in all other relevant fields
5. Click on Save

### Step 2: Map the travel agency profile

If you are using a channel manager, it is important to map travel agency profiles. Quadro will automatically detect the reservations made by the agencies and apply the conditions dictated by the collaboration agreement.

#### Method 1: Use the Channel dropdown (recommended)

We recommend trying this method before moving on to another.

1. Open the Travel Agency profile you just created
2. Under "Channel" search for the OTA, GDS or travel agency for which the profile is intended. If you cannot find it, you will need to request the mapping information directly from your channel manager.
3. Click on Save
   If you are unable to map the travel agency with the dropdown of the "Channel" field, request the mapping information from your channel manager and try one of the methods below

#### Method 2: Use the channel manager ID

1. From the Main Menu go to Marketplace> My Subscriptions
2. Find the integration of your channel manager and click on Settings
3. Click on Channel manager companies
4. Click on the + button
5. Under Channel manager ID enter the code provided by your channel manager
6. Under Company, search for the travel agency profile you wish to map
7. Click on Create

#### Method 3: Use the IATA number

1. Open the profile of the newly created Travel Agency
2. Under IATA enter the IATA number provided by your channel manager
3. Click on Save

#### Method 4: Use the travel agency name

1. Open the profile of the newly created Travel Agency
2. Under Name, enter the name of the travel agency you are trying to map. This must be formatted exactly as sent by the channel manager, or it won't work. So always double check with your channel manager before proceeding.
3. Click on Save

### Step 3: Create a travel agency contract

Create a contract for travel agencies, so Quadro will always know how to manage bookings made with a specific travel agency (such as commissions and property rules)

1. From the Main Menu go to Profiles> Travel Agency contracts
2. Click on the + button
3. Under Company, look for the profile of the newly created Travel Agency
4. Choose how bookings should be made through a specific Travel Agency. Reservations can be made both through the guest and the travel agency
5. Fill in all other relevant fields
6. Click on Save

#### Automatically create travel agency profiles

Enables Quadro to automatically create profiles for companies and travel agencies when they are provided by the channel manager but find no match in Quadro.

1. From the Main Menu go to Marketplace> My subscriptions
2. Find the integration with your channel manager and click on Settings
3. Under Options, enable Create company profiles and profiles for travel agencies
4. Click on Save

## Travel agency commission

When you are setting up the Travel Agency Agreement, a field relating to commissions can also be filled in.

This field is not mandatory, it all depends on how you want to view the commissions.

If the field is filled in, it will not affect the booking price and only the report will show the amount paid to the travel agency.

If you would like to have different prices for a reservation, that is, if the guest has already paid the travel agency commissions and only has to pay the rest to you, then you can add changes.

You can create both an Absolute Change and a Relative Change.

- An absolute Change will always have the same value
- If the change is 100, the reservation price will be changed by +100 (in any currency applied to it)
- Instead, a Relative Change will use a percentage of the booking price value in the calculation
- If the change is 12%, the commission will change based on the total booking price

!!! note
      If you want to change the price down, you will need to add a “-” (minus) before the number

The contract options give the possibility to include the cancellation fee in the commission estimate and / or manually adjust the bookings arriving from the travel agency
