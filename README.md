<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
    <title>PORTFOLIO</title>
    <link rel="stylesheet" type="text/css" href="MYSTYLE.css">
    <script>
function youhave() {
  fname = document.forms[0].fname.value;
  alert("Hello " + fname + "! You have send a message/feedback!!");
}
</script>
</head>
<body>
 <section class="page" id="home">

   <h1>FOSTECH PORTFOLIO WEBSITE</h1>
     <p> <ul>
           <li><a href="#home" id="scroll-down">HOME</a></li>
            <li><a href="#about" id="scroll-down">ABOUT</a></li>
           <li> <a href="#skills" id="scroll-down">SKILLS</a></li>
            <li><a href="#contact" id="scroll-down">CONTACT ME</a></li>
            <li><a href="#education" id="scroll-down">EDUCATION QUALIFICATION</a></li>
        </ul></p>

     <div class="row" style="padding:0px;margin-top:60px;">
    <div class="column side">
        <h2>MY PROFILE</h2><br>
        <p><img src="pic/pro.png"></p>
        <p>FOSTER MAKONOMBERA</p><br>
        <p> STUDENT AT MUST</p><br>
        <p>WEB DEVELOPER</p><br>
        <p>BLANTYRE</p><br>
        <p>MALAWI</p>
    </div>
     <div class="column main">
     <br><h2>WELCOME TO MY PORTFOLIO WEBSITE</h2>
     <h3>HOME</h3>
         <p>This is Foster Makonombera,a student at Malawi University Of Science and Technology
         <br>doing bancherlors degree in Business Information Technology (BIT),i'm in third year of my study.
         <br>I'm passionate about website design and development </p><br>
         <p ><a href="pic/fostercv.pdf" download="cv" style="background-color:white;color:black;">DOWNLOAD CV</a></p><br>
        <br> <p><img src="pic/pro.png" width="400px" height="auto"></p>
     </div>
     </div>
  </section>

  <section class="page" id="about">
    <h2>ABOUT ME</h2>
    <p><img src="pic/pro.png"></p>
      <div class="about">
          <p><b>PERSONAL DETAILS:</b></p><br>
          <p>NAME: FOSTER MAKONOMBERA</p><br>
          <p>UNIVERSITY: MALAWI UNIVERSITY OF SCIENCE AND TECHNOLOGY</p><br>
          <p>PROGRAM: BANCHELOR'S DEGREE IN BUSINESS INFORMATION TECHNOLOGY</p><br>
          <p>YEAR OF STUDY: THIRD YEAR</p>
          <br><p><b>PERSONAL STATEMENT</b>
      <br>I am a self-motivated, innovative IT expert (web designer & developer,mobile app developer,data analyst etc) with an ability
          <br>to demonstrate energy, determination, and assurance to a high standard of work.</p>

      </div>
    <a href="#home" class="scroll-down">Go Back</a>
      <section/>
      <section class="page" id="skills">
    <h2> MY SKILLS</h2><br>
    <div class="skills">
        <p><b>WEBSITE DESIGN AND DEVELOPMENT</b>
        <br>I'm passionate website designer and developer,i do design and develops websites using HTML,CSS,JAVASCRIPT,
            <br>PHP and MYSQL.</p><br>
        <p><b>PROGRAMMING LANGUAGES</b>
            <br>I'm computer programmer proficient in different programming languages like<br>
            Java,Python,C++,PHP and Javascript.
        </p><br>
        <p><b>DATA ANALYSIS</b>
            <br>I have knowledge in data analysis tools,technigues,how to collect data,clean and translate it into
            <br>meaningiful insights to help business company to make best decision.
        </p><br>
        <p><b>APP DEVELOPMENT</b>
        <br>I'm passionate mobile App developer,I have knowledge,understanding and skills  in different frameworks for
           <br> mobile application development with their respective programming language.</p><br>
        <p><b>DATABASE SYSTEM</b>
            <br>I have knowledge and skills in database management, i do use MYSQL.
        <br></p><br>
    </div>
    <a href="#home" class="scroll-down">Go Back</a>
  </section>
       <section class="page" id="contact"><br>
    <h2>CONTACT ME</h2><br>
    <div class="contact">
        <p><img src="pic/EMAIL.png" width="30px" height="auto">fostermakonombera59@gmail.com</p><br>
        <p><img src="pic/wat.png" width="20px" height="auto">+265(0) 996 937 756</p><br>
        <form onsubmit="youhave()" action="#">
            <p><input type="text"  placeholder="your full name" name="fname" required></p><br>
        <p><input type="email" placeholder="email" required></p><br>
        <p><textarea name="message" cols="25" rows="5" placeholder="type message/feedback" required></textarea></p><br>
        <p><input type="submit" value="send"></p><br>
        <p><img src="pic/fb.png" width="20px" height="auto"><img src="pic/in.png" width="20px" height="auto"></p>
        </form>

    </div>
    <a href="#home" class="scroll-down">Go Back</a>
  </section>
       <section class="page" id="education" style="background-color:background-color:black;">
    <h2>EDUCATION QUALIFICATION</h2>
    <div class="education">
       <p><b>MALAWI UNIVERSITY OF SCIENCE AND TECHNOLOGY</b>
       <br>BUSINESS INFORMATION TECHNOLOGY (CURRENTLY) IN THIRD YEAR
       <br> FROM 2021-UP TO NOW</p>
        <p><b>AFRICAN DRONE AND DATA ACADAMY & MUST</b>
        <br>CERTIFICATE IN DRONE TECHNOLOGY
        <br>FROM FEBRUARY 2024-MAY 2024</p>
        <p></p>
    </div>
    <a href="#home" class="scroll-down">Go Back</a>
  </section>
      <footer> Copyright &copy;2024 Designed & developed by FOSTER MAKONOMBERA</footer>
</body>
</html>
