💻 Local Setup Guide (Windows + VSCode)
Beginner-friendly instructions to help you run the system locally using CMD and Visual Studio Code.

📋 Step-by-Step Setup
1. Choose a folder where you want to store the project files.

2. Open CMD in that folder:
In File Explorer, click the folder path bar → type cmd → press Enter

3. Clone the repository (https://github.com/kirbylat69/SMS):
"(https://github.com/kirbylat69/SMS.git)"

4.Open VSCode, then:

5. Open the cloned project folder in VSCode:
File > Open Folder → choose the student-management-system folder

6. Open Terminal inside VSCode:
Ctrl + Shift + ~ or go to Terminal > New Terminal

7. Create and activate a virtual environment:
"python -m venv .venv  
.venv\Scripts\activate.bat"

8. Navigate into the Django project directory (if needed):
"cd Project  # Replace 'Project' with your actual Django app folder name if different

9. Install required packages:"
"pip install -r requirements.txt"

10. Run database migrations:"
"python manage.py migrate

11. Create a superuser account (for admin access):"
"python manage.py createsuperuser"

12. Start the development server:
"python manage.py runserver"

13. Access the system:
"Open your browser and go to:
http://127.0.0.1:8000/"
