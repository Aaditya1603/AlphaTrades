# AlphaTrades 📈

AlphaTrades is a full-stack, data-driven fintech trading platform inspired by Zerodha. Built using the **MERN stack**, this application focuses on secure user authentication, high-performance dashboard states, and real-time order execution.

🌐 **[Live Demo Link]** | 📁 **[Backend Repository Link - If separated]**

## 🚀 Key Features

*   **Global Theme Sync (Dark/Light Mode)** – A flawless, responsive theme toggle built natively across all application routes and custom dashboards.
*   **Secure Authentication & Authorization** – Full user lifecycle management with encrypted credentials and strict route protection.
*   **Real-Time Order Executions** – Dynamic buy and sell functionalities that process and reflect live computational data instantly on the user orders dashboard.
*   **Comprehensive Exit Dashboard** – Integrated workspace for users to manage open positions, track portfolios, and exit trades seamlessly.

## 🛠️ Tech Stack

*   **Frontend:** React.js, Tailwind CSS (or CSS/Bootstrap), HTML5
*   **Backend:** Node.js, Express.js
*   **Database:** MongoDB
*   **State Management:** [e.g., Redux Toolkit / React Context API]

## 🛠️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd alphatrades
   ```

2. **Install dependencies:**
   ```bash
   # Install frontend dependencies
   cd client && npm install
   
   # Install backend dependencies
   cd ../server && npm install
   ```

3. **Environment Variables:**
   Create a `.env` file in the server directory and configure your `MONGO_URI`, `JWT_SECRET`, etc.

4. **Run the application:**
   ```bash
   # From the root directory (if using concurrently) or separately:
   npm run dev
   ```
