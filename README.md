# Odin Project: Sign-Up Form

## Project Overview

This project is part of **The Odin Project's Intermediate HTML and CSS curriculum**. The goal is to build a visually appealing sign-up form that closely matches a provided design reference, while practicing key layout and positioning techniques.

The final result features:
- A full-height sidebar with a background image of lush green ferns.
- An overlaid semi-transparent banner containing the "ODIN" logo and text.
- A clean right-hand section with motivational introductory text, a structured form (with paired input fields), a "Create Account" button, and a "Log in" link.

This project emphasizes **positioning** (relative, absolute, and basic floats) without relying on modern layout tools like Flexbox or Grid, as per the assignment guidelines.

## Features

- Responsive image sidebar that covers the full viewport height.
- Absolutely positioned logo banner over the sidebar image.
- Form fields arranged in two columns using simple float-based layout.
- Subtle shadowing and styling to match the reference design.
- Basic form validation attributes (required fields, email type, phone pattern).
- Clean typography and spacing for readability.

## Technologies Used

- HTML5
- CSS3 (positioning, floats, basic styling)

No external libraries or frameworks were used.

## What I Learned

- How to create a containing block with `position: relative` so absolutely positioned children stay within their parent.
- Building multi-column form layouts with floats and clearing.
- Using `object-fit: cover` to properly scale background images.
- Structuring HTML semantically with logical parent-child container relationships.
- Debugging layout issues using browser developer tools (inspecting boxes, borders, and positioning contexts).

## Setup & Installation

Since this is a static site, no build process is required.

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/odin-signup-form.git
