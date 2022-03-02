### Django REST API Assignment (MCDA - 5550)

This is MyHotel - A Django Web Application, Developed as a part of MCDA-5550 course.

API endpoints:

#### POST: /app/hotel_list - Should include 'id', 'name', 'price', 'address' and 'availablity' in the request body
Where, 
'name' (Char field) is name of the Hotel and should be a series of characters or a string,
'address' (Char field) describes address of the Hotel and should be a series of characters or a string,
'id' (Int field) is the unique identifier for the hotel (Primary Key)
'price' (Int field) denotes the price of the Hotel and should contain only integers
'availablity' (Boolean field) denotes the availablity of the hotel, It can be either True or False (since it is not a mandatory field, it can be null).

#### This adds a new Hotel to the hotel table in connected database.


#### GET: /app/hotel_list - This returns the list of all Hotels from the connected database.
The returned array of hotels contain the following fields: id, name, address and price.
