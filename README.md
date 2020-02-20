# TTCQuiz

# Synopsis
This is a fun quiz built using HTML, CSS, Javascript and Jquery. The quiz asks a series of questions, saves replies and generates the final score based on user replies. 


# Screenshot 
<img width="769" alt="Screen Shot 2020-02-11 at 8 44 16 AM" src="https://user-images.githubusercontent.com/56641651/74241794-ba2ec500-4caa-11ea-9221-ee0a7684e86b.png">

# Acceptance Criteria 
Timed quiz 

GIVEN I am taking a code quiz
WHEN I click the start button
THEN a timer starts and I am presented with a question
WHEN I answer a question
THEN I am presented with another question
WHEN I answer a question incorrectly
THEN time is subtracted from the clock
WHEN all questions are answered or the timer reaches 0
THEN the game is over
WHEN the game is over
THEN I can save my initials and score

# Sample Code


    function makeQuestions() {
    questionNumber++;
    answer = questions[questionNumber].answer

    questionHead.textContent = questions[questionNumber].title;
    answerChoices.innerHTML = "";

    var choices = questions[questionNumber].choices;

    for (var q = 0; q < choices.length; q++) {
        var nextChoice = document.createElement("button");

        nextChoice.textContent = choices[q]
        answerBtn = answerChoices.appendChild(nextChoice).setAttribute("class", "p-3 m-1 btn btn-light btn-block");
    }

  
  
 # Installation
To use this portfolio, log into your GitHub account (if you don’t have a GitHub user profile, create one at https://github.com/join) and open this link in your browser: https://github.com/natashagils/ttcquiz. Then click on the "Fork" button at the top right corner and wait until the repo is forked. 



