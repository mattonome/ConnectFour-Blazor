# Connect Four — Blazor

A Connect Four game built with Blazor Web App (.NET 8) using Interactive Server render mode.

## Features
This application fulfills the base requirements of the Connect Four module and includes two additional features:
1. **Move History Panel**: Displays a live, numbered list of every move made during the current game (Player, Column, Row).
2. **Consecutive Win Tracker**: Tracks total wins across multiple games in the same browser session. If a player wins two or more games in a row, a "🔥 Win Streak!" banner appears. Win totals persist across game resets (managed via a singleton `GameState` service).

## How to Run
1. Ensure you have the .NET 8 SDK installed.
2. Open a terminal in the project directory.
3. Run `dotnet run`.
4. Open your browser to the URL provided in the console (e.g., `http://localhost:5239`).