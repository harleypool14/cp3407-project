Priority: 10
Iteration 1 (Customer core flow).

Estimation:
TBD (planning poker).

Assumptions (if any):
Payment can be mocked for Iteration 1 if needed (order still gets created and sent).
Description:
Description-v1: As a customer, I want to confirm and place my order, so it is sent to the restaurant.

Tasks:
1.Checkout review screen (items + delivery details).
Information
Order Items:
- Item name
- Quantity of items
- Price of the items
- The Subtotal amount

Order Summary:
- Subtotal amount
- Delivery fee
- Total amount

Delivery Details:
- Name of the customer
- The address of the customer
- Contact details just in case if anything goes wrong

2. Confirm/place order action.
This is what will happen when the user places the order:
- The system will make sure the cart is not empty and has at least 1 item in it
- If there is an item in the cart then a refence number will be produced
- After that there will be a order record
- Saves the order
- Then the customer will be redirected to some sort of successful order placed screen

3. Success screen and order reference.
Information that will appear:
- A confirmtation message
- A Order reference number
- A Message that confirms that the restaurant has recieved the order

UI Design:
Link/attach Figma frame once confirmed.

Completed:
