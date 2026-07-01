## Problem Statement

Analyzing restaurant dependency on food delivery platforms is difficult because valuable insights are scattered across large datasets of customer reviews and images. Manual analysis is time-consuming and inefficient, making it challenging to generate reliable business insights.

# rasd-platform-dependency-analysis

Rasd is a Flask-based web application that analyzes restaurant datasets to estimate their dependency on digital food delivery platforms. The system processes uploaded datasets, analyzes customer reviews and restaurant images, generates business indicators, and presents the results through an interactive dashboard.

---

## Problem Statement

Manually analyzing restaurant reviews and images to measure dependency on food delivery platforms is time-consuming and inefficient, especially when working with large datasets.

---

## Features

* Upload restaurant datasets in CSV and JSON formats.
* Automatic data cleaning and preprocessing.
* Detect delivery-related keywords from customer reviews.
* Analyze restaurant images using the Google Gemini API.
* Generate business indicators:

  * Digital Activity Score
  * Platform Dependency Index
  * Estimated Gig Workers
  * Registered Workers
  * Activity Gap
  * Risk Level
* Compare analysis results across restaurants.
* Interactive dashboard with charts and summary tables.

---

## Technologies Used

* Python
* Flask
* HTML
* Chart.js
* Google Gemini API

---

## Screenshots

### 1. Dataset Upload and Restaurant Selection

![Dataset Upload](screenshots/01-upload-page.png)

### 2. Dashboard Overview

![Dashboard Overview](screenshots/02-dashboard-overview.png)

### 3. Data Cleaning Report

![Data Cleaning Report](screenshots/03-data-cleaning-report.png)

### 4. Activity Gap Details

![Activity Gap Details](screenshots/04-activity-gap.png)

### 5. Analysis Summary

![Analysis Summary](screenshots/05-analysis-summary.png)

### 6. Estimated vs Registered Workers Comparison

![Workers Comparison](screenshots/06-workers-comparison.png)

### 7. Digital Activity Score Comparison

![Digital Activity Score](screenshots/07-digital-activity-score.png)

### 8. Registration Gap Comparison

![Registration Gap](screenshots/08-registration-gap.png)

### 9. Restaurants Comparison Table

![Restaurants Comparison Table](screenshots/09-restaurants-comparison-table.png)

### 10. Analysis History

![Analysis History](screenshots/10-analysis-history.png)

---

## Dataset

A demonstration dataset is included in this repository for testing and showcasing the application's functionality.

---

## Note

The Google Gemini API key is intentionally omitted from this repository. Replace the placeholder with your own API key before running the application.
