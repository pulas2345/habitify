# Habitify

**Habitify** is a super chill simple command-line habit tracker built in Python.

## What it does
- **Add** new habits to track  
- **List** all your habits  
- **Mark** a habit as done for today  
- **View** your history and streaks  

## How to run it

1. **Install dependencies**  
   ```bash
   pip install typer rich
2. **Run directly with Python**
python3 habitify.py add "Exercise"
python3 habitify.py done "Exercise"
python3 habitify.py list
python3 habitify.py history "Exercise"
3. **Or use the standalone binary**
./habitify add "Read"
./habitify done "Read"
./habitify list
./habitify history "Read"

## Dependencies / Requirements

Python 3.7 or higher
Typer
Rich
PyInstaller (only needed for building the Linux binary)

## Why I created it

I wanted a lightweight, terminal-based tool to quickly log daily habits and visualize my streaks without leaving the shell. Habitify is my on-the-fly solution for tracking and maintaining positive daily routines.
