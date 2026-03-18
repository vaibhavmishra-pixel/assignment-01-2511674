## Anomaly Analysis

**Insert Anomaly:**
New products (e.g., P009) cannot exist without an order.
Columns: `product_id`, `product_name`, `category`, `unit_price`

**Update Anomaly:**
SR01’s office address is duplicated and inconsistent ("Nariman Point" vs "Nariman Pt").
Column: `office_address` - Rows: ORD1180, ORD1174, ORD1171, ORD1175, ORD1176, ORD1179

**Delete Anomaly:**
Deleting all rows for a customer removes them entirely (e.g., C008 - Kavya Rao).
Columns: `customer_id`, `customer_name`, `customer_email`, `customer_city`