✊✋✌️ Rock-Paper-Scissors: Java Implementation

A refined terminal-based game engine that brings the classic Rock-Paper-Scissors experience to the command line with a focus on visual feedback and logic optimization.

1. Technical Highlights:
- **AI Decision Engine:** `java.util.Random` to generate unpredictable computer moves based on array-index mapping.
- **Visual Rendering:** ASCII art switch-case logic that translates string inputs into graphical terminal output (the art is extracted from web).
- **Input Resilience:** Implements defensive programming through `equalsIgnoreCase()` and conditional loops to prevent runtime crashes from user typos.
- **Optimized Logic:** Replaces nested if-else structures with compound boolean expressions for cleaner, more maintainable code.

2. Programming Concepts Used:
- **Control Flow:** `do-while` game loops for continuous playability.
- **Data Structures:** String arrays for move sets.
- **Methods:** Modularized code with specific functions for UI display and ASCII art rendering.

3. Gameplay Preview:
- Input your move: `rock`, `paper`, or `scissor`.-
-  View the visual battle through terminal-rendered hand signals.
- Compare results and choose to play again instantly.
