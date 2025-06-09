
YOUTUBE DEMONSTRATION LINK -> https://youtu.be/zr6ys9KrzWc

🎮 Java GUI Tic-Tac-Toe Game (With Scoreboard & Computer Mode)
This project is a visually styled and interactive Tic-Tac-Toe game created using Java Swing. It allows users to play:

🧍 vs 🧍 Two-Player Mode

🧍 vs 🤖 Computer Mode (with random move logic)

It includes round tracking, score calculation, and final result declaration — all wrapped in a clean, GUI-based experience.

🧩 Features
✅ 1. Game Modes
Two Player Mode: Two users can play locally, taking turns using the same interface.

Computer Mode: Play against the system. The computer selects its moves randomly from available options.


🧠 2. Turn-Based Logic
The game board alternates turns between:

X player (goes first)

O player (second player or computer)

Click-based turns are registered only on empty slots.

🎮 3. 3×3 Game Grid
The 9 buttons start labeled as "TIC", "TAC", or "TOE".

When clicked, these convert into X or O based on the current player.

Once a cell is used, it cannot be clicked again.

🧾 4. Player Input
Players are prompted to enter their names.

In computer mode, both the player and computer are named via JOptionPane.

🔁 5. Round Management
The game supports multiple rounds.

A label shows “Playing Round – N”.

After a win/draw, the user can click NEXT ROUND to continue.

📈 6. Score Tracking
Each player’s wins are counted and displayed live.

Win counts are updated after every round.

Scoreboard shows:

SCORE X : Player 1

SCORE O : Player 2 or Computer

🏆 7. Result Display
A text pane shows round outcome:

"X IS THE WINNER!"

"O IS THE WINNER!"

"THE GAME IS A DRAW"

After all rounds, the CALCULATE RESULTS button displays:

Overall winner across rounds

Or "THE GAME IS A DRAW" if equal scores

🚫 8. Button State Control
Used cells are disabled to prevent re-clicks.

Entire grid is disabled once a winner is found.

New round resets all grid buttons to default text and state.

🎨 9. GUI Design & Styling
Built using Java Swing with:

JFrame, JPanel, JButton, JTextPane, JOptionPane, etc.

Fonts used: Cooper Black, Algerian, Iskoola Pota, etc.

Colorful borders and layout formatting for aesthetics.


Built in NetBeans IDE (GUI Builder)

Uses java.util.Random for random move generation

Game logic handled through ActionListener methods

Computer logic handled in a method named computer()

💻 Requirements
Java JDK 8+

NetBeans IDE (recommended)

No external libraries required

🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/tictactoe-java.git
Open the project in NetBeans or your Java IDE.

Run TicTacToe.java.

Choose game mode and start playing!

✅ Summary
This game demonstrates:

Swing-based GUI programming
Interactive game design with input validation
Turn-based logic
Simple randomized computer opponent
Dynamic round and score tracking
Great for beginners learning Java GUI development and event-driven programming.
