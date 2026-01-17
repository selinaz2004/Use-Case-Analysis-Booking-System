# Use-Case-Analysis-Booking-System
Visualizes a booking system for an independent cosmetic service worker using an activity diagram and use case descriptions

Below I dive in detail regarding one specific use case:

**Use Case: Booking An Appointment**

Description: Independent service worker wants to develop a booking system to allow clients to self-book online without additional assistance

Goals: Select desired date, time, service, and input any additional information, and view booking information

Stakeholders: Independent service worker, client

Pre-Condition: Customer is logged in

Post-condition: Customer is provided confirmation of booking and method to view booking information in the future


Basic flow: 
    Client logs in and opens availability calendar
    System returns a calendar with color-coded dates and times showing what is available
    Client selects date and time of their choice
    System confirms date and time and shows client a page to input service and additional information
    Client selects desired service and inputs any additional information
    System processes and saves information to database and shows payment page for deposit
    Client pays the necessary deposit for the time slot
    System receives payment and shows client success page confirming the booking
    Client has a confirmed booking and is provided their booking confirmation information

Alternate flow:
    Client logs in and views booked bookings
    System presents client with all the booking information
    Client cancels their existing booking
    System processes the cancellation and refunds the deposit only if cancellation is 24hrs+ before appointment
    System provides client confirmation page

