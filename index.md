---
title: Home
layout: home
---

# JULIUS'S WEBSITE FOR CS10 BJC
## I like coding and robotics! 

[Snap Final Project Link Github](https://github.com/JuliusZhou124/OpenStreetMapParser)
[Snap Final Project Link](https://snap.berkeley.edu/project?username=jzhou124&projectname=final%2dproject%2dfailed%2dgeneralization)

![Julius' Image](imgur-cs-thing.png)

<object data="https://personal.math.ubc.ca/~CLP/CLP3/combined_clp_3.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://personal.math.ubc.ca/~CLP/CLP3/combined_clp_3.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://personal.math.ubc.ca/~CLP/CLP3/combined_clp_3.pdf">Download PDF</a>.</p>
    </embed>
</object>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Random Dog Image</title>
</head>
<body>
    <h1>Random Dog Image</h1>
    <button id="fetchDogButton">Fetch a Dog Image</button>
    <br><br>
    <img id="dogImage" src="" alt="Random Dog" width="300">
    
    <script>
        document.getElementById('fetchDogButton').addEventListener('click', function() {
            fetch('https://dog.ceo/api/breeds/image/random')
                .then(response => response.json())
                .then(data => {
                    document.getElementById('dogImage').src = data.message;
                })
                .catch(error => console.error('Error fetching dog image:', error));
        });
    </script>

    <iframe width="480" height="390" frameBorder=0 allowfullscreen allow="geolocation; microphone;camera" src="https://snap.berkeley.edu/embed?projectname=final%2dproject%2dfailed%2dgeneralization&username=jzhou124&showTitle=true&showAuthor=true&editButton=true&pauseButton=true"></iframe>
</body>
</html>
