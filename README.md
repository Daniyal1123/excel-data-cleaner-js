# excel-data-cleaner-js 🧹

An interactive, browser-based tool built purely with **HTML and Vanilla JavaScript** to quickly clean, transform, and prepare Excel data (.xlsx, .xls) files without relying on server-side processing or external software.

## ✨ Key Functionalities

This tool now covers all core data manipulation and cleaning tasks through its four tabbed interfaces:

### 1. 🧹 Cleanup & Filtering
* **Live Filtering:** Instantly filter the displayed data by typing any keyword.
* **Data Sorting (NEW):** Reorder rows based on any column in **Ascending** or **Descending** order (handles text and numeric values).
* **Text Transformation:**
    * **Convert Case:** Change text to **UPPERCASE**, **lowercase**, or **Title Case**.
    * **Trim Whitespace:** Remove unnecessary leading and trailing spaces.
* **Email Processing (Advanced):**
    * **Remove specific email entries** from a single multi-email cell based on keywords.
    * **Flag rows** by adding a new column based on keywords found in the email column.
* **Structural Cleanup:**
    * Delete **duplicate rows** based on a unique key column.
    * Remove entire columns.

### 2. 🚫 Null Value Management
* **Find Empty Cells:** Identify and count rows containing empty/null cells based on a column selection.
* **Fill Empty Cells:** **Fill** empty cells with a custom default value (e.g., `N/A`, `0`).
* **Delete Rows:** **Delete** entire rows that contain an empty cell in the specified column.

### 3. 🧮 Calculations
* **Split Column (NEW):** Break a single column (e.g., "Full Address") into multiple new columns using a specified **delimiter** (e.g., comma, space).
* **Merge Columns:** Combine multiple columns into a single new column (e.g., First Name + Last Name = Full Name).
* **Calculate New Column:** Create a new column using standard arithmetic operations (+, -, \*, /) on two existing numeric columns.

### 4. ⬇️ Export
* **File Upload & Export:** Load standard Excel files and download the final processed dataset as a new Excel file.

## 🚀 How to Use

Since this is a client-side application (meaning it runs entirely in your browser), **no installation or server setup is required.**

1.  **Download:** Download the repository.
2.  **Open:** Locate the main file, **`index.html`**, and open it directly in any modern web browser (Chrome, Firefox, Edge, etc.).
3.  **Process:** Upload your file and use the tabs to perform operations. All processing is instant and local.

## 🛠️ Technology Stack

* **HTML, CSS (Modernized Styling), & Vanilla JavaScript:** Core structure and all processing logic is executed directly in the browser.
* **SheetJS (xlsx.full.min.js):** Used for robust client-side reading and writing of Excel files.

## 💡 Why Use This?

* **Privacy & Security:** All data processing happens locally in your browser. Data is **never** uploaded to a server.
* **Speed:** Instantaneous feedback and processing for moderately sized datasets.
* **Simplicity:** Zero setup time—just open the HTML file.

---

## 🤝 Contribution

Contributions, issues, and feature requests are welcome!

---

