# fuzzy-couscous
Point of sale terminal for a pharmarcy.
Software Requirement Specification (SRS) – Pharmacy Point of Sale Terminal

1. Introduction:
The Pharmacy Point of Sale Terminal is a software system designed to streamline the sales process and manage inventory in a pharmacy. It aims to provide an efficient and user-friendly interface for handling customer transactions and updating product availability. This SRS document outlines the functional and non-functional requirements of the system.

2. Scope:
The system will allow pharmacy staff to input customer details, check product availability, process sales transactions, and update inventory. If a product is available, the system will calculate the subtotal, apply discounts or promotions, calculate the total amount payable, allow selection of payment method, process the payment, print a receipt, update inventory, and complete the sale. In case a product is unavailable, an out-of-stock message will be displayed, giving the option to restart or exit.

3. Functional Requirements:
- Input Customer Details: The system shall allow the user to input customer information, including name, contact details, and any relevant prescription details.
- Check Product Availability: The system shall verify if the requested product is available in the inventory.
- Enter Product Quantity: If the product is available, the user shall be able to enter the quantity of the product required.
- Calculate Subtotal: The system shall calculate the subtotal by multiplying the price of the product by the entered quantity.
- Apply Discounts or Promotions: The system shall apply any applicable discounts or promotions to the subtotal.
- Calculate Total: The system shall calculate the total amount payable by subtracting the discounts from the subtotal.
- Select Payment Method: The user shall be able to choose the desired payment method from available options.
- Process Payment: The system shall process the payment using the selected payment method.
- Print Receipt: The system shall generate a receipt with details of the transaction and print it for the customer.
- Update Inventory: After completing the sale, the system shall update the inventory by reducing the quantity of sold products.
- Display Out of Stock Message: If a product is unavailable, the system shall display an out-of-stock message.
- Restart or Exit: The user shall have the option to restart the sales process or exit the system.

4. Non-Functional Requirements:
- User Interface: The system shall provide a user-friendly and intuitive interface for easy navigation and data entry.
- Performance: The system shall perform efficiently, providing quick responses to user actions.
- Security: The system shall ensure the security of customer information and payment transactions.
- Reliability: The system shall be reliable, minimizing errors and ensuring accurate calculations and inventory updates.
- Scalability: The system should be scalable to accommodate future growth and increased transaction volume.

This SRS document outlines the key requirements for the Pharmacy Point of Sale Terminal, providing a foundation for the development process. Additional detailed specifications and design considerations will be addressed during the implementation phase.
