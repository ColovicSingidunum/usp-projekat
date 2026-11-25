Podnosilac: USP Tim 1

direktoru Sektora za upravljanje projektima – PMO

Dana: 13.11.2026.

**PREDMET: NACRT PROJEKTA**

## 1. NAZIV PROJEKTA

**KadarGlas: AI glasovni asistent za video montažu i video striming**

U dokumentaciji i izveštajima koristi se skraćeni naziv KadarGlas.

## 2. CILJ PROJEKTA

Do 29.10.2027. javno lansirati KadarGlas, desktop aplikaciju koja glasom upravlja programima za strim i montažu, u okviru budžeta od 321.200 €. Korisnik govorom, na srpskom ili engleskom jeziku, upravlja prenosom u OBS Studiju i zadaje komande za montažu u DaVinci Resolveu i Premiere Prou.

| Cilj          | Mera uspeha                                                                        | Rok         |
| ------------- | ---------------------------------------------------------------------------------- | ----------- |
| MVP za strim  | Zatvorena beta sa 300 strimera i 40 komandi za OBS Studio                          | 28.05.2027. |
| Proizvod      | Aplikacija javno dostupna za Windows i macOS, na srpskom i engleskom               | 29.10.2027. |
| Obim          | Najmanje 120 glasovnih komandi: 40 za strim, 80 za montažu                         | 29.10.2027. |
| Tačnost       | Najmanje 95% za engleski i 92% za srpski, na test korpusu od 500 komandi po jeziku | 29.10.2027. |
| Brzina odziva | Najviše 800 ms u strimu za 30 osnovnih komandi; najviše 2 s u montaži              | 29.10.2027. |
| Budžet        | Ukupan trošak realizacije najviše 321.200 €                                        | 26.11.2027. |
| Usvajanje     | Prosečno 2.500 plaćenih korisnika Pro verzije u prvoj godini                       | 29.10.2028. |
| Zadovoljstvo  | Prosečna ocena najmanje 4,2 od 5 u anketi korisnika                                | 30.04.2028. |

Prvih šest ciljeva odnosi se na sam projekat. Usvajanje i zadovoljstvo korisnika mere uspeh proizvoda, pa njih posle zaključenja projekta prati ceo tim.

## 3. RAZLOG POKRETANJA PROJEKTA

Poslovni razlozi:

NovaKadar d.o.o. je novootvoreni startup bez proizvoda, osnovan da bi napravio KadarGlas. Projekat je zato ujedno i početak poslovanja firme.

Strimeri koji rade sami ne mogu da menjaju scene, puštaju grafike ili isključuju mikrofon dok nastupaju, sviraju ili igraju. Montažeri gube najviše vremena na ponavljajuće radnje, kao što su sečenje pauza, titlovi i podešavanje nivoa zvuka. U našoj anketi među 300 strimera i montažera, 52% bi probalo glasovno upravljanje.

AI asistenti u postojećim editorima rade preko teksta, a OBS Studio, koji koristi većina strimera, nema glasovno upravljanje. KadarGlas ne traži od korisnika da promeni program na koji je navikao, nego radi uz njega. Glasovno upravljanje na srpskom jeziku ne nudi nijedan konkurent koji smo pregledali.

Uticaj na poslovanje:

- firma dobija prvi proizvod i prvi izvor prihoda, Pro pretplatu od 10 € mesečno, sa 300.000 € prihoda u prvoj godini
- javljaju se troškovi koji rastu sa brojem korisnika, jer se AI servisi plaćaju po upotrebi, oko 0,90 € po plaćenom korisniku mesečno
- firma preuzima obaveze u zaštiti glasovnih podataka, naplati i podršci korisnicima
- tim raste sa četiri na osam ljudi, pa firma prvi put zapošljava

## 4. OČEKIVANA DOBIT

Za tri godine od lansiranja projekat vraća uloženo i donosi još 681.400 €. Neto sadašnja vrednost, uz diskontnu stopu od 15%, iznosi 349.200 €.

| Pokazatelj                      | Vrednost                    |
| ------------------------------- | --------------------------- |
| Prihod za 3 godine              | 2.340.000 €                 |
| Operativni troškovi za 3 godine | 1.337.400 €                 |
| Neto novčani tok za 3 godine    | 1.002.600 €                 |
| Ulaganje u realizaciju          | 321.200 €                   |
| Dobit posle povraćaja ulaganja  | 681.400 €                   |
| NPV uz diskontnu stopu 15%      | 349.200 €                   |
| Interna stopa prinosa (IRR)     | 48,2%                       |
| Period povraćaja                | Oko 26 meseci od lansiranja |

Ceo prihod dolazi od Pro pretplate: prosečno 2.500 plaćenih korisnika u prvoj godini, 6.000 u drugoj i 11.000 u trećoj. Prva godina je u gubitku od 78.600 €, a od druge godine prihod pokriva troškove. Obračun po godinama i scenarije sadrži Studija izvodljivosti (oblasti 1 i 6).

Pored novca, projekat donosi vrednost samoj firmi. Posle lansiranja NovaKadar ima proizvod, korisnike i tim, što je osnova za sledeću rundu ulaganja. Aplikacija je korisna i osobama sa motoričkim teškoćama, a tim stiče znanje o govornim tehnologijama za srpski jezik.

## 5. DETALJAN OPIS REZULTATA PROJEKTA (Funkcionalna ograničenja)

Projekat isporučuje desktop aplikaciju sa najmanje 120 glasovnih komandi, prvo za strim, a zatim za montažu. Posle pripreme rad je podeljen u četiri faze, a na kraju svake faze upravni odbor odlučuje o nastavku.

| Faza i rok                                    | Aktivnosti                                                                                      | Funkcionalnosti                                                                                       | Dokumenti                                                                                                           |
| --------------------------------------------- | ----------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Priprema, do 18.12.2026.                      | Razrada plana, procena rizika, ugovor sa investitorom                                           | Nema                                                                                                  | Projektni plan, Definicija projekta, plan komunikacije, registar rizika, ugovor o ulaganju                          |
| 1. Analiza i prototip, do 26.02.2027.         | Intervjui sa 20 strimera i montažera, izbor dobavljača, izrada prototipa, snimanje test korpusa | Prototip sa 20 komandi za OBS Studio na oba jezika                                                    | Specifikacija zahteva, katalog komandi, opis arhitekture, izveštaj o prototipu, procena uticaja na zaštitu podataka |
| 2. MVP za strim, do 28.05.2027.               | Razvoj, zatvorena beta sa 300 strimera                                                          | 40 komandi za OBS Studio, taster i budna reč, lokalno prepoznavanje 30 osnovnih komandi, poništavanje | Plan testiranja, izveštaj o beti, izveštaj o tačnosti i brzini                                                      |
| 3. Režim montaže, do 27.08.2027.              | Zapošljavanje, razvoj integracija, beta za montažu                                              | 80 komandi za DaVinci Resolve i Premiere Pro, istorija komandi, potvrda rizičnih komandi              | Izveštaj o beti za montažu, korisničko uputstvo v1                                                                  |
| 4. Stabilizacija i lansiranje, do 29.10.2027. | Bezbednosno testiranje, ispravke, kampanja lansiranja                                           | Besplatna i Pro verzija, naplata pretplate, daljinsko isključenje asistenta                           | Izveštaj bezbednosnog testiranja, politika privatnosti, uslovi korišćenja, konačno uputstvo, plan lansiranja        |
| Zaključenje, do 26.11.2027.                   | Analiza projekta, prelazak na redovno održavanje                                                | Nema                                                                                                  | Završni izveštaj, naučene lekcije                                                                                   |

Tokom strima asistent menja scene i kamere, pušta špicu i grafike, označava momente za kasnije klipove, uključuje i isključuje mikrofon i pokreće i zaustavlja snimanje. U montaži seče i skraćuje klipove, uklanja pauze, pokreće titlove, dodaje prelaze, podešava nivoe zvuka i izvozi snimak u zadatom formatu.

Van obima projekta su:

- sopstveni program za montažu ili strim
- mobilna aplikacija i veb verzija
- programi osim OBS Studija, DaVinci Resolvea i Premiere Proa, osim preko prečica na tastaturi
- jezici osim srpskog i engleskog
- generisanje video sadržaja i kloniranje glasa
- prepoznavanje identiteta govornika
- samostalne kreativne odluke asistenta, koji izvršava samo ono što korisnik zatraži

## 6. PROCESI NA KOJE PROJEKAT/REZULTATI PROJEKTA UTIČU I NA KOJI NAČIN

Pošto firma tek počinje da radi, projekat većinu procesa uspostavlja, a ne menja.

| Proces                            | Uticaj                                                                                                  |
| --------------------------------- | ------------------------------------------------------------------------------------------------------- |
| Razvoj proizvoda                  | Uvodi se razvoj u sprintovima, pregled koda i automatski testovi integracija sa OBS-om i editorima.     |
| Testiranje kvaliteta              | Nova vrsta testa: tačnost i brzina na govornom korpusu, uz ponavljanje pri svakoj novoj verziji.        |
| Podrška korisnicima               | Uspostavlja se podrška na srpskom i engleskom, baza znanja i zajednica korisnika na Discordu.           |
| Prodaja i naplata                 | Uvodi se pretplata preko platnog servisa, probni period Pro verzije od 30 dana i obračun PDV-a.         |
| Marketing                         | Kampanja lansiranja, saradnja sa kreatorima sadržaja i prisustvo u zajednicama strimera.                |
| Zapošljavanje                     | Firma prvi put zapošljava: četiri nove osobe u 2027, uz ugovore o radu i uvođenje u posao.              |
| Finansije i izveštavanje          | Praćenje troška po korisniku, mesečni izveštaj investitoru, saradnja sa knjigovodstvenom agencijom.     |
| Pravni poslovi i zaštita podataka | Politika privatnosti, uslovi korišćenja, evidencija obrade glasovnih podataka, ugovori sa dobavljačima. |

Menja se i način rada korisnika. Ponavljajuće radnje u montaži i upravljanje prenosom više ne moraju da rade mišem i tastaturom, već mogu glasom.

## 7. FUNKCIJE U KOMPANIJI I EKSTERNI SARADNICI KOJE JE NEOPHODNO UKLJUČITI U REALIZACIJU PROJEKTA

U startapu nema posebnih sektora, pa su funkcije podeljene po ulogama.

| Funkcija u kompaniji                     | Odgovornost u projektu                                                        |
| ---------------------------------------- | ----------------------------------------------------------------------------- |
| Direktor (osnivač zadužen za poslovanje) | Menadžer projekta, odnos sa investitorom, finansije, marketing, zapošljavanje |
| Razvoj (dva osnivača programera)         | Arhitektura i razvoj desktop aplikacije, integracija sa OBS Studiom           |
| AI/ML (osnivač AI/ML inženjer)           | Prepoznavanje govora, jezički model, katalog komandi, test korpus             |
| Integracije (dva nova inženjera)         | Integracije sa DaVinci Resolveom i Premiere Proom, od 01.06.2027.             |
| Kvalitet (novi QA inženjer)              | Plan testiranja, beta testiranje, automatski testovi, od 01.06.2027.          |
| Podrška i zajednica (nova osoba)         | Podrška korisnicima, baza znanja, Discord zajednica, od 01.09.2027.           |

Od eksternih saradnika potrebni su:

| Eksterni saradnik                 | Uloga                                                                     |
| --------------------------------- | ------------------------------------------------------------------------- |
| Anđeo investitor                  | Ulaganje od 450.000 €, mentor i član upravnog odbora projekta             |
| Dobavljači STT i LLM servisa      | Prepoznavanje govora i tumačenje komandi, tehnička podrška                |
| Konsultant za govorne tehnologije | Tačnost za srpski jezik, 30 radnih dana                                   |
| UX dizajner                       | Dizajn glasovnog interfejsa i aplikacije, honorarno                       |
| Advokatska kancelarija            | Ugovor sa investitorom, zaštita podataka, propisi o AI, uslovi korišćenja |
| Knjigovodstvena agencija          | Knjigovodstvo, obračun plata i PDV-a                                      |
| Firma za bezbednosno testiranje   | Nezavisno testiranje pre lansiranja                                       |
| Spikeri i anotatori               | Snimanje i označavanje test korpusa od 1.000 komandi                      |

U zatvorenim betama učestvuje i 300 strimera i montažera iz online zajednica, kao dobrovoljni testeri.

## 8. UGOVORI I ODLUKE NA KOJE SE PROJEKAT OSLANJA

Postojeće odluke i ugovori:

- Osnivački akt društva NovaKadar d.o.o., registrovanog u Agenciji za privredne registre 2026. godine
- Ugovor osnivača o podeli udela, postepenom sticanju udela i ulogama u firmi
- Studija izvodljivosti projekta KadarGlas od 13.11.2026, sa preporukom da se projekat pokrene

Treba zaključiti sledeće ugovore:

- ugovor o ulaganju sa anđeo investitorom, sa uslovima za drugu tranšu, do 18.12.2026.
- ugovore o korišćenju STT i LLM servisa, sa ugovorima o obradi podataka o ličnosti, do 26.02.2027.
- ugovor o konsultantskim uslugama za govorne tehnologije, do 26.02.2027.
- ugovore o poverljivosti sa beta testerima, pre početka prve bete
- ugovore o radu sa četiri nova zaposlena, od 01.06.2027.
- ugovor sa platnim servisom za naplatu pretplate, pre lansiranja

Potrebna je i odluka skupštine društva o povećanju kapitala i ulasku investitora.

## 9. ZAINTERESOVANE STRANE NA KOJE REZULTATI PROJEKTA UTIČU DIREKTNO ILI INDIREKTNO (*STAKEHOLDERS*)

| Zainteresovana strana                         | Uticaj     | Opis uticaja                                                                         |
| --------------------------------------------- | ---------- | ------------------------------------------------------------------------------------ |
| Strimeri koji rade sami                       | Direktan   | Upravljaju prenosom bez pomoćnika i bez prekida nastupa                              |
| Korisnici koji montiraju video                | Direktan   | Brže obavljaju ponavljajuće radnje; moraju da nauče novi način rada                  |
| Korisnici sa motoričkim teškoćama             | Direktan   | Dobijaju pristup funkcijama koje su im mišem i tastaturom teško dostupne             |
| Osnivači                                      | Direktan   | Rade puno radno vreme na projektu; od njegovog uspeha zavisi opstanak firme          |
| Novi zaposleni                                | Direktan   | Četiri radna mesta od juna i septembra 2027.                                         |
| Anđeo investitor                              | Direktan   | Ulaganje od 450.000 € za 18% udela i očekivani rast vrednosti firme                  |
| Gosti u prenosima i ukućani korisnika         | Indirektan | Mikrofon može da uhvati njihov glas; štiti ih slušanje samo na zahtev                |
| Gledaoci prenosa                              | Indirektan | Gledaju tekući prenos sa manje prekida i grešaka                                     |
| Dobavljači STT i LLM servisa                  | Indirektan | Novi kupac sa rastućim obimom upotrebe                                               |
| Proizvođači OBS Studija, Resolvea i Premierea | Indirektan | Njihovi programi dobijaju glasovno upravljanje; promene njihovih API-ja utiču na nas |
| Poverenik za zaštitu podataka o ličnosti      | Indirektan | Nadzire zakonitost obrade glasovnih podataka                                         |
| Konkurenti                                    | Indirektan | Pritisak da ponude sličnu funkciju                                                   |

## 10. PRETPOSTAVKE PROJEKTA

1. Sva četiri osnivača rade na projektu puno radno vreme tokom celog projekta.
2. Investitor isplaćuje prvu tranšu do 18.12.2026, a drugu do 15.06.2027. ako beta za strim dostigne ciljeve iz ugovora.
3. Potrebni HW i SW resursi su raspoloživi prema projektnom planu, a oprema za testiranje stiže do 29.01.2027.
4. Uloge članova tima, vremenska ograničenja, linije izveštavanja, oblici komunikacije, odgovornosti i hijerarhija precizno su definisani u Definiciji projekta do 18.12.2026.
5. Svi učesnici u projektu, interni i eksterni, sarađuju i koordinisani su preko menadžera projekta.
6. Zahtevi se zaključuju na kraju faze 1, a kasnije promene prolaze postupak upravljanja promenama.
7. API-ji OBS Studija, DaVinci Resolvea i Premiere Proa pokrivaju najmanje 80% radnji potrebnih za 120 planiranih komandi.
8. Najmanje jedan dobavljač STT servisa podržava srpski jezik u realnom vremenu uz traženu tačnost.
9. Nove ljude zaposlimo do 01.06.2027, odnosno do 01.09.2027.
10. Za betu za strim prijavi se najmanje 300 strimera.
11. Cene AI servisa ne rastu više od 20% do lansiranja.
12. Propisi o zaštiti podataka i o AI ne menjaju se bitno do lansiranja.

Pretpostavke 7 i 8 proverava prototip u fazi 1. Ako se ne potvrde, upravni odbor odlučuje o daljem toku projekta na kontrolnoj tački 26.02.2027.

## 11. RIZICI I MERE ZA SMANJENJE NJIHOVOG UTICAJA

Najveći rizik je da proizvod ne privuče dovoljno korisnika, jer firma nema postojeću bazu. Slede tačnost za srpski jezik, brzina odziva uživo i zavisnost od API-ja tuđih programa. Verovatnoća i uticaj svakog rizika ocenjeni su u Studiji izvodljivosti (oblast 6).

| Rizik                                                          | Plan delovanja za rešavanje ili predupređenje rizika                                                                                                 |
| -------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| Premalo korisnika, jer nemamo postojeću bazu                   | Besplatna verzija, beta sa 300 strimera, saradnja sa kreatorima sadržaja. Ako posle šest meseci Pro plaća manje od 1.500 korisnika, tim se smanjuje. |
| Tačnost prepoznavanja za srpski jezik ispod 92%                | Provera na prototipu u fazi 1 sa konsultantom. Ako ne uspe, lansira se samo engleski, a srpski dolazi u sledećoj verziji.                            |
| Odziv u strimu duži od 800 ms                                  | Lokalno prepoznavanje 30 osnovnih komandi bez slanja na servis. Merenje odziva pri svakoj novoj verziji.                                             |
| Pogrešno izvršena komanda tokom prenosa uživo                  | Glasovna potvrda za rizične komande, poništavanje, beta sa 300 strimera pre lansiranja.                                                              |
| Promena API-ja OBS Studija, DaVinci Resolvea ili Premiere Proa | Praćenje najava proizvođača, automatski testovi integracija pri svakoj novoj verziji, prečice na tastaturi kao rezerva.                              |
| Investitor ne isplati drugu tranšu                             | Ciljevi bete jasno upisani u ugovor. Ako se tranša ne isplati, lansira se samo režim strima, bez zapošljavanja.                                      |
| Incident sa privatnošću glasovnih podataka                     | Zvuk se ne čuva. Procena uticaja na zaštitu podataka u fazi 1, nezavisno bezbednosno testiranje u fazi 4.                                             |
| Rast cena ili ukidanje AI servisa dobavljača                   | Sloj koji omogućava zamenu dobavljača bez izmene aplikacije, ugovor sa dva ponuđača, lokalni model kao rezerva.                                      |
| Konkurent objavi sličnu funkciju pre lansiranja                | MVP za strim gotov je već u maju 2027. Prednost gradimo na srpskom jeziku i radu uz programe koje korisnici već koriste.                             |
| Prekoračenje budžeta                                           | Mesečna kontrola troškova. Rezervu od 29.200 € odobrava upravni odbor projekta.                                                                      |
| Kašnjenje u zapošljavanju                                      | Oglasi od aprila 2027. Do dolaska novih ljudi posao privremeno pokrivaju honorarni saradnici.                                                        |
| Odlazak osnivača ili neplanirano odsustvo člana tima           | Ugovor osnivača sa postepenim sticanjem udela. Zamenik za svaku ulogu, rad u paru i dokumentacija.                                                   |
| Nedostatak potrebnih informacija na početku projekta           | Faza 1 je posvećena analizi, sa intervjuima 20 korisnika i prototipom. Plan se dopunjava posle faze 1.                                               |
| Promene projektnih zahteva u toku realizacije                  | Prioritizacija po metodi MoSCoW u okviru roka i budžeta. Od 120 komandi 70 je obaveznih, 30 poželjnih i 20 mogućih.                                  |
| Loša komunikacija članova projektnog tima                      | Dnevni sastanak od 15 minuta i nedeljni izveštaj. Svi zaključci i odluke u pisanoj formi.                                                            |
| Nizak nivo znanja o vođenju projekta i firme                   | Mentor investitora, obuka o metodologiji upravljanja projektima u decembru 2026.                                                                     |
| Eksterni saradnici kasne sa isporukom                          | Rokovi i penali u ugovorima. Rezervni dobavljač za svaki AI servis.                                                                                  |

## 12. ULAGANJA (Materijalna ograničenja)

Realizacija projekta košta najviše 321.200 €, a finansira je anđeo investitor. Eksploatacija rezultata košta 336.600 € fiksno godišnje, uz 1,40 € po plaćenom korisniku mesečno.

### Ulaganja u realizaciju projekta

| Stavka                                            | Obračun                                                            | Iznos (€)   |
| ------------------------------------------------- | ------------------------------------------------------------------ | ----------- |
| Osnivači                                          | 4 × 12 meseci × 2.500                                              | 120.000     |
| Softverski inženjeri za integracije               | 2 × 6 meseci × 4.000                                               | 48.000      |
| QA inženjer                                       | 1 × 6 meseci × 3.000                                               | 18.000      |
| Podrška korisnicima i zajednica                   | 1 × 3 meseca × 2.000                                               | 6.000       |
| **Ljudski resursi ukupno**                        | 69 čovek-meseci                                                    | **192.000** |
| Cloud i AI servisi tokom razvoja i beta           | Procena                                                            | 12.000      |
| Oprema                                            | Računari za Windows i macOS, mikrofoni, oprema za testiranje zvuka | 16.000      |
| Konsultant za govorne tehnologije                 | 30 radnih dana                                                     | 12.000      |
| UX dizajn                                         | Honorarno                                                          | 6.000       |
| Pravne usluge                                     | Ugovor sa investitorom, zaštita podataka, uslovi korišćenja        | 8.000       |
| Test korpus glasovnih komandi                     | Snimanje i označavanje 1.000 komandi                               | 10.000      |
| Licence, alati i sertifikati za potpis aplikacije | Procena                                                            | 4.000       |
| Kancelarija i knjigovodstvo                       | 12 meseci × 800                                                    | 9.600       |
| Marketing lansiranja                              | Kampanja i saradnja sa kreatorima sadržaja                         | 22.400      |
| **Nabavke i usluge ukupno**                       |                                                                    | **100.000** |
| Rezerva za rizike                                 | 10% od 292.000                                                     | 29.200      |
| **Ukupno ulaganje u realizaciju**                 |                                                                    | **321.200** |

Mesečne cene rada su ukupan trošak poslodavca po zaposlenom. Osnivači primaju niže plate nego što bi imali na tržištu, jer su vlasnici firme.

### Ulaganja u eksploataciju rezultata projekta

| Stavka                                     | Obračun                      | Godišnje (€) |
| ------------------------------------------ | ---------------------------- | ------------ |
| Osnivači                                   | 4 × 12 meseci × 2.500        | 120.000      |
| Softverski inženjeri                       | 2 × 12 meseci × 4.000        | 96.000       |
| QA inženjer                                | 1 × 12 meseci × 3.000        | 36.000       |
| Podrška korisnicima                        | 1 × 12 meseci × 2.000        | 24.000       |
| Infrastruktura, alati i nadzor             | Procena                      | 18.000       |
| Marketing                                  | Procena                      | 30.000       |
| Kancelarija, knjigovodstvo i pravne usluge | 12 meseci × 800 + 3.000      | 12.600       |
| **Fiksno ukupno**                          |                              | **336.600**  |
| AI servisi i naplata, godina 1             | 2.500 korisnika × 12 × 1,40  | 42.000       |
| AI servisi i naplata, godina 3             | 11.000 korisnika × 12 × 1,40 | 184.800      |

## 13. ROKOVI (Vremenska ograničenja)

Projekat traje od 13.11.2026. do 26.11.2027. Javno lansiranje je 29.10.2027, a poslednji mesec ostaje za analizu projekta i prelazak na redovno održavanje.

- Priprema projektnog plana i Definicije projekta do 18.12.2026.
- Realizacija
  - 1\. faza, analiza i prototip, do 26.02.2027. Kontrolna tačka: nastavak, sužavanje ili obustava.
  - 2\. faza, MVP za strim i zatvorena beta, do 28.05.2027. Kontrolna tačka: druga tranša, zapošljavanje i cena Pro verzije.
  - 3\. faza, režim montaže, do 27.08.2027.
  - 4\. faza, stabilizacija i javno lansiranje, do 29.10.2027.
- Zaključenje do 26.11.2027.

## 14. MENADŽER PROJEKTA

**Jovan Stoiljković**, suosnivač i direktor *NovaKadar d.o.o.*, zadužen za poslovanje, angažovan puno radno vreme tokom celog projekta.

Menadžer projekta odgovara upravnom odboru projekta, koji čine osnivači i predstavnik investitora, za rok, budžet i obim. Vodi tim od četiri osnivača, koji do lansiranja raste na osam članova.
