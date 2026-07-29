# Pixel Pizza - Form Styling Challenge

A custom order form for a fictional retro-arcade pizzeria. This project was built to demonstrate proficiency in styling complex HTML5 form elements while maintaining strict web accessibility standards and a clean user experience. The live deployment for this page can be found here [https://cryleafing.github.io/Pixel-Pizza/]

## Pixel Pizza - Form Challenge

**Objective:** Create a visually appealing and highly functional web form.

**Requirements:** Style a variety of input types—including text fields, email inputs, drop-down menus, radio buttons, and checkboxes. This ensures that the styling degrades gracefully and remains intuitive for the user.

## Implementation

Historically, styling form elements like radio buttons and checkboxes required complex CSS hacks. This project deliberately avoids those workarounds in favour of modern, semantic, and efficient CSS properties. Key features include:

* **Semantic Structure:** Extensive use of `<fieldset>`, `<legend>`, and explicitly linked `<label>` tags to ensure the form is fully accessible to screen readers and provides a larger click target for users.
* **Modern CSS Properties:** Utilising the `accent-color` property to instantly match the browser's default checkboxes and radio buttons to the brand's neon pink theme.
* **UX/UI States:** Implementing the `:focus` pseudo-class on all text and select inputs. This removes the default browser outline and replaces it with a brand-consistent border, providing the user with immediate visual feedback with which input is currently active.
* **Flexbox Layout:** Using `display: flex` with `flex-direction: column` to stack labels directly above their respective inputs, ensuring a readable vertical flow.

## Getting Started

This is a static HTML and CSS project. No build tools or package managers are required.

1. Clone or download this repository.
2. Open the project directory.
3. Open `index.html` in a standard web browser.

## Built With

* HTML5
* CSS3
* Google Fonts
