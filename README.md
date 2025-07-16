Here you go, Aaina! Below is the **complete content for your `README.md` file** — professionally formatted, easy to copy-paste directly into your project folder (`WEB SCRAPPING`).

---

### 📄 `README.md` (Copy everything below)

```markdown
# 🕸️ Web Scraping Projects – Python for Everybody (PY4E)

This repository contains two Python web scraping projects created as part of the [Using Python to Access Web Data](https://www.py4e.com/) course by Dr. Charles Severance. These projects demonstrate how to use `urllib` and `BeautifulSoup` to scrape and process HTML data from web pages.

---

## 📁 Folder Structure

```

WEB SCRAPPING/
├── follow\_links.py
├── extract\_span\_numbers.py
├── .gitignore
└── README.md

```

---

## 🧠 Project Descriptions

### 1️⃣ `follow_links.py`

**Objective**:  
Follow a series of hyperlinks based on a specific position and number of repetitions, printing each URL visited, and finally displaying the **last name** found.

**How it works**:
- Starts at a given URL.
- Finds the link at the Nth position (1-based).
- Follows it and repeats this process a specific number of times.

**Sample Input**:
```

Enter URL: [http://py4e-data.dr-chuck.net/known\_by\_McKay.html](http://py4e-data.dr-chuck.net/known_by_McKay.html)
Enter count: 7
Enter position: 18

```

**Sample Output**:
```

Retrieving: [http://py4e-data.dr-chuck.net/known\_by\_McKay.html](http://py4e-data.dr-chuck.net/known_by_McKay.html)
...
The answer to the assignment is: Sophia

```

---

### 2️⃣ `extract_span_numbers.py`

**Objective**:  
Parse the HTML content of a webpage, extract numbers from all `<span>` tags, and compute their **sum and count**.

**Sample Input**:
```

Enter URL: [http://py4e-data.dr-chuck.net/comments\_42.html](http://py4e-data.dr-chuck.net/comments_42.html)

```

**Sample Output**:
```

Count: 50
Sum: 2758

````

---

## ⚙️ Requirements

- Python 3.x
- BeautifulSoup library

**Install required library**:
```bash
pip install beautifulsoup4
````

---

Running the Programs

In your terminal or VS Code terminal:

```bash
cd "WEB SCRAPPING"

# Run link follower
python follow_links.py

# Run span number extractor
python extract_span_numbers.py
```

## 📚 Reference
These projects are part of:
**Course**: Using Python to Access Web Data
**Instructor**: Dr. Charles Severance (Dr. Chuck)
**Website**: [https://www.py4e.com/](https://www.py4e.com/)
