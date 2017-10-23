# HW-3
void setup() {
  //Set Windows size
  size(500,500); 

} 
  
  
void draw() {
  
  background(#000000);

for (int y = 0; y <= height; y += 40) {
for (int x = 0; x <= width; x += 40) {

fill(#4F4C9B);
pushMatrix();
  translate(240,-113);
  rotate(radians(45));
  fill(#FF0303);
  rect(x,y,30,30);
  fill(#1603FF);
rect(x,y,20,20);
fill(#000000);
rect(x,y,10,10);

popMatrix();




  
  
}
}
}
