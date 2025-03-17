# Aircraft Management System

## Introduction

The **Aircraft Management System** is a Python-based application designed to manage aircraft operations efficiently. It provides functionalities for tracking aircraft details, scheduling flights, managing crew assignments, and maintaining aircraft maintenance records. This system is beneficial for aviation companies, airports, and airline operators to streamline their operations.

## Features

- **Aircraft Management:** Register and track aircraft details.
- **Flight Scheduling:** Plan and schedule flights with aircraft availability.
- **Crew Assignment:** Assign pilots and crew members to flights.
- **Maintenance Tracking:** Log and monitor aircraft maintenance records.
- **Database Management:** Store and retrieve data using SQLite or MySQL.
- **Graphical User Interface (GUI):** User-friendly interface using Tkinter (if applicable).
- **Data Handling & Visualization:** Pandas for data processing and Matplotlib for visualization (if needed).

## Technologies Used

- Python (>=3.7)
- SQLite/MySQL (For database management)
- Tkinter (For GUI-based applications, if applicable)
- Pandas (For data handling)
- Matplotlib (For visualization, if needed)
- Flask (For web-based system, if applicable)

## Installation

### Prerequisites

Ensure you have Python installed on your system (>=3.7). You can download it from [Python's official website](https://www.python.org/downloads/).

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/aircraft-management-system.git
   cd aircraft-management-system
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Set up the database:**
   ```bash
   python setup_database.py
   ```
4. **Run the application:**
   ```bash
   python main.py
   ```
   If using Flask for a web-based system, start the server:
   ```bash
   flask run
   ```

## Usage

- Launch the application and navigate through the menu.
- Use the **"Add Aircraft"** option to register a new aircraft.
- Schedule flights by selecting an aircraft and entering necessary details.
- Assign crew members to flights and manage their schedules.
- Update maintenance records regularly to ensure safety compliance.

## Folder Structure

```
/aircraft-management-system
│── main.py                # Main entry point of the system
│── models.py              # Database models
│── setup_database.py      # Database initialization script
│── templates/             # HTML templates (if using Flask)
│── static/                # CSS, JS, images (if using Flask)
│── gui.py                 # GUI (if using Tkinter)
```

## License

This project is licensed under the **MIT License**.

## Contributors

- **Aditya Sinha** - Developer

Contributions are welcome! Feel free to fork the repository and submit pull requests.

## Contact

For any inquiries or support, please reach out to (adityasinha06841@gmail.com)

