# E_DX-s-weather-script
a simple weather script
the following dependencies:

i also have a python install_weather_checker.py to install it faster


# Clone the Git repository
git clone https://github.com/Edx-X11/E_DX-s-weather-script/

# Create and activate a virtual environment (optional but recommended)
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

For your PyQt5-based weather checker GUI application, the main dependency is PyQt5 itself, as well as the requests library for making HTTP requests. 

Here's a list of the dependencies along with their purposes:

PyQt5 (5.15.4): A Python library for creating graphical user interfaces (GUIs). It's used to design and run the graphical part of your weather checker application.

requests (2.26.0): A Python library for making HTTP requests. It's used to fetch weather data from an external API.

These are the core dependencies needed



To install the required dependencies on Arch Linux, you can use the pacman package manager. Here's how you can do it:

PyQt5:
Arch: sudo pacman -S python-pyqt5
Ubuntu: sudo apt-get install python3-pyqt5
CentOS/RHEL: sudo yum install python3-qt5
Requests:
Arch: sudo pacman -S python-requests
Ubuntu: sudo apt-get install python3-requests
CentOS/RHEL: sudo yum install python3-requests

OpenSUSE a little more detail.
-------------------------------
Check if Python is already installed by running the following command in the terminal:
python3 --version
If Python is not installed, you can install it using the package manager:
pip3 install -r requirements.txt
Clone the Repository:
Clone your GitHub repository containing the Python application code to your local system. You can use the git command:
git clone https://gitNavigate to the Application Directory:
Change the directory to the location of your cloned repository
CD E_DX-s-weather-script //untested if it states diffrent please use that.//

Run the Application:
Run the Python script that launches the GUI or the weather checker app, depending on your code. Use the following command: 
python3 weather_checker_gui.py or python3 weather_checker.py

Ensure that you have a valid API key from OpenWeatherMap (or another weather API provider). This API key is required to fetch weather data. If you haven't done so, you need to sign up for an API key and replace the placeholder value in your code with the actual key.
