# Frequently Bought Together (FBT) Section – Shopify Assignment

## Overview
This project implements a **Frequently Bought Together (FBT)** section for a Shopify store.  
It allows customers to see related products, select multiple items, view a live total, and add them to the cart in one click.  
The section is fully dynamic, powered by **Shopify product metafields**, and styled with vibrant gradients and mint branding for a joyful user experience.

---

## Features
- **Dynamic metafields**: Each product can have its own related items without hardcoding.
- **Real-time total calculation**: Updates instantly when checkboxes are selected.
- **Cart integration**: Selected products are added to the cart together via Shopify’s `/cart/add.js` API.
- **Polished UI**:
  - Gradient background and mint green accents.
  - Product thumbnails with hover effects.
  - Playful emojis and animations for reviewer delight.

---

## Setup Instructions
1. **Metafield Definition**
   - Go to **Settings → Metafields → Products**.
   - Add a new metafield definition:
     - Name: `Frequently Bought Together`
     - Namespace and key: `fbt.products`
     - Type: Product reference
     - Accepts multiple values: ✅ Enabled

2. **Assign Related Products**
   - Open any product in **Products → All products**.
   - Scroll down to **Metafields → Frequently Bought Together**.
   - Select one or more related products.
   - Save.

3. **Add Section Code**
   - In **Online Store → Themes → Edit code**.
   - Create a new section file: `frequently-bought-together.liquid`.
   - Paste the provided Liquid + JS + CSS code.
   - Save.

4. **Test**
   - Open a product page on the storefront.
   - Confirm the FBT section shows related products.
   - Select items → verify total updates.
   - Click **Add Selected to Cart** → confirm items appear in cart.

---

## Demo
- **Storefront link:** `https://ikkasa-fbt-demo.myshopify.com`
- **Password:** `shreyash`

---

## Files Included
- `frequently-bought-together.liquid` → Custom section code.
- `README.md` → Documentation and setup guide.

---

## Author
**Shreyash**  
Frontend developer passionate about vibrant UI, Shopify customization, and joyful user experiences."# fbt-assignment" 
