Q:Šta je projekat softvera?
A:Plan po kome će se implementirati neki softver.
<!-- 1667209013891 -->

Q:Koje informacije treba da srdži jedan projekat sofvera?
A:Projekat softvera treba da sadrži informacije o tome šta se pravi, zašto se prav, i kako će se napraviti.
<!-- 1667209013896 -->

Q:Na koje tri gurpe možemo da podelimo metodologije razvoja?
A:Na klasične metodologije, objektno orijentisane metodologije i agilne metodologije.
<!-- 1667209013898 -->

Q:Šta karakteriše klasične metodologije?
A:Striktan redosled obavljanja poslova i posmatranej problema usmereno na posmatranje procesa koji čine taj problem.
<!-- 1667209013900 -->

Q:Kako izgleda životni ciklus projekta u klasičnim razvojnim metodologijama?
A:Analiza projekta, projektovanje, kodiranje, testiranje, održavanje.
<!-- 1667209013903 -->

Q:Šta je model vodopada?
A:Model vodopada opisuje model razvoja softvera koji podrazumeva:
- Kretanje kroz razvojne faze samo u jednom smeru.
- Prelazak u narednu fazu samo kada je tekuća faza završena.
<!-- 1667209013905 -->

Q:Šta karakteriše OO metodologiju razvoja softvera?
A:Fokus se sa opisivane procesa prebacuje na opisivanje objekata unutar problema i enkapsulaciju njihovih ponašanje.
<!-- 1667209013907 -->

Q:Šta znači da su objekti stabilniji od procesa?
A:- Procesi imaju veću tendenciju nastajanja i nestajanja.
- Promene u procesima povlače dublje promene nego promene u objektima i njihovim ponašanjima.
<!-- 1667209013910 -->

Q:Šta karakterišu agilne metodologije?
A:- Brisanje oštih granica između različitih faza razvoja softvera.
- Razvijaoci su osposobljeni i za projektovanje i za razvoj softvera.
<!-- 1667209013912 -->

Q:Šta je dizajn softvera?
A:Struktura sorverskog sistema (komponente, implementacija, strukture podataka, mopoćni alati,...)
<!-- 1667209013914 -->

Q:Šta je arhitektura softvera?
A:Struktura softverskog sistema posmatrana na relativno visokom nivou, bez ulaženja u detalje implementacije softvera.
<!-- 1667209013916 -->

Q:Kako možemo definisati razliku između arhitekture i dizajna softvera?
A:Arhitektura predstavlja značajne odluke o dizajnu koje daju oblik sistemu, gde je značajnost određena cenom pravljenja izmena.
<!-- 1667209013919 -->

Q:Koja su dva osnovna postupka u projektovanju softvera?
A:Apstrakcija i dekomponovanje.
<!-- 1667209013921 -->

Q:Šta je apstrahovanje?
A:Apstrahovanje je uopštavanje karakteristika nekog problema zanemarivanjem pojedinosti pojedinačnih slučajeva koje ne utiču na opšti koncept rešenja.
<!-- 1667209013923 -->

Q:Šta je dekomponovanje?
A:Dekomponovanje je proces prepoznavanja manjih celina i pojedinosti u modelu jednog softvera.
<!-- 1667209013925 -->

Q:Koji su najvažniji vidovi apstrahovanja?    
A:Klasifikacija, generalizacija, oblikovanje servisa i komponovanje.
<!-- 1667209013928 -->

Q:Šta je klasifikovanje u kontekstu apstrakcije?
A:Klasifikacija je prepoznavanje zajedničkih karakteristika skupa posmatranih obejekata (definisanje klasa).
<!-- 1667209013930 -->

Q:Šta je generalizacija u kontekstu apstrakcije?
A:Generalizacija je izdvajanje zajedničkih karakteristika koje definišu neki skup klasa.
<!-- 1667209013933 -->

Q:Šta je oblikovanje servisa u kontekstu apstrakcije?
A:Oblikovanje servisa je definisanje apstraktnog interfejsa koji od servisa zahteva da pružaju određene usluge bez definisanja kako te usluge treba da se implementiraju.
<!-- 1667209013935 -->

Q:Šta je komponovanje u konktestu apstrakcije?
A:Podrazumeva grupisane skupa objekata koji mogu da se posmatraju kao jeda celina iz "spoljašnjeg" sveta.
<!-- 1667209013937 -->

Q:Šta je funkcionalna dekompozicija?
A:Funkcionalna dekompozicija je rastavljanje celine na manje komponente, svaka od kojih obavlja tačno jednu, doboro definisanu ulogu.
<!-- 1667209013940 -->

Q:Šta je dekompozicija prema promenljivosti?
A:Dekomponovanje prema promenljivosti podrazumeva razdvajanje tačaka promenljivosti, i grupisanje osa promenljivosti.
<!-- 1667209013942 -->

Q:Šta je logička dekompozicija?
A:Logička dekompozicija podrazumeva dekomponovanje softvera na celine koje se mogu zajedno distribuirati, iako ne moraju da predstavljaju jednu funkcionalnu celinu.
<!-- 1667209013944 -->

Q:Šta je kohezija sistema?
A:Stepen povezanosti elemenata jednog modula.
<!-- 1667209013946 -->

Q:Šta je spregnutost sistema?
A:Stepen međusobne povezanosti elemenata dvaju različitih modula.
<!-- 1667209013949 -->

Q:Kakvi su kohezija i spregnutost u dobro dizajniranom softveru?
A:Kohezija je visoka, a spregnutost niska.
<!-- 1667209013951 -->

Q:Koje vrste kohezije postoje?
A:- Funckionalna
- Sekvencjalna
- Komunikaciona
- Proceduralna
- Vremenska
- Logička
- Koincidentalna
<!-- 1667209013953 -->

Q:Šta je funkcionalna kohezija?
A:Povezanost delova jednog modula na osnovu međusobne funkcionalne zavisnosti.
<!-- 1667209013955 -->

Q:Šta je sekvencijalna kohezija?
A:Povezanost delova jednog modula tako da izlaz jedne komponente predstavlja ulaz druge tako da ne postoji potpuna funkcionalna kohezija.
<!-- 1667209013957 -->

Q:Šta je komunikaciona kohezija? 
A:Grupisanje komponenti u jedan modul se zasniva na činjenici da svi koriste iste podatke, ali ne moraju da budu funkcionalno zavisne.
<!-- 1667209013959 -->

Q:Šta je proceduranla kohezija?
A:Grupisanje komponenti u jedan modul se zasniva na činjenici da se koriste za izvršavanje nekog celovitog posla, ali ne moraju da budu funkcionalno zavisne.
<!-- 1667209013961 -->

Q:Šta je vremenska kohezija?
A:Grupisanje komponenti u jednom modulu se zasniva na činjenici da se koriste u približno istom vremenskom periodu, ali ne mora da budu funkcionalno zavisne.
<!-- 1667209013963 -->

Q:Šta je logička kohezija?
A:Grupisanje komponenti u jednom modulu se zasniva na činjenici da imaju slične uloge u sistemu, ali ne mora da budu funkcionalno zavisne.
<!-- 1667209013965 -->

Q:Šta je slučajna kohezija?
A:Komponente unutar modula nisu spregnute ili su veoma nisko spregnute.
<!-- 1667209013968 -->

Q:Koje su tri vrste spregnutosti?
A:- Sprega logike
- Sprega tipova 
- Sprega specifikacije
<!-- 1667209013970 -->

Q:Šta je logička sprega?
A:Komponente dele informacije ili pretpostavke jedna o drugoj.
<!-- 1667209013972 -->

Q:Da li je logička sprega poželjna?
A:Nije.
<!-- 1667209013975 -->

Q:Šta je sprega tipova?
A:Jedna komponenta koristi tipove definisane u drugoj komponenti.
<!-- 1667209013977 -->

Q:Koji tipovi sprege tipova postoje?
A:Određena i neodređena.
<!-- 1667209013979 -->

Q:Šta je određena sprega tipova?
A:Ako se u komponenti A prave instance tipa iz komponente B.
<!-- 1667209013982 -->

Q:Šta je neodređena sprega tipova?
A:Ako se u komponenti A ne prave instance tipa definisanog u komponenti B.
<!-- 1667209013984 -->

Q:Da li je sprega tipova poželjna?
A:Ako je ona dobro implementirana, i kada je neodređena, onda nije nepoželjna.
<!-- 1667209013986 -->

Q:Šta je sprega specifikacije?
A:Komponente dele samo pretpostavke o izgledu iterfejsa.
<!-- 1667209013989 -->

Q:Da li je sprega specifikacije poželjna?
A:Kada je dobro implementirana onda nije nepoželjna.
<!-- 1667209013991 -->

Q:Koji nivoi spregnutosti postoje?
A:- Po sadržaju
- Preko zajedničkih delova
- Spoljašnja spregnutost
- Preko kontrole
- Preko markera
- Preko podataka
- Preko poruka
<!-- 1667209013993 -->

Q:Šta je spregnutost po sadržaju?
A:Neposredno pristupanje ili menjanje sadržaja unutar neke druge komponente.
<!-- 1667209013995 -->

Q:Šta je spregnutost preko zajedničkih delova?
A:Dve ili više komponenti neposredno pristupaju nekim zajedničkim podacima.
<!-- 1667209013998 -->

Q:Šta je spoljašnja spregnutost?
A:Dve ili više komponenti koriste neki interfejs nametnut sa spoljašnosti celokupnog softvera.
<!-- 1667209014001 -->

Q:Šta je spregnutost preko kontrole?
A:Jedna komponenta upravlja radom druge komponente.
<!-- 1667209014003 -->

Q:Šta je spregnutosto preko markera?
A:Više komponenti međusobno razmenjuju neku složenu strukturu podataka (marker), tako da svaki od modula strukturom upravlja na različiti način.
<!-- 1667209014006 -->

Q:Šta je spregnutost preko podataka?
A:Jedna komponenta koristi interfejs druge komponente putem koga se prenose informacije.
<!-- 1667209014009 -->

Q:Šta je spregnutost preko poruka?
A:Jedna komponenta koristi interfejs druge komponente pri čemu se ne prenose nikakvi podaci.
<!-- 1667209014012 -->

Q:Šta je širina sprege?
A:Broj elemenata komponente A koje upotrebljavaju elemente komponente B.
<!-- 1667209014014 -->

Q:Da li je široka ili uska sprega poželjnija?
A:Uska sprega je poželjnija.
<!-- 1667209014017 -->

Q:Koji su smerovi sprege?    
A:Jednosmerna, dvosmerna i cirkularna.
<!-- 1667209014020 -->

Q:Šta je jednosmerna sprega?
A:Jedna komponenta upotrebljava drugu komponentu, ali ne i obrnuto.
<!-- 1667209014023 -->

Q:Šta je dvosmerna sprega?
A:Komponenta A upotrebljava komponentu B, ali i obrnuto.
<!-- 1667209014025 -->

Q:Šta je cirkularna sprega?
A:Komponenta A upotrebljava komponentu B, ali i komponenta B posredno upotrebljava komponentu A.
<!-- 1667209014028 -->

Q:Na koje načine može da se ostvari sprega?
A:Statički i dinamički.
<!-- 1667209014030 -->

Q:Koji smer sprege je najpoželjniji?
A:Jednosmerna sprega.
<!-- 1667209014033 -->

Q:Šta je statička sprega?
A:Sprega se ostvaru pre početka izvršavanja programa.
<!-- 1667209014036 -->

Q:Šta je dinamička sprega?
A:Sprega se ostvaruje u toku izvšavanja programa.
<!-- 1667209014039 -->

Q:Koja je sprega poželjnija, statička ili dinamička?
A:Dinamička sprega je poželjnija.
<!-- 1667209014042 -->

