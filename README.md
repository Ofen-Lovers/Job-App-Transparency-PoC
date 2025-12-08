# Job Application Transparency - Proof of Concept (PoC)

This is the Proof-of-Concept for the CS412 Position Paper: **"Why Transparent-by-Design Job Application Systems Are Ethically Necessary"**.

## Live Demo
Check out the live version here: [Job Application Transparency PoC](https://ofen-lovers.github.io/Job-App-Transparency-PoC/)

## Overview
This PoC demonstrates the trade-off between **Performance** (Black Box Mode) and **Transparency** (Transparent Mode) in automated hiring systems.
- **Black Box Mode**: Provides immediate feedback but generic rejection reasons.
- **Transparent Mode**: Simulates processing time and provides specific, actionable feedback on rejection.

## Team Roles & Implementation
*   **Javier Raut**: Initial Core Setup & Black Box Mode Logic.
    *   Implemented the basic application skeleton, core scoring logic, and the "Generic" rejection flow.
*   **Krystal Bacalso**: Transparent Mode Logic.
    *   Implemented the mode toggle, simulated delays for transparency, and the logic to switch between Black Box and Transparent modes.
*   **Jhon Lloyd Omblero**: Frontend Design & Layout.
    *   Enhanced the UI with professional CSS styling, responsive layout, and visual feedback states.
*   **Joseph Deysolong**: Input Validation & Explanation Logic.
    *   Implemented robust input validation (GPA ranges, etc.) and the "Explanation Engine" that generates specific feedback for the user in Transparent Mode.

## How to Run Locally
Since this is a single-file application with no external dependencies, you can run it simply by opening the file in your browser:

1.  Clone the repository.
2.  Locate `index.html` in the folder.
3.  Double-click it or drag it into your web browser.

## Requirements Compliance
*   **Single File**: The entire application (HTML, CSS, JS) is contained within `index.html`.
*   **No Frameworks**: Built entirely with Vanilla JS and CSS.
