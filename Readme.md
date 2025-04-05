#  Online Marketing Brand Analysis Framework

This project presents a comprehensive framework for analyzing **brand popularity and online presence** using a combination of **web scraping**, **network analysis**, and **sentiment analysis**. The system builds a graph-based representation of online brand mentions and ranks them using **PageRank** and sentiment scores to identify the most influential and positively received content.

> ⚡ Powered by `BeautifulSoup`, `Neo4j`, `NetworkX`, and `TextBlob/VADER`.

---

##  Objectives

- Evaluate the **digital visibility and popularity** of brands  
- Analyze **sentiment** surrounding brand mentions  
- Use **graph-based PageRank** to identify high-impact content  
- Recommend **effective marketing and advertising channels**

---

## 🧠 Framework Overview

###  1. Web Scraping
- Scrape search engine results for brand-related queries using `BeautifulSoup`
- Extract metadata, URLs, snippets, and page content

###  2. Graph Network Construction
- Build a **brand-centric network** where:
  - Nodes represent web pages or domains
  - Edges are based on co-occurrence, references, or domain relationships
- Store and visualize using **Neo4j** or **NetworkX**

###  3. PageRank Calculation
- Apply **PageRank** to identify influential pages in the brand network
- Prioritize content for brand exposure and partnerships

###  4. Sentiment Analysis
- Perform sentiment analysis on scraped content using:
  - `TextBlob`, `VADER`
- Combine sentiment score with PageRank to rank content by **impact + positivity**

---

## 🛠️ Tech Stack

-  **BeautifulSoup** – for web scraping
-  **Neo4j** / **NetworkX** – for building and analyzing networks
-  **TextBlob**, **VADER** – for sentiment scoring
-  **Matplotlib**, **Seaborn** – for visualizations
-  **Python**, **Pandas**, **NumPy**

---



