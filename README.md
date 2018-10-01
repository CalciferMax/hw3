# hw3
1. function draw() {
  stroke(random(60, 70), 100, 90);
  line(x, height-10, x + random(-10, 10), height-10-random(h));

  x = x + 10;

  if (x > width) {
    x = random(10);
    h = h + 3;
  }
  
2.if (random() > 0.999) {
    noStroke();
    fill(255);
    rect(-1, -1, width+2, height-15);
    h = 10;
  }
 It comes by by the chance of 1/1000 every piece of grass grows 
  
3. It determines how long the grass grow each time.
4. It determines the color of each grass piece.
5. In the second argument it determines the lower y-axis of each line, and the fourth argument determines the upper y-axis of each line.
