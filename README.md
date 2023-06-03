# EXPERIMENT-03
# <p align="center"> WEB PORTFOLIO USING HTML & CSS </P>

## AIM: 
To create a web portfolio/cv by using html & css.
     
## ALGORITHM:

### STEP 1:
Create a folder and index.html

### STEP 2:
Write the code for both html and css

### STEP 3:
Connect the css into html by the syntax

### STEP 4:
Create the folder images and give the correct path

### STEP 5:
Run the program.

## PROGRAM:

### index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume-Suganya Parthiban</title>
    <link rel="stylesheet" href="assets/css/style.css">
   <style>
    * {
  max-width: 2000px;
  margin: auto;
}
</style>
</head>
<body class="screen"> 
  
  <div class="tittle">
    <h1 style="text-align:center;">P.Suganya</h1>
    <h2 style="text-align:center;">Prefinal year student</h2>
    <div class="vertical"></div>
    <div class="obj">
      <h3>About me</h3>
            <p>Aspiring and Enthusiastic computer programmer and proven problem solving and troubleshooting skills. Seeking an entry-level programmer or
              coder position to continue expanding my knowledge of different
              languages and systems.</p>
    </div>
    <div class="skill">
      <p style="text-align:left;"><b>Area of Expertise</b></p>
     <ul style="text-align:left;">
      <li>Machine Learning</li>
      <li>Android</li>
      <li>Deep Learning</li>
      <li>Data Science</li>
      <li>Artificial Intelligence</li>
      <li>Web Technology</li>
      <li>Digital Image Processing</li>
     </ul>
    </div>
    <div class="project">
      <p style="text-align:left;"><b>Projects</b></p>
      <ul style="text-align:left;">
        <li><b>Simple Calculator</b> - Using C developed a simple
          calculator.</li>
        <li><b>Woman Safety SOS App</b> – Developed an Android app for Woman safety.</li>
        <li><b>Gender Classification</b> – Using deepface created a model for classifying gender.</li>
        <li><b>Object Detection</b> – Created a own dataset of images and evaluted an image having any object or not.</li>

      </ul>
      </div>
  </div>
  <div class="contact">
    <p style="text-align:left;"><b>Contact</b></p>
    <ul>
      <li><a class="mail" href = "mailto: suganya.parthiban2002@gmail.com">Mail - suganya.parthiban@gmail.com   </a></li>
      <li><a class="phone" ><i class="contact-icon fas fa-phone"></i>+919894191816 </a></li>
      <li><a class="linked" href="https://www.linkedin.com/in/suganya-parthiban-52254224b/" target="_blank"><i class="contact-icon fab fa-linkedin"></i>LinkedIn</a></li>
      <li><a class="git" href="https://github.com/Sugan2002" target="_blank"><i class="contact-icon fab fa-linkedin"></i>GitHub</a></li>
    </ul>
  </div>
  <div class="edu">
  <p style="text-align:left;"><b>Education</b></p>
  <ul style="text-align:left;">
    <li><b>B.TECH - Artificial Intelligence And Data Science</b> – 85% (till 4th sem) from Saveetha Engineering College(Anna University affiliated), Chennai.</li>
    <li><b>HSC</b> – 70% from Kendriya Vidhyalaya, INS Rajali, Arakkonam.
        </li>
    <li><b>SSLC</b> – 75% from Navy Children School, INS Rajali, Arakkonam.</li>
  </ul>
  </div>
  <div class="strength">
    <p style="text-align:left;"><b>My Strengths</b></p>
  <ul style="text-align:left;">
    <li>Confidence</li>
    <li>Team Work</li>
    <li>Time Management</li>
    <li>Good Communication</li>
  </ul>
  </div>
  
</body>
</html>
```

### style.css
```css
.screen {
    background-color: #b79f84;
    background-repeat:no-repeat;
    
}



.contact{
    margin-left: 20px;
    margin-top: 20px;
    padding: 20px;
    width: 300px;
    background-color: var(--primary-color);
    border: 3px solid var(--secondary-color);
}
 
.skill {
    float: right; 
    margin-left: 226px;
    margin-top: 20px;
    padding: 20px;
    width: 300px;
    background-color: var(--primary-color);
    border: 3px solid var(--secondary-color);
}

.project{
    float: right; 
    margin-left: 226px;
    margin-top: 20px;
    padding: 20px;
    width: 350px;
    background-color: var(--primary-color);
    border: 3px solid var(--secondary-color);
}

.obj {
    margin-left: 226px;
    margin-top: 20px;
    padding: 20px;
    width: 750px;
    background-color: var(--primary-color);
    border: 3px solid var(--secondary-color);
}



:root {
    --primary-color: #E6DDC6;
    --secondary-color: #C2B8A3;
    --accent-color: #A19882;
  }

.edu {
    line-height: 1.5em;
    margin-left: 20px;
    margin-top: 20px;
    padding: 20px;
    width: 300px;
    background-color: var(--primary-color);
    border: 3px solid var(--secondary-color);
    
    
}

.strength {
    margin-left: 20px;
    margin-top: 20px;
    padding: 20px;
    width: 300px;
    background-color: var(--primary-color);
    border: 3px solid var(--secondary-color);
}
.tittle {
    width: 1570px;
    height: 100px;
    border: 3px solid #585b45;
    background-color: var(--accent-color);
    display: grid;
    grid-template-columns: 1fr;
    gap: 20px;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
  }
``` 
  
## OUTPUT:

![image](https://github.com/Sugan2002/mern-PORTFOLIO-03/assets/77089743/a4122b16-eb1f-4444-b72c-ce184c9dbf65)

## RESULT:

   Thus, the web portfolio/cv is developed successfully using HTML & CSS.
