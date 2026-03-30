# python-assignment-part3

# 📦 Assignment Part 3 — Product Explorer & Error-Resilient Logger

## 📌 Overview

This project demonstrates practical usage of Python concepts including File Handling, API Integration, Exception Handling, and Logging.
All tasks are implemented in a single notebook/script and simulate real-world application behavior.

---

## 🧩 Tasks Completed

### ✅ Task 1 — File I/O (Read & Write)

* Created a file `python_notes.txt` using write mode.
* Added 5 predefined topics related to Python basics.
* Appended additional custom topics using append mode.
* Read file content line-by-line with numbering.
* Counted total lines in the file.
* Implemented keyword-based search (case-insensitive).

---

### 🌐 Task 2 — API Integration

* Used the DummyJSON Products API.
* Fetched 20 products using GET request.
* Displayed products in formatted table (ID, Title, Category, Price, Rating).
* Filtered products with rating ≥ 4.5.
* Sorted filtered products by price (descending).
* Retrieved products from **laptops category**.
* Simulated product creation using POST request.

---

### ⚠️ Task 3 — Exception Handling

* Implemented `safe_divide(a, b)`:

  * Handles division by zero.
  * Handles invalid input types.
* Built `read_file_safe(filename)`:

  * Handles missing file errors.
  * Uses `finally` block for cleanup message.
* Added robust exception handling in API calls:

  * ConnectionError
  * Timeout
  * General exceptions
* Created input validation loop:

  * Accepts only valid product IDs (1–100).
  * Handles invalid inputs without crashing.
  * Displays product details or error message.

---

### 📝 Task 4 — Logging System

* Implemented error logging to `error_log.txt`.
* Used timestamp format with `datetime.now()`.
* Logged:

  * ConnectionError (invalid URL test)
  * HTTP error (404 for invalid product ID)
* Ensured logs are appended across runs.
* Displayed full log file content at the end.

---

## 📁 Project Structure

```
python-assignment-part3/
├── part3_api_files.ipynb
├── python_notes.txt
├── error_log.txt
└── README.md
```

---

## ▶️ How to Run

1. Open the notebook (`part3_api_files.ipynb`)
2. Run all cells sequentially
3. The following files will be generated automatically:

   * `python_notes.txt`
   * `error_log.txt`

---

## 🛠️ Technologies Used

* Python
* requests library (for API calls)
* datetime module (for logging)

---

## 📊 Key Learning Outcomes

* Hands-on experience with file operations
* Working with real-world APIs
* Writing error-resilient code
* Implementing logging for debugging
* Input validation and user interaction

---

## ⚠️ Notes

* DummyJSON API is a mock API; POST requests simulate creation but do not store data.
* Ensure internet connection is active for API tasks.

---

## 🚀 Conclusion

This project simulates a real-world data processing workflow by combining multiple Python concepts into a single application. It focuses on robustness, clarity, and practical implementation.
