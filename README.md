# BT-Console-Tool
![image](https://github.com/user-attachments/assets/b9682e6e-7acf-4071-af1f-07ba006e2e3a)

Questo progetto fornisce una soluzione pratica ed economica per sostituire il tradizionale cavo console con una connessione Bluetooth, eliminando così i limiti fisici di un collegamento cablato. Oltre alla connettività wireless, il sistema integra una memoria flash, ideale per gestire gli aggiornamenti firmware e archiviare configurazioni dei dispositivi.

Grazie all’applicazione dedicata, gli utenti possono utilizzare uno smartphone Android o iOS come terminale, con la possibilità di creare tasti macro personalizzati per automatizzare i comandi più utilizzati. Per dettagli tecnici, consultare la documentazione ufficiale:

https://github.com/espressif/arduino-esp32/tree/master/libraries/BluetoothSerial

_______________________________________________

Materiali necessari:

-1 cavo USB tipo A

-1 cavo RJ-45

-1 modulo Bluetooth HC-05

-1 convertitore di livello MAX332CSE

-1 USB flash drive

_______________________________________________

![image](https://github.com/user-attachments/assets/85ba1bac-b0cc-440a-8bbe-72050df56418)



Configurazione opzionale del modulo Bluetooth HC-05
1. Sicurezza e personalizzazione
Per incrementare la sicurezza della connessione, si consiglia di cambiare la password predefinita e il nome del dispositivo.

Configura una connessione seriale a 9600 bps.

Porta il modulo HC-05 in modalità AT command: tieni premuto il pulsante di programmazione (KEY) mentre alimenti il modulo.

Verifica l’accesso alla modalità AT inviando il comando:
"AT"
Il modulo risponderà con:
"OK"

Configura il modulo con i seguenti comandi:

Cambia la password:
"AT+PSWD=NuovaPassword"

Cambia il nome del dispositivo:
"AT+NAME=NuovoNome"


2. Note tecniche
La modalità AT è fondamentale per configurare correttamente il modulo.
La procedura e i comandi possono variare in base alla versione del firmware preinstallato nel modulo HC-05. Si consiglia di consultare la documentazione ufficiale del produttore per dettagli specifici.

![image](https://github.com/user-attachments/assets/d205d0e6-82f7-4179-b780-bb3e8abb413b)



