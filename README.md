# Canva Calculator

Canva Calculator is an interactive web application that allows users to draw mathematical expressions on a canvas and automatically calculates the result of the expression. It combines a drawing canvas with color selection and MathJax rendering for mathematical equations.

## Features
- **Canvas Drawing**: Users can draw mathematical expressions on a canvas using a customizable brush with different colors.
- **MathJax Integration**: Automatically render and display mathematical expressions on the canvas.
- **Reset Functionality**: Clear the canvas and reset the state of the app with the "Reset" button.
- **Result Display**: Automatically calculate and display the result of the drawn expression using a backend service.

## Technologies Used
- **React**: For building the user interface.
- **Axios**: To send the drawn canvas data to the backend for processing.
- **MathJax**: To render mathematical expressions using LaTeX.
- **React-Draggable**: To allow users to move the result expression around on the canvas.
- **Mantine**: For UI components like color swatches and buttons.

## Installation

1. **Navigate to the project directory**:
    ```bash
    cd canva_calculator
    ```

2. **Install the dependencies**:
    ```bash
    npm install
    ```

3. **Run the development server**:
    ```bash
    npm start
    ```

4. Open your browser and go to [http://localhost:3000](http://localhost:3000).

## Usage

- **Draw on the Canvas**: Use your mouse to draw mathematical expressions on the canvas.
- **Select Color**: Click on one of the color swatches to change the drawing color.
- **Reset**: Click the "Reset" button to clear the canvas and reset the state.
- **Run Calculation**: Click the "Run" button to send the drawn expression to the server and calculate the result.
- **View Results**: The result will be displayed as a LaTeX expression that you can drag and move around.

## Dependencies

- **@mantine/core**: For UI components like color swatches and buttons.
- **react-draggable**: To enable dragging of LaTeX expressions.
- **axios**: For making API requests to the backend.
- **MathJax**: For rendering LaTeX expressions on the canvas.
