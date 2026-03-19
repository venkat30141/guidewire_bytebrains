SECTION-1 
---------------
# GigShield AI
[THe main Insurance App named "GigShield AI"  for Q-commerce gig workers ]
“GigShield AI is designed for diverse gig workers — from full-time riders to students and multi-platform earners — ensuring instant payouts when real-world conditions disrupt their income.”

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

2-3 persona's for better understanding... of the gig workers accross the near by cities in the Andhra Pradesh
=====================================================
👤 Persona 1: The High-Volume Delivery Rider
--------------------
🧑 Name: Ravi Kumar
Age: 26
City: Guntur
Platform: Food delivery (Swiggy/Zomato-type)
Work Style: Full-time (10–12 hrs/day)
💼 Behavior
---------------
Completes 25–35 deliveries/day
Works during peak hours (lunch + dinner)
Relies heavily on incentives & surge pricing
-----------------------
💰 Income Pattern
₹800–₹1500/day (variable)
Weekly income fluctuates based on:
Weather 🌧️
Demand
City conditions
--------------------------
⚠️ Pain Points
Heavy rain = fewer orders + unsafe riding
Heatwaves = health risk + reduced working hours
Sudden government bandh = zero income day
-------------------------------------
💡 Why He Needs our Insurance
If rainfall crosses threshold → payout triggered
If bandh announced → instant compensation
If AQI too high → health-risk payout
====================================================
👤 Persona 2: The Part-Time Student Worker
🧑 Name: Sneha Reddy
Age: 21
City: Tenali
Platform: Grocery/Q-commerce (Zepto/Blinkit-type)
Work Style: Part-time (evenings + weekends)
-------------------------
💼 Behavior
Works 4–5 hours/day
Focuses on quick deliveries (2–5 km radius)
Balances college + work
--------------------------
💰 Income Pattern
₹400–₹700/day
Uses income for:
Tuition fees
Personal expenses
--------------------------
⚠️ Pain Points
Unexpected rain = cannot go out → lost income
Air pollution alerts → parents restrict her from working
Safety concerns during extreme weather
-------------------------------------------------------------
💡 Why She Needs our Insurance
Parametric triggers ensure:
She doesn’t lose income on days she can’t safely work
Small payouts matter a lot for her stability
=======================================================================================
👤 Persona 3: The Multi-App Hustler
🧑 Name: Arjun Singh
Age: 30
City: Vijayawada
Platform: Works on multiple apps (food + courier + grocery)
Work Style: Flexible, opportunistic
----------------------------------------
💼 Behavior
Switches apps based on:
Demand
Surge pricing
Covers large city zones
----------------------------------
💰 Income Pattern
₹1000–₹2000/day (high but unstable)
Depends on:
City activity
Events
Weather
---------------------------------
⚠️ Pain Points
City-wide bandhs = total shutdown
Extreme pollution = reduced outdoor movement
Heavy rain/floods = no mobility → zero earnings
----------------------------------------------------
💡 Why He Needs our Insurance
Your system protects him across:
Multiple platforms
Multiple risk factors
Fully automated payouts = no claim filing hassle
===================================================================================================

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

##  Key Features

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
=========================================================================================================================================================================

SECTION-2
Adversarial Defense & Anti-Spoofing Strategy
which is integrated in our system
1. Problem Overview

The platform faces a coordinated fraud attack where malicious actors exploit GPS spoofing and mass account creation to simulate fake delivery incidents and trigger illegitimate payouts.

Traditional location verification systems relying solely on GPS signals are vulnerable to spoofing, making them insufficient to detect such adversarial behavior.

This system is designed with a defense-in-depth strategy to identify, analyze, and mitigate fraudulent activities while ensuring fairness for genuine delivery partners.

2. Threat Model

The attack scenario includes:

 GPS Spoofing using fake location apps

 Fraud Rings with hundreds of coordinated accounts

 Device Reuse across multiple fake identities

 IP Clustering indicating centralized control

 Synchronized Behavior Patterns (same time, same claims)

3. Multi-Layer Detection Strategy

Instead of relying on a single signal, the system uses multi-layer verification:

 GPS Anomaly Detection

Detect impossible movement speeds

Identify sudden long-distance jumps

Check route consistency over time

🔹 Device Fingerprinting

Track unique device identifiers

Flag multiple accounts linked to the same device

🔹 Network Intelligence

Monitor IP address patterns

Detect multiple accounts operating from a single network

🔹 Behavioral Analysis

Analyze frequency of claims

Identify repetitive or scripted patterns

Compare against normal user behavior baselines

4. Fraud Ring Detection (Cluster-Based Intelligence)

To combat coordinated attacks, the system identifies groups of suspicious users rather than isolated individuals.

Cluster users based on:

Location similarity

IP address overlap

Time-based activity patterns

If a large group exhibits highly similar behavior:

Mark as a potential fraud ring

Increase risk scores collectively

This approach enables early detection of large-scale coordinated fraud attempts.

5. Risk Scoring System

Each delivery partner is assigned a dynamic risk score (0–100) based on multiple signals:

Factor	Impact
GPS anomalies	High
Device reuse	High
IP clustering	Medium
Claim frequency	Medium
Risk Levels:

🟢 Low Risk (0–30) → Normal operations

🟡 Medium Risk (31–70) → Additional verification required

🔴 High Risk (71–100) → Restricted actions + manual review

6. Progressive Enforcement Mechanism

To avoid harsh penalties on genuine users, actions are taken progressively:

✅ Low Risk → No interruption

⚠️ Medium Risk → Request proof (photo/video/selfie verification)

🚫 High Risk → Temporary hold on payouts + manual investigation

This ensures security without disrupting honest workers.

7. False Positive Prevention (Protecting Genuine Workers)

The system is designed to minimize harm to legitimate delivery partners:

 Proof-Based Validation (live photo, video, or task verification)

 Appeal Mechanism for flagged users

 Historical Trust Score (based on past behavior)

 Grace Thresholds to tolerate minor anomalies

This balances fraud prevention with user trust and fairness.

8. Key Design Principles

 Defense in Depth — multiple layers of validation

 Behavioral Intelligence over raw data reliance

 Cluster-Based Fraud Detection for coordinated attacks

 Fairness First Approach to protect genuine workers

9. Conclusion

A single-point verification system (like GPS alone) is no longer reliable in adversarial environments.
This system follows a Defense-in-Depth strategy,
combining multi-layer validation, behavioral intelligence,
and cluster-based fraud detection to counter coordinated attacks.
The system avoids binary decisions (fraud/not fraud).
Instead, it uses progressive trust evaluation to ensure that
genuine workers affected by network issues or bad weather
are not unfairly penalized.

Architecture Flow

                ┌────────────────────┐
                │  Delivery Partner  │
                │  (App / Request)   │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │   Data Collection   │
                │ GPS | Device | IP   │
                └─────────┬──────────┘
                          │
                          ▼
        ┌──────────────────────────────────┐
        │ Multi-Layer Detection Engine     │
        │                                  │
        │ • GPS Anomaly Check              │
        │ • Device Fingerprinting          │
        │ • IP Monitoring                  │
        │ • Behavioral Analysis            │
        └─────────┬────────────────────────┘
                  │
                  ▼
        ┌──────────────────────────────────┐
        │ Fraud Ring Detection Engine      │
        │ (Cluster / Pattern Analysis)     │
        └─────────┬────────────────────────┘
                  │
                  ▼
        ┌────────────────────┐
        │   Risk Scoring     │
        │   (0 - 100)        │
        └─────────┬──────────┘
                  │
        ┌─────────┼─────────┐
        ▼         ▼         ▼
   Low Risk   Medium Risk   High Risk
      │            │            │
      ▼            ▼            ▼
 Allow        Ask Proof     Hold + Review
 Normal     (Photo/Video)   Flag Account
This architecture leverages multi-dimensional analysis, risk scoring, and intelligent clustering to detect and prevent fraud at scale — while maintaining a seamless experience for legitimate users.

====================================================================================================================================================================


yours faithfully
Team ByteBrains
Team Lead- Venkat Dupaguntla


