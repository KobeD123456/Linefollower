# Gebruiksaanwijzing

### opladen / vervangen batterijen
Je laadt de batterijen op met een specifieke batterij lader

### draadloze communicatie
#### verbinding maken
uitleg over het verbinden van de robot met laptop / smartphone

#### commando's
•	 “run” => Starten met rijden (dit kan ook met de knop gedaan worden)
•	“stop” => Stoppen met rijden
•	“debug” => Tonen van de ingestelde parameters met de waarden
•	“calibrate” => Kalibreren van de sensoren
•	“set cycle ‘waarde’ ” => Set cycle naar ‘waarde’ (waarde moet cijfer zijn)
•	 “set power ‘waarde’ ” => Set power naar ‘waarde’ (waarde moet cijfer zijn)
•	 “set diff ‘waarde’ ” => Set diff naar ‘waarde’ (waarde moet cijfer zijn)
•	“set kp ‘waarde’ ” => Set kp naar ‘waarde’ (waarde moet cijfer zijn)
•	“set ki ‘waarde’ ” => Set ki naar ‘waarde’ (waarde moet cijfer zijn)
•	 “set kd ‘waarde’ ” => Set kd naar ‘waarde’ (waarde moet cijfer zijn)


### kalibratie
Voor de sensoren te kalibreren moet er in de seriële monitor via de computer of bluetooth module het commando “calibrate white” of “calibrate black” worden getypt. Indien het commando is doorgestuurd zal deze de waarden opslaan. Zorg er wel voor dat de line follower op een volledige witte ondergrond staat om de witte waarden op te slaan en bij de zwarte waarden op een volledige zwarte ondergrond.
### settings
De robot rijdt stabiel met volgende parameters:  
diff: 0.18
power: 80
kp: 3.8
ki : 0.1
kd : 0.1
### start/stop button
De knop die op het protypebordje is gemonteerd zorgt ervoor of de wagen in “Run” standt wordt gebracht of in “Niet RUN”.
![image](https://user-images.githubusercontent.com/115156903/209109758-73900116-eb08-4f85-a626-6a931d0ec0c2.png)

