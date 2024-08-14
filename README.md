```markdown
# Pharmacy App

This repository contains the Pharmacy App, a web application built with Python and Flask. This app is designed to manage pharmacy-related operations. Below is the structure of the project, along with instructions on how to set it up and run it.

Based on the Internet Application Programming course, this repository focuses on a project of Pharmacies connecting with each other. The team members are:
- Katarzyna Góźdź
- Jan Michalak
- Maciej Stępień
- Wiktor Zborowski

This project is based on a Python, using library Flask

## Project Structure

pharmacy_app/
|-- pharmacy_app/
|   |-- static/
|   |   |-- images/
|   |   |   |-- example_image.jpg
|   |   |   |-- example_image2.jpg
|   |   |-- uploads/  # Folder to store uploaded files (if any)
|   |-- templates/
|   |   |-- index.html
|   |   |-- prescription_page.html  # Example additional page
|   |-- __init__.py
|   |-- routes.py
|   |-- main.py  # Main entry point for the application
|-- venv/  # Virtual environment folder (optional, recommended)
|-- README.md  # Documentation for the project
|-- setup.py  # Script for packaging and installing the project (if needed)
|-- .gitignore  # To ignore unnecessary files and folders like venv

## Getting Started

### Prerequisites

- Python 3.8 or later
- [pip](https://pip.pypa.io/en/stable/) (Python package installer)
- [virtualenv](https://virtualenv.pypa.io/en/stable/) (optional but recommended)

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Torekas/pharmacy_app.git
    cd pharmacy_app
    ```

2. **Set up a virtual environment (optional but recommended):**

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

### Running the Application

1. **Run the Flask application:**

    ```bash
    python pharmacy_app/main.py
    ```

2. **Access the application:**

    Open your web browser and go to `http://127.0.0.1:5000/`.

### Project Structure Details

- **`pharmacy_app/static/`**: Contains static files like images, CSS, and JavaScript.
- **`pharmacy_app/templates/`**: Contains HTML templates for rendering views.
- **`pharmacy_app/__init__.py`**: Initializes the Flask app and other configurations.
- **`pharmacy_app/routes.py`**: Contains the route definitions for the web application.
- **`pharmacy_app/main.py`**: The main entry point of the application.
- **`venv/`**: The virtual environment directory (not included in the repo, but can be created locally).
- **`setup.py`**: Used for packaging and installing the project (if applicable).
- **`.gitignore`**: Specifies files and directories to be ignored by git.

### Contributing

If you wish to contribute to this project, please fork the repository and submit a pull request. Contributions are welcome!

### License

[MIT](https://choosealicense.com/licenses/mit/)

```
