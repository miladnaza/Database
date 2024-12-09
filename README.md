# Book E-commerce Website - Database

This repository contains the database schema and seed data for the Book E-commerce Website project. The database is structured to efficiently store and manage information about users, books, and advertisements, enabling seamless functionality for the application.
## 📋 Features

### User Data Management
- Stores and manages user information, including personal details and authentication data.
### Book Inventory
- Maintains detailed records of books, including their titles, authors, categories, ratings, stock availability, and descriptions.
### Advertisement Management
- Displays promotional content dynamically to enhance the user experience.

## 🗂 Collections

### 1. **Users**  
**Purpose:** Stores user information, including authentication details.  
**Fields:**
- `firstName`: User's first name.
- `lastName`: User's last name.
- `email`: Unique email for authentication.
- `password`: Hashed password for secure authentication.

### 2. **Books**  
**Purpose:** Stores book details to support browsing, searching, and purchasing functionalities.  
**Fields:**
- `shortTitle`: A brief title for display purposes.
- `fullTitle`: Complete title of the book.
- `author`: Author's name.
- `ratings`: Average user ratings for the book.
- `price`: Price of the book.
- `category`: Book category (e.g., Fiction, Adventure).
- `stock`: Available stock for the book.
- `image`: URL or file path to the book's cover image.
- `isbn`: International Standard Book Number.
- `description`: A brief synopsis of the book.

### 3. **Ads**  
**Purpose:** Stores advertisements to display dynamic promotional content on the website.  
**Fields:**
- `text`: The advertisement text to be displayed.
  
## 🛠 Prerequisites
  - MongoDB installed locally or a cloud instance, such as MongoDB Atlas.
  - Access credentials for connecting to the MongoDB instance if hosted on the cloud.

## 🤝Contributors
  - Niloofar Koochakian Jazi
  - Ansh Satish Acharya
  - Milad Nazari
  - Utsav Ketanbhai Mistry
  - Yeoul Kang
