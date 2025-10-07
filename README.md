# React Password Generator

A simple and intuitive web application built with React.js and Tailwind CSS that generates strong, random passwords based on user-defined criteria.

[**Live Demo**](https://debasishsasmal.github.io/React-Password-Generator/) 

---

## Tech Stack

- **Framework:** React.js
- **Styling:** Tailwind CSS
- **Language:** JavaScript (ES6)

---

## Screenshot

<img width="1279" height="686" alt="image" src="https://github.com/user-attachments/assets/498aef2b-a832-4f7c-9377-5e6a2f6bbb79" />

---

## Features

- **Customizable Length:** Generate passwords of any length between 6 and 30 characters using a range slider.
- **Character Options:** Easily include or exclude numbers and special characters with simple checkboxes.
- **Instant Updates:** The password updates in real-time as you change the criteria.
- **One-Click Copy:** A convenient "Copy" button to copy the generated password to the clipboard.
- **Responsive Design:** A clean and modern UI that works perfectly on all screen sizes.

---

## Core Concepts & Hooks Implemented

This project was a deep dive into some of the most fundamental hooks in React:

- `useState`: To manage state for variables like password length, number inclusion, special character inclusion, and the final generated password.
- `useEffect`: To trigger the password generation function whenever the dependencies (length, numbers, characters) change.
- `useCallback`: To memoize the password generation function for performance optimization.
- `useRef`: To get a direct reference to the password input field for the "copy to clipboard" functionality.

---

## Getting Started / How to Run Locally

To get a local copy up and running, follow these simple steps.

1.  Clone the repository:
    ```sh
    git clone [https://github.com/debasishsasmal/React-Password-Generator.git](https://github.com/debasishsasmal/React-Password-Generator.git)
    ```
2.  Navigate to the project directory:
    ```sh
    cd React-Password-Generator
    ```
3.  Install NPM packages:
    ```sh
    npm install
    ```
4.  Run the application:
    ```sh
    npm run dev
    ```
