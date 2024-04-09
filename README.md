This GitHub repository contains a Python script designed to integrate with a custom Anythingllm API. The script allows users to send chat messages to a specified workspace within the API's environment. It utilizes the Requests library to make HTTP POST requests, sending chat messages and receiving responses. The functionality includes setting up necessary parameters such as the API base URL, authentication token, and workspace slug, ensuring a customizable and secure communication channel. This tool is ideal for developers looking to automate interactions or integrate chat functionalities within their applications or services.


# Anythingllm API Integration Tool

This Python script provides a straightforward way to send chat messages to a specific workspace using Anythingllm API. It's designed to facilitate communication and integration for developers looking to incorporate chat functionalities into their applications.

## Features

- Send chat messages to a specified workspace.
- Customize the API endpoint, authentication token, and workspace slug.
- Receive and display responses from the Anythingllm API.

## Prerequisites

Before you begin, ensure you have the following installed:
- Python 3.x
- Requests library (Install using `pip install requests`)

## Configuration

Replace the placeholders in the script with your actual data:
- `SERVER_IP`: Your server's IP address.
- `API_TOKEN`: Your API authentication token.
- `WS_NAME`: Your workspace name in lower case.

## Usage

1. Open your terminal or command prompt.
2. Navigate to the directory containing the script.
3. Run the script using the command `python script_name.py`.
4. Enter your chat message when prompted. Type 'exit' to stop the script.
