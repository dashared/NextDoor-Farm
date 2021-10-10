| Title | Description |
| --- | --- |
| Use case title | **Create subscription** |
| Precondition | Person is authorised as a Customer. He/she logged in into the system. |
| Postcondition | Customer subscribed to scheduled deliveries with the fixed set of products. |
| Main actor | Customer|
| Date | 10/10/2021 |

## Main scenario

Customer initiates the use case.

1. Customer goes to the section with all orders by pressing the button "All orders".
2. System forms the UI with all the orders.
3. Customer presses the button "Subscribe to the order" on one of the presented orders.
4. System forms the UI with the following fields: prefarable time of delivery, list of products, 
5. Customer edits the information.
6. Customer submits the changes by pressing the button "Save".
7. System validates the information and creates subscription.
8. System forms a UI with a corresponding successful message.

## Alternative order

Start condition - Customer wants to cancel subscription.
1. Customer presses the button "Cancel subscription".
2. System forms a UI with a corresponding successful message.
3. End of the alternative flow.

On step 8: start condition - validation failed.
1. System forms a UI with a corresponding error message.
2. Customer clicks the button "OK" on the alert.
3. Transition to the previous step of the main flow.