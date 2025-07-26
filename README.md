# Overview
This is a fictitious eCommerce clothing site dataset. 

## Data Dictionary

### 1. `distribution_centers.csv`
**Columns:**
- `id`: Unique identifier for each distribution center.
- `name`: Name of the distribution center.
- `latitude`: Latitude coordinate of the distribution center.
- `longitude`: Longitude coordinate of the distribution center.

### 2. `inventory_items.csv`
**Columns:**
- `id`: Unique identifier for each inventory item.
- `product_id`: Identifier for the associated product.
- `created_at`: Timestamp indicating when the inventory item was created.
- `sold_at`: Timestamp indicating when the item was sold.
- `cost`: Cost of the inventory item.
- `product_category`: Category of the associated product.
- `product_name`: Name of the associated product.
- `product_brand`: Brand of the associated product.
- `product_retail_price`: Retail price of the associated product.
- `product_department`: Department to which the product belongs.
- `product_sku`: Stock Keeping Unit (SKU) of the product.
- `product_distribution_center_id`: Identifier for the distribution center associated with the product.

### 3. `order_items.csv`
**Columns:**
- `id`: Unique identifier for each order item.
- `order_id`: Identifier for the associated order.
- `user_id`: Identifier for the user who placed the order.
- `product_id`: Identifier for the associated product.
- `inventory_item_id`: Identifier for the associated inventory item.
- `status`: Status of the order item.
- `created_at`: Timestamp indicating when the order item was created.
- `shipped_at`: Timestamp indicating when the order item was shipped.
- `delivered_at`: Timestamp indicating when the order item was delivered.
- `returned_at`: Timestamp indicating when the order item was returned.

### 4. `orders.csv`
**Columns:**
- `order_id`: Unique identifier for each order.
- `user_id`: Identifier for the user who placed the order.
- `status`: Status of the order.
- `gender`: Gender information of the user.
- `created_at`: Timestamp indicating when the order was created.
- `returned_at`: Timestamp indicating when the order was returned.
- `shipped_at`: Timestamp indicating when the order was shipped.
- `delivered_at`: Timestamp indicating when the order was delivered.
- `num_of_item`: Number of items in the order.

### 5. `products.csv`
**Columns:**
- `id`: Unique identifier for each product.
- `cost`: Cost of the product.
- `category`: Category to which the product belongs.
- `name`: Name of the product.
- `brand`: Brand of the product.
- `retail_price`: Retail price of the product.
- `department`: Department to which the product belongs.
- `sku`: Stock Keeping Unit (SKU) of the product.
- `distribution_center_id`: Identifier for the distribution center associated with the product.

### 6. `users.csv`
**Columns:**
- `id`: Unique identifier for each user.
- `first_name`: First name of the user.
- `last_name`: Last name of the user.
- `email`: Email address of the user.
- `age`: Age of the user.
- `gender`: Gender of the user.
- `state`: State where the user is located.
- `street_address`: Street address of the user.
- `postal_code`: Postal code of the user.
- `city`: City where the user is located.
- `country`: Country where the user is located.
- `latitude`: Latitude coordinate of the user.
- `longitude`: Longitude coordinate of the user.
- `traffic_source`: Source of the traffic leading to the user.
- `created_at`: Timestamp indicating when the user account was created.

---

