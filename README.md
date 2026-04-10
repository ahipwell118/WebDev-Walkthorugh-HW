# WebDev-Walkthorugh-HW
<!DOCTYPE html>
<html>
<head>
    <title>Homer Simpson Resume</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <div class="header">
        <div class="nav">
            <a href="index.html">Home</a> | 
            <a href="resume.html">Resume</a> | 
            <a href="about.html">About Me</a>
        </div>
    </div>

    <div class="container">
        
        <div class="sidebar">
            <p><strong>Homer Simpson</strong></p>
            <p>Nuclear Safety Inspector<br>
            Springfield Nuclear Powerplant<br>
            Springfield, State, 55555</p>
            <a href="https://en.wikipedia.org/wiki/Homer_Simpson">See my Wikipedia Page.</a>
        </div>

        <div class="main-text">
            <img src="homer.png" alt="Homer Simpson" width="100">
            <p><strong>Mission Statement:</strong> My goal is to become a blockchain developer...</p>
            
            <ol>
                <li><strong>Education</strong>
                    <ul>
                        <li>Brigham Young University MISM</li>
                        <li>Brigham Young University BSIS</li>
                    </ul>
                </li>
                <li><strong>Skills</strong>
                    <ul>
                        <li>Database design development</li>
                        <li>SQL, Tableau, Excel, VBA</li>
                        <li>HTML and CSS</li>
                    </ul>
                </li>
            </ol>
        </div>
    </div>

</body>
</html>

/* Fixed Navigation Bar */
.header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background-color: white;
    border-bottom: 1px solid #ccc;
    text-align: right;
    padding: 10px;
    z-index: 100; /* Keeps it above everything else */
}

/* Add space at the top so content doesn't hide under the header */
body {
    padding-top: 50px;
    font-family: Arial, sans-serif;
}

/* Sidebar floated to the right */
.sidebar {
    float: right;
    width: 20%;
    border-left: 1px solid #ccc;
    padding: 20px;
    height: 100vh;
    font-size: 0.9em;
}

/* Main text area */
.main-text {
    width: 70%;
    padding: 20px;
}

/* Style the links */
a {
    color: blue;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
    color: red; /* Link state change from Chapter 24 */
}
