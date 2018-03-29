TouchDesigner und 3D mit Video
====================

 

## Satelite

### SOP:Copy

automatisch generiert meherere 3D-Model Instanzen.

![](K2/copy.PNG)

**sphere1:**

radius 0.2 0.2 0.2

**circle1:**

divisions 15

 

## SOP:Copy Anwendung1

 mit Video

![ide](K2/video.PNG)



### SOP:Copy Anwendung2

mit Kamerabewegungen

 

![amer](K2/camera.PNG)

Export chop zwischen animation1 und cam1

 

Animation-Editor steurt die Kamerabewegung

 ![nimatio](K2/animation.PNG)



## Gold Cello in TD

### SOP: FileIn 

3D Model in TD laden

![ell](K2/cello.PNG)



Viele 3D Modelle sind kostenlos verfugbar auf https://www.turbosquid.com/



Man kann mit Phong-OP Texture und Modell kombinieren.

![extur](C:\Users\chikashi\Desktop\Software2-SS2018\K2\texture.PNG)



## Particles in TD



### Wichtigste Parameter

- Forces
  - Wind xyz: simuliert Wind 
  - Tubulance xyz: simuliert turbulente Strömung
- Particles
  - Life Expect: Lebensdauer eines Particles
  - Birth: Geburtsrate von Particles



![articl](C:\Users\chikashi\Desktop\Software2-SS2018\K2\particle.PNG)



### Instancing (Wiederholung)



![nstancin](C:\Users\chikashi\Desktop\Software2-SS2018\K2\Instancing.PNG)



Mehrere Instanzen eines 3D Models kann man mit Instance CHOP/DAT erzeugen.

## Particle System + Instancing

![article+instancin](C:\Users\chikashi\Desktop\Software2-SS2018\K2\particle+instancing.PNG)

CHOP: SopTo extrahiert die Positionen jedes Particles. Man kann diese extrahierte Daten als Quelle von Instancing benutzen.



## Particle + MAT

Jeder Particle ist jetzt eine Instanz des 3D Models deshalb mit MAT-Ops eine Texture verknupfen.



![ideo_ball](C:\Users\chikashi\Desktop\Software2-SS2018\K2\video_balls.PNG)



# Wasserfall-Brunnen Effekt

Projection Mapping ist auch moglich

![rojection_agains](C:\Users\chikashi\Desktop\Software2-SS2018\K2\projection_against.PNG)