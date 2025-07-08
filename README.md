# Profile Page
## Date:
## Objective:

To design a simple Profile Page using HTML that displays a user's profile image, name, headings, and a short bio, suitable for personal or academic purposes.

## Tasks:

#### 1. Set Up the HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the basic structure.

Add an appropriate <title> such as "My Profile".

#### 2. Add Page Headings:

Insert a main heading using ```<h1>``` for the user's name.

Include subheadings such as ```<h2>``` or ```<h3>``` for titles or roles (e.g., "Student", "Web Developer").

#### 3. Insert a Profile Image:

Use the ```<img>``` tag to display the user’s profile picture.

Add alt text and set basic attributes like width and height.

#### 4. Include a Short Bio Section:

Add a paragraph using <p> to provide a short introduction or biography.

The content may include education, interests, or a personal statement.

#### 5. Organize Content Using HTML Elements:

Use ```<section>```, ```<div>```, or ```<article>``` for logical grouping.

Add a horizontal line (```<hr>```) to separate sections.

#### 6. Keep the Design HTML-Only:

Do not use CSS or JavaScript.

Focus on semantic HTML and readability.
## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admission Enquiry-SEC</title>
</head>
<body>
    <form>
        <h1>SAVEETHA ENGINEERING COLLEGE</h1>
        <h2>Admission enquiry form</h2>
        <label>Full Name</label> <br><input type="text">
        <br><br>
        <label>Email Id</label><br> <input type="email">
        <br><br>
        <label>Phone Number</label> <br> <input type="tel">
        <br><br>
        <label>D.O.B</label><br><input type="date">
        <br><br>
        <label name="gender">Gender: </label>
        <input type="radio" name="gender">Male
        <input type="radio" name="gender">female
        <input type="radio" name="gender">Others
        <br><br>
        <label>Choose Department : </label>
        <select>
          <option>ECE</option>
          <option>CSE</option>
          <option>EEE</option>
          <option>AIML</option>
          <option>MECH</option>
          <option>EIE</option>
          <option>AIDS</option>
        </select>
        <br><br>
        <label>Academic Qualification</label><br>
        <textarea rows=5 cols="30"></textarea>
        <br><br>
        <label>Address</label><br>
        <textarea rows=5 cols="30"></textarea>
        <br><br>
        <label>Preferred Mode of Contact : </label>
        <input type = "checkbox">Email
        <input type = "checkbox">Phone
        <br><br>
        <button>Submit</button>
        <button type="reset">Clear</button>
    </form>
</body>
</html>
```
## Live WEB PAGE:
https://samjxdev.github.io/Profile_page/
## Output:
![image](https://github.com/user-attachments/assets/dfaf36ac-e7c6-414a-ae47-957e5bacf99b)


## Result:
A simple Profile Page using HTML that displays a user's profile image, name, headings, and a short bio, suitable for personal or academic purposes is designed successfully.
