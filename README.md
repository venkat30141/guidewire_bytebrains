# GigShield AI

### AI-Powered Parametric Insurance for Gig Economy Delivery Workers

---

##  Problem Statement

India’s gig economy delivery workers (Swiggy, Zomato, Zepto, Blinkit, Amazon, etc.) depend on daily earnings. However, external disruptions such as extreme weather, pollution, floods, or sudden curfews can significantly reduce their working hours, leading to income loss.

Currently, these workers have **no financial safety net** to protect them from such unpredictable disruptions.

GigShield AI addresses this problem by providing an **AI-powered parametric insurance platform** that automatically compensates gig workers for income loss caused by external events.

---

##  Our Solution

GigShield AI is an **intelligent insurance platform** that provides automated income protection for delivery partners.

The platform uses **AI models and real-time environmental data** to detect disruptions such as heavy rain, extreme heat, or pollution that prevent delivery workers from completing orders.

When such events occur, the system automatically triggers claims and processes payouts without requiring manual claim submissions.

---

##  Target Persona

**Primary Persona:**
Q-Commerce Delivery Partner (Zepto / Blinkit / Instamart)

**Worker Profile**

* Works 8–10 hours per day
* Earns approximately ₹600 – ₹1000 daily
* Highly dependent on weather and traffic conditions
* Paid weekly or daily based on completed deliveries

**Key Challenge:**
When disruptions occur (heavy rain, floods, pollution), deliveries stop and workers lose their daily income.

GigShield AI protects their **lost earnings through weekly insurance coverage.**

---

##  Coverage Scope

GigShield AI provides protection for:

✔ Income loss due to external disruptions

The platform **does NOT cover**:

✖ Health insurance
✖ Vehicle damage or repair
✖ Accident medical claims

---

## 🧠 Key Features

### 1️ AI-Powered Risk Assessment

* Predictive risk modeling using historical weather data
* Dynamic weekly premium calculation based on risk factors

Example inputs:

* Weather history
* Location flood risk
* Pollution levels
* Delivery activity patterns

---

### 2️ Parametric Claim Automation

The system monitors real-time disruption parameters.

Example triggers:

| Event         | Condition               |
| ------------- | ----------------------- |
| Heavy Rain    | Rainfall > 50mm         |
| Extreme Heat  | Temperature > 42°C      |
| Pollution     | AQI > 350               |
| Flood Warning | Government flood alerts |

When these triggers occur, claims are **automatically initiated**.

---

### 3️ Intelligent Fraud Detection

AI-based anomaly detection helps identify fraudulent claims such as:

* GPS spoofing
* Duplicate claims
* Fake weather disruptions
* Location inconsistencies

---

### 4️ Weekly Insurance Pricing Model

GigShield AI uses a **weekly subscription-based premium model** aligned with gig worker payment cycles.

Example:

| Risk Level       | Weekly Premium |
| ---------------- | -------------- |
| Low Risk Area    | ₹15/week       |
| Medium Risk Area | ₹22/week       |
| High Risk Area   | ₹30/week       |

Premiums are dynamically calculated using AI risk prediction models.

---

##  Platform Features

### Worker Application

Delivery workers can:

* Register and verify identity
* Subscribe to weekly insurance plans
* View coverage details
* Track disruptions in their area
* Monitor payouts and claim history

---

### Admin Dashboard

Insurance providers can:

* Monitor active policies
* View disruption analytics
* Detect fraud patterns
* Analyze claim statistics
* Forecast risk zones using AI predictions

---

## ⚙ System Architecture

```
User Interface (React Web / Mobile App)
            |
            |
Backend Services (Spring Boot / Node.js)
            |
            |
Database (PostgreSQL)
            |
            |
AI Engine (Python ML Models)
            |
            |
External APIs
  - Weather API
  - Air Quality API
  - Maps / Location API
  - Payment Gateway (Sandbox)
```

---

##  API Integrations

GigShield AI integrates with external services including:

* **OpenWeather API** → Real-time weather data
* **Air Quality APIs** → Pollution monitoring
* **Google Maps API** → Location validation
* **Payment Gateway (Razorpay Sandbox)** → Simulated payouts

---

##  Technology Stack

**Frontend**

* React
* Tailwind CSS

**Backend**

* Spring Boot (Java)

**Database**

* PostgreSQL

**AI / ML**

* Python
* Scikit-learn / TensorFlow

**Deployment**

* Docker
* AWS / Render

---

##  System Workflow

```
Worker Registration
        ↓
AI Risk Assessment
        ↓
Weekly Premium Calculation
        ↓
Worker Subscribes to Policy
        ↓
System Monitors External Disruptions
        ↓
Trigger Detected
        ↓
Automatic Claim Processing
        ↓
Instant Payout
```

---

##  Future Enhancements

* Predictive disruption alerts for workers
* Dynamic coverage adjustment
* Hyper-local risk maps
* Advanced ML fraud detection models
* Multi-city scalability

---

##  Team

Team Name: ByteBrains
Team Lead: Venkat Dupaguntla
Members:   1.Rushmitha, 2. Siva Durga

---

##  Demo Video

Demo video link: *(To be added)*

---

##  Repository Structure

```
gigshield-ai
│
├── frontend
├── backend
├── ai-model
├── docs
└── README.md
```

---

##  Vision

GigShield AI aims to build a **financial safety net for India’s gig workforce**, ensuring that delivery partners remain protected from unpredictable external disruptions while maintaining stable income streams.

---

**Built for Guidewire DEVTrails 2026**
