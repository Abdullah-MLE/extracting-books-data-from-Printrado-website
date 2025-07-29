Great! Here's a complete and clean `README.md` file in English for your project **"Extracting Books Data from Printrado Website"**:

---

````markdown
# 📚 Extracting Books Data from Printrado Website

This project is a web scraping script designed to extract book data from the [Printrado](https://www.printrado.com/) website. It collects key information from multiple pages and stores it in a structured format for analysis or record-keeping.

---

## 🚀 Project Overview

The script performs the following tasks:

- Sends requests to Printrado’s book listing pages
- Parses the HTML content of each page
- Extracts information such as:
  - Book title
  - Book URL
- Saves the results in a CSV file

---

## 🛠️ Technologies Used

- **Python 3**
- **requests** – to fetch page content
- **BeautifulSoup** – to parse and extract data from HTML
- **pandas** – to store data in a DataFrame and export to CSV
- **time** – to handle pauses between requests

---

## 📂 How to Run

1. Make sure Python is installed on your system.
2. Install required packages:
   ```bash
   pip install requests beautifulsoup4 pandas
````

3. Run the Jupyter Notebook:

   * You can run the `.ipynb` file in Jupyter Lab, VS Code, or Google Colab.
4. After execution, the script will generate a CSV file containing the extracted book data.

---

## 📄 Output

The output is saved in a file named something like:

```
books_data.csv
```

It includes columns for:

* Book Title
* Book URL

---

## ⚠️ Notes

* The script uses `time.sleep()` between requests to avoid overloading the server.
* If the website structure changes, the scraping logic may need to be updated.

---

## 📬 Contact

For questions or suggestions, feel free to reach out.
