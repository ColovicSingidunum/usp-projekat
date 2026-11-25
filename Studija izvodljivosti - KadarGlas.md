# Studija izvodljivosti projekta KadarGlas

AI glasovni asistent za video montažu i striming uživo

NovaKadar d.o.o., Novi Sad, 13.11.2026.

## Sažetak

Predlažemo da se projekat pokrene, uz kontrolnu tačku posle prve faze. Ulaganje od 321.200 € trebalo bi da se vrati za oko 26 meseci od lansiranja, a neto sadašnja vrednost (NPV) za tri godine iznosi oko 349.200 €.

NovaKadar d.o.o. je novootvoreni startup iz Novog Sada sa četiri osnivača: dva programera, AI/ML inženjerom i osnivačem zaduženim za poslovanje. Firma još nema proizvod ni prihode, pa projekat finansira anđeo investitor, sa 450.000 € za 18% udela.

KadarGlas je desktop aplikacija za Windows i macOS koja radi u pozadini i glasom upravlja programima koje korisnik već koristi: OBS Studiom za strim i DaVinci Resolveom i Premiere Proom za montažu. Radi na srpskom i engleskom jeziku. Osnovna verzija je besplatna, a Pro verzija košta 10 € mesečno. Projekat traje od 13.11.2026. do 26.11.2027, a javno lansiranje planirano je za 29.10.2027.

*Napomena: kompanija NovaKadar i svi njeni interni podaci (osnivači, ankete, cene, troškovi) izmišljeni su za potrebe primera. Tržišni podaci su stvarni, a izvori su navedeni na kraju.*

### Šta KadarGlas radi

Korisnik izgovori komandu, a asistent je izvrši u programu koji je otvoren, pa ruke ostaju slobodne za kameru, instrument ili gejmpad. Primeri komandi:

- u montaži: „Iseci sve pauze duže od dve sekunde“, „Dodaj titlove na srpskom“, „Skrati ovaj klip na 30 sekundi“, „Pojačaj glas i utišaj muziku“
- tokom strima: „Prebaci na kameru dva“, „Pusti uvodnu špicu“, „Označi ovaj momenat“, „Isključi mikrofon gosta“

Svaka komanda može da se poništi. Za komande koje brišu sadržaj ili prekidaju prenos asistent prvo traži glasovnu potvrdu.

Besplatna verzija sadrži 30 osnovnih komandi koje se prepoznaju lokalno na računaru korisnika. Pro verzija otključava svih 120 komandi i prirodan govor, što radi preko servisa u oblaku.

## 1. Finansijska izvodljivost (Financial appraisal)

Projekat ispunjava sva četiri finansijska kriterijuma koja smo dogovorili sa investitorom, a novac investitora pokriva i realizaciju i gubitak u prvoj godini posle lansiranja.

### Da li se projekat isplati?

Za tri godine od lansiranja projekat donosi 1.002.600 € neto novčanog toka, uz ulaganje od 321.200 €. To je prinos na ulaganje (ROI) od 212%. Prva godina je u gubitku, jer korisnike tek treba privući, a od druge godine prihod pokriva troškove.

| Stavka modela                          | Godina 1 | Godina 2 | Godina 3  |
| -------------------------------------- | -------- | -------- | --------- |
| Aktivni besplatni korisnici (prosek)   | 50.000   | 120.000  | 220.000   |
| Plaćeni korisnici Pro verzije (prosek) | 2.500    | 6.000    | 11.000    |
| Prihod (€)                             | 300.000  | 720.000  | 1.320.000 |
| Operativni troškovi (€)                | 378.600  | 437.400  | 521.400   |
| Neto novčani tok (€)                   | −78.600  | 282.600  | 798.600   |

Model polazi od sledećih pretpostavki:

- prva godina počinje lansiranjem, 29.10.2027.
- Pro verziju plaća 5% aktivnih korisnika, po 10 € mesečno (120 € godišnje, bez PDV-a)
- fiksni trošak eksploatacije je 336.600 € godišnje, uglavnom za tim od osam ljudi
- varijabilni trošak je 1,40 € po plaćenom korisniku mesečno. Od toga 0,90 € odlazi na servise za prepoznavanje govora i jezički model, a 0,50 € na naplatu (5% cene)
- besplatni korisnici ne stvaraju trošak servisa, jer se njihove komande prepoznaju lokalno

### Tržište i konkurencija

Tržište softvera za video montažu procenjuje se na 3,75 milijardi USD u 2026. godini i 4,99 milijardi USD u 2031, uz rast od 5,88% godišnje ([Mordor Intelligence, prema Vidpros](https://vidpros.com/video-editing-software-statistics/)). Softver za striming uživo raste brže, sa 2,60 milijardi USD u 2026. na 8,04 milijarde USD u 2032, odnosno oko 20,6% godišnje ([360iResearch](https://www.giiresearch.com/report/ires2012198-live-streaming-software-market-by-component.html)). Procene različitih izdavača dosta se razlikuju, zavisno od toga kako definišu tržište, pa ih uzimamo samo kao pokazatelj rasta.

Descript ima AI asistenta Underlord, a Adobe Premiere nudi pretragu snimaka prirodnim jezikom. Nijedan od devet AI editora iz [pregleda koji je objavio Descript](https://www.descript.com/blog/article/best-ai-video-editor) ne radi na glasovne komande. OBS Studio, glavni alat za oko 60% strimera ([VoxBooster](https://voxbooster.com/blog/streaming-software-statistics-2026)), takođe nema glasovno upravljanje. Naša prednost je to što korisnik ne mora da menja program na koji je navikao, a glasovno upravljanje na srpskom jeziku ne nudi niko.

### Da li ispunjava finansijske kriterijume organizacije?

Ispunjava sva četiri. Kriterijume smo postavili zajedno sa investitorom. Diskontna stopa od 15% je viša nego za postojeću firmu, jer je ulaganje u startup rizičnije.

| Kriterijum                                    | Prag                  | Rezultat projekta              | Ispunjen |
| --------------------------------------------- | --------------------- | ------------------------------ | -------- |
| NPV za 3 godine, diskontna stopa 15%          | veći od 0             | 349.200 €                      | Da       |
| Interna stopa prinosa (IRR)                   | najmanje 30%          | 48,2%                          | Da       |
| Period povraćaja od lansiranja                | najviše 36 meseci     | oko 26 meseci                  | Da       |
| Investicija pokriva najveću potrebu za novcem | uz rezervu od bar 10% | potreba 399.800 €, rezerva 11% | Da       |

NPV smo izračunali uz diskontnu stopu od 15%:

NPV = −321.200 − 78.600 / 1,15 + 282.600 / 1,15² + 798.600 / 1,15³ ≈ 349.200 €

Posle dve godine ostaje nepokriveno još 117.200 €, a to treća godina pokrije za manje od dva meseca. Otuda period povraćaja od oko 26 meseci. Mesečni prihod prestiže troškove kada broj plaćenih korisnika pređe oko 3.300, što očekujemo početkom druge godine.

### Možemo li da obezbedimo novac?

Možemo, ali samo uz investitora, jer firma nema sopstveni novac ni prihode. Anđeo investitor ulaže 450.000 € za 18% udela, u dve tranše:

- 250.000 € po potpisivanju ugovora, do 18.12.2026.
- 200.000 € posle druge kontrolne tačke, 28.05.2027, ako beta za strim dostigne dogovorene ciljeve

Ulaganje u realizaciju iznosi 321.200 €. Od toga 192.000 € ide na rad tima, 100.000 € na usluge, opremu i marketing, a 29.200 € je rezerva za rizike (10%). Detaljan obračun nalazi se u tački 12 Nacrta projekta.

Najveća potreba za novcem je na kraju prve godine posle lansiranja, kada se ulaganju doda i gubitak te godine, ukupno 399.800 €. Investicija to pokriva, uz 50.200 € rezerve.

## 2. Tehnička izvodljivost (Technical)

Sve potrebne komponente već postoje kao gotove usluge, otvoreni modeli ili javni API-ji programa kojima upravljamo. Otvorena su još dva pitanja, tačnost za srpski jezik i brzina odziva tokom strima, i njih proveravamo prototipom u fazi 1.

Komanda prolazi kroz pet koraka:

1. Korisnik drži taster (push-to-talk) ili izgovori budnu reč „Kadar“.
2. Osnovne komande prepoznaje lokalni model na računaru. Ostale se šalju servisu za prepoznavanje govora (STT) u oblaku.
3. Jezički model pretvara izgovorenu rečenicu u komandu iz unapred definisanog kataloga.
4. KadarGlas izvršava komandu preko API-ja otvorenog programa: obs-websocket za OBS Studio, skripting API za DaVinci Resolve i proširenje (UXP) za Premiere Pro. Za ostale programe koristi prečice na tastaturi.
5. Aplikacija potvrđuje izvršenje oznakom na ekranu i kratkim zvučnim signalom, a za rizične komande traži glasovnu potvrdu.

### Da li imamo veštine i znanje?

Osnovne veštine imamo, jer osnivači pokrivaju razvoj aplikacije, AI/ML i poslovanje. Ostalo dobijamo zapošljavanjem posle prve bete i angažovanjem spoljnih saradnika.

| Potrebna veština                                  | Stanje u timu                                | Mera                                    |
| ------------------------------------------------- | -------------------------------------------- | --------------------------------------- |
| Razvoj desktop aplikacije (Windows, macOS)        | Imamo: dva osnivača programera               | Nije potrebna                           |
| Prepoznavanje govora i jezički modeli             | Imamo: osnivač AI/ML inženjer                | Nije potrebna                           |
| Integracija sa OBS Studiom                        | Delimično: iskustvo sa obs-websocket API-jem | Prototip u fazi 1                       |
| Integracija sa DaVinci Resolveom i Premiere Proom | Nemamo                                       | Dva softverska inženjera od 01.06.2027. |
| Govorne tehnologije za srpski jezik               | Nemamo                                       | Eksterni konsultant, 30 radnih dana     |
| Dizajn glasovnog interfejsa                       | Nemamo                                       | UX dizajner, honorarno                  |
| Testiranje kvaliteta                              | Nemamo                                       | QA inženjer od 01.06.2027.              |
| Zaštita podataka i propisi o AI                   | Nemamo                                       | Advokatska kancelarija                  |

### Da li je zaista moguće?

Jeste, ako prototip u fazi 1 dostigne pragove iz tabele. Ako ih ne dostigne, na kontrolnoj tački 26.02.2027. projekat se zaustavlja ili mu se smanjuje obim.

| Pokazatelj                                          | Cilj                                  | Kako se meri                           |
| --------------------------------------------------- | ------------------------------------- | -------------------------------------- |
| Tačnost izvršenja komande                           | najmanje 95% engleski, 92% srpski     | Test korpus od 500 komandi po jeziku   |
| Odziv u režimu strima, od kraja govora do izvršenja | najviše 800 ms za 30 osnovnih komandi | Lokalno prepoznavanje osnovnih komandi |
| Odziv u režimu montaže                              | najviše 2 s                           | Merenje na referentnom računaru        |
| Lažna aktivacija budne reči                         | najviše 1 na 8 sati strima            | Test sa muzikom i govorom gostiju      |
| Rad bez interneta                                   | 30 osnovnih komandi                   | Lokalni model                          |

Kod strima postoji još jedan problem. Mikrofon koji sluša komande ide i u prenos, pa bi gledaoci čuli svaku komandu. Zato taster za komandu istovremeno isključuje mikrofon iz prenosa dok se komanda izgovara.

Pošto ne pravimo sopstveni editor, zavisimo od API-ja tuđih programa. Prototip zato proverava i da li ti API-ji pokrivaju radnje koje su nam potrebne.

### Da li će dobavljači moći da isporuče?

Hoće. Za servise u oblaku postoje bar dva ponuđača i lokalna rezerva. Za programe kojima upravljamo rezerva su prečice na tastaturi.

| Komponenta             | Primarni izvor                                      | Rezerva                                                                |
| ---------------------- | --------------------------------------------------- | ---------------------------------------------------------------------- |
| Prepoznavanje govora   | Komercijalni STT servis sa strimovanjem             | Drugi ponuđač; lokalni otvoreni model                                  |
| Jezički model          | Komercijalni LLM API sa pozivanjem funkcija         | Drugi ponuđač preko istog sloja; lokalni mali model za osnovne komande |
| Budna reč              | Lokalni model otvorenog koda                        | Samo taster                                                            |
| Upravljanje programima | API-ji OBS Studija, DaVinci Resolvea, Premiere Proa | Prečice na tastaturi                                                   |
| Naplata pretplate      | Platni servis koji obračunava i PDV                 | Drugi platni servis                                                    |

Cene prepoznavanja govora u realnom vremenu kreću se od 0,15 do 1,02 USD po satu zvuka ([AssemblyAI, poređenje ponuđača od 03.11.2026](https://assemblyai.com/blog/speech-to-text-api-pricing)). U fazi 1 treba utvrditi koji ponuđač podržava srpski jezik u realnom vremenu uz traženu tačnost.

## 3. Organizaciona izvodljivost (Organizational)

Projekat počinju četiri osnivača, a tim raste na osam ljudi do lansiranja. Novi ljudi dolaze tek kada beta potvrdi da proizvod ima korisnike.

### Možemo li to da uradimo?

Možemo, uz pomoć investitora. Osnivači znaju da naprave proizvod, ali nisu do sada vodili firmu ni projekat ove veličine. Zato investitor ima predstavnika u upravnom odboru projekta i dodeljuje nam mentora sa iskustvom u startapima.

Projekat vodi osnivač zadužen za poslovanje. Radimo u sprintovima od dve nedelje, a faze se završavaju kontrolnim tačkama na kojima se odlučuje o nastavku.

### Da li imamo ljude i opremu?

Za prve dve faze imamo, jer MVP prave sami osnivači. Za režim montaže i lansiranje zapošljavamo još četiri osobe. Ukupno je potrebno 69 čovek-meseci rada.

| Uloga                              | Broj ljudi | Angažovanje          | Izvor         |
| ---------------------------------- | ---------- | -------------------- | ------------- |
| Direktor i menadžer projekta       | 1          | 100%, ceo projekat   | Osnivač       |
| Softverski inženjer                | 2          | 100%, ceo projekat   | Osnivači      |
| AI/ML inženjer za govor i jezik    | 1          | 100%, ceo projekat   | Osnivač       |
| Softverski inženjer za integracije | 2          | 100%, od 01.06.2027. | Zapošljavanje |
| QA inženjer                        | 1          | 100%, od 01.06.2027. | Zapošljavanje |
| Podrška korisnicima i zajednica    | 1          | 100%, od 01.09.2027. | Zapošljavanje |

Osnivači rade na sopstvenim računarima. Treba nabaviti računare za testiranje na Windowsu i macOS-u, različite mikrofone i opremu za testiranje zvuka, ukupno za 16.000 €. Kancelariju iznajmljujemo u coworking prostoru.

### Da li je to vrsta posla kojom se bavimo?

Jeste. Firma je osnovana upravo zbog ovog proizvoda. To je i prednost i rizik: ceo tim radi samo na KadarGlasu, ali firma nema drugi izvor prihoda ako proizvod ne uspe.

## 4. Kulturološka izvodljivost (Cultural)

Projekat je poželjan i etički prihvatljiv, pod uslovom da asistent obrađuje glas samo kada ga korisnik sam uključi.

### Da li želimo to da uradimo?

Želimo. Sva četiri osnivača rade puno radno vreme na projektu, a investitor je spreman da uloži novac. U anketi koju smo u oktobru 2026. sproveli među 300 strimera i montažera iz online zajednica, 52% bi probalo glasovno upravljanje, a 21% bi ga platilo. U modelu smo ipak računali da će Pro verziju plaćati samo 5% aktivnih korisnika.

### Da li je etično i moralno?

Jeste, uz mere iz tabele. Najosetljivija je privatnost, jer je glas podatak o ličnosti, a mikrofon hvata i goste i ukućane.

| Pitanje             | Rizik                                      | Mera                                                                                                             |
| ------------------- | ------------------------------------------ | ---------------------------------------------------------------------------------------------------------------- |
| Privatnost glasa    | Snimanje ljudi koji nisu dali pristanak    | Slušanje samo na taster ili budnu reč; zvuk se ne čuva; jasna oznaka kada asistent sluša                       |
| Obuka modela        | Korišćenje podataka korisnika bez pristanka | Zvuk se ne čuva, pa se ne koristi za obuku; uz izričit pristanak, koji se može povući, za poboljšanje se koristi samo tekst komandi; dobavljačima STT i LLM servisa ugovorom je zabranjena obuka na podacima korisnika |
| Transparentnost     | Korisnik ne zna šta je AI uradio           | Svaka radnja je vidljiva u istoriji komandi i može se poništiti                                                  |
| Jednak kvalitet     | Slabija tačnost za neke govornike          | Test korpus pokriva ekavicu i ijekavicu, muške i ženske glasove i različite akcente; tačnost se prati po grupama |
| Uticaj na montažere | Strah da AI zamenjuje ljude                | Asistent izvršava komande, a kreativne odluke ostaju korisniku                                                   |

Projekat je koristan i osobama sa motoričkim teškoćama, koje će moći da montiraju i strimuju glasom. Asistent ne prepoznaje ko govori i ne klonira glas, i obe ove funkcije su izričito van obima projekta.

### Da li je uvredljivo?

Nije. Asistent ne pravi sadržaj za publiku i govori samo kratke potvrde. Titlove pravi sam editor, a KadarGlas samo pokreće tu funkciju.

## 5. Operativna izvodljivost (Operational)

Projektom možemo da upravljamo, a gotov proizvod održava tim od osam ljudi. Fiksni troškovi posle lansiranja iznose 336.600 € godišnje, a svaka kritična komponenta ima rezervu.

### Možemo li da upravljamo projektom?

Možemo. Upravni odbor projekta čine četiri osnivača i predstavnik investitora. Sastaje se jednom mesečno i na kraju svake faze. Menadžer projekta svake nedelje šalje izveštaj o roku, budžetu, obimu i rizicima. Izmene zahteva prolaze postupak upravljanja promenama, a prioriteti se određuju metodom MoSCoW.

### Možemo li da podržimo rezultat kada se završi?

Možemo. Ceo tim ostaje na proizvodu i posle lansiranja, a njegov trošak je već uračunat u finansijski model.

| Stavka eksploatacije                        | Godišnje (€) |
| ------------------------------------------- | ------------ |
| Osnivači: 4 × 12 meseci × 2.500             | 120.000      |
| Softverski inženjeri: 2 × 12 meseci × 4.000 | 96.000       |
| QA inženjer: 12 meseci × 3.000              | 36.000       |
| Podrška korisnicima: 12 meseci × 2.000      | 24.000       |
| Infrastruktura, alati i nadzor              | 18.000       |
| Marketing                                   | 30.000       |
| Kancelarija, knjigovodstvo i pravne usluge  | 12.600       |
| Ukupno fiksno                               | 336.600      |

Tim prati tačnost i brzinu odziva u produkciji i svaka tri meseca dodaje nove komande u katalog. Cilj je da servis u oblaku bude dostupan 99,5% vremena.

### Da li imamo potrebne rezerve?

Imamo. Asistent je zamišljen tako da nikada nije jedini način da se nešto uradi, jer programi kojima upravlja rade i bez njega.

| Šta može da otkaže         | Rezerva                                                                          |
| -------------------------- | -------------------------------------------------------------------------------- |
| Glasovni asistent u celini | Korisnik nastavlja rad mišem i tastaturom; asistent se može daljinski isključiti |
| STT servis                 | Automatski prelazak na drugog ponuđača ili lokalni model                         |
| LLM servis                 | Lokalni model za 30 osnovnih komandi                                             |
| API nekog programa         | Prečice na tastaturi dok se integracija ne popravi                               |
| Internet kod korisnika     | Osnovne komande rade lokalno                                                     |
| Ključni član tima          | Zamenik za svaku ulogu, rad u paru, dokumentacija                                |
| Kod i test korpus          | Dnevna rezervna kopija na dve lokacije                                           |

## 6. Rizici (Risk)

Postoji rizik koji ugrožava opstanak firme. KadarGlas je njen jedini proizvod, pa bi neuspeh projekta značio i gašenje startapa. Rizik smanjujemo tako što novac stiže u tranšama, a o nastavku se odlučuje na kontrolnim tačkama.

### Postoje li rizici koji ugrožavaju organizaciju?

Postoje. Ako proizvod ne privuče dovoljno plaćenih korisnika, novac investitora će se potrošiti pre nego što prihod pokrije troškove. Osnivači ne garantuju ličnom imovinom, pa bi najveći gubitak bio novac investitora i godina rada osnivača. Dva rizika mogu i da naškode ugledu, pa za njih imamo najstrože mere: pogrešna komanda tokom prenosa uživo i incident sa privatnošću glasa.

| Rizik                                              | Verovatnoća | Uticaj  | Odgovor                                                                                     |
| -------------------------------------------------- | ----------- | ------- | ------------------------------------------------------------------------------------------- |
| Premalo korisnika, jer nemamo postojeću bazu       | Visoka      | Visok   | Besplatna verzija, zatvorena beta sa 300 strimera, saradnja sa kreatorima sadržaja          |
| Tačnost za srpski jezik ispod 92%                  | Srednja     | Visok   | Prototip u fazi 1; rezerva je lansiranje samo na engleskom, srpski kasnije                  |
| Odziv uživo duži od 800 ms                         | Srednja     | Visok   | Lokalno prepoznavanje 30 osnovnih komandi                                                   |
| Pogrešna komanda tokom prenosa uživo               | Srednja     | Visok   | Potvrda za rizične komande, poništavanje, beta pre lansiranja                               |
| Promena API-ja OBS Studija, Resolvea ili Premierea | Srednja     | Visok   | Praćenje najava proizvođača, automatski testovi integracija, prečice kao rezerva            |
| Investitor ne isplati drugu tranšu                 | Niska       | Visok   | Jasni ciljevi bete u ugovoru; ako se ne isplati, lansira se samo režim strima               |
| Odlazak osnivača                                   | Niska       | Visok   | Ugovor osnivača sa postepenim sticanjem udela, dokumentacija, rad u paru                    |
| Kašnjenje u zapošljavanju                          | Srednja     | Srednji | Oglasi od aprila 2027, honorarni saradnici do dolaska novih ljudi                           |
| Incident sa privatnošću glasa                      | Niska       | Visok   | Zvuk se ne čuva, procena uticaja na zaštitu podataka, bezbednosno testiranje pre lansiranja |
| Rast cena ili ukidanje servisa dobavljača          | Niska       | Srednji | Dva ponuđača iza istog sloja, lokalni model                                                 |

Mere za svaki rizik detaljnije su opisane u tački 11 Nacrta projekta.

### Da li smo spremni da rizikujemo?

Jesmo, jer se rizik preuzima postepeno. Do prve kontrolne tačke, 26.02.2027, potrošiće se oko 80.000 €, odnosno četvrtina ulaganja. Tada će prototip pokazati da li su tačnost i brzina dostižne, a upravni odbor odlučuje da li se projekat nastavlja, sužava ili obustavlja.

Druga kontrolna tačka je kraj bete za strim, 28.05.2027. Tada investitor odlučuje o drugoj tranši, a mi o zapošljavanju i ceni Pro verzije.

### Da li je raspon mogućih ishoda prihvatljiv?

Za investitora jeste, jer je to uobičajen rizik ulaganja u startup. Projekat izlazi na nulu kada ostvari 76% planiranog prihoda. U pesimističkom scenariju gubitak je veliki, a novac investitora ne bi bio dovoljan.

| Scenario     | Obim prihoda u odnosu na plan | NPV za 3 godine (€) | Period povraćaja  |
| ------------ | ----------------------------- | ------------------- | ----------------- |
| Pesimistički | 60%                           | −226.400            | Duže od 36 meseci |
| Osnovni      | 100%                          | +349.200            | Oko 26 meseci     |
| Optimistički | 130%                          | +780.900            | Oko 20 meseci     |

U pesimističkom scenariju najveća potreba za novcem bila bi 503.000 €, više od uloženih 450.000 €. Zato smo unapred dogovorili meru: ako šest meseci posle lansiranja Pro verziju plaća manje od 1.500 korisnika, tim se smanjuje na osnivače i jednog inženjera, ili tražimo novu rundu ulaganja.

## Zaključak i preporuka

Projekat je izvodljiv u svih šest oblasti i preporučujemo da se pokrene (GO), uz tri uslova:

1. ugovor sa investitorom, sa obe tranše i ciljevima bete, potpisuje se do 18.12.2026.
2. prototip do kontrolne tačke 26.02.2027. dostiže pragove tačnosti i brzine iz oblasti 2
3. procena uticaja na zaštitu podataka završava se pre početka bete sa korisnicima

Sledeći korak je odobrenje Nacrta projekta, koji je priložen uz ovu studiju.

## Izvori

Tržišni podaci i cenovnici preuzeti su zaključno sa 10.11.2026.

- [Vidpros: statistika softvera za video montažu 2026](https://vidpros.com/video-editing-software-statistics/), prenosi procenu Mordor Intelligence
- [360iResearch: Live Streaming Software Market, prognoza 2026–2032](https://www.giiresearch.com/report/ires2012198-live-streaming-software-market-by-component.html)
- [AssemblyAI: vodič kroz cene STT servisa, 03.11.2026](https://assemblyai.com/blog/speech-to-text-api-pricing)
- [Descript: pregled AI video editora](https://www.descript.com/blog/article/best-ai-video-editor), blog jednog od ponuđača
- [VoxBooster: statistika softvera za striming 2026](https://voxbooster.com/blog/streaming-software-statistics-2026)
