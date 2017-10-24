---
title: Registracije
datetime: 24.10.2017 15:00
---
Upotreba registracija na vašem sajtu omogućava brojne integracije sa ostatkom
Petlje. Korisnici koji žele da učestvuju u vašem takmičenju ili aktivnosti treba
da se registruju i dostave određene informacije koje su vam potrebne ali ih Petlja
ne prikuplja.

### Kreiranje registracije
Registracije se kreiraju iz kontrolne table. Potrebno je da konfigurišete koje
podatke želite da prikupljate prilikom registracije.
Funkcionalnosti:
- Registraciju možete zaštititi šifrom, a onda šifru distribuirati do korisnika
koje želite pouzdanim kanalima. Primer upotrebe šifre je registracija profesora.
- Korisnici mogu birati region, opštinu, školu i razred. Ovi parametri u
registraciji omogućavaju recimo filtriranje rezultata.
- Korisnici koji se registruju mogu upisati mentora ili poslati vam poruku ako im
to omogućite. Ova polja su kreirana na osnovu dosadašnje potrebe i mogu biti
proširena na zahtev.
- Prihvatanje pravilnika omogućava da korisnike obavežete na poštovanje odredjenih
pravila time što se registruju za učešće.
- Automatsko odobravanje zahteva ima smisla kada ste sigurni da zahtevi dolaze od
odgovarajućih korisnika (recimo registracija ima šifru) ili vam nije važno i svi
korisnici Petlje mogu da učestvuju. Inače, registracija ide u stanje NEREŠENO i
potrebno je ručno rešiti je.
- Višestruki zahtevi omogućavaju slanje više zahteva sa različitim obaveznim parametrima.
- Privatna registracija služi kada želite ručno da registrujete odredjene korisnike
kako bi koristili integracije sa Petljom. Recimo korisnike koji su se kvalifikovali
na sledeći nivo takmičenja.

### Povezivanje registracija
Možete omogućiti korisnicima koji su se registrovali za odredjenu ulogu da upravljaju
drugim registracijama. Recimo registracija profesora upravlja registracijama učenika.
Ovako možete dobiti potvrdu da je korisnik dao tačne podatke prilikom registracije.

### Registujte korisnike
U svaku registraciju možete ručno dodati korisnike, ali savetujemo da to radite
samo za privatne registracije (za ove registracije korisnik ne vidi da je
registrovan i ne može napustiti registraciju). Takodje, ako imate dodatne podatke
u nekoj drugoj registraciji, možete ih prebaciti. Funkcionalnost je napravljena
kako bi omogućila lakše upravljanje takmičenjima u više nivoa.

### Korisnici
Korisnici imaju pristup registracijama iz glavnom menija (leva navigacija).
Mogu videti poslate registracije i poništiti svoju registraciju.

### Upravljanje registracijama
Registracijama se upravlja iz prikaza koji je dostupan organizatorima i članovima
odredjenih registracija (koje ste konfigurisali u delu povezivanja). Ovom prikazu
se pristupa iz glavnog menija (leva navigacija).
Postoje sledeći statusi zahteva za registraciju:
- NEREŠEN poslata registracija ide u ovo stanje osim ako automatsko odobravanje
nije uključno
- ODOBREN poslata registracija je odobrena
- ODBIJEN poslata registracija je odbijena
- PONIŠTEN korisnik je poništio svoju registraciju
- POVUČEN odobrenu registraciju nemoguće je odbiti, već ona ide u ovo stanje koje
je ekvivalentno stanju ODBIJEN
