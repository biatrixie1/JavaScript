# JavaScript

function setup() {
  createCanvas(400, 400);
  background ("red")
}

function draw(){
  stroke("black");
  fill("grey");
    
    if (mouseIsPressed){
      rect (mouseX, mouseY, 20, 30);
    }
}
