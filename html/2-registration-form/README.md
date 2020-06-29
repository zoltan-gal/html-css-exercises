# User registration form.

Build a simple user registration form with using HTML form elements. Your form should contain the following fields:
 - First and sure name input fields, next to each other
 - Gender choice radio button with to items: male and female
 - Birthdate date picker
 - Email address box
 - Phone number input field
 - User address:
   - Country drop-down list: include at least five countries and set one to be selected by default
   - Post code input field
   - Address input field
   - Town input field 
 - Free text area for optional notes
 - A submit button that posts the form
 - A reset butting that clears the form

Although there are no constraints on the design, form should look aesthetic and clear.
Choose self-descriptive names for field labels.

## Play with your form

Set URL for the action attribute to `/user-registration` and the method attribute type to `GET`.

Observe of what happens when submitting form. Open your page in browser, fill the form fields out and submit it. Where can you find the form values being sent? (Hint: inspect the URL)

Modify the method type to `POST` and submit form again what differences you have experienced?

## Adding extra constraints

By adding constraints onto input fields, you will see how to refine the form.

### Compuslory inputs

Use `required` attributes on some input fields and check what happens when you try to submit the form without supplying them with value.

### Character limits

Restrict the input values to maximum 30-character long. Use `maxlength` attribute to set limit on text fields.

### Min-max value

Set a minimum and a maximum date boundaries on the birth date field. Look for how to use `min` and `max` attributies.

## Extra exercises

 - Set `autofocus` attribute on the first field and see how it works.
 - Add more different types of fields to your form and see how those look and work by default.
