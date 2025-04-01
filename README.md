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
/* Apply styles to the entire page */
body {
    font-family: 'Verdana', sans-serif;
    background-color: #f2f2f2;
    margin: 0;
    padding: 20px;
    text-align: center;
}

/* Style the title */
.title {
    color: #4CAF50;
    font-family: 'Arial', sans-serif;
    text-align: center;
    padding: 15px;
    font-size: 24px;
    text-transform: uppercase;
    border-bottom: 3px solid #4CAF50;
    margin-bottom: 20px;
}

/* Style the description paragraph */
#description {
    font-size: 18px;
    color: #333;
    margin: 25px auto;
    padding: 15px;
    border: 2px solid #ddd;
    background-color: #f9f9f9;
    line-height: 1.6;
    border-radius: 5px;
    width: 80%;
    text-align: left;
}

/* Style the image */
.styled-image {
    display: block;
    margin: 30px auto;
    border-radius: 15px;
    border: 4px solid #4CAF50;
    width: 60%;
    max-width: 600px;
    box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.1);
}

/* Button styling */
.button {
    display: inline-block;
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    text-align: center;
    text-decoration: none;
    font-size: 16px;
    margin: 10px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.button:hover {
    background-color: #45a049;
}

/* Additional spacing and layout improvements */
.container {
    width: 80%;
    margin: 0 auto;
}

/* Input form styling */
form {
    background: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
    width: 50%;
    margin: 20px auto;
    text-align: left;
}

input, select, textarea {
    width: 100%;
    padding: 10px;
    margin: 8px 0;
    display: block;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
}

input[type="submit"] {
    background-color: #4CAF50;
    color: white;
    border: none;
    padding: 10px 15px;
    cursor: pointer;
    font-size: 16px;
}

input[type="submit"]:hover {
    background-color: #45a049;
}

