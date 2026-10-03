# flexbox
Flex Box Layout

A simple HTML and CSS project demonstrating a webpage layout using CSS Flexbox.

📌 Project Overview

This project creates a basic webpage structure consisting of:

Header

Left sidebar

Main content area

Top and bottom sections

Two columns inside the bottom section

Footer

The layout is created using HTML elements and CSS properties such as display: flex, width, height, and background-color.

🛠️ Technologies Used

HTML5

CSS3

CSS Flexbox

📂 Project Structure
Flex-Box/
│
├── index.html
└── README.md

🎨 Layout Structure

The page follows this structure:

+---------------------------------------+
|               HEADER                  |
|               (Teal)                  |
+----------+----------------------------+
|          |            TOP             |
|   LEFT   |           (Brown)          |
| (Orange) +----------------------------+
|          |   BOTTOM  |   BOTTOM      |
|          |  1        |      2        |
|          | (Chocolate)| (Goldenrod)  |
+----------+------------+---------------+
|               FOOTER                  |
|               (Teal)                  |
+---------------------------------------+

📐 CSS Layout
Container

The main container has a height of 600px and a black border.

.con {
    height: 600px;
    border: 1px solid black;
}

Header and Footer

The header and footer each occupy 20% of the container height.

.header, .footer {
    height: 20%;
    background-color: teal;
}

Center Section

The center section occupies 60% of the container and uses Flexbox.

.center {
    height: 60%;
    background-color: beige;
    display: flex;
}

Left and Right Sections

The left section takes 20% of the available width, while the right section takes 80%.

.left {
    height: 100%;
    background-color: orange;
    width: 20%;
}

.right {
    height: 100%;
    background-color: orangered;
    width: 80%;
}

Top and Bottom Sections

The right section is divided vertically into two equal parts.

.top {
    height: 50%;
    background-color: brown;
}

.bottom {
    height: 50%;
    background-color: red;
    display: flex;
}

Bottom Columns

The bottom section is divided horizontally into two equal columns.

.bottom1 {
    height: 100%;
    width: 50%;
    background-color: chocolate;
}

.bottom2 {
    height: 100%;
    width: 50%;
    background-color: goldenrod;
}

🚀 How to Run

Create a file named index.html.

Add the HTML and CSS code to the file.

Save the file.

Open index.html in any modern web browser.

No additional libraries or installations are required.

📚 Concepts Demonstrated

This project is useful for learning:

HTML document structure

CSS selectors

CSS box model

display: flex

Flexbox-based layouts

Percentage-based widths and heights

Nested HTML elements

Background colors

Basic webpage layout design

🎯 Purpose

The main purpose of this project is to practice creating a structured webpage layout using CSS Flexbox and understand how nested flex containers can be used to divide a page into different sections.

👨‍💻 Author

Created as a basic HTML & CSS Flexbox practice project.
