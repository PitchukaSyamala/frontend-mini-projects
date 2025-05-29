# frontend-mini-project
🧩 Project: Pokémon Selector
This is a mini React.js project that fetches and displays data from the PokéAPI based on the selected Pokémon number. It uses React hooks (useState, useEffect) and Axios for making API calls.

🚀 Features
Dropdown to select a Pokémon by its number (1 to 10).

Displays:

The Pokémon number you selected.

The Pokémon's name fetched from the API.

The number of moves that Pokémon can perform.

⚙️ Tech Stack
React.js

Axios (for HTTP requests)

PokéAPI (for data)

🧠 How It Works (Code Explanation)
useState is used to track:

num: The selected Pokémon number.

name: The name of the Pokémon.

moves: The total number of moves the Pokémon can perform.

useEffect runs every time the component renders, fetching data from https://pokeapi.co/api/v2/pokemon/${num} based on the selected number.

The <select> dropdown allows you to choose a number between 1 and 10.

Upon selection, it fetches:

The name of the Pokémon.

The number of moves.

These are then displayed in the UI using <h1> elements, with the selected data highlighted in red.

