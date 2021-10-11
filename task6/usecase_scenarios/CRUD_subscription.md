| Title | Description |
| --- | --- |
| Use case title | **Create subscription** |
| Precondition | Person is authorised as a Customer. He/she logged in into the system. |
| Postcondition | Customer subscribed to scheduled deliveries with the fixed set of products. |
| Main actor | Customer|
| Date | 10/10/2021 |

## Main scenario

Customer initiates the use case.

### Read [R]
1. Customer goes to the section with all existing subscriptions by pressing the button "All subscriptions".
2. System forms the UI with all the subscriptions.

### Create [C]

1. Customer presses the button "Create subscription".
2. System forms the UI with the following fields: prefarable time of delivery, list of products, how often should the chosen products be delivered.
3. Customer edits the information.
4. Customer submits the changes by pressing the button "Save".
5. System validates the information and creates subscription.
6. System forms a UI with a corresponding successful message.

### Update [U]

1. Customer presses the button on one of the created subscriptions "Edit".
2. System forms the UI with the following editable information: prefarable time of delivery, list of products, how often should the chosen products be delivered.
3. Customer edits the information.
4. Cutomer submits the changes by pressing the button "Save".
5. System validates the information and creates subscription.
6. System forms a UI with a corresponding successful message.

### Delete [D]

1. Customer presses the button "Delete".
2. System forms the UI alert asking for confirmation of the action.
3. Customer presses the "OK" button conforming the delition.
4. System validates the information and deletes the subscription.
5. System forms a UI with a corresponding successful message.

## Alternative scenario

Start condition - Customer wants to cancel subscription.
1. Customer presses the button "Cancel subscription".
2. System forms a UI with a corresponding successful message.
3. End of the alternative flow.

On step **C6, U6**: start condition - validation failed.
1. System forms a UI with a corresponding error message.
2. Customer clicks the button "OK" on the alert.
3. Transition to the previous step 3 of the main flow.

On step **D2**: Start confition - Customer miclicked and doesn't want to delete subscription.
1. Customer presses the "Cancel" button.
4. End of the alternative flow.