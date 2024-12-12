<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal portfolio</title>
    <link rel="stylesheet" href="index.css">
    <script src="https://kit.fontawesome.com/4b1cda401a.js" crossorigin="anonymous"></script>
</head>
<body>
<div id="header">
    <div class="container">
        <nav>


            <ul>
                <li><a href="#header">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contacts</a></li>
            </ul>
        </nav>
        <div class="header-text">
            <p>B.Tech Student</p>
            <h1>Hi, This is JAGADEESH</h1>
        </div>
    </div>
</div>
<!-- ------about------- -->
<div id="about">
    <div class="container">"<source>="<a href="https://ibb.co/PrSyWtv"><img src="https://i.ibb.co/ZfZrgNp/Whats-App-Image-2024-12-12-at-10-47-08-AM.jpg" human picture"
        <div class="row">
            <div class="about-col-1">
                
            </div>
            <div class="about-col-2">
                <h1 class="sub-title">About Me</h1>
                <p>Currently educating myself to improve my skills and knowledge,constantly
                trying to learn about new things in my free time and exploring the internet.
                always likes to take risk and know more about others and their life exeriences.</p>

                <div class="tab-titles">
                    <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                    <p class="tab-links" onclick="opentab('experience')">Experience</p>
                    <p class="tab-links" onclick="opentab('education')">Education</p>
                </div>
                <div class="tab-contents active-tab"  id="skills">
                    <ul>
                        <li><span>UI/UX</span><br>Designing Web/App interfaces</li>
                        <li><span>Web Development</span><br>Web App Development</li>
                        <li><span>App Development</span><br>Building Android/iOS apps</li>
                    </ul>
                </div>
                <div class="tab-contents" id="experience">
                    <ul>
                        <li><span>2024 - current intern</span><br>Frontend Development</li>
                        <li><span>intern</span><br>Web App Development</li>
                        <li><span>intern</span><br>Building Android/iOS apps</li>
                    </ul>
                </div>
                <div class="tab-contents" id="education">
                    <ul>
                        <li><span>2023</span><br>st'annes internation school</li>
                        <li><span>2024 - current</span><br>B.tech VTMT</li>
                        <li><span>2020</span><br>st'annes international school</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>
<!-- ----------------services------------------- -->
<div id="services">
    <div class="container">
        <h1 class="sub-title">My Services</h1>
        <div class="services-list">
            <div>
                <i class="fa-solid fa-fire"></i>
                <h2>Web Design</h2>
                <p>The pain itsef is important,it will be followed by the education system. But there is no plan,
                    I the developer should be the smart one.</p>
                    <a href="#">learn more</a>
            </div>
            <div>
                <i class="fa-solid fa-cloud-bolt"></i>
                <h2>UI/UX Design</h2>
                <p>The pain itsef is important,it will be followed by the education system. But there is no plan,
                    I the developer should be the smart one.</p>
                    <a href="#">learn more</a>
            </div>
            <div>
                <i class="fa-solid fa-droplet"></i>
                <h2>App Design</h2>
                <p>The pain itsef is important,it will be followed by the education system. But there is no plan,
                    I the developer should be the smart one.</p>
                    <a href="#">learn more</a>
            </div>
        </div>
    </div>
</div>
<!-- ---------------contact---------------- -->
<div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="sub-title">Contact Me</h1>
                <p><i class="fa-solid fa-paper-plane"></i> jagadeeshnagesh1218@gmail.com</p>
                <p><i class="fa-solid fa-phone"></i> +91 8110057344</p>
                <div class="social-icons">
                    <a href=""><i class="fa-brands fa-facebook"></i></a>
                    <a href=""><i class="fa-brands fa-twitter-square"></i></a>
                    <a href=""><i class="fa-brands fa-instagram"></i></a>
                    <a href=""><i class="fa-brands fa-linkedin"></i></a>

                </div>
            </div>
            </div>
        </div>
    </div>
</div>

<script>
    var tablinks = document.getElementsByClassName("tab-links");
    var tabcontents = document.getElementsByClassName("tab-contents");

    function opentab(tabname){
        for(tablink of tablinks){
            tablink.classList.remove("active-link");
        }
        for(tabcontent of tabcontents){
            tabcontent.classList.remove("active-tab");
        }
        event.currentTarget.classList.add("active-link");
        document.getElementById(tabname).classList.add("active-tab");
    }

</script>
</body>
</html>