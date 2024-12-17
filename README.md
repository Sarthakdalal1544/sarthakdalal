# sarthakdalal
/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    line-height: 1.6;
    color: #333;
}

/* Navigation Bar */
header {
    background: #0073e6;
    color: #fff;
    padding: 10px 0;
    position: sticky;
    top: 0;
    z-index: 1000;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 90%;
    margin: 0 auto;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin: 0 10px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

.logo {
    font-size: 1.5em;
    font-weight: bold;
}

/* Section Styling */
.section {
    padding: 50px 20px;
    text-align: center;
}

#home {
    background: #f4f4f4;
    padding: 100px 20px;
}

#home h1 span {
    color: #0073e6;
}

/* Projects Section */
.projects-container {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}

.project-card {
    background: #fff;
    padding: 20px;
    border: 1px solid #ddd;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    width: 300px;
    border-radius: 5px;
}

.project-card h3 {
    margin-bottom: 10px;
}

.project-card a {
    color: #0073e6;
    text-decoration: none;
    font-weight: bold;
}

/* Footer */
footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}
