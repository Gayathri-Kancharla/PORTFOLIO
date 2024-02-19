<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KANCHARLA GAYATHRI - Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        body {
            font-family: 'Georgia', 'Times New Roman', Times, serif;
            margin: 0;
            margin-bottom: 60px; 
            padding: 0;
            scroll-behavior: smooth;
            background: linear-gradient(45deg, #01060b, #001a33);
            color: #fff;
            overflow-x: hidden;
        }

        .navbar {
            background: linear-gradient(45deg, #01060b, #001a33);
            box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.1);
            transition: background 0.5s ease;
        }
        .navbar {
        opacity: 0;
        animation: fadeInNavbar 1s ease-in-out forwards;
    }

    @keyframes fadeInNavbar {
        from {
            opacity: 0;
            transform: translateY(-20px);
        }
        to {
            opacity: 1;
            transform: translateY(0);
        }
    }

        .navbar-dark .navbar-brand,
        .navbar-dark .navbar-nav .nav-link {
            color: #ffffff;
            transition: color 0.5s ease;
        }

        .navbar-dark .navbar-toggler-icon {
            border-color: #ffffff;
        }

        .navbar-nav .nav-item:hover .nav-link {
            color: #17a2b8;
        }

        .navbar-toggler {
            border-color: #17a2b8;
        }

        .navbar-toggler-icon {
            background-color: #ffffff;
        }

        .jumbotron {
            background: linear-gradient(45deg, #01060b, #001a33);
            color: #fff;
        }

        .jumbotron h1, .jumbotron p {
            opacity: 0;
            animation: fadeIn 1s ease-in-out forwards;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        #about {
        opacity: 0;
        animation: fadeInAbout 1s ease-in-out forwards;
    }

    @keyframes fadeInAbout {
        from {
            opacity: 0;
            transform: translateY(20px);
        }
        to {
            opacity: 1;
            transform: translateY(0);
        }
            }
        .card {
            transition: transform 0.5s ease-in-out;
            width: 300px;
            margin: 0 10px 30px 10px;
            display: inline-block;
        }
        h5 {
            color: #ffffff;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        .card-text {
            color: #e7d7d9;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        }
        .card:hover {
            transform: scale(1.05);
        }
        .skills, .skills2 {
            text-align: center;
            margin: 30px 0;
        }
        .skills img, .skills2 img {
            width: 50px;
            height: auto;
            margin: 10px;
        }
        .container.contact {
            margin-top: 50px;
        }
        .card-body {
    background: linear-gradient(45deg, #001a33, #17a2b8);
    
    padding: 20px;
    border-radius: 10px;
    overflow-y: auto;
    max-height: 150px;
     }

        .card-body::-webkit-scrollbar {
            width: 8px;
        }

        .card-body::-webkit-scrollbar-thumb {
            background-color: #17a2b8;
            border-radius: 4px;
        }

        .card-body::-webkit-scrollbar-track {
            background-color: #001a33;
        }

        #projects h2 {
            text-align: center;
            margin-bottom: 30px;
        }

        #projects .row {
            display: flex;
            justify-content: center;
        }

        #projects .card {
            width: 300px;
            margin: 0 15px 30px;
        }

        #contact .contact-links {
            max-width: 500px;
            margin: 0 auto;
        }

        #contact p {
            margin: 10px 0;
        }
        #contact a {
            color: #17a2b8;
            text-decoration: none;
            font-weight: bold;
        }
        #contact a:hover {
            text-decoration: underline;
        }
        .btn-primary {
            background-color: #17a2b8;
            border-color: #17a2b8;
        }
        .btn-primary:hover {
            background-color: #165670;
            border-color: #165670;
        }
        iframe {
    max-width: 100%;
    max-height: 100%;
         }
      div.modal {
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: auto;
       }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand" href="#"></a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#home"><i class="fa-solid fa-house"></i>Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#about"><i class="fa-solid fa-id-badge"></i>About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#projects"><i class="fa-regular fa-folder-open"></i>Projects</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#contact"><i class="fa-solid fa-person"></i>Contact</a>
                </li>
            </ul>
        </div>
    </nav>
    <section id="home" class="jumbotron text-center">
        <div class="heading">
            <h1 class="display-4">KVS GAYATHRI</h1>
            <p class="lead">I'm a Web Developer.</p>
            <button id="resumeButton" class="btn btn-primary">View Resume</button>
        </div>
    </section>

    <section id="about" class="container mt-4">
        <div class="row">
            <div class="col-md-6">
                <h2 style="text-decoration: underline;">About Me</h2>
                <p>
                    Hello! I'm a B.Sc graduate passionate about both frontend and backend technologies. I love building digital things that look good and work well. I've got the hang of HTML, CSS, and JavaScript for creating cool and responsive websites. On the backend, I enjoy working with PHP, and I know my way around databases like MySQL. Check out my projects, like the ATM Management System on GitHub, to see what I can do. I'm open to new opportunities and collaborations, so feel free to drop me an email or connect on LinkedIn. Let's make awesome things together!
                </p>
            </div>
        </div>
    </section>
    <section id="projects" class="container mt-4">
        <h2>P R O J E C T S</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">ATM Project</h5>
                        <p class="card-text">I used my skills to develop a website that facilitates withdrawal, deposits, bank balance inquiries, receipt generation, and language selection—features commonly performed at ATMs.</p>
                        <a href="https://github.com/Gayathri-Kancharla/Gaya2526" class="btn btn-primary">Check Once</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Pixelsmovies Website</h5>
                        <p class="card-text">I redesigned a webpage using HTML, CSS, and Bootstrap, used a HTML is for structuring the content, CSS is for styling and making it look good, and Bootstrap is a framework that helps you do this more easily, especially for making your design work well on different devices like phones and tablets.</p>
                        <a href="https://github.com/Gayathri-Kancharla/My-Tasks" class="btn btn-primary">Check Once</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">To Do-List</h5>
                        <p class="card-text">A handy tool to keep track of tasks easily. It helps you stay organized with features like setting priorities, due dates, Meetings, wishes.By maintaining this, reach your goals effortlessly. 
                            #TaskList.</p>
                        <a href="https://github.com/Gayathri-Kancharla/My-Tasks" class="btn btn-primary">Check Once</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Payment Gateway Page</h5>
                        <p class="card-text">Payment gateway page choose a wide range of payment methods checkout the source code for more information.</p>
                        <a href="https://github.com/Gayathri-Kancharla/My-Tasks/blob/main/account.php" class="btn btn-primary">Check Once</a>
                    </div>
                </div>
            </div>
        </div>
    </section>
   <div class="skills">
    <h3>S K I L L S</h3>
    <div class="row">
        <div class="col">
            <b>H T M L</b>
        </div>
        <div class="col">
           <b>C S S</b>
        </div>
        <div class="col">
           <b>B O O T S T R A P</b>
        </div>
    </div>
</div>
<div class="skills2">
    <div class="row">
        <div class="col">
            <b>P H P</b>
        </div>
        <div class="col">
           <b>MY S Q L</b>
        </div>
        <div class="col">
            <b>J A V A S C R I P T</b>
        </div>
    </div>
</div>
    <section id="contact" class="container mt-4">
        <h2>Contact Me</h2>
        <div class="contact-links">
            <p><strong><i class="fa-solid fa-envelope"></i></strong><a href="mailto:kvs.gayathri25@gmail.com">kvs.gayathri25@gmail.com</a>
            <p><strong><i class="fa-brands fa-linkedin"></i></strong><a href="https://www.linkedin.com/in/kvsgayathri" target="_blank"> https://www.linkedin.com/in/kvsgayathri</a></p>
            <p><strong><i class="fa-brands fa-github"></i></strong><a href="https://github.com/Gayathri-Kancharla" target="_blank"> https://github.com/Gayathri-Kancharla</a></p>
        </div>
    </section>
    <script>
        function openResume() {
            var iframe = document.createElement('iframe');
            iframe.src = 'c:\\Users\\suren\\Downloads\\KVS GAYATHRI Resume.pdf';
            iframe.style.width = '100%';
            iframe.style.height = '600px';
            iframe.style.border = 'none';
            var modal = document.createElement('div');
            modal.style.position = 'fixed';
            modal.style.top = '0';
            modal.style.left = '0';
            modal.style.width = '100%';
            modal.style.height = '100%';
            modal.style.backgroundColor = 'rgba(0, 0, 0, 0.8)';
            modal.style.display = 'flex';
            modal.style.alignItems = 'center';
            modal.style.justifyContent = 'center';
            modal.appendChild(iframe);
            document.body.appendChild(modal);
           modal.addEventListener('click', function (e) {
             e.preventDefault();
                document.body.removeChild(modal);
                 });
        }
        document.getElementById('resumeButton').addEventListener('click', openResume);
    </script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
