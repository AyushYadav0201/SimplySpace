# SimplySpace - MERN Full-Stack Project

## Overview
Welcome to SimplySpace, a comprehensive MERN (MongoDB, Express.js, React.js, Node.js) full-stack project aimed at providing a seamless and intuitive platform for users to post listings and make purchases, particularly focusing on housing and furniture. The application leverages modern technologies such as Google authentication, Stripe for secure transactions, Google Maps for location referencing, and internationalization in both English and Spanish, ensuring a rich and diverse user experience.

## Project Description
SimplySpace is designed to encapsulate the essence of simplicity, security, and functionality, mirroring the ease of use found in popular platforms like Facebook Marketplace. Its core features include:

- **Google Authentication:** Users can securely sign up and log in through Google authentication, ensuring a streamlined and secure access process.
- **Interactive Dashboard:** An intuitive dashboard allows users to effortlessly manage their profiles and post listings, ensuring a smooth and user-centric experience.
- **Seamless Payment Processing:** Integration with Stripe enables users to make purchases with ease, while providing a transparent and trackable transaction history.
- **Location Referencing:** Listings incorporate Google Maps for easy and accurate location referencing, enhancing the usability and reliability of the platform.
- **Internationalization:** Supporting both English and Spanish languages broadens accessibility and inclusivity for a diverse user base.

## Task Distribution
### Team Members & Responsibilities
- **Frontend Developer:** Crafting the dashboard layout, implementing user authentication features, and designing transactional pages for a seamless user interface.
- **Backend Developer:** Setting up the Node.js server, integrating MongoDB for efficient data management, and implementing robust APIs for seamless backend functionality.
- **Full Stack Developer:** Overseeing the integration of React.js to harmonize frontend and backend interactions, ensuring a cohesive and efficient application.
- **Testing and Documentation Specialist:** Engaged in comprehensive unit testing, end-to-end testing, and meticulous documentation to ensure the project's reliability and maintainability.

## Squad
[Ayush Yadav] (002878172): Aka "Ayush_002878172"
[Dushyant Singh Rajput] (002840002): Aka "Dushyant_002840002"
[Omkar Nitin Vaity] (002836207): Aka "Omkar_002836207" 
[Ravikumar Gangenapura Suresh] (002875960): Aka "Ravi_002875960"

### API Specifications
#### OpenAPI Specification Yaml Files
- **User Authentication API**
  - Functionality: Manages user authentication processes, including login, signup, and secure authentication methods.
  - Endpoints: /api/auth/login, /api/auth/signup, /api/auth/logout.
  
- **Listing Management API**
  - Functionality: Facilitates Create, Read, Update, and Delete (CRUD) operations for housing and furniture listings.
  - Endpoints: /api/listings, /api/listings/create, /api/listings/:id.
  
- **Payment Processing API**
  - Functionality: Integration with payment gateways (e.g., Stripe) to handle secure and streamlined payment transactions.
  - Endpoints: /api/payments/process, /api/payments/history.
  
- **Geolocation Services API**
  - Functionality: Incorporates Google Maps API to provide location-based data and referencing.
  - Endpoints: Utilizes geolocation endpoints for mapping and location data retrieval.
  
- **Language Translation API**
  - Functionality: Implements internationalization features, allowing users to switch between languages.
  - Endpoints: Handles language selection and translation functionalities.
  
- **Profile Management API**
  - Functionality: Manages user profile information, enabling users to edit, update, and delete their profiles.
  - Endpoints: /api/profile, /api/profile/edit, /api/profile/delete.

## Development Milestones
### Milestone 1: Foundation Setup and User Authentication
#### User Stories
- **Secure Sign Up and Login:** Enable users to securely sign up and log in, ensuring the authenticity and security of user accounts.
- **Secure Logout:** Provide a seamless and secure logout functionality for user sessions.
- **Email Verification:** Implement email verification for account confirmation to enhance security measures.

### Milestone 2: Listing Management and Payment Integration
#### User Stories
- **Listing Operations:** Allow users to perform Create, Read, Update, and Delete (CRUD) operations for housing and furniture listings.
- **Seamless Payment Processing:** Implement a streamlined payment process for purchasing listed items.
- **Location Visualization:** Display listing locations on a map for better user understanding and navigation.

### Milestone 3: Multilingual Support and Profile Management
#### User Stories
- **Multilingual Support:** Enable users to seamlessly switch between languages (English and Spanish) within the application.
- **Profile Management:** Provide users with the functionality to edit, update, and delete their profile information.

### Milestone 4: Enhancement and Refinements
#### User Stories
- **Transaction Notifications:** Implement notification features for users to receive updates on successful transactions.
- **Performance Optimization:** Optimize application performance for enhanced speed and efficiency.
- **UI/UX Improvements:** Enhance the overall user interface and experience for better usability and navigation.
