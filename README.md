# 🏆 Sports League Management System

A MongoDB-based platform designed to manage teams, players, and matches across multiple sports.  
Developed as part of the **CSAI 410 – Advanced Database Systems** course.

## 📌 Project Overview

This project delivers a sports league database system that enables real-time data access, performance analysis, and operational management.  
The system supports professional and amateur sports such as:

- ⚽ Soccer
- 🏀 Basketball
- 🏊 Swimming
- 🎾 Tennis

## 🧱 Key Features

- 📂 **Collections** for players, teams, and matches in different sports
- 🔍 **Analytical Queries** for top performers, win ratios, and stadium statistics
- 🎯 **Performance Metrics**: Player goals, assists, points, and ratings
- 📊 **Team Stats**: Total wins, losses, and league points
- 🖥️ **Graphical User Interface** for real-time interaction with the database

## 🛠️ Technologies Used

- **MongoDB** – NoSQL document-oriented database
- **Mongo Shell** – For CRUD and aggregation queries
- **Python/JavaScript (GUI layer - optional)** – For interfacing with the database (if implemented)

## 🧩 Collections Overview

| Collection           | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| `SoccerPlayers`      | Names, roles (e.g., Defender), goals, assists, teams                        |
| `BasketBallPlayers`  | Names, positions, points scored, assists, teams                             |
| `SinglePlayers`      | Individual athletes (swimmers/tennis), matches played, points, ratings      |
| `SoccerMatches`      | Competing teams, scores, stadiums, referees, attendance                     |
| `BasketBallMatches`  | Match results, venues, audience stats                                       |
| `SingleMatches`      | Tennis/swimming matches and scores                                          |
| `Teams`              | Team details, player rosters, win/loss stats, and accumulated points        |

## 🔍 Sample Queries

- Get defenders with more than 5 assists
- Find top goal scorers in football
- Retrieve players by team or match date
- Group matches by stadium or team
- Calculate average attendance
- Insert/update players (e.g., Lionel Messi assist count)
- Find tennis players with top performance ratings

## 💻 GUI Features (if implemented)

- Filter players by sport/team
- View match statistics and leaderboards
- Insert/update player information
- Query league trends with real-time feedback

## 🧠 Use Cases

- Coaches and analysts tracking player performance
- League managers organizing fixtures and scoring
- Fans accessing team/player statistics
- Sports analytics teams generating insights

## 📜 License

This project is developed for academic and educational purposes.

---

Let me know if you want a `.md` version or if you'd like to expand this into a web dashboard or API!
