# Extract-Transform-Load Challenge Instructions V1.0
## Written by Christopher Sadlo and Glenda Decapia

<br><br>

# Step 1
### Clone the repository:

* Launch Git BASH or your favorite terminal.

* Move into the directory you want to store the package


        cd <my_directory>
        git clone https://www.github.com/csadlo/ETL-challenge


# Step 2
### Installing the country_converter API:  https://pypi.org/project/country-converter/

    source activate NewPythonData
    pip install country_converter --upgrade
    cd ETL-challenge


# Step 3
### Creating api_keys.py file:

* Create a file called "api_keys.py" in the ETL-challenge folder and add the following code:

        weather_api_key = "<insert your api key for OpenWeatherMaps.org>"
        google_key = "<insert your api key for Google Maps>"

* Save and close the api_keys.py file in the ETL-challenge root folder.


# Step 4
### Creating config.py file:

* Create a file called "config.py" in the ETL-challenge folder and add the following code:

        username = "<insert your username>"
        password = "<insert your password>"

* Save and close the config.py file in the ETL-challenge root folder.


# Step 5
### Launching and setting up the hurricanes database in pgAdmin:

* Launch pgAdmin.
* Right-click on "Databases" and create a new database called "hurricanes".
* Right-click on "hurricanes" and left-click on "query-tool".
* Click on the open file icon and navigate to the ETL-challenge folder.
* Open the "schema.sql" file.
* Run the schema.sql file to create the table.


# Step 6
### Executing the jupyter notebook:

* Move into the ETL-challenge folder if not there already.

        cd ETL-challenge
        jupyter notebook

* Open and execute hurricane.ipynb file

# Step 7
## Profit?