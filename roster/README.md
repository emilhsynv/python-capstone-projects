# 📌 Roster Database Project  

A simple Python script that processes **user-course-role** data from JSON and stores it in an **SQLite database**.  

## 🔹 Features  
✔️ Stores **users, courses, and roles** in a relational database  
✔️ Prevents duplicate entries using constraints  
✔️ Loads and updates data dynamically  

## 🚀 How to Run  

1. **Ensure Python & SQLite3 are installed**  
2. **Prepare JSON Data** (`roster_data.json`):
   ```json
   [
     ["Alice", "Python101", 1],
     ["Bob", "Python101", 0]
   ]

3. **Run the script**
(Default file: roster_data.json)
4. Check rosterdb.sqlite in DB Browser for SQLite.
5. Reset database:
   rm rosterdb.sqlite  # Mac/Linux
   del rosterdb.sqlite  # Windows

✅ Great for learning Python, SQLite, and relational data handling! 🚀
