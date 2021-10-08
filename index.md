<!doctype html>
<html lang="en">
<head>

    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- Website Name -->
    <title>Index</title>
    <!-- Bootstrap CSS/JS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-F3w7mX95PdgyTmZZMECAngseQB83DfGTowi0iMjiWaeVhAn4FJkqJByhZMI3AhiU" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-/bQdsTh/da6pkI1MST/rWKFNjaCP5gBSY4sEBT38Q/9RBh9AH40zEOg7Hlq2THRZ" crossorigin="anonymous"></script>

    <!-- Custom Styles -->

    <!-- Styles for <body> - dark-mode and light-mode -->

</head>
<body>
    <!-- Navigation Bar on Top -->
    <!-- Nav buttons up to 10char! -->
    <!-- Up to 6 nav buttons! -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-info bg-gradient">
        <div class="container-fluid">

            <a class="navbar-brand" href="#">
                <img src="https://pbs.twimg.com/profile_images/819237681/twitter_400x400.gif" width="90" height="90" alt="">
            </a>

            <button class="navbar-toggler col-sm-12 col-md-12" type="button" data-bs-toggle="collapse" data-bs-target="#navmenu" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div id="navmenu" class="collapse navbar-collapse">
                <ul class="navbar-nav me-auto mb-2 mb-lg-1">
                    <li class="nav-item">
                        <a class="nav-link active fs-2" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link fs-2" href="#">Link</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle fs-2" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Dropdown
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <li><a class="dropdown-item" href="#">Action</a></li>
                            <li><a class="dropdown-item" href="#">Another action</a></li>
                            <li><hr class="dropdown-divider"></li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>
                        </ul>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link fs-2" href="#">Link</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link fs-2" href="#">Link</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link fs-2" href="#">Link</a>
                    </li>
                </ul>
                <form class="d-flex">
                    <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                    <button class="btn btn-outline-success" type="submit">Search</button>
                </form>
            </div>
        </div>
    </nav>

    <!--Main Info Container-->

    <section class="p-1">
        <div class="container">
            <div>

                <div class="row-2 text-center">
                    <div><h1>Welcome to <span class="text-primary">TITLE</span></h1></div>
                </div>

                <div class="container col-lg-4 col-sm-7 justify-content-center">
                    <div class="row-2">
                        <img class="img-fluid" src="http://www.mandysam.com/img/random.jpg" alt="">
                    </div>
                </div>

                <div class="row-3 py-4 text-center">
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-circle-fill" viewBox="0 0 16 16">
                        <circle cx="8" cy="8" r="8"/>
                    </svg>
                </div>

                <div class="container col-md-8">
                    <div class="text-wrap text-center fs-4">
                        Prevent long strings of text from breaking your components' layout by using .text-break to set word-wrap: break-word and word-break: break-word. We use word-wrap instead of the more common overflow-wrap for wider browser support, and add the deprecated word-break: break-word to avoid issues with flex containers.
                    </div>
                </div>

                <div class="row-4 py-4 text-center">

                    <button type="button" class="btn btn-success btn-lg" data-bs-toggle="modal" data-bs-target="#VikoModal">VIKO</button>

                    <!-- VIKO Website Modal -->
                    <div  id="VikoModal" class="modal fade" tabindex="-1" aria-labelledby="VikoModalLabel" aria-hidden="true">
                        <div class="modal-dialog modal-xl">
                            <div class="modal-content">
                                <div class="modal-header">
                                    <h5 class="modal-title" id="VikoModalLabel">VIKO website</h5>
                                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                                </div>
                                <div class="modal-body">
                                    <iframe class="ratio ratio-16x9" height="600" src="https://viko.lt"></iframe>
                                </div>
                                <div class="modal-footer">
                                    <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                                </div>
                            </div>
                        </div>
                    </div>

                    <a href="https://youtu.be/dQw4w9WgXcQ" class="link-light"><button type="button" class="btn btn-danger btn-lg">Youtube</button></a>

                    <a href="https://frame.work/" class="link-light"><button type="button" class="btn btn-secondary btn-lg">Custom URL</button></a>

                </div>

                <div class="row-5 text-center">
                    <button type="button" class="btn btn-info btn-lg" id="FormPopUpButton">Fill out a form!</button>
                </div>
            </div>
        </div>
        <div id="FormPopUp"></div>
    </section>

    <section class="py-5">
        <div class="container">
            <div class="row">
                <div class="col">
                    <!-- Education Accordion -->
                    <div class="accordion fs-4" id="EductionAccordion">
                        <div class="accordion-item">
                            <h2 class="accordion-header" id="headingOne">
                                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                                    <strong>What is education?</strong>
                                </button>
                            </h2>
                            <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#EductionAccordion">
                                <div class="accordion-body">
                                    <strong>Education</strong> is the process of facilitating learning, or the acquisition of knowledge, skills, values, morals, beliefs, and habits.
                                </div>
                            </div>
                        </div>
                        <div class="accordion-item">
                            <h2 class="accordion-header" id="headingTwo">
                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                                    <strong>What kind of educational methods are there?</strong>
                                </button>
                            </h2>
                            <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#EductionAccordion">
                                <div class="accordion-body">
                                    <strong>Educational methods</strong> include teaching, training, storytelling, discussion and directed research.
                                </div>
                            </div>
                        </div>
                        <div class="accordion-item">
                            <h2 class="accordion-header" id="headingThree">
                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                                    <strong>More info</strong>
                                </button>
                            </h2>
                            <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#EductionAccordion">
                                <div class="accordion-body">
                                    <strong>Education</strong> frequently takes place under the guidance of educators; however, learners can also educate themselves. Education can take place in formal or informal settings, and any experience that has a formative effect on the way one thinks, feels, or acts may be considered educational. The methodology of teaching is called pedagogy. Formal education is commonly divided formally into stages such as preschool or kindergarten, primary school, secondary school and then college, university, or apprenticeship. In most regions, education is compulsory up to a certain age. There are movements for education reforms, such as for improving quality and efficiency of education towards relevance in students' lives and efficient problem solving in modern or future society at large, or for evidence-based education methodologies.
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- Educational Carousel -->
                <div class="col d-none d-xl-block">
                    <div id="carouselExampleSlidesOnly" class="carousel slide carousel-fade" data-bs-ride="carousel">
                        <div class="carousel-inner d-flex justify-content-start">
                            <div class="carousel-item active">
                                <img src="http://analyticsindiamag.com/wp-content/uploads/2017/09/college-1.jpg" class="ratio ratio-16x9 d-block w-100" alt="...">
                            </div>
                            <div class="carousel-item">
                                <img src="https://www.migration.lt/media/cache/d/6/b/9/5/d6b9525a9c53aa41843c888607678f0f61404609.jpeg" class="ratio ratio-16x9 d-block w-100" alt="...">
                            </div>
                            <div class="carousel-item">
                                <img src="https://makeinbusiness.com/wp-content/uploads/2019/11/Improve-Education-Experiences.jpg" class="ratio ratio-16x9 d-block w-100" alt="...">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Table of numbers -->

    <section class="p-1">
        <div class="container text-center">
            <h2>Something Something Table</h2>
            <div class="row p-4">
                <table class="table">
                    <thead>
                    <tr>
                        <th scope="col">#</th>
                        <th scope="col">One</th>
                        <th scope="col">Two</th>
                        <th scope="col">Three</th>
                        <th scope="col">Four</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr>
                        <th scope="row">1</th>
                        <td>A<span class="align-baseline fs-6">11</span></td>
                        <td>A<span class="align-baseline fs-6">12</span></td>
                        <td>A<span class="align-baseline fs-6">13</span></td>
                        <td>A<span class="align-baseline fs-6">14</span></td>
                    </tr>
                    <tr>
                        <th scope="row">2</th>
                        <td>B<span class="align-baseline fs-6">21</span></td>
                        <td>B<span class="align-baseline fs-6">22</span></td>
                        <td>B<span class="align-baseline fs-6">23</span></td>
                        <td>B<span class="align-baseline fs-6">24</span></td>
                    </tr>
                    <tr>
                        <th scope="row">3</th>
                        <td>C<span class="align-baseline fs-6">31</span></td>
                        <td>C<span class="align-baseline fs-6">32</span></td>
                        <td>C<span class="align-baseline fs-6">33</span></td>
                        <td>C<span class="align-baseline fs-6">34</span></td>
                    </tr>
                    </tbody>
                </table>
            </div>
            <div class="px-5">
                <p>
                    <button class="btn btn-primary" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
                        Something about this table
                    </button>
                </p>
                <div class="collapse" id="collapseExample">
                    <div class="card card-body">
                        Description about something...
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="p-4">
        <div class="container-md">
            <div class="row">
                <div class="text-center px-0 py-10 my-10 ">
                    <h3>Hello, world!</h3>
                </div>
            </div>
        </div>
    </section>

    <div class="text-center">
        <p><h2>Made by Sebastian Termen student at Vilniaus kolegija/Universtiy of Applied Sciences</h2></p>
    </div>

    <!--Script for Form Pop Up-->
    <script>
        var alertPlaceholder = document.getElementById('FormPopUp')
        var alertTrigger = document.getElementById('FormPopUpButton')

        function alert(message, type) {
            var wrapper = document.createElement('div')
            wrapper.innerHTML = '<div class="alert alert-' + type + ' alert-dismissible" role="alert">' + message + '<button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close"></button></div>'

            alertPlaceholder.append(wrapper)
        }

        if (alertTrigger) {
            alertTrigger.addEventListener('click', function () {
                alert('<form>\n' +
                    '  <div class="form-group">\n' +
                    '    <label for="InputName">Name</label>\n' +
                    '    <input type="name" class="form-control" id="InputName" aria-describedby="nameHelp">\n' +
                    '    <small id="nameHelp" class="form-text text-muted">Please write down your full name.</small>\n' +
                    '  </div>\n' +
                    '  <div class="form-group">\n' +
                    '    <label for="InputAge">Age</label>\n' +
                    '    <input type="age" class="form-control" id="InputAge">\n' +
                    '  </div>\n' +
                    '  <div class="form-group form-check">\n' +
                    '    <input type="checkbox" class="form-check-input" id="Check1">\n' +
                    '    <label class="form-check-label" for="Check1">Do not save my age information</label>\n' +
                    '  </div>\n' +
                    '  <button type="submit" class="btn btn-primary">Submit</button>\n' +
                    '</form>', 'success')
            })
        }
    </script>

</body>
</html>
