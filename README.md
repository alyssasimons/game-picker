# game-picker

A website application that picks a random game for you when you're indecisive.
The top 100 most played games on Steam (as of 1/28/2024) are included, as well as others games from different launchers.


## Installation

Run this video game picker with a local server:

1. Clone the repository to your local machine.
    ```bash
    git clone https://github.com/alyssasimons/game-picker
    ```

2. Install the dependencies.
    ```bash
    cd game-picker
    npm i
    ```

3. Start the server.
    ```bash
    nodemon script.js
    ```

4. Open your web browser type [http://localhost:3000](http://localhost:3000) into the search bar to start receiving game suggestions.

## Dependencies

This project uses the following npm packages:

- [Express](https://www.npmjs.com/package/express)
- [EJS](https://www.npmjs.com/package/ejs)
- [body-parser](https://www.npmjs.com/package/body-parser)