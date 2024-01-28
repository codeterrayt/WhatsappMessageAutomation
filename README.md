# 📱 Whatsapp Message Automation

Automate sending WhatsApp messages using Python and the `pywhatkit` library. Schedule messages to be sent to specific contacts at a designated time.

## Introduction

This WhatsappMessageAutomation project allows you to automate sending WhatsApp messages using Python. It utilizes the `pywhatkit` library to interact with the web version of WhatsApp and send scheduled messages.

## Features

- **Message Automation:** Schedule and send WhatsApp messages programmatically.
- **Easy Configuration:** Customize the recipient's phone number, message content, and delivery time in the script.
- **Time-Sensitive:** Send messages at specific hours and minutes.

## Prerequisites

Ensure you have Python installed on your system.

## Installation

1. Clone the GitHub repository:

    ```bash
    git clone https://github.com/codeterrayt/WhatsappMessageAutomation.git
    cd WhatsappMessageAutomation
    ```

2. Install the required library:

    ```bash
    pip install pywhatkit
    ```

## Usage

1. Open `main.py` in a text editor.

2. Update the following variables with your message details:
    - `recipient_number`: The phone number of the message recipient, including the country code.
    - `message_content`: The content of the message you want to send.
    - `hour`: The hour at which the message should be sent (24-hour format).
    - `minute`: The minute at which the message should be sent.

3. Save the changes.

4. Run the script:

    ```bash
    python main.py
    ```

5. The script will send the specified message to the designated recipient at the scheduled time.

## Development

Feel free to explore and modify the code to suit your specific needs. You can customize the recipient's phone number, message content, and delivery time as per your requirements.

## Acknowledgments

This project uses the `pywhatkit` library for interacting with WhatsApp. Explore the [pywhatkit GitHub Repository](https://github.com/Ankit404butfound/PyWhatKit) for more information.

📬 Happy Messaging Automation! 🚀
