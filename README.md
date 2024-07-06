<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./style.css" />
    <title>Document</title>
</head>
<body>
    <div class="containerNew">
        <header>
            <div>
                <a href="./Maxmarks.html">
                    <button class="scores-header" 
                            id="view-Max-marks">
                             view Max marks
                    </button>
                </a>
            </div>
            <div class="timer">
                <p>
                    Time:
                    <span id="timer">
                        0
                    </span>
                </p>
            </div>
        </header>
        <main class="quiz">
            <div id="quiz-start">
                <div class="landing" 
                     id="start-screen">
                    <h1 id="top">
                        Gyan Mandir Quiz Competition
                    </h1>
                    <h1>
                        GK Quiz 
                    </h1>
                    <p>
                        Please note that incorrect answers
                        will penalize your Marks/time
                        by ten seconds!
                    </p>
                    <button id="start">
                        Start Quiz
                    </button>
                </div>
            </div>
            <div class="hide" id="questions">
                <h2 id="question-words"></h2>
                <div class="options" id="options">
                </div>
            </div>
            <div class="hide" id="quiz-end">
                <h2>All Done!</h2>
                <p>Your final score is:
                    <span id="score-final">
                    </span>
                </p>
                <p>
                    Please enter your name:
                    <input type="text" 
                           id="name" 
                           max="3" />
                    <button id="submit-score">
                        Submit
                    </button>
                </p>
            </div>
            <div id="feedback" 
                 class="feedback hide">
            </div>
        </main>
    </div>
    <script src="./script.js"></script>
</body>
</html>
