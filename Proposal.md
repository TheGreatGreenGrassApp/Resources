                                                  ## Group Project #1
 
## Title
Great Green Grass App
 
### Team Members
Julie Quinn
Peng Wang
Kuhri Howard
Steve Mieskoski
 
### Project Description
* A user management system for a landscaping business to track their customers and how frequently they mow their lawns
* Features 
    * Page 1:  Data table of users and info; 2 buttons - Add a new customer & Edit Settings
        * Add a new customer
            * Customer info
                * Name
                * Email
                * Phone #
                * Address
            * Contract Info
                * Start date
                * End date
                * Frequency (ex: every 2 weeks)
                * Rate
        * Edit Settings (Bonus)
            * Choose city
            * Password
        * Ability to edit/remove customers
    * Page 2:  Google Map 
        * Map all customer lawns
    * Page 3:  Google Calendar & Weather & Statistics
        * Schedule each customer’s lawn using info from data table
            * Weekly and monthly stats
                * \# of lawns scheduled
                * Estimated revenue
    * Additional features
        * Send out email alerts the day before scheduled lawn service. (Do not send if it will be raining)
        * Separate customer profile to track all scheduled services
        * Ability to bill customers through paypal
        * Authentication
        * Get lot size from Google map API, update lot size to work on a day on Calendar
 
### Sketch of Final Product
https://docs.google.com/presentation/d/1qzms68IuYq3_lJLCZTpTGEhKglhUr0dk2mg456eXsZc/edit?usp=sharing
 
 
### APIs to be Used
* Weather.com
* Google Maps
* Google Calendars
 
### Tasks
* Structure HTML layout
* Choose bootstrap theme & styling guidelines
    * Page 1:  
    * Data Table
    * Data Entry form
        * Ability to edit customer 
            * Pulls open the data entry form with fields populated with current customer info - user can 
            * then edit info 
            * Option to delete customer - Prompt: Are you sure?
            * Save & user info updated or removed
        * Store data in Firebase
    * Page 2:
        * Google Map
            * Automatically zoom to chosen city
            * Ability to switch between map types/styles
    * Page 3:
        * Calendar
            * Uses customer variables to schedule service (start date, frequency)
            * Bonus: Ability to edit calendar
    * Weather
        * Display 5 day forecast of the user’s city
    * Statistics
        * Weekly & Monthly stats
            * \# of lawns mowed
            * Estimated revenue
