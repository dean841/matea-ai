# SPEC MODUL 001 – MEETING INTELLIGENCE

## 1. Naziv modula
Meeting Intelligence

## 2. Prioritet
NAJVIŠI PRIORITET

## 3. Svrha modula
Meeting Intelligence je modul unutar sustava Matea AI čija je svrha automatski pratiti sastanke i razgovore, snimiti ih, napraviti transkript, razumjeti sadržaj razgovora te iz njega automatski izdvojiti sve važne informacije, obveze, zadatke, rokove i termine.

Cilj je da korisnik tijekom sastanka ne mora voditi bilješke niti nakon sastanka ponovno prolaziti kroz razgovor.

---

## 4. Pokretanje modula

Modul se pokreće glasovnom naredbom:

"Hey Matea, pokreni sastanak."

Nakon naredbe Matea odgovara:

"Sastanak je pokrenut."

Od tog trenutka aplikacija počinje snimati i obrađivati razgovor u pozadini.

Mora postojati i glasovna naredba:

"Hey Matea, završi sastanak."

Nakon te naredbe snimanje se zaustavlja i automatski započinje obrada sastanka.

---

## 5. Snimanje razgovora

Tijekom aktivnog sastanka modul treba:

- snimati kompletan razgovor
- nastaviti raditi dok je aplikacija u pozadini, gdje operativni sustav to dopušta
- spremiti originalnu audio snimku
- zabilježiti datum i vrijeme početka sastanka
- zabilježiti datum i vrijeme završetka sastanka
- zabilježiti trajanje sastanka

---

## 6. Transkripcija

Matea AI automatski izrađuje transkript cijelog sastanka.

Transkript treba:

- sadržavati kompletan razgovor
- prepoznati različite govornike kada je to moguće
- sadržavati vremenske oznake
- podržavati hrvatski jezik
- podržavati njemački jezik
- podržavati engleski jezik
- prepoznati razgovore u kojima se jezici međusobno izmjenjuju

Originalni transkript mora se sačuvati kako bi ga bilo moguće kasnije ponovno analizirati.

---

## 7. AI analiza sastanka

Nakon završetka sastanka Matea automatski analizira kompletan transkript.

Iz razgovora treba prepoznati i izdvojiti:

- glavne teme razgovora
- donesene odluke
- dogovorene poslove
- zadatke
- osobe odgovorne za pojedine zadatke
- rokove
- datume
- termine
- sastanke
- telefonske pozive koje treba obaviti
- e-mailove koje treba poslati
- ponude koje treba napraviti
- dokumente koje treba dostaviti
- narudžbe koje treba napraviti
- dogovorene cijene
- spomenute novčane iznose
- informacije o plaćanju
- neplaćene obveze
- otvorena pitanja
- probleme koje treba riješiti
- sljedeće korake

---

## 8. Sažetak sastanka

Nakon svakog sastanka Matea izrađuje strukturirani sažetak.

Sažetak treba sadržavati:

### Osnovni podaci
- datum
- vrijeme
- trajanje
- sudionike, ako ih je moguće identificirati
- povezani klijent
- povezani projekt

### Kratki sažetak
Kratko objašnjenje najvažnijeg sadržaja sastanka.

### Dogovoreno
Jasan popis svega što je dogovoreno.

### Zadaci
Za svaki zadatak navesti:

- što treba napraviti
- tko je odgovoran
- rok
- prioritet
- status

### Termini i rokovi
Poseban popis svih datuma i rokova spomenutih tijekom razgovora.

### Otvorena pitanja
Sve što tijekom sastanka nije konačno riješeno.

### Sljedeći koraci
Što treba napraviti nakon sastanka.

---

## 9. Kalendar

Ako Matea tijekom razgovora prepozna konkretan termin ili rok, treba pripremiti prijedlog kalendarskog događaja.

Primjer:

U razgovoru je rečeno:

"Nađemo se u Zagrebu u četvrtak u 10 sati."

Matea treba pripremiti:

Naziv:
Sastanak – [osoba/projekt]

Datum:
prepoznati datum

Vrijeme:
10:00

Lokacija:
Zagreb

Opis:
kratki kontekst sastanka

Ako nedostaje važan podatak ili postoji dvojba, Matea treba tražiti potvrdu prije unosa.

---

## 10. Zadaci i podsjetnici

Ako se tijekom razgovora pojavi obveza, Matea treba napraviti prijedlog zadatka.

Primjer:

"Pošalji ponudu do petka."

Matea kreira prijedlog:

ZADATAK:
Poslati ponudu

ROK:
Petak

POVEZANO:
odgovarajući klijent/projekt

STATUS:
Otvoreno

PRIORITET:
odrediti prema kontekstu ili pitati korisnika ako je potrebno.

---

## 11. Poslovni projekti

Meeting Intelligence mora biti povezan s poslovnim modulima Matea AI.

Ako se tijekom razgovora spomene postojeći projekt, Matea treba prepoznati projekt i povezati sastanak s njim.

Primjeri informacija:

"Strojarica je gotova."

"Bazen je pušten u rad."

"Čekamo električara."

"Oprema još nije stigla."

"Klijent još nije platio."

"Ponuda je prihvaćena."

Takve informacije trebaju postati prijedlozi za ažuriranje statusa projekta.

---

## 12. Financijske informacije

Ako se tijekom razgovora spomene:

- cijena
- ponuda
- račun
- uplata
- dug
- avans
- ostatak za plaćanje

Matea treba to prepoznati kao financijski relevantnu informaciju.

Primjer:

"Bazen je završen, ali još nije plaćen ostatak od 8.500 eura."

Matea treba prepoznati:

PROJEKT:
odgovarajući projekt

STATUS RADOVA:
završeno

STATUS NAPLATE:
nije plaćeno

IZNOS:
8.500 EUR

AKCIJA:
predložiti praćenje naplate/podsjetnik.

---

## 13. E-mail nakon sastanka

Nakon završetka analize Matea treba automatski pripremiti e-mail sa sažetkom sastanka.

E-mail treba sadržavati:

- naziv sastanka
- datum
- kratki sažetak
- dogovorene odluke
- zadatke
- rokove
- sljedeće korake

Interni sažetak sastanka treba biti moguće automatski poslati na unaprijed definiranu korisnikovu e-mail adresu.

Ako se e-mail šalje drugoj osobi ili vanjskom primatelju, prije slanja potrebna je potvrda korisnika.

---

## 14. Pohrana

Za svaki sastanak treba sačuvati:

- originalnu audio snimku
- kompletan transkript
- AI sažetak
- popis zadataka
- rokove
- predložene kalendarske događaje
- povezane osobe
- povezane klijente
- povezane projekte
- financijske informacije
- datum i vrijeme sastanka

Svi podaci moraju kasnije biti pretraživi.

---

## 15. Memorija i pretraživanje

Korisnik mora moći kasnije pitati Mateu pitanja poput:

"Što sam dogovorio s Ivanom prošli tjedan?"

"Kad smo rekli da dolaze monteri?"

"Koliko je Horvat još dužan?"

"Jesmo li poslali ponudu za taj bazen?"

"Što smo dogovorili na zadnjem sastanku za projekt Novalja?"

Matea treba pronaći odgovarajući sastanak i odgovoriti na temelju spremljenog sadržaja.

---

## 16. Predložene akcije

Nakon sastanka Matea ne treba samo napraviti sažetak.

Treba predložiti konkretne sljedeće akcije.

Primjeri:

- Dodaj sastanak u kalendar
- Postavi podsjetnik
- Kreiraj zadatak
- Ažuriraj status projekta
- Evidentiraj nenaplaćeni iznos
- Pripremi e-mail
- Pošalji e-mail
- Pripremi ponudu
- Dodaj osobu u CRM
- Poveži sastanak s postojećim projektom

---

## 17. Potvrde i sigurnost

Matea može samostalno:

- snimiti pokrenuti sastanak
- napraviti transkript
- analizirati razgovor
- napraviti sažetak
- spremiti dokumentaciju sastanka
- pripremiti prijedloge akcija

Za osjetljive vanjske radnje mora tražiti potvrdu korisnika.

To posebno uključuje:

- slanje e-maila drugoj osobi
- slanje poruke
- promjene važnih poslovnih podataka
- financijske transakcije
- plaćanja
- narudžbe

---

## 18. Mobilna aplikacija

Primarna platforma za Meeting Intelligence bit će Android, prvenstveno Samsung uređaji.

Modul mora biti dizajniran za korištenje glasom uz minimalno dodirivanje telefona.

Korisnik mora moći pokrenuti i završiti sastanak glasovnom naredbom.

Aplikacija treba jasno prikazivati kada je snimanje aktivno.

---

## 19. Telefonski razgovori

Dugoročni cilj je omogućiti obradu telefonskih razgovora tamo gdje Android uređaj, telefonska aplikacija, lokalni zakoni i dostupna tehnička rješenja omogućuju snimanje.

Ako je snimanje telefonskog razgovora dostupno, isti Meeting Intelligence pipeline treba obraditi poziv:

SNIMKA
→ TRANSKRIPT
→ AI ANALIZA
→ SAŽETAK
→ ZADACI
→ KALENDAR
→ PROJEKT
→ MEMORIJA

Implementacija mora poštovati pravila o privatnosti, snimanju razgovora i potrebnom obavještavanju ili pristanku sudionika.

---

## 20. Cilj prve funkcionalne verzije

MODUL 001 smatra se funkcionalnim tek kada možemo napraviti stvarni test:

1. Korisnik kaže:
   "Hey Matea, pokreni sastanak."

2. Sustav počinje snimati.

3. Vodi se stvarni razgovor.

4. Korisnik kaže:
   "Hey Matea, završi sastanak."

5. Snimanje završava.

6. Automatski nastaje transkript.

7. AI analizira razgovor.

8. Automatski nastaje sažetak.

9. Izdvoje se zadaci i rokovi.

10. Prepoznaju se termini za kalendar.

11. Sažetak se spremi.

12. Korisnik dobije sažetak sastanka na e-mail.

13. Podaci sastanka mogu se kasnije pronaći i pretraživati.

