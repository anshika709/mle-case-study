# mle-case-study
# Clinical Intelligence: 30-Day Hospital Readmission Risk Modeling

An end-to-end machine learning workflow utilizing penalized statistical modeling to stratify patient risk and optimize resource allocation in healthcare settings.

---

## 📋 Executive Summary

Thirty-day hospital readmissions are a vital benchmark for clinical quality. This repository contains an educational, end-to-end pipeline leveraging a synthetic dataset of 10,000 patient records to predict readmission risks using **L2-Penalized (Ridge) Logistic Regression**.

> ⚠️ **Disclaimer:** For educational and demonstration purposes only. Uses synthetic data and is not validated for live clinical deployment.

---

## 🎯 Core Objectives

Binary classification of patient risk outcomes within a 30-day window:
* **`0`**: Stable (No readmission)
* **`1`**: High Risk (Readmission occurred)

---

## 📊 Feature Architecture & Data Schema

Tracks 15 distinct clinical, demographic, and historical features across a 10,000-record synthetic cohort:
* **Demographics:** `Age`, `Gender`
* **Vitals & Biometrics:** `Heart rate`, `Systolic/Diastolic BP`, `Temperature`, `Oxygen saturation (SpO2)`
* **Medical History:** `Diabetes`, `Hypertension`, `Number of diagnoses`, `Previous readmission`
* **Utilization:** `Length of stay`, `Prior visits`, `Emergency visits`, `Inpatient visits`

---

## ⚙️ Model Architecture & Pipeline

