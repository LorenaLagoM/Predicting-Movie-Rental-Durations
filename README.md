# Predicting-Movie-Rental-Durations
DVD rental company seeks regression models predicting rental duration with NDE ≤ 3 on test data to optimize inventory.

A DVD rental company needs your help. They want to find out how many days a customer will rent a DVD based on some characteristics and have asked for your assistance. They want you to try out some regression models to help predict the number of days a customer will rent a DVD. The company is looking for a model that produces a Mean Squared Error (MSE) of 3 or less on a test set. The model you create will help the company plan their inventory more efficiently.

The data they provided is in the CSV file rental_info.csv. It has the following features:

"rental_date": The date (and time) when the customer rents the DVD.
"return_date": The date (and time) when the customer returns the DVD.
"amount": The amount paid by the customer for renting the DVD.
"amount_2": The square of "amount".
"rental_rate": The rate at which the DVD is rented.
"rental_rate_2": The square of "rental_rate".
"release_year": The year the rented movie was released.
"length": The length of the rented movie, in minutes.
"length_2": The square of "length".
"replacement_cost": The amount it will cost the company to replace the DVD.
"special_features": Any special features, e.g., trailers/deleted scenes, that the DVD also has.
"NC-17", "PG", "PG-13", "R": These columns are dummy variables for the movie rating. They take the value 1 if the movie is rated as the column name and 0 otherwise. For your convenience, the reference dummy variable has already been removed.
