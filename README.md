# Dosa-Restaurant-Orders


Introduction:

The owner of the Dosa Restaurant needs help in designing a better system to keep track of the orders they have received in the past year. This project will process the customer orders from a JSON file and create two new files.
    
    1. customers.json: which contains an object with phone numbers as keys and customers names as values
    2. items.json: which contains an object with item names, object with price, and number of times it has been ordered

How it works:
  1. Reading the JSON file
     - argparse will be used to handle the first postional argument (the file)
     - the script will read the order details from the input file (example_order.JSON)
  2. Creating customers.json
     - script will extract the customer name and phone number from each order
     - it will make sure that phone number and customer names are strings
  3. Creating items.json
     - script will extract item names, price , and keep track of occurences of items ordered
       
