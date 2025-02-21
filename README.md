### **Step-by-Step Setup Guide** 🚀  

#### **1️⃣ Extract the ZIP File**  
- Download and extract **lic_policy_app.zip** on your system.  
- Inside, you will find two folders:  
  - **backend/** → (Node.js + Express API)  
  - **frontend/** → (Angular App)  

---

### **2️⃣ Setup Backend (Node.js + Express)**
#### **A. Install Node.js**  
If you don’t have Node.js installed, download and install it from:  
🔗 [https://nodejs.org/](https://nodejs.org/)  

To verify installation, open **Command Prompt (Windows) / Terminal (Mac/Linux)** and run:  
```sh
node -v
npm -v
```
You should see version numbers.

#### **B. Install Backend Dependencies**  
1. Open a terminal in the **backend/** folder.  
2. Run the following command to install required packages:  
   ```sh
   npm install
   ```

#### **C. Set Up Environment Variables**  
1. Open the **backend/.env** file.  
2. Update it with your **Neon Tech PostgreSQL database URL** and a secret key:  
   ```
   DATABASE_URL=your_neon_database_url
   SECRET_KEY=your_secret_key
   ```

#### **D. Start the Backend Server**  
Run:  
```sh
npm start
```
If successful, the server will start on **http://localhost:3000** ✅.

---

### **3️⃣ Setup Frontend (Angular)**
#### **A. Install Angular CLI (if not installed)**
```sh
npm install -g @angular/cli
```

#### **B. Install Frontend Dependencies**
1. Open a new terminal in the **frontend/** folder.  
2. Run:  
   ```sh
   npm install
   ```

#### **C. Start the Angular App**
Run:  
```sh
ng serve --open
```
Your app will open in a browser at **http://localhost:4200** ✅.

---

### **4️⃣ Testing the App**
- **Login as Admin** (use the credentials stored in your database).  
- **Add LIC Policies** and verify they are stored in the database.  
- **Click "Send Reminder"** → It should open the SMS app with a pre-filled draft.  

Let me know if you face any issues! 🚀
