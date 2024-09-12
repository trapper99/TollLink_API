# TollLink_API - A Toll API Project

This is a Toll API for managing toll booths, vehicles, transactions, and payments, built using Django Rest Framework.

## Features
- Vehicle management
- Toll booth management
- Tariff and transaction tracking
- Payment processing

## Setup

### Prerequisites

- Python 3.x
- PostgreSQL or SQLite

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/toll-api.git
    ```

2. Navigate to the project directory:
    ```bash
    cd toll-api
    ```

3. Create and activate a virtual environment:
    ```bash
    python -m venv env
    source env/bin/activate
    ```

4. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

5. Set up your database in `toll_api/settings.py`. 

6. Apply migrations:
    ```bash
    python manage.py migrate
    ```

7. Run the development server:
    ```bash
    python manage.py runserver
    ```

### Running Tests

To run tests, use:

```bash
python manage.py test
