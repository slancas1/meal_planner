## Dining Hall Meal Planner

**Authors:** Sophie Lancaster, Brianna Hoelting, Anthony DiFalco, Elisabetta Caldesi

A program that takes user input and creates a menu for the user based on the items that can be found in the dining halls. 
For more details about the project refer to the *finalreport.txt* file.

## How to Use

1. For optimal performance, use on your local machine and preferably on a Mac.
2. Download the API client library using the following instructions:
	* Download pip installer in Terminal using the following command: `sudo easy_install pip`
	* Download the Google API client using the following command: `sudo pip install --upgrade google-api-python-client`
3. Clone this repository using the following command: `git clone https://github.com/slancas1/meal_planner.git`
4. Run the Makefile by using the following command: `make`
5. Insert meal preference when prompted using the following input options:
	* B = breakfast
	* L = lunch
	* D = dinner
6. Enter food preferences in CSV format when prompted.
	* **EXAMPLE:** corn,chicken,rice
	* Make sure there are no spaces in the input
	* Max of 5 inputs
7. Enter total desired calorie count for meal as a single number when prompted.
8. If you are running the program on your local machine, the output will be an HTML page that opens in your preferred browser.
Otherwise, the output, excluding the images, will be displayed in a terminal window.

## Still to Do

* Make it more cohesive by allowing input to come from an HTML page as well
* Make it more dynamic
	* Use web scraping to retrieve daily menu items
	* Allow the user to enter as many menu items as they would like
* Create more detailed algorithm for choosing food items / utilize calories better when choosing menu items
* Include other options like allergens, dietary restraints, etc.

## Known Issues

* Sometimes the Google API returns very strange photos or no photo at all 
