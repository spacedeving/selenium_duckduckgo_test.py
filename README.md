Selenium DuckDuckGo Search Automation (Python)
Overview

This project is a simple Selenium automation test written in Python.
It opens DuckDuckGo, performs a search for "Selenium Python", clicks the first result, and verifies that the resulting page contains the word "selenium".

This project is ideal for beginners learning:

Selenium WebDriver

Explicit waits

Basic UI test automation

Assertions in Python

Technologies Used

Python 3

Selenium

Google Chrome

ChromeDriver

Features

Launches a Chrome browser using Selenium

Uses explicit waits for reliable element interaction

Performs a search on DuckDuckGo

Clicks the first search result

Asserts that the page content is correct

Keeps the browser open after execution for inspection

Project Structure
selenium-duckduckgo-test/
│
├── test_search.py
└── README.md

Prerequisites

Before running the script, make sure you have:

Python 3 installed

Google Chrome installed

ChromeDriver installed and added to your system PATH

Selenium installed

Install Selenium with:

pip install selenium

How to Run

Clone this repository:

git clone https://github.com/your-username/selenium-duckduckgo-test.git


Navigate to the project directory:

cd selenium-duckduckgo-test


Run the script:

python test_search.py

Expected Output

Chrome opens DuckDuckGo

Searches for "Selenium Python"

Clicks the first result

Verifies the page content

Prints:

TEST PASSED

Notes

The script uses explicit waits to handle dynamic page loading.

The browser remains open after execution due to the detach option.

This project is intended for learning and demonstration purposes.

Author

Created by a Python automation learner practicing Selenium WebDriver and UI testing.
