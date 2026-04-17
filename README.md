# 🍔 Happy Tummy Restaurant Website

A polished, fully responsive single-page restaurant website for **Happy Tummy**, a cozy fast-food spot in **West Rampura, Dhaka**. The project was built to present the restaurant's menu, brand story, location, and ordering options in a clean, modern layout that works well both as a live product and as a portfolio piece.

## Live Demo

- Vercel: https://happytummybd.vercel.app

## Repository

- GitHub: git@github.com:Maruf-ahmed-07/Resturant-HappyTummy-Website.git

## Features

- Single-page navigation with smooth section switching for Home, Menu, and About.
- Fully responsive layout that adapts well across mobile, tablet, and desktop screens.
- Dynamic menu rendering powered by a JavaScript data array, making future updates simple.
- Sticky category navigation for quick browsing through the menu sections.
- Modern visual styling with Tailwind CSS, Google Fonts, and Lucide icons.
- Direct links to Foodpanda, Google Maps, and the restaurant's social presence.
- Portfolio-friendly presentation that shows both design and front-end structure clearly.

## Technologies Used

- HTML5 for semantic structure.
- Tailwind CSS via CDN for styling and responsive layout.
- Vanilla JavaScript for navigation, menu rendering, and interactive behavior.
- Lucide Icons for lightweight SVG icons.
- Google Fonts for the Poppins and Playfair Display type pairing.

## How to Run

This project does not require a build step or package installation.

1. Clone or download the repository.
2. Open `index.html` in any modern browser.
3. Make sure you have an internet connection so external assets such as Tailwind, fonts, icons, and images can load properly.

## Project Structure

The application is self-contained inside `index.html`.

- `head`: meta tags, CDN links, fonts, icons, and custom styles.
- `nav`: the sticky top navigation with desktop and mobile actions.
- `main`: the Home, Menu, and About sections.
- `footer`: social links and copyright information.
- `script`: icon initialization, SPA navigation, and menu rendering logic.

## Updating the Menu

To update the menu, edit the `menuData` array inside the `<script>` section near the bottom of `index.html`.

Each menu item can be updated directly in the data object:

```js
{
	name: "New Item Name",
	price: 150,
	desc: "Description of the item",
	img: "https://url-to-your-image.jpg"
}
```

The page will automatically render the new content in the correct section.

## Contact Information

- Address: 211/C, Ulon Road, West Rampura, Dhaka, Bangladesh, 1219
- Phone: 01719-185428
- Email: happytummy041019@gmail.com
- Order Online: [Foodpanda](https://www.foodpanda.com.bd/restaurant/t3ny/happy-tummy?utm_source=google&utm_medium=organic&utm_campaign=google_reserve_place_order_action)

