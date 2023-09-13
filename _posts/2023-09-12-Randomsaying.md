---
toc: true
comments: false
layout: post
title: Inspirational Saying Generator 
description: Gives random sayings 
type: hacks
courses: { compsci: {week: 3} }
---
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inspirational Sayings</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            text-align: center;
        }

        .container {
            max-width: 400px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        }

        h1 {
            color: #333;
        }

        #inspirational-saying {
            font-size: 18px;
            margin: 20px 0;
        }

        #generate-saying {
            background-color: #007BFF;
            color: #fff;
            border: none;
            border-radius: 5px;
            padding: 10px 20px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        #generate-saying:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Inspirational Sayings</h1>
        <p id="inspirational-saying">Click the button below to get inspired!</p>
        <button id="generate-saying">Generate</button>
    </div>

    <script>
        // Define an array of inspirational sayings
        const inspirationalSayings = [
            "Believe in yourself and all that you are. Know that there is something inside you that is greater than any obstacle.",
            "The only way to do great work is to love what you do.",
            "Success is not final, failure is not fatal: It is the courage to continue that counts.",
            "Your time is limited, so don't waste it living someone else's life.",
            "The future belongs to those who believe in the beauty of their dreams."
        ];

        // Function to generate a random saying
        function generateRandomSaying() {
            const randomIndex = Math.floor(Math.random() * inspirationalSayings.length);
            const saying = inspirationalSayings[randomIndex];
            document.getElementById("inspirational-saying").textContent = saying;
        }

        // Add a click event listener to the "Generate" button
        document.getElementById("generate-saying").addEventListener("click", generateRandomSaying);

        // Initial saying on page load
        generateRandomSaying();
    </script>
</body>
</html>