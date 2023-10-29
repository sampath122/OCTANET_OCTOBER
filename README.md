# OCTANET_OCTOBER
my landing page using HTML and CSS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,
    initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="graph.css">
    <title>Photography project</title>
</head>

<body>
    <main>
        <!--Landing Area-->
        <div id="landing">
            <div id="landing-text">
                <div id="landing-text-inner">
                    <h1>My Photography</h1>
                    <h2>Beautiful Images</h2>
                    <a href="#images" class="btn" id="view-work">
                        View Work
                    </a>
                </div>
            </div>
            <div id="landing-image"></div>
        </div>
        <div id="images">
            <div id="header">
                <h2>My Work</h2>
            </div>

            <img src="https://source.unsplash.com/1600x900/?nature,water
" alt="nature image">
            <div class="caption">
                <h3>Photo One</h3>
                <p>Trees and the Soul. “A tree is our most intimate contact with nature.” ... Provident, error!</p>
            </div>
            <img src="https://source.unsplash.com/1600x900/?nature,trees
            " alt="nature image">
            <div class="caption">
                <h3>Photo Two</h3>
                <p> Lost in the serenity of the still waters.Provident, error!</p>
            </div>
            <img src="https://source.unsplash.com/1600x900/?nature,flowers
            " alt="nature image">
            <div class="caption">
                <h3>Photo Three</h3>
                <p>No better way to recharge than outside. Provident, error!</p>
            </div>
            <img src="https://source.unsplash.com/1600x900/?nature,animals
            " alt="nature image">
            <div class="caption">
                <h3>Photo Four</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident, error!</p>
            </div>
            <img src="https://source.unsplash.com/1600x900/?nature,clouds
            " alt="nature image">
            <div class="caption">
                <h3>Photo Five</h3>
                <p>Finding solace in the gentle lapping of the lake. Provident, error!</p>
            </div>
        </div>
    </main>

    <footer>
        <h3>Get In Touch</h3>
        <p>Email or call us to set up a consult</p>
        <p>Email: <strong>contactus sam123@gmail.com</strong></p>
        <p>Phone:
            <a href="+91 7569495033">
                <strong>(+91) 333-3333</strong>
            </a>
        </p>
    </footer>

</body>
 
</html>


@import url('https://fonts.googleapis.com/css?family=Roboto+Condensed');

html {
    scroll-behavior: smooth;
}

body {
    font-family: 'Roboto Condensed', sans-serif;
    margin: 0;
    background: #eee;
    height: auto;
}

h1 {
    font-weight: 400;
    font-size: 2.5rem;
    text-transform: uppercase;
    margin: 0;
}

h2 {
    font-weight: 400;
    font-size: 1.2rem;
    text-transform: capitalize;
    margin: 0;
}

img {
    display: block;
    width: 100%;
}

main {
    max-width: 900px;
    margin: auto;
    box-shadow: 30px 0px 40px rgba(0, 0, 0, 0.1), -30px 0px 40px rgba(0, 0, 0, 0.1)
}

#landing {
    background: #fff;
}

#landing-text {
    display: flex;
    flex: 0 1 40vw;
    height: 50vh;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding-right: 1rem;
    padding-left: 1rem;
}

#landing-text h2 {
    color: #888;
}

#landing-image {
    background: url(https://source.unsplash.com/De8wMYoSSBc);
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    height: 50vh;
    flex: 0 1 60vw;
    margin: 0;
}

.btn {
    padding: 0.5rem 2rem;
    border: 1px solid #ccc;
    display: inline-block;
    margin: 2rem 0 0;
    border-radius: 50px;
    text-decoration: none;
    color: #333;
    transition: background 500ms ease;
}

.btn:hover {
    background: #f4f4f4;
}

#header {
    padding: 1.5rem;
    text-align: center;
    background: #333;
    color: #fff;
}

#header h2 {
    border-left: 1px dotted #fff;
    border-right: 1px dotted #fff;
    display: inline-block;
    padding-right: 1rem;
    padding-left: 1rem;
}

.caption {
    padding: 0.8rem;
    text-align: center;
}

footer {
    text-align: center;
    padding: 2rem 1rem;
    margin: auto;
    color: #333;
}

footer h3 {
    font-size: 3rem;
    margin-bottom: 0;
}

footer p a {
    text-decoration: none;
    color: red;
}

/*Screen Sizes 500px +*/

@media(min-width: 31.25rem) {
    #landing {
        display: flex;
        height: 100%;
    }

    #landing-text {
        height: 100vh;
    }

    #landing-image {
        height: 100vh;
    }
}

/*Screen Sizes 700px +*/

@media(min-width: 43.75rem) {
    .btn {
        padding: 1rem 3rem;
    }
}
