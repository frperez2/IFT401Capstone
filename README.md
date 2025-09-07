# IFT401Capstone
IFT 401 Capstone
StockTrader is a basic Flask web application that allows users to **register**, **log in**, and view a simple account page.  
This project has the foundation for a stock trading system and can be extended with additional features like an **admin page**, **portfolio dashboard**, and **buy/sell stock functionality**.
StockTrader/
│── app.py # Main Flask app with login, register, and account routes
│── init_db.py # Initializes SQLite database (users.db)
│── users.db # SQLite database (created after running init_db.py)
│── requirements.txt # Python dependencies
└── templates/ # HTML templates
├── login.html # Login form
├── register.html # Registration form
