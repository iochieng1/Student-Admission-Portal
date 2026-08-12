# School Admission Portal - HTML Learning Project

## Overview

The **Gifted Hearts High School Admission Portal** is a simple HTML5 project designed to collect student admission information. The webpage allows users to enter student details, parent information, and submit an admission application through a structured form.

This project demonstrates the use of semantic HTML, form elements, fieldsets, labels, validation, placeholders, and accessibility best practices.

---

# Features

* Semantic HTML5 structure
* Student information section
* Parent information section
* Form validation using `required`
* Date picker for Date of Birth
* Placeholder text for user guidance
* Mobile-friendly viewport configuration
* Accessible labels linked to inputs
* Professional page layout with header and footer

---

# HTML Elements Used

## 1. `<!DOCTYPE html>`

Declares the document as an HTML5 webpage.

```html
<!DOCTYPE html>
```

### Purpose

* Ensures the browser renders the page using HTML5 standards.

---

## 2. `<html>`

Root element of the webpage.

```html
<html lang="en">
```

### Purpose

* Contains all webpage content.
* Specifies English as the document language.

---

## 3. `<head>`

Stores metadata and page configuration.

```html
<head>
```

### Elements Included

#### Character Encoding

```html
<meta charset="UTF-8">
```

Ensures proper display of text and special characters.

#### Viewport

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

Improves responsiveness on mobile devices.

#### Title

```html
<title>Gifted Hearts High School Admission Portal</title>
```

Appears in the browser tab.

---

## 4. `<body>`

Contains all visible content displayed to users.

```html
<body>
```

---

## 5. `<header>`

Introduces the webpage.

```html
<header>
    <h1>Gifted Hearts High School</h1>
    <p>School Admission Portal</p>
</header>
```

### Purpose

* Displays the school name.
* Provides context for visitors.

---

## 6. Headings (`<h1>`)

Main heading of the webpage.

```html
<h1>Gifted Hearts High School</h1>
```

### Purpose

* Identifies the webpage.
* Improves accessibility and SEO.

---

## 7. `<main>`

Contains the primary content of the webpage.

```html
<main>
```

### Purpose

* Helps screen readers identify the main content area.
* Organizes page structure.

---

## 8. `<form>`

Creates the admission application form.

```html
<form action="#" method="post">
```

### Purpose

* Collects user information.
* Defines how form data is submitted.

---

## 9. `<fieldset>`

Groups related form controls together.

### Student Information

```html
<fieldset>
```

### Parent Information

```html
<fieldset>
```

### Purpose

* Organizes form sections.
* Improves readability and accessibility.

---

## 10. `<legend>`

Provides a title for each fieldset.

Examples:

```html
<legend>Student Information</legend>
```

```html
<legend>Parent Information</legend>
```

### Purpose

* Identifies grouped form controls.

---

## 11. `<label>`

Associates descriptive text with input fields.

Examples:

```html
<label for="fullname">Full Name</label>
```

```html
<label for="phone">Phone Number</label>
```

### Purpose

* Improves accessibility.
* Helps users understand required information.

---

## 12. `<input>`

Accepts user information.

### Full Name

```html
<input
    type="text"
    id="fullname"
    name="fullname"
    placeholder="Enter student's full name"
    required
>
```

### Admission Number

```html
<input
    type="text"
    id="admission-number"
    name="admission-number"
    required
>
```

### Date of Birth

```html
<input
    type="date"
    id="dob"
    name="dob"
    required
>
```

### Parent Name

```html
<input
    type="text"
    id="parent-name"
    name="parent-name"
    required
>
```

### Phone Number

```html
<input
    type="tel"
    id="phone"
    name="phone"
    placeholder="e.g. 0712345678"
    required
>
```

### Purpose

* Collects user data.
* Provides built-in validation.
* Offers a date picker for birth dates.

---

## 13. `<button>`

Creates a clickable form submission button.

```html
<button type="submit">
    Submit Application
</button>
```

### Purpose

* Submits the admission application form.

---

## 14. `<footer>`

Represents the footer section.

```html
<footer>
```

Example:

```html
<p>&copy; 2026 Gifted Hearts High School. All Rights Reserved.</p>
```

### Purpose

* Displays copyright information.
* Appears at the bottom of the page.

---

## 15. `<p>`

Defines paragraphs used throughout the page.

Examples:

```html
<p>School Admission Portal</p>
```

```html
<p>&copy; 2026 Gifted Hearts High School. All Rights Reserved.</p>
```

### Purpose

* Displays supporting information and footer content.

---

# Website Structure

```text
HTML
│
├── Head
│   ├── Meta Charset
│   ├── Viewport Meta
│   └── Title
│
└── Body
    ├── Header
    │   ├── H1
    │   └── Intro Paragraph
    │
    ├── Main
    │   └── Form
    │       ├── Fieldset
    │       │   ├── Legend (Student Information)
    │       │   ├── Labels
    │       │   └── Inputs
    │       │
    │       ├── Fieldset
    │       │   ├── Legend (Parent Information)
    │       │   ├── Labels
    │       │   └── Inputs
    │       │
    │       └── Submit Button
    │
    └── Footer
        └── Copyright Paragraph
```

---

# Accessibility Improvements

This version includes several accessibility enhancements:

* Labels linked to inputs using `for` and `id`.
* Semantic elements such as `header`, `main`, and `footer`.
* Required field validation.
* Placeholder text for user guidance.
* Proper input types (`date`, `tel`, `text`).
* Structured fieldsets and legends.

---

# Future Enhancements

Potential improvements include:

* Add CSS styling.
* Create a navigation menu.
* Add email address field.
* Add gender selection using radio buttons.
* Add file upload for student documents.
* Connect the form to a backend database.
* Display a success message after submission.

---

# Learning Outcomes

By completing this project, you will gain experience with:

* HTML5 document structure
* Semantic HTML elements
* Form creation and validation
* Labels and accessibility
* Fieldsets and legends
* Input types and placeholders
* Headers and footers
* Building a real-world admission form

This project provides a practical introduction to creating accessible and well-structured forms using HTML.
