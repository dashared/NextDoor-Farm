| Title | Description |
| --- | --- |
| Use case title | **Create and update order** |
| Precondition | Person is authorised as a Customer. He/she logged in into the system.  |
| Postcondition | Order is created in the system. All changes are correctly written and can be read. |
| Main actor | Customer|
| Date | 11/10/2021 |

## Main scenario

### Create [C]

1. Customer enters a query in the search bar.
2. Customer selects the required tags.
3. Customer clicks search button.
4. System provides the Customer with a list of relevant products.
5. Customer adds the products he likes to the cart.
6. Customer clicks "Create order" button.
7. System shows the selected product list and order details (basic payment method and delivery address).
8. Customer, if necessary, changes the order details and confirms order.
9. System forms a UI with a corresponding successful message.

### Read [R]

1. Customer opens the history of his orders.
2. System displays a list of orders that the Customer made.
3. Customer opens the order he is interested in.
4. System displays information about the order.

## Alternative scenario

### 1: Update[U]

Start condition: customer wants to cancel the order.

3.1. Customer opens an order that is at the checkout stage and has not yet been shipped.

3.2. System dispalys the current composition of the order and information about.

3.3. Customer adds new products or delete old ones.

3.4. Customer saves the changes.

3.5. System forms a UI with a corresponding successful message.

### 2: Delete[D]

1. Customer opens an order that is at the checkout stage and has not yet been shipped.
2. System dispalys the current composition of the order and information about.
3. Customer deletes order.
4. System forms a UI with a corresponding successful message.
