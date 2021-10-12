| Title | Description |
| --- | --- |
| Use case title | **Create and update products** |
| Precondition | Person is authorised as a Farmer. He/she logged in into the system |
| Postcondition | Product(s) is(are) created in the system and are visible to the Customers. All changes are correctly written and can be read |
| Main actor | Farmer|
| Date | 10/10/2021 |

## Main scenario

Use case is initiated by the farmer.

### Create [C]

1. Farmer taps the button "Add product".
2. System forms a corresponding UI.
3. Farmer adds necessary information about the product into the text fields: title, description, price, available amount, picture.
4. Farmer checks all the information and presses the button "Save".
5. System validates received information and saves it.
6. System forms a UI with a corresponding successful message.

### Read[R]

1. Farmer presses the button "View product".
2.  System forms a corresponding UI with the provided information about the product: title, description, price, available amount, picture.

### Update[U]

1. Farmer presses the button "Change product".
2. System forms a UI with the editing interface: title, description, price, available amount, picture fields are editable.
3. Farmer edits one or more available fields (title, description, price, available amount, picture).
4. Farmer saved all changed information by pressing the button "Save changes".
5. System validates changes and saved the product.
6. System forms a UI with a corresponding successful message.

### Delete[D]

1. Farmer presses the button "Delete the product".
2. System asks for confirmation.
3. Farmer confirms his action.
4. System forms a UI with a corresponding successful message.

## Alternative scenario

C6, U6, D4 - Start condition:

1. System forms a UI alert with a corresponding error message.
2. Farmer clicks the button "OK" on the alert.
3. Transition to the previous step of the main flow.
