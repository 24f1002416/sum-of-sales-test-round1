# sum-of-sales-test

## Summary
Publish a single-page site that fetches data.csv from attachments, sums its sales column, sets the title to 'Sales Summary Test', displays the total inside #total-sales, and loads Bootstrap 5 from jsdelivr.

## Setup
This is a static web application. No build step required.

## Usage
1. Clone the repository
2. Open `index.html` in a web browser
3. Or deploy to GitHub Pages for online access

## Code Explanation
This application implements the following features:
- document.title === 'Sales Summary Test'
- !!document.querySelector("link[href*='bootstrap']")
- Page has #total-sales element

## License
MIT License - See LICENSE file for details
