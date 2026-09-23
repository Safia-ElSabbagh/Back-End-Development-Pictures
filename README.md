# coding-project-template

# Back-End-Development-Pictures

A Python Flask REST API project for managing picture data. This project was developed as part of the IBM Back-End Development Capstone work.

## Environment Setup

This project was created from the provided coding project template.

### Python Version

The project uses Python **3.9.x**.

### Virtual Environment

The virtual environment used for this project is:

```text
backend-pics-venv
```

### Setup

After cloning the repository, create and activate the virtual environment and install the required dependencies.

The provided setup script was executed successfully:

```bash
bin/setup.sh
```

The application can then be started using the project's Flask configuration.

## API

The application provides endpoints for working with pictures, including:

* `GET /picture` — retrieve all pictures
* `GET /picture/<id>` — retrieve a picture by ID
* `POST /picture` — create a new picture
* `PUT /picture/<id>` — update a picture
* `DELETE /picture/<id>` — delete a picture

## Testing

The API was tested using PyTest.

The tests cover:

* Application health
* Picture count
* Retrieving pictures
* Creating pictures
* Updating pictures
* Deleting pictures

All required API tests pass successfully.

## Repository

This repository contains the backend implementation and tests for the Pictures service.
