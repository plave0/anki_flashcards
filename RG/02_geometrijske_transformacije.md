Q:Šta su linearne transformacije u algebarskom smislu?
A:Linearna transformacija čuva zbir dva vektora i množenje vektora skalarom.
<!-- 1666787164727 -->

Q:Koja su geometrijska svojstva linearnih transformacija?
A:Prave se preslikavaju u prave i koordinatni početak se ne menja.
<!-- 1666787164757 -->

Q:Zašto su linearne transofrmacije značajne u računarskoj grafici?
A:Jeftine su za primenu, mogu se predstaviti matricama (što je povoljno za čuvanje u računaru) i možemo ih jednostavno komponovati.
<!-- 1666787164762 -->


Q:Kako izvodimo matricu određene linearne transformacije kada radimo sa ortonormiranom bazom?
A:Kolone matrice transforamacije će biti koordinate baznih vektora nakon izvršene transformacije.
<!-- 1666787164774 -->

Q:Koja su svojstva skaliranja u odnosu na koordinatni početak?
A:- Ne čuva uglove između pravih ako se ne skalira za isti faktor u odnosu na svaku osu.
- Objekti koji se ne nalaze u koordinatnom početku će biti udaljeni ili približeni u odnosu na koordinatni početak.
<!-- 1666788819228 -->

Q:Kako izvodimo matricu skaliranja i kako ona izgleda?
A:Svaki od baznih vektora pomnožimo određenim faktorom skaliranja. Ona je oblika: \[\begin{bmatrix} s _{X} & 0 \\ 0 & s _{Y} \end{bmatrix}\]
<!-- 1666787164791 -->

Q:Na koje dve transformacije možemo da rastavimo skaliranje kada su faktori skaliranja \(-1\) in \(-1\)?   
A:Možemo je rastaviti na refleksiju u odnosu na \(x\)-osu i refleksiju u odnosu na \(y\)-osu.
<!-- 1666787164793 -->

Q:Koja su svojstva rotacije u odnosu na koordinatni početak?
A:- Čuva dužine duži.
- Čuva uglove između duži.
<!-- 1666788819266 -->

Q:Kako izvodimo matricu rotacije i kako ona izgleda?
A:Bazni vektori se kreću po jediničnoj kružnici, pa je matrica rotacije za ugao \(\phi\) u odnosu na koordinatni početak oblika: \[\begin{bmatrix} \cos{\phi} & -\sin{\phi} \\ \sin{\phi} & \cos{\phi} \end{bmatrix}\]
<!-- 1666787164798 -->

Q:Koja su svojstva smicanja?
A:- Ne čuvaju se dužine duži, sem duži koje su u pravcu ose u odnosu nakoju se vrši smicanje.
- Ne čuvaju se uglovi.
<!-- 1666787164801 -->

Q:Kako izvodimo matricu smicanja?
A:Bazni vektor ortogonalan na smer smicanja se kreće po kotangensnoj tangetni jediničnog kruga, pa oblik matrice u pravcu \(x\)-ose za ugrao \(\phi\) je: \[\begin{bmatrix} 1 & \cot{\phi} \\ 0 & 1 \end{bmatrix}\] a u pravu \(y\)-ose je: \[\begin{bmatrix} 1 & 0 \\ \cot{\phi} & 1 \end{bmatrix}\]
<!-- 1666787164803 -->

Q:Zašto translacija nije linearna atransofmracija?
A:Transformacija translacije pomera koordinatni početak.
<!-- 1666787164805 -->

Q:Kako dobijamo matricu kompozicije nekih linearnih trasnformacije?
A:Matrice pojedinačnih transformacija množimo s leva nadesno.
<!-- 1666791220411 -->

Q:Zašto uvodimo homogene koordinate?
A:Zato što kompozicija translacije i bilo koje linearne tansformacije može predstaviti kao množenje matrica kada se radi u homogenim koordinatama.
<!-- 1666787164807 -->

Q:Koja je veza između afinih transofrmacija u dve dimenzije i linearnih tranformacija u tri dimenzije?
A:Afine transformacije u dve dimenzije možemo da predstavimo kao linearne transformacije u tri dimenzije.
<!-- 1666787164810 -->

Q:Šta je inverz matrice rotacije?
A:Inverz matrice rotacije je njen transponat.
<!-- 1666787164813 -->

Q:Šta dobijamo ako komponujemo dve trasnformacije istog tipa?
A:Kada komponujemo dve transformacije istog tipa, tada dobijamo transofmraciju istog tog tipa.
<!-- 1666787164818 -->

Q:Šta dobijamo kompozicijom translacija?
A:Dobija se translacija. Pomeraj dobijene translacije je jednak zbiru pomeraja pojedinačnih translacija.
<!-- 1666787164820 -->

Q:Šta dobijamo kompozicijom skaliranja u odnosu na koordinatni početak?
A:Dobija se skaliranje u odnosu na koordinatni početak. Faktori skaliranja dobijene transformacije se sobijaju množenjem faktora skaliranja pojedinačnih transofrmacija po koordinatama.
<!-- 1666787164824 -->

Q:Šta dobijamo kompozicijom rotacija oko koordinatnog početka?
A:Dobijamo rotiranje oko koordinatnog početka. Ugao rotacije jejednak zbiru uglova rotacije pojedinačnih transformacija.
<!-- 1666787164826 -->

Q:Šta dobijamo kompozicijom smicanja po istoj osi?
A:Dobija se smicanje po istoj osi. Ugao smicanja je jednak zbiru uglova pojedinačnih smicanja.
<!-- 1666787164829 -->

Q:Kako vršimo transofrmacije koje nisu u odnosu na koordinatni početak?
A:To možemo da uradimo tako što prvo izvršimo translaciju objekta u koordinatni početak, uradimo željenu linearnu transformaciju, pa zatim objekat vretimo u svoj prvobitni položaj inverznom translacijom.
<!-- 1666787164832 -->

Q:Šta dobijomo inverzom kompozicije transformacija?
A:Dobijamo kompoziciju inverza pojedinačnih transofrmacija primenjenih u suprotnom redosledu.
<!-- 1666787164834 -->

Q:Šta su izometrijske transofmracije?
A:Izometrijske transformacije su afine transformacije koje čuvaju stastojanje između tačaka.
<!-- 1666787164837 -->

Q:Kako izgleda matrica izometrijskih transformacija?
A:Ona je oblika \[\begin{bmatrix} a & b & t _{x} \\ c & d & t _{y} \\ 0 & 0 & 1 \end{bmatrix}\] gde je \[\begin{bmatrix} a & b \\ c & d \end{bmatrix}\] ortogonalna matrica.
<!-- 1666787164840 -->

Q:Šta čuvaju izometrijske transformacije?
A:Čuvaju rastojanje između tačaka, dužine duži i uglove među dužima.
<!-- 1666787164843 -->

Q:Koje transformacije spadaju u izometrijske transformacije?
A:Translacija, rotacija i simetrija.
<!-- 1666787164846 -->

Q:Šta dobijamo kompozicijom izometrijskih transofrmacija?
A:Dobija se izometrijska transformacija.
<!-- 1666787164849 -->

Q:Koja dva tipa izometrijskih transofmracija postoje?
A:Direktne i indirektne izometrijske transformacije.
<!-- 1666787164852 -->

Q:Šta su direktne izometrijske transofrmacije?
A:To su izometrijske transofmracije koje čuvaju orijentaciju ravni.
<!-- 1666791220459 -->

Q:Šta su indirektne izometrijske transofmracije?
A:To su izometrijske transofmracije koje ne čuva orijentaciju ravni.
<!-- 1666791220462 -->

Q:Šta su afine transofmracije?
A:Afine transformacije su transofrmacije koje čuvaju kolinearnost tačaka, ali ne nužno i njihvo rastojanje.
<!-- 1666787164854 -->

Q:Opšti oblik matrice afine transoframcije?
A:Matrice afinih transofrmacija su oblika: \[\begin{bmatrix} a & b & t _{x} \\ c & d & t _{y} \\ 0 & 0 & 1 \end{bmatrix}\].
<!-- 1666787164857 -->

Q:Razlaganje matrice afine transforamcije?
A:Matrica afine transormacije se može zapisati u obliku \[\begin{bmatrix} T ^{*} & t ^{*} \\ 0 & 1 \end{bmatrix}\] gde \(T ^{*}\) nazivamo linearnim delom transofmacije, a \(t ^{*}\) translacionim delom transofmracije.
<!-- 1666787164860 -->

