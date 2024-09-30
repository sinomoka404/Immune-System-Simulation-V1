# Immune-System-Simulation-V1
This is a little python project that took me a pretty long time to make

Description: The Immune System Simulation is an educational and interactive game designed to simulate the human immune response to various pathogens. Players manage the health of a virtual human host by responding to pathogen introductions and making strategic decisions to maintain and restore health. The game offers a unique blend of strategy and education, providing insights into immune system dynamics and pathogen management.

Features:

Pathogen Management:

Dynamic Pathogen Introduction: Pathogens are introduced at random intervals, varying from every 10 seconds to 1 hour, depending on their rarity.
Variety of Pathogens: A diverse list of diseases ranging from common to extremely rare, each with unique probabilities of appearance and damage rates.
Immune Response:

Immune Cells: Manage a limited number of immune cells that can be used to remove pathogens from the host.
Loading Bar: An ASCII loading bar visualizes the process of pathogen removal, with duration based on pathogen severity.
Human Vitals:

Vitals Management: Human vitals decrease over time as pathogens inflict damage. Vitals can recover through medication or gradual healing.
Medication: A 65% chance for medication to be taken after pathogen removal, which helps in faster healing of the human host.
Difficulty Levels:

Adjustable Difficulty: Players can choose between Easy, Normal, and Hard difficulty settings, affecting the challenge and frequency of pathogen introductions.
Interactive Menu:

Menu Screen: Options to start the game, view help, adjust difficulty, and exit the program.
Help Section: Provides detailed instructions on how to play the game.
Command System:

Commands: Input commands to remove pathogens, display current pathogens, list available diseases, and heal the human host.
Real-Time Feedback: Immediate feedback on actions taken, including the status of pathogens and human vitals.
How to Play:

Starting the Game:

Launch the game and navigate to the menu screen.
Select "Play" to start the simulation or choose "Help" to learn more about the game mechanics.
Managing Pathogens:

Pathogens will appear at random intervals. Monitor the list of pathogens and respond by removing them when necessary.
Use the remove command to choose which pathogen to remove from the list.
Handling Human Vitals:

Watch the vitals of the human host decrease as pathogens cause damage. Use the heal command to manage health recovery.
After removing pathogens, there is a chance for medication to be taken, which speeds up recovery. If no medication is taken, healing occurs gradually.
Adjusting Difficulty:

Use the difficulty option in the menu to select the level of challenge. The difficulty affects how frequently pathogens are introduced and their impact.
Navigating Commands:

Use commands to interact with the game, including display to view current pathogens, list to see available diseases, and exit to end the simulation.

Essential Dependencies:
Python Standard Library:
random: For introducing pathogens at random intervals.
time: For handling delays (e.g., pathogen removal, healing processes).
threading: To manage multiple processes, such as pathogens being introduced while interacting with the command center.
sys: For interacting with the console and capturing inputs.
