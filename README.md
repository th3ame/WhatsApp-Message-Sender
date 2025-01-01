WhatsApp Message Sender

A web-based application to send WhatsApp messages to a list of recipients using the Metaphilia API. This script allows you to specify the message content, recipient numbers, and an interval between each message.

Features

Send WhatsApp messages via the Metaphilia API.

Input multiple recipient numbers separated by new lines.

Define a custom interval (in seconds) between sending each message.

Receive success or error alerts for each message sent.

Responsive design using Bootstrap 5.

Prerequisites

An active API key for the Metaphilia WhatsApp API.

A web browser to run the HTML file.

Installation

Clone the repository or download the index.html file.

Open the index.html file in any modern web browser.

Usage

Enter your API Key provided by Metaphilia.

Provide the sender's WhatsApp number.

Add recipient numbers, one per line, in the designated text area.

Write the message content in the provided text area.

Specify the interval in seconds between sending messages.

Click the Send Messages button.

View the status of each message below the button.

API Details

Endpoint

https://wweb.metaphilia.com/api/send-message

Parameters

Parameter

Type

Required

Description

api_key

string

Yes

API key for authentication

sender

string

Yes

Sender's WhatsApp number

number

string

Yes

Recipient's WhatsApp number

message

string

Yes

Message content

Response

Success

{
  "status": 1,
  "success": "Message sent successfully."
}

Error

{
  "status": 0,
  "message": "Error message."
}

Technologies Used

HTML5: Markup structure

CSS3: Styling with Bootstrap 5

JavaScript: Logic and API interaction

Bootstrap 5: Responsive design

License

This project is licensed under the MIT License.

Author

ENG Abdulrahman Mohamed Eid

© 2025 ENG Abdulrahman Mohamed Eid. All rights reserved.

