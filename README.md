Assignment 4 | Akanshi Khandelwal | Media Queries
This project demonstrates the use of CSS Media Queries to create responsive web designs that adapt to different screen sizes. It showcases different screen sizes using text elements that change based on the width of the viewport.

Features:
A simple responsive layout that uses media queries to adjust the content for different screen sizes.
The content dynamically changes with different screen widths, displayed for four breakpoints: 1440px (Laptop Large), 1024px (Laptop), 768px (Tablet), and 425px (Mobile).
Technologies Used:
HTML: The structure of the webpage and content.
CSS: Media queries to adjust the layout based on different screen sizes. (styles.css)
Setup Instructions:
Clone the repository to your local machine:

bash

git clone https://github.com/your-username/assignment-4.git
Navigate to the project directory:

bash

cd assignment-4
Open the index.html file in your browser to view the project.

bash

open index.html  # macOS
start index.html  # Windows
xdg-open index.html  # Linux
If you make changes to the HTML, CSS, or add new assets, be sure to refresh your browser.

Folder Structure:
bash

assignment-4/
│
├── styles.css            # Main stylesheet for media queries and responsive design
└── index.html            # Main HTML file
Media Queries:
The page adapts to the following screen sizes:

1440px (Laptop Large): Displays the content for large screens.
1024px (Laptop): Adjusts for medium-sized laptop screens.
768px (Tablet): Adjusts for tablets or smaller laptop screens.
425px (Mobile): Adjusts for mobile screens.
Example of Media Queries:
css

/* Laptop Large (1440px and up) */
@media (min-width: 1440px) {
    .laptop_large { display: block; }
}

/* Laptop (1024px and up) */
@media (min-width: 1024px) {
    .laptop { display: block; }
}

/* Tablet (768px and up) */
@media (min-width: 768px) {
    .tablet { display: block; }
}

/* Mobile (425px and up) */
@media (min-width: 425px) {
    .mobile { display: block; }
}
Contributing:

Feel free to fork the repository, create a branch, and submit a pull request if you'd like to contribute improvements or suggestions.



