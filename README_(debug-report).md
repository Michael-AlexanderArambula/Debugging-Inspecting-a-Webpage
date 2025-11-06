# Debugging-Inspecting-a-Webpage

Broken Code Issues

CSS:

background-colr | Typo (colr --> color)

border: 5px solid blackk; | Typo (blackk --> black)

.box has border-radius: 20%;; | Double semicolon

.hidden { display: non; } | Typo (non --> none)

JS:

colorButton.addEventListener("click", () => {
    bx.style.backgroundColor = "blue"; 
  });

  Error: Typo - should be "box", not "bx"

  console.log("Page loaded!" 
});

Error: Missing parenthesis for console.log()
