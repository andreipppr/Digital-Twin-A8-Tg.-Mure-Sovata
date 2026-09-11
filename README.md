  Aici îmi voi documenta parcursul proiectului meu, care constă în realizarea autostrăzii A8 din România, secțiunea I (Tg. Mureș - Miercurea Nirajului) și Lot 1b (Miercurea Nirajului - Sarateni) în jocul Cities Skylines, la scară redusă, pe o suprafață de joc de 9x9 parcele echivalentul a 69,120 km*2 suprafața terestră. 

Proiectul e impartit pe mai multe etape, structurate logic pentru o munca mai eficienta : 
- Pregătirea mediului de lucru: Instalarea modurilor necesare pentru o simulare mai avansată (81 Tiles 2, Network Anarchy, TM:PE, Harmony).  
- Generarea reliefului: Documentarea, extragerea și generarea heightmap-ului corespunzător suprafeței terestre reale
- Modelarea mediului înconjurător: Importarea heightmap-ului în joc și detalierea hărții cu elemente specifice reliefului local (rețea hidrografică, resurse naturale, floră). 
- Construcția infrastructurii rutiere: Replicarea realistă a traseului autostrăzii A8. Pentru o acuratețe ridicată, traseul este preluat din date reale (openstreetmap.org), iar detaliile tehnice sunt integrate folosind documentația de pe site-ul Asociației Pro Infrastructură.    
- Dezvoltarea rețelei urbane : Construirea localităților adiacente (Târgu Mureș, Miercurea Nirajului, Sovata, Sărățeni, Acățari) și conectarea acestora la nodurile rutiere aferente autostrăzii A8  (Nodurile rutiere DN15J, DN13, DJ151D, DN13A)
- Exportul pentru simulare de trafic: Extragerea elementelor din lotul de autostradă (noduri rutiere, viaducte, pasaje) și importarea lor într-un simulator de trafic dedicat (PreScan).  
- Exportul și prelucrarea datelor GIS: Extragerea parametrilor autostrăzii (pante, profile rutiere etc.) sub formă de date GIS, în vederea analizării acestora în softuri de specialitate precum ArcGIS sau QGIS. 
- Exportul pentru analiză structurală: Transformarea datelor din noduri rutiere, viaducte și pasaje în modele 3D, cu scopul de a simula și evalua analiza structurală a acestora. 

Scop : Proiectul are ca scop transpunerea fidelă a documentației tehnice a autostrăzii A8 într-un mediu virtual 3D. Prin acest demers, se urmărește nu doar vizualizarea realistă a impactului infrastructurii asupra reliefului și localităților (Târgu Mureș - Sărățeni), ci și generarea de date spațiale și structurale exportabile pentru analize complexe de trafic (PreScan) și geospațiale (QGIS/ArcGIS).

Progres la zi  : 
6.09.2026 -> 8.09.2026 :
Am replicat în totalitate traseul segmentului autostrazii A8 în Cities Skylines conform Hărții proiectelor de infrastructura, unde am realizat următoarele, conform proiectului tehnic : 
- Nodurile rutiere Legătura A3-A8 (DN15J), Acățari (DN13), Miercurea Nirajului (DJ151D), Sărățeni (DN13A) ; 
- zonă de odihna din proximitatea localității Miercurea Nirajului; 
- zonă de odihnă - după tunelul 2 din lot 1B , Miercurea Nirajului - Sărățeni ;   

Din cauza constrângerii a reliefului din joc, am fost nevoit să fac peisagistică pentru a realiza nodul rutier de la Sărățeni și Miercurea Nirajului.

Am construit , aproximativ realist, localitățile adiacente segmentului de autostradă, mai precis : Miercurea Nirajului, Sărățel, Acățari, Sovata, Gălățeni

9.09.2026 : 
Am analizat harta orașului Târgu Mureș și am finalizat construcția acestuia, care a constat în : 
- replicarea celor mai circulate și populare străzi din Târgu Mureș ;
- atribuirea de spații rezidențiale, comerciale , parcuri, școli, primăria orașului etc. ;
- construirea la scară mai mică a cartierelor Libertății, Dâmbul Pietros, Tudor Vladimirescu, Centru, 22 Decembrie, Podeni.

10.09.2026 : Finalizarea Aeroportului Transilvania din zona Ungheni și conectarea acestuia  la nodul rutier al A3. Prima parte realizată cu succes

Structuri omise : poduri cu lungimi sub 400 m în zone terestre restrânse, deoarece nu era posibilă construcția lor ; relocări de drumuri comunale și județene ; 


Observații : Scopul principal al proiectului este de a reproduce, la o scară realistă, traseul autostrăzii și de a prelucra mai apoi datele în diferite simulatoare, NU de a creea la același nivel și localitățile adiacente. Scopul construcției localităților este de a simula traficul și dezvoltarea zonei Târgu Mureș.
