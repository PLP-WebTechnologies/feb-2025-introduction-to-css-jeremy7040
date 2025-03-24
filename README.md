# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨






body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
}

#main {
    background: #fff;
    padding: 20px;
    margin-top: 20px;
    border: 1px solid #ddd;
}

.card {
    background: #f9f9f9;
    border: 1px solid #ddd;
    padding: 20px;
    margin-bottom: 20px;
}

.card img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 0 auto 10px;
}

.card h2 {
    margin: 0 0 10px;
}

.card p {
    color: #666;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}
