# MATEA AI — MASTER PLAN

## CILJ PROJEKTA

Izraditi osobnog AI asistenta pod imenom "Matea" koji će prvenstveno raditi na Android/Samsung telefonu i s kojim mogu razgovarati prirodnim govorom.

Matea nije samo chatbot. Cilj je napraviti osobnog izvršnog asistenta koji može razumjeti moje zahtjeve, koristiti povezane aplikacije i servise, izvršavati zadatke, pamtiti relevantne informacije i proaktivno me obavještavati.

## OSNOVNA ARHITEKTURA

Matea AI sastoji se od četiri glavna dijela:

1. AI MOZAK
- razumije prirodni govor
- zaključuje što korisnik želi
- planira radnje
- odabire odgovarajući modul
- priprema odgovore i prijedloge

2. AUTOMATIZACIJA
- povezuje AI s vanjskim servisima
- Gmail
- Google Calendar
- kontakti
- dokumenti
- putovanja
- kupovina
- plaćanja
- poslovni sustavi

3. MEMORIJA
- pamti projekte
- klijente
- zadatke
- dogovore
- preferencije
- prethodne razgovore i sastanke
- otvorene obaveze
- statuse projekata

4. MOBILNA APLIKACIJA
Primarna platforma: Android / Samsung

Glavni način korištenja treba biti glas.

Primjer:
"Hej Matea..."

---

# MODULI

## MODUL 1 — MEETING INTELLIGENCE
PRIORITET: NAJVIŠI

Glasovna naredba:

"Hej Matea, pokreni sastanak."

Matea treba:

- pokrenuti snimanje razgovora
- nastaviti snimati u pozadini
- napraviti potpuni transkript razgovora
- prepoznati sudionike
- prepoznati projekte i klijente
- izdvojiti ključne informacije
- izdvojiti dogovorene obaveze
- izdvojiti rokove i datume
- prepoznati iznose i financijske obaveze
- napraviti kratki sažetak razgovora
- napraviti detaljni sažetak razgovora
- izdvojiti zadatke
- predložiti sljedeće korake
- prepoznati termine koji trebaju ići u kalendar
- predložiti događaje i podsjetnike u kalendaru
- povezati razgovor s odgovarajućim projektom ili klijentom
- po završetku poslati sažetak na moj e-mail
- spremiti transkript i sažetak u memoriju

Cilj:
Nakon razgovora ne trebam ručno zapisivati što je dogovoreno.

---

## MODUL 2 — SMART EMAIL

Kada stigne važan e-mail:

Matea treba:
- prepoznati pošiljatelja
- pročitati sadržaj
- napraviti kratki sažetak
- glasovno me obavijestiti
- ponuditi čitanje cijelog e-maila
- predložiti odgovor
- pročitati mi prijedlog odgovora
- omogućiti izmjene glasovnom naredbom
- poslati odgovor nakon moje potvrde

---

## MODUL 3 — SMART CALENDAR

Matea treba moći:
- čitati moj kalendar
- dodavati termine
- mijenjati termine
- brisati termine
- postavljati podsjetnike
- upozoravati na preklapanje termina
- povezivati termine s projektima, klijentima i sastancima

---

## MODUL 4 — TRAVEL ASSISTANT

Matea treba moći:
- tražiti avionske karte
- uspoređivati letove
- uspoređivati cijene
- uzimati u obzir moje preferencije
- tražiti poslovnu i ekonomsku klasu
- tražiti hotele
- koristiti Booking.com
- koristiti Airbnb
- organizirati kompletno putovanje
- povezati putovanje s kalendarom
- pripremiti kupnju
- koristiti Payment modul nakon moje potvrde

---

## MODUL 5 — SHOPPING ASSISTANT

Matea treba moći:
- otvoriti trgovinu ili servis
- pronaći proizvode
- sastaviti košaricu
- naručivati namirnice, uključujući Konzum.hr
- pamtiti proizvode koje često kupujem
- predložiti ponovnu kupnju
- koristiti Payment modul za plaćanje

---

## MODUL 6 — PAYMENT CENTER

Centralni modul za sva plaćanja.

Koriste ga:
- Travel Assistant
- Shopping Assistant
- budući moduli koji zahtijevaju plaćanje

Mora imati visok stupanj sigurnosti.

AI ne smije samostalno izvršiti konačno plaćanje bez odgovarajuće autorizacije korisnika.

---

## MODUL 7 — BUSINESS / CRM

Matea treba:
- pamtiti klijente
- pamtiti dobavljače
- povezivati komunikaciju s klijentom
- voditi otvorene zadatke
- pratiti rokove
- pratiti dogovore
- pratiti što je završeno
- pratiti što još nije riješeno
- pratiti otvorene naplate

---

## MODUL 8 — POOL PROJECT MANAGER

Specijalizirani poslovni modul za projekte izgradnje bazena.

Primjer glasovne naredbe:

"Hej Matea, na projektu X strojarica je završena i bazen je pušten u rad. Označi to kao završeno, ali ostavi podsjetnik da račun još nije plaćen."

Matea treba razumjeti zahtjev i ažurirati:
- projekt
- status radova
- završene radove
- otvorene radove
- rokove
- naplatu
- podsjetnike
- zadatke

---

# DODATNI BUDUĆI MODULI

- ponude i troškovnici
- računi i naplata
- nabava
- dobavljači
- upravljanje dokumentima
- poslovne analize
- praćenje cijena
- proaktivne obavijesti
- ostali moduli koji se naknadno definiraju

---

# GLAVNO PRAVILO RAZVOJA

Razvoj ide modul po modul.

Ne prelazimo na sljedeći modul dok prethodni modul nije funkcionalno testiran.

Prvi modul za razvoj:

MEETING INTELLIGENCE
