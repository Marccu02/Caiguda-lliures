# Caiguda-lliure

color c = color(0);
float x = 0;
float y = 100;
float yspeed = 1;
float xspeed = 1;
void setup() {
  size(200,200);
}
void draw() {
  background(255);
  move();
  display();
}
 void move (){
   x = x + xspeed*1
   y=y+speed
   if (x > width) {
x = 0;
   }

{ y = x+ yspeed*5;
   if (y > width) {
y = 0;}
}
 }
 void display() {
   fill(c);
   rect(x,y,30,10)
   }
   
   1- Laura, Javi, Julia, Marc
   2-Encara no ho hem calculat
   3-Primer hem fet la caiguda d'una forma diferent, accelerant cada cop, anant afegint la speed enlloc de deixar que acceleri la y
   
