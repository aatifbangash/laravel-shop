Laravel shop


Users
    - Customers (front-end)
    - Admin (Back-end)
    - Manager (Back-end)

brands (id, name, slug)
Categories (id, name, slug)
    - subcategories (id, cat_id, name, slug)
        - products (id, name, desc, price, compare_price, cat_id, sub_cat_id, brand_id, etc...)
            - images (id, filename, path, product_id)
            - reviews (id, username, comments, ratting, product_id)

Shipping (id, location, shipping_rates)
Orders (id, product_id, user_id, shipping_id, discount_id)
Discounts (id, name, discount_code, discount_type, discount)
Static Pages 
