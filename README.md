# **THIS TUTORIAL IS FOR WINDOWS / QUESTO TUTORIAL E' STATO CREATO PER IL SISTEMA OPERATIVO DI WINDOWS**

## **ENGLISH TUTORIAL**
**HOW TO DONWLOAD & SETUP NGROK:**
1. Go to the `ngrok WebSite`. *(https://ngrok.com/)*
2. Create a `ngrok Account`. *(without it you can't use ngrok)*
3. Once you created the Account you can download `ngrok` or use this link to download it: *https://ngrok.com/download*
4. Finished downloading `ngrok` you will need to create a Folder called *"ngrok" (or whatever you want)* where you want.
5. Take the content of the `.zip` downloaded before and copy it in the Folder that you created.
6. Inside of you `ngrok Folder` you need to `SHIFT + RIGHT-CLICK` e navigate until you find the `Open PowerShell window here` option.
7. Once in the PowerShell you'll need to go back to the `ngrok Site` *(https://ngrok.com)* in your Account Section.
8. You should see on the left a section called *Your Authtoken*, once opened you'll need to copy your `Token`.
9. Open the PowerShell Window and write `.\ngrok.exe config add-authtoken <Token>`, replace `<Token>` with the one copied earlier.
10. You've finished the Installation & Setup of `ngrok`! :D

**HOW TO USE NGROK TO HOST A MINECRAFT WORLD FOR YOUR FRIENDS:**
***DISCLAIMER: Use ngrok ONLY with people you trust because if someone knows how they can get your IP!***

1. Open `ngrok` as shown in the *6th* point of Installation & Setup.
2. Enter the Minecraft World of your choice.
3. Press `ESC` e click on *Open to LAN*, set your options e click on *Start LAN World*.
4. Once done you'll see in the Chat a message with the Port on which the World ha been opened to LAN, copy it and go on the `ngrok PowerShell Window`.
5. Inside of the PowerShell write `.\ngrok.exe tcp <Port>`, replace `<Port>` with the number that you copied earlier.
6. The PowerShell will change aesthetically and you should see a different window, go under the voice that says `Forwarding` and copy whatever you see before `->` and after the `tcp://`, it should look like something like this `4.tcp.eu.ngrok.io:13475`.
*(Note that to copy the IP you'll need to click `RIGHT-CLICK` and not `CTRL + C` because this will close the Terminal)*
7. Now you only need to send the IP to your friends and have fun!

## **ITALIAN TUTORIAL**
**COME SCARICARE E CONFIGURARE NGROK:**
1. Andare sul sito di ngrok. *(https://ngrok.com/)*
2. Creare un Account di ngrok. *(senza di esso non potrete usare ngrok)*
3. Una volta creato l'Account potete scaricare ngrok dal sito oppure utilizzando questo link: *https://ngrok.com/download*
4. Finito di scaricare create una cartella chiamata *"ngrok" (o come preferite)* dove volete all'interno del vostro PC.
5. Prendere il contenuto del `.zip` scaricato precedentemente e spostatelo nella cartella appena creata.
6. All'interno della vostra cartella `ngrok` premete in uno spazio senza elementi la combinazione di tasti `SHIFT + TASTO DESTRO` e navigate fino alla voce che dice `Apri nel PowerShell di Windows`.
7. Una volta aperto il PowerShell dovete andare sul sito di ngrok *(https://ngrok.com/)* nella sezione del vostro Account.
8. Dovreste vedere sulla sinistra una sezione chiamata *Your Authtoken*, una volta aperta quella sezione dovrete copiare il vostro `Token`.
9. Aprite la finestra del PowerShell e digitate `.\ngrok.exe config add-authtoken <Token>`, cambiate `<Token>` con il vostro.
10. Hai finito l'Installazione e la Configurazione di ngrok! :D

**COME USARE NGROK PER HOSTARE I PROPRI MONDI PER I PROPRI AMICI:**
***DISCLAIMER: Usate ngrok UNICAMENTE con le persone di cui vi fidate siccome una persona competente potrebbe utilizzarlo per risalire al vostro IP!***
1. Aprite `ngrok` come mostrato nel passaggio *6* dell'Installazione & Configurazione.
2. Entrate nel mondo di Minecraft che volete aprire ai vostri amici.
3. Premete `ESC` e cliccate su *Apri in LAN / Open to LAN*, inserite le impostazioni che volete e dopo cliccate su *Avvia il mondo in LAN / Start LAN World*.
4. Una volta fatto ciò in Chat vi comparirà la Porta sulla quale è stato aperto il vostro mondo, copiatela e andate sul PowerShell di `ngrok`.
5.  All'interno del PowerShell scrivete `.\ngrok.exe tcp <Porta>`, sostituite `<Porta>` con il numero che avete appena copiato.
6. Il PowerShell cambierà estetica e dovreste vedere una schermata diversa, dovete andare sotto la voce di `Forwarding` e copiare tutto quello che si trova prima del `->` e dopo il `tcp://`, dovrebbe assomigliare a qualcosa di questo tipo `4.tcp.eu.ngrok.io:13475`.
*(Piccolo appunto per copiare l'IP dovete evidenziarlo e premere `TASTO DESTRO` e non `CTRL + C` poiché questa combinazione chiude il Terminale)*
7. Ora l'unica cosa che ti manca è inoltrare l'IP ai tuoi amici e divertirti!
