# 13_B_3d_animacio_technika

## Feladatleírás

**Egy számítógépes játékhoz készít 3D karaktermodelleket. A játék tervezett gépigénye alacsony, ezért alacsony geometriai felbontású poligonmodellekre van szükség. Ismertesse ezt a modellezési technikát, hasonlítsa össze más lehetőségekkel!**

- 3D modellezési technikák általános ismerete
- Poligon alapú modellezési technika ismerete
- Pontok, élek és lapok (Vertex, Edge, Face), geometriai háló 

## Tanulási vázlatpontok

### 1. 3D modellezési technikák általános ismerete

#### Alapvető modellezési megközelítések
- **Poligon alapú modellezés**: háromszögek és négyszögek összekapcsolása
- **NURBS modellezés**: matematikai görbék és felületek
- **Subdivision surface**: poligon háló finomítása és simítása
- **Procedurális modellezés**: algoritmusok alapján történő generálás
- **Sculpting**: digitális agyagmintázás, szabad formák

#### Modellezési technikák jellemzői
- **Pontosság**: matematikai pontosság vs. vizuális minőség
- **Szerkeszthetőség**: módosítási lehetőségek és rugalmasság
- **Teljesítmény**: renderelési sebesség és memóriahasználat
- **Alkalmazási terület**: játékok, filmek, építészet, ipari tervezés

### 2. Poligon alapú modellezési technika ismerete

#### Alapvető geometriai elemek
- **Vertex (pontok)**: térbeli koordináták, geometria alapjai
- **Edge (élek)**: pontok közötti vonalak, háló struktúrája
- **Face (lapok)**: élek által határolt felületek, megjelenítés alapja
- **Geometriai háló (mesh)**: összefüggő felület, teljes modell

#### Poligon háló típusai
- **Háromszöges háló (triangle mesh)**: minden lap háromszög, stabil geometria
- **Négyszöges háló (quad mesh)**: négyzetes lapok, könnyebb szerkesztés
- **Topológia**: háló struktúrája, pontok és élek kapcsolatai
- **Edge loop**: folyamatos élvonalak, modellezési kontroll

#### Modellezési eszközök és technikák
- **Manipulators**: modellezési eszközök, transzformációk
- **Primitives**: alapformák (kocka, gömb, henger, kúp)
- **Curve and deform**: görbék és deformációs eszközök
- **Topológiai megoldások**: háló struktúra optimalizálása

### 3. Low poly modellezés játékokhoz

#### Low poly technika jellemzői
- **Alacsony poligon szám**: kevés geometriai elem, gyors renderelés
- **Egyszerűsített formák**: alapvető geometriai alakok
- **Optimalizált topológia**: hatékony háló struktúra
- **Játékbarát formátum**: real-time rendereléshez optimalizált

#### Low poly modellezési folyamat
- **Alapformák**: primitívek használata kezdésként
- **Alakformálás**: vertex manipuláció, edge extrusion
- **Topológia optimalizálás**: felesleges pontok és élek eltávolítása
- **Normal vektorok**: felület irányok beállítása
- **UVW map**: textúra koordináták létrehozása

#### Játékokhoz optimalizált megoldások
- **LOD rendszer**: távolság alapú részletesség
- **Instancing**: azonos modellek többszörös használata
- **Culling**: láthatatlan elemek kizárása
- **Batching**: hasonló modellek csoportosítása

### 4. Más modellezési technikák összehasonlítása

#### NURBS vs. Poligon modellezés
- **NURBS**: 
  - Pontosság: matematikai pontosság, sima felületek
  - Teljesítmény: lassabb renderelés, nagyobb memóriahasználat
  - Alkalmazás: ipari tervezés, autóipar, precíziós modellezés
- **Poligon**: 
  - Pontosság: közelítő, de vizuálisan megfelelő
  - Teljesítmény: gyors renderelés, hatékony memóriahasználat
  - Alkalmazás: játékok, filmek, vizuális effektek

#### Subdivision surface vs. Low poly
- **Subdivision surface**: 
  - Minőség: sima, részletes felületek
  - Teljesítmény: magas poligon szám, lassabb renderelés
  - Alkalmazás: filmek, magas minőségű vizualizációk
- **Low poly**: 
  - Minőség: egyszerű, stilizált megjelenés
  - Teljesítmény: alacsony poligon szám, gyors renderelés
  - Alkalmazás: játékok, real-time alkalmazások

#### Sculpting vs. Poligon modellezés
- **Sculpting**: 
  - Munkamódszer: szabad formák, intuitív modellezés
  - Pontosság: részletes, organikus formák
  - Teljesítmény: magas poligon szám, utómunka szükséges
- **Poligon**: 
  - Munkamódszer: szerkezeti, kontrollált modellezés
  - Pontosság: geometriai pontosság, mérnöki megközelítés
  - Teljesítmény: optimalizálható, játékbarát

### 5. Szánútógépes játékok specifikus igényei

#### Teljesítmény követelmények
- **Real-time renderelés**: 60 FPS minimum, akadásmentes játékélmény
- **Alacsony gépigény**: régebbi hardvereken is futó játékok
- **Mobil kompatibilitás**: különböző eszközökön működő alkalmazások
- **Hálózati optimalizálás**: online játékok, multiplayer támogatás

#### Low poly modellezés előnyei játékokhoz
- **Gyors renderelés**: kevés poligon, gyors képkocka generálás
- **Kis memóriahasználat**: optimalizált adatstruktúra
- **Egyszerű animáció**: kevés csont, gyors számítások
- **Stilizált megjelenés**: játékosok által kedvelt vizuális stílus
- **Könnyű optimalizálás**: LOD rendszer, instancing

#### Textúrázás és anyagok
- **UVW map**: textúra koordináták optimalizálása
- **Textúra méretezés**: kis méretű textúrák, gyors betöltés
- **Normal mapping**: részletek szimulálása alacsony poligon számmal
- **Material shader**: egyszerű anyagok, gyors renderelés
