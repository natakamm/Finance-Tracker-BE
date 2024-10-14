
# FinanceEase Backend Service

FinanceEase is a comprehensive finance tracking application built as a backend service using **Node.js**, **Express**, and **MongoDB**. This API-driven backend enables secure user authentication, income and expense tracking, and robust data management for personal finance monitoring.

### Project Overview
FinanceEase was developed over a three-week period to provide users with an intuitive interface for managing their finances. The application supports the creation and management of transactions, user authentication, and personalized categorization of income and expenses.

### Features
- User Authentication: Secure authorization and authentication using JWT (JSON Web Tokens) for user sessions.
- Income and Expense Tracking: Users can create, edit, and manage their financial transactions.
- Preset and Custom Categories:
  - Predefined categories available for all users.
- Ability for users to create custom categories for their income and expenses.
- Data Management: Secure data handling with MongoDB for storing user and transaction information.
- File Upload:
  - Support for uploading invoices and category icons using Multer and Cloudinary.


### Models
The application consists of the following key models:

- **UserModel.js**: Handles user data, authentication, and authorization.
- **TransactionModel.js**: Manages financial transactions, including income and expenses.
- **CategoryModel.js**: Defines and manages categories for transactions, allowing users to categorize their financial activities.

### Technologies Used
- **Node.js**: JavaScript runtime environment for building the backend.
- **Express**: Web application framework for Node.js, facilitating API creation.
- **MongoDB**: NoSQL database for secure and scalable data storage.
- **JWT**: Token-based authentication for secure user sessions.
- **Multer**: Middleware for handling file uploads.
- **Cloudinary**: Cloud storage service for managing uploaded files.
