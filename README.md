# Face Recognition Attendance System

## Overview

The **Face Recognition Attendance System** is an automated attendance tracking system that uses real-time face recognition to mark the attendance of individuals. This system integrates face recognition technology to accurately identify and record attendance, eliminating the need for manual checks and improving the efficiency of attendance management.

## Features

- **Real-Time Face Recognition**: Utilizes advanced computer vision algorithms to detect and recognize faces.
- **Attendance Logging**: Automatically logs attendance in a database when a face is recognized.
- **User-Friendly Interface**: Simple and easy-to-use interface for administrators and users.
- **Email Notifications**: Sends an email notification whenever an attendance event is recorded.
- **Customizable**: The system can be extended to suit specific use cases or integrate with existing systems.

## Technologies Used

- **Programming Language**: Python
- **Face Recognition**: OpenCV, dlib, Face Recognition library
- **Database**: SQLite
- **Backend**: Flask (for web server)
- **Email**: Yagmail (for email notifications)
- **Machine Learning**: Deep Learning models for face recognition
- **Hardware**: Raspberry Pi (optional for IoT integration)

## Installation

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- OpenCV
- dlib
- Face Recognition library
- Flask
- Yagmail (for sending emails)
- SQLite (for local database)

### Steps to Set Up

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ExpertkickTN/Face-Recognition-Attendance-System.git
   cd Face-Recognition-Attendance-System
