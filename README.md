# opimap-

Kirjuta üles (enda) domeeninimi, mida testid: 
Algse päringu tüüp on: "A"
1. Alusta ükskõik millisest juurnimeserverist.
dig +norec @k.root-servers.net. <minudomeen> a
2.Millised NS kirjed tagastati? Loetle need siia:.
3. Korda oma päringut kõigi nimeserverite pihta, mis punktis 2 tagastati.
Kas tulemus oli viide järgmisele serverile või lõplik vastus?
Loetle vastused siia:
Kas iga server vastas?
Kas kõik vastused olid samad?
4. Kui samm 3 oli viide, korda päringut iga nimeserveri pihta, mis vastuseks saadeti.
Loetle vastused siia:
Kas kõik serverid vastasid?
Kas vastused olid samad?
 
Vajadusel jätka (kui vastus polnud lõplik)
5. Kontroll:
* Kas kõik nimeserverid olid kättesaadavad?
* Kas kõik serverid tagastasid viite (referral) või pädeva vastuse (Authoritative Answer)?
* Kas kõik vastused olid samad?
* Loetle vastuste TTL väärtused:
Vormista vastus GitHubi- readme.md formaadis.
 
Lisa sellele tööle github readme.md faili link.
