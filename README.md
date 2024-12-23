# ERD Database Project

## Team Members
- TIO MARIANA
- IRA WIDYA SRI REZEKI 
- INDRIYANI 
- SARI SEPTIAN LUMBAN TOBING
- NURUL MAHARANI

## Overview
This repository contains the Entity-Relationship Diagram (ERD) for our database project. The diagram visualizes the structure and relationships between tables used in the database.

## ERD Diagram
![ERD Diagram](./public/diagram.png)

## Relationships
1. **Users ↔ Carts**: One-to-Many relationship (1 user can have multiple carts).
2. **Products ↔ Carts**: One-to-Many relationship (1 product can appear in multiple carts).
3. **Categories ↔ Products**: One-to-Many relationship (1 category can include multiple products).
4. **Users ↔ Orders**: One-to-Many relationship (1 user can place multiple orders).
5. **Users ↔ Wishlists**: One-to-Many relationship (1 user can have multiple wishlist items).
6. **Products ↔ Wishlists**: One-to-Many relationship (1 product can appear in multiple wishlists).
