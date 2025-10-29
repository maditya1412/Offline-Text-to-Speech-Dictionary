# 🗣️ Offline Text-to-Speech English Dictionary

An **offline English Dictionary** built using **Python**, **Tkinter**, **SQLite**, and **pyttsx3**.
This application lets users **search, add, and listen** to words, meanings, and example sentences — all without requiring an internet connection.



## 🚀 Features

* 🔎 **Search words** and get instant meanings and examples
* 🗣️ **Text-to-speech** support for word, meaning, and example pronunciation
* ➕ **Add new words** with meanings and examples to your local database
* 🕓 **Search history** window for quick reference
* 💾 Works **completely offline** using SQLite database


## 🧠 Technologies Used

* **Python 3.x**
* **Tkinter** – for GUI design
* **SQLite3** – for local database storage
* **pyttsx3** – for text-to-speech functionality
* **json** and **messagebox/simpledialog** – for user interaction



## ⚙️ How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/offline-dictionary.git
   ```
2. Navigate to the project directory:

   ```bash
   cd offline-dictionary
   ```
3. Install dependencies (if not installed):

   ```bash
   pip install pyttsx3
   ```
4. Run the program:

   ```bash
   python dictionary.py
   ```



## 📂 Database

The app uses an SQLite database file named `dictionary.db`.
It automatically creates the table `words` if it doesn’t exist:

```sql
CREATE TABLE IF NOT EXISTS words (
    word TEXT PRIMARY KEY,
    meaning TEXT,
    example TEXT
);
```



## 💡 Example Usage

* Type a word → Click **Search**
* Hear pronunciation → Click **Word🔊**
* Add new entries → Click **Add Word**
* View your past searches → Click **History**

