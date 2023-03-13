## Resume-Generator

Resume generator from a HTML form. </br>

#### HTML file
Creates a basic HTML form for generating a resume. <br>
The form contains various input fields for personal details, education, skills, and employment experience. <br>
The form also includes a button to create the resume. 
<hr>
#### Js file 
```createResume()``` function retrieves the data from the form elements on a webpage and uses that data to generate an HTML document. <br>

```document.getElementById()``` -> retrieve the values entered into input fields, including "fullName", "city", "telePhone", "email", "website", "careerSkills", "personalInfo", and "educationDeets". <br>
``` myText``` -> strig variable holds values of fullName, city, phone, email, and website are added to myText in the appropriate places to generate the header of the document. <br>


If a ```startDate``` value is present -> an employment section is added to myText (including startDate, endDate, and employment values). <br>

```window.open()``` ->  opens the generated HTML in a new window with the name "myResume".




