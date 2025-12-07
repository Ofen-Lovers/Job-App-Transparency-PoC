# Job Application Transparency - Proof of Concept (PoC)

This is the Proof-of-Concept for the CS412 Position Paper: **"Why Transparent-by-Design Job Application Systems Are Ethically Necessary"**.

## Overview
This PoC demonstrates the trade-off between **Performance** (Black Box Mode) and **Transparency** (Transparent Mode) in automated hiring systems.

## Team Roles & Assignments

*   **Javier Raut**: Initial Core Setup & Black Box Mode Logic.
    *   *Current Status*: Implemented basic skeleton and Black Box scoring.
*   **Krystal Bacalso**: Transparent Mode Logic.
    *   *Task*: Implement the mode toggle, simulated delays, and the logic to switch between Black Box and Transparent modes.
*   **Jhon Lloyd Omblero: Frontend Design & Layout
    *   *Task*: Enhance the UI by applying professional CSS styling to replace the current basic HTML appearance.
*   **Joseph Deysolong**: Input Validation & Explanation Logic.
    *   *Task*: Implement input validation (e.g., GPA range checks) and helper functions to generate specific explanation text for rejections.

## How to Run
Since this is a single-file application with no external dependencies, you can run it simply by opening the file in your browser:

1.  Locate `index.html` in this folder.
2.  Double-click it or drag it into your web browser.

## Developer Guide

The `index.html` file is currently a **barebones skeleton** initialized by Javier. It contains the core Black Box logic.

### For Krystal (Transparent Mode)
*   Look for `TODO: [KRYSTAL]` comments.
*   You need to add the radio buttons for mode selection.
*   Implement the `setTimeout` delay in `processApplication`.
*   Update `displayResult` to show specific reasons when in Transparent Mode.

### For Jhon (Frontend)
*   Look for `TODO: [JHON]` comments.
*   Add a `<style>` block in the `<head>` and apply CSS.
*   **Constraint**: Keep all CSS inside `index.html`. Do not create external CSS files.

### For Joseph (Validation & Explanations)
*   Look for `TODO: [JOSEPH]` comments.
*   Add checks in `handleSubmission` to ensure GPA is between 0.0-4.0.
*   Create a function (e.g., `generateExplanations(gpa, experience)`) that returns an array of reason strings.

## Requirements
*   **Single File**: Do not create separate `.css` or `.js` files. Everything must stay in `index.html`.
*   **No Frameworks**: Stick to Vanilla JS and CSS.
