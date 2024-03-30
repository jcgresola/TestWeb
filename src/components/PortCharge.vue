<template>
    <nav class="navbar navbar-expand-lg sticky-top p-3" style="background-color: #16262e;">
        <div class="container-fluid mx-auto">
                <a class="navbar-brand text-light fs-5 ms-4 me-5" href="#home">
                    <img src="profile.png" alt="Portfolio Icon" width="50" height="50">
                </a>
                <a class="nav-link text-light fs-6 me-5" aria-current="page" href="#about">About</a>

                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                    <ul class="navbar-nav me-4">
                        <li class="nav-item">
                            <a class="me-3 ms-4" href="https://web.facebook.com/ApoMan123" target="_blank">
                                <img src="facebook.png" width="30px" title="Facebook" class="zoom-in-effect">
                            </a>
                        </li>
                        <li class="nav-item">
                            <a class="me-3" href="https://www.instagram.com/jhnnchris/" target="_blank">
                                <img src="instagram.png" width="30px" title="Instagram" class="zoom-in-effect">
                            </a>
                        </li>
                        <li class="nav-item">
                            <a href="mailto:jcgresola24@gmail.com" class="text-dark text-decoration-none me-3" target="_blank">
                                <img src="gmail.png" width="30px" title="Gmail" class="zoom-in-effect">
                            </a>
                        </li>
                        <li class="nav-item">
                            <a href="https://twitter.com/Jankrissss/" class="text-dark text-decoration-none" target="_blank">
                                <img src="social-media.png" width="30px" title="Gmail" class="zoom-in-effect" style="filter: brightness(0) invert(1);">
                            </a>
                        </li>
                    </ul>                                                                                                                                                               
                </div>
        </div>
    </nav>

    <div id="home" class="container-fluid p-5" style="background-color: #3c7a89;">
        <div class="container">
            <div class="row justify-content-center align-items-center">
                <div class="col-md-6">
                    <h2 class="fw-bold text-light">John Chris Gresola</h2>
                        <div class="mb-5 text-white" style="font-size: 0.67rem;">BSIT STUDENT, MAJOR IN PROGRAMMING</div>
                    <div class="row">
                        <div class="col-md-12">
                            <h5 class="text-light">
                                A committed learner currently enrolled at Cordova Public College, pursuing my degree in computer science.
                            </h5>
                        </div>
                    </div>
                </div>
                <div class="col-md-6">
                    <img class="img-fluid rounded mb-5" alt="Portrait" src="/portrait2.png">
                </div>
            </div>
        </div>
    </div>

    <div id="about"></div>
        
        <h2 class="text-center mt-5 fw-bold">About Me</h2>

        <div class="container-fluid">
            <div class="row p-5">
                <div class="col-md-6 text-dark p-5 mx-auto">
                    <p class="fs-5">
                        Hello there! I'm John Chris Gresola, an enthusiastic and skilled developer dedicated 
                        to crafting exceptional digital experiences. With a keen eye for detail and a passion 
                        for innovation, I specialize in both frontend and backend development. From conceptualization 
                        to execution, I strive to transform ideas into engaging interfaces that captivate users.
                    </p>
                    <p class="fs-5">
                        What sets me apart is my commitment to effective communication and strategic planning. 
                        I thrive on understanding the unique needs of each project, delivering solutions that 
                        exceed expectations. I approach every aspect of development with meticulous attention 
                        to detail, ensuring seamless execution and optimal results from start to finish.
                    </p>
                    <p class="fs-5">
                        My expertise spans a wide range of technologies, including HTML, CSS, PHP, Bootstrap, and more. 
                        Whether you're looking for a responsive website, dynamic web application, or custom software 
                        solution, I'm here to turn your vision into reality. Additionally, I offer comprehensive services 
                        such as website maintenance, performance optimization, and security enhancements to ensure the 
                        ongoing success of your digital presence.
                    </p>

                </div>
                <div class="col-md-6 p-5 mt-5">
                    <div class="container">
                        <div class="row justify-content-evenly px-lg-0 px-md-3 px-5">
                            <div class="col-lg-6 col-md-4 text-center py-4 my-3">
                                <img src="bootstrap.png" width="80px" title="Bootstrap" class="zoom-in-effect">
                            </div>
                            <div class="col-lg-6 col-md-4 text-center py-4 my-3">
                                <img src="css.png" width="80px" title="CSS" class="zoom-in-effect">
                            </div>
                            <div class="col-lg-6 col-md-4 text-center py-4 my-3">
                                <img src="php.png" width="140px" title="PHP" class="zoom-in-effect">
                            </div>
                            <div class="col-lg-6 col-md-4 text-center py-4 my-3">
                                <img src="html.png" width="80px" title="HTML" class="zoom-in-effect">
                            </div>
                            <div class="col-lg-6 col-md-4 text-center py-4 my-3">
                                <img src="c-sharp.png" width="80px" title="CSharp" class="zoom-in-effect">
                            </div>
                            <div class="col-lg-6 col-md-4 text-center py-4 my-3">
                                <img src="js.png" width="80px" title="JS" class="zoom-in-effect">
                            </div>
                        </div>
                    </div>

                        <a class="btn btn-success zoom-in-effect mt-3" href="https://github.com/jcgresola/WEB" target="_blank">My Projects</a>
                </div>
            </div>
        </div>


</template>

<script>

</script>


<style>

.navbar-brand, .nav-link {
  font-family: sans-serif;
  font-size: 10px; 
}

body {
  font-family: 'Times New Roman', Times, serif;
}

h1,
h5 {
  font-size: 15px; /* You can adjust the font size as needed */
}

</style>
