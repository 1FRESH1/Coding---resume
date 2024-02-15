# Sticky Header Tests

## I. Description

This project contains unit tests for the functionality responsible for the behavior of the sticky header on a web page.

## II. Table of Contents

III. **Project Structure**

IV. **Tests**

V. **Running Tests**

VI. **Requirements**

VII. **Author**

## III. Project Structure

- `script.js`: File containing functions handling the behavior of the sticky header.
- `styles.css`: Stylesheet for the web page.
- `index.html`: Web page containing sample header and scrollable content.
- `tests.js`: File containing unit tests for the sticky header functionality.

## IV. Tests

1. Header should have sticky class when scrolling down: 
    - Checks if the header receives the "sticky" class when scrolling down.

2. Header should not have sticky class when scrolling up: 
    - Checks if the header loses the "sticky" class when scrolling up.

3. Header should become sticky after scrolling past its offset: 
    - Checks if the header receives the "sticky" class after scrolling down past a specified header offset.

4. Header should lose sticky class when scrolling above its offset: 
    - Checks if the header loses the "sticky" class when scrolling up above a specified header offset.

## V. Running Tests

To run the tests, open the `tests.html` file in a web browser and check the developer console.

## VI. Requirements

Web browser with support for the QUnit unit testing tool.

## VII. Author

This project was created by Grzegorz Skalski.

---