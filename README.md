


draw = function() {
    background(207, 254, 255);
    var corpoX = 200;
var corpoY = 220;
var corpoW =110;
var corpoz = 100;
var faceW = corpoW/2;
var botoesx = corpoX;
var botoesy = corpoY;
var olhosx = corpoX;
var olhosy = corpoY;
var bocax = corpoX;
var bocay = corpoY;
var raio = corpoW/10;
var raioy = corpoz/10;
 var mov = 204;
     fill(255, 252, 252);
rect(0, 258, 398, 142);
    fill(240, 209, 36);
    ellipse(corpoX, corpoY, corpoW, 99); // body?
    ellipse(corpoX, corpoY-70, faceW, 47); // face?
    // botoes
    fill(5, 13, 242);
    ellipse(botoesx, botoesy - 20, raio, raioy);
     fill(5, 13, 242);
    ellipse(botoesx, botoesy , raio, raioy);
     fill(5, 13, 242);
    ellipse(botoesx, botoesy + 20, raio,  raioy);
     //olhos
     fill(127, 253, 255);
    ellipse(olhosx +10, olhosy -75, raio,  raioy);
     fill(127, 253, 255);
    ellipse(olhosx - 10, olhosy - 75, raio,  raioy);
    // boca
    fill(255, 0, 0);
    arc(bocax, bocay - 60, raio+20,  raioy+10, 0, 180);
    // neve

    
stroke(255, 255, 255);
    fill(255, 255, 255);
    ellipse( 20, mov + 10, 10, 10);
    stroke(255, 255, 255);
    fill(255, 255, 255);
    ellipse( 60, mov+50, 10, 10);
    stroke(255, 255, 255);
    fill(255, 255, 255);
    ellipse( 100, mov+90, 10, 10);
    stroke(255, 255, 255);
    fill(255, 255, 255);
    ellipse( 140, mov+10, 10, 10);
    stroke(255, 255, 255);
    fill(255, 255, 255);
    ellipse( 180, mov+70, 10, 10);
    stroke(255, 255, 255);
    fill(255, 255, 255);
    ellipse( 250, mov+10, 10, 10);
    stroke(255, 255, 255);
    fill(255, 255, 255);
    ellipse( 300, mov+70, 10, 10);
    stroke(255, 255, 255);
    fill(255, 255, 255);
    ellipse( 350, mov+10, 10, 10);
    stroke(255, 255, 255);
    fill(255, 255, 255);
    ellipse( 380, mov+90, 10, 10);
   
    mov = mov + 1;
    
};
