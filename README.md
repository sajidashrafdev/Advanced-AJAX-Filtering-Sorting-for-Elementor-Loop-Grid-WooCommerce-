# Advanced AJAX Filtering & Sorting for Elementor Loop Grid (WooCommerce)

A lightweight, high-performance, all-in-one PHP snippet and shortcode solution that adds powerful AJAX-powered filtering (Categories, Colors, Materials, Price Range) and sorting to the **Elementor Pro Loop Grid** in WooCommerce, without requiring heavy or bloated third-party plugins.

---

## 🚀 Features

* **⚡ Real-Time AJAX Filtering:** Instantly filter products without page reloads.
* **📂 Multiple Taxonomies Support:** Filter by WooCommerce product categories, colors, materials, and custom price ranges.
* **🔀 Smart Query Logic:** Operates with **AND** conditions across different filter types and **OR** conditions within the same filter group.
* **📱 Responsive Design:** Includes a clean desktop inline dropdown bar and a mobile full-screen slide-out filter drawer.
* **🔄 Seamless URL Synchronization:** Updates browser URL parameters dynamically for easy sharing and bookmarking of filtered states.
* **🎨 Elementor Loop Integration:** Fully compatible with Elementor Pro Loop Grids using native template rendering and dynamic image background support.
* **🧩 Zero Plugin Bloat:** Self-contained code snippet running via WPCode or Code Snippets plugin.

---

## 🛠️ Installation Guide

1. Navigate to your WordPress dashboard and open **WPCode** or **Code Snippets** plugin -> **Add New**.
2. Set the snippet type to **PHP Snippet**.
3. Copy the entire PHP code provided in the script and paste it into the editor.
4. Set the location/insertion rule to **"Run Everywhere"**.
5. Click **Save and Activate**.
6. Edit your Elementor page, place a **Shortcode** widget right **ABOVE** your Loop Grid, and paste this shortcode:
   ```text
   [alf_filters]
