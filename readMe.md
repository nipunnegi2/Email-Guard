## SafeMail
<a href="https://nipunnegi2.github.io/Email-Guard/">UiDemo</a>
SafeMail is a web application that allows users to check the reputation of an email address using the [emailrep.io](https://emailrep.io/) API. It provides information about the email's reputation, whether it is suspicious, and other related details.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Key](#api-key)
- [Project Structure](#project-structure)
- [License](#license)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/safemail.git
    cd safemail
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Set your `API_KEY` in the `templates/app.py` file:
    ```python
    API_KEY = 'your_api_key_here'
    ```

2. Run the Flask application:
    ```bash
    python templates/app.py
    ```

3. Open your web browser and go to `http://127.0.0.1:5000/`.

4. Use the form on the homepage to enter an email address and check its reputation.

## API Key

You need an API key from [emailrep.io](https://emailrep.io/) to use this application. Follow these steps to obtain your API key:

1. Go to [emailrep.io](https://emailrep.io/).
2. Sign up for an account.
3. Navigate to the API section to obtain your API key.
4. Replace the `API_KEY` in `templates/app.py` with your key.

## Project Structure

