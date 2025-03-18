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
body{
    font-family: 'Times New Roman', Times, serif;
    background-color: azure;
    margin: 40px;
    padding: 40px;
}

header{
    text-align: center;
    padding: 20px;
    background-color: rgb(160, 95, 151);
    color:rgb(5, 87, 180);
    border-radius: 60px;
}

h2{
    color: cadetblue;
}

ol{
    background-color: rgb(240, 237, 234);
    padding:20px;
    border-radius: 50px;
}

img{
    display: block;
    margin: 20px;
    border-radius: 60px;
}

table{
    width:100px;
    border-collapse: collapse;
    margin-top:10px;
    background-color: rgb(177, 153, 153);
}

th,td{
    border:1px;
    padding: 20px;
    text-align:left;
}

form{
    background: rgb(226, 224, 219);
    padding: 40px;
    border-radius: 70px;
    box-shadow:4px 4px 10px royalblue;
}

label{
    font-weight:bold;
    display:inline-block;
    margin-top: 20px;
}

input,select, button{
    width: 120px;
    padding: 8px;
    margin-top:2px;
    border: 10px;
    border-radius: 5px;
}

button{
    background-color: brown;
    color:blue;
    border:10px;
    font-size:smaller;
    cursor:pointer;
}

button:hover{
    background-color: aquamarine;
}
