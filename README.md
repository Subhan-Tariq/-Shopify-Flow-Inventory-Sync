# -Shopify-Flow-Inventory-Sync
A Shopify Flow automation to adjust inventory for room booking variants based on selected date ranges and occupancy types. Prevents overbooking by syncing inventory across variants.

Shopify Flow - Inventory Adjustment for Room Bookings and More

📌 Overview

This Shopify Flow automation ensures that when a customer books a room for a specific date range and selects a particular occupancy type, the inventory for other occupancy variants is also updated accordingly.

For example, if a customer books a Single Occupancy room for the dates Feb 5 - 10, the flow will automatically set the inventory of Double Occupancy and other variants for the same date range to zero, preventing overbooking.

🚀 How It Works

The flow is triggered when an order is created.

It loops through the line items in the order.

A GraphQL query retrieves product variants and their inventory.

The script adjusts inventory for the corresponding variants.

🎯 Other Use Cases

This Shopify Flow automation can be adapted for other inventory synchronization needs, including:

Event Ticketing: Ensure that if one ticket category (e.g., VIP) is sold out, other linked categories (e.g., General Admission) are also updated.

Subscription Box Variants: If a monthly box option is selected, prevent customers from selecting conflicting subscriptions for the same period.

Rental Products: Auto-adjust inventory for rental equipment where different options share the same stock.

Limited-Edition Bundles: When one product in a bundle is out of stock, automatically mark related bundles as unavailable.

📂 Installation & Usage

Download the Flow File: Get the Inventory-Adjustment-Workflow.flow from the flow-files directory.

Upload to Shopify Flow:

Go to your Shopify admin panel.

Navigate to Apps > Shopify Flow.

Click Import Workflow and upload the file.

Activate the Flow: Ensure the flow is enabled so it can run automatically when an order is placed.

🔧 Customization

You can modify the flow logic to match your store’s specific booking and inventory rules.

Adjust the GraphQL query if additional variant data is required.

✨ Contributions

If you have improvements or bug fixes, feel free to fork the repository and submit a pull request!

Author: Subhan Tariq
📧 Contact: subhant745@gmail.com

