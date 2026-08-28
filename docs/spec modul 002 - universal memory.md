# SPEC MODUL-002 — UNIVERSAL MEMORY

## 1. Naziv modula
Universal Memory

## 2. Prioritet
KRITIČNI / TEMELJNI MODUL

## 3. Svrha modula

Universal Memory je centralna memorija sustava Matea AI.

Svi ostali moduli koriste istu memoriju kako Matea AI ne bi svaki put kretala od nule.

Cilj je da Matea AI dugoročno može pamtiti i povezivati relevantne informacije iz:
- razgovora
- sastanaka
- e-mailova
- kalendara
- projekata
- klijenata
- dobavljača
- putovanja
- dokumenata
- zadataka
- ponuda i računa
- kupovine
- drugih budućih modula

Universal Memory mora omogućiti Matei AI da razumije kontekst i povezuje informacije iz različitih izvora.

---

## 4. Osnovni princip

Matea AI mora razlikovati:

1. Trenutni razgovor
2. Kratkoročnu memoriju
3. Dugoročnu memoriju
4. Projekte
5. Osobe i tvrtke
6. Zadatke i rokove
7. Dokumente
8. Financijske informacije
9. Korisničke preference
10. Povijest izvršenih radnji

Sve informacije moraju biti povezive.

Primjer:

Ako na sastanku kažem:

"Strojarica kod Horvata je završena, bazen je pušten u rad, ali još nije plaćeno."

Matea AI treba razumjeti:

Klijent: Horvat  
Projekt: Horvat – bazen  
Status strojarice: završeno  
Status bazena: pušten u rad  
Status naplate: nije plaćeno  

Ako kasnije pitam:

"Što još nije riješeno kod Horvata?"

Matea AI mora pronaći prethodne informacije i odgovoriti bez potrebe da joj ponovno objašnjavam cijelu situaciju.

---

## 5. Vrste memorije

### A. Osobe

Za svaku relevantnu osobu moguće je spremiti:

- ime i prezime
- tvrtku
- funkciju
- kontakt
- povezane projekte
- povijest komunikacije
- otvorene zadatke
- dogovore
- relevantne napomene

---

### B. Tvrtke

Moguće je spremiti:

- naziv tvrtke
- kontakt osobe
- kontakt podatke
- projekte
- ponude
- račune
- dobavljačke odnose
- povijest komunikacije
- otvorena pitanja

---

### C. Projekti

Svaki projekt treba imati vlastitu memoriju.

Primjer:

PROJEKT: Horvat – bazen

Mogući podaci:

- klijent
- lokacija
- vrsta projekta
- datum početka
- rok
- trenutno stanje
- završeni radovi
- otvoreni radovi
- materijal
- dobavljači
- sastanci
- komunikacija
- dokumenti
- financije
- izdani računi
- primljene uplate
- nenaplaćeni iznosi
- zadaci
- podsjetnici

---

### D. Zadaci

Svaki zadatak može sadržavati:

- naziv
- opis
- povezani projekt
- odgovornu osobu
- datum nastanka
- rok
- prioritet
- status
- izvor zadatka

Izvor može biti:

- sastanak
- telefonski razgovor
- e-mail
- moja glasovna naredba
- dokument
- drugi modul

---

### E. Odluke i dogovori

Matea AI mora posebno evidentirati važne odluke.

Primjer:

"Dogovoreno je da montaža počinje 15. rujna."

Spremiti:

ODLUKA:
Montaža počinje 15. rujna.

POVEZANO:
Projekt X

IZVOR:
Sastanak / e-mail / razgovor

---

### F. Korisničke preference

Matea AI može pamtiti moje dugoročne preference koje joj pomažu pri radu.

Primjeri:

- način pisanja poslovnih e-mailova
- preferirane aviokompanije
- preferirani hoteli
- način organiziranja kalendara
- način prikazivanja zadataka
- poslovne procedure
- često korištene tvrtke i dobavljači

---

## 6. Automatsko povezivanje informacija

Universal Memory mora pokušati povezati novu informaciju s postojećim podacima.

Primjer:

U e-mailu se spominje:
"Hotel Excelsior Lovran"

Ako već postoji projekt:

"Excelsior Lovran"

sustav treba prepoznati moguću povezanost.

Ako nije siguran, Matea AI treba pitati:

"Želiš li da ovo povežem s projektom Excelsior Lovran?"

---

## 7. Pretraživanje memorije

Mora biti moguće razgovornim jezikom pitati:

"Što još moramo napraviti ovaj tjedan?"

"Koji projekti kasne?"

"Koji klijenti nam još nisu platili?"

"Što sam dogovorio s Ivanom prošli tjedan?"

"Pronađi mi zadnji razgovor vezan uz projekt X."

"Što smo dogovorili na zadnjem sastanku?"

"Koje ponude još čekaju odgovor?"

Matea AI mora pretražiti relevantnu memoriju i dati kratak, konkretan odgovor.

---

## 8. Povezivanje s Meeting Intelligence modulom

MODUL-001 Meeting Intelligence nakon završetka sastanka šalje Universal Memory modulu:

- transkript
- sažetak
- sudionike
- projekte
- zadatke
- rokove
- odluke
- dogovorene termine
- iznose
- sljedeće korake

Universal Memory zatim podatke organizira i povezuje s postojećim informacijama.

---

## 9. Povezivanje s budućim modulima

Universal Memory mora biti dostupan svim modulima Matea AI sustava.

Planirani moduli uključuju:

- Meeting Intelligence
- Smart Email
- Smart Calendar
- Business / Project Manager
- Pool Project Manager
- CRM
- Travel Assistant
- Accommodation Booking
- Shopping / Konzum
- Payment Center
- Documents
- Ponude i računi
- Nabava
- Notifikacije
- budući moduli

---

## 10. Glasovne naredbe

Primjeri:

"Hey Matea, zapamti da je strojarica kod Horvata završena."

"Hey Matea, što još moramo napraviti kod Horvata?"

"Hey Matea, pronađi što sam dogovorio s Markom."

"Hey Matea, koji projekti imaju otvorene zadatke?"

"Hey Matea, što ovaj tjedan moram riješiti?"

---

## 11. Ispravak memorije

Korisnik mora moći reći:

"To nije točno."

"Promijeni status na završeno."

"Zaboravi tu informaciju."

"To nije povezano s tim projektom."

"Premjesti to na projekt X."

Matea AI mora izvršiti ispravak i zabilježiti promjenu.

---

## 12. Sigurnost

Osjetljivi podaci moraju imati dodatnu zaštitu.

Posebno:

- bankovne kartice
- lozinke
- pristupni tokeni
- API ključevi
- bankovni podaci

NE SMIJU se spremati kao običan tekst u Universal Memory bazu.

Za njih će postojati poseban sigurnosni sustav / Secret Vault.

Universal Memory smije znati da određena metoda plaćanja postoji, ali ne mora imati pristup punom broju kartice.

---

## 13. Kontrola korisnika

Korisnik mora uvijek moći:

- pregledati što Matea AI pamti
- ispraviti podatak
- izbrisati podatak
- zabraniti spremanje određene informacije
- vidjeti odakle informacija dolazi

---

## 14. Povijest promjena

Za važne poslovne podatke treba čuvati povijest.

Primjer:

01.09. — Status: čeka montažu  
05.09. — Status: montaža u tijeku  
07.09. — Status: završeno  
07.09. — Naplata: nije plaćeno  
12.09. — Naplata: plaćeno  

Na taj način Matea AI zna ne samo trenutno stanje nego i što se događalo ranije.

---

## 15. Očekivani rezultat

Universal Memory mora omogućiti da Matea AI postane dugoročni osobni i poslovni asistent.

Korisnik ne bi trebao stalno ponavljati informacije koje je Matea AI već dobila.

Informacije iz sastanaka, e-mailova, projekata, kalendara i drugih modula moraju biti povezane u jednu zajedničku memoriju.

Krajnji cilj:

Matea AI zna:
- što je dogovoreno
- s kim je dogovoreno
- kada je dogovoreno
- na koji projekt se odnosi
- što je napravljeno
- što nije napravljeno
- koji je sljedeći korak
- koji su rokovi
- što čeka naplatu

i može te informacije pronaći običnim razgovorom.

---

## 16. Kriterij da je MODUL-002 završen

Modul se NE smatra završenim samo zato što je kod napisan.

Prije prelaska na sljedeći modul moramo dokazati da:

1. nova informacija može biti spremljena
2. informacija se može ponovno pronaći
3. informacija se može povezati s osobom
4. informacija se može povezati s projektom
5. zadatak i rok mogu biti spremljeni
6. Meeting Intelligence može automatski predati podatke memoriji
7. pogrešna informacija može biti ispravljena
8. informacija može biti izbrisana
9. sustav može odgovoriti na pitanja koristeći ranije spremljene podatke
10. podaci ostaju spremljeni nakon ponovnog pokretanja sustava

Tek kada svi testovi prođu, MODUL-002 dobiva status:

FUNCTIONAL / PASSED

i možemo prijeći na sljedeći modul.
