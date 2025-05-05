Airbnb Clone Project
Objective
The Airbnb Clone project simulates the development of a robust, scalable backend for a property rental platform. It focuses on essential functionalities such as user management, property listings, bookings, payments, and reviews, mimicking Airbnb’s core features.

Project Goals
User Management: Secure user registration, authentication, and profile handling.
Property Management: CRUD operations for property listings.
Booking System: Booking creation, management, and scheduling.
Payment Processing: Transaction handling and payment tracking.
Review System: Posting and managing property reviews and ratings.
Data Optimization: Efficient storage and retrieval of data using optimized database structures.

 Team Roles
- Backend Developer – Builds the server and logic.
- Database Admin – Manages the data.
- Frontend Developer – Creates the user interface.
- DevOps Engineer – Manages deployment and updates.
  
Technology Stack
- Django – Builds the backend.
- PostgreSQL – Stores data.
- GraphQL – Lets frontends fetch data easily.
- Docker – Helps run the app anywhere.
- GitHub Actions – Automates testing and deployment.

Database Design
Main Entities:
- User – name, email, password
- Property – title, location, price
- Booking – user, property, dates
- Review – rating, comment
- Payment – amount, status

Feature Breakdown
- User Management – Login, signup, profile.
- Property Management – Add and update listings.
- Booking System – Book places to stay.
- Reviews – Rate and review properties.
- Payments – Pay for bookings.

API Security
- Authentication – Login with secure password.
- Authorization– Only certain users can do certain things.
- Rate Limiting– Stops too many requests.
- Data Encryption– Protects sensitive info.

CI/CD Pipeline
We’ll use GitHub Actions and Docker to:
- Run tests automatically
- Deploy the app easily

