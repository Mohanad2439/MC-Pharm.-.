Online-Pharmacy (MCPharm)
=========================

Live demo: https://mcpharm.ct.ws

Brief
-----
This repository contains a PHP-based web application located in the MCPharm directory. 

Repository layout (files exactly as in the repo)
-----
MCPharm/
- .gitignore
- index.php
- Search results page.php
- Product View page.php
- Shopping Cart.php
- Delivery Details.php
- Order received.php
- style.css
- Images/  (image assets)

What each file is (based only on file names / code entry points)
-----
- index.php — main entry page for the application (front page).
- Search results page.php — handles search form results (index.php contains a form pointing to this file).
- Product View page.php — product detail / product view page.
- Shopping Cart.php — shopping cart page and cart-related UI.
- Delivery Details.php — delivery / checkout details page.
- Order received.php — order confirmation / receipt page shown after checkout.
- style.css — site styling used by the PHP pages.
- Images/ — directory containing image assets referenced by the pages.

How to run the application locally (exact steps for files present)
-----
1. Clone the repository:
   git clone https://github.com/Mohanad2439/Online-Pharmacy.git

2. Serve the MCPharm directory with PHP's built-in server:
   cd Online-Pharmacy/MCPharm
   php -S localhost:8000

3. Open the application in your browser:
   http://localhost:8000/index.php
