<!DOCTYPE html>
<html>
<head>
    <title>My CV</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        .container {
            max-width: 800px;
            margin: 30px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            color: #333;
        }

        .section {
            margin-bottom: 20px;
        }

        .section h2 {
            color: #555;
            margin-bottom: 10px;
        }

        .section p {
            margin: 0;
        }

        .section ul {
            margin: 0;
            padding: 0;
            list-style-type: none;
        }

        .section ul li {
            margin-bottom: 5px;
        }

        .section ul li:before {
            content: "\2022";
            color: #999;
            display: inline-block;
            width: 1em;
            margin-left: -1em;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>My CV</h1>

        <div class="section">
            <h2>Personal Information</h2>
            <p>Name: John Doe</p>
            <p>Email: john@example.com</p>
            <p>Phone: 123-456-7890</p>
            <p>Address: 123 Main St, City, Country</p>
        </div>

        <div class="section">
            <h2>Education</h2>
            <ul>
                <li>Bachelor's Degree in Computer Science - University XYZ</li>
                <li>High School Diploma - ABC High School</li>
            </ul>
        </div>

        <div class="section">
            <h2>Work Experience</h2>
            <ul>
                <li>Software Engineer - Company XYZ (2018 - Present)</li>
                <li>Intern - Company ABC (2017 - 2018)</li>
            </ul>
        </div>

        <div class="section">
            <h2>Skills</h2>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>PHP</li>
            </ul>
        </div>
    </div>
</body>
</html>
