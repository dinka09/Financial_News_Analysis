# financial-news-analysis
## Overview
This project involves setting up the development environment, configuring version control with Git and GitHub, and performing an initial Exploratory Data Analysis (EDA) on a dataset of financial news. These steps will lay the groundwork for further analysis and model development.
# Getting Started
## 1. Repository and Branch Setup
1. **Create a GitHub Repository:**

Create a new repository on GitHub named `financial-news-analysis`.

Clone the repository to your local machine:
```bash
git clone https://github.com/olaniSiyum/financial-news-analysis.git
```
2. **Create a New Branch**
Create and switch to a new branch named `task-1`
```bash
git checkout -b task-1
```
3. **Set Up Version Control:**
Ensure `.gitignore` is properly configured to exclude unnecessary files (virtual environment files, data).
```bash
echo "venv/" >> .gitignore
```
## 2. Development Environment Setup
1. **Create a Virtual Environment:**
Set up a virtual environment to manage dependencies:
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```
2. **Install Dependencies:**
Create a `requirements.txt` file listing necessary packages(like pandas
matplotlib seaborn nltk pytest numpy)
```bash
pip freeze > requirements.txt
```
## 3. Initial Exploratory Data Analysis (EDA)
**Publisher Activity:** Count the number of articles per publisher.
**Publisher Activity:** Count the number of articles per publisher.
![Publication Trends Over Time](https://github.com/dinka09/Financial_News_Analysis/blob/main/images/Image1.pnj.png)

**Sentiment Analysis:**
![Sentiment Distribution](https://github.com/dinka09/Financial_News_Analysis/blob/main/images/sentiment.png)
**Topic Modeling:**
![Word Cloud of Headlines](https://github.com/dinka09/Financial_News_Analysis/blob/main/images/wordcload.png)