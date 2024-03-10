Q1. Explain the relationship between the "Product" and "Product_Category" entities from the above diagram.
Ans:-
The "Product" table has a column named "category_id" and inventory_id which is a foreign key referencing the primary key ("id") of the "Product_category" table.
the "category_id" from 'product ' table and "id" from 'product_category' both are having many to one Relationship 
the "inventory_id" from 'product ' table and "id" from 'product_category' both are having one to one Relationship

Similarly "Product" table has a column named "category_id" and inventory_id which is a foreign key referencing the primary key ("id") of the "Product_inventory" table.
the "category_id" from 'product ' table and "id" from 'product_inventory' both are having many to one Relationship
the "category_id" from 'product ' table and "id" from 'product_inventory' both are having one to one Relationship

And "Product" table has a column named "discount_id" which is a foreign key referencing the primary key ("id") of the "discount" table.
the "discount_id" from 'product ' table and "id" from 'discount' both are having many to one Relationship

Q2.How could you ensure that each product in the "Product" table has a valid category assigned to it?
Ans:-
You can make sure that the "category_id" column in the "Product" table only accepts values that already exist in the "id" column of the "Product_Category" table. 
This ensures that each product is assigned to a valid category. If someone tries to add a product with a category ID that doesn't exist in the "Product_Category" table, it won't be allowed.
This helps maintain consistency and accuracy in the database.
