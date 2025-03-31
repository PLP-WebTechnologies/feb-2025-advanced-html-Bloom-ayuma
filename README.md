# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.

 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Elements Demo</title>
</head>
<body>
    <!-- Ordered List with Roman Numerals -->
    <h2>Ordered List</h2>
    <ol type="I">
        <li>First Item</li>
        <li>Second Item</li>
        <li>Third Item</li>
        <li>Fourth Item</li>
        <li>Fifth Item</li>
    </ol>
    
    <!-- External Image -->
    <h2>External Image</h2>
    <img src="https://www.pexels.com/photo/beautiful-landscape-1234567/" alt="Pexels Image" width="500">
    
    <!-- Contacts Table -->
    <h2>Contacts Table</h2>
    <table border="1">
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Linda Ayuma</td>
                <td>Kasarani ICIPE Road</td>
                <td>0114054527</td>
                <td>lindaayuma01@gmail.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Elm St</td>
                <td>+9876543210</td>
                <td>jane@gmail.com</td>
            </tr>
            <tr>
                <td>Michael Johnson</td>
                <td>789 Oak St</td>
                <td>+1122334455</td>
                <td>michael@gmail.com</td>
            </tr>
            <tr>
                <td>Emily Brown</td>
                <td>321 Pine St</td>
                <td>+5566778899</td>
                <td>emily@example.com</td>
            </tr>
            <tr>
                <td>David Wilson</td>
                <td>654 Maple St</td>
                <td>+6677889900</td>
                <td>david@gmail.com</td>
            </tr>
        </tbody>
    </table>
    
    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="#" method="POST">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Linda Ayuma" required>
        <br>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="lindaayuma01@gmail.com" required>
        <br>
        
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Lbuluma01@bloom#" required>
        <br>
        
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" value="2003-07-05" required>
        <br>
        
        <label for="gender">Gender:</label>
        <input type="radio" id="female" name="gender" value="Female" checked> Female
        <input type="radio" id="male" name="gender" value="Male"> Male
        <input type="radio" id="other" name="gender" value="Other"> Other
        <br>
        
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="Kenya" selected>Kenya</option>
            <option value="UK">UK</option>
            <option value="Canada">Canada</option>
            <option value="Australia">Australia</option>
        </select>
        <br>
        
        <label>Interests:</label>
        <input type="checkbox" name="interests" value="Coding" checked> Coding
        <input type="checkbox" name="interests" value="Music" checked> Music
        <input type="checkbox" name="interests" value="Sports"> Sports
        <br>
        
        <button type="submit">Register</button>
    </form>
</body>
</html>
