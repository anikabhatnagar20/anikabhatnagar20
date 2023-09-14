---
toc: true
comments: true
layout: post
title: Calculator 
description: My calculator
type: hacks
courses: { compsci: {week: 1} }
---

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