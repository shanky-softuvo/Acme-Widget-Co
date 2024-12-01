# Acme Widget Co. Sales System

This is a proof of concept for the Acme Widget Co. sales system. The system includes the following features:
- A product catalog with three products: Red Widget (R01), Green Widget (G01), and Blue Widget (B01).
- Special offers, such as "Buy one red widget, get the second half-price".
- Delivery charges based on the total order value.

## Features

- **Add Products**: Products can be added to the basket using their product code.
- **Calculate Total**: The total price of the basket is calculated, including any special offers and delivery costs.

## How to Use

1. Clone the repository to your local machine.
2. Include the `Basket` class in your PHP code.
3. Use the `add($productCode)` method to add products to the basket.
4. Use the `total()` method to calculate the total price of the basket, including offers and delivery.

## Example Usage

```php
$basket = new Basket();
$basket->add('R01');
$basket->add('G01');
echo "Total: $" . $basket->total();
