# Conceps Application

A responsive React application for managing users, products, and business registrations.

## 🌟 Features

### 🔐 Authentication
- **Secure Sign In**: Admin credentials validation logic.
- **OTP Verification**: 
  - 6-digit input with auto-focus functionality.
  - Support for backspace navigation and pasting codes.

### 📊 Dashboard
- **Visual Analytics**: Interactive charts using `recharts` (Sales Trends, User Stats).
- **Key Metrics**: At-a-glance cards for Revenue, Users, and Orders.

### 📝 Registration Module
- **Comprehensive Form**: Captures personal and professional details (Department, Location, Experience).
- **Smart Validation**: 
  - **Real-time JavaScript Validation**: Replaces default HTML attributes for custom behavior.
  - **Regex Patterns**: Enforces specific formats for Name (3+ chars), Email, and Phone (10 digits).
  - **Immediate Feedback**: Error messages appear dynamically as the user types.

### 👥 User Management
- **User List**: Tabular view of registered users.
- **Data Presentation**: Styled tables with status indicators.

### 🛍️ Product Management
- **Product Catalog**: Grid layout displaying product cards with ratings and prices.
- **Product Details**: Dedicated page for individual product information.

### 🎨 UI/UX
- **Responsive Sidebar**: Navigation adapted for the requested application flow.
- **Modern Styling**: Clean aesthetic using CSS Modules.
- **Theme Support**: Integrated **Dark Mode** toggle for comfortable viewing.
- **Interactive Elements**: Hover effects, transitions, and focused inputs.

---

## 🚀 Application Workflow

### 1. Authentication
*   **Sign In Page** (`/auth/signin`)
    *   **Action**: Enter valid credentials.
    *   **Default Credentials**: `admin@gmail.com` / `Admin@123`
    *   **Next Step**: Redirects to **Verify OTP**.

*   **Verify OTP** (`/auth/verify-otp`)
    *   **Action**: Enter the 6-digit OTP.
    *   **Next Step**: Redirects to **Dashboard**.

### 2. Core Navigation
The Sidebar follows this specific order:
1.  **Dashboard** (`/`)
2.  **Registration** (`/forms/registration`)
3.  **User List** (`/lists/users`)
4.  **Products** (`/products`)

---

## 💻 Installation & Setup

Follow these steps to get the project running on your local machine.

### Prerequisites
- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation Steps

1.  **Clone the repository**
    ```bash
    git clone <repository-url>
    cd conceps
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Start the development server**
    ```bash
    npm start
    ```

4.  **Access the application**
    Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🛠 Tech Stack
*   **Frontend**: React.js
*   **Styling**: CSS Modules
*   **Routing**: React Router DOM
*   **Icons**: React Icons
*   **Charts**: Recharts
