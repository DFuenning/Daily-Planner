Daily Planner

Created by: Derek Fuenning in March, 2020

This is a daily planner made with javascript, jquery, bootstrap/html and css.

# How it works:

- The current date and time are updated upon each refresh using jquery, and then are displayed at the top of the HTML page for the user. 
- Below this date are rows and columns created using bootstrap for the user to plan out their day by adding text into the main column, and saving it to local storage upon clicking the piggy bank button.
- Those same values that are saved to local storage are then fetched and displayed back on the page upon refresh. Only a clearing of the local storage will delete these values. 
- Finally, the current hour of the day is compared to the hour set for each row hour of the planner. If when the time shown on the planner has passed, the color of the text area turns grey, when it is within that hour it displays as red, and a future time is displayed as green. 

I hope you enjoy!

