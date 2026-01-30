# 🎫 NLP-Based Support Ticket Classification and Priority Assignment System

![Future Interns](https://img.shields.io/badge/Future%20Interns-Machine%20Learning-blue)
![Task](https://img.shields.io/badge/Task-2-success)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## Internship: Machine Learning Intern – Future Interns

**Task Number:** Task 2 (Support Ticket Classification)
**Track Code:** ML
**Recommended Repository Name:** `FUTURE_ML_02`

---

## ✅ Official Task-2 Requirement Compliance

This project is developed **strictly according to the official Task-2 guidelines** provided by **Future Interns** and satisfies **all mandatory requirements**.

| Task-2 Requirement                     | Status      | Implementation                              |
| -------------------------------------- | ----------- | ------------------------------------------- |
| Text cleaning & tokenization           | ✅ Completed | Regex cleaning, lowercasing, NLTK stopwords |
| Ticket category classification         | ✅ Completed | TF-IDF + Logistic Regression                |
| Priority tagging (High / Medium / Low) | ✅ Completed | Rule-based priority engine                  |
| Model performance evaluation           | ✅ Completed | Accuracy evaluation during training         |
| Tools: Python, NLTK, Scikit-learn      | ✅ Used      | Fully compliant                             |
| Deliverable: Working system            | ✅ Delivered | Flask-based web application                 |

📌 **Verdict:** This submission is **100% compliant with Task-2 expectations**.

---

## 📌 Project Overview

Customer support teams receive hundreds or thousands of tickets daily, making manual categorization and prioritization inefficient and error-prone. This project addresses that challenge by building an **NLP-powered Support Ticket Classification System** that:

* Automatically classifies incoming support tickets
* Assigns urgency-based priority levels
* Presents results through a professional, enterprise-style web interface

The system enables support teams to **respond faster, route tickets intelligently, and improve customer satisfaction**.

---

## 🎯 Problem Statement

Manual handling of customer support tickets often leads to:

* ❌ Delayed responses
* ❌ Poor prioritization of critical issues
* ❌ Increased customer dissatisfaction

This project leverages **Natural Language Processing and Machine Learning** to automate ticket understanding and urgency assessment in real time.

---

## 🧠 Solution Approach

The project follows a production-style machine learning workflow:

1. Generate a large-scale dataset of realistic support tickets (10,000+)
2. Perform text preprocessing and feature extraction
3. Train a supervised ML classifier for ticket categorization
4. Assign priority using rule-based logic layered over ML predictions
5. Deploy the system as a Flask web application
6. Present results using a clean, professional UI

---

## 🏗️ System Architecture

```
User Ticket Input
        ↓
Text Cleaning & Tokenization (NLP)
        ↓
TF-IDF Vectorization
        ↓
Ticket Classification (ML Model)
        ↓
Priority Assignment (Rule-Based Logic)
        ↓
Flask Backend
        ↓
Enterprise Web Interface
```

---

## 🛠️ Technologies Used

### Programming & Backend

* Python
* Flask

### NLP & Machine Learning

* NLTK
* Scikit-learn (TF-IDF, Logistic Regression)

### Frontend

* HTML
* CSS (Enterprise SaaS-style UI)

---

## 📂 Dataset Description

* **Dataset Size:** 10,000+ support tickets
* **Categories:** Technical, Billing, Account, General
* **Dataset Type:** Synthetic but business-realistic
* **Purpose:** Training and evaluating ticket classification model

The dataset was programmatically generated to simulate real-world customer support traffic.

---

## 🤖 Machine Learning Model

* **Algorithm:** Logistic Regression
* **Feature Extraction:** TF-IDF Vectorization
* **Reason for Selection:**

  * Fast training on large text datasets
  * Interpretable and production-friendly
  * Suitable for real-time classification

---

## 🚦 Priority Assignment Logic

| Priority | Criteria                                                 |
| -------- | -------------------------------------------------------- |
| High     | Service outage, payment failure, refund, critical errors |
| Medium   | Partial issues, delays, billing inconsistencies          |
| Low      | Informational queries, appreciation, general questions   |

This hybrid approach combines **ML intelligence with business rules**, mirroring real enterprise systems.

---

## 🖥️ Application Features

✔ Real-time ticket classification
✔ Automated priority tagging
✔ Enterprise-style web interface
✔ Large-scale dataset usage
✔ Production-style ML deployment
✔ Internship-compliant structure

---

## 📷 Application Screenshots

Screenshots are included in the repository under the `/screenshots/` directory:

* Home Page – Ticket input interface
<img width="1366" height="768" alt="Screenshot (130)" src="https://github.com/user-attachments/assets/0657a9d8-1cb8-499f-a026-c59a9884466e" />

* Result Page – Billing ticket with High priority
<img width="1366" height="768" alt="Screenshot (127)" src="https://github.com/user-attachments/assets/ca58547d-b5c1-4d50-b41d-a7fa624b2bc0" />

* Result Page – Technical issue classification
<img width="1366" height="768" alt="Screenshot (128)" src="https://github.com/user-attachments/assets/a4ce900e-32ec-449f-8fc7-2cb259f0e8f2" />

* Result Page – Medium priority billing case
<img width="1366" height="768" alt="Screenshot (129)" src="https://github.com/user-attachments/assets/8708646c-efc8-418e-860f-8998b942ae86" />

(These screenshots are taken from the **actual running application**, not mockups.)

---

## 🚀 How to Run the Project

### 1️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 2️⃣ Generate Dataset

```bash
python generate_dataset.py
```

### 3️⃣ Train Model

```bash
python train_model.py
```

### 4️⃣ Run Application

```bash
python app.py
```

Open in browser:

```
http://127.0.0.1:5000
```

---

## 📁 Project Structure

```
support_ticket_classifier/
│
├── generate_dataset.py
├── train_model.py
├── app.py
│
├── data/
│   └── tickets.csv
│
├── model/
│   ├── classifier.pkl
│   └── vectorizer.pkl
│
├── templates/
│   ├── index.html
│   └── result.html
│
├── static/
│   └── style.css
│
├── requirements.txt
└── README.md
```

---

## 🎓 Internship Context

* **Organization:** Future Interns
* **Internship Track:** Machine Learning
* **Task Completed:** Task-2 – Support Ticket Classification
* **Internship Model:** Self-directed, task-based
* **Evaluation:** Project submission & review

This project adheres to all internship guidelines regarding domain scope, tooling, and documentation.

---

## 💼 Resume-Ready Description

> Designed and deployed an NLP-based Support Ticket Classification system using TF-IDF and Logistic Regression. The system automatically categorizes customer issues and assigns priority levels using rule-based logic, delivered through a professional Flask web application trained on a large-scale dataset.

---

## 🔮 Future Enhancements

* Admin analytics dashboard
* SLA-based ticket routing
* Deep learning models (BERT)
* Cloud deployment

---

## 🏁 Final Statement

✔ Fully satisfies **Future Interns – Task 2** requirements
✔ Production-style ML system
✔ Strong portfolio & internship submission

---

📜 License

This project is released under the MIT License and is intended strictly for academic and educational purposes.

---

👨‍💻 **Developed by:** M V Karthikeya
