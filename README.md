# Admission_Enquiry_Form
## Date: 07/07/2025

## Objective:
To design a simple Admission Enquiry Form using basic HTML that collects student details such as name, contact, program of interest, and a message for further communication.

## Tasks:
#### 1. Set Up the HTML Structure:
Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document structure.
Set the ```<title>``` as "Admission Enquiry Form".

#### 2. Add a Page Heading:
Use ```<h1>``` to title the page as “Admission Enquiry”.

#### 3. Create the Form Layout:
Use the ```<form>``` tag to wrap all input elements. Set method="post" for structure.

#### 4. Add Input Fields:
Include the following fields using appropriate HTML elements:

Full Name

Email Address

Phone Number 

Program of Interest 

Message

#### 5. Add Submit and Reset Buttons:
Use submit and reset at the bottom of the form.

#### 6. Use HTML-only:
No CSS or JavaScript is to be included. Focus on structure and accessibility.

## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saveetha Engineering College - Admission Enquiry</title>

</head>
<body>
    <h1 align="center">Admission Enquiry Form</h1>
    <form align="center">
        <label>Full Name:</label>
        <input type="text">
        <br>
        <br>
        <label>Email Address:</label>
        <input type="email">
        <br>
        <br>
        <label>Mobile Number:</label>
        <input type="tel">
        <br>
        <br>
        <label>Gender:</label>
        <input type="radio">
        <label>FEMALE</label>
        <input type="radio">
        <label>MALE</label>
        <input type="radio">
        <label>OTHERS</label>

        <br>
        <br>
        <label>Date of birth:</label>
        <input type="date">
        <br>
        <br>
        <label>Department Interested:</label>
        <select name="dept">
            <option value="CSE">CSE</option>
            <option value="ECE">ECE</option>
            <option value="MECH">MECH</option>
        </select>
        <br>
        <br>
        <label>Academic Qualification:</label>
        <textarea></textarea>
        <br>
        <br>
        <label>Address:</label>
        <textarea></textarea>
        <br>
        <br>
        <label>Mode of Contact:</label>
        <input type="checkbox">Email
        <input type="checkbox">Phone
        <br>
        <br>
        <button type="submit">Submit</button>


    </form>
    
</body>
</html>
```
## Output:
![image](https://github.com/user-attachments/assets/8b215e75-9850-48bd-8eda-0e002e34f46a)

## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
