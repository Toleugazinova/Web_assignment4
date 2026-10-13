Assignment 4
Amina Toleugazinova IT-2513
Part 1
Task 0
I created a contact form with Name, Email, Message, and Submit fields. Each input has an associated label. The form uses standard HTML elements.
![alt text](<Task 0.png>)


Task 1
I added built-in validation attributes to the contact form:
required - for the Name and Email fields;
type="email" - to check the email format;
maxlength="30" - to limit the name length.
![alt text](<Task 1.png>)
![alt text](<Part 1.png>)

Part 2
Task 2
I recreated the contact form using Bootstrap classes. The Bootstrap grid arranges fields responsively, and placeholders explain what users should enter.
![alt text](<Task 2.png>)

Task 3
I added valid-feedback and invalid-feedback messages. JavaScript checks fields using checkValidity() and adds is-valid or is-invalid classes to show feedback. The Bootstrap contact form uses novalidate so that custom visual feedback can be displayed instead of the browser's default validation pop-ups.
![alt text](<Task 3.png>)
![alt text](<Task 3 java.png>)
![alt text](<Part 2.png>)

Part 3
Task 4
I created a responsive registration form. The form checks required fields, email format, and a minimum password length of eight characters. JavaScript checks whether both passwords match by using setCustomValidity(). It also checks the gender selection and displays feedback. When the form is valid, a success message appears. The Reset button clears the fields and validation feedback.
![alt text](<Task 4.png>)
![alt text](<Part 3.png>)