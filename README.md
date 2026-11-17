# Stack Overflow Error Helper — Web Scraping

**A small Python utility that runs a command and, if it fails, scrapes Stack Overflow for the most relevant answer to the error.**
Built as part of the Executive Master in Big Data Science (Universidad de Navarra).

---

## What it does

1. Executes a Python command passed as a string.
2. If the command runs correctly, it prints **"works as intended"**.
3. If it raises an error, it captures the error message, searches Stack Overflow and returns the **first relevant link**.

Example:

```python
get_SOS_help(command="np.random.uniform(-1, 1, siz=100)")
# -> prints the Stack Overflow link for the TypeError raised by the typo `siz`
```

---

## Tech Stack

```
Python    requests · BeautifulSoup · lxml · Selenium · exception handling
```

---

## Project Structure

```
├── Entregable-1-TrabajoFinal.ipynb   # Functions and examples
└── README.md
```
