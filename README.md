# insider-trading
_FA 22 SEC Insider Trading Project_

## Table of Contents

-   [Introduction](#introduction)
-   [Description](#description)
-   [Project Roadmap](#project-roadmap)
-   [Setup](#setup)
-   [Relevant Links](#relevant-links)

## Introduction

We all know what insider trading is, but do we know how to detect it? What makes a trade suspicious? How does the SEC go about detecting suspicious activity from filings? Can we do _better?_ These are some questions we will try to answer!

## Description

This is an open-ended project where we analyze, synthesize, and display findings from SEC filings. Specifically, we will be exploring filings released for Q1 2020 by the SEC. Here is a sample filing for [Elon Musk](https://www.sec.gov/Archives/edgar/data/1318605/000089924322028189/xslF345X03/doc4.xml).

Some areas towe will explore
-  Python webscraping development
-  Data visualization for SEC filings
-  Interactive data analysis tools (build a website?!)
-  anything that interests you!

## Project Roadmap

**10/2,** Meeting 1: Kickoff!

-  Introductions
-  Setup
-  Exploratory Data Analysis

---

**10/9,** Meeting 2: More EDA

-  Webscraping tutorial on Yahoo Finance data
-  Further information on SEC form 4 filings
-  Encourage sub-group formulation to tailor to everyones goals
-  Group work


---
#### **10/16,** _Fall Study Break!_

---

**10/23,** Meeting 3: Group work

-   Sub-teams!
-   work on web scrapers/models/visualizations

---

**10/30,** Meeting 4: Group work

---

**11/6,** Meeting 5: Group work

---

**11/13,** Meeting 6: Group work
-  Re-evaluating goals to ensure completion by Meeting 7

---
**11/20,** Meeting 7: Penultimate
-  Start write-up

---
**12/4,** Meeting 8: Final Touches
-  Finish write-up
-  Prepare for expo
---


## Setup

There are not many dependencies needed for this project, so if you already have a virtual environment that contains what is specified in requirements.txt, feel free to skip this section.

### Virtual Environment

We are going to initialize a Python virtual environment with all the required packages. We use a virtual environment to isolate our development environment from the rest of our computer. This is helpful because it standardizes the environment we run our program in across computers.

First create a Python 3.8 virtual environment. The virtual environment creation code for Linux/MacOS is below:

```bash
python3 -m venv venv
```

Now that you have a virtual environment installed, you need to activate it. This may depend on your system, but on Linux/MacOS, this can be done using

```bash
source ./venv/bin/activate
```

Now your computer will know to use the Python installation in the virtual environment rather than your default installation.

After the virtual environment has been activated, we can install the required dependencies into this environment using

```bash
pip install -r requirements.txt
```

## Relevant Links

[MDST Calendar](https://www.mdst.club/agenda)

Dataset:

-  [Sample Filing](https://www.sec.gov/Archives/edgar/data/1318605/000089924322028189/xslF345X03/doc4.xml)
-  [Yahoo Finances](https://finance.yahoo.com/quote/TSLA/history?p=TSLA)

Interesting Articles:

-  [Conflict of Interest for Congressional Committees](https://www.nytimes.com/interactive/2022/09/13/us/politics/congress-stock-trading-investigation.html)
-  [Congress Stock Act](https://www.businessinsider.com/congress-stock-act-violations-senate-house-trading-2021-9#sen-roger-marshall-a-republican-from-kansas-3)
-  [Senator Hawley's Letter on Insider Trading](https://www.hawley.senate.gov/following-pelosi-trades-hawley-calls-hearing-banning-insider-trading-congress)