# Java Notes App – File I/O

## Overview
This is a simple **console-based Notes Manager** built in Java.  
It allows you to:
1. Add new notes.
2. View saved notes.
3. Exit the application.

Notes are stored in a text file (`notes.txt`) so they are saved even after the program closes.

## Features
- Uses **FileWriter** (append mode) to write notes.
- Uses **BufferedReader** to read notes.
- Handles missing file gracefully.
- Works entirely in the terminal.

## Requirements
- Java Development Kit (JDK) installed.
- VS Code / Terminal to run.

## How to Run
1. Save the file as `NotesApp.java`.
2. Open terminal in the file's directory.
3. Compile:
   ```bash
   javac NotesApp.java
