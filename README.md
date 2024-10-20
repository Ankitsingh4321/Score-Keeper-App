# Score Keeper App

A simple web-based scorekeeper application built with React. This app allows users to track the score and wickets of a cricket game. Users can add runs, wickets, and reset the score with ease.


## Features

- **Track Scores**: Add runs (0, 1, 2, 3, 4, 5, 6) to the current score.
- **Track Wickets**: Add wickets to track the number of outs in the game.
- **Ball-by-Ball Result Display**: View results of each ball in the current session.
- **Delete Last Ball**: Undo the most recent ball result.
- **Reset Game**: Reset the score, wickets, and ball-by-ball results to start a new game.
## Demo




## Technologies Used

- React (with UMD CDN)
- HTML5
- CSS3
- Babel Standalone (for JSX support)

## Getting Started

You can use this project by simply opening the index.html file in any modern web browser.

## Prerequisites

You don't need to install any packages or dependencies as the app runs entirely in the browser using React via CDN.


## Running the project

1. Download the project or clone this repository:

```bash
  git clone https://github.com/Ankitsingh4321/Score-Keeper-App.git
```

2. Open the **index.html** file in any modern browser (e.g., Chrome, Firefox).


## Code Explanation

## Components

ScoreButtons

This component renders all the buttons for scoring and wicket tracking, as well as the reset functionality. It includes:

* Buttons for adding runs (0, 1, 2, 3, 4, 5, 6)
* A button for adding a wicket (W)
* A button to delete the last ball result
* A button to reset the game (Reset)

## State Management

* Score and Wicket tracking is managed through global variables and updated with each button click.

* Ball-wise results are stored in the ballWiseRes array, which allows for displaying the history of ball results.

## License

This project is open-source and available under the MIT License.

---

Feel free to adjust the content and sections as per your project's specific needs.

