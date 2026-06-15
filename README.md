# 🌾 Smart Crop Advisory System

### AI-Powered Decision Support System for Sustainable Agriculture

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen)
![FastAPI](https://img.shields.io/badge/FastAPI-ML%20Backend-009688)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-FF6F00)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue)
![Status](https://img.shields.io/badge/Status-Active-success)

---

# 🌐 Live Demo

**🔗 Deployment:** https://your-deployment-link.com

**🎥 Demo Video:** https://your-demo-video-link.com

---

# 📌 Project Overview

**Krishi Sahayak** is an AI-powered Smart Crop Advisory System developed to empower farmers with intelligent, data-driven agricultural recommendations.

The platform combines Machine Learning, Deep Learning, Weather Intelligence, and Natural Language Processing (NLP) to assist farmers in crop selection, fertilizer optimization, disease detection, and agricultural decision-making.

By transforming complex agricultural data into actionable insights, Krishi Sahayak helps reduce crop failure risks, improve productivity, and promote sustainable farming practices.

---

# 🎯 Problem Statement

Many farmers rely on traditional knowledge and guesswork while making critical agricultural decisions.

Challenges include:

* Unpredictable weather conditions
* Soil nutrient imbalance
* Lack of expert guidance
* Crop diseases causing major losses
* Excessive fertilizer usage
* Limited access to modern agricultural technologies

Krishi Sahayak addresses these challenges through AI-driven recommendations and real-time advisory services.

---

# 🚀 Key Features

## 🌱 Crop Recommendation System

Provides the most suitable crop recommendation based on:

* Nitrogen (N)
* Phosphorus (P)
* Potassium (K)
* Temperature
* Humidity
* Soil pH
* Rainfall

### Benefits

* Higher yield potential
* Better resource utilization
* Reduced crop failure risk

---

## 🧪 Fertilizer Recommendation System

Analyzes soil health and nutrient deficiencies to recommend:

* Urea
* DAP
* 14-35-14
* 28-28
* Organic alternatives

### Benefits

* Reduced fertilizer wastage
* Lower farming costs
* Improved soil sustainability

---

## 🌿 Plant Disease Detection

Uses Deep Learning and Computer Vision to identify plant diseases from leaf images.

### Capabilities

* Detects 34+ disease categories
* Image-based diagnosis
* Early disease detection

### Model

* MobileNetV2 (Transfer Learning)
* TensorFlow/Keras

---

## 🌦️ Weather Advisory

Provides:

* Real-time weather forecasts
* Rainfall alerts
* Temperature monitoring
* Farming activity recommendations

---

## 🤖 Multilingual AI Chatbot

An NLP-powered agricultural assistant capable of:

* Answering farming-related questions
* Providing crop guidance
* Supporting regional languages
* Delivering simple and understandable responses

---

## 📝 Community Blog Platform

Allows:

* Knowledge sharing among farmers
* Expert agricultural articles
* Best farming practices
* Community discussions

---

# 🧠 AI Models & Architecture

## 1️⃣ Crop Recommendation Model

### Algorithm

* Random Forest
* XGBoost Ensemble

### Input Features

* N
* P
* K
* Temperature
* Humidity
* pH
* Rainfall

### Goal

Match soil and climatic conditions with the most suitable crop.

---

## 2️⃣ Fertilizer Recommendation Model

### Algorithm

Classification-based Machine Learning

### Dataset

* 5,500+ agricultural records
* Soil nutrient data
* Crop-specific fertilizer requirements

### Output

Precise fertilizer recommendations based on deficiencies.

---

## 3️⃣ Disease Detection Model

### Architecture

MobileNetV2 CNN

### Dataset

PlantVillage Dataset

### Features

* Image classification
* Disease detection
* Healthy plant identification

---

# 🏗️ System Architecture

```text
Farmer
   │
   ▼
Web Application
   │
   ├── Spring Boot Backend
   │      │
   │      ├── User Management
   │      ├── Blog System
   │      └── Authentication
   │
   ├── FastAPI ML Services
   │      │
   │      ├── Crop Recommendation
   │      ├── Fertilizer Prediction
   │      └── Disease Detection
   │
   └── Weather API
           │
           └── Forecast & Alerts

Database (MySQL)
```

---

# 🛠️ Technology Stack

## Frontend

* HTML5
* CSS3
* Bootstrap
* JavaScript
* Thymeleaf / Jinja2

## Backend

* Spring Boot
* Spring Security
* REST APIs

## AI & Machine Learning

* Python
* FastAPI
* TensorFlow
* Keras
* Scikit-Learn
* Pandas
* NumPy

## Database

* MySQL

## Tools

* Git & GitHub
* Postman
* Docker

---

# 📊 Dataset Details

The project uses agricultural datasets collected from:

* Kaggle Agricultural Datasets
* PlantVillage Dataset
* Government Agricultural Repositories

### Data Includes

#### Soil Data

* Nitrogen
* Phosphorus
* Potassium
* pH

#### Environmental Data

* Temperature
* Humidity
* Rainfall

#### Image Data

* Healthy plant leaves
* Diseased plant leaves
* Multiple crop categories

---

# ⚙️ Installation & Setup

## Prerequisites

* Python 3.10+
* Java JDK 17+
* MySQL Server
* Maven

---

## Clone Repository

```bash
git clone https://github.com/your-username/krishi-sahayak.git
cd krishi-sahayak
```

---

## Setup ML Backend

```bash
cd ml_backend

python -m venv venv

# Windows
venv\Scripts\activate

# Linux/Mac
source venv/bin/activate

pip install -r requirements.txt

uvicorn main:app --reload --port 8000
```

---

## Setup Spring Boot Backend

Configure:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/krishi_sahayak

spring.datasource.username=root

spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
```

Run:

```bash
mvn spring-boot:run
```

---

## Access Application

```text
http://localhost:8080
```

---

# 📈 Expected Outcomes

| Metric                       | Target         |
| ---------------------------- | -------------- |
| Crop Recommendation Accuracy | >90%           |
| Disease Detection Accuracy   | >95%           |
| Response Time                | <3 Seconds     |
| Farmers Supported            | 10,000+        |
| Language Support             | Multi-Language |

---

# 🌍 Impact & Benefits

### Farmers

* Improved crop selection
* Reduced production costs
* Better disease management
* Increased yield

### Environment

* Sustainable fertilizer usage
* Reduced chemical waste
* Improved soil health

### Society

* Enhanced food security
* Digital agriculture adoption
* Rural technology empowerment

---

# 🚀 Future Enhancements

* Mobile Application (Android/iOS)
* IoT Sensor Integration
* Drone-Based Crop Monitoring
* AI Yield Prediction
* Satellite Imagery Analysis
* Government Agriculture Portal Integration
* Voice-Based Advisory Services

---

# ⚠️ Disclaimer

This project is developed for educational and academic purposes.

The recommendations generated by the AI models are advisory in nature and should not replace professional agricultural consultation. Farmers are encouraged to verify critical decisions with local agricultural experts and extension officers.

---

# 🤝 Contributing

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push changes

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 👨‍💻 Team

**Krishi Sahayak Development Team**

Empowering Farmers Through Artificial Intelligence & Sustainable Agriculture 🌾

---

⭐ If you found this project useful, consider giving it a star on GitHub!
