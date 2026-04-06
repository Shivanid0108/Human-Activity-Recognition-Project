# Human Activity Recognition (HAR) System

A collaborative academic project developed at Concordia University, integrating 
hardware sensing, machine learning, and a web interface to recognize and classify 
physical activities in real time.

## Project Overview

This system detects and classifies physical activities — sitting, standing, and 
walking — using motion sensor data from an Arduino-based hardware setup, processed 
through a machine learning pipeline in Python, and visualized through an interactive 
web frontend.

## My Contributions

- **Hardware setup** — configured MPU6050 accelerometer with Arduino Uno for 
  real-time motion data collection
- **Frontend development** — built the HTML/CSS/JS interface for data upload and 
  interactive activity prediction display
- **ML pipeline** — contributed to data preprocessing and Random Forest model 
  training and validation (equal collaboration)

## Tech Stack

| Layer | Tools |
|---|---|
| Hardware | Arduino Uno, MPU6050 (6-DOF accelerometer) |
| Data & ML | Python, scikit-learn, Random Forest, WISDM dataset |
| Frontend | HTML, CSS, JavaScript |

## Results

- **95% classification accuracy** across sitting, standing, and walking activity classes
- Validated against the WISDM benchmark dataset
- Real-time prediction display via web interface

## How It Works

1. MPU6050 sensor captures 6-axis motion data via Arduino Uno
2. Data is exported and preprocessed using Python scripts
3. Random Forest classifier predicts activity class
4. User uploads data through the web interface and views predictions interactively

## Context

Developed as a team project for a Concordia University engineering course. 
All team members contributed equally across hardware, ML, and frontend components.
