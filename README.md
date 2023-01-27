# Weather-API-Analysis-

Contains script to analyze weather data to determine the how latitude plays a factor in various weather factors.

weatherpy will:

  1. make API calls to openweathermap.org to gather various data for random cities, store them in a DataFrame, and export to a csv file.
  2. analysize the relationship of latitude and various weather factors through scatter plots.
  3. compute linear regression for each relationship.

vacationpy will:

  1. read in csv file of city data from previous script and create a map that displays a point for every city.
  2. filter cities down to desired weather conditions for vacation.
  3. make API calls to geoapify to locate the first hotel located within 10,000 meters for each city.
  4. create another map with hotel name and country as additional information in the hover message.
