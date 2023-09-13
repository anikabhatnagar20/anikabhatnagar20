---
toc: true
comments: false
layout: post
title: Stopwatch
description: My version of a stopwatch for one minute
type: hacks
courses: { compsci: {week: 3} }
---


<html>
<head>
    <title>Analog Clock with Stopwatch</title>
    <style>
        #clock {
            width: 200px;
            height: 200px;
            border: 5px solid #ffb6c1;
            border-radius: 50%;
            position: relative;
        }

        .hand {
            position: absolute;
            transform-origin: 100%;
            width: 5px;
            background: #333;
            top: 30%;
            left: 50%;
            transform: translateX(-50%);
        }

     

        #second-hand {
            height: 70px;
            background: #ffb6c1;
            z-index: 1;
        }

        .number {
            position: absolute;
            font-size: 14px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div id="clock">
        <div class="hand" id="hour-hand"></div>
        <div class="hand" id="minute-hand"></div>
        <div class="hand" id="second-hand"></div>
        <!-- Numbers for hours and minutes -->
        <div class="number" style="top: 10px; left: 85px;">1</div>
        <div class="number" style="top: 95px; left: 183px;">15</div>
        <div class="number" style="top: 180px; left: 90px;">30</div>
        <div class="number" style="top: 95px; left: 10;">45</div>
        <!-- Minute markers -->
        
    </div>


    <script>
        let stopwatchInterval;
        let stopwatchSeconds = 0;

        function updateClock() {
            const now = new Date();
            const hours = now.getHours();
            const minutes = now.getMinutes();
            const seconds = now.getSeconds();

            const hourDeg = (hours % 12) * 30 + (minutes / 60) * 30;
            const minuteDeg = minutes * 6 + (seconds / 60) * 6;
            const secondDeg = seconds * 6;

            const hourHand = document.getElementById('hour-hand');
            const minuteHand = document.getElementById('minute-hand');
            const secondHand = document.getElementById('second-hand');

            hourHand.style.transform = `rotate(${hourDeg}deg)`;
            minuteHand.style.transform = `rotate(${minuteDeg}deg)`;
            secondHand.style.transform = `rotate(${secondDeg}deg)`;
        }

        function startStopwatch() {
            clearInterval(stopwatchInterval);
            stopwatchSeconds = 0;
            stopwatchInterval = setInterval(updateStopwatch, 1000);
        }

        function updateStopwatch() {
            if (stopwatchSeconds >= 60) {
                clearInterval(stopwatchInterval);
                stopwatchSeconds = 0;
            } else {
                stopwatchSeconds++;
            }
        }

        setInterval(updateClock, 1000);
    </script>
</body>
</html>
