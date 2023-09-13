---
## Anika Bhatnagar's Blog: 
## About Me:
My name is Anika Bhatnagar, and I am a sophmore. I took AP Computer Science Princepals to further advance my knowledge in this field, and to get more familar with coding. In the future, I would like to pursue a job as a biomedical engineer, so this helps me learn more about the techincal aspect. 

<a href="https://ibb.co/xsrrR4H"><img src="https://i.ibb.co/xsrrR4H/biomed.jpg" alt="biomed" border="0"></a>

<a href="https://imgbb.com/"><img src="https://i.ibb.co/MNS7j8C/image.png" alt="image" border="0"></a>
## Freeform: 

<a href="https://ibb.co/3kbjhvP"><img src="https://i.ibb.co/ZNrFTSb/img-3154.jpg" alt="img-3154" border="0"></a>

I have 4 people in my family, my mom, my dad, and my older brother. My two favorite apps are Netflix, and TikTok. I love to find new shows to watch with interesting plots. My favorite show right now is 13 reasons why. My favorite weather is when its bright and sunny! I love summer time, I love spending the day at the beach or pool, just enjoying the outdoors with some watermelon! Though I don't play, I do really love to watch soccer. Lastly, I love flowers!  
## Class Schedule: 

<html>
<head>
  <style>
    table {
      border-collapse: collapse;
      width: 50%;
      border: 4px solid pink; /* Pink border */
    }
    
    th, td {
      border: 2px solid black;
      padding: 8px;
    }
  </style>
</head>
<body>
  <table>
    <tr>
      <th>Period</th>
      <th>Class</th>
    </tr>
    <tr>
      <td>1</td>
      <td>AP Chemistry 2</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Honors Princepals of Engineering</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Honors Humanities </td>
    </tr>
    <tr>
      <td>4</td>
      <td>Integrated Math 3a</td>
    </tr>
    <tr>
      <td>5</td>
      <td>AP Computar Science Princepals</td>
    </tr>
  </table>
</body>
</html>
<a href="https://imgbb.com/"><img src="https://i.ibb.co/MNS7j8C/image.png" alt="image" border="0"></a> 
<html>
<head>
    <title>Calculator</title>
    <style>
        .calculator {
            width: 200px;
            border: 1px solid #ccc;
            padding: 10px;
            margin: 0 auto;
        }
    </style>
</head>

<body>
    <div class="calculator">
        <input type="text" id="display" disabled>
        <table>
            <tr>
                <td><button onclick="appendToDisplay('7')">7</button></td>
                <td><button onclick="appendToDisplay('8')">8</button></td>
                <td><button onclick="appendToDisplay('9')">9</button></td>
                <td><button onclick="appendToDisplay('/')">/</button></td>
            </tr>
            <tr>
                <td><button onclick="appendToDisplay('4')">4</button></td>
                <td><button onclick="appendToDisplay('5')">5</button></td>
                <td><button onclick="appendToDisplay('6')">6</button></td>
                <td><button onclick="appendToDisplay('*')">*</button></td>
            </tr>
            <tr>
                <td><button onclick="appendToDisplay('1')">1</button></td>
                <td><button onclick="appendToDisplay('2')">2</button></td>
                <td><button onclick="appendToDisplay('3')">3</button></td>
                <td><button onclick="appendToDisplay('-')">-</button></td>
            </tr>
            <tr>
                <td><button onclick="appendToDisplay('0')">0</button></td>
                <td><button onclick="clearDisplay()">C</button></td>
                <td><button onclick="calculate()">=</button></td>
                <td><button onclick="appendToDisplay('+')">+</button></td>
            </tr>
        </table>
    </div>
    
    <script>
        function appendToDisplay(value) {
            document.getElementById('display').value += value;
        }

        function clearDisplay() {
            document.getElementById('display').value = '';
        }

        function calculate() {
            var expression = document.getElementById('display').value;
            var result = eval(expression);
            document.getElementById('display').value = result;
        }
    </script>
</body>
</html>
<a href="https://imgbb.com/"><img src="https://i.ibb.co/MNS7j8C/image.png" alt="image" border="0"></a>
<html>
<head>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 0;
      padding: 0;
    }
    
    #game {
      margin-top: 50px;
    }
  </style>
</head>
<body>
  <h1>Rock Paper Scissors Game</h1>
  <div id="game">
    <button onclick="play('rock')">Rock</button>
    <button onclick="play('paper')">Paper</button>
    <button onclick="play('scissors')">Scissors</button>
    <p id="message"></p>
  </div>
  
  <script>
    const choices = ["rock", "paper", "scissors"];
    
    function play(playerChoice) {
      const computerChoice = choices[Math.floor(Math.random() * choices.length)];
      const message = document.getElementById("message");
      
      const result = getResult(playerChoice, computerChoice);
      
      message.textContent = `You chose ${playerChoice}. The computer chose ${computerChoice}. ${result}`;
    }
    
    function getResult(player, computer) {
      if (player === computer) {
        return "It's a tie!";
      } else if (
        (player === "rock" && computer === "scissors") ||
        (player === "paper" && computer === "rock") ||
        (player === "scissors" && computer === "paper")
      ) {
        return "You win!";
      } else {
        return "Computer wins!";
      }
    }
  </script>
</body>
</html>
<a href="https://imgbb.com/"><img src="https://i.ibb.co/MNS7j8C/image.png" alt="image" border="0"></a>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Quiz Game</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .quiz-container {
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
            background-color: #f9f9f9;
        }
        .question {
            font-size: 24px;
            margin-bottom: 10px;
        }
        .options {
            list-style-type: none;
            padding: 0;
        }
        .option {
            margin: 5px 0;
        }
        .option label {
            cursor: pointer;
        }
        #result {
            font-size: 20px;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="quiz-container">
        <h1 class="question" id="question">Question 1: What is the capital of France?</h1>
        <ul class="options" id="options">
            <li class="option">
                <input type="radio" name="answer" id="option1" value="a">
                <label for="option1">a) London</label>
            </li>
            <li class="option">
                <input type="radio" name="answer" id="option2" value="b">
                <label for="option2">b) Madrid</label>
            </li>
            <li class="option">
                <input type="radio" name="answer" id="option3" value="c">
                <label for="option3">c) Paris</label>
            </li>
        </ul>
        <button onclick="checkAnswer()">Submit Answer</button>
        <p id="result"></p>
    </div>

    <script>
        const correctAnswer = 'c'; // The correct answer for the question

        function checkAnswer() {
            const selectedOption = document.querySelector('input[name="answer"]:checked');
            const result = document.getElementById('result');

            if (selectedOption) {
                if (selectedOption.value === correctAnswer) {
                    result.textContent = 'Correct! Well done!';
                } else {
                    result.textContent = 'Incorrect. Please try again.';
                }
            } else {
                result.textContent = 'Please select an option.';
            }
        }
    </script>
</body>
</html>


<a href="https://imgbb.com/"><img src="https://i.ibb.co/MNS7j8C/image.png" alt="image" border="0"></a>


## Errors and Trouble Shooting Along the Way:
-The largest issue I faced was lack of storage. When I started this class, I figured out I had about 7 GBs of storage left. I ended up spending a lot of time trying to delete things, and figuring out what to delete since about 180 GBs were labeled under "Others." 

-Another big issue we faced was that the make command would not work. At first, we thought the issue was with the notebook converter because when trouble shooting, we deleted the notbook, and the make command was working. Though we later found out there was an issue with the python version we had. We had python3, and once we got rid of the 3, it ended up working!  

-Another struggle we came across was when trying to insert a picture. When we added a image, rather then the image showing up on the blog, there was a small blue folder icon, and to fix this we figured out we needed to adjust the code. In the end, we was able to create our blog, and information add about us and our experience creating the blog. 


</body>
</html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>White Cursive Font on Purple Background</title>
    <style>
        body {
            background-color: pink; /* Set background color to purple */
            color: blue; /* Set text color to white */
            font-family: times new roman; /* Use cursive font-family */
            font-size: 18px; /* Set the font size (adjust as needed) */
        }
    </style>