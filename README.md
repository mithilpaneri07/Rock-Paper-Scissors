# Rock-Paper-Scissors
Rock, Paper, Scissors is a simultaneous, zero-sum hand game played by two people, where each player forms one of three shapes to determine a winner.
Winning Conditions: The game follows an intransitive cycle: Rock beats Scissors (crushes them), Scissors beats Paper (cuts it), and Paper beats Rock (covers it).
Ties: If both players choose the same shape, the round is tied and is typically replayed until a winner emerges.
Coded Simple Rock-Paper-Scissors as a Favorite Game of Childhood using HTML, CSS, JS.

---
<h1>HTML</h1>
Simple HTML<br>
▪️3 Choice
▪️Score Board

---
<h1>CSS</h1><br>
Normal Color Palette and Text Colors <br>
▪️Calling Classes<br>
▪️@media (max-width: 600px)(responsive)
▪️cursor: pointer;

---
<h1>JavaScript</h1><br>
Logical with functions such as:
▪️genCompchoice
▪️drawGame
▪️showWinner
▪️playGame

```
const genCompchoice=()=>{
    const options=["rock","paper","scissors"];
    //rock,paper,scissors
    const randIdx=Math.floor(Math.random()*3);
    return options[randIdx];
```
<h2>Win Patterns 🏆</h2><br>

```
if(userChoice ==="rock"){
            //scissors,paper
            userWin=compChoice ==="paper"?false:true;
        }else if(userChoice ==="paper"){
            //rock,scissor
            userWin=compChoice ==="scissors"?false:true;
        }else{
            //rock,paper
            userWin=compChoice==="rock"?false:true;
        }
```
