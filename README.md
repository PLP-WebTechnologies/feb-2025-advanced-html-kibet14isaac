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
- <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Practice</title>
</head>
<body>

    <h2>Numeral List</h2>
    <ol type="I">
        <li>Item One</li>
        <li>Item Two</li>
        <li>Item Three</li>
        <li>Item Four</li>
        <li>Item Five</li>
    </ol>

    <h2>External Image</h2>
    <img src="https://images.pexels.com/photos/2102416/pexels-photo-2102416.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Nature Image" width="500">

    <h2>Contact Table</h2>
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
                <td>John Doe</td>
                <td>123 Main St</td>
                <td>123-456-7890</td>
                <td>john.doe@gmail.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Oak Ave</td>
                <td>987-654-3210</td>
                <td>jane.smith@gmail.com</td>
            </tr>
             <tr>
                <td>Alice Johnson</td>
                <td>789 Pine Ln</td>
                <td>555-123-4567</td>
                <td>alice.johnson@gmail.com</td>
            </tr>
            <tr>
                <td>Bob Williams</td>
                <td>101 Elm Rd</td>
                <td>111-222-3333</td>
                <td>bob.williams@gmail.com</td>
            </tr>
            <tr>
                <td>Eva Brown</td>
                <td>202 Maple Dr</td>
                <td>444-555-6666</td>
                <td>isaac@gmail.com</td>
            </tr>
        </tbody>
    </table>

    <h2>Registration Form</h2>
    <form action="#" method="post">
        <fieldset>
            <legend>User Registration</legend>

            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

            <label for="password">Password:</label><br>
            <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>

            <label for="dob">Date of Birth:</label><br>
            <input type="date" id="dob" name="dob" required><br><br>

            <label for="country">Country:</label><br>
            <select id="country" name="country">
                <option value="">Select a country</option>
                <option value="usa">USA</option>
                <option value="canada">Canada</option>
                <option value="uk">UK</option>
                <option value="australia">Australia</option>
            </select><br><br>

            <p>Gender:</p>
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">Male</label><br>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label><br>
            <input type="radio" id="other" name="gender" value="other">
            <label for="other">Other</label><br><br>

            <p>Interests:</p>
            <input type="checkbox" id="sports" name="interests" value="sports">
            <label for="sports">Sports</label><br>
            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label><br>
            <input type="checkbox" id="reading" name="interests" value="reading">
            <label for="reading">Reading</label><br><br>

            <input type="submit" value="Register">
        </fieldset>
    </form>

</body>
</html>

Happy Coding! 💻✨
