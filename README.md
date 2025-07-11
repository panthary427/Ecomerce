
# To Start Using The Project
# Step 1: Clone The Repositories
git clone https://github.com/tharypan/Ecomerce.git
# Step 2: Navigate To Computer-Selling
cd Computer-Selling
# Step 3: Create Python Environment
For Windows
python -m venv .env
For Mac
python3 -m venv .env
# Step 4: Activate The Environment
For Windows
.env\Scripts\activate
For Mac
source .env/bin/activate
# Step 5: Install Dependencies From requirements.txt
pip install -r requirements.txt
Step 6: Navigate To The File
cd Django
# Step 7: Create Database (SQL lite)
python manage.py makemigrations 
python manage.py migrate
# Step 8: Create Admin User
python manage.py createsuperuser
Note : For skipping email just press Enter
# Step 9: Run The Project
python manage.py runserver
# ‼️To Close The Python Environment ‼️
cd ..

