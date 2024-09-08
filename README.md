# capstone-project

# Store Inventory Application

## Project Overview
The **Store Inventory Application** is a web-based system developed to help small and medium enterprises (SMEs) manage their stock levels efficiently. It allows users to create accounts, add, edit, and delete stock items, and receive low-stock alerts. This system is developed using the Python framework Django and Bootstrap for the frontend, ensuring a clean, responsive interface.

## Features
- User account creation and login system.
- Stock management: Add, update, delete, and view items.
- Low-stock alerts.
- Category management to organize store items.
- Intuitive and user-friendly interface.

## Live Demo
*(Include a link if the app is hosted online)*

## Usage Instructions
1. **Create an Account**:  
   Sign up for a new account. After registration, you will be automatically logged in and redirected to the landing page.
   
2. **Get Started**:  
   Click the "Get Started" button to be redirected to your store inventory dashboard.

3. **Set Up Your Store Inventory**:
   - Click the "+" button to add items to your inventory.
   - Fill in the form with the item's details:
     - **Name of the Item**
     - **Quantity**
     - **Category**
   - After entering the details, click "Save." Your items should now display on the dashboard.

4. **Update or Delete Items**:
   - You can update the quantity of an item after a sale by clicking the "Edit" button beside the item and changing the value.
   - You can also delete items from your store list by clicking the "Delete" button.

## Installation Instructions
Since this is a web-based application, no installation is required. To run the application locally, follow these steps:

### Prerequisites:
- Python 3.x
- Django
- PostgreSQL or MySQL (or any preferred database system)
  
### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/store-inventory-app.git
   cd store-inventory-app
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run database migrations:
   ```bash
   python manage.py migrate
   ```

4. Run the development server:
   ```bash
   python manage.py runserver
   ```

5. Open your browser and navigate to `http://127.0.0.1:8000/` to access the application.

## Technology Stack
- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: Python, Django
- **Database**: PostgreSQL or MySQL (configured in `settings.py`)
- **Version Control**: Git
