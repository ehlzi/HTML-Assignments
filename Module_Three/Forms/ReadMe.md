# Forms

Forms are a part of everyday life. When we use a physical form in real life, we write down information and give it to someone to process. Think of the times you’ve had to fill out information for various applications like a job, or a bank account, or dropped off a completed suggestion card — each instance is a form!

Just like a physical form, an HTML `<form>` element is responsible for collecting information to send somewhere else. Every time we browse the internet we come into contact with many forms and we might not even realize it. There’s a good chance that if you’re typing into a text field or providing an input, the field that you’re typing into is part of a `<form>`!

In this lesson, we’ll go over the structure and syntax of a `<form>` and the many elements that populate it.

-----

The purpose of a `<form>` is to allow users to input information and send it.

The `<form>`‘s action attribute determines where the form’s information goes.

The `<form>`‘s method attribute determines how the information is sent and processed.

To add fields for users to input information we use the <input> element and set the type attribute to a field of our choosing:

- Setting type to "text" creates a single row field for text input.

- Setting type to "password" creates a single row field that censors text input.

- Setting type to "number" creates a single row field for number input.

- Setting type to "range" creates a slider to select from a range of numbers.

- Setting type to "checkbox" creates a single checkbox which can be paired with other checkboxes.

- Setting type to "radio" creates a radio button that can be paired with other radio buttons.

- Setting type to "list" will pair the <input> with a <datalist> element if the id of both are the same.

- Setting type to "submit" creates a submit button.

A `<select>` element is populated with `<option>` elements and renders a dropdown list selection.

A `<datalist>` element is populated with `<option>` elements and works with an `<input>` to search through choices.

A `<textarea>` element is a text input field that has a customizable area.

When a `<form>` is submitted, the name of the fields that accept input and the value of those fields are sent as name=value pairs.

Using the `<form>` element in conjunction with the other elements listed above allows us to create sites that take into consideration the wants and needs of our users. 

### Click [here](https://codepen.io/ehlzi/details/oNdNRxm) for a live preview.
