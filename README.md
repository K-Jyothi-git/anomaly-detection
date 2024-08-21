# Anomaly Detection Project

## Anomalous Score ≥ 2
*(The model produces scores from 1–10. If the score is ≥ 3, the record is considered anomalous.)*

---

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Algorithms Used](#algorithms-used)
- [About the Maintainer](#about-the-maintainer)

---

## Introduction

Anomaly detection plays a crucial role in identifying and mitigating potential security threats. This project focuses on detecting anomalies in **user login behavior**, which can help identify suspicious activities such as:

- Unauthorized access attempts  
- Compromised user accounts  

The project uses **machine learning techniques**, specifically **XGBoost**, to train an anomaly detection model based on a labeled dataset. The trained model can then classify new login events as **normal or anomalous** based on their features.

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/anomaly-detection.git
cd anomaly-detection