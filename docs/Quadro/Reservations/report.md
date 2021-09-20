## Reservation report

To view the bookings report, go to Main Menu> Bookings> Report
The Booking Report offers most of the data and filtering options of any report for analyzing your property's booking data.

### Filters

- Filter: Select a filter option to narrow the results by booking type:
  - Arrival: All past, current and future confirmed bookings, sorted by arrival date.
  - Canceled: All reservations completely canceled within the selected interval, sorted by arrival date.
  - Confirmed: All confirmed bookings, regardless of current status and sorted by confirmation date.
  - Coverage: Guests in house for the entire duration of the selected interval, arriving before the start and leaving after the end.
  - Created: Reservations created in the selected range, sorted by creation date and time.
  - Departure: All bookings departing within the selected interval, sorted by departure date.
  - Request: All booking requests.
  - Confirmed request: All confirmed booking requests, sorted by arrival date.
  - Optional: All optional bookings, sorted by release date.
  - Confirmed Optional: All optional bookings that have been confirmed, sorted by arrival date.
  - Overlap: All bookings arriving, departing and staying within the selected range, sorted by arrival date.
  - Overnight: Not arriving or departing, but for at least two nights in the selected interval.
  - Staying: Arrival and overnight (but not departure) within the selected interval.
  - Updated: All reservations that have been updated at some point in the selected interval
- Start: Select a start date and time to limit the results to a specific time period.
- End: Select an end date and time to limit the results to a specific time period.
- Status: Select one of the following options to filter results by booking status:
  - Deleted
  - Check-out done
  - Check-in done
  - Confirmed
  - Request
  - Optional
- Load balances: Choose whether to display the customers' current open balance, displayed in an additional column
- Values:
  - Gross: cost of reservations including taxes
  - Net: cost of bookings excluding taxes
  - Taxes: cost of taxes only per booking
- Sort by: Choose how you want the results to be sorted and displayed.
  - Arrival date: sorted in chronological order
  - Automatic Settlement: View which accounts have not been automatically settled and check for unpaid payments.
  - Balance: View the outstanding balance on any invoices and quickly evaluate which accounts still need to be settled.
  - Booker: Displays bookings grouped by the person who booked them.
  - Reason for cancellation: Displays according to the selected cancellation reasons.
  - Company: View bookings linked to company profiles within your facility.
  - Confirmation Status: Displays reservations grouped by Requested, Optional and Confirmed Status.
  - Creation date: sorted in chronological order
  - Customer Ratings: Sort by customer ratings, defined in the Internals section of the customer profile.
  - Customer Nationality: View based on the selected nationality of your customers.
  - Departure date: sorted in chronological order
- Group: Displays group bookings with the group name as the section title; the results are also sorted by group size from smallest to largest for easy classification.
- Parent Company: View all bookings related to parent company profiles within your property, including revenues from all other subordinate companies.
- Origin: Sort by booking source
  - Rate: Displays results according to the rate types defined in your property
  - rate Group: View results according to the rate groups defined at your facility.
  - Segment: View results by segment
  - Space: displays the results for each room number
  - Space Type: Displays results based on the types of space defined in your property.
  - Status: Displays the results based on the current booking status.
  - Travel Agency: View bookings linked to travel agencies defined at your property.
  - Voucher: Sorts the results based on the voucher codes used by customers.
- Rate: Select a particular rate to see the results for the selection only.
- rate Group: Select a particular rate group to see the results for the selection only.
- Group Name: Enter a group name to display only the results for that particular group booking. Please note that you need to enter the full group name and number to see the results.
- Type: Displays only the results linked to a particular type of profile.
  - Company: Any booking linked to a company profile; filtering by mother companies will include both smaller companies and all travel agency contracts that may be related.
  - Client: Any booking linked to the client profile only.
  - Travel agency: Any booking linked to a travel agency.
- Travel Agency: Select a particular travel agency to view the results linked to that profile; if you select a travel agency that is a parent company of other travel agencies, please note that child companies will appear in the results.
- Company: Select a specific company to view the results linked to that profile; if you select a parent company, please note that the subsidiaries will appear in the results.
- Room: Select a particular space to view only reservations that have been or are assigned to that space.
- Room Category: Select a particular space category to view only the reservations that requested that space category during the booking process. If a reservation has been assigned to a seat in a category other than the one requested, it will not appear in the report.
- Source: Displays reservations that have been created by a particular source.
  - Channel
  - Channel manager
  - Painting
  - Connector
  - Booking engine
  - E-mail
  - Import
  - In person
  - Message
  - Phone
  - Website
  - Segments: Display only reservations that are attached to the selected segment (s).

### Data

The information displayed in the report always depends on which option you choose to filter on (eg Arrival, Canceled, Confirmed, etc.).

- Number: Unique reservation number automatically generated by the system and assigned to the reservation. All guest confirmations are sent with this number, which can be used directly in the search field to find a specific booking.
- Booking status: An icon representing the current booking status; hover the mouse over this icon to see the written form of the status.
- Client: Name of the reservation owner displayed with the rating icons; click on the name for a direct link to the customer profile; hover the mouse over the icons to view the label written for each customer.
- Travel companions: Number of companions (including owner) listed in icon x number format.
- Created: date and time when the reservation was created
- Arrival: date and time of arrival
- Departure: date and time of departure
- Room: allocated space
- Room category: room category listed in its short format; hover over the short name to see the full title of any spatial category. If the data in this column includes an arrow (eg SR -> 4BD), the space category of the allocated space is different from the space category requested during the booking process.
- rate: selected rate listed in its short format; hover your mouse over the short name to see the full title of the assigned rate.
- Products: Any additional products added to the reservation listed in quantity x short name format; hover the mouse over the short name to see the full name of any product; in case of stay products, they can be listed in quantity x nights x short name format.
- Company: Company name for business travelers or company related bookings; click on the company name for a direct link to the company profile.
- Travel Agency: Name of the travel agency for bookings associated with any OTA; click on the travel agency name for a direct link to the company profile.
- Commission: Amount of money owed or paid in commission to the travel agency.
- Average rate: average night rate
- Total: total amount due for the reservation
- CC: The credit card icon will appear for customers who have the card details in their profile; click on this icon to go directly to the customer billing screen; hover your mouse over this icon to view the last 4 digits and card type.
- Notes: any additional notes on the booking

### Practical use

#### Travel agency statistics

To view a breakdown of travel agency performance over a specific period of time, run the report with the following filters:
Group by: select Travel agency
If you have set up commissions for any of your travel agency contracts, you can also see the amount of money owed or paid in commission to each travel agency.

#### Credit card check

To easily check if one of the automatic expenses related to recently made bookings has been rejected by the payment portal, run the report with the following filters applied:

- Filter: Select Created
- Start: select yesterday's date 12:00
- End: select yesterday's date 23:59
- Group by: Select Automatic Settlement
- Click on the arrow icon on the right

#### Customer balances

If you want to make sure that all guests who are currently home or arriving on a specific date have a zero balance, run the report with the following filters applied:

- Filter: To view a detailed report of guests arriving or staying at home during a certain time period, select Arriving or Home Sharing.
- Start: Select a start date and time for the time period you want to view.
- End: Select an end date and time for the time period you want to view
- Options: Select Load Balances to add a Balance column to the report.
- Click on the arrow icon on the right. In the Balance column, you will see the current balance of the invoice for the customer linked to the booking.

#### Canceled bookings

Regarding canceled reservations, it is important to check every day that cancellation fees have been charged where necessary, as well as to see the reasons for canceling the reservation. To view a report with this information, select the following filters:

- Filter: To view a detailed report of reservations canceled in a given time period, select Cancel.
- Start: Select a start date and time for the time period you want to view. When running this report daily, select yesterday's date, 12:00 in the morning.
- End: Select an end date and time for the time period you want to view. When running this report daily, select the date yesterday, 23:59.
- Click on the arrow icon on the right. To easily see the reasons for the cancellation, select and apply the following filter:
- Group by: reason for cancellation
