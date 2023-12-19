# Chess Tournament Management Program

This Python program is designed to help you create, launch, and manage chess tournaments with ease. Follow the step-by-step instructions below to get started:

## Table of Contents
- [Getting Started](#getting-started)
- [Player Menu](#player-menu)
- [Create Tournament](#create-tournament)
- [View Tournament](#view-tournament)
- [Add Player in Tournament](#add-player-in-tournament)
- [Create Match Schedule](#create-match-schedule)
- [Update Match Result](#update-match-result)
- [Tournament Completion](#tournament-completion)
- [Checking Completed Tournaments](#checking-completed-tournaments)
- [Notes](#Note)
- [PEP8 Compliance](#PEP8-compliance)
- [How to generate a flake8 repport](#How-to-generate-a-flake8-repport)

## Getting Started

1. Clone or download this repository to your local machine.
2. Make sure you have Python installed on your computer.
3. Open a terminal or command prompt and navigate to the project directory.

## Player Menu

1. Run the program and select "Player Menu."
2. Create a player profile by following the prompts.
3. You can create multiple player profiles as needed.

## Create Tournament

1. From the main menu, select "Create Tournament."
2. Follow the on-screen instructions to set up your tournament.
3. Specify the tournament details, such as name and date.

## View Tournament

1. Select "View Tournament" from the main menu to see tournament details.
2. You can view information about the current tournament, including players and rounds.

## Add Player in Tournament

1. To add a player to an existing tournament, choose "Add Player in Tournament."
2. Select the tournament to which you want to add a player.
3. Follow the prompts to add players to the selected tournament.

## Create Match Schedule

1. After adding players to the tournament, choose "Create Match Schedule for current round."
2. The program will generate match schedules for the current round.

## Update Match Result

1. Once matches are played, select "Update Match Result" to record results.
2. You can update match results until all matches for the round are completed.
3. Repeat steps 6 and 7 for each round until the tournament is completed.

## Tournament Completion

1. To mark a tournament as completed, select "Tournament Completion."
2. This action will finalize the tournament, and certain options will become unavailable.

## Checking Completed Tournaments

1. After a tournament is completed, you can check its details with the following options:
   - List All Tournaments
   - Tournament Details
   - List All Player in Tournament
   - List of all completed rounds and matches of rounds
   - Get Score
   - View Tournament with Date

## Note

- Certain options, such as "Add Player in Tournament," "Create Match Schedule for current round," and "Update Match Result," become unavailable once a tournament is completed.

## PEP8 Compliance

The code of this program is PEP8 compliant, ensuring clean and consistent Python code style. Additionally, a Flake8 report is included to help maintain code quality.

## How to generate a flake8 repport

1. **Create a virtual environment**:
   - Open your command prompt or terminal
   - Navigate to the programme directory
   - Run the following command to create a virtual environment:
```
python -m venv yenv
```

2. **Install Requirement.txt**:
To install the packages listed in a `requirements.txt` file using `pip`, use the following command in your command prompt or terminal:
```
pip install -r requirements.txt
```

3. **Activate the Virtual Environment**:
   - On Windows:
     ```
     source env\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source env/bin/activate
     ```

4. **Save the Report to a File**:
   To save the Flake8 report to a file for later reference, use the following command:
   ```
   flake8 . > flake8_report.txt
   ```
   This command will save the report to a file named `flake8_report.txt` in the current directory.