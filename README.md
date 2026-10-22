# NEON NEXUS 3D — Heroes Edition v3.3.0

**Játék:** https://zsombi12345.github.io/neon-nexus-3d/

3D, legfeljebb 6 fős kooperatív kristályvédős böngészős játék. Minden hullám után 3 fejlesztés közül lehet választani. **Minden 10. hullámon boss** jelenik meg.

## Karakterek — az eredeti, feltöltött 3D modellekkel

A belépés előtt választható 3 karakter:
- **Marin Kitagawa**, *My Dress-Up Darling* — `models/marin.glb`
- **Makima**, *Chainsaw Man* — `models/makima.glb`
- **Po**, *Kung Fu Panda* — `models/po.glb`

A játékkód már tudja betölteni mindhárom GLB-t, és a választás a többi játékosnak is látható. **A modellfájlokat külön fel kell tölteni a GitHubra**: töltsd le a ChatGPT mellékelt ZIP-csomagját, csomagold ki, majd a `models` mappába töltsd fel a három `.glb`-t az **Add file → Upload files** segítségével. Amíg hiányoznak, a játék átmeneti rajzfilmszerű karaktereket mutat. Az állapotról a belépési menü tájékoztat.

## Képességek

- **Lila energiatörés** — egyenes, átütő energiacsapás.
- **Végtelen mező** — a közeli ellenfeleket ellöki és erősen lassítja; a hatás alatt **folyamatosan sebez**.
- **Árnyékidézés** — harcoló társakat idéz. `R`-rel válthatsz **farkas** (4 mana) és **nyuszi** (2 mana) között, `Q`-val idézel. Az idézettek addig harcolnak, amíg van életerejük. A farkas erősebb és több HP-val rendelkezik; a nyuszi olcsóbb és gyorsabb. Mana regenerálódik, alap idézési limit 2.
- **Fekete villanás** — amikor feltöltött, `Q`-ra megjelenik egy fel-le mozgó időzítősáv. Újra `Q` a kis zöld sávon: **piros-fekete, 15 sebzés**. Mellényomás: **kék-fekete, 3 sebzés**, azaz ötször gyengébb.
- **Fordított energia** — gyógyítja a csapatot és a kristályt.

Ha Árnyékidézést választasz, hullámok végén kaphatsz speciális fejlesztéseket: **Falka vezető** (+1 idézési hely), **Mana forrás** (+4 maximális mana és gyorsabb regeneráció), **Falka erő** (+HP és sebzés az idézetteknek).

Az összes képesség és az idézettek állapota multiplayerben a házigazda felől szinkronizálódik. Az extra lövések az egér céljához szorosabban igazodnak.

## Irányítás

- **WASD** — mozgás
- **Egér + bal kattintás** — célzás és plazmalövés
- **Q** — képesség; Fekete villanásnál első és második nyomás az időzítéshez
- **R** — farkas és nyuszi közti váltás (Árnyékidézés esetén)
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
