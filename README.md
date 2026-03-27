# DSA Oral Test Platform

A simple, static webpage designed for conducting Data Structures and Algorithms (DSA) live coding oral tests. It uses a clean UI with Dark/Light mode support and built-in KaTeX rendering for math symbols.

## Features

- **Randomizer (The Well):** Contains 8 hidden normal difficulty questions. Clicking the "Draw Question" button draws one random question for the student to live-code.
- **Hard Questions:** 2 advanced questions are constantly displayed at the bottom of the page.
- **KaTeX Support:** Fully supports mathematical formulas like $O(n \log n)$ or subsets $A \cup B$.
- **Dark/Light Mode:** A toggle in the top right corner switches the theme instantly.

## Topics Covered

These questions focus on fundamental Python constructs:
- Numeric Data, String Data
- Loops (`for`, `while`), `range`
- Conditionals (`if`)
- Data Structures (`dict`, `list`, `tuple`, `set`)

## Deployment (GitHub Pages)

Since this is a single static HTML file with zero build steps, deploying it via your GitHub Student account is incredibly easy:

1. Create a new repository on your GitHub account (e.g., `dsa-oral-test`).
2. Upload this `index.html` (and this `README.md`) to the root of the repository.
3. Go to the repository's **Settings** tab.
4. Navigate to **Pages** on the left sidebar.
5. Under **Build and deployment > Source**, select **Deploy from a branch**.
6. Select the `main` (or `master`) branch and click **Save**.
7. GitHub will provide you with a URL where your static site is live (usually `https://<your-username>.github.io/dsa-oral-test/`).

## Editing Questions

To change the questions, open `index.html` and modify the `normalQuestions` and `hardQuestions` arrays inside the `<script>` tag at the bottom of the file. No build tools required!

Good luck with your tutoring sessions!
