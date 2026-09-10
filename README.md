# WitleShop-ERD-Assignment
ERD design for the WitleShop Online Retail System database assignment

## Overview

This project presents the Entity Relationship Diagram (ERD) design for the WitleShop Online Retail System.

The purpose of the project is to design a database structure that supports the management of customers, delivery addresses, products, categories, suppliers, orders, payments, and deliveries.

The assignment identifies the main entities, primary keys, foreign keys, relationships, and cardinalities required for the database.

## Business Case

WitleShop (Pty) Ltd is a South African online retail company that sells electronics, clothing, and home appliances directly to customers through a web and mobile platform. 
The company is growing fast and wants to build a new database system to manage:
•	Customers
•	Products
•	Orders
•	Payments
•	Deliveries
•	Suppliers

The proposed database is designed to support:

- Customer management
- Product management
- Order processing
- Payment management
- Delivery management
- Supplier management

## Entities Identified

The main entities are:

- CUSTOMER
- ADDRESS
- ORDER
- PRODUCT
- CATEGORY
- SUPPLIER
- PAYMENT
- DELIVERY
- ORDER_ITEM

`ORDER_ITEM` is used to resolve the many-to-many relationship between ORDER and PRODUCT.

## Key Relationships

- CUSTOMER to ADDRESS - One-to-Many
- CUSTOMER to ORDER - One-to-Many
- CATEGORY to PRODUCT - One-to-Many
- SUPPLIER to PRODUCT - One-to-Many
- ORDER to PRODUCT - Many-to-Many
- ORDER to ORDER_ITEM - One-to-Many
- PRODUCT to ORDER_ITEM - One-to-Many
- ORDER to PAYMENT - One-to-One
- ORDER to DELIVERY - One-to-One
- ADDRESS to DELIVERY - One-to-Many

## Tools Used

- Microsoft Word
- Miro
- GitHub

## Project Files

- ![ERD Assignment] (WitleShop-ERD-Assignment/ERD Assignment Linn Brown.docx)

## Key Outcome

The completed ERD provides a structured database design for the WitleShop Online Retail System and shows how the major business entities are connected through primary keys, foreign keys, and defined cardinalities.
