# OpenFi

<p align="center">
<img width="300" height="350" alt="Captura de pantalla 2025-09-19 220714" src="https://github.com/user-attachments/assets/90518a81-c8de-4ce9-af20-e16daaeb3d52" />
</p>

## What is OpenFi?

-**Open Payments for Financial Inclusion**
-Our project addresses the lack of financial inclusion faced by low-income communities. It proposes an accessible, low-cost system for conducting secure transactions without relying on traditional banking. It works on simple devices with limited connectivity, encouraging savings, the formalization of small businesses, and economic integration, thus contributing to a more just and equitable society. Translate this into English. 

---
## What is the solution?

A lightweight mobile application that enables people in rural communities to send and receive digital payments even with minimal connectivity.  
The system requires only one participant (buyer or seller) to have internet access. Each transaction is validated with a unique SMS code (OTP), ensuring user identity and secure balance updates on the server.  

**Example:**  
- The merchant selects the buyer in the app.  
- The buyer receives an SMS with a code and shares it with the merchant.  
- The merchant enters the code in the app, validates the buyer, and confirms the payment.  
- The server updates the balances because at least one party is connected to the internet.  

---
## What are the benefits?

- Real financial inclusion for communities without constant internet access.  
- Less reliance on cash, reducing security risks.  
- Simple and reliable validation through SMS.  
- Easy adoption: only a basic phone and registration are required.  
- Potential integration with remittance systems (Open Payments) in the future. 

## What are the indispensable features?

1. User registration with basic data (name, phone number).  
2. Send and receive payments (OP).  
3. Transaction validation through SMS (OTP).  
4. Automatic synchronization when internet is available.  
5. Transaction history for each user.  
6. Data encryption and account security.

## What is your simple architecture/stack?

---
## Who will be responsible for building each part?

- **Mayra Capetillo González** – Mobile frontend (Flutter) and user experience design.  
- **Leonardo Medina Castañeda** – Backend (Node.js/NestJS) and business logic APIs.  
- **Noé Quintero Águila** – Database (PostgreSQL/Firebase) and data modeling.  
- **Pedro Escalera Tavares** – Cloud infrastructure and SMS/OTP integration.  
