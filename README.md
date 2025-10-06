# React Password Generator

A simple and intuitive web application built with React.js and Tailwind CSS that generates strong, random passwords based on user-defined criteria.

### [Live Demo]([<YAHAN_APNA_NETLIFY_LINK_DAALO](https://glittering-cajeta-9814b5.netlify.app/))

---

## Features

- **Customizable Length:** Generate passwords of any length between 6 and 50 characters using a range slider.
- **Character Options:** Include or exclude numbers and special characters with simple checkboxes.
- **Instant Generation:** The password updates in real-time as you change the options.
- **One-Click Copy:** A convenient "Copy" button to copy the generated password to the clipboard.
- **Responsive Design:** A clean and modern UI that works perfectly on all screen sizes.

---

## Core Concepts & Hooks Implemented

This project was a deep dive into some of the most fundamental hooks in React:

- **`useState`:** For managing multiple states like password length, character options, and the final generated password.
- **`useEffect`:** To trigger the password generation function whenever the dependencies (length, numbers, characters) change.
- **`useCallback`:** To memoize the password generation function for performance optimization.
- **`useRef`:** To get a direct reference to the password input field for the "copy to clipboard" functionality.
