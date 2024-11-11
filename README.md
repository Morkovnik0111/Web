# Web
Project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>task4</title>
    <link rel="stylesheet" media="screen" href="style.css">
</head>
<body>
    <header></header>
    <main>
        <div class="vieww">
            <div class="container">
                <h1>Design and Development</h1>
                <div class="grid-container">
                    <div class="grid-item">
                        <h2>01</h2>
                        <p>Sample text. Click to select the text box. Click again or double click to start editing the text.</p>
                        <a href="#">learn more</a>
                    </div>
                    <div class="grid-item">
                        <h2>02</h2>
                        <p>Sample text. Click to select the text box. Click again or double click to start editing the text.</p>
                        <a href="#">learn more</a>
                    </div>
                    <div class="grid-item">
                        <h2>03</h2>
                        <p>Sample text. Click to select the text box. Click again or double click to start editing the text.</p>
                        <a href="#">learn more</a>
                    </div>
                    <div class="grid-item">
                        <h2>04</h2>
                        <p>Sample text. Click to select the text box. Click again or double click to start editing the text.</p>
                        <a href="#">learn more</a>
                    </div>
                    <div class="grid-item">
                        <h2>05</h2>
                        <p>Sample text. Click to select the text box. Click again or double click to start editing the text.</p>
                        <a href="#">learn more</a>
                    </div>
                    <div class="grid-item">
                        <h2>06</h2>
                        <p>Sample text. Click to select the text box. Click again or double click to start editing the text.</p>
                        <a href="#">learn more</a>
                    </div>
                </div>
            </div>
        </div>
    </main>
    <footer>
        <p>image by <a href="#">freepik</a></p>
        
    </footer>
</body>
</html>


CSS

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Arial, "sans-serif";
    background: rgb(230, 230, 229);
    display: flex;
    flex-direction: column;
    align-items: center;
    height: 100vh;
    overflow-y: scroll;
    background: rgb(209, 108, 1);
}
.vieww {
    width: 100%;
    display: flex;
    justify-content: center;
}
.container {
    max-width: 850px;
    margin: 20px;
    padding: 20px 0px;
}
h1 {
    text-align: center;
    font-size: 3em;
    margin-bottom: 50px;
    color: white;
}
.grid-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 3fr));
    gap: 10px;
}
.grid-item {
    background-color: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    text-align: center;
}
.grid-item h2 {
    font-size: 3em;
    color: #FFD700;
}
.grid-item p {
    font-size: 1em;
    margin: 15px 0;
}


.grid-item a {
    font-size: 1.2em;
    color: #26251d;
    border-bottom: 2px solid #26251d;
    text-decoration: none;
    transition: all .2s ease-in-out;
}

.grid-item a:hover {
    border-bottom: 2px solid #FFD700;
}
