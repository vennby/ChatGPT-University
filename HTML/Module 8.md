# Module 8: Forms

In this module, we will explore HTML forms. Forms are an essential part of web development and allow users to input and submit data. We'll cover the introduction to HTML forms, text input fields, checkboxes, radio buttons, dropdown menus, text areas, submit buttons, form validation, and attributes. Let's dive in!

### 8.1: Introduction to HTML Forms (`<form>`)
HTML forms provide a way to collect user input on a webpage. The `<form>` element is used to create a form. It acts as a container for various form elements. Here's an example of a basic form structure:

```html
<form>
  <!-- form elements go here -->
</form>
```

Inside the `<form>` element, we'll add the necessary components to build the form.

### 8.2: Text Input Fields (`<input type="text">`)
Text input fields allow users to enter text. The `<input>` element with the `type="text"` attribute is used to create a text input field. Here's an example:

```html
<input type="text" name="username" placeholder="Enter your username">
```

In this example, we have a text input field with the name attribute set to "username." The placeholder attribute provides a hint or example text to guide the user.

### 8.3: Checkboxes (`<input type="checkbox">`)
Checkboxes allow users to select multiple options. The `<input>` element with the `type="checkbox"` attribute is used to create checkboxes. Here's an example:

```html
<input type="checkbox" name="interests" value="football"> Football
<input type="checkbox" name="interests" value="basketball"> Basketball
<input type="checkbox" name="interests" value="tennis"> Tennis
```

In this example, we have three checkboxes grouped under the same name attribute "interests." The value attribute represents the value associated with each checkbox when the form is submitted.

### 8.4: Radio Buttons (`<input type="radio">`)
Radio buttons allow users to select a single option from a list. The `<input>` element with the `type="radio"` attribute is used to create radio buttons. Here's an example:

```html
<input type="radio" name="gender" value="male"> Male
<input type="radio" name="gender" value="female"> Female
```

In this example, we have two radio buttons with the name attribute set to "gender." Only one option can be selected at a time within the same group.

### 8.5: Dropdown Menus (`<select>` and `<option>`)
Dropdown menus, also known as select menus, provide a list of options for users to choose from. The `<select>` element is used to create a dropdown menu, and the `<option>` element represents each selectable option. Here's an example:

```html
<select name="country">
  <option value="usa">USA</option>
  <option value="uk">UK</option>
  <option value="canada">Canada</option>
</select>
```

In this example, we have a dropdown menu with three options. The selected option will be sent when the form is submitted.

### 8.6: Text Areas (`<textarea>`)
Text areas allow users to enter multi-line text. The `<textarea>` element is used to create a text area. Here's an example:

```html
<textarea name="message" rows="4" cols="30" placeholder="Enter your message"></textarea>
```

In this example, we have a text area with the name attribute set to "message." The rows and cols attributes determine the size of the text area.

### 8.7: Submit Buttons (`<input type="submit">`)
Submit buttons are used to submit the form data to the server. The `<input>` element with the `type="submit"` attribute is used to create a submit button. Here's an example:

```html
<input type="submit" value="Submit">
```

In this example, we have a submit button with the value "Submit." When the button is clicked, the form data will be submitted.

### 8.8: Form Validation and Attributes
Form validation ensures that user input meets specific criteria. HTML provides built-in form validation attributes such as `required`, `maxlength`, `min`, and more. Here's an example of using the `required` attribute:

```html
<input type="text" name="name" required>
```

In this example, the `required` attribute indicates that the field must be filled out before the form can be submitted. There are various validation attributes available to enforce specific rules on form inputs.

### 8.9: Closing Thoughts
In this module, we've learned about creating forms, text input fields, checkboxes, radio buttons, dropdown menus, text areas, submit buttons, form validation, and attributes. Practice creating different types of forms and experiment with various validation techniques. 

<p> In the next module, we will explore semantic HTML.

<br>

<p align="left"><a href="https://github.com/vennby/ChatGPT-University/blob/main/HTML/Module%207.md"><< Previous</a></p>
<p align="center"><a href="https://github.com/vennby/ChatGPT-University/blob/main/HTML/Handout.md">Handout</p>
<p align="right"><a href="https://github.com/vennby/ChatGPT-University/blob/main/HTML/Module%209.md">Next >></p>
