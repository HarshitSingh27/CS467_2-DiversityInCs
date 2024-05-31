# Diversity in CS Faculty

## Project Overview

This project aims to visualize and analyze the diversity among Computer Science faculty across various universities in the United States. By creating composite images of faculty members, the project provides a visual representation of diversity, highlighting the racial and gender composition within academic departments.

## Table of Contents

1. [Introduction](#introduction)
2. [Research Question](#research-question)
3. [Methodology](#methodology)
4. [Demo](#demo)
5. [Limitations](#limitations)

## Introduction

Diversity is a key element of university excellence. This project addresses the need to visually compare diversity across universities by using average profile pictures of CS faculty. It provides insights into the racial and gender diversity within these departments.

## Research Question

1. What is the racial composition reflected in the composite image of CS faculty in the United States, and what does it tell us about diversity in these departments?
2. How do university, departmental, and individual faculty characteristics influence the visual diversity in a composite image of CS faculty?

## Methodology

### Data Collection

- Created CSV files to map URLs to each school for scraping.
- Iterated through the CSV files to sanitize and organize data for filing.
- Maintained a neat and organized data directory.

### Dataset Summary

The dataset contains 3,900 professor profile pictures from 48 universities, categorized by rankings and types (e.g., mainstream universities, women's colleges, minority-serving institutions).

### Tools and Analysis

- Used **Facer**, a Python package, to generate average faces with modifications to the code.
- Implemented the website using **JavaScript**, **HTML**, and **CSS**.
- Utilized **AWS** cloud-based solutions for data processing and **Tableau** for data visualization.

### Process

1. Detected faces in images and removed those that could not be analyzed, storing them in a separate repository.
2. Applied facial landmark predictors to ensure uniformity in position, size, and background of the profile pictures.
3. Generated the average face for each dataset.

## Demo

You can access the demo of our project [here](https://cs-faculty-diversity.web.app/).

## Limitations

1. Not all universities list complete or up-to-date information regarding faculty status, leading to potential inaccuracies in our labeling.
2. Selection bias due to:
   - Absence of profile pictures for some faculty members (especially women and teaching professors).
   - Exclusion of poor quality images by the algorithms.

## Results

The project results include composite images reflecting the diversity or lack thereof among CS faculty. The visual data helps understand the diversity dynamics and guides efforts to improve inclusivity in academia.
