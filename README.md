## What is this?

This is a personal **Food Nutrition App**, a.k.a **'Victual'**, designed to be used by an individual to track their daily food and drink intake, provide a daily nutritional analysis to the user compared with the Recommended Daily Amounts and make recipe suggestions based on the user's three lowest nutrients, based on the food that they have entered. The user can also view historical data by selecting previous days.

Built as a single-page application using **Node.JS**, **Vanilla Javascript** and **MongoDB** (a NoSQL database). This app makes use of three (free) APIs provided by **Edamam**, as per the link below:

https://developer.edamam.com/

This app also makes use of the HighCharts JS library, as per the link below:

https://www.highcharts.com/docs/

## Why is it here?

This was a week-long group project that I completed during my 16-week CodeClan course with three other students. This project acted as a tool to consolidate my learning of Javascript, a NoSQL database (Mongo), **event-driven programming** and complex interactions with an **external API**. My role in the group was full-stack. It was also the result of my first end-to-end application produced as a team!

## How do I use it?

Take a look and have a play around with the app as deployed on Heroku here:
https://victual-nutrition.herokuapp.com/

_NOTE! There is a slight issue with the app as per the above Heroku link, which seems to have broken over time since it was first built...I might look into this further to fix this some time (or I might not..!)_

## How could it be extended/improved?

- More API requests per minute

Currently the app is limited to the free version of the Edamam APIs, which particularly constrain the recipe suggestions - as only 5 requests can be made per minute to the recipe API. If this were to be actually deployed on the market then this would need to be addressed!

- More analysis customization

Currently, the user can select individual nutrients to get a last-7-day analysis with a line-graph. The app has functionality to allow the user to change the time-frame, so this could be included in the UI. More customization would improve the app further, for example seeing two nutrients over time on the line graph to compare.

- Data accuracy relies on external API and some foods not recognised

Due to the nature of the content of the app, there is a very large range of potential inputted items by the user (bascially, any food and drink item!). The accuracy of the RDA% amounts that it returns is reliant on the external API recognising the food item, and the data held by the API being accurate which is difficult to validate ourselves! Also currently, there is no error message if the food item is not recognised by the API, which the app would benefit from if added in.











