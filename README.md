# BT-Console-Tool
"Il progetto ha come scopo la sostituzione del cavo di console con una connessione Bluetooth e incude una memoria flash utile per gli aggiornamenti dei dispositivi.

Inoltre, con questa applicazoine è possibile utilizzare uno smartphone android come termiale.

https://play.google.com/store/apps/details?id=de.kai_morich.serial_bluetooth_terminal

_______________________________________________
Materiali necessari:

1 cavo USB tipo A

1 cavo RJ-45

1 modulo Bluetooth HC-05

1 convertitore di livello MAX332CSE

1 USB flash drive 
_______________________________________________


Cambiare la password e il nome del modulo HC-05 è indispensabile per migliorare la sicurezza della connessione Bluetooth e l'identificazione del dispositivo.


Assicurati che il modulo HC-05 sia in modalità AT. (generalmente 9600 bps)
Puoi farlo tenendo premuto il pulsante di programmazione (KEY) mentre alimenti il modulo.
Per controllare se il modulo sia in modalità AT, inviate il comando
"AT" nel terminale, Il modulo risponderà con "OK".


Invia i seguenti comandi AT per cambiare la password e il nome dispositivo:

AT+PSWD=NuovaPassword
AT+NAME=NuovoNome


