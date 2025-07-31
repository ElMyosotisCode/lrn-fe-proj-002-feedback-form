# Misael's F. End 2nd Learning Project - "Feedback Form Web Page"

Hello... 😃👋🏻  
It's me Misael Randy Limpaty (ElMyosotisCode) your future Front End Developer Expert.

This project is my second learning project, for now it's only got simple visually Web Form.

---


## Roadmap

So here are my plan for this learning project
*May change in the future

**_Phase 1 : Barebone Structure (HTML)_**
- ☑ **HTML** | Base structure & Semantics
    Build the form framework with semantic tags (`form`, `fieldset`, `label`, etc.).

**_Phase 2 : Visual Styling (CSS)_**
- ☑ **CSS** | Global Styling & Variables
    Set up global styles and CSS variables for consistent theming.

- ☑ **CSS** | Input & Label Alignment
    Adjust the layout for each input group. Possibly use Flexbox to arrange labels and inputs neatly and responsively.

- ⬜ **CSS** | Form Container Layout
    Create a “card view” for the form so that it is centered on the page using `max-width`, `margin: auto`, and `box-shadow`.

- ⬜ **CSS** | Custom Radio Button Styling
    Hide the default radio button display and style the `label` to create a customizable, clickable star rating.

- ⬜ **CSS** | Input, Textarea & Button Styling
    Styling `input` and `textarea`. Also, redesigning the “Submit” `button` to make it more appealing with `:hover` and `:active` state effect.

---

## Development Log / Project Journal

### Project Progress Session 1 - HTML Form Basic Structure
<italic>**Date:** 2025-07-23</italic>

💬 In this initial session, the main focus is on building the structural foundation of the feedback page using pure semantic _`HTML`_. 
The result is a page that is functional in terms of structure, albeit without visual styling.

- 📍 **Complete Form Structure**
    - Successfully created a dummy form structure that includes inputs for name, email, a 5-star rating system, and a text area for messages.

- 📍 **Semantic Grouping**
    - Using `fieldset` and `legend` to group _rating options_, providing better context for users and screen readers.

- 📍 **Browser Basic Validation**
    - Implemented simple client-side validation. 
    - The form now automatically checks whether required fields have been filled in and whether the email format is correct before it can be sent.

### Web Page Visual in Project Progress Session 1

![Web Page Screenshot 01](https://github.com/ElMyosotisCode/lrn-fe-proj-002-feedback-form/blob/main/images/documentations/webpage-screenshot-01.JPG)

<p align="center">- - -</p>

### Project Progress Session 2 - HTML Basic A11y and CSS Flexbox
<italic>**Date:** 2025-07-28</italic>

💭 In this progress session, I began to apply _`CSS`_ to transform the form from a pure structure into a neatly arranged layout that is easier to use. The foundation for the visual design system also began to take shape.

- 🎯 **CSS Design System**
    - Setting up a framework for the design system in CSS, including variables for color schemes, typography scales, and spacing systems (8-Point Grid) for consistency across the project.

- 🎯 **Vertical Layout Arrangement**
    - Applied _`Flexbox layout`_ to arrange each input group (label and form) vertically, creating a clear filling flow.

- 🎯 **Horizontal Layout Arrangement**
    - Added semantically linked text cues to the message area to provide additional context for screen reader users.

- 🎯 **Accessibility Enhancements**


### Web Page Visual in Project Progress Session 2

![Web Page Screenshot 02](https://github.com/ElMyosotisCode/lrn-fe-proj-002-feedback-form/blob/main/images/documentations/webpage-screenshot-02.JPG)

<p align="center">- - -</p>

### Project Progress Session 3 - CSS Grid Layout
<italic>**Date:** 2025-07-30</italic>

✌ In this session, I focused on implementing CSS Grid Layout to enhance the form's structure and responsiveness:✌
- ✍️ **CSS Grid Layout Implementation**

---
---

## Points of Key Learnings

### Learning Module Session 6 -> HTML Form Basic Structure

💡 Here are some key points I learned through this session:
- 1️⃣ **Structure & Semantic (HTML Architecture)**
    ➤  Understand the use of basic _HTML form_ tags such as `<form>`,  `<input>`, `<textarea>`, and `<button>` to create a functional form structure.
    ➤  Make use of `<fieldset>` and `<legend>` to group related elements (such as rating options), which significantly improves structural clarity and accessibility.

- 2️⃣ **Accessibility & UX**
    ➤  Implemented a <u>"_sacred pairing_"</u> between `<label>` and `<input>` elements using their `for` attribute to improve accessibility and user experience.
    ➤  With that, I can ensure that each input can be clearly identified by _screen readers_ and allows users to click on the label to activate the input.

- 3️⃣ **Data Handling & Validations**
    ➤  Learn about the crucial role of the `name` attribute as a key for data sent to the server and for grouping `radio buttons` into a single exclusive option.
    ➤  Implemented client-side validation without JavaScript using HTML5 attributes:
        🟣  `required` to ensure mandatory fields are filled.
        🟣  `type="email"` to validate email format.
        🟣  `maxlength=200` to limit the length of the feedback message.

<p align="center">- - -</p>

### Learning Module Session 7 -> HTML Basic A11y and CSS Flexbox

🔴🟠🟡🟢🔵🟣
💡 Here are some key points I learned through this session:
- 1⃣ **CSS Architecture & Design System**
    ≫   _<u>CSS Variables (`:root`)</u>_ 
        Building a “_Single Source of Truth_” for design values. I created a comprehensive variable system for:
        🔵  `8-Point Spacing System (--space-sm, etc)` to ensures that all spacing (_margins, padding, gaps_) is consistent.
        🔵  `Typography Scale (--font-size-base, etc)`
        🔵  `Color Palette (--color-primary, etc)`

- 2⃣ **Flexbox Layout for Responsive Design**
    - Learning how to use Flexbox to create a responsive layout for the form, allowing it to adapt to different screen sizes.
    - Using properties like `display: flex`, `flex-direction`, and `justify-content` to control the layout of form elements.
    - `flex-direction: row` to align items horizontally, and the main axis is the horizontal line.
    - `flex-direction: column` to align items vertically, and the main axis is the vertical line.
    - `justify-content` to control the alignment of items along the main axis, such as `space-between`, `space-around`, or `space-evenly`.
    - `gap` to control the spacing between items in a Flexbox container, making it easier to manage layout without additional margins or padding.

<p align="center">- - -</p>

### Learning Module Session 8 -> CSS Grid Layout

💡 Here are some key points I learned through this session:

#### CSS Grid Base Mind Concept
╰┈➤ **CSS Grid** 
    is a powerful layout system that allows you to create complex, responsive web layouts with ease. It uses a two-dimensional grid system to arrange elements in rows and columns.

╰┈➤ **Grid Container**
    - _Grid Container_ is the parent element that holds the grid items.
    - It is defined by setting `display: grid` on the container.
    - Any properties applied to the _Grid Container_ will affect the _Grid Items_ inside it

╰┈➤ **Grid Items**
    - _Grid Items_ are the child elements within the _Grid Container_ that will be arranged in a grid layout.
    - _Grid items_ can be any HTML element, such as `<div>`, `<section>`, or `<article>`, and they will automatically become grid items when placed inside a _Grid Container_.

    ![Key Learnings Table 01](https://github.com/ElMyosotisCode/lrn-fe-proj-002-feedback-form/blob/main/images/documentations/key-learnings-table-01.JPG)

#### CSS Grid Blueprint
╰┈➤ **Grid Template Columns and Rows**
    - The `grid-template-columns` and `grid-template-rows` properties define the structure of the grid by specifying the number and size of columns and rows.
    - You can use fixed sizes (e.g., `100px`), percentages (e.g., `50%`), or flexible units like `fr` (fractional units) to create responsive layouts.

#### CSS Grid Item Placement
╰┈➤ **Grid Start and End**
    - The `grid-column-start` is used to specify the starting position of a grid item within the grid columns.
    - The `grid-column-end` is used to specify the ending position of a grid item
    - The `grid-row-start` is used to specify the starting position of a grid item within the grid rows.
    - The `grid-row-end` is used to specify the ending position of a grid item.

╰┈➤ **Grid Items Alignment**
    - The `align-items` property is used to align grid items vertically within their grid area.
    - The `justify-items` property is used to align grid items horizontally within their grid area.
    - The `align-self` and `justify-self` properties can be used on individual grid items to override the alignment set by the container.
---

Update: 2025-07-31