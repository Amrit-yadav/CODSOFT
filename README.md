<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="app.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css"/>
    <title>Portfolio</title>


</head>

<body>
    <nav>
        <div class="container nav-container">
            <a href="" class="logo">
                <h2>Amrit<span> Kumar</span></h2>
            </a>
            <ul>
                <li><a href="#About">About </a></li>
                <li><a href="#Services">Services</a></li>
                <li><a href="#Blog">Blog</a></li>
                <li><a href="#Contact">Contact </a></li>

            </ul>
        </div>
    </nav>
    <header>
        <div class="header-container container">
            <div class="header-left">
                <h1>
                    Hello,

                    <p class="name"> I am <span>Rajnish</span></p>
                </h1>
                <p>Proficient in HTML,CSS, Javascript and React.js with
                    experience in windows and linux<br> environmenst
                    committed to deliveing hight-quality and driving organzation growth.
                </p>

                <h5>Frontend Developer</h5>
                <br>
                <div class="header-action-aria">
                    <a href="cv.pdf" download class="btn btn-primary">Download CV</a>
                    <a href="" class="btn">Read more</a>
                </div>
            </div>
            <div class="header-right">
                <img src="pic22.jpeg" alt="">
            </div>
    </header>

    <section id="About">
        <h1><span>A</span>BOUT</h1>
        <div class="container about-container">
            <p>I'm a diligent <span>Frontend Developer </span>, passionately committed to refining my <span> CSS, HTML,
                </span> and <span> React </span> skills. My
                relentless dedication drives me to continually learn and adapt, staying at the forefront of <span>web
                    development</span> trends. My goal is to create captivating, responsive, and user-friendly web
                interfaces.</p>
        </div>
        <div class="about-content">
            <article class="about-article">
                <img src="man.png" alt="">
                <h5>FULL NAME</h5>
                <p>Rajnish KUmar</p>

            </article>
            <article class="about-article">
                <img src="email.png" alt="">
                <h5>EMAIL</h5>
                <p>sonyrajnish845455@gmail.com </p>

            </article>
            <article class="about-article">
                <img src="linkedin.png" alt="">
                <h5>Linkedin</h5>
                <p>www.linkedin.com/in/rajnish-kumar-aa9123209</p>

            </article>
            <article class="about-article">
                <img src="telephone-call.png" alt="">
                <h5>PHONE </h5>
                <p>+918789512130</p>

            </article>
        </div>
    </section>


    <section id="Services">
        <h1><span>W</span>hat I Do</h1>

        <div class="container services-container">
            <article class="services-article">
                <img src="software.png" alt="">
                <h2>Software Development</h2>
                <p>Software development services encompass designing, coding, testing, and maintaining applications to
                    meet specific client needs, delivering tailored software solutions.</p>
            </article>
            <article class="services-article">
                <img src="coding.png" alt="">
                <h2>Web
                    Development</h2>
                <p>Web development

                    Crafting websites by coding, designing, and optimizing for functionality, performance, and user
                    experience, enabling online presence and interaction.</p>
            </article>
            <article class="services-article">
                <img src="python.png" alt="">
                <h2>Python Programming</h2>
                <p>

                 Python is extensively applied in data science, data analysis, machine learning, data engineering, web development, software development, and other fields.</p>
            </article>
        </div>
    </section>

    <section id="skills">
        <h1> <span>M</span>y Skills</h1>
        <div class="container skills-container">
            <article class="skill-article">

                <h4>HTML </h4>
            </article>
            <article class="skill-article">

                <h4>CSS</h4>
            </article>
            <article class="skill-article">

                <h4>Javascript</h4>
            </article>
            <article class="skill-article">

                <h4>MySql</h4>
            </article>
            <article class="skill-article">

                <h4>Python</h4>
            </article>
            <article class="skill-article">

                <h4>WebDesign</h4>
            </article>
            <article class="skill-article">

                <h4>Testing</h4>
            </article>
            <article class="skill-article">

                <h4>Promt Engineering</h4>
            </article>

        </div>
    </section>


    <section id="Blog">
        <div class="row">
            <div class="header">
                <h1>B<span>log</span></h1>
                <p>Welcome to the dynamic world of front-end development, web design, and web development. In this
                    concise guide, we'll delve into the key aspects of this exciting field.</p>
            </div>
            <div class="content">
                <div class="card">

                    <img src="web design (1).jpg" alt="">
                    <br>
                    <p>
                        Web design is the art of crafting visually appealing and user-friendly websites, blending
                        elements like typography, color theory, and layout to create memorable online experiences. HTML,
                        CSS, and JavaScript are the cornerstone languages that enable us to build interactive and
                        responsive websites, making them not only look great but also function seamlessly on various
                        devices interface.

                    </p>
                </div>
                <div class="card">

                    <img src="web design (2).jpg" alt="">
                    <br>
                    <p>
                        Responsive web design ensures that websites adapt effortlessly to different screen sizes,
                        offering a consistent experience across platforms. As you progress, you can explore frameworks
                        like Bootstrap or delve into user-centric design principles to create intuitive interfaces. Web
                        accessibility creativity and innovation, waiting for you to explore world-wide.

                    </p>
                </div>
            </div>
        </div>
    </section>
    <section id="Contact">
        <h1> <span>Get</span> In Touch</h1>
        <div class="contatact-container container">
            <form>
                <div class="form-top">
                    <input type="text" placeholder="  First Name" required>
                    <input type="text" placeholder="Last Name" required>
                    <input type="email" placeholder="Email" required>
                    <input type="number" placeholder="Phone Number" required>

                </div>
                <div class="form-bottom">
                    <textarea name="message" placeholder="message"></textarea>
                    <button type="submit" class="btn btn-primary">Sumbit Now</button>
                </div>
            </form>
        </div>
    </section>
    <footer>
        &copy;Amrit yadav

    </footer>
    <script src="script.js"></script>

</body>
</html>