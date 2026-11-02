# Java Password Strength Checker

A simple Java program that checks password strength based on a few basic security requirements.

## The Problem

Weak passwords can put personal accounts at risk. If someone uses a weak password, their personal information could be stolen or exposed. I wanted to make something that helps people check how secure their passwords are.

## Project Goal

The goal of this project is to create a simple password strength checker using Java. It will help users understand whether their passwords meet basic security requirements.

## How It Works

The user will enter a password, and the program will check it against three requirements:

- Is the password at least 8 characters long?
- Does the password contain at least one number?
- Does the password contain at least one special character?

Based on how many requirements are met, the program will display a strength rating of Weak, Medium, or Strong.

## MVP Features

The first version of the program will:

- Allow users to enter a password.
- Check the password's length.
- Check for numbers.
- Check for special characters.
- Calculate and display a password strength rating.

## System Diagram

The flowchart below shows how the program will check each requirement and calculate the password strength.

![System Diagram](System%20Diagram.drawio.png)

The original editable diagram is also included in this repository as `System-Diagram.drawio`.

## Eisenhower Matrix

I used an Eisenhower Matrix to decide which features should be included in the first version of the project and which ones could be added later.

- **Do:** Password length check, number and special character checks, and strength rating.
- **Schedule:** Detailed suggestions, graphical interface, and password generator.
- **Delegate:** Built-in Java String methods, Scanner, and character checks.
- **Delete:** User accounts, password history databases, and animated backgrounds.

The complete matrix is available in `Eisenhower-Matrix.pdf`.

## Tech Stack

- **Language:** Java
- **User Input:** Scanner
- **String Processing:** Built-in Java String methods
- **Character Checking:** Built-in Java character methods
- **Development Environment:** Visual Studio Code
- **Version Control:** Git and GitHub
- **Data Storage:** No database needed
- **External APIs:** None

The program will run locally in the terminal.

## Development Plan

I plan to build the project in smaller steps so that each part can be tested before moving on.

1. Set up the GitHub repository and project files.
2. Create the Java program and set up user input.
3. Add a check for password length.
4. Add a check for numbers.
5. Add a check for special characters.
6. Create a system for calculating password strength.
7. Display the strength rating to the user.
8. Test the program with different passwords and fix any issues.

Each step will be tracked using Git commits.

## Setup

This project is currently in the planning stage. Once the Java program is completed, users will need Java installed on their computer to run it.

The program will not require a database or any external libraries.

## Usage

Once completed, the program will work as follows:

1. Run the Java program.
2. Enter a password when prompted.
3. The program checks the password requirements.
4. The program displays a strength rating.

## Roadmap

Features I might add in future versions:

- [ ] Give detailed suggestions for improving passwords.
- [ ] Add a graphical user interface.
- [ ] Create a random password generator.

These features are not part of the initial MVP.

## Project Status

Currently in the planning and design stage.

The Eisenhower Matrix, system diagram, and development plan have been completed. The next step is to begin implementing the Java program.

## Author

Sreshta Sripuram

GitHub: https://github.com/sripuramsreshta
