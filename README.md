# Business Management Web App

A web-based ERP-style application for managing manufacturing operations,
client orders, warehouse inventory, and invoicing.
Built with Laravel and Bootstrap 5.

## Features

**Order Management**
- External (client) orders with status tracking — draft, approved, fulfilled, cancelled
- Internal/production orders generated automatically from client orders
- Route cards linked to production orders and technology cards
- Multi-stage production controls with barcode scanning support

**Technology Cards**
- Manage manufacturing process cards per product
- Role-based access — only authorized departments can create or edit
- Linked to warehouse inventory for real-time stock availability

**Warehouse & Inventory**
- Stock intake and expense documents
- Inventory availability reports
- Integration with product and material nomenclatures

**Nomenclatures & Settings**
- Manage products, materials, machines, operations, and workstations
- Configurable per company — document ranges, screen layout, external system sync
- REST API integration with external accounting software

## Tech Stack
- **Backend:** Laravel 12 (PHP 8.2)
- **Frontend:** JavaScript, Bootstrap 5, SCSS
- **Database:** MySQL
- **PDF Generation:** Laravel Snappy (wkhtmltopdf)
- **Tables:** Yajra DataTables
- **Libraries:** Tom Select, Bootstrap Icons
