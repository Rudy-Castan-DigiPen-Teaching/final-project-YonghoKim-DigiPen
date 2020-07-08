ProgrammingConcepts
====================
1. Shapes
-----------
![Shapes](https://user-images.githubusercontent.com/65119324/86886020-3251c780-c131-11ea-9d8c-40d3a7ddaecc.png)

push()

fill(this.c1);

translate(100, 100)

rotate(PI / -3.0);

ellipse(0, 0, 200, 100);

pop()

push()

strokeWeight(5);

fill('White')

ellipse(170, 100, 40, 40);

ellipse(130, 170, 40, 40);

fill('Black');

noStroke();

ellipse(175, 110, 20, 20);

ellipse(135, 160, 20, 20);

pop()

I use this code in my final project

2. Color
---------
![Colors](https://user-images.githubusercontent.com/65119324/86886505-07b43e80-c132-11ea-8dc8-9464cd833945.png)

noFill();

stroke('DarkViolet')

strokeWeight(10);

circle(100, 500, 80);

point(100, 500)

I use this code in my final project

3. Variables
-------------
![Variables](https://user-images.githubusercontent.com/65119324/86886651-4649f900-c132-11ea-9f8c-1c57821fda38.png)

let timeElapsed = 0;

timeElapsed += (millis() - time) / 1000;

if (timeElapsed > 1) {
    
      timeElapsed = 0
      
}

time = millis();

I use this code in my final project

4. Conditional Statements
-----------------------------
![ConditionalStatements](https://user-images.githubusercontent.com/65119324/86887164-1fd88d80-c133-11ea-8cff-24128413f57e.png)

if (ship_x2 == 60 || ship_x2 == 260 || ship_x2 == 460) {

    ship_hp -= 30
    
}

I use this code in my final project

5. Loops
------------
![Loop](https://user-images.githubusercontent.com/65119324/86887395-70e88180-c133-11ea-9c21-c0ef59ba74ef.png)

for(let T = 50; T < 550;) {

square(T, 350, 100);

  T += 100
  
}

for(let I = 50; I < 550;) {

square(I, 450, 100);

  I += 100
  
}

I use this code in my final project

6. Function
------------
![Function](https://user-images.githubusercontent.com/65119324/86887608-c886ed00-c133-11ea-89c2-5cac6242fb5d.png)

function keyPressed() {

if (Scene == 1 && Control == 1) {

playgo.Control1();

}

if (Scene == 1 && Control == 2) {

playgo.Control2();

}

if (Scene == 4 && Control == 1) {

playback.Control1();

}

if (Scene == 4 && Control == 2) {

playback.Control2();

}

}

I use this code in my final project

7. Classes
-----------
![Classes](https://user-images.githubusercontent.com/65119324/86887798-13086980-c134-11ea-9101-001fc98964a4.png)

class playScreen {

constructor() {

ship_x = 260

ship_y = 360

}

Control1() {

switch(keyCode) {

  case 37:
  
    if (ship_x > 60 && ship_x <= 460) {
    
    ship_x -=100
    
    }
    
  break;
  
  case 39:
  
    if (ship_x >= 60 && ship_x < 460) {
    
    ship_x += 100
    
    }
    
  break;
  
  case 38:
  
    if (ship_y > 360 && ship_y < 480) {
    
    ship_y -=100
    
    }
    
  break;
  
  case 40:
  
    if (ship_y >= 360 && ship_y < 460) {
    
    ship_y += 100
    
    }
    
  break;
  
}

}

Control2() {

  switch(keyCode) {
  
  case 65:
  
    if (ship_x > 60 && ship_x <= 460) {
    
    ship_x -=100
    
    }
    
  break;
  
  case 68:
  
    if (ship_x >= 60 && ship_x < 460) {
    
    ship_x += 100
    
    }
    
  break;
  
  case 87:
  
    if (ship_y > 360 && ship_y < 480) {
    
    ship_y -=100
    
    }
    
  break;
  
  case 83:
  
    if (ship_y >= 360 && ship_y < 460) {
    
    ship_y += 100
    
    }
    
  break;
  
}

}

}

I use this code in my final project

8. Array
---------

I don't use Array in my final project
