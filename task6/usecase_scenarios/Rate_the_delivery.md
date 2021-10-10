| Title | Description |
| --- | --- |
| Use case title | **Rate the delivery** |
| Precondition | Person is authorised as a user. He/she logged in into the system. User has at least one unrated and completed delivery. |
| Postcondition | The completed delivery is rated by user. |
| Main actor | User|
| Date | 10/10/2021 |

## Main scenario

User initiates the use case.

1. System forms the UI with the list of all the deliveries user have already had.
2. User chooses one unrated delivery and presses the button "Rate the delivery".
3. System forms the UI with the following fields: rating from 1 to 5 stars ⭐️ and comment.
4. User chooses rating, leaves the comment.
5. User presses the button "Send".
6. System validates the information and saves it.
7. System forms a UI with a corresponding successful message.

## Alternative scenario

Step 7: Start condition - user didn't fill in all the necessary fields:

1. System forms a UI with a corresponding error message and asks user to try again.
2. Transition to the step 4 of the main flow.