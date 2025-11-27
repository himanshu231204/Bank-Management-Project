 🏦 Bank Management System using Streamlit

A simple and beginner-friendly web-based bank application built using **Python** and **Streamlit**. It allows users to perform basic banking operations such as account creation, deposit, withdrawal, update, and deletion.

---

## 🚀 Features

- 📝 Create Account (with name, age, email, and 4-digit PIN)
- 💵 Deposit Money (up to ₹10,000 at once)
- 💸 Withdraw Money (with balance check)
- 🔍 View Account Details
- 🛠️ Update Name, Email or PIN
- 🗑️ Delete Account

---

## 🧰 Tech Stack

| Component       | Technology                   |
|----------------|------------------------------|
| Frontend       | Streamlit (Python Framework) |
| Backend Logic  | Python (OOP with Classes)     |
| Data Storage   | JSON file (`data.json`)       |
| Deployment     | Streamlit Community Cloud     |
| Version Control| Git & GitHub                  |

---

## 📁 Project Structure

Bank-Management-Project/
├── app.py # Streamlit frontend (main entry point)
├── hello.py # Bank class and logic
├── data.json # Stores user account data
├── requirements.txt # Python dependencies for deployment


---

## 📚 Python Libraries Used

- `streamlit` – For building the web interface  
- `json` – For reading/writing user data  
- `random` – For generating random account numbers  
- `string` – For characters in account ID  
- `pathlib` – To check file existence

> Note: All libraries except `streamlit` are built-in.

---

## 🧑‍💻 How It Works

1. User creates an account by entering personal info and a 4-digit PIN
2. The account is assigned a unique account number
3. Data is stored in `data.json` file
4. User can log in using account number and PIN to:
   - Deposit or withdraw money
   - View account info
   - Update or delete the account

---

## 🌐 Live Deployment

- 🚀 Deployed on: [Streamlit Community Cloud](https://streamlit.io/cloud)
- 🔗 Live App: [Click here to open](https://<your-username>-bank-management-project.streamlit.app)

> Replace `<your-username>` with your actual Streamlit username.

---

## ⚠️ Limitations

- Data is stored in a local JSON file — not suitable for production use
- Streamlit Cloud does not persist JSON data after restart
- No login session handling — uses simple PIN verification

---

## ✅ Future Improvements

- Use SQLite or Firebase for permanent data storage
- Add user login sessions
- Add transaction history
- Improve UI with animations and charts

---

## 📄 License

This project is open-source and free to use.

---

## 🙋‍♂️ Author

Developed by **Himanshu Kumar**

- GitHub: [@himanshu231204](https://github.com/himanshu231204)
