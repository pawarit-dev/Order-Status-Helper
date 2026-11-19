# Order Status Helper

A small JavaScript project that summarizes an order's payment, shipping, item count, and delivery status.

This project was created for the [Order Status Helper project](https://roadmap.sh/projects/js-order-status-helper) on roadmap.sh.

## Features

- Check whether an order has been paid.
- Check whether an order has shipped.
- Generate a delivery message.
- Calculate the total number of items.
- Flag orders that need attention.

## Requirements

- [Node.js](https://nodejs.org/) 18 or later

## Run the project

```bash
node orderStatus.js
```

The script prints an order summary and several status checks to the console.

## Example

```text
{
  id: 'ORD-1001',
  customerName: 'Ava Stone',
  paid: true,
  shipped: true,
  itemCount: 3,
  deliveryMessage: 'Order Shipped. Estimated delivery: 2026-06-18',
  needsAttention: false
}
```
