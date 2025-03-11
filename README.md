# 📌 Mess Token System – Student App  



## 🏫 About the Project  
The **Mess Token System – Student App** is a mobile application designed for students to manage their mess tokens, and transactions efficiently. This app allows students to redeem, track their meals while ensuring smooth communication with mess owners.  

## ✨ Features  
✅ **User Authentication** – Secure login for students.  
✅ **Token Management** – Students can generate and use meal tokens.  
✅ **Transaction History** – Track past meal records and payments.  
✅ **Notifications** – Receive important notifications.  

## 🛠️ Tech Stack  
- **Frontend:** React Native (CLI)  
- **Backend:** Node.js, Express  
- **Database:** MongoDB  
- **Real-time Communication:** Socket.io (for notifications)  

## 📲 Installation & Setup  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/your-repo/mess-token-system-student.git
cd mess-token-system-student
```

### 2️⃣ Install Dependencies  
```sh
npm install
```

### 3️⃣ Run the App  
For Android:  
```sh
npx react-native run-android
```
For iOS (Mac required):  
```sh
npx react-native run-ios
```

## 📡 API Endpoints (Backend Integration)  
- **POST** `/auth/login` – Student login  
- **GET** `/tokens` – Fetch available meal tokens  
- **POST** `/tokens/book` – Redeem a meal token  
- **GET** `/transactions` – View transaction history 

## 🔔 Notifications  
- **Real-time notifications** using **Socket.io** for meal confirmations and important updates.  

## 📌 Future Enhancements  
🚀 QR Code-based token verification  
🚀 Wallet-based payment system integration  

## 👨‍💻 Contributing  
1. Fork the repository.  
2. Create a new branch (`feature-branch`).  
3. Commit your changes.  
4. Push to your branch and open a pull request.  

## 📝 License  
This project is licensed under the **MIT License**.  

---

### 💡 Need Help?  
If you have any queries or feature requests, feel free to reach out! 🚀
