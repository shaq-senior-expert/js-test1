# Javascript Assessment Test

### Problem 1:

## test - prob1.html
The HTML file that contains the form and table elements.

The dropdown should contain all the weeks of the current month.
The button should be labeled "Start Tracking" and positioned in the middle of the screen.
When the button is clicked, it should trigger a JavaScript function that sends an API call to retrieve weather data for the selected week.

## script.js
The JavaScript file that contains the logic for fetching the temperature data from the API and displaying it in the table.

In the JS code, the `getWeatherData()` function is called when the "Start Tracking" button is clicked. 
It first gets the selected week from the dropdown and calculates the start and end date of the selected week. 
Then it constructs the API URL with the calculated dates and makes an API call using the `fetch()` function.

If the API call is successful, the function loops through the data to create a table with the temperature details and displays it on the page in the `table-container` div. 
If the API call fails, an error message is displayed instead.

Determine the current month and year using the Date object.
Loop through all the weeks of the month and add them as options to the dropdown.

When the "Start Tracking" button is clicked, use JavaScript to send an API call to retrieve weather data for the selected week:<br>
 Determine the start and end dates for the selected week.<br>
 Construct the API URL using the start and end dates.<br>
 Send an HTTP GET request to the API using the fetch function.<br>
 Parse the JSON response and display the temperature data in a table.<br>
 If there's an error in the API, display a custom error message instead of the table.<br>

