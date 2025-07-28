# Misael's F. End 2nd Learning Project - "Feedback Form Web Page"

Hello... 😃👋🏻  
It's me Misael Randy Limpaty (ElMyosotisCode) your future Front End Developer Expert.

This project is my second learning project, for now it's only pure HTML without internal nor inline CSS.

---




## Roadmap

So here are my plan for this learning project
*May change in the future

**_Phase 1 : Barebone Structure (HTML)_**
- ☑ **HTML** | Base structure & Semantics<br>
    Build the form framework with semantic tags (`form`, `fieldset`, `label`, etc.).

**_Phase 2 : Visual Styling (CSS)_**
- ⬜ **CSS** | Global Styling & Variables<br>
    Set up global styles and CSS variables for consistent theming.

- ⬜ **CSS** | Form Container Layout<br>
    Create a “card view” for the form so that it is centered on the page using `max-width`, `margin: auto`, and `box-shadow`.

- ⬜ **CSS** | Input & Label Alignment<br>
    Adjust the layout for each input group. Possibly use Flexbox to arrange labels and inputs neatly and responsively.

- ⬜ **CSS** | Custom Radio Button Styling<br>
    Hide the default radio button display and style the `label` to create a customizable, clickable star rating.

- ⬜ **CSS** | Input, Textarea & Button Styling<br>
    Styling `input` and `textarea`. Also, redesigning the “Submit” `button` to make it more appealing with `:hover` and `:active` state effect.

---




## Development Log / Project Journal

### Progress Session 1 - HTML Form Basic Structure
~~ <i>**Date:** 2025-07-23</i>

In this initiation session, I created the barebone of HTML structure, such as: ✌
- ✍️ **Base structure of my Feedback Form web page**
    - Including input boxes for name, email address, and a text area for feedback message.
    - I also added a rating system with radio buttons for user feedback.
    - A button to simulate the form submission.

### Web Page Appearances in Session 6

![Web Page Screenshot 01](https://github.com/ElMyosotisCode/lrn-fe-proj-002-feedback-form/blob/main/images/webpage-screenshot-01.JPG)

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