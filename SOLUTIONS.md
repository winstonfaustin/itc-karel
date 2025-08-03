<!-- Easy Solution -->

// You can define your own functions
function turnRight() {
turnLeft();
turnLeft();
turnLeft();
}

// Your program must be in a main() function
function main() {
move();
move();
turnLeft();
move();
move();
move();
move();
move();
move();
pickBeeper();
turnRight();
move();
turnRight();
move();
move();
move();
move();
turnLeft();
move();
pickBeeper();
move();
move();
turnRight();
move();
move();
pickBeeper();
}

<!-- Medium Solution -->

// You can define your own functions
function turnRight(){
turnLeft();
turnLeft();
turnLeft();
}

function jumpHurdle(){
turnLeft();
move();
move();
move();
move();
move();
move();
move();
turnRight();
move();
turnRight();
move();
move();
move();
move();
move();
move();
move();
turnLeft();
}

// Your program must be in a main() function
function main() {
move();
jumpHurdle();
for(3){
move();
pickBeeper();
jumpHurdle();
move();
pickBeeper();
jumpHurdle();
move();
pickBeeper();
}
}

<!-- Hard Solution -->

// You can define your own functions
function turnRight() {
turnLeft();
turnLeft();
turnLeft();
}

function turnAround(){
turnLeft();
turnLeft();
}

// Your program must be in a main() function
function main() {
// Commands end in ();
turnRight();
move();
move();
turnLeft();
move();
move();
turnRight();
move();
turnRight();
move();
move();
turnLeft();
move();
turnLeft();
move();
pickBeeper();
turnAround();
move();
turnRight();
move();
turnRight();
move();
move();
turnRight();
move();
move();
turnRight();
move();
move();
turnLeft();
move();
move();
putBeeper();
turnLeft();
move();
move();
move();
move();
turnLeft();
move();
move();
turnRight();
move();
turnLeft();
move();
move();
move();
move();
turnRight();
move();
move();
turnLeft();
move();
pickBeeper();
turnAround();
move();
move();
move();
turnRight();
move();
turnLeft();
move();
move();
turnLeft();
move();
turnRight();
move();
move();  
}
