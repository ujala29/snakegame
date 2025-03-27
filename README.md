# Snake Game

## Installation

To run the Snake Game, you'll need to have a web server set up on your local machine. You can use a simple HTTP server like Python's built-in `http.server` module or a more advanced server like Node.js with Express.

1. Clone the repository:
```
git clone https://github.com/your-username/snake-game.git
```
2. Navigate to the project directory:
```
cd snake-game
```
3. Start the web server:
```
python -m http.server 8000
```
4. Open your web browser and go to `http://localhost:8000` to play the game.

## Usage

The objective of the game is to control the snake and make it eat the food. The snake grows longer as it eats the food, and the game ends when the snake collides with itself or the walls.

- Use the arrow keys to control the direction of the snake.
- The score is displayed in the top-right corner of the screen.
- The high score is also displayed in the top-right corner.

## API

The game uses the following APIs:

- `requestAnimationFrame()`: This API is used to create a smooth animation loop for the game.
- `localStorage`: This API is used to store the high score.

## Contributing

If you'd like to contribute to the Snake Game project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test them thoroughly.
4. Submit a pull request with a detailed description of your changes.

## License

This project is licensed under the [MIT License](LICENSE).

## Testing

To run the tests for the Snake Game, you'll need to have a testing framework set up. You can use a tool like Jest or Mocha.

1. Install the testing framework:
```
npm install --save-dev jest
```
2. Create a new file called `test.js` in the project directory.
3. Write your test cases in the `test.js` file.
4. Run the tests:
```
npx jest
```
