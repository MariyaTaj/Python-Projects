# Python Projects

### 1. Menstrual Cycle Predictor
This Python script predicts menstrual cycle phases, analyzes past cycle trends, and tracks menstrual symptoms. It provides an interactive interface for users to input past cycle data and current cycle information, generating predictions and visualizations accordingly.

**Features**
1. Predicts ovulation date and fertile window within the menstrual cycle.
2. Analyzes past menstrual cycle data to identify trends and regularity.
3. Allows users to input menstrual symptoms for each cycle.
4. Displays statistics and visualizations of past cycle lengths.
5. Provides an interactive interface for inputting current cycle information and generating predictions.

### 2. Dynamic Quiz Game
This Python script contains a dynamic quiz game. Users are prompted to play the game and, upon agreement, they answer a series of questions. Their responses are evaluated against predefined answers, and a final score is provided at the end.

**Usage**

1. Clone the repository:
```bash
git clone https://github.com/your-username/dynamic-quiz-game.git
```
2. Open the Jupyter Notebook `Dynamic Quiz Game.ipynb`.
3. Run each cell in the notebook to play the game.
4. Answer each question and see your final score.

### 3. NBA Stats Viewer
This Python script retrieves and displays NBA statistics and scores using data from the NBA website.

**Functionality**
 1. Scoreboard: Retrieves and displays the current scoreboard, including teams, scores, game clock, and period.
 2. Team Statistics: Retrieves and displays statistics for NBA teams, including points per game (PPG).

**Usage**

Dependencies: Ensure you have the required libraries installed. You can install them using pip install requests.

**Note**

The NBA stats URL used in this code (https://data.nba.net/prod/v1/today.json) may no longer be available due to changes in data agreements. Ensure the script is updated with the correct URL or alternative data sources if necessary.

### 4. Password Manager
This Python script serves as a basic password manager. It allows users to store and retrieve passwords securely using the Fernet encryption algorithm.

**Features**
Encryption: Passwords are encrypted using the Fernet symmetric encryption algorithm, ensuring security.
Master Password: Users are required to enter a master password to access stored passwords, adding an additional layer of security.
Add and View Passwords: Users can add new passwords or view existing ones.
Persistent Storage: Passwords are stored in a file (passwords.txt) and encrypted, allowing for persistence between sessions.

**How to Use**
1. Set Up: Before running the script, ensure you have the cryptography library installed (pip install cryptography).
2. Master Password: When prompted, enter your master password. This will be used along with the key to encrypt and decrypt passwords.
3. Options:
   view: View existing passwords stored in passwords.txt.
   add: Add a new password to the manager.
   q: Quit the program.

**Requirements**

- Jupyter Notebook
- Python 3.x
- pandas
- numpy
- matplotlib
