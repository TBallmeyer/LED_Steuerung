# LED_Steuerung
It is an ESP8266 (NodeMCU) based LED Controller.
It's based on the Arduino FastLED biebliotek and include different effekt modes.
1. a standart RGB-Color 
2. a sound reactive Effekt
3. a running light around the strip
4. a random Color mode 
5. and a kind of fairy lights

Plus You can define Times on wich the Strips shuld switchs on or off


Die LEd Steuerung basiert auf einem NodeMCU modul, wahlweise in Verbindung mit einer Real-Time-Clock (für zeitlich festgelegte Steuerungen) und - / oder einem Mikrofon (für ein VU-Meter);
Ergänzend zu der Steuerung des NodeMCU Moduls gibt es eine (mit dem MIT-Appinventor erstellte APP, zur einfacheren Steuerung).
Gesteuert wird der Controller entweder über eine Weboberfläche (Müsste allerding selber in der html.h datei ertellt werden) oder was einfacher ist über eine App.

Mit dem Programm ist es möglich 4 WS2812B LedStreifen gleichzeitig zusteuern.
Und es sind verschiedene Effekte im Porgramm hinterlegt...
1. Die normale RGB Farbwahl
2. ein VU-Meter, nutzbar nur in verbindung mit einem Mikrofon
3. eine art Lichterkette (x anzahl von LED leuchten in einer farbe, die nächsten x in einer anderen usw...)
4. ein lauflicht über alle streifen
5. und ein Zufallsmodus
