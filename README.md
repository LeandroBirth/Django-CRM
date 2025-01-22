
# Django CRM - Management

This is a Django-based CRM application designed for managing contacts. It provides features such as user registration, login, logout, password changes, and profile updates. The project is built using Django and Python, and it includes a user-friendly UI.

<img width="904" alt="Screenshot 2025-01-22 at 18 19 52" src="https://github.com/user-attachments/assets/690d855a-b7b8-47c3-8ef4-d2f12e070168" />


### Features
- **User Management**:
  - Registration
  - Login/Logout
  - Change Password
  - Update User Information
  - Register with Facebook (currently not fully working)

### Setup
1. **Create a Folder**
   - Create a folder and place all the project files inside it.

2. **Create a Virtual Environment**
   - Run the following command to create a virtual environment:
     ```bash
     virtualenv env
     ```

3. **Activate the Virtual Environment**
   - On Ubuntu/Linux:
     ```bash
     source env/bin/activate
     ```
   - On Windows:
     ```bash
     . .\env\Scripts\activate
     ```

4. **Install Dependencies**
   - Use the `requirements.txt` file to install the necessary Python packages:
     ```bash
     pip install -r requirements.txt
     ```

5. **Apply Database Migrations**
   - Run the following commands to apply database migrations:
     ```bash
     python manage.py makemigrations
     python manage.py migrate
     ```

6. **Run the Application**
   - Start the Django development server:
     ```bash
     python manage.py runserver
     ```

### Notes
- Ensure that all dependencies are installed before running the application.
- The Facebook registration feature is included but currently not functional.
- For any issues, please check the server logs or refer to the Django documentation.



