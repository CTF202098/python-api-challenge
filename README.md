# python-api-challenge
HW 6

WeatherPy
1.	For this activity, starter code was used as often as made sense. 
2.	In cell 1, imports were edited. 
3.	In cell 5, I used Professor Booth’s example code to create an endpoint URL for each city. I also used his example to retrieve the latitude of each city, then I used that base to extract the other variables necessary.
4.	I used in class examples from unit 6, day 2, activity 4 as a basis for my scatter plots and regressions. 
5.	I used Prof.’s homework example to define my regression function. I used the following code: 
def do_regression_plot(x_values, y_values, x_label, y_label, annotation): 
# do regression (slope, intercept, rvalue, pvalue, stderr) = sc.linregress(x_values, y_values)
regress_values = x_values * slope + intercept # these are the points/predictions 
line_eq = "y = " + str(round(slope,2)) + "x + " + str(round(intercept,2)) 
print(rvalue) 
print(line_eq)
6.	I added my own variable, “color” so that my regression graphs would match my original scatter plots. I also used one of my previous scatter plots as a base for my plot in the regression function, but I used Prof.’s example for variable syntax. I also copied Pros.’s example for adding in an annotation. 
VacationPy
1.	For this activity, starter code was used as often as made sense. 
2.	In cell 1, imports were edited. 
3.	I used Prof.’s example in cell 4 to create the initial map.
4.	In cell 5, I used Prof.’s example as a syntax guide to create a narrowed down data frame. I did not use variables for some things that he did, and hard coded them in instead. I did this to practice my own syntax, and because we could theoretically assume that these ideal vacation factors do not change from year to year or season to season, therefore they can stay the same even as weather conditions change. 
5.	In cell 6, I asked Xpert AI, “I have a data frame that contains the columns "City_ID", "City", "Lat", "Lng", "Max Temp", "Humidity", "Cloudiness", "Wind Speed", "Country", and "Date". How can I use the Pandas copy function to create a data frame called hotel_df to store the city, country, coordinates, and humidity?”  and used its answer to create my data frame. I also asked Xpert how to add a new column to this data frame and used its suggestion, hotel_df['New_Column'] = np.nan
6.	In cell 8, I used the official solution from in class activity 6.3.5 as a guide to follow the starter code provided in the homework. 

