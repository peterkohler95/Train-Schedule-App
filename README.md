# Train-Schedule-App

This web application allows users to input train starting times and frequency in order to calculate when the next train will arrive and the minutes until the next train.

The firebase realtime database allows users from multiple different computers to view the same train schedule. However, only the name, destination, start time and frequency are stored on the database. All calculations are done by the browser. 

Moment js is used to convert user time input as a string into a standarized time that can be used to perform calculations such as the minutes until the next train.

## Live Link

https://peterkohler95.github.io/Train-Schedule-App/

### Technologies Used

* HTML
* CSS
* Bootstrap
* Moment.js
* Firebase realtime database
