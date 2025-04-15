# Simon-Says
This is a simple Simon Says-like game built in the Godot Engine. The game features three colored buttons that light up and play sounds in a random sequence. Players must watch and memorize the sequence, then repeat it by clicking the buttons in the correct order. The sequence gets longer with each round.
## Features
- Three interactive colored buttons (e.g., Red, Green, Blue)
- Buttons light and play sounds when activated
- A random sequence generator that:
  * Pciks random button presses
  * Prevents any single button from repeating more than three times in a row
- Player input system to validate the sequence
- Basic UI system:
  * Start, Restart, and Quit Buttons
  * Pause Menu with Restart and Quit
- Feedback for correct and incorrect sequences
## Gameplay
1. Click Start to begin the game
2. The game plays a random sequence of button lights and sounds
3. Repeat the sequence by clicking the buttons in the correct order
4. If incorrect, game is restarted to initial state
5. If correct, score increases by one and the sequence grows longer each round
6. Use the Restart button to reset the game at any time, or Quit to exit
