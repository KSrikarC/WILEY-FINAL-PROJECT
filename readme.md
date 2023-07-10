# Flask & SQL Web app for Banking application

This is a simple banking application developed using Flask and MySQL. It allows users to sign up, sign in, perform withdrawals, deposits, and view transaction history.

## Features

- User Sign Up: Users can create an account by providing their name, username, password, date of birth, mobile number, and initial deposit amount.

- User Sign In: Existing users can sign in using their username and password.

- Withdrawal: Users can withdraw funds from their account. The available balance is displayed, and the user can enter the withdrawal amount.

- Deposit: Users can deposit funds into their account. The user can enter the deposit amount.

- Transaction History: Users can view their recent transaction history, including the type of transaction (withdrawal or deposit), amount, date, and remaining balance.

## Prerequisites

- Python 3.8 or higher
- Flask
- MySQL
- MySQL Connector

## Installation

1. Clone the repository:

   git clone https://github.com/KSrikarC/WILEY-FINAL-PROJECT.git

2. Install the required dependencies:   

    pip install -r requirements.txt

3. Set up the MySQL database:

    Create a new MySQL database named bank.
    Update the database connection details in app.py file (host, user, password).

4. Start the application:
    
    python app.py

5. Access the application in your web browser:

    http://localhost:5000


## File Structure
app.py: Contains the Flask application code, including routes and database interactions.
templates/: Contains HTML templates for different pages.

## Contributing
This is a publice repo and Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

