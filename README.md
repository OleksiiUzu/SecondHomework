# Flask - creating API part 2

## About

This repository is my second homework assignment from the Python Pro course. 

My task was to create a database and tables. 
We hadn't studied models and migrations yet, so we did it through third-party software SQLiteStudio. 
All in order to add to the endpoints where it was possible to connect to the database and extract information from the database. 

 - I added a script from the db_methods.py file get_db_data() to the endpoints in view.py. The script only retrieves information from the database.
 - The POST method is not yet implemented.

## How to Run

1. Clone the repository:  
   ```bash
   git clone https://github.com/OleksiiUzu/SecondHomework.git
   cd SecondHomework
2.(Optional) Create and activate a virtual environment:
  python -m venv venv
  source venv/bin/activate

3.Install dependencies:
  pip install -r requirements.txt

4.Run the application:
  python app.py
