# portfolio-website
I have created it by using html and css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website</title>
    <link rel="stylesheet" href="style1.css">
</head>
<body>
    </div>
    <nav class="navbar">
        <div class="max-width">
            <div class="logo"><a href="#">MY<span> SPACE </span></a></div>
            <ul class="menu">
                <li><a href="#home" class="menu-btn">Home</a></li>
                <li><a href="#hobbies" class="menu-btn">Hobbies</a></li>
                <li><a href="#skills" class="menu-btn">Skills</a></li>
            </ul>   
        </div>
    </nav>

    <!-- home section starts here -->
    <section class="home" style="border-radius: 20px; background-color: #121212; height: 100vh;width: max-content;" id="home">
        <div class="max-width">
            <div class="home-content">
                <div class="text">Hey, my name is</div>
                <div class="text-1">SHIVAM GIRI</div>
                <div class="text">I have done my complete schooling from Kendiya Vidyalaya. I have always been an active student in high school. I have won medals in judo, athletics and basketball at regional sports meet. Currently I'm pursuing B.Tech in electrical engineering at Netaji Subhas University of technology. I am exploring all avenues liable to improve my learning curve in college. I have keen interest in coding too. Recently I've started my internship with Bhumi. My strengths are my analytical approach, interpersonal skills and my human touch to the situation. My goal is to create a successful start-up in tech world. In my free time I love to listen to soothing music and read novels. Thank you</div>
                <a href="hobbies.html" target="_blank">
                <button class="btn" style="background-color: rgba(63, 188, 238, 0.966);"> My hobbies </button>
                </a>
                <a href="skills.html" target="_blank">
                <button class="btn" style="background-color:rgba(63, 188, 238, 0.966);">Skills </button>
                </a>
                <div class="secondhalf">
                    <img src="/Users/shivamgiri/Desktop/img/shiv.jpg" style="border-radius: 20px;height: 400px; " alt="my image">
                </div>
            </div>
        </div>
    </section>

    <!-- my hobbies section starts here -->
    <section class="hobbies" style="background-color:rgb(228, 216, 216);border-radius: 20px;height: 100vh;" id="hobbies">
        <div class="max-width">
            <h2 class="title" style="border-radius: 20px; color: black;">My hobbies</h2>
            <div class="serv-content">
                <div class="card">
                    <div class="box">
                        <div class="text" style="background-color: skyblue;"><b>Reading self help books and novels.</b></div>
                        <img src="/Users/shivamgiri/Desktop/img/book.jpg" style="border-radius: 20px; height: 100px; width: 200px;align-content: flex-end;" alt="book image">
                        <ul style="background-color: pink; border-radius: 10px;">
                            <li>It improve My knowledge and help me in different walks of life.</li>
                            <li>Empowers me to empathize with other people.</li>
                        </ul>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        <div class="text" style="background-color: skyblue;"><b>Listning to music.</b></div>
                        <img src="/Users/shivamgiri/Desktop/img/music.jpg" style="border-radius: 20px;height: 100px;" alt="music img">
                        <ul style="background-color: pink;border-radius: 10px;">
                            <li>Improves my memory.</li>
                            <li>Improves my mood.</li>
                        </ul>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        
                        <div class="text" style="background-color: skyblue;"><b>Playing different sports.</b></div>
                        <img src="/Users/shivamgiri/Desktop/img/sports.jpg" style="border-radius: 20px;height: 150px;" alt="playing spoets">
                        <ul style="background-color: pink; border-radius: 10px;">
                            <li>kerps me fit and healthy.</li>
                            <li>Reduces my stress.</li>
                        </ul>
                     </div>
                </div>
               </div>
            </div>
        </div>
    </section>

  <!-- skill sec starts here-->
    <section class="skills" style="background-color: #121212 ;border-radius: 20px; height: 100vh;width: max-content;" id="skills">
        <div class="max-width">
            <h2 class="title" style="background-color: white;border-radius: 20px;">My skills</h2>
            <div class="skills-content">
                <div class="column left">
                    <div class="text" style="background-color: white;border-radius: 8px;">My Skills and experience</div>
                    <div class="text" style="color: white;"> I've started learning coding in 11th standard. Initially it was quite boring but gradually I realised the power of coding and started enjoying my own creation. FLEX: I've scored 96% in c++ in 12th boards. Now I'm learning complete web dev from internshala. I've been building my own web{called WOOP(one world one platform)} for some time but it's still in early stages.</div> 
                </div>
                <div class="column right">
                    <div class="bars">
                        <div class="info">
                            <span>HTML</span>
                            <span>80%</span>
                        </div>
                        <div class="line html"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>CSS</span>
                            <span>60%</span>
                        </div>
                        <div class="line css"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>JavaScript</span>
                            <span>10%</span>
                        </div>
                        <div class="line js"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>c++</span>
                            <span>85%</span>
                        </div>
                        <div class="line c"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>AIML</span>
                            <span>30%</span>
                        </div>
                        <div class="line aiml"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
</body>
</html>
*{
    margin: 0;
    padding: 0;
    text-decoration: none;
    box-sizing: border-box;
}
html{
    scroll-behavior: smooth;
}
 .info{
    color: white ;
}
section{
    padding: 90px 0;
}

.max-width{
    max-width: 1300px;
    padding: 0 80px;
    margin: auto;
}
.hobbies, .skills{
    font-family: 'Poppins', sans-serif;
}

.hobbies,
.skills .skills-content{
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
}
section .title{
    position: relative;
    text-align: center;
    font-size: 40px;
    font-weight: 500;
    margin-bottom: 60px;
    padding-bottom: 20px;
    font-family: 'Ubuntu', sans-serif;
}

/* my navbar styling*/
/* navbar */
.navbar{
    background-color: #1212120e;
    border-radius: 1.3rem;
    padding-top: 1rem;
}

.navbar{
    position: fixed;
    width: 100%;
    z-index: 999;
    padding: 30px 0;
    transition: all 0.3s ease;
    font-family: Arial, Helvetica, sans-serif;
}

.navbar .max-width{
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.navbar .menu li a:hover{
    color: rgb(48, 199, 236);
}
.navbar .menu li a{
    display: block;
    color: whitesmoke;
    font-size: 18px;
    font-weight: 500;
    margin-left: 25px;
    transition: color 0.3s ease;
}
.navbar .menu li{
    list-style: none;
    display: inline-block;
}
.navbar .logo a{
    color: #fff;
    font-size: 35px;
    font-weight: 600;
}
.navbar .logo a span{
    color: rgb(48, 199, 236);
    transition: all 0.3s ease;
}
.hobbies{
    margin: initial;
}


/* my hime styling */
.home{
    
    background-color: black;
    height: 100vh;
    display: flex;
    color: #fff;
    min-height: 500px;
    background-size: cover;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-attachment: fixed;
}

.home .home-content .text-1{
    font-size: 30px;
}
.home .max-width{
    width: 100%;
    display: flex;
  }
/* my btn styling */
.btn {
    padding: 8px 20px;
    margin: 7px;
    border: 2px;
    border-radius: 19px;
    font-size: 16px;
    cursor: pointer;
}
/* my skill styling */
.skills .skills-content .column{
    width: calc(50% - 30px);
}
.skills .skills-content .left .text{
    font-size: 20px;
    font-weight: 600;
    margin-bottom: 10px;
}
.skills .skills-content .left p{
    text-align: justify;
}
.skills .skills-content .right .bars{
    margin-bottom: 15px;
}

.skills .skills-content .right .line{
    height: 5px;
    width: 100%;
    background: lightgrey;
    position: relative;
    background-color: whitesmoke;
}
/* only for bar representation of skill section */
.skills .skills-content .right .line::before{
    content: "";
    position: absolute;
    height: 100%;
    left: 0;
    top: 0;
    background: skyblue;
}
.skills-content .right .html::before{
    width: 80%;
}
.skills-content .right .css::before{
    width: 60%;
}
.skills-content .right .js::before{
    width: 10%;
}
.skills-content .right .c::before{
    width: 85%;
}
.skills-content .right .aiml::before{
    width: 30%;
}


