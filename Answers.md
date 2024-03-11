1st(Answer):
            The relationship between the "Product" and "Product_Category" tables is typically a one-to-many relationship. 
            This means that one product category can have multiple products associated with it, but each product belongs to only one category.
            Each entry in the "Product_Category" table represents a distinct category for products.
            Each entry in the "Product" table contains information about a specific product, including a reference to the category it belongs to via 
            the "category_id" column.



2nd(Answer):You create a "Category" table with a unique ID for each category. Then, in the "Product" table,
            you add a column to store the category ID, linking each product to a category. This ensures that every product must have a valid category, 
            maintaining data integrity.
            
    
