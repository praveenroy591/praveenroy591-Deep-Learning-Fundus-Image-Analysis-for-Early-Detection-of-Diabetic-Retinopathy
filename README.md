
# 👁️ Diabetic Retinopathy Detection System

## Project Overview

This project is an AI-based medical web application that detects and classifies the stages of Diabetic Retinopathy from retinal fundus images using a deep learning model (Xception). The system allows users to register, login, upload retinal images, and view prediction results through an interactive medical dashboard.

The goal of this project is to assist in early detection of Diabetic Retinopathy and reduce the risk of vision loss using Artificial Intelligence.

---
# 👥 Team Details

**Team ID:** LTVIP2026TMIDS81330

**Team Size:** 4 Members

### 👩‍💻 Team Members

* **Gummadi Praveen Roy**
* **Dandu Vyshnavi**
* **Seemala Sai Kumar**
* **Mogilapalapu Veera Ravindra Babu**

---
# 📂 Project Files Overview

### 1. app.py

Main backend file of the project.

* Loads the trained deep learning model (.h5 file)
* Handles routing (home, register, login, prediction, logout)
* Manages user authentication and sessions
* Processes image uploads
* Performs DR stage prediction
* Connects to Cloudant database

---

### 2. Updated-Xception-diabetic-retinopathy.h5

Saved trained deep learning model file.

* Built using Xception (Transfer Learning)
* Classifies retinal images into 5 DR stages

---

### 3. templates Folder

Contains all frontend HTML files.

#### index.html

* Home page
* Project introduction
* Navigation menu

#### register.html

* User registration page
* Stores user data in database

#### login.html

* User login page
* Validates credentials
* Creates session

#### prediction.html

* Image upload page
* Displays classification result
* Shows confidence percentage
* Highlights detected stage

#### logout.html

* Logout confirmation page
* Ends session securely

---

### 4. uploads Folder

Stores uploaded retinal images temporarily for prediction processing.

---

### 5. README.md

Contains complete project documentation including setup and features.

---

# 📘 Documentation Overview

The project documentation is divided into **7 phases** to explain the complete development lifecycle:

### Phase 1 – Brainstorming & Problem Definition

* Idea generation
* Problem identification
* Real-world application
* Technology selection

### Phase 2 – Requirement Analysis

* Data Flow Diagram (DFD)
* System Architecture
* Solution requirements
* Technology stack

### Phase 3 – Project Design Phase

* Selected Algorithm (Xception CNN)
* Model architecture explanation
* Proposed solution design

### Phase 4 – Project Planning Phase

* Data collection
* Data cleaning
* Exploratory Data Analysis (EDA)
* Detailed workflow planning

### Phase 5 – Project Development Phase

* Model building and training
* Performance testing
* User acceptance testing

### Phase 6 – Documentation

* Complete technical documentation
* Screenshots and diagrams
* Architecture explanation

### Phase 7 – Final Project Submission

* Demo video


---

# 🛠 Technologies Used

* Python
* Flask
* TensorFlow
* Keras
* Xception Model
* HTML
* CSS
* JavaScript
* IBM Cloudant Database

