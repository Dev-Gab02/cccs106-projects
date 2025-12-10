# CCCS 106 Projects
Application Development and Emerging Technologies  
Academic Year 2025-2026

## Student Information
- **Name:** Gabriel Concepcion
- **Student ID:** 231001672
- **Program:** Bachelor of Science in Computer Science
- **Section:** 3B

## Repository Structure

### Week 1 Labs - Environment Setup and Python Basics
- `week1_labs/hello_world.py` - Basic Python introduction
- `week1_labs/basic_calculator.py` - Simple console calculator

### Week 2 Labs - Git and Flet GUI Development
- `week2_labs/hello_flet.py` - First Flet GUI application
- `week2_labs/personal_info_gui.py` - Enhanced personal information manager
- `week2_labs/enhanced_calculator.py` - GUI calculator (coming soon)

### Week 3 Labs - User Login App with MySQL and Flet
- `week3_labs/main.py` - Main Flet app with login logic
- `week3_labs/db_connection.py` - MySQL connection helper

### Week 4 Labs - Contact Book App with Flet
- `week4_labs/main.py` — Main Flet app entry point
- `week4_labs/app_logic.py` — UI logic and event handlers
- `week4_labs/database.py` — SQLite database helpers

### Module 1 Final Project
- `module1_final/` - Final integrated project (TBD)

### Module 6 - Weather Application
- `mod6_labs/main.py` — Main Flet app and UI logic  
- `mod6_labs/weather_service.py` — Async weather API service 
- `mod6_labs/config.py` — Configuration and environment variables  
- `mod6_labs/test_weather_service.py` — Simple async tests for the weather service
  
## Technologies Used
- **Python 3.8+** - Main programming language
- **Flet 0.28.3** - GUI framework for cross-platform applications
- **Git & GitHub** - Version control and collaboration
- **VS Code** - Integrated development environment

## Development Environment
- **Virtual Environment:** cccs106_env
- **Python Packages:** flet==0.28.3
- **Platform:** Windows 10/11

## How to Run Applications

### Prerequisites
1. Python 3.8+ installed
2. Virtual environment activated: `cccs106_env\Scripts\activate`
3. Flet installed: `pip install flet==0.28.3`

### Running GUI Applications
```cmd
# Navigate to project directory for week1_labs
cd week1_labs

# Run applications
python hello_world.py
python basic_calculator.py

# Navigate to project directory for week2_labs
cd week2_labs

# Run applications
python hello_flet.py
python personal_info_gui.py

# Navigate to project directory for week3_labs
cd week3_labs

# Run applications
python src/main.py

# Navigate to project directory for week4_labs
cd week4_labs
cd contact_book_app

# Run applications
python src/main.py

# Navigate to project directory for mod6_labs
cd mod6_labs

# Run applications
python src/main.py


