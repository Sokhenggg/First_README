# Rock-Paper-Scissors(RPS)Game with PostgreSQL Database
This is a simple Rock-Paper-Scissors(RPS)game implemented in Python. It allows players to play the classic game against a computer opponent. The game keeps track of the player's wins and losses using a PostgreSQL database. Player's names and ages are used to uniquely identify them in database.
## Prerequisites

1. Python 3.x
2. PostgreSQL database server installed and running
3. `psycopg2` library installed (`pip install psycopg2`)
## Setup
1. Install the required libraries using the following command:
2. Set Up your PostgreSQL database with the following connection details:
- Database name: posgres
- User: posgres
- Password: heng
- Host: localhost
- Port: 5432

## Database Structure

The game uses a PostgreSQL database to store player information and scores. The database has a single table named `scores` with the following columns:
- `name` (VARCHAR): Player's name
- `age` (INTEGER): Player's age
- `wins` (INTEGER): Number of wins
- `losses` (INTEGER): Number of losses

## Code Description

The Python script `rps_game.py` connects to the PostgreSQL database, gets player information, plays the RPS game, updates scores, and handles the game loop.

## Acknowledgments

This code was created for educational purposes and is a simple demonstration of using PostgreSQL with Python for a game application.

## Contact

For more details, contact me via sokheng.soeng22@kit.edu.kh


