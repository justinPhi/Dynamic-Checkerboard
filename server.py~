from flask import Flask, render_template, request  # Import Flask to allow us to create our app
app = Flask(__name__)    # Create a new instance of the Flask class called "app"
print(__name__) #just for fun, print name
@app.route('/')          # The "@" decorator associates this route with the function immediately followingcopy
def index():
    return render_template("index.html")

if __name__=="__main__":   # Ensure this file is being run directly and not from a different module    
    app.run(debug=True)
