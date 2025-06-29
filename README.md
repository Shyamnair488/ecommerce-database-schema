# E-commerce Database Schema

A complete relational database schema designed for an online e-commerce platform. This repository contains SQL schema definitions and an entity-relationship diagram (ERD) for managing users, products, orders, and addresses.

---

## 📁 Files

- `schema/schema.sql` — SQL file defining tables, relationships, and constraints.
- `schema/schema-diagram.svg` — ERD (Entity-Relationship Diagram) for visual reference.

---

## 📦 Tables Overview

### 🧍 `profiles`
Stores user information including full name, email, and user role.

### 🏠 `addresses`
Stores user shipping addresses with support for multiple entries per user.

### 📦 `products`
Stores product data like name, pricing, categories, sizes, colors, and reviews.

### 🛒 `orders`
Tracks customer orders, statuses, total amount, and shipping details.

### 🧾 `order_items`
Links individual products to each order along with quantity and pricing.

---

## ⚙️ Usage

To use this schema:

1. Open your database client or CLI.
2. Run the contents of `schema/schema.sql` to create the tables.
3. Optionally use the ERD to visualize relationships during development.

---

## 🧩 Features

- Proper UUID primary keys
- Referential integrity with foreign keys
- Use of enums and array types for flexible product features
- Automatic timestamps for creation and updates

---

## 🖼️ ERD Preview

![ERD](schema/schema_diagram.svg)

---

## 📄 License

MIT License — free to use, modify, and distribute.
