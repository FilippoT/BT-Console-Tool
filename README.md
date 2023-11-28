# BT-Console-Tool
"Il progetto molto semplice ed economico da realizzare risolve un bel fastidio, sostituisce il cavo console con una connessione Bluetooth e incude una memoria flash utile per gli aggiornamenti dei dispositivi.

Inoltre, con la seguente applicazoine è possibile utilizzare uno smartphone Android/iOS come termiale, con la possibilità di creare dei tasti macro per i comandi più usati.

https://github.com/espressif/arduino-esp32/tree/master/libraries/BluetoothSerial

_______________________________________________
Materiali necessari:

-1 cavo USB tipo A

-1 cavo RJ-45

-1 modulo Bluetooth HC-05

-1 convertitore di livello MAX332CSE

-1 USB flash drive

_______________________________________________

RICORDA
Cambiare la password e il nome del modulo HC-05 è indispensabile per migliorare la sicurezza della connessione Bluetooth e l'identificazione del dispositivo.


Assicurati che il modulo HC-05 sia in modalità AT. (generalmente 9600 bps)

Puoi farlo tenendo premuto il pulsante di programmazione (KEY) mentre alimenti il modulo.
Per controllare se il modulo sia in modalità AT, invia il comando
"AT" nel terminale, Il modulo risponderà con "OK".


Invia i seguenti comandi per cambiare la password e il nome dispositivo:

AT+PSWD=NuovaPassword

AT+NAME=NuovoNome

NB: la procedura e/o i comandi potrebbero cambiare a seconda della versione firmware preinstallata nel modulo.


