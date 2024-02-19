

var radius;
var circ;
var points;
var length2;
var sides;
var repeat;

function draw_a_circle(radius, unnamed, unnamed) {
  circ = 2 * (3.14 * radius);
  for (var count5 = 0; count5 < 180; count5++) {
      moveForward(circ / 180);
    turnLeft(2);
  }
}

function draw_a_star(points, length2) {
  for (var count6 = 0; count6 < points; count6++) {
      moveForward(length2);
    turnLeft(360 / points);
    moveForward(length2);
    turnRight(720 / points);
  }
}

function draw_a_pinwheel(sides, length2, repeat) {
  for (var count8 = 0; count8 < repeat; count8++) {
      for (var count7 = 0; count7 < sides; count7++) {
          moveForward(length2);
      turnRight(360 / sides);
    }
    turnRight(60);
  }
}

function draw_a_triangle(length2) {
  for (var count9 = 0; count9 < 3; count9++) {
      moveForward(length2);
    turnLeft(120);
  }
}

function draw_a_shape(sides, length2) {
  for (var count10 = 0; count10 < sides; count10++) {
      moveForward(length2);
    turnLeft(360 / sides);
  }
}

function draw_a_house(length2) {
  for (var count11 = 0; count11 < 3; count11++) {
      moveForward(length2);
    turnLeft(120);
  }
  for (var count12 = 0; count12 < 4; count12++) {
      moveForward(length2);
    turnRight(90);
  }
}

function draw_a_square(length2, sides) {
  for (var count13 = 0; count13 < 4; count13++) {
      moveForward(length2);
    turnRight(90);
  }
}

for (var count2 = 0; count2 < 8; count2++) {
  for (var count = 0; count < 4; count++) {
      penColour('#0000cd');
    moveForward(100);
    turnRight(90);
  }
  turnLeft(45);
}
for (var count3 = 0; count3 < 8; count3++) {
  penColour('#0000cd');
  draw_a_circle(100, null, null);
  turnRight(45);
}
for (var count4 = 0; count4 < 4; count4++) {
  drawSticker("Cat", null);
  turnLeft(90);
}
