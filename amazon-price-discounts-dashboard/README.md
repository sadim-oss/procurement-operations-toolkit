# Amazon Price & Discounts Dashboard

An interactive dashboard analyzing 1,465 Amazon India listings - prices, markdowns, and discount patterns by category. Built as a Handshake AI Skills Studio mission ("Turn Data into an Interactive Dashboard").

## What it shows
- Median sale price ($8.27) and median marked discount (50%) across all listings
- Average actual vs. discounted price by category (Electronics, Computers & Accessories, Home & Kitchen, Office Products)
- Average discount depth by category - Computers & Accessories leads at 54%
- Largest listed markdowns spotlight (up to 94%)

## How it's built
Single self-contained HTML file: hand-written SVG charts rendered by embedded JavaScript, hover tooltips, responsive layout, no libraries or build step. Open amazon-price-discounts-dashboard.html in any browser.

## Key analytical calls
- Prices converted from INR at the Oct 11, 2026 reference rate, rounded to cents
- Categories under 30 listings excluded from charts to avoid noise
- Flagged data limitation: listing-level prices only, no sales volume or time field - so these are listed prices, not realized sales

## Status
✅ Shipped October 2026 - first completed portfolio project.
