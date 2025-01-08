# AI\_Voice\_Agents\_Hackathon

## Project Name

*NAilaVox*

## Project Description

*NAilaVox* is an AI-powered voice bot designed to streamline order confirmation and delivery scheduling for e-commerce companies utilizing Cash on Delivery (COD). The bot automates customer interactions, ensuring quick, efficient, and polite communication while minimizing operational overhead.

## Project Links

- [Project Demo Video](https://drive.google.com/file/d/1yrUAz1k5ssImC5lZWeDFG1b83StFZvUX/view): A recorded demonstration showcasing the capabilities and workflow of NAilaVox.  
- [AI Assistant Demo](https://vapi.ai/?demo=true\&shareKey=fb4fa5f2-3fdc-4e5b-9547-90501ee3e9f2\&assistantId=392736c0-f06f-4df5-894a-4101ae316b0f): This link provides a live demonstration of the NAilaVox assistant in action.
- [Customer Data Spreadsheet](https://docs.google.com/spreadsheets/d/18KDg8HJW0ZBWElJH7Anblasbcy8RncoDOw5j_NcPoYg/edit?gid=0#gid=0): This spreadsheet serves as the database where NAilaVox stores customer responses, such as delivery addresses and confirmation statuses.

## Key Features

- *Order Confirmation*: The bot verifies ordered items, confirms delivery addresses, and checks payment details.
- *Delivery Scheduling*: Offers customers the option to provide preferred delivery times or additional courier instructions.
- *Flexible Response Handling*: Recognizes variations in user responses (e.g., "Yeah," "Yup," "That’s right" for "Yes") and gracefully manages unclear inputs.
- *Error Recovery*: Rephrases requests and minimizes repetition to ensure clarity without causing frustration.

## Workflow Example

1. The AI agent introduces itself and provides order details:
   - "Hello! This is NAilaVox from [Company Name], calling to confirm your recent order with us. You placed an order for [item details] with a total amount of [amount] to be paid upon delivery. Can you please confirm if this is correct?"
2. Customer confirms or denies the order.
3. If confirmed:
   - The bot requests the delivery address and stores it using the save_address tool.
   - The bot asks about delivery timing preferences or additional instructions.
4. If declined:
   - The bot uses the order_declined tool to process the cancellation.
5. The bot summarizes the confirmation and provides final delivery details.

## Example Interaction

*AI Agent:* "Hello! This is NAilaVox from [Company Name], calling to confirm your recent order with us. You placed an order for a pair of sneakers in size 10 with a total amount of 500 Dirham to be paid upon delivery. Can you please confirm if this is correct?"

*User:* "Yes."

*AI Agent:* "Great! Would you please provide us with your delivery address?"

*User:* "Sure, it’s [Delivery Address]."

*AI Agent:* "Thank you! Could you also confirm if there is a preferred time for delivery, or if any additional instructions need to be noted for the courier?"

*User:* "No, anytime is fine."

*AI Agent:* "Perfect! Your order is now confirmed and will be delivered to [Delivery Address] within the next 2 days. The total payment of 500 Dirham will be collected upon delivery. If you have any questions or need assistance, feel free to reach out. Thank you for shopping with [Company Name], and have a great day!"

*User:* "Thank you!"

*AI Agent:* "You're welcome! Goodbye!"

## Tools and Integrations

- *save\_address*: Stores the confirmed delivery address in the company database.
- *order\_declined*: Processes order cancellations as declined by the customer.

## Target Use Case

NAilaVox is ideal for e-commerce platforms seeking to:

- Reduce human resource dependency in customer service.
- Enhance customer satisfaction with prompt and polite interactions.
- Streamline COD order confirmations and minimize errors in delivery scheduling.
