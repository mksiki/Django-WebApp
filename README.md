# Django-WebApp
Django WebApp is a web application built using the Django framework that allows users to interact with a subscription system, Google authentication, and user management features. It provides functionalities for user registration, login with Google, subscription management using Stripe, PostgresSQL(ElephantSQL-PGAdmin4) and more.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- - [Prerequisites](#prerequisites)
- - [Installation Steps](#installation-steps)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- User registration and login using Google authentication.
- Subscription management system.
- Viewing, creating, updating, and deleting user accounts.
- Integrates with Stripe for handling subscriptions and payments.

## Installation

### Prerequisites

- Python 3.x
- Pip (Python package installer)
- Docker (optional, for containerized deployment)
- Stripe API keys (required for subscription functionality)

### Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Django-WebApp.git
   cd Django-WebApp

    Install the required Python packages using pip:

    bash

pip install -r requirements.txt

Set up your Stripe API keys:

    Replace STRIPE_PUBLISHABLE_KEY and STRIPE_SECRET_KEY in settings.py with your Stripe API keys.
    Replace STRIPE_PRICE_ID and STRIPE_ENDPOINT_SECRET with your Stripe price ID and webhook secret.

Run the Django development server:

bash

    python manage.py runserver

    Access the web application in your browser at http://localhost:8000/.

Dockerized Installation (Optional)

    Make sure you have Docker installed.

    Build the Docker image and run the container:

    bash

    docker-compose up --build

    Access the web application in your browser at http://localhost:8000/.

Usage

    Launch the application and navigate to the home page.
    Use Google authentication to log in.
    Once logged in, you can manage your subscription, view, create, update, or delete user accounts.

Contributing

Contributions are welcome! If you find any issues or want to improve the project, feel free to open a pull request.
License

This project is licensed under the MIT License.

Note: This README provides a general guide to get started with the Django WebApp project. Make sure to customize it according to your specific project details and requirements.
