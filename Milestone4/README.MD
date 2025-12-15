# Milestone 4 — Web Interface & Admin Panel (AI-Based Recommendation System)
This submission contains the implementation of **Milestone 4** for the Study Track – AI-Based Recommendation System project.  
The goal of this milestone is to build a **Student Interface** and **Admin Panel** inside a Google Colab notebook with **real-time database connectivity** using SQLite.

All functionality (data entry, admin login, CRUD operations, and integration with a simple AI retraining placeholder) has been implemented successfully.


---

##  How to Run the Notebook (Google Colab)

1. Open the file **Milestone_4_WebInterface_Colab.ipynb** in Google Colab.
2. Run the first cell to **mount Google Drive**:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
Run the Setup & Database cell to create the SQLite DB inside Drive.

Run all remaining cells top to bottom to load:

Student Interface (ipywidgets)

Admin Panel (login + CRUD)

Quick DB View

Retraining function

 Admin Login Credentials (for evaluation)
Username: admin
Password: admin123
 Student Interface (Features)

Enter Name, Email, Subject, Study Duration, Notes

Add new students dynamically

Automatically log timestamps

Save directly into SQLite database (stored in Drive)

Real-time update of dropdown student list

## Admin Panel (Features)

Secure login using hashed password (SHA256)

View all students (table format)

## CRUD Operations:

-- Add Student

-- Update Student

-- Delete Student

Real-time database updates

Integrated with quick-view table for verification

## AI Retraining (Placeholder Demo)

A simple example ML model is included:

Uses Linear Regression

Trains on subject-length vs. study-duration (toy example)

Demonstrates integration of AI logic after DB updates

Run using:

retrain_model()

## Screenshots Included

All required screenshots are added in the /screenshots/ folder:

-- Notebook structure

-- Database created successfully

-- Student interface

-- Save log success message

-- DB table view

-- Admin login success

-- CRUD operation (Add/Update/Delete)

## Demo Video (Optional)

A short walk-through video is provided inside /demo/milestone4_demo.mp4 showing:

Student Interface workflow

Database update

Admin login

CRUD operation
## Milestone Requirements Completed

-- Student interface → DONE

-- Admin panel → DONE

-- Secure admin login → DONE

-- CRUD operations → DONE

-- Real-time DB updates → DONE

-- AI retraining integration → DONE

-- Screenshots → DONE

-- Demo → Optional (Included if provided)





