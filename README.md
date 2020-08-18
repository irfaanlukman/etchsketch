DESCRIPTION:

In this simple project, we are required to combine the fundamentals of Javascript, HTML and CSS to create a web-browser Etch-a-Sketch application. It is a simple application involving basic concepts involving all 3 languages to further enhance knowledge and understanding.

What I learned:

1. A new concept of setting up CSS classes to be called back later on Javascript. More instances of integrating both languages and caling upon when necessary.

2. More practice on CSS grids and building grid template rows and columns and the ability to manipulate them later on Javascript. 
    For example: Creating a function on js, to alter the grid elements to user input.
    
    updateGrid = () => {
    grid.innerHTML = "";
    grid.style.setProperty(
    "grid-template-columns", `repeat(${userInput.value}, 2fr)`
    );
    grid.style.setProperty(
    "grid-template-rows", `repeat(${userInput.value}, 2fr)`
    );

3. More practice with Javascript for example creating for loops to:
    - createGrid
    - updateGrid that implements user input to build and append as many squares needed to fill in grid rows and columns.

4. More practice with addEventlisteners including mouseover functions and calling back a change of css class.
