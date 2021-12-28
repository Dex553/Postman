# API testing exercise

The main objective of this exercise is to create a test suite for the following API: [https://openweathermap.org/current](https://openweathermap.org/current)

**Tools used:**

- Postman – to make API calls and create test scenarios;
- Newman – to generate a more detailed report.

**Results:**

The given API lets the user get weather data of a selected city by entering either the city name, ID, geographic coordinate, or zip code. The created test cases check if the city and weather data match if requested by different parameters (name, id, coordinates), and also check the request status and speed. The test read the initial city data from a file that was found on the API website, but shortened to include less cities. After completing multiple test loops, a report was generated from Postman and another report with the help of Newman.

**Files and their content:**

- Postman Collection.json – contains the exported collection from postman;
- Postman Report.json – contains the ran test report created by postman;
- Newman Report.rar – contains a html link to more detailed report of the same tests, but created by Newman;
- 20cities.json – contains the initial data used in the tests.
