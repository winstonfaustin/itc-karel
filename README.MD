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
