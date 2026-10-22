# NEON NEXUS 3D — Combat Edition v3.4.0

## FPS Animated Arsenal v1.2 — új karakterek és animációk

**FPS játék:** https://zsombi12345.github.io/neon-nexus-3d/fps.html  
**Eredeti külső nézetes játék:** https://zsombi12345.github.io/neon-nexus-3d/ (változatlan)

Az FPS változatban három **beépített** procedurális 3D skin választható, külön GLB feltöltése nélkül:
- **Nova Reaper:** saját tervezésű, sötét-lila cyber-nindzsa, energiamaszk, fénylő páncélzat és köpeny.
- **Astra Sentinel:** saját tervezésű, fehér/arany futurisztikus őrző, kék energia-kristályok és fénykorona.
- **Po:** a korábban használt pandás 3D skin **változatlanul megmaradt**.

### Fegyverdizájn és támadóanimációk

A fegyvermodellek saját Three.js geometriából készülnek:
- **Plazmapuska:** új sci-fi Photon AR, világító energiamag, réteges páncélzat, részletes cső, optika, lövésre visszarúgás és torkolati fény.
- **Kard:** kristályos, világító penge, fémes él és részletes markolat; többfázisú kardlendítés fénycsík-effekttel.
- **Lándzsa:** díszített markolat, arany energia-gyűrűk és kristályhegy; előreszúró animáció.
- **Ökölharc:** két külön mozgó 3D energiapáncélos kéz váltott ütésekkel.

Az animációkat a játék valóban megtörtént támadásai indítják, a házigazdáról szinkronizált támadásszámlálóval. Nincs szükség új modellfájlokra.

### Közelharci fejlesztések

**Fekete villanás** és **Árnyékidézés** esetén a hullámok utáni normál fejlesztésválasztásból kikerült a **Többszörös lövés** és az **Átütő plazma** (közelharcosként nem hasznosak). Helyettük:

- **Hosszabb ütés és csapás:** +0,75 játékbeli egység a támadási hatótávhoz, legfeljebb négy fejlesztésszinten.
- **Szélesebb támadóív:** több ellenfelet érhetsz el a fegyver lendítésének irányában, legfeljebb öt fejlesztésszinten.

A távolsági karakterek továbbra is kaphatnak Többszörös lövést és Átütő plazmát. Az 5 hullámonkénti boss, a ritka bossjutalmak, az idézéses mana és a multiplayer változatlanul megmaradnak.

## FPS Boss Hunter v1.1 — új funkciók (csak az FPS változatban)

Az eredeti, külső nézetes játék változatlan: https://zsombi12345.github.io/neon-nexus-3d/

Az új **FPS Boss Hunter v1.1** változat: https://zsombi12345.github.io/neon-nexus-3d/fps.html

- **Minden 5. hullám boss**: az 5., 10., 15. stb. hullámokban Titán boss jelenik meg két kísérővel, több HP-val, nagyobb sebzéssel, gyorsabban támadva. A boss figyelmeztetett területi sokkhullámot küld, és erősítést hív.
- **Minden karakternek kissé több élete van**: normál játékosok 115 HP, Fekete villanás harcosok 185 HP; a kristály 125 HP. A normál, futó és páncélos ellenfelek, valamint az idézett farkasok és nyuszik is több HP-val rendelkeznek.
- **Az idézettek a mozgás irányába fordulnak**: a farkasok és nyuszik az általuk követett útvonal szerint fordulnak el, és a multiplayerben is a szerverük szinkronizálja a forgást.
- **Boss-exkluzív jutalmak**: csak legyőzött boss után jelennek meg az aranyszínű, ritka fejlesztések. Minden játékos a saját három ritka opciójából választhat egyet; legalább egy aktiválható képesség mindig szerepel.
- **3 F-gombos boss képesség**: Égi Meteor (területi sebzés), Időfagyasztás (ellenfelek megállítása), Titánpajzs (a csapat és kristály védelme). A használatuk után visszatöltési idő következik.
- **További boss-ereklyék**: Boss dühe (extra sebzés és gyorsaság), Lélekszívás (ütéskor életerőt gyógyít), Árnyéklégió (csak Árnyékidézőnek: több és erősebb idézett).
- **Irányítás**: `F` aktiválja a kiválasztott boss képességet. Ha többet szereztél, `G`-vel válthatsz közöttük. A ritka fejlesztések a jobb oldali HUD-on is látszanak; érintéses gombok is vannak.

A bónuszok és a boss-harcok a szobagazda által számolt, többjátékos állapotban működnek. Az eredeti `index.html` ettől függetlenül megmaradt.

## Két külön játékmód (az eredeti játék megmaradt)

- **Eredeti, külső nézetes NEON NEXUS:** https://zsombi12345.github.io/neon-nexus-3d/
- **ÚJ FPS / belső nézetes NEON NEXUS:** https://zsombi12345.github.io/neon-nexus-3d/fps.html

Az FPS mód külön `fps.html` fájlban található, és nem írja felül az eredeti `index.html`-t. Az FPS-ben ugyanaz a kristályvédelem, a hullámok, a főellenségek, a fegyverek, a képességek és a szobakódos multiplayer működik, mint az eredeti változatban. A két nézethez külön multiplayer szobák tartoznak, így külön indíthatók.

**FPS irányítás:**
- **W, A, S, D** — mozgás a kamera irányához képest
- **Egér mozgatása** — körbenézés
- **Bal egérgomb** — plazmalövés vagy a választott közelharci támadás
- **Első kattintás a játéktéren** — az egér rögzítése a belső nézethez
- **Esc** — egérkurzor felszabadítása
- **Q** — különleges képesség, Fekete villanásnál a második Q-val időzítés
- **R** — farkas/nyuszi váltás Árnyékidézésnél
- **T** — kard/lándzsa váltás Árnyékidézésnél

Hullámvégi fejlesztésválasztáskor az egér felszabadul. A következő harcban kattints ismét a pályára a körbenézés folytatásához. Az FPS mód külön célkeresztet, 3D-s fegyvert és radart is tartalmaz. Érintőkijelzőn a pályán húzással lehet körbenézni.

**Játék:** https://zsombi12345.github.io/neon-nexus-3d/

3D, legfeljebb 6 fős kooperatív kristályvédős böngészős játék. Minden hullám után 3 fejlesztés közül lehet választani. **Minden 10. hullámon boss** jelenik meg.

## Karakterek — az eredeti, feltöltött 3D modellekkel

A belépés előtt választható 3 karakter:
- **Marin Kitagawa**, *My Dress-Up Darling* — `models/marin.glb`
- **Makima**, *Chainsaw Man* — `models/makima.glb`
- **Po**, *Kung Fu Panda* — `models/po.glb`

A játékkód már tudja betölteni mindhárom GLB-t, és a választás a többi játékosnak is látható. **A modellfájlokat külön fel kell tölteni a GitHubra**: töltsd le a ChatGPT mellékelt ZIP-csomagját, csomagold ki, majd a `models` mappába töltsd fel a három `.glb`-t az **Add file → Upload files** segítségével. Amíg hiányoznak, a játék átmeneti rajzfilmszerű karaktereket mutat. Az állapotról a belépési menü tájékoztat.

## Combat Edition v3.4 – fő változások

- **Mana**: amíg akár egy farkas vagy nyuszi él, a mana egyáltalán nem töltődik. Az utolsó idézett halála után indul a visszatöltés, amely a hiányzó mana teljes pótlásához **120 másodpercig** tart. Újabb idézés leállítja és később újrakezdi a folyamatot.
- **Fekete villanás**: **170 alapéleterő**, közeli ökölharc bal kattintásra. Jó Q-időzítés: 15 sebzés, elrontott: 3 sebzés, mindkettő közelharci.
- **Fordított energia**: legfeljebb **9,5 játékbeli egységre** gyógyítja a játékosokat és a közelében lévő kristályt.
- **Árnyékidézés**: az idézettek továbbra is önállóan harcolnak, az idéző bal kattintásra karddal vagy lándzsával támad. **T-vel lehet fegyvert váltani**, a lándzsa messzebb ér el, a kard nagyobbat sebez.
- **Skinek**: Po jelenlegi tartalék modellje változatlan. Makima tartalék modellje sötét nadrágot, fehér inget, piros nyakkendőt, rézszínű fonott hajat és különleges szemeket kapott.

**Fontos az eredeti skinekhez:** a GitHubon jelenleg még nincs fent a három bináris modellfájl. A modellcsomagból a main ág models/ mappájába töltsd fel pontosan marin.glb, makima.glb és po.glb néven. A models/README.md fájlban részletes útmutató és licencinformációk találhatók.

## Képességek

- **Lila energiatörés** — egyenes, átütő energiacsapás.
- **Végtelen mező** — a közeli ellenfeleket ellöki és erősen lassítja; a hatás alatt **folyamatosan sebez**.
- **Árnyékidézés** — harcoló társakat idéz. `R`-rel válthatsz **farkas** (4 mana) és **nyuszi** (2 mana) között, `Q`-val idézel. Az idézettek addig harcolnak, amíg van életerejük. A farkas erősebb és több HP-val rendelkezik; a nyuszi olcsóbb és gyorsabb. A mana csak akkor regenerálódik, ha az összes idézett meghalt; a hiányzó mana teljes feltöltése 120 másodperc. Az alap idézési limit 2.
- **Fekete villanás** — amikor feltöltött, `Q`-ra megjelenik egy fel-le mozgó időzítősáv. Újra `Q` a kis zöld sávon: **piros-fekete, közelharci 15 sebzés**. Mellényomás: **kék-fekete, közelharci 3 sebzés**, azaz ötször gyengébb.
- **Fordított energia** — gyógyítja a csapatot és a kristályt.

Ha Árnyékidézést választasz, hullámok végén kaphatsz speciális fejlesztéseket: **Falka vezető** (+1 idézési hely), **Mana forrás** (+4 maximális mana és gyorsabb regeneráció), **Falka erő** (+HP és sebzés az idézetteknek).

Az összes képesség és az idézettek állapota multiplayerben a házigazda felől szinkronizálódik. Az extra lövések az egér céljához szorosabban igazodnak.

## Irányítás

- **WASD** — mozgás
- **Egér + bal kattintás** — célzás és plazmalövés
- **Q** — képesség; Fekete villanásnál első és második nyomás az időzítéshez
- **R** — farkas és nyuszi közti váltás (Árnyékidézés esetén)
- **T** — kard és lándzsa közti váltás (Árnyékidézés esetén)
- Érintőképernyőn külön gombok: lövés, képesség, idézettváltás

## Többjátékos mód

Hozz létre egy szobát a menüben, oszd meg a 6 karakteres kódot vagy a meghívólinket, majd a többiek csatlakozhatnak. Maximum 6 játékos. Az egyes fejlesztéseket minden játékos maga választhatja. A házigazdának játékban kell maradnia.

## Technika

Statikus GitHub Pages weboldal, Three.js, GLTFLoader, PeerJS és WebRTC. A játékhoz internet kell; a kapcsolat nem minden tűzfal mögött garantált. Az előrehaladás nem mentődik a böngésző bezárása után. A skin és képesség választását a böngésző helyileg megőrzi.

## Modellkészítők és licencek

A három feltöltött Sketchfab modell az eredeti alkotóké, és csak a megfelelő felhasználási feltételekkel használható:

- **Marin**: Lappy — [eredeti](https://sketchfab.com/3d-models/marin-kitagawa-from-dress-up-darling-ef75d04c0a42413692a5b59f938428b7), **CC BY 4.0**
- **Makima**: xinren — [eredeti](https://sketchfab.com/3d-models/chainsawman-makima-a0fdfa91fee143898a80958362ba052c), **CC BY-NC 4.0 – csak nem kereskedelmi felhasználásra**. Monetizáláshoz külön engedély kell.
- **Po**: Kaveesha — [eredeti](https://sketchfab.com/3d-models/kung-fu-panda-po-rigged-af8808931d50415db22d2cfda4e7c69c), **CC BY 4.0**

Részletes licencinformációk a `models/README.md` fájlban. Ez rajongói prototípus, nem hivatalos anime-/filmjáték.
