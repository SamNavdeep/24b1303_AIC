AI PROJECT:

problem statement: a 4 wheeler bot which identifies the objects and places the misplaced obect in predefiened place.

real world impact: often many objecs are misplaed at home, offices and working areas, ultimately which get lost. this bot could minimize the possibilities of losing the objects as it places them in their correct position back.

technical approch:

what we need:
 a sensor which can identify the object, other materials required to maake a bot.

steps:
mechanical:
attach all the mechanical parts from the chass to the wheels

electrical:
connect the arduiono to the motor diver and to the sensor

software:
we need to do the image recognition here, initially we train the model using large set of image data, once its validation accuracy is decent, we can expect it to be recognising the images(assuming that there are limited set of objects that the bot needs to carry). now the bot needs to know the position, for this the bot needs to know its locstion hece it can again use the image recognition to know how the path is, it compares the objects near the path with the map(which would be preloaded) and identifies its location.



