# Back-End Development Songs

## Project Overview

This project is a Python Flask microservice for managing song data. It provides API endpoints for checking service health and retrieving, creating, updating, and deleting song records.

## Environment Setup

### Prerequisites

- Python 3.9.x
- Git
- A terminal or command-line environment

### Create the Project

Create or clone the `Back-End-Development-Songs` repository from the course-provided project template.

### Run the Setup Script

From the project root directory, run:

```bash
bin/setup.sh
```

Review the output and confirm that setup completes successfully.

### Activate the Virtual Environment

The expected virtual environment name is `backend-songs-venv`. If the setup script creates it, activate it using the command appropriate to your shell. For a typical Bash environment:

```bash
source backend-songs-venv/bin/activate
```

If the environment is stored in a different location, use the path reported by the setup script.

### Run the Application

Follow the project's configuration and instructions to start the Flask application. Confirm that the service starts successfully before testing its endpoints.

## Testing

Run the automated tests from the project root:

```bash
pytest
```

Use the course lab instructions to verify the expected health and song API endpoints.

## Notes

Use the course lab instructions for any required database configuration, environment variables, and deployment settings.
