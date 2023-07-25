# Fighters-Voting-Database

![image](https://github.com/JorgeCJ/Fighters-Voting-Database/assets/127647774/370db28a-5461-41c9-8969-330003ea7676)

This is a database for voting the best fighters using PostgreSQL.You can choose the best male and the female fighter. Each user must choose only one from each category. Let's start by looking at the "VoteMale" and "VoteFemale" tables. The "likes" field, present in both tables, serves to store the like value. If a certain fighter receives a like, the value will be 1. Otherwise, it will be 0. The "liked" field, also present in each of these two tables, is a boolean and serves to keep the fighter as true if it is clicked once, and false if it is clicked again.

## Technologies used:
- [PostgreSQL](https://www.postgresql.org/)
