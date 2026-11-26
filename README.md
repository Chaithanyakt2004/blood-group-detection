# Blood Group Detection

A web application built with **Flask** and **PyTorch** for blood group classification and prediction through an interactive browser interface.

## Overview

This project combines a deep learning model with a Flask backend and HTML/CSS templates so users can upload or test images and view blood group predictions, supported by sample test assets and a local SQLite database.

## Project Structure

- `app.py` — Main Flask application, routes, and model inference logic.
- `templates/` — HTML templates for the web interface.
- `static/` — Static assets (CSS, JavaScript, and UI files).
- `dataset_blood_group/` — Blood group dataset used for training/experimentation.
- `Test Images/` & `testing/` — Sample test images and verification/testing files.
- `users.db` — SQLite database for storing application/user records.
- `.gitignore` — Specifies untracked files and directories ignored by Git.

## Setup & Installation

1. **Clone the repository**
   ```bash
   git clone [https://github.com/Chaithanyakt2004/blood-group-detection.git](https://github.com/Chaithanyakt2004/blood-group-detection.git)
   cd blood-group-detection
