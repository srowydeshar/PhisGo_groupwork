# PhisGo

PhisGo is a game-based cybersecurity awareness project developed for CSCI 4830.

The goal of PhisGo is to teach players how to recognize phishing attacks and other cybersecurity threats through an interactive game experience.

## Project Goals

- Teach players how to identify phishing attempts
- Provide realistic but educational phishing scenarios
- Use game mechanics to make cybersecurity awareness engaging
- Track player progress, scores, and decisions
- Provide explanations after player decisions

## Technology Stack

| Technology | Purpose |
|---|---|
| HTML | Web page structure |
| CSS | Web page styling |
| JavaScript | Frontend interactions |
| Flask | Backend, API, authentication |
| SQLite / SQL | Database |
| Unity | 3D game and gameplay |
| C# | Unity scripting |
| GitHub | Version control and team collaboration |

## Project Architecture

```text
                    PHISGO
                       |
          ┌────────────┴────────────┐
          |                         |
     Web Frontend              Unity Game
     HTML/CSS/JS                 C# / Unity
          |                         |
          └────────────┬────────────┘
                       |
                    Flask API
                       |
                    SQLite
