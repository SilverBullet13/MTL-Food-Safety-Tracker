<!--#### Table of Contents
1. [About The Project](https://github.com/SilverBullet13/Montreal-Food-Safety-Alerts/blob/main/README.md#table-of-contents)
   - [Built With](https://github.com/SilverBullet13/Montreal-Food-Safety-Alerts/blob/main/README.md#built-with)
2. [Getting Started](https://github.com/SilverBullet13/Montreal-Food-Safety-Alerts/blob/main/README.md#getting-started)
   - [Prerequisites](https://github.com/SilverBullet13/Montreal-Food-Safety-Alerts/blob/main/README.md#prerequisites)
   - [Installation](https://github.com/SilverBullet13/Montreal-Food-Safety-Alerts/blob/main/README.md#installation)
   - [Run](https://github.com/SilverBullet13/Montreal-Food-Safety-Alerts/blob/main/README.md#run)
3. [Future Work](https://github.com/SilverBullet13/Montreal-Food-Safety-Alerts/blob/main/README.md#future-work) -->

## About The Project

MTL Food Safety Tracker is a Flask web application to search and explore food safety violations reported by the City of Montreal using public inspection data.

![Landing page project image](https://github.com/SilverBullet13/Montreal-Food-Safety-Alerts/blob/dev/images/Screenshot%202026-10-06%20at%2014.27.06.png)

#### Demo
[Watch here](https://www.loom.com/share/c3d91704ee4343a8976e747e3f5e1339)

[Link to dataset](https://donnees.montreal.ca/en/dataset/inspection-aliments-contrevenants?)

#### Features
- Search by establishment name, owner, and street
- Date range filtering - returns total violations per establishment within the selected period
- Automated data sync via BackgroundScheduler

#### Built With
- Python
- Flask
- SQLite3
- Git

## Getting Started

#### Prerequisites 
- python 3.12

#### Installation
1. Clone the repo
   - ```git clone https://github.com/SilverBullet13/Montreal-Food-Safety-Alerts.git```
2. Install dependencies
   - ```pip install -r requirements.txt```

#### Run
1. Collect the data from the City of Montreal public 
database.
   - ```python collect_data_script.py```
2. Launch the app: 
   - ```python app.py```

 <!-- ## Future Work  
- Complete unfinished features : 
  - Set up a BackgroundScheduler to update the data in the database
   - Add a "Basic Auth" authentication procedure to restrict access to
    modification and deletion features only to a predefined user
  - Add deletion feature
  - Add modification feature
  - Add a form to make inspection requests to the city
- Improve project structure and code readability
- Refactor parts of code base 
- Continue testing and bug fixing  -->
