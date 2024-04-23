File: Calculator.java
-LOC = 188
-Imena varijabli su jasna i deskriptivna
-Logika kalkulatora je uokvirena unutar statičkih metoda
-Kod uključuje osnovno rukovanje greskama za raščlanjivanje float vrednosti iz input stringa. Medjutim, povratna poruka "ERROR" ne daje dovoljno informacija o razlogu pojave greske
-Metoda Calculate procenjuje izraz na osnovu redosleda operacija
-Aritmetika sa pomerajucim zarezom može dovesti do problema s preciznoscu, posebno kada se radi o deljenju
-Dizajn kalkulatora je jednostavan i pogodan za osnovne aritmetičke operacije


File: Start.java 
-LOC = 26
-Imena varijabli su jasna i deskriptivna
-Kod traži od korisnika da unese input i neprekidno cita unos dok korisnik ne upise "exit"
-Upotreba objekta Scanner (scanIn) omogucava citanje inputa sa konzole
-While petlja efikasno rukuje iterativnim procesom citanja izraza i provere izlaznog uslova
-Klasa Start stupa u interakciju s klasom Calculator prosledjivanjem inputa njenoj metodi Run
-Objekt Scanner se zatvara kada se prekine program, osiguravajuci pravilno upravljanje resursima
-Dizajn klase Start je jednostavan i fokusiran na interakciju korisnika, sluzeci kao ulazna tacka za aplikaciju kalkulatora
 
