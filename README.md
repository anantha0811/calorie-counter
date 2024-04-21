Calorie Counter and Exercise Planner

This Django application helps you track your food intake, calculate calorie consumption, and estimate the time required for various exercises to burn those calories. It utilizes the API Ninja service to retrieve nutritional information for foods.

Features:

Food Search and Calorie Calculation: Enter a food name and get its calorie count and detailed nutritional breakdown (carbs, protein, fat, etc.)
Exercise Time Estimation: Based on the calculated calories, estimate the duration needed for different exercises (jogging, swimming, cycling, etc.) to burn them off.
Nutritional Value Visualization: View a clear bar chart to visualize the food's nutritional composition.
Requirements:

Python 3.x (https://www.python.org/downloads/)
Django (https://docs.djangoproject.com/en/5.0/)
API Ninja account (https://api-ninjas.com/)
Installation:

Clone this repository:

Bash
`git clone https://your-repository-url.git`

Create a virtual environment (recommended) and activate it.

Install dependencies:

Bash
`pip install -r requirements.txt`
Use code with caution.
Create a project settings file:

Bash
`cp .env.example .env`
Use code with caution.
Edit the .env file to include your API Ninja API key.


Bash
`python manage.py makemigrations`
`python manage.py migrate`

Running the App:
`Start the development server:`

Bash
`python manage.py runserver`

This will typically run the app at http://localhost:8000/ by default.

Usage:

Access the app in your web browser.
Enter a food name in the search field and submit.
View the calculated calories, nutritional breakdown, and estimated exercise durations.

Contributing:

We welcome contributions to this project! Feel free to fork the repository, make changes, and submit pull requests.

