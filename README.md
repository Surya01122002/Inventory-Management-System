# Inventory Management Web Application 📦
Welcome to the Inventory Management Web Application! This application is built using the Flask framework and provides a user-friendly interface to manage inventory for a list of products in various warehouses. Whether you run a shop or manage a warehouse, this application will help you keep track of your products and their respective locations efficiently.🏬📦

# Functionality 🛠️
The application covers the following key functionalities:

## Database Tables 🗄️
**Product:** This table stores information about various products. Each product is identified by a unique product_id.

**Location:** This table keeps track of different warehouse locations. Each location is identified by a unique location_id.

**ProductMovement:** This table records the movement of products between different locations. It includes movement_id, timestamp, from_location, to_location, product_id, and qty fields.
## Summary Page
![This is a Summary Page](https://github.com/Surya01122002/Inventory-Management-System/assets/95231128/274f530b-2469-4c13-859a-1c56711f9765)
![Screenshot (316)](https://github.com/Surya01122002/Inventory-Management-System/assets/95231128/11cf2396-adbd-4ab5-82a1-53d5c838c062)

# Views 👀
The application provides easy-to-use views for the following entities:
# Stock Page
![Screenshot (317)](https://github.com/Surya01122002/Inventory-Management-System/assets/95231128/d3b74119-846b-42e4-abd3-849b5c6fb256)
## Product:
**1.Add new products.**

**2.Edit existing product details.**

**3.View the list of products with their respective information.**

# Warehouses Page
![Screenshot (318)](https://github.com/Surya01122002/Inventory-Management-System/assets/95231128/8e47b697-29b6-4bec-a36a-a0832713491f)
## Location:
**1.Add new warehouse locations.**

**2.Edit existing location details.**

**3.View the list of warehouse locations with their respective information.**
# Logistics Page
![Screenshot (319)](https://github.com/Surya01122002/Inventory-Management-System/assets/95231128/61bb1238-be0a-4ae0-a462-5ff0d1afd8d6)
![Screenshot (320)](https://github.com/Surya01122002/Inventory-Management-System/assets/95231128/8aaa0be1-8290-444d-aa51-278550e00e4a)
## ProductMovement:
Add new product movements to record the transfer of products between locations.
Edit existing movement details if necessary.
View the list of product movements with relevant information.
# Report 📊
The application generates a comprehensive report that displays the balance quantity of each product in each warehouse location. The report is presented in a grid view with the following columns:
**Product:** Name or identifier of the product.

**Warehouse:** Name or identifier of the warehouse location.

**Qty:** The quantity of the product available in the respective warehouse.
# Use Cases 📋
**To familiarize yourself with the functionality, follow these steps:**
# Create 3 to 4 different products in the system.
**Add 3 to 4 warehouse locations.**

1.Record various product movements, which include:🆕📦🛍️

2.Moving Product A to Location X.🆕🏢🗺️

3.Moving Product B to Location X.🔄🚛

4.Moving Product A from Location X to Location Y.🚚🔄🏢➡️🏢

5.Repeat these movements for around 20 instances to simulate real-world scenarios.🚚🔄🏢🔢

6.Once you have performed these use cases, you can generate the product balance report to see the quantity of each product available in each warehouse location.📈📊🏢🔢
# Getting Started 🚀
To run the Inventory Management Web Application locally, follow these steps:
*Clone this repository to your local machine.

*Install the required dependencies using pip install -r requirements.txt.

*Run the Flask application using python app.py.

*Access the application in your web browser by visiting

**http://localhost:5005.**

**https://wonderful-flower-0e43d630f.5.azurestaticapps.net**

**Note: Ensure you have Python and Flask installed on your system before starting the application.**
# Conclusion 🎯
Congratulations! You have explored the amazing features of the **Inventory Management Web Application**. 🎉 This application offers a comprehensive solution for efficiently managing your product inventory across multiple warehouse locations. Whether you're running a shop or a large-scale warehouse, this user-friendly web application will streamline your inventory tracking processes and keep everything well-organized. 🏬📦🚛

With the ability to add, edit, and view product details, as well as warehouse locations, you have complete control over your inventory data. The ProductMovement feature empowers you to track the movement of products from one location to another, ensuring that you always know the exact quantity and location of your items. 🛍️🏢🚚📝🔄

#### Happy inventory managing! 🚀💼📦🏬📊
 
