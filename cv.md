# Daniel Bielecki
## Junior Frontend Developer
## Contact details:
**Email:** bieleckidaniel35@gmail.com
## About myself
Hello, I am a beginner Frontend Developer from Warsaw, Poland. In programming, I like the intellectual challenges it brings - it's like a puzzle to be solved. Besides Frontend I am an amateur cyclist and I also like hiking.
## My goals
In my past job as a cashier I created a simple but useful app in form of a website which helps cashiers with their job. After some time I realised that I can give myself a try with programming and I started an on-line JS/Frontend development course in RSSchool. My goal is to get a Junior Frontend Developer job in the near future.
## Skills
- HTML
- CSS
- Java Script
## Code example
Code from one of my projects:

```
function startGame() {
        currentSnake.forEach(index => squares[index].classList.remove('snake'));
        squares[appleIndex].classList.remove('apple');
        clearInterval(interval);
        score = 0;
        randomApple();
        direction = 1;
        scoreDisplay.innerText = score;
        intervalTime = 1000;
        currentSnake = [2,1,0];
        currentIndex = 0;
        currentSnake.forEach(index => squares[index].classList.add('snake'));
        interval = setInterval(moveOutcomes, intervalTime);
    }
```
## Education
2004 - 2007 King Casimir the Great High School in Białystok
## Courses
RSSchool JS / Front-end (In progress)
## languages
- English (B2)
- Polish (native)