### HTML `<input>` tag

The HTML `<input>` tag defines the field where the user can enter data. For example :

```HTML
<input type="text" name="firstname">
```

**Browser Output :**

<input type="text" name="firstname">

Here,

- type - determines the type of input the `<input>` tag takes
- name - specifies the name of the input which is what the data is named as when submitting the data to a server.

#### Different Input Types

1. **Text**: `<input type="text">` - Used for single-line text input.
2. **Password**: `<input type="password">` - Similar to text input, but the entered characters are masked for security.
3. **Checkbox**: `<input type="checkbox">` - Allows users to select one or more options from a list of options.
4. **Radio Button**: `<input type="radio">` - Allows users to select one option from a list of options.
5. **Submit Button**: `<input type="submit">` - Submits the form data to the server.
6. **Reset Button**: `<input type="reset">` - Resets all form fields to their initial values.
7. **File**: `<input type="file">` - Allows users to select and upload files.
8. **Hidden**: `<input type="hidden">` - Hides the input from the user interface but includes it in form submission.
9. **Number**: `<input type="number">` - Allows users to enter a numerical value.
10. **Date**: `<input type="date">` - Allows users to select a date from a calendar.
11. **Time**: `<input type="time">` - Allows users to select a time.
12. **Email**: `<input type="email">` - Validates that the input value is an email address.
13. **URL**: `<input type="url">` - Validates that the input value is a URL.
14. **Tel**: `<input type="tel">` - Validates that the input value is a telephone number.
15. **Search**: `<input type="search">` - Represents a text field for entering search queries.
16. **Color**: `<input type="color">` - Allows users to select a color from a color picker.
17. **Range**: `<input type="range">` - Allows users to select a value from a range using a slider.
18. **Datetime**: `<input type="datetime">` - Allows users to enter a date and time (not widely supported).
19. **Datetime-local**: `<input type="datetime-local">` - Allows users to enter a date and time (local time zone).
20. **Month**: `<input type="month">` - Allows users to select a month and year from a dropdown.
21. **Week**: `<input type="week">` - Allows users to select a week and year from a dropdown.
22. **number** - Define a field for entering a number (We can also set restrictions on what numbers are accepted)

These input types provide various functionalities and validation features to handle different types of user input in HTML forms.