# Coding School Sign Up Form

This is a simple signup form created as part of the HTML exercises. 

## What was done:
- Created a form using semantic HTML (`<form>`, `<fieldset>`, `<legend>`).
- Included fields for **Name**, **Email**, and **Telephone** using the correct input types (`text`, `email`, `tel`).
- Added a `<select>` dropdown for choosing a bootcamp course.
- Ensured accessibility by associating `<label>` tags with their respective `<input>` and `<select>` elements using the `for` and `id` attributes. This means clicking the label text will focus the input field!
- Made all fields mandatory by adding the `required` attribute to them.
- Everything is wrapped inside a `<fieldset>` to visually group the form fields together, which is helpful since we are not using CSS yet.

## How to test:
Open `index_Ki.html` in your browser. Try to submit the form without filling it out to see the `required` validation in action. Also, click on the text labels (like "Name:" or "Email:") to see how it automatically focuses the corresponding input box.
