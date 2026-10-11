# QuickNotes

QuickNotes is a small note-taking web app built with plain HTML, CSS and JavaScript. You can write short notes, file them under Personal, Work or Study, search through them and delete the ones you no longer need. Your notes are saved in the browser, so they are still there after you refresh the page.

## Features

- Add notes (up to 200 characters) with a category: Personal, Work or Study
- Each note shows its text, a category label, the date and time, and a Delete button
- Colour-coded note cards for each category
- Validation with clear error messages for empty or too-long notes
- Live search that ignores upper/lower case
- Note counter ("no notes", "1 note" or "N notes")
- Notes saved to `localStorage` and loaded when the page opens
- Responsive layout that stacks the form on screens 600px wide or smaller
- Bonus: "Clear all" button with a confirmation prompt

## How to run locally

1. Clone the repository: `git clone https://github.com/your-username/quicknotes-app.git`
2. Open the `quicknotes-app` folder.
3. Double-click `index.html` to open it in your browser (no server or install needed).

## What I learned

- How to use semantic HTML (`header`, `main`, `section`, `footer`) and link a `label` to an input with `for` and `id`.
- How to lay out a form with Flexbox and change it for small screens with a `@media (max-width: 600px)` rule.
- How to keep data in an array of objects and rebuild the page from it with a `render()` function using `createElement` and `textContent`, which avoids injecting user text as HTML.
- How to save and load data with `localStorage`, `JSON.stringify` and `JSON.parse`.
- How committing after each small task makes a project easier to build and to review.
