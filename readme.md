# Firecrawl Agent README

## Table of Contents

1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Troubleshooting](#troubleshooting)

## Introduction

Firecrawl Agent is a Python script that uses the Firecrawl API to scrape websites and save their content to a Markdown file.

## Prerequisites

* Python 3.6 or higher
* Git
* A Mac computer

## Installation

### Clone the repository
git clone git@github.com:alejandrosuarez/firecrawl-agent.git

### Navigate to the cloned repository
cd firecrawl-agent

### Create a new virtual environment
python3 -m venv venv

### Activate the virtual environment
source venv/bin/activate

### Install the required dependencies
python3 -m pip install -r requirements.txt

## Usage

To use Firecrawl Agent, simply run the script and enter the URL of the website you want to scrape:
python3 firecrawl_script.py

Follow the prompt to enter the website URL.

## Troubleshooting

If you encounter any issues during installation or usage, check the following:

* Make sure you have the latest version of Python and Git installed.
* Verify that you have activated the virtual environment before running the script.
* Check the Firecrawl API documentation for any changes to the API endpoint or parameters.

**Note**: This script uses the Firecrawl API, which requires an API key. Make sure you have a valid API key in your .env file before running the script.