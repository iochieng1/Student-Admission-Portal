# School Admission Portal - HTML Learning Project

## Overview

This project is a basic school admission form built using HTML. It allows users to enter student and parent information and submit the form.

The goal of this project is to practice core HTML elements such as forms, fieldsets, labels, inputs, buttons, and semantic page structure.

---

## HTML Elements Used

### 1. `<!DOCTYPE html>`

Defines the document as an HTML5 document.

```html
<!DOCTYPE html>
```

---

### 2. `<html>`

The root element that contains the entire webpage.

```html
<html lang="en">
```

* `lang="en"` specifies that the page content is in English.

---

### 3. `<head>`

Contains metadata and information about the webpage.

```html
<head>
```

Inside the head section:

#### `<meta>`

Defines character encoding.

```html
<meta charset="UTF-8">
```

**Note:** In the original code there is a typo:

```html
<metacharset="UTF-8">
```

Correct version:

```html
<meta charset="UTF-8">
```

#### `<title>`

Sets the page title shown in the browser tab.

```html
<title>Gifted Hearts High School</title>
```

---

### 4. `<body>`

Contains all visible content displayed on the webpage.

```html
<body>
```

---

### 5. `<h1>`

Main heading of the page.

```html
<h1>School Admission Portal</h1>
```

Purpose:

* Displays the primary title.
* Improves accessibility and page structure.

---

### 6. `<main>`

Represents the main content area of the webpage.

```html
<main>
```

Purpose:

* Helps search engines and screen readers identify the primary content.

---

### 7. `<form>`

Creates a form for collecting user input.

```html
<form>
```

Purpose:

* Groups all form controls together.
* Allows data submission.

**Note:** There is an extra `s` after the opening tag in the original code:

```html
<form>s
```

It should be:

```html
<form>
```

---

### 8. `<fieldset>`

Groups related form elements together.

```html
<fieldset>
```

Used twice:

* Student Information
* Parent Information

Purpose:

* Organizes form sections.
* Improves readability.

---

### 9. `<legend>`

Provides a title for a fieldset.

```html
<legend>Student Information</legend>
```

Examples:

* Student Information
* Parent Information

---

### 10. `<label>`

Describes an input field.

```html
<label>Full Name</label>
```

Purpose:

* Helps users understand what information is required.
* Improves accessibility.

---

### 11. `<input>`

Accepts user input.

Examples:

Text input:

```html
<input type="text">
```

Telephone input:

```html
<input type="tel">
```

Input fields used:

| Field            | Type |
| ---------------- | ---- |
| Full Name        | text |
| Admission Number | text |
| Date of Birth    | text |
| Parent Name      | text |
| Phone Number     | tel  |

---

### 12. `<button>`

Creates a clickable button.

```html
<button type="submit">
    Submit
</button>
```

Purpose:

* Sends form data when clicked.

---

### 13. `<footer>`

Represents the footer section of the webpage.

```html
<footer>
```

Purpose:

* Displays information at the bottom of the page.

---

### 14. `<p>`

Defines a paragraph.

```html
<p>School Portal</p>
```

Purpose:

* Displays footer text.

---

## Page Structure

```text
HTML
│
├── Head
│   ├── Meta
│   └── Title
│
└── Body
    ├── H1 Heading
    ├── Main
    │   └── Form
    │       ├── Fieldset (Student Information)
    │       ├── Fieldset (Parent Information)
    │       └── Submit Button
    │
    └── Footer
        └── Paragraph
```

---

## Improvements To Make

1. Use proper labels linked to inputs with `for` and `id`.
2. Change Date of Birth input to:

```html
<input type="date">
```

3. Add placeholder text.

```html
<input type="text" placeholder="Enter Full Name">
```

4. Add required validation.

```html
<input type="text" required>
```

5. Add CSS styling to improve appearance.

---

## Learning Outcomes

After completing this project, you should understand:

* Basic HTML document structure
* Semantic HTML elements
* Form creation
* Input fields
* Buttons
* Fieldsets and legends
* Footer usage
* Accessibility basics

This project is an excellent beginner exercise for learning HTML forms and page structure.
