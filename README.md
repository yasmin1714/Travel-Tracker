# 🌍 Travel Tracker  

A simple web application to track visited countries using **Node.js, Express, PostgreSQL, and EJS**. Users can enter country names, and the app will store them in a PostgreSQL database. The visited countries are displayed on a map.


---

## 🚀 Features  

- ✅ Add visited countries to the database  
- ✅ Display total visited countries  
- ✅ Prevent duplicate entries  
- ✅ Validate country names  
- ✅ Interactive UI with EJS and CSS  

---

## 🛠️ Technologies Used  

- **Backend:** Node.js, Express  
- **Database:** PostgreSQL  
- **Frontend:** EJS, HTML, CSS  
- **Styling:** Bootstrap  

---

## 📂 Project Structure  

#### **📁 Travel-Tracker** 
#### **│── 📂 public/ # Static files (CSS, images)**
#### **│── 📂 views/ # EJS templates**
#### **│── 📜 index.ejs # Main UI template** 
#### **│── 📜 styles/main.css # Styling** 
#### **│── 📜 app.js # Main server file** 
#### **│── 📜 database_schema.sql # Database schema** 
#### **│── 📜 countries.sql # Countries table dump**
#### **│── 📜 package.json # Node dependencies**


---

## 📌 Setup Instructions  

### 🔹 1. Clone the Repository  

git clone https://github.com/YOUR_USERNAME/Travel-Tracker.git
cd Travel-Tracker

### 🔹 2. Install Dependencies
```bash
 npm install
```


### 🔹 3. Set Up PostgreSQL Database

- Make sure PostgreSQL is installed.
- Create a database named world.
```bash
CREATE DATABASE world;
```
- Import the schema:
```bash
psql -U postgres -h localhost -d world -f database_schema.sql
```
- Import countries data (if needed):
```bash
psql -U postgres -h localhost -d world -f countries.sql
```
### 🔹 4. Run the Server

```bash
 node app.js
```
The server will start at: http://localhost:3000

---

### 🎯 How to Use
- Enter a country name and click "Add".
- The country will be stored in the database.
- The total visited countries will update automatically.

---

### 🛠️ Troubleshooting
#### ❓ PostgreSQL Password Prompt Not Accepting Input?
#### 👉 Just type your password and press Enter (input is hidden for security).

#### ❓ pg_dump Not Found?
#### 👉 Add PostgreSQL bin folder to your system PATH:
```bash
set PATH=%PATH%;C:\Program Files\PostgreSQL\15\bin
```
---


## License
This project is open-source under the MIT License.

---



### **📌 Next Steps**
1. **Save this file as `README.md` in your project folder.**  
2. **Commit and push it to your GitHub repository:**  
```bash
 git add README.md
   git commit -m "Added project documentation"
   git push origin main
```
3. **Replace YOUR_USERNAME with your actual GitHub username in the repository link.**
   




