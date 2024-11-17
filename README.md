# Bechdel Test Analysis: Automating Gender Representation Evaluation in Films

## Overview

This repository contains the code, data, and findings for our project on applying and automating the **Bechdel Test** to a selection of Oscar-nominated films. The Bechdel Test, designed to assess gender representation in movies, poses three questions:
1. Does the film feature at least two women?
2. Do these women speak to each other?
3. Is their conversation about something other than a man?

Our goal was to evaluate gender representation programmatically by analyzing film scripts, cast details, and dialogue content using a relational database and natural language processing techniques.

---

## Introduction

The film industry significantly influences cultural norms and gender perceptions. Despite progress in representation, gender biases remain evident. 
This study automates the Bechdel Test for 20 Oscar-nominated films, utilizing structured data from scripts and casts to identify trends in female representation. Our findings highlight the persistent disparities in gender portrayal.

---

## Features

- **Automated Bechdel Test Evaluation**: Determines compliance with each level of the Bechdel Test.
- **Database Integration**: Uses an SQLite database to store and analyze structured data.
- **Script Analysis**: Extracts character interactions from film scripts.
- **Statistical Insights**: Visualizes data on gender distribution and Bechdel Test compliance.

---

## Data Sources
Publicly available data from:
- [Internet Movie Script Database (IMSD)](https://imsdb.com/) for script data.
- [Internet Movie Database (IMDb)](https://www.imdb.com/) for cast and role information.
- [Names Dataset](https://pypi.org/project/names-dataset/) for gender inference based on character names.

### Prerequisites
- Python 3.x
- SQLite
- Required libraries (code)

