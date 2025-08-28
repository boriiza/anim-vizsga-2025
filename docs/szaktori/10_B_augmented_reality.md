# 10_B_augmented_reality

## Eredeti tételezés

**A városi önkormányzat megbízza egy telefonos alkalmazás elkészítésével, aminek segítségével a történelmi belváros nevezetesebb épületei különböző történelmi koroknak megfelelő állapotban jeleníthetők meg a helyszínen sétáló turisták számára. Ismertesse a kiterjesztett valóság (Augmented Reality) jellemzőit, további lehetséges felhasználási módjait!**

## Tanulási vázlatpontok

### 1. Interaktív és generatív képalkotási technikák ismerete

#### Interaktív képalkotás
- **Felhasználói befolyásolás**: közvetlen interakció
- **Valós időben**: azonnali válasz
- **Dinamikus tartalom**: változó képek
- **Kétirányú kommunikáció**: adatcsere
- **Személyre szabás**: egyéni beállítások

#### Generatív képalkotás
- **Algoritmusok**: szabályok alapján
- **Paraméterek**: változó bemenetek
- **Automatikus generálás**: gépi létrehozás
- **Változatosság**: egyedi eredmények
- **Skálázhatóság**: nagy mennyiségek

#### Kevert technikák
- **Interaktív + generatív**: kombinált megoldások
- **Adaptív tartalom**: környezethez igazodás
- **Intelligens rendszerek**: AI-alapú döntések
- **Tanuló algoritmusok**: folyamatos fejlesztés
- **Kontextuális tartalom**: helyzetfüggő információk

### 2. Augmented Reality mobil-alkalmazás műszaki feltételei

#### Kamerák és szenzorok
- **Kamera felbontása**: minőség és sebesség
- **GPS**: földrajzi hely meghatározása
- **Gyorsulásmérő**: mozgás észlelése
- **Magnetométer**: irány meghatározása
- **Barométer**: magasság mérése

#### Hardver követelmények
- **Processzor**: számítási teljesítmény
- **Memória**: RAM és tárhely
- **Grafikus kártya**: képi feldolgozás
- **Kijelző**: felbontás és színek
- **Akkumulátor**: energiaellátás

#### Szoftver követelmények
- **Operációs rendszer**: iOS vagy Android
- **AR keretrendszer**: ARKit, ARCore
- **3D motor**: Unity, Unreal Engine
- **Adatbázis**: helyi és távoli adatok
- **Hálózat**: internet kapcsolat

### 3. 3D modellek optimalizálása

#### Low-poly modellezés
- **Alacsony poligon szám**: gyors renderelés
- **Geometriai egyszerűsítés**: formák egyszerűsítése
- **LOD rendszer**: távolság alapú részletesség
- **Textúra optimalizálás**: képek tömörítése
- **Tömörített formátumok**: glTF, FBX

#### Pontok, élek és lapok (Vertex, Edge, Face)
- **Vertex**: térbeli pontok
- **Edge**: pontok közötti vonalak
- **Face**: felületek
- **Geometriai háló (Mesh)**: összefüggő felület
- **Topológia**: háló struktúrája

#### Renderelési optimalizálás
- **Frustum culling**: láthatatlan elemek kizárása
- **Occlusion culling**: takart elemek kizárása
- **Instancing**: azonos objektumok csoportosítása
- **Level of Detail**: részletesség szintek
- **Texture atlasing**: textúrák egyesítése

### 4. Augmented Reality alapelvei és működése

#### AR definíció és jellemzők
- **Kiterjesztett valóság**: valós és virtuális keverése
- **Valós időben**: azonnali megjelenés
- **Interaktív**: felhasználói befolyásolás
- **3D regisztráció**: térbeli illesztés
- **Kontextuális**: környezethez igazodás

#### AR vs. VR vs. MR
- **AR (Augmented Reality)**: valóság kiegészítése
- **VR (Virtual Reality)**: teljes virtuális környezet
- **MR (Mixed Reality)**: valós és virtuális keverése
- **Háromdimenziós tér**: térbeli kapcsolatok
- **Immersion**: bemerülés a tartalomba

#### AR technológiák
- **Marker-based AR**: jelölő alapú
- **Markerless AR**: jelölő nélküli
- **Projection-based AR**: vetítés alapú
- **Superimposition-based AR**: felülrajzolás
- **Location-based AR**: hely alapú

### 5. Történelmi épületek AR alkalmazása

#### Történelmi rekonstrukció
- **Különböző korszakok**: időbeli változások
- **Építészeti stílusok**: stílusjegyek
- **Kulturális kontextus**: történelmi háttér
- **Vizuális összehasonlítás**: múlt vs. jelen
- **Interaktív tanulás**: oktatási célok

#### Turisztikai alkalmazások
- **Vezetett túrák**: interaktív séta
- **Információs rétegek**: részletes információk
- **Nyelvi támogatás**: több nyelv
- **Akadálymentesítés**: mindenki számára
- **Személyre szabás**: egyéni preferenciák

#### Műszaki megvalósítás
- **GPS alapú pozicionálás**: pontos helymeghatározás
- **Kamera alapú felismerés**: épületek azonosítása
- **3D térképek**: digitális térképek
- **Valós időben**: azonnali frissítés
- **Offline működés**: internet nélkül is

### 6. További lehetséges felhasználási módok

#### Oktatás és kutatás
- **Múzeumi alkalmazások**: interaktív kiállítások
- **Történelmi oktatás**: élő történelem
- **Archeológiai rekonstrukció**: eltűnt épületek
- **Kulturális örökség**: megőrzés és bemutatás
- **Tudományos vizualizáció**: komplex adatok

#### Kereskedelmi alkalmazások
- **Ingatlan**: virtuális lakásnézés
- **Belsőépítészet**: tervezési segítség
- **Kiskereskedelem**: termékek bemutatása
- **Reklám**: interaktív hirdetések
- **Szolgáltatások**: virtuális próbák

#### Ipari alkalmazások
- **Karbantartás**: javítási útmutatók
- **Oktatás**: szakmai képzés
- **Távoli támogatás**: szakértői segítség
- **Minőségellenőrzés**: termék vizsgálat
- **Logisztika**: raktárkezelés

#### Egészségügy és rehabilitáció
- **Orvosi vizualizáció**: anatómiai modellek
- **Fizioterápia**: gyakorlatok bemutatása
- **Pszichológia**: fóbia kezelés
- **Rehabilitáció**: mozgás visszatanítása
- **Oktatás**: orvosi képzés

### 7. Műszaki kihívások és megoldások

#### Teljesítmény optimalizálás
- **Battery life**: energiahatékonyság
- **Processing power**: számítási teljesítmény
- **Memory usage**: memóriahasználat
- **Network bandwidth**: hálózati sávszélesség
- **Storage**: tárhelyigények

#### Pontosság és megbízhatóság
- **GPS pontosság**: helymeghatározás
- **Tracking stability**: követés stabilitása
- **3D alignment**: térbeli illesztés
- **Latency**: késleltetés
- **Error handling**: hibakezelés

#### Felhasználói élmény
- **Intuitive interface**: intuitív felület
- **Accessibility**: akadálymentesítés
- **Performance**: teljesítmény
- **Battery optimization**: energiaoptimalizálás
- **Offline functionality**: offline működés

### 8. Jövőbeli trendek és fejlesztések

#### Technológiai fejlesztések
- **5G hálózatok**: gyorsabb adatátvitel
- **Edge computing**: helyi feldolgozás
- **AI integráció**: mesterséges intelligencia
- **Wearable devices**: hordozható eszközök
- **Holographic displays**: holografikus kijelzők

#### Új alkalmazási területek
- **Social AR**: közösségi alkalmazások
- **Gaming**: játékok és szórakozás
- **Communication**: kommunikációs eszközök
- **Productivity**: termelékenység növelése
- **Entertainment**: szórakozás

#### Integráció más technológiákkal
- **IoT**: internetes kapcsolat
- **Blockchain**: biztonságos adatkezelés
- **Cloud computing**: felhő alapú szolgáltatások
- **Machine learning**: gépi tanulás
- **Computer vision**: számítógépes látás

## Kulcsszavak és fogalmak
- **Augmented Reality (AR)**: kiterjesztett valóság
- **Virtual Reality (VR)**: virtuális valóság
- **Mixed Reality (MR)**: kevert valóság
- **GPS**: földrajzi hely meghatározása
- **Gyorsulásmérő**: mozgás észlelése
- **Magnetométer**: irány meghatározása
- **Low-poly**: alacsony poligon számú modellek
- **Vertex, Edge, Face**: geometriai elemek
- **Geometriai háló (Mesh)**: összefüggő felület
- **Topológia**: háló struktúrája
- **ARKit**: Apple AR keretrendszer
- **ARCore**: Google AR keretrendszer
- **Unity**: 3D játék motor
- **Unreal Engine**: 3D motor
- **glTF**: 3D formátum
- **FBX**: 3D formátum
- **Frustum culling**: láthatatlan elemek kizárása
- **Occlusion culling**: takart elemek kizárása
- **Instancing**: azonos objektumok csoportosítása
- **Level of Detail**: részletesség szintek
- **Texture atlasing**: textúrák egyesítése
- **Marker-based AR**: jelölő alapú AR
- **Markerless AR**: jelölő nélküli AR
- **Location-based AR**: hely alapú AR
- **GPS alapú pozicionálás**: pontos helymeghatározás
- **Kamera alapú felismerés**: épületek azonosítása
- **3D térképek**: digitális térképek
- **Valós időben**: azonnali frissítés
- **Offline működés**: internet nélkül is
- **Battery life**: energiahatékonyság
- **Processing power**: számítási teljesítmény
- **Memory usage**: memóriahasználat
- **Network bandwidth**: hálózati sávszélesség
- **Storage**: tárhelyigények
- **GPS pontosság**: helymeghatározás
- **Tracking stability**: követés stabilitása
- **3D alignment**: térbeli illesztés
- **Latency**: késleltetés
- **Error handling**: hibakezelés
- **Intuitive interface**: intuitív felület
- **Accessibility**: akadálymentesítés
- **Performance**: teljesítmény
- **Battery optimization**: energiaoptimalizálás
- **Offline functionality**: offline működés
- **5G hálózatok**: gyorsabb adatátvitel
- **Edge computing**: helyi feldolgozás
- **AI integráció**: mesterséges intelligencia
- **Wearable devices**: hordozható eszközök
- **Holographic displays**: holografikus kijelzők
- **Social AR**: közösségi alkalmazások
- **IoT**: internetes kapcsolat
- **Blockchain**: biztonságos adatkezelés
- **Cloud computing**: felhő alapú szolgáltatások
- **Machine learning**: gépi tanulás
- **Computer vision**: számítógépes látás
