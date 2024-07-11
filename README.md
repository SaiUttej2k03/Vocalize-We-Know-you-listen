# Vocalize: Text-to-Speech Converter

Vocalize is a text-to-speech converter that links VSCode with the AWS Management Console to synthesize speech using Amazon Polly. This project uses the AWS SDK for Python (Boto3) and a simple Tkinter GUI to convert user-inputted text to speech.

## Features

- Convert text to speech using Amazon Polly
- Simple and intuitive GUI built with Tkinter
- Output speech in MP3 format
- Exception handling for robust performance

## Requirements

- Python 3.6 or higher
- Boto3
- Tkinter

## Setup

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/vocalize.git
    cd vocalize
    ```

2. **Install dependencies:**

    ```bash
    pip install boto3
    ```

3. **AWS Configuration:**

    Ensure you have an AWS account and set up a user with the necessary permissions to access Amazon Polly. Configure your AWS credentials using the AWS CLI:

    ```bash
    aws configure
    ```

    Or set up a profile for the user in your `~/.aws/credentials` file:

    ```plaintext
    [Demo_user]
    aws_access_key_id = //Enter your access key id here that is generated by the IAM or Root user using Polly service
    aws_secret_access_key = //Secret key for the same
    ```

## Usage

1. **Run the application:**

    ```bash
    python vocalize.py
    ```

2. **Enter text in the GUI text box and click the "Read" button to convert the text to speech.**


