# Foodie - Food Delivery Website

## Overview
Foodie is a food delivery website developed using React.js for the frontend and Spring Boot for the backend. The platform offers a wide range of features to enhance user experience and ensure secure and efficient operations.

## Key Features
- **Multi-vendor Support**: Unlock a vast array of dining choices as multiple restaurants register and offer their delicious cuisines on the Foodie platform.
- **Admin Panels**: Empower restaurant owners with specialized admin panels and a super admin panel for platform owners, ensuring smooth operations for all parties involved.
- **Role-based Access**: Seamlessly manage user roles and access levels, guaranteeing a secure and controlled experience.
- **User-friendly Functions**: Convenient features including 'Add to Favorite,' 'Carousel Display,' 'Add to Cart,' and 'Remove from Cart,' enhancing the overall user experience.
- **Robust Security Measures**: Implementing secure authentication, password reset via email, and email notifications for order updates, alongside the integration of the Stripe payment gateway.

## Technologies Used
- **Frontend**: React.js
- **Backend**: Spring Boot
- **Payment Gateway**: Stripe
- **Security**: Secure authentication, password reset via email, email notifications

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/DB4558/foodie.git
   cd foodie
   ## Installation

### Prerequisites

- Java Development Kit (JDK)
- MySQL
- Maven

### Backend Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/DB4558/backend-springboot.git
   cd backend-springboot
2. **Configure the database in src/main/resources/application.properties:****

   ```bash

      spring.datasource.url=jdbc:mysql://localhost:3306/backend-springboot
      spring.datasource.username=root
      spring.datasource.password=yourpassword

3. **Build and run the backend:**
 
      ```bash

          mvn clean install
          mvn spring-boot:run

5. **Frontend Setup**

    Clone the repository:

    ```bash

      git clone https://github.com/DB4558/frontend-react.git
      cd frontend-react

6. **Install dependencies and run the frontend:**

   ```bash

       npm install
       npm start

6.**Usage**

    Open the browser and navigate to http://localhost:3000.
    

    
