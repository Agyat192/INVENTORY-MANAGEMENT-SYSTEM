
# Inventory Management System

## Author
**Name: Sunil Santosh Bokare**

## Overview
The Inventory Management System is a Python-based application designed to manage and track inventory for stores or warehouses. The system features functionalities such as adding, editing, and deleting products, tracking inventory levels, and generating various reports. The application also includes user authentication, data validation, and a graphical user interface (GUI) for enhanced usability.

## Features
- **User Authentication:** Secure login and access control.
- **Product Management:** Add, edit, and delete products with detailed information.
- **Inventory Tracking:** Monitor and manage inventory levels.
- **Reports Generation:** Low-stock alerts, sales summaries, and other customizable reports.
- **Data Validation:** Ensure data integrity and prevent errors.
- **Graphical User Interface (GUI):** User-friendly interface for easier interaction with the system.

## Installation

### Prerequisites
- Python 3.8 or higher
- Required Python libraries (listed in `requirements.txt`)

### Steps
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Agyat192/INVENTORY-MANAGEMENT-SYSTEM.git
   ```
   
2. **Navigate to the Project Directory:**
   ```bash
   cd inventory-management-system
   ```

3. **Install Required Libraries:**
   Create a virtual environment and install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   pip install -r requirements.txt
   ```

4. **Run the Application:**
   ```bash
   python main.py
   ```

## Usage

1. **Authentication:**
   - Upon starting the application, you will be prompted to log in. Use your credentials to access the system.

2. **Managing Products:**
   - Navigate to the product management section where you can add, edit, or delete products.
   - Provide necessary details such as product name, SKU, quantity, and price.

3. **Tracking Inventory:**
   - View current inventory levels and update quantities as needed.
   - The system will alert you when stock levels are low.

4. **Generating Reports:**
   - Access the reports section to generate and view various reports including low-stock alerts and sales summaries.

## Data Validation
The application includes data validation to ensure that all inputs are accurate and consistent. This includes checks for valid product information and inventory levels.

## GUI
The application uses a GUI to provide a more intuitive and user-friendly experience. It is built using [Tkinter](https://docs.python.org/3/library/tkinter.html), a standard Python library for creating graphical interfaces.

## Contributing
If you would like to contribute to the development of this project, please fork the repository and submit a pull request with your proposed changes. Ensure that your code adheres to the existing coding style and includes appropriate tests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

