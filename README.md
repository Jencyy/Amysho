# 🛒 My E-Commerce React Project

This project is a full-fledged e-commerce application built with React, using the `useContext` hook extensively. The application features a unified user and admin interface, authentication via Firebase, and essential e-commerce functionalities such as product filtering and an "Add to Cart" feature.

## ✨ Features

- **👥 User and Admin Roles:** The application distinguishes between user and admin roles. The admin interface is accessible only by logging in with a specific account.
- **🔐 Authentication:** Users must sign up and log in to interact with the application, with authentication managed by Firebase.
- **🛍️ Product Listing:** Products are displayed with filtering options based on categories and prices.
- **🛒 Add to Cart:** Users can add products to their cart, with the cart data stored locally.
- **📱 Responsive Design:** The UI is responsive and adjusts seamlessly across various screen sizes.
- **🔥 Firebase Integration:** Firebase is used for backend services, including user authentication.

## 🔑 Admin Access

To access the admin interface, use the following credentials:

- **Email:** `jenu@gmail.com`
- **Password:** `121212`

Logging in with this account grants access to the application's administrative features. Other accounts will be restricted to the user interface.

## 🛠️ Installation

To get a local copy up and running, follow these simple steps:

### Prerequisites

Ensure that you have the following installed:

- **Node.js**
- **npm (Node Package Manager)**
- **Git**

### Installation Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/Jencyy/Amysho.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Amysho
    ```
3. Install npm packages:
    ```bash
    npm install
    ```

### Firebase Configuration

This project uses Firebase for authentication and other backend services. You'll need to set up your Firebase project and configure it in your React application.

- Go to the Firebase Console and create a new project.
- Create a Firebase app and add your project's Firebase configuration to your React project.
- Replace the Firebase configuration in your project with your own. This configuration is typically found in a file like `firebaseConfig.js` or within your main application file.

## 🚀 Running the Application

Once everything is set up, you can start the application with:

```bash
npm run dev
```
This will start the development server, and you can view the application in your browser at http://localhost:5173.

## 💡 Usage
Sign Up/Log In: Users can create an account or log in to access the application's features.
Admin Access: Log in with the admin credentials provided above to access the admin panel.
Product Management: Browse products, apply filters, and add items to your cart.
Cart Management: View and manage your cart with the added products.

## 🛠️ Technologies Used
React: Frontend framework
Firebase: Backend services and authentication
Context API: State management
CSS/Tailwind CSS: Styling
React Router: Navigation

## 📂 Project Structure
src/

├── components/          # Reusable UI components like Header, Footer, ProductCard, Filter, Modal

├── context/             # Context API implementation for global state management

├── firebase/            # Firebase configuration and utilities

├── pages/               # Different pages (e.g., Home, Admin, Product Details)

├── App.js               # Main application component

└── index.js             # Entry point of the application


## 🤝 Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss potential changes.

