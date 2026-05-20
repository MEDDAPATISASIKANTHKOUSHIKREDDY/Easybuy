Yes — build Easy Buy as a price comparison shopping website.

Main idea

User searches a product → Easy Buy shows prices from sites like Amazon, Flipkart, Meesho, etc. → user compares and clicks the best deal.

Important note

Do not directly scrape websites without permission. Use official APIs or affiliate APIs. Flipkart’s Affiliate API supports shopping comparison sites and provides product/offer information.  Amazon India’s older PA-API documentation says PA-API is being deprecated and points developers to the Creators API. 

Features for Easy Buy

1. Search product


2. Show product image, name, rating


3. Show price from different websites


4. Show delivery charge


5. Show total price


6. “Buy Now” button linking to original site


7. Sort by lowest price


8. Price history later


9. Price drop alert later



Best tech stack for beginner

Frontend: HTML, CSS, JavaScript / React
Backend: Node.js + Express
Database: MongoDB
APIs: Flipkart Affiliate API, Amazon Creators/API, other partner APIs
Hosting: Vercel for frontend, Render/Railway for backend, MongoDB Atlas for database

Basic website flow

User searches "iPhone 15"
        ↓
Backend searches product APIs
        ↓
Prices are collected
        ↓
Frontend displays comparison table
        ↓
User clicks lowest price
        ↓
Redirect to seller website

Example comparison table

Website	Price	Delivery	Total	Link

Amazon	₹65,999	₹0	₹65,999	Buy
Flipkart	₹64,999	₹40	₹65,039	Buy
Meesho	₹66,499	₹0	₹66,499	Buy


Development roadmap

Start with a simple version:

Step 1: Create homepage with search bar
Step 2: Create product results page
Step 3: Add fake/sample product data first
Step 4: Build backend API
Step 5: Connect real affiliate/product APIs
Step 6: Add sorting and filters
Step 7: Add login and price alerts

Project name

Easy Buy
Tagline: Compare prices. Save money. Buy smarter.
