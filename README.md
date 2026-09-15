Country Explorer (by Region)

See a video description of the program at:
https://www.loom.com/share/cb3865ef9de249ddb7bbe76d6f354d59

-------------

A command-line tool for exploring countries by region. Fetch country data from the REST Countries API, view general information (description, population, government structure), and filter countries by international memberships (EU, NATO, etc.)

_ _ _ _ _ _ _

API used: "https://api.restcountries.com/countries/v5"

API key: required, free to obtain on the website: https://restcountries.com/docs/countries

Key handling: stored in .env file, read via "COUNTRY_API_KEY" environment variable

The project requires installation of your own .env file
_ _ _ _ _ _ _

Requirements

Required: Python Python 3.14.6 or greater installed. 

Dependencies: install with pip install -r requirements.txt

Required: 
certifi==2026.7.22
charset-normalizer==3.5.1
contourpy==1.4.0
cycler==0.12.1
fonttools==4.65.0
idna==3.19
kiwisolver==1.5.1
matplotlib==3.11.2
numpy==2.5.3
packaging==26.3
pillow==12.3.0
pyparsing==3.3.2
python-dateutil==2.9.0.post0
python-dotenv==1.2.3
requests==2.34.2
six==1.17.0
urllib3==2.7.0
_ _ _ _ _ _ _

How To Run: python main.py

The program presents a looping menu:
        === Country Explorer (by Region) ===
        1. Get general country information
        2. Filter by membership
        3. Compare Countries (Chart)
        4. Quit

        Choose an option (1-4):


Option 1: Input a region (Europe, Asia, etc.). The program fetches all countries and prints: country name, short description, population, government type

Option 2: Prompts for a region and then shows a menu of international organizations. Input numbers separated by spaces. THe program matches the countries that are members and prints their names.

Option 3: Compare Countries (Chart)
## Visualization (Option A)
   After picking a region, the user sees output of countries they can compare and the following menu with 4 available choices.
   
        What would you like to compare?
        1. Population
        2. Area
        3. Population density
        4. Go back
        Choose an option (1-4):

After the user chooses, next menu allows user to pick what countries they want to compare.

        Compare data for chosen countries
        Pick 2-6 countries to compare:

Option 4: Quit

-------------------
