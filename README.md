# Candy-Crush
A JavaScript-based Candy Crush-style game with draggable candies, match detection, and an automatic refill mechanism.

🎮 Features
Drag & Swap: Players can swap adjacent candies.
Match Detection: Identifies three or more matching candies and removes them.
Gravity Effect: Remaining candies slide down, and new ones appear at the top.
Scoring System: Earn 30 points per match.
Sound Effects & Music: Background music plays on load, and a match sound effect is triggered on a valid move.
🛠️ How It Works
Game Initialization

Generates a 9x9 grid filled with random candies.
Candies are <img> elements with unique IDs (e.g., "0-0").
Drag & Drop Logic

Players drag and drop candies to swap them.
If the move results in a match, candies are removed.
Match Handling & Scoring

crushThree() detects matching candies and replaces them with blank tiles.
Score increases dynamically (score += 30).
Gravity & Refill Mechanism

Sliding effect moves candies down to fill gaps.
New random candies generate at the top.
Game Loop (Runs every 100ms)

crushCandy(): Removes matches.
slideCandy(): Moves candies downward.
generateCandy(): Spawns new candies.
📂 File Structure
index.html → Main game interface.
style.css → Styling.
script.js → Game logic.
🚀 How to Play
Open index.html in a browser.
Drag and swap candies to create matches.
Earn points and keep playing as new candies appear!
🔥 Future Enhancements
Power-ups (e.g., Bombs, Color Bombs).
Timed Mode & Levels.
Mobile Support.
Perfect for beginners in JavaScript looking to learn DOM manipulation and game logic! 🎯
