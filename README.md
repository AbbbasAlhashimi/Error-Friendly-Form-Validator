# Error-Friendly-Form-Validator
Error Friendly Form Validator using Vanilla JS
The form takes 5 entries: Username, Full Name, Email, Password, and Password Confirmation. Each entry has a type, id, and a placeholder value. Along with every entry, there is an error friednly validator triggered upon submitting an entry via the <b>Submit Button</b>.<br>
Each Entry has two potential entry states: Success and Error. Along with input states, there are styling conditions [.form-control.success input] and [.form-control.error input] while error messages remain hidden until inputs are checked.<br>
The Script begins with constant variable initiation linking them with the DOM Entries by their id(s).<br>
There are 4 Functions along with an event Listener which operate as an automatic input validator.<br>
<b> The Functions are as follows:<b><br>
<ul>
  <li><b>showError</b>: The function takes two values: Inputs and Message. This function is triggered by the event listener then change the field border color to red and display the error message.</li>
  <li><b>showSuccess</b>: The function takes a single input. It is triggered by the event listener and changes the input box border's color to green.</li>
  <li><b>isValidEmail</b>: The function takes a single input</li>
  <li><b>checkRequired</b>:</li>
  
 <li><b>checkLength</b>:</li>
  <li><b>checkLength</b>:</li>
  <li><b>checkPasswordsMatch</b>:</li>
  <li><b>getFieldName</b>:</li>
  
</ul>
