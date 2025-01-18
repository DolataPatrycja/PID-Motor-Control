# PID-Motor-Control
Projekt mikroprocesorowego systemu sterowania prędkością silników DC

#Otwieranie Telemetry Viewer (zainstalowana najnowsza wersja Java ze strony https://www.oracle.com/pl/java/technologies/downloads/#jdk23-windows)
1. Otwórz CDM jako administrator
2. Przejdź do folderu z plikiem Telemetry Viewer'a
3. Uruchom aplikację komendą:
   java --add-exports=java.base/java.lang=ALL-UNNAMED --add-exports=java.desktop/sun.awt=ALL-UNNAMED --add-exports=java.desktop/sun.java2d=ALL-UNNAMED -jar TelemetryViewer_v0.8.jar
5. Enjoy!

#Piny w Nucleo
1. PC8 - wypełnienie PWM
2. PE9 i PE11 - sygnały enkodera
