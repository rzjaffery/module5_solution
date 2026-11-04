# David Chu's China Bistro

This project is a responsive restaurant website for David Chu's China Bistro. It presents restaurant information, menu categories, menu items, delivery details, business hours, and a location map.

## Features

- Responsive layout for desktop, tablet, and mobile screens
- Restaurant home page with featured sections
- Dynamic menu categories and menu items loaded from Firebase
- Reusable HTML snippets for menu content
- Restaurant images and menu item photos
- Contact phone number, hours, address, and Google Maps location

## Technologies

- HTML5
- CSS3
- JavaScript
- jQuery
- Bootstrap
- Firebase Realtime Database

## Project Structure

```text
index.html           Main page
css/                 Bootstrap and project styles
js/                  JavaScript and AJAX utilities
snippets/            Reusable HTML templates
images/              Restaurant and menu images
fonts/               Bootstrap icon fonts
```

## Running the Project

Because the site loads HTML snippets and menu data with AJAX, open it through a local web server rather than directly from the file system.

For example, from the project directory:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in a browser.

## Data Source

Menu categories and menu items are retrieved from the Coursera JHU Firebase Realtime Database configured in `js/script.js`.
