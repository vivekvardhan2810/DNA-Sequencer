# DNA Sequencer Game

The DNA Sequencer Game challenges players to correctly arrange a randomized DNA sequence using drag-and-drop functionality. The goal is to match the sequence to a target sequence within an allotted time.

## Features
- Drag-and-drop DNA bases (A, T, C, G) to arrange them in the correct order.
- Shuffle the sequence if you want to try a different random arrangement.
- A timer adds urgency, giving players a limited time to complete the task.

## Technologies Used
- **HTML**: Structure of the game.
- **CSS**: Styling the game elements.
- **JavaScript**: Game logic, drag-and-drop functionality, timer, and sequence checking.
- **JSON**: Storing the target DNA sequence.

## How to Play
1. Clone or download this repository to your local machine.
2. Open the `index.html` file in your preferred web browser.
3. The target sequence is displayed at the top. Drag and drop the DNA bases in the random sequence to match the target sequence.
4. Use the "Shuffle" button to randomize the sequence again if needed.
5. Complete the arrangement within the time limit (60 seconds) to win!

## Files
- `index.html`: The main HTML file containing the structure of the game.
- `styles.css`: The CSS file for styling the game elements.
- `script.js`: The JavaScript file containing the game logic and drag-and-drop functionality.
- `data.json`: A JSON file storing the target DNA sequence.

## Customization
- Modify the `targetSequence` array in the `data.json` or `script.js` file to create different sequences.
- Adjust the timer duration in the `script.js` file by changing the initial `timer` value.

## Future Enhancements
- Add more complex sequences with more DNA bases.
- Include different levels of difficulty.
- Implement scoring based on the time taken to complete the sequence.

## Example

![image](https://github.com/user-attachments/assets/3ee63f81-33a7-4ad3-afcf-b2d8da39d593)

## License
This project is open-source and available under the MIT License.
