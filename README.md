# Restaurant


Restaurant caracteristici:

  1.  Pentru fiecare loc la masa exista cate un meniu in care sunt afisate:
        - cod QR (indica masa la care te afli)
        - preparatele,
  2.  Preparatele se pot comanda doar prin aplicatie,pentru cei care nu detin un telefon se poate comanda prin vecinu.
  3.  Autentificarea prezentei clientului in restaurant se va face de catre persoana care a rezervat masa la un QR Reader.
  4.  Comenzile la masa se pot face individual sau in grup.
  5.  Premiile oferite de restaurant sunt valabile doar pentru cei care au comandat prin aplicatie.
  

lista:

1. Baza de date 
1. Site,
2. App,


## Baza de Date (UI)

1.  Crearea articolelor,tipul(aliment,tacam,etc),unitatea de masura(g,l,bucati)
2.  Adaugarea alimentelor venite(cantitate, pret, aliment not-ok),
3.  Crearea retetelor + consumul alimentelor(calculare marja de consum pentru fiecare aliment in functie de preparat(reteta + consum + marja de consum a fiecarei retete) + pret,
4.  Algoritm pentru a vedea ce mancaruri se mai pot prepara in acel moment in functie de :
    - Prioritatea 1: disponibilitatea alimentelor,
    - Prioritatea 2: numarul de persoane(din restaurant) + comenzile in curs.
    - Prioritatea 3: numarul de persoane(din restaurant) + comenzile nevalidate(default (per portie) sau la cerere (n portii) )
5.  Aliment/reteta manipulat gresit(pierderi tehnologice)


## Site:

1.  Site de prezentare(restaurant,meniu),
2.  Functia de a vedea mese disponibile sau customiza online o masa, cat si functia de a rezerva
3.  Functia de a comanda preparatul/preparatele inainte de ora rezervarii(comanda se va plati fix cand s-a solicitat), 
4.  Functia de ridicare / la pachet,
5.  Plata cu cash / card / moneda virtuala proprie, 

 ## App
 
 
