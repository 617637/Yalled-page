<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yalled's Resume</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="flex">
        <div class="container">
            <h2 id="Yayaname">Yalled Irakoze</h2>
            <p><a target="_self"  href="Welcome.html"> Welcome page</a> </p>
            <p><a target="_self" href="about me.html"> About me</a></p>
            <p><a target="_self" href="Myobjective.html">My Objectives</a></p>
            <p><a target="_self" href="Myprojects.html">My projects</a></p>
            <p><a target="_self" href="Competences.html">My Skills</a></p>
            <p><a target="_self" href="contact.html">My contacts</a></p>
        </div>
        <div>
            <h1>Learn more about Yalled here...</h1>
        </div>
    </div>
<br><br>
    <div id="aboume">
<h1>Who am I?</h1>
<div id="aboutme">
     <p> I am <b>Yalled Irakoze</b> who was born and raised in Burundi, in Kumoso Region. 
        I started my primary school at a local school on tehe same colline. I did my high school at <b>
        <em>Lycee d'Excellence Saint Joseph de Rusengo</em></b>in Ruyigi. After my high school, I applied to a leadership and english
        based program called <a target="_blank" href="https://www.tujenge.org/"><em>Tujenge Africa Foundation</em></a> in Burundi. Now I am pursuing my bachelor degree at ULT in Burundi
    </p>

    <p>If you want to learn more about my skills, click here <button id="moreon" onclick="readmore()">More</button></p>
</div>
<script>
      const userResponse = window.prompt("Do you want to continue? (Type 'yes' or 'no' or click OK/Cancel)");
      function readmore(){
            if (userResponse === null) {
                window.alert("You clicked Cancel. Leaving me alone!");
                console.log("User cancelled the prompt.");
            } else if (userResponse.toLowerCase() === "yes") { 
                console.log("Let's go!");
                window.alert("Great! Let's continue.");
            } else { 
                window.alert("Leave me alone!!");
                console.log("User chose not to continue or provided unexpected input.");
            }
        }
</script>
    </div>

<br><br><br>
 <img id="image" style=" width:600px; height: 400px; text-align: center;" src="DSC_0503.JPG" alt="yalledirakoze078">

<div id="Myobjective">
    <h1>My objectives: </h1>
    <h2>I. General Objective: </h2>
    <p>I plan to acquire a robust foundation in computer science and software development, 
        enabling me to innovate and implement effective technological solutions for 
        Burundi's pressing issues, particularly in data management and internet infrastructure.</p>
    <h2>II. SMART Objectives: </h2>
<ol>
    <li> <h2>Short term objective</h2></li>
    <p>By December 2025, I look forward to complete five online courses or certifications focusing on data structures,
         algorithms, a modern programming language, database management (SQL), 
         and web development fundamentals. I will achieve this by dedicating 15 hours per week to coursework
          and practical exercises, evidenced by course completion certificates and the creation 
          of two small portfolio projects demonstrating learned concepts.</p>
    <li><h2>Long Term Objective</h2></li>
    <p> Within five years (by June 2030),I envision to design, develop, and deploy at least one impactful
         software solution or system that demonstrably improves data accessibility or internet
          efficiency for a specific community or sector in Burundi. This project will be measurable 
          by user adoption rates (e.g., 500+ users), improved service metrics,
           or positive feedback from stakeholders, contributing directly to 
           mitigating Burundi's technological challenges.</p>
</ol>
</div>

<div id="Myprojects">
   <h1>My HTML Projects</h1>
  <ol>
    <li style="color: blue;"> My calculator here: <a target="_parent" href="Calculateur.html">Voir</a></li>
    <li style="font-size: large;"> See my clock right here: <a target="_parent" href="TempsReel.html">Voir</a></li>
    <li style="text-align: end;"> See this exercice: <a target="_top" href="Exercice.html">Voir</a></li>
  </ol> 
</div>

<div id="Myskills">
    <h1>I. Proficiency in Languages: </h1>
     <div class="Language">
<ol>
    <li>English</li>
    <li>French</li>
    <li>Swahili</li>
</ol>
     </div>

     
<h1>II. My soft skills</h1>
     <div class="Soft">
<ol>
    <li>Microsoft Office word</li>
    <li>Microsoft Office Excel</li>
    <li>HTML</li>
    <li>CSS</li>
    <li>JS</li>
    <li>Introduction to Python</li>
</ol>
    </div>
</div>

<div id="Mycontacts">
    <p>If you need me, Get in touch with me at 
    <ol>
        <li><a href="tel:+257 67427115">My phone number</a> Or, </li> 
        <li> <a href="mailto:yalledirakoze078@gmail.com">My email</a></li> 
    </ol></p>

    <h2 style=" border: 2px solid red; text-align: center;border-radius: 15px;
    background-color:rgb(202, 247, 4); margin-right: 1100px;">Contact form</h2>

    <div id="contact">
    <p>You can also choose to complete this form for an emergency, and send it.</p>
    <form id="ContactForm" >
        <label for="FirstName"> Your first name</label>
        <input type="text" name="FirstName" id="FirstName" placeholder="Your first name" required>
        <br>
        <br>
        <label for="LastName">Your last name</label>
        <input type="text" name="LastName" id="LastName" placeholder="Your last name" required>
        <br><br>
        <label for="Answer">Your request here</label>
        <textarea name="Answer" id="Answer" placeholder="Your request here...." required min="30" max="1000" ></textarea>
        <br><br>
        <button id="mit" type="submit" style="background-color: yellow;">Submit</button>
        <button type="reset" style="  background-color: rgb(245, 118, 131); color: blue;">Reset</button>
    </form>
    </div>
</div>

<br><br><br>
<p id="download">You can access my Resume by downloading it here: <b><a href="Yalled's Resume.pdf" download>My Resume</a> </b> </p>

</body>
</html>
