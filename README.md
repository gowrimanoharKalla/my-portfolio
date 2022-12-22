<!DOCTYPE html>
<html lang="en">

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="manohar.css" />
    <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
    <title>Manohar</title>
</head>

<body>
    <div id="sectionHomepage col-12 col-md-6 col-lg-3">
        <div class="Homepage d-flex flex-column justify-content-center">
            <h1 class="Homeheading">Hello , I'm <span class="style">Gowri Manohar Kalla</span>.</h1>
            <h1 class="Homeheading">I'm a Frontend Developer.</h1>
            <button class="btn btn-outline-primary" onclick="display('sectionINFO')">
                View My Work
            </button>
        </div>
        </div>

    <div id="navbar">
        <nav class="navbar navbar-expand-md navbar-dark bg-dark">
            <a class="navbar-brand" href="#"><img class="mylogo" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRjz_svaXM7GWgIjMbJcKK81zxOf6py0BG42TJpa-eCbdAjrH-vABLwCyp-SFHojTTm7Vs&usqp=CAU" /></a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav">
                    <a class="nav-link active" href="#">Home <span class="sr-only">(current)</span></a>
                    <a class="nav-link" href="#">About</a>
                    <a class="nav-link" href="#">My Projects</a>
                    <a class="nav-link" href="#">Skills Known</a>
                    <a class="nav-link" href="#">
                        <div class="dropdown">
                            <button class="btn btn-outline-secondary dropdown-toggle" type="button" id="dropdownMenuButton" data-mdb-toggle="dropdown" aria-expanded="false">
                                Contacts
                            </button>
                            <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton">
                                <li><a class="dropdown-item" href="#">Action</a></li>
                                <li><a class="dropdown-item" href="#">Another action</a></li>
                                <li><a class="dropdown-item" href="#">Something else here</a></li>
                            </ul>
                        </div>
                    </a>
                </div>
            </div>
        </nav>
    </div>
    <div id="sectionINFO">
        <div class="aboutme">
            <div class="container">
                <div class="row">
                    <div class="col-12 col-md-6">
                        <div class="image-container m-5 pt-1">
                            <img class="my-image" src="https://scontent.fvtz3-2.fna.fbcdn.net/v/t1.6435-9/94701668_2634050533499115_281070206107779072_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=09cbfe&_nc_ohc=PPXPDsrsK0sAX_DR2ZZ&_nc_ht=scontent.fvtz3-2.fna&oh=00_AfBJSMeTqwfjbg8azhXvPk42uRgC31dtnOT0zA7B_iRzeg&oe=63CBD712" />
                        </div>
                    </div>
                    <div class="col-12 col-md-6">
                        <div class="sub-container pt-1 m-5">
                            <h1 class="Homeheading">About Me</h1>
                            <p class="description">
                                Strong in design and integration with intuitive problem-solving skills. Passionate about implementing and launching new projects. Ability to translate business requirements into technical solutions.
                                Looking to start the career as an entry-level software engineer with a reputed firm driven by technology.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="row">
                <div class="col-12 col-md-6">
                    <div class="myEducation m-5 pt-1">
                        <h1 class="Homeheading">Education Details</h1>
                        <ul>
                            <li class="description">Bachelor Of Technology in Avanthi's Research & Technological Academy (EEE)with 63.85%</li>
                            <li class="description">Diploma in Sai Ganapathi Polytechnic(EEE) with 72.77%</li>
                            <li class="description">Schooling in AKM Jubliee English Medium School with 8.5 (CGPA)</li>
                        </ul>
                    </div>
                </div>
                <div class="col-12 col-md-6">
                    <div class="image-container m-5 pt-1">
                        <img class="my-images" src="https://www.thoughtco.com/thmb/IfrEEpBwmg9i_X3T7B004yLJdu0=/1500x994/filters:fill(auto,1)/GettyImages-769821735-5b789e22c9e77c00504431b1.jpg" />
                    </div>
                </div>
            </div>
        </div>
        <div class="myadvantages">
            <h1 class="Homeheading pb-3">About My Webpages</h1>
            <div class="container">
                <div class="row">
                    <div class="col-12 col-md-6 col-lg-3 mb-3 mt-3">
                        <div class="sub-divs">
                            <span class="iconstar">
                                <ion-icon name="train-outline"></ion-icon>
                            </span>
                            <h1 class="smallheading">Fast</h1>
                            <p class="smallparagraph">Fast load times and lag free interaction, my highest priority.</p>
                        </div>
                    </div>
                    <div class="col-12 col-md-6 col-lg-3 mb-3 mt-3">
                        <div class="sub-divs">
                            <span class="iconstar">
                                <ion-icon name="bulb-outline"></ion-icon>
                            </span>
                            <h1 class="smallheading">Intutive</h1>
                            <p class="smallparagraph">Strong preference for easy to use, intuitive UX/UI.</p>
                        </div>
                    </div>
                    <div class="col-12 col-md-6 col-lg-3 mb-3 mt-3">
                        <div class="sub-divs">
                            <span class="iconstar">
                                <ion-icon name="terminal-outline"></ion-icon>
                            </span>
                            <h1 class="smallheading">Responsive</h1>
                            <p class="smallparagraph">My layouts will work on any device, big or small.</p>
                        </div>
                    </div>
                    <div class="col-12 col-md-6 col-lg-3 mb-3 mt-3">
                        <div class="sub-divs">
                            <span class="iconstar">
                                <ion-icon name="rocket-outline"></ion-icon>
                            </span>
                            <h1 class="smallheading">Dynamic</h1>
                            <p class="smallparagraph">Websites don't have to be static, I love making pages come to life.</p>
                        </div>
                    </div>

                    <button class = "btn btn-outline-secondary" onclick="display('sectionProjects')">Go To My Projects</button>
                </div>
            </div>
        </div>
    </div>
    </div>
    <div id="sectionProjects">
        <h1 class="Homeheading">My Projects</h1>
    <div class="projects-container">
        <div class = "row">
            <div class = "col-12 col-md-6 col-lg-3 m-5 p-3">
            <div class="project-details">
                <img class="" src="https://th.bing.com/th/id/OIP.wexzCmlUZ-SiTg5Vqdx6lwHaEF?w=320&h=180&c=7&r=0&o=5&dpr=1.5&pid=1.7"/>
                <h1 class="projectheadings">Created Responsive and Static Websites using Virtual Reality Gaming</h1>
                <button class = "btn btn-outline-success">View All Projects</button>
            </div>
            </div>
            <div class = "col-12 col-md-6 col-lg-3 m-5 p-3">
                <div class="project-details">
                    <img class="" src="https://th.bing.com/th/id/OIP.wexzCmlUZ-SiTg5Vqdx6lwHaEF?w=320&h=180&c=7&r=0&o=5&dpr=1.5&pid=1.7"/>
                    <h1 class="projectheadings">Created Responsive and Static Websites using Virtual Reality Gaming</h1>
                    <button class = "btn btn-outline-success">View All Projects</button>
                </div>
                </div>
                <div class = "col-12 col-md-6 col-lg-3 m-5 p-3">
                    <div class="project-details">
                        <img class="" src="https://th.bing.com/th/id/OIP.wexzCmlUZ-SiTg5Vqdx6lwHaEF?w=320&h=180&c=7&r=0&o=5&dpr=1.5&pid=1.7"/>
                        <h1 class="projectheadings">Created Responsive and Static Websites using Virtual Reality Gaming</h1>
                        <button class = "btn btn-outline-success">View All Projects</button>
                    </div>
                    </div>
                    <div class = "col-12 col-md-6 col-lg-3 m-5 p-3">
                        <div class="project-details">
                            <img class="" src="https://th.bing.com/th/id/OIP.wexzCmlUZ-SiTg5Vqdx6lwHaEF?w=320&h=180&c=7&r=0&o=5&dpr=1.5&pid=1.7"/>
                            <h1 class="projectheadings">Created Responsive and Static Websites using Virtual Reality Gaming</h1>
                            <button class = "btn btn-outline-success">View All Projects</button>
                        </div>
                        </div>
        </div>
        </div>
        </div>
    </body>
    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
</body>
</html>
