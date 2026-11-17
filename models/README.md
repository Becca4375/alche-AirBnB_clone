# ALX — `AirBnB clone` The console

0x00. AirBnB clone - The console

## Project Overview

Part of the **ALX Software Engineering Program**, this project focuses on creating a command interpreter for an AirBnB website clone. The command-line interface allows data manipulation tasks without a visual interface, including object management and a robust storage system using JSON files.

## Description of the command interpreter:

This is a command-line tool that lets you manage the data for an AirBnB-like website. You can use it to create, view, update, and delete objects like users, places, and reviews without needing a website. It's a simple way to interact with the application's data directly.

## How to Use the Console:

You can start the console by running the `console.py` file. Once it's running, you can type commands to manage your application's data. For example, you can create a new user, find a place by its ID, or update a review.

## Project File Structure:

The project is organized into several folders and files:

- **`console.py`**: This is the main entry point for the command-line interpreter.
- **`models/`**: This folder contains all the data models for the application.
  - `base_model.py`: This is the main model that all other models are built on.
  - Other files like `user.py`, `place.py`, and `review.py` define specific objects in the application.
  - **`engine/`**: This sub-folder manages data storage.
    - `file_storage.py`: This file handles saving and loading data to and from a JSON file.
- **`tests/`**: This folder contains all the tests to make sure the application works correctly.
- **`web_static/`**: This folder contains the files for the web front-end of the project.

## Project Implementation Steps:

This project was built in several stages, starting with the base model and file storage, then creating the command-line interpreter, and finally adding all the different data models and tests.

## Team Members:

*Rebecca Adhiambo oduor** — [_https://github.com/EL-OUARDY_](https://github.com/EL-OUARDY) \
**Chioma Mmadu** — [_https://github.com/zakariabahlaoui_](https://github.com/zakariabahlaoui)
