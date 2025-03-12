# Group-Project-8
MIST 4610

Team Name:
71552 Group 8


Team Members:
Alt, Jared @jaralt
Cheetha Rajesh, Sai @saicheetha
Gregg, Stephen
Lutz, Nic @niclutz3
Tanti, Dev @DevTanti


Problem Description:
When it comes to supply chain management there are a lot of products that are constantly being manufactured, stored in warehouses, ordered, shipped, and delivered. Suppliers, manufacturers, warehouse managers, shipping services, and retailers need to stay constantly informed on where everything is currently and what to do to ensure everything runs smoothly. This is all extremely difficult to track without a database that can keep everyone involved informed. Without it, products may be lost, overproduced, delivered at the wrong time, shipped to the wrong location, and not evenly distributed. This could lead to millions lost for all parties involved


Data Model:
This data model represents a supply chain system, tracking suppliers, manufacturers, products, storage, orders, and shipments. The Suppliers entity stores information about vendors providing raw materials or goods, which are recorded in the Supply_Transaction entity that links suppliers to manufacturers and logs supplied items and quantities. The Manufacturers entity details companies that produce goods, which are then stored as Products with attributes such as type, description, and manufacture date.

Inventory management is handled through the Product_Storage entity, which associates products with warehouses and tracks stock levels. Warehouses are represented in the Warehouse entity, storing details like location, capacity, and address. The Orders entity logs customer purchases, detailing order items, quantities, and buyers. Order fulfillment is tracked in Shipments, linking orders to deliveries, shipment services, and shipping speeds. Finally, Shipment_Packing records the packaging process, associating shipments with warehouses and specifying the packed items and their quantities. The relationships between these entities ensure efficient management of procurement, production, storage, and distribution.

Suppliers and Manufactures are a many to many relationship because a manufacturer can pull from many suppliers and a supplier can supply many manufacturers.

Manufacturers to product is an identifying one to many relationship because a manufacturer can make many products but a product can only have one manufacturer, products can also only exist because of the manufacturer.

Products and Warehouse have a many to many relationships because one type of product can be stored in many different warehouses and one warehouse can store many types of products.

Warehouse and Shipments have a Many to Many relationship because a Shipment can pull from many warehouses and a warehouse can put together many shipments.

Shipments and orders are a one-to-many identifying relationship because an order can be associated with many shipments, but a shipment can only be associated with one order. 



