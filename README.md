# Data Science Program  Building Software

# Hello World ! & GitHub Star Explorer 

This project consists of a Python script (`hello.py`) that uses `argparse` to handle YAML configuration files and makes API requests to GitHub to retrieve a list of the top 20 starred GitHub repositories.

## Getting Started

Follow these instructions to set up the project on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have Python installed on your system and `requests` for making API requests.


### Setting Up

1. **Clone the Repository**:

2. **Navigate to the Project Directory**:

### Configuration

Create a YAML configuration file (`config.yml`) in the project directory with the following structure:

yaml
token: YOUR_GITHUB_ACCESS_TOKEN
Replace YOUR_GITHUB_ACCESS_TOKEN with your personal GitHub access token.

Running the Script
Run hello.py with the path to your configuration file:

python hello.py -c config.yml

This will execute the script, which fetches the top 20 starred GitHub repositories and prints them to the console.

How It Works

hello.py: A Python script that reads  for the GitHub API token, makes an API request to GitHub and retrieves information about the top 20-starred repositories.

GitHub API: Used for fetching repository data based on star counts.

Deployment
This script is intended for local running and testing.
For deployment in a production environment, additional security and error-handling measures should be considered.

Built With
Python
Requests - For making HTTP requests to the GitHub API

Authors
Initial work - rashettycode

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

### Acknowledgments
GitHub API for providing repository data.
Python community for the extensive libraries and support.
