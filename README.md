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

### Progress Session 1 - HTML Form Basic Structure
**Date:** 2025-07-23

✌ In this initiation session, I created the barebone of HTML structure, such as: ✌
- ✍️ **Base structure of my Feedback Form web page**
    - Including input boxes for name, email address, and a text area for feedback message.
    - I also added a rating system with radio buttons for user feedback.
    - A button to simulate the form submission.

### Web Page Appearances in Session 6

![Web Page Screenshot 01](https://github.com/ElMyosotisCode/lrn-fe -006-feedback-form-html-structure/blob/main/images/webpage-screenshot-01.JPG)

<p align="center">- - -</p>

### Progress Session 2 - HTML Basic A11y and CSS Flexbox
**Date:** 2025-07-28

✌ In this session, I focused on enhancing the accessibility of the HTML form, like: ✌
- ✍️ **Improved Accessibility Features**
    - Enhanced form accessibility by linking hint text to the textarea using `aria-describedby`, providing crucial context for screen reader users.
    - Ensured that all form controls are properly labeled and associated with their respective inputs.

Also, I applied Flexbox for layout to make the form more responsive and visually appealing:
- ✍️ **Flexbox Layout Implementation**
    - Structured the primary form layout with Flexbox, organizing input groups into vertical columns (`flex-direction: column`) and aligning the rating options into a balanced horizontal row (`justify-content: space-evenly`).
    - Adjusted the spacing and alignment of labels and inputs for better user experience.

### Web Page Appearances in Session 7

![Web Page Screenshot 02](https://github.com/ElMyosotisCode/lrn-fe -006-feedback-form-html-structure/blob/main/images/webpage-screenshot-02.JPG)

<p align="center">- - -</p>

---

## Key Learnings

### Learning Module Session 6 -> HTML Form Basic Structure

💡 Here are some key points I learned through this session:
- 1️⃣ **Basic Structure of an HTML Form**
    - Understanding the basic structure of an HTML form, including the use of `<form>`, `<input>`, `<textarea>`, and `<button>` elements.

- 2️⃣ **Input Types and Attributes**
    - How to use different types of input fields such as `text`, `email`, and `radio buttons` to collect user data.

- 3️⃣ **Relationship Between `for` _inside_ `<label>` tag and `id` _inside_ `<input>` tag**
    - The value of the `for` attribute in a `<label>` tag should match the `id` of the corresponding `<input>` element to ensure proper accessibility and better User Experience.

- 4️⃣ **The Significance of `name` Attribute**
    - The `name` attribute in form elements is crucial for identifying the data when the form is submitted, allowing the server to recognize the input correctly.
    - For `radio buttons`, using the same value of `name` attribute for each `radio buttons` in the same context, is meant to group them together and make sure only one option can be selected at a time.

- 5️⃣ **The Semantic Grouping of `<fieldset>` and `<legend>`**
    - The `<fieldset>` element is used to group related form controls, and the `<legend>` element provides a caption for the group, enhancing accessibility and clarity of the form.

- 6️⃣ **Utilizing Browser's Simple Input Validation**
    - Using the `required` attribute on form elements to ensure that users fill out necessary fields before submission.
    - Using the `type="email"` attribute on the email input field to ensure that the user enters a valid email format.
    - Using the `maxlength=200` attribute on the feedback textarea to limit the number of characters a user can input, ensuring that the feedback message is concise and manageable.

<p align="center">- - -</p>

### Learning Module Session 7 -> HTML Basic A11y and CSS Flexbox

💡 Here are some key points I learned through this session:
- **Web Accessibility Principle (A11y) for Web Form**
    - Understanding the importance of web accessibility and how to implement it in forms.
    - Using `aria-describedby` to provide additional context for screen readers, enhancing the usability of the form for users with disabilities.
    - By using standard HTML elements such as `<label>`, `<input>`, and `<textarea>`, I ensured that the form is accessible with keyboard.

- **Flexbox Layout for Responsive Design**
    - Learning how to use Flexbox to create a responsive layout for the form, allowing it to adapt to different screen sizes.
    - Using properties like `display: flex`, `flex-direction`, and `justify-content` to control the layout of form elements.
    - `flex-direction: row` to align items horizontally, and the main axis is the horizontal line.
    - `flex-direction: column` to align items vertically, and the main axis is the vertical line.
    - `justify-content` to control the alignment of items along the main axis, such as `space-between`, `space-around`, or `space-evenly`.
    - `gap` to control the spacing between items in a Flexbox container, making it easier to manage layout without additional margins or padding.

---

Update: 2025-07-28