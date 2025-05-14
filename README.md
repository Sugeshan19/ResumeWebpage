# Create your own resume webpage

## Aim :
  To create a web page for personal resume

## Procedure:

 1.open visual studio code and create a project folder 
 2.create a html file and css file 
 3.paste the code

 # Program:
 HTML CODE 
 ```
 <head>
    <title>My Resume</title>
    <link rel="stylesheet" href="style.css">
    <script>
        function themeToggle() {
            document.body.classList.toggle("dark");
        }
    </script>
</head>

<body class="body">
    <button class="theme-btn" onclick="themeToggle()">Theme</button>
    <center>
        <img src="assets/pic.jpg" alt="profile" class="image">
    </center>
    <h2 class="name">NAME</h2> 
    <h4 class="name">Frontend Developer</h4>
    <br>
    <hr>

    <h3 class="topics">Executive Summary</h3> 
    <p class="epara">Motivated and detail-oriented front-end developer with hands-on experience building 
        responsive web applications using HTML, CSS, JavaScript, React, and Bootstrap.<br>
        Recently developed a fully functional e-commerce website using React, receiving
        positive feedback for clean design and user experience. Eager to contribute to<br>
        dynamic development teams and grow in a professional front-end role.
    </p>
    <hr>


    <h3 class="topics">Education </h3>
    <p class="epara">
        Bachelor’s of Engineering (CSE)</strong><br/>
        ABC Engineering College (2024–2028)<br/>
        CGPA: 8.5<br/>
        Activities: Coder’s Club, Volleyball
    </p>
    <hr>
    
    
    <h3 class="topics">Internships</h3>
      <p class="epara">
        <strong>React Intern</strong> – Spark Solutions (Jan–Mar 2025)</p>
      <ul>
        <li>Built responsive UIs with React.js, HTML, CSS, JavaScript</li>
        <li>Used React Hooks, Context API, integrated REST APIs</li>
        <li>Practiced Git, Agile workflows, performance optimization</li>
      </ul>

      <p class="epara">
      <strong>Web Developer Intern</strong> – Rinex.AI (Mar–Apr 2025)</p>
      <ul>
        <li>Styled responsive pages using HTML, CSS, JavaScript</li>
        <li>Improved web performance & collaborated with mentors</li>
      </ul>
    <hr>


    <h3 class="topics">Skills</h3>
    <ul>
        <li>React</li>
        <li> HTML/CSS</li>
        <li> JavaScript</li>
        <li> Bootstrap</li>
        <li> Typography</li> 
        <li> Python</li>

    </ul>
    <ol>        
            <li>Version Control: Git, GitHub</li>
            <li>Tools: Visual Studio Code</li>
            <li>Soft Skills: Teamwork, Communication, Problem-solving</li>
    </ol>

    <footer>
        <div class="footer">
        <h3>Contact</h3>
        <p><strong>Email: sugeshans19@gmail.com</strong> <br/>
        <strong>Phone: +91 6382111708</strong> <br/>
        Github: <a href="https://github.com/Sugeshan19">github.com/Sugeshan19</a> <br/>
        LinkedIn: <a href="https://www.linkedin.com/in/sugeshan-s-5a65a4303/">linkedin.com/in/sugeshan-s</a> <br/>
    </div>
    </footer>

</body>
```
CSS CODE
```
body {
    font-family: 'Segoe UI', sans-serif;
    background-color:white
    color: #222;
    padding: 30px;
    line-height: 1.6;
}
.center-header {
    display: flex;
    align-items: center;
    gap: 20px;
    margin-bottom: 20px;
}  
.image {
    width: 120px;
    height: 120px;
    object-fit: cover;
    border-radius: 50%;
    border: 3px solid #333;
}
.name {
    text-align: center;
    margin-top: 10px;
    font-weight: 600;
}
.name + h4 {
    text-align: center;
    color:whitesmoke
    margin-bottom: 20px;
}
.topics {
    font-size: 20px;
    color: #333;
    margin-top: 30px;
    margin-bottom: 10px;
    border-left: 5px solid #333;
    padding-left: 10px;
}
.epara {
    padding: 15px;
    border-left: 4px solid #007acc;
    border-radius: 5px;
}
.p {
    margin-top: 10px;
    border-left: 4px solid #007acc;

}
footer {
    margin-top: 40px;
    padding: 20px;
    background-color: rgb(119,119,233);
    border-top: 2px solid #ccc;
    text-align: center;
}  
footer a {
    color: white;
    text-decoration: none;
  }
  
footer a:hover {
    text-decoration: underline;
}
hr {
    border: none;
    border-top: 1px solid #ccc;
    margin: 20px 0;
}
  
.image {
      margin-bottom: 10px;
}
  
  



    .theme-btn {
        position: fixed;
        top: 20px;
        right: 20px;
        padding: 8px 16px;
        background-color: white;
        color: black;
        border-radius: 10px;
        cursor: pointer;
        hover: {
            background-color: black;
            color: white;
        }
      }

      body.dark {
        background-color: black;
        color: white;
      }
      
      body.dark a {
        color: #90caf9;
      }
      
      body.dark .topics {
        color: #90caf9;
      }
      
      body.dark footer {
        background-color: rgb(119, 119, 233);
        color: #f0f0f0;          
        border-top: 1px solid #444; 
      }
      body.dark .footer a {
        color:blue;
      }
```
# OUTPUT

  ![alt text](<Screenshot 2025-05-14 131350.png>)



![alt text](<Screenshot 2025-05-14 131428.png>)



![alt text](<Screenshot 2025-05-14 131450.png>)