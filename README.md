# Day-Scheduler
A simple calendar application that allows you to save your daily events for each hour of the day. Programmed using HTML and CSS powered by Javascript/jQuery.
Moment.js allows the user to know what Day it is that they are scheduling and implementing localStorage allows a user to save a text event in the timeblocks.
If and Else conditionals are used to dynamically let the user know what time of day they are entering a new text event either in the past, present, or future!
Enjoy your scheduling!

GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with timeblocks for standard business hours
WHEN I view the timeblocks for that day
THEN each timeblock is color coded to indicate whether it is in the past, present, or future
WHEN I click into a timeblock
THEN I can enter an event
WHEN I click the save button for that timeblock
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist
