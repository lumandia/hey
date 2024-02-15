# hey
from flask import Flask

# Create a Flask web application
app = Flask(__name__)

# Define a route for the home page
@app.route('/')
def home():
    return 'Hello, World! This is my website.'

if __name__ == '__main__':
    # Run the Flask app
    app.run(debug=True)
