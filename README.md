# Python_Api

### Hotel Finder
This program uses the Geoapify API to find hotels in cities that meet certain weather criteria. The program reads in a CSV file containing weather data for various cities, filters the cities based on temperature, humidity, and cloudiness, then uses the Geoapify API to find hotels in the remaining cities. The program then generates a map showing the location and hotel information of the cities where hotels were found.

### Prerequisites
To run this program, you will need to have the following installed:

- Python 3.6 or later
- pandas
- hvplot
- requests
- You will also need to obtain an API key for the Geoapify API.

### Installation
To install the required packages, run the following command:

### bash

- pip install pandas hvplot requests //
You can obtain an API key for the Geoapify API from their website: https://www.geoapify.com/

### Usage
To use this program, simply run the irfansenyurt_VacationPy.ipynb The program will read in a CSV file named cities.csv containing weather data for various cities. The program will then filter the cities based on temperature, humidity, and cloudiness, then use the Geoapify API to find hotels in the remaining cities. Finally, the program will generate a map showing the location and hotel information of the cities where hotels were found.

### Example Output
Here's an example of what the output map might look like:

### Output Map

![map_ss](https://user-images.githubusercontent.com/35157651/231942853-d4eb0def-cd8d-483e-a17b-9b857f36d428.png)


### Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

### Credits
This program was written by Irfan Senyurt. The Geoapify API was developed by Geoapify (https://www.geoapify.com/).
