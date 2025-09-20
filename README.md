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

https://github.com/AllyWalk/OpenFi/blob/main/App%20OpenFi.rar

---
## Who will be responsible for building each part?

- **Mayra Capetillo González** – Mobile frontend and user experience design.  
- **Leonardo Medina Castañeda** – Backend (Node.js/NestJS) and business logic APIs.  
- **Noé Quintero Águila** – Frrontend and Backend
- **Pedro Escalera Tavares** – Cloud infrastructure and SMS/OTP integration.

---
## Español

## ¿Qué es OpenFi?  

- **Pagos Abiertos para la Inclusión Financiera**  
- Nuestro proyecto aborda la falta de inclusión financiera que enfrentan las comunidades de bajos ingresos. Propone un sistema accesible y de bajo costo para realizar transacciones seguras sin depender de la banca tradicional. Funciona en dispositivos sencillos con conectividad limitada, fomenta el ahorro, la formalización de pequeños negocios y la integración económica, contribuyendo así a una sociedad más justa y equitativa.  

---  
## ¿Cuál es la solución?  

Una aplicación móvil ligera que permite a las personas en comunidades rurales enviar y recibir pagos digitales incluso con conectividad mínima.  
El sistema requiere que solo un participante (comprador o vendedor) tenga acceso a internet. Cada transacción se valida con un código único por SMS (OTP), garantizando la identidad del usuario y la actualización segura de los saldos en el servidor.  

**Ejemplo:**  
- El comerciante selecciona al comprador en la aplicación.  
- El comprador recibe un SMS con un código y lo comparte con el comerciante.  
- El comerciante ingresa el código en la aplicación, valida al comprador y confirma el pago.  
- El servidor actualiza los saldos porque al menos una de las partes está conectada a internet.  

---  
## ¿Cuáles son los beneficios?  

- Inclusión financiera real para comunidades sin acceso constante a internet.  
- Menor dependencia del efectivo, reduciendo riesgos de seguridad.  
- Validación simple y confiable a través de SMS.  
- Fácil adopción: solo se requiere un teléfono básico y un registro.  
- Potencial integración futura con sistemas de remesas (Open Payments).  

## ¿Cuáles son las funciones indispensables?  

1. Registro de usuario con datos básicos (nombre, número de teléfono).  
2. Enviar y recibir pagos (OP).  
3. Validación de transacciones mediante SMS (OTP).  
4. Sincronización automática cuando haya internet disponible.  
5. Historial de transacciones para cada usuario.  
6. Cifrado de datos y seguridad de cuentas.  

## ¿Cuál es la arquitectura/stack simple?  

https://github.com/AllyWalk/OpenFi/blob/main/App%20OpenFi.rar  

---  
## ¿Quién será responsable de construir cada parte?  

- **Mayra Capetillo González** – Frontend y diseño de experiencia de usuario.  
- **Leonardo Medina Castañeda** – Backend (Node.js/NestJS) y APIs de lógica de negocio.  
- **Noé Quintero Águila** – Frontend y Backend  
- **Pedro Escalera Tavares** – Infraestructura en la nube e integración SMS/OTP.  

