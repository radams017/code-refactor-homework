# Horiseon Digital Services | Code Refactor
---

## Description

- The purpose of this project was to refactor the website HTML and CSS to improve accessibility and SEO.
- The website code functionality was, at its core, unchanged during this project.
- To improve accessibility, elements were adjusted and attributes were added to the existing code.
- Further description of the changes made are delineated below. 

## Index.html Adjustments

- Replaced various instances of the `<div>` element with semantic elements such as `<header>`, `<section>`, and `<footer>` to improve the site for SEO.
- Added `<a>` tags above each respective `<div>` in the container with the `content` class to allow functionality of the search bar options "Search Engine Optimization", "Online Reputation Management", and "Social Media Marketing".
- Spaced out the index to improve readability. 
- Added `alt` attributes to the images to improve accessibility. 
- Replaced `website` in the `<title>` tag with `Horiseon Digital Services`.
- Consolidated the `search-engine-optimization`, `online-reputation-management`, and `social-media-marketing` classes into one class named `content-box` for CSS consolidation. 
- Consolidated the `benefit-lead`, `benefit-brand`, and `benefit-cost` classes into one class named `benefit-box` for CSS consolidation.

## CSS Adjustments
- Consolidated the `search-engine-optimization`, `online-reputation-management`, and `social-media-marketing` selectors with the new `content-box` class in order to increase efficiency. 
- Consolidated the `benefit-lead`, `benefit-brand`, and `benefit-cost` selectors with the new `benefit-box` class in order to increase efficiency.

