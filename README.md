# 📊 GroupDNA – WhatsApp Group Chat Analyzer

## Overview

**GroupDNA** is a Python-based analytics project that extracts meaningful insights from an exported WhatsApp group chat. The project converts raw chat data into a structured format and performs multiple analyses to understand participant activity, communication patterns, word usage, response behavior, and personality archetypes.

The project was developed as part of a **Data Analytics and Decision Support Systems (DADS)** minor project and focuses on implementing analytics using **Python Fundamentals** and **NumPy** without relying on advanced data analysis libraries.

---

## Objectives

* Parse exported WhatsApp chat data into a structured format.
* Analyze participant activity and message contributions.
* Identify peak communication periods.
* Visualize hourly activity using a NumPy-based heatmap.
* Discover frequently used words across the group.
* Study response behavior and silent streaks.
* Assign personality archetypes based on communication patterns.
* Generate a consolidated report summarizing all insights.

---

## Features

### ✅ Feature 1 – Chat Parser

* Reads the exported WhatsApp chat.
* Extracts timestamp, sender, and message content.
* Identifies system, media, and deleted messages.
* Stores valid messages in a structured format.

### ✅ Feature 2 – Group Overview

* Total messages
* Total participants
* Chat duration
* Individual message contributions
* Participant statistics

### ✅ Feature 3 – Activity Analysis

* Busiest day
* Peak activity hour
* Daily activity summary
* Hourly activity summary

### ✅ Feature 4 – NumPy Activity Heatmap

* Builds a participant × hour activity matrix.
* Represents message intensity using ASCII symbols.
* Implemented entirely using NumPy.

### ✅ Feature 5 – Word Frequency Analysis

* Top 10 most frequent words
* Participant-wise top words
* Word occurrence statistics

### ✅ Feature 6 – Response Pattern Analysis

* Average response time
* Fastest responder
* Slowest responder
* Longest silent streak

### ✅ Feature 7 – Personality Archetypes

Participants are categorized based on their communication behavior, including:

* Conversation Starter
* Story Teller
* Silent Observer
* Fast Responder
* Active Participant

### ✅ Feature 8 – Final Report

Generates a consolidated report by combining the outputs of all previous features into a structured summary.

---

## Technologies Used

* Python 3
* NumPy
* Datetime Module
* File Handling
* Lists
* Dictionaries
* Sets
* Functions

---

## Project Structure

```text
GroupDNA/
│
├── GroupDNA.ipynb          # Main Jupyter Notebook
├── hostel_bois.txt         # Sample WhatsApp chat dataset
├── README.md
└── screenshots/            # Output screenshots (optional)
```

---

## Sample Output

The project generates reports for:

* Parser Summary
* Group Overview
* Participant Statistics
* Activity Analysis
* NumPy Activity Heatmap
* Word Frequency Analysis
* Response Pattern Analysis
* Personality Archetypes
* Final GroupDNA Report

---

## Learning Outcomes

This project strengthened my understanding of:

* Text parsing
* Data preprocessing
* Python programming fundamentals
* NumPy arrays
* Dictionary-based analytics
* Date and time manipulation
* Report generation
* Problem-solving using core programming concepts

---

## Future Improvements

* Interactive visualizations
* Emoji analysis
* Sentiment analysis
* Network graph of participant interactions
* Export reports to PDF or Excel

---

## Author

**Somyajeet Satapathy**

If you found this project useful or interesting, feel free to ⭐ the repository and share your feedback.
