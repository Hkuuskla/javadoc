*JavaFX*
========

*JavaFX* on graafika- ning meediapakettide teek (*library*), mis võimaldab arendajatel luua erinevaid desktop-rakendusi või
*rich internet application*'e (RIA) ehk installeeritavaid internetirakendusi, milleks võivad olla näiteks brauseri pluginad.
*JavaFX* on Java API, mis tähendab, et *JavaFX* rakenduse koodis võib kasutada ka teisi API'sid ükskõik millistest Java teekidest.

*JavaFX*'i kasutamiseks on mitmeid erinevaid võimalusi, näiteks saab rakenduse kujunduse loomiseks kasutada CSS faile;
samuti on võimalik eraldi luua rakenduse *backend*, kasutades Java koodi, ning *frontend*, kasutades spetsiaalset FXML skriptimiskeelt.
*JavaFX* kasutajaliideseid saab luua ka koodi kirjutamata. Selle jaoks on loodud eraldi rakendus *SceneBuilder*, 
mis aitab lihtsalt luua kujundust ja rakenduse visuaalset ülesehitust
ning aitab kergelt siduda Javas kirjutatud rakenduse loogika (meetodid)
ja kujunduselemendid (erinavad *JavaFX* objektid). *SceneBuilder* loob ise FXML faili sisu,
rakenduse loojal tuleb ainult vajalikud elemendid ekraanil õigesse kohta panna.

Kust saada *JavaFX*?
--------------------

*JavaFX* API on *Java Runtime Environment*'i (JRE) ning *Java Development Kit*'i (JDK) osaks,
seega pole seda tarvis eraldi alla tõmmata.

Kust saada *SceneBuilder*?
--------------------------

Nagu eelnevalt mainitud, pole *SceneBuilder*'it otseselt tarvis, et luua *JavaFX* rakendusi,
kuid alustuseks on seda märksa mugavam (ning võib-olla ka lõbusam) kasutada.
IntelliJ pakub ka võimalust, mis laseb *SceneBuilder*'it kasutada otse koodikirjutamiseks mõeldud aknaga analoogses aknas. 

*SceneBuilder*'i saab alla laadida järgnevalt lingilt:
http://gluonhq.com/products/scene-builder/

.. image:: images/JavaFXSceneBuilder.png

Kuidas luua *JavaFX* projekti?
------------------------------

IntelliJ's saab *JavaFX* rakenduse luua järgmiselt:

- Vali *File* -> *new Project*
- Avanenud akna vasakus ääres olevast nimekirjast vali *Java FX* ning seejärel vajuta *next*
- Vali asukoht projektile ning anna sellele nimi
- IntelliJ loob automaatselt FXML faili nimega *sample.fxml*
- Seda faili saab avada *SceneBuilder*'is, selleks tee paremklikk faili nimel ning vali menüüst *Open in SceneBuilder*

Abiks on ka:
http://docs.oracle.com/javafx/scenebuilder/1/use_java_ides/sb-with-intellij.htm

Eclipse'is projekti loomise juures on abiks:
http://docs.oracle.com/javafx/scenebuilder/1/use_java_ides/sb-with-eclipse.htm


Viiteid:

https://dzone.com/refcardz/javafx-8-1


