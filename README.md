# Workout Tracking

A Workout Tracking app helps you to save your workout data to Google Sheets.

<p align="center">
  <img src="https://i.giphy.com/media/cedP12gz6jwgurvtre/giphy.webp" alt="workout-tracking-app"/>
</p>

# Installing
Download the [Python 3](https://python.org) installer package from the official website and install it, if not installed previously.

* Run the following in the terminal to install the Requests module to **post** your working data to [Sheety](https://sheety.co/).
```
pip install requests
```
* Follow to [this](https://docs.google.com/spreadsheets/) link to create a blank **Google Spreadsheets** file to save our data here.
* Go to the [Nutritionix API](https://www.nutritionix.com/business/api) website and select **"Get Your API Key"** to sign up for a free account. 
* Once logged in, you should be able to access your ```API_KEY``` and ```API_ID```. You can replace it in the code file.
* Now, Log into [Sheety](https://sheety.co/) with your Google Account. (Make sure the email matches between your Google Sheet and Sheety Account)
* Click on "New Project" and create a new project in Sheety with the name "Workout Tracking" and paste in the URL of your own Google Sheet file.
* Modify the workouts API endpoint and enable GET and POST settings.
* Add either "Bearer Token" to your Sheety endpoint to secure it. 

# How to Use?

Download the source code from the repository and run the file just as any other Python script (.py) file.
```
python3 main.py
```
* Note! For the code to work you need to replace all the placeholders with your own details. e.g. ```API_KEY```, ```SHEETY_USER_ID```, ```PROJECT_NAME```.

Once you replace the own details in the code, run the program.

<p align="center">
  <img src="https://i.giphy.com/media/0oCIUVut3eqR4IaFZy/giphy.webp" alt="workout-tracking-console"/>
</p>

Type your workout what you did today and type enter to save it. It will save it to your Google Sheets file. 

Check out the link below for more details about API sources.

# Documentations

* [Sheety](https://sheety.co/)
* [Nutritionix](https://developer.nutritionix.com)
* [Nutritionix API Docs](https://docs.google.com/document/d/1_q-K-ObMTZvO0qUEAxROrN3bwMujwAN25sLHwJzliK0/edit#heading=h.73n49tgew66c)
* [Google Sheets](https://docs.google.com)

