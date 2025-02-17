# Pacman-XDOMRA00

Pacman-XDOMRA00 is a Java-based implementation of the classic Pacman game. This project is built using Java 17 and Maven, featuring a structured and modular codebase.

## Team Members:
- **Danil Domrachev** (xdomra00)
- **Dinara Garipova** (xgarip00)

## Requirements:
To build and run this project, you need:
- **Java 17**
- **Apache Maven**

## Project Structure:
```bash
Pacman-XDOMRA00/
├── data/                 # Game data including logs and maps
│   ├── log/              # Log files
│   │   └── log.txt
│   ├── maps/             # Game maps
│       ├── mapa1.txt
│       ├── mapa2.txt
│       ├── mapa3.txt
│       ├── mapa4.txt
│       ├── mapa5.txt
│       ├── mapa6.txt
│       ├── mapa7.txt
│       ├── mapa8.txt
├── lib/                  # Resources (backgrounds, icons, sounds, sprites)
├── src/                  # Source code
│   ├── custom/           # Custom UI components
│   │   ├── CustomDefaultJbutton.java
│   │   ├── CustomJpanelBackground.java
│   ├── frames/           # Game UI frames
│   │   ├── GamePanel.java
│   │   ├── MainFrame.java
│   │   ├── MenuPanel.java
│   │   ├── OpenableFrame.java
│   │   ├── PickMapPanel.java
│   │   ├── ReplayPanel.java
│   ├── logic/            # Game logic
│   │   ├── common/       # Common game utilities
│   │   │   ├── Field.java
│   │   │   ├── Maze.java
│   │   │   ├── MazeObject.java
│   │   ├── game/         # Game mechanics and AI
│   │       ├── BFS.java
│   │       ├── FieldClass.java
│   │       ├── GameLogger.java
│   │       ├── GhostObject.java
│   │       ├── KeyObject.java
│   │       ├── MazeClass.java
│   │       ├── MazeConfigure.java
│   │       ├── MazeObjectClass.java
│   │       ├── PacmanObject.java
│   │       ├── PathField.java
│   │       ├── PointObject.java
│   │       ├── TargetObject.java
│   │       ├── WallField.java
├── out/                  # Compiled output
│   ├── visual/
│       ├── Main.java
├── target/               # Compiled JAR and documentation
├── pom.xml               # Maven build configuration
├── readme.txt            # Additional documentation

```
## How to Build and Run

### 1. Clone the Repository
```sh
git clone https://github.com/yourusername/Pacman-XDOMRA00.git
cd Pacman-XDOMRA00
```
### 2. Build the Project
Use Maven to package the project:
```sh
mvn package
```
### 3. Run the Game
After building, navigate to the target folder and execute:
```sh
java -jar xdomra00-1.0.0.jar
```
###4. Running from a Custom Directory
If you want to run the application from another location:

- Copy the data and lib folders from Pacman-XDOMRA00 to your new directory.
- Create a subdirectory (e.g., bin) inside your chosen location.
- Move the xdomra00-1.0.0.jar file into the bin folder.
- Run the JAR file as described above.
Example:

```sh
D:/Pacman/
│── data/
│── lib/
│── bin/
    └── xdomra00-1.0.0.jar
```
### 5. View the Documentation
After building the project, you can access the generated documentation:

- Navigate to target/site/apidocs
- Open index.html in a web browser

## **Features**
- Classic Pacman gameplay
- Maze navigation and AI-driven ghosts
- Customizable maps and assets
- Java-based rendering and UI components
- Logging system for tracking gameplay
  
## License
This project is developed for educational purposes.

