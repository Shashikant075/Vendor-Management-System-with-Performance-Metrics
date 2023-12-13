
# vendor_management_project
Welcome to the Vendor Management System repository, a powerful and comprehensive system developed using Django and Django REST Framework. The primary objective of this system is to efficiently manage vendor profiles, track purchase orders, and calculate vendor performance metrics.

# Objective:
Develop a Vendor Management System with the following core features:

# Core Features:
# Vendor Profile Management:

# Model Design: 
Create a robust model to store vendor information, including name, contact details, address, and a unique vendor code.
API Endpoints:
POST /api/vendors/: Create a new vendor.
GET /api/vendors/: List all vendors.
GET /api/vendors/{vendor_id}/: Retrieve a specific vendor's details.
PUT /api/vendors/{vendor_id}/: Update a vendor's details.
DELETE /api/vendors/{vendor_id}/: Delete a vendor.
Purchase Order Tracking:

# Model Design:
Track purchase orders with fields like PO number, vendor reference, order date, items, quantity, and status.
API Endpoints:
POST /api/purchase_orders/: Create a purchase order.
GET /api/purchase_orders/: List all purchase orders with an option to filter by vendor.
GET /api/purchase_orders/{po_id}/: Retrieve details of a specific purchase order.
PUT /api/purchase_orders/{po_id}/: Update a purchase order.
DELETE /api/purchase_orders/{po_id}/: Delete a purchase order.

## Screenshots

# List all vendors

![Screenshot 2023-12-08 195917](https://github.com/Shashikanttt/Vendor-Management-System-with-Performance-Metrics/assets/101270238/4345be41-a816-481a-b114-8b26cc30f629)


# Create a purchase order

![Screenshot 2023-12-08 203012](https://github.com/Shashikanttt/Vendor-Management-System-with-Performance-Metrics/assets/101270238/37bf2efe-f2b5-42bc-8884-5e993c3caeae)

# vendor's details

![Screenshot 2023-12-08 203852](https://github.com/Shashikanttt/Vendor-Management-System-with-Performance-Metrics/assets/101270238/de460cd5-366b-4d37-9ac0-fbcc749e6167)



## Run Locally


To set up the Employee Management System, follow these steps:

1. Clone the repository to your local machine.



```bash
  git clone https://github.com/Shashikanttt/Vendor-Management-System-with-Performance-Metrics.git
```

Go to the project directory

```bash
  cd vendor_management_project

```

Create Virtual Environment

```bash
  py -m venv venv   #install virtual enviroment
  venv\scripts\activate   #activate virtual enviroment venv
```
Install

```bash
  pip install -r requirements.txt #install required packages
  py manage.py migrate # run first migration
```

Start the server

```bash
  python manage.py runserver # run the server
```


## Usage


To use the vendor_management_project, follow these steps:

Access the system via the provided URL (e.g., http://127.0.0.1:8000/ ).



```bash
    http://127.0.0.1:8000/api/](http://127.0.0.1:8000/api/vendors/

```

Create a new vendor.
● GET /api/vendors/: List all vendors.
● GET /api/vendors/{vendor_id}/: Retrieve a specific vendor's details.
● PUT /api/vendors/{vendor_id}/: Update a vendor's details.
● DELETE /api/vendors/{vendor_id}/: Delete a vendor.
 as needed.






