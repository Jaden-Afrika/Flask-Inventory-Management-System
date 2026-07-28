Flask Inventory Management System

A small REST API for managing product inventory, built with Flask.

It lets you add, view, update, and delete inventory items (product name, brand, price, barcode, quantity) through a simple set of HTTP endpoints, backed by an in-memory data store. A command-line client (cli.py) is included for interacting with the API without needing a separate frontend, and there's an integration with the Open Food Facts API for looking up products by barcode or name.

Run it with python app.py, then hit http://127.0.0.1:5000/inventory.

Features
View all inventory items or look one up by ID
Add new items to the inventory
Update existing items (price, quantity, etc.)
Delete items
Command-line client for managing inventory without calling the API directly
Look up product info by barcode or name via Open Food Facts
In-memory storage — no database setup needed
Test suite covering the API and the Open Food Facts integration