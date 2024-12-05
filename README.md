
# Web Scraping - Magazine Luiza (Magalu)

### 🛒 **About the Project**

This was one of my first web scraping projects, and I decided to create it for a very practical reason: I was planning to buy a new smartphone and wanted to track prices on the Magazine Luiza (Magalu) website. Instead of manually checking the website every day, I thought, "Why not automate this process?"

The script collects information about smartphones, such as their names, original prices, and discounted prices, making it easier to compare and track deals.

---

### ⚙️ **Features**

The script extracts the following details for each product:

- **Product Name:** The name of the smartphone or related product.
- **Price Without Discount:** The original price listed.
- **Price With Discount:** The final price after discounts.

---

### 🛠️ **Technologies Used**

- **Programming Language:**
  - Python

- **Libraries:**
  - `pandas`: For organizing and exporting the data.
  - `selenium`: To navigate the website and scrape the information.
  - `webdriver-manager`: To manage the ChromeDriver for Selenium.

---

### 📄 **Workflow**

1. **Why this project?**
   - I was curious about web scraping and wanted to try out Selenium.
   - This project gave me hands-on experience with navigating dynamic websites and extracting useful information.

2. **How it works:**
   - The script uses Selenium to visit the Magalu website and navigate through a set number of pages (e.g., 5).
   - It grabs the smartphone names, along with their discounted and non-discounted prices, from the product listings.
   - Finally, it organizes the data into an Excel file.

3. **What you get:**
   - A neat Excel file with all the extracted data, ready for analysis or price tracking.

---

### 📊 **Example Data Output**

| Product Name               | Price Without Discount | Price With Discount |
|----------------------------|------------------------|---------------------|
| Smartphone XYZ             | R$ 2,000              | R$ 1,800           |
| Smartphone ABC             | R$ 3,000              | R$ 2,700           |
| Smartphone DEF             | R$ 1,500              | R$ 1,400           |

---

### 🔧 **How to Run**

1. **Install dependencies:**
   Make sure Python is installed, then run:
   ```bash
   pip install pandas selenium webdriver-manager
   ```

2. **Run the script:**
   Execute the script to collect data from the Magalu website:
   ```bash
   python Webscraping_MagaLu.ipynb
   ```

3. **Results:**
   - The output will be saved as an Excel file (`teste_magalu.xlsx`).

---

### 🤔 **What I Learned**

- How to use Selenium to navigate and interact with dynamic websites.
- Handling challenges like loading times and missing elements during scraping.
- Organizing scraped data into a clean format using Pandas.

---

### 📬 **Contact**

If you're curious about web scraping or have suggestions, feel free to reach out!

- **GitHub:** [OscarFantozzi](https://github.com/OscarFantozzi)
- **LinkedIn:** [Oscar Fantozzi](https://linkedin.com/in/oscarfantozzi)
