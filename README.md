## "Pixel Play": our commercial online business of videogames
#### Guidelines Followed:
- Design and create an ERD in MySQL workbench *(your ERD should include a log table)*
- Create triggers:
  1. one for updates, and
  2. a trigger that inserts a row in a “log” table
- Write queries:
  1. List all the customer’s names, dates, and products or services used/booked/rented/bought by these customers in a range of two dates.
  2. List the best three customers/products/services/places
  3. Get the average amount of sales/bookings/rents/deliveries for a period that involves 2 or more years *(Returns only one record)*
  4. Get the total sales/bookings/rents/deliveries by geographical location (city/country)
  5. List all the locations where products/services were sold, and the product has customer’s ratings *(Yes, your ERD must consider that customers can give ratings)*
- Generation of an INVOICE: Create two views to recreate the information on the INVOICE, one view for the head and totals, one view for the details.

*details about each videogame: title, description, release date, price, genre, publisher, platform
