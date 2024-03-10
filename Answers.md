Q1. Explain the relationship between the "Product" and "Product_Category" entities from the above diagram.
=>
The "Product" table has a column named "category_id" and inventory_id which is a foreign key referencing the primary key ("id") of the "Product_category" table.
the "category_id" from 'product ' table and "id" from 'product_category' both are having many to one Relationship 
the "inventory_id" from 'product ' table and "id" from 'product_category' both are having one to one Relationship

Similarly "Product" table has a column named "category_id" and inventory_id which is a foreign key referencing the primary key ("id") of the "Product_inventory" table.
the "category_id" from 'product ' table and "id" from 'product_inventory' both are having many to one Relationship
the "category_id" from 'product ' table and "id" from 'product_inventory' both are having one to one Relationship

And "Product" table has a column named "discount_id" which is a foreign key referencing the primary key ("id") of the "discount" table.
the "discount_id" from 'product ' table and "id" from 'discount' both are having many to one Relationship
