# IntelliReply

IntelliReply is an AI-powered email assistant designed to process customer emails, analyze their context, and generate human-like responses. The assistant allows employees to review and approve AI-generated replies before sending, ensuring efficiency and professionalism.

## Installation

Clone the repository, create a virtual environment, and install the dependencies listed in `requirements.txt`. Use the `.env` file to configure environment variables like `OPENAI_API_KEY`, `SMTP_SERVER`, `EMAIL_ADDRESS`, and `EMAIL_PASSWORD`.

## Features

- Email processing with `imaplib` and `smtplib`.
- AI-powered reply generation using OpenAI's API.
- Employee review and approval before email replies are sent.
- Flask backend with SQLAlchemy for database management.

## Usage

Run the Flask application to process incoming emails and generate replies. Approve replies via the provided interface before sending.

## Project Structure

- `env/`: Virtual environment directory (excluded from version control)
- `app/`: Application code, including routes, models, and utilities
- `migrations/`: Database migrations
- `tests/`: Unit tests
- `requirements.txt`: Project dependencies

## License

This project is licensed under the MIT License.
