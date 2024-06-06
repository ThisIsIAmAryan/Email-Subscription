# Email Subscription Page

This is a simple email subscription page that allows users to subscribe to a newsletter. The form submission is connected to Google Sheets to store the email addresses.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Credits](#credits)

## Features
- Responsive design
- Email input validation
- Form submission without page reload
- Confirmation message after successful subscription

## Technologies Used
- HTML
- CSS
- JavaScript
- Google Sheets

## Setup and Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/ThisIsIAmAryan/email-subscription.git
    cd email-subscription
    ```

2. **Set up Google Sheets:**
    - Follow the instructions provided in [this repository](https://github.com/jamiewilson/form-to-google-sheets) to set up Google Sheets and create a Google Apps Script.

3. **Update the script URL:**
    - Replace the `scriptURL` in the `index.html` file with the URL of your Google Apps Script.

4. **Run the project:**
    - Open `index.html` in your browser to see the email subscription page in action.

## Usage
1. Open the `index.html` file in your browser.
2. Enter your email address in the input field.
3. Click the submit button.
4. A confirmation message will be displayed, and the email will be added to the connected Google Sheet.

## Credits
- Form to Google Sheets conversion code by [Jamie Wilson](https://github.com/jamiewilson/form-to-google-sheets)

---

*Created by ThisIsIAmAryan*
