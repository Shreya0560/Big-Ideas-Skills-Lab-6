### README

## What our Program Does

Our program predicts the future! Based on your name and age, our program will predict what your future occupation will be as well as the name of your future spouse.

## How to Use it  

# Getting Started
In order to use our program, you first install the program using the following commands 
If you use conda, mamba, or pip, you can install CrystalBall  with one of the following commands.
If you use conda:
conda install -c conda-forge crystalball
If you use mamba:
mamba install -c conda-forge crystalball
If you use pip:
pip install crystalball
If installing using pip install --user, you must add the user-level bin directory to your PATH environment variable in order to launch crystal ball. If you are using a Unix derivative (e.g., FreeBSD, GNU/Linux, macOS), you can do this by running export PATH="$HOME/.local/bin:$PATH". If you are using a macOS version that comes with Python 2, run pip3 instead of pip.
For more detailed instructions, consult the installation guide. Project installation instructions from the git sources are available in the contributor documentation.

# Running
Start up CrystalBall  using:
crystal ball
CrystalBall will open automatically in the browser. See the documentation for additional details.
If you encounter an error like "Command 'crystal' not found", please make sure PATH environment variable is set correctly. Alternatively, you can start up CrystalBall using ~/.local/bin/crystal ball without changing the PATH environment variable.
Prerequisites and Supported Browsers
The latest versions of the following browsers are currently known to work:
Firefox
Chrome
Safari



## How to Contribute

Do you wish our program could predict even more aspects of the future? Have an idea for how to implement it? We’d love to have your contributions on our project.

When you send us a pull request, please be sure to introduce yourself and specify what area of the program you’d like to contribute to, as well as a short explanation of what your code does. 

# Testing

Please test your changes before submission- it makes our jobs even easier and allows us to see how your changes will enhance our project.

# Manual testing
We support recent versions of Firefox, Chrome, Internet Explorer, Edge, iOS Safari and the Android browsers (full list of supported browsers and versions). Be sure to try your feature out in IE9, iOS and Android if it's a risk. Sauce Labs lets you run manual tests in these browsers remotely.

# UI tests
Our continuous integration server regularly runs a suite of UI tests using Selenium / Cucumber which run against many browsers via Sauce Labs, and can also be run locally using chromedriver. 
If your changes might affect level paths, blockly UI, or critical path site logic, be sure to test your changes with a local UI test.
