1. Install Python 3.13+ on your PC
2. Extract this folder anywhere
3. Open terminal in the folder
4. Create virtual environment:
   python -m venv venv
5. Activate virtual environment:
   Windows: venv\Scripts\activate
   Mac/Linux: source venv/bin/activate
6. Install dependencies:
   pip install -r requirements.txt
7. Run server:
   python manage.py runserver
8. Open browser:
   http://127.0.0.1:8000/
9. Login using admin credentials (if db.sqlite3 included)