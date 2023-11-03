# UF4-Moodle
## Práctica de la UF4 
1. Inicia sessió com a administrador del teu Moodle i realitza les següents tasques prèvies d'administració.

a) Canvia la teva direcció de correu electrònic i també la teva contrasenya per una altra. Afegeix-te a més un avatar. Tot això es pot fer anant al teu perfil (opció que apareix sota el teu nom que es veu a la part superior dreta de la finestra del Moodle) i clicant sobre l'enllaç **Editar** (o també anant a l'opció **Preferències**, situada al mateix lloc).

![Foto](Captura%20de%20pantalla%20de%202023-10-31%2013-19-02.png)

b) Canvia el nom del teu lloc (tant llarg com curt) i fes que la pàgina principal no mostri res pels usuaris que no estiguin autentificats. Això es pot fer anant a l'opció **Administració del lloc** > **Primera plana** > **Paràmetres**

![Foto](Captura%20de%20pantalla%20de%202023-10-30%2014-15-21.png)
![Foto](Captura%20de%20pantalla%20de%202023-10-30%2014-16-22.png)

c) Comprova que la franja horària del teu lloc sigui la correcta. Això es pot fer anant a l'opció **Administració del lloc** > **Ubicació** > **Paràmetres**.

![Foto](hora.png)

NOTA: Aquesta configuració és important, per exemple, per les hores límit d'entregues d'exercicis
d) Canvia l'idioma del teu lloc. Això es pot fer anant a l'opció **Administració del lloc** > **Idioma** > **Paràmetres** i tenint en compte tant el checkbox **Detecció automàtica de l'idioma** com el desplegable **Idioma per defecte**.

![Foto](defaul%20lenguaje.png)
![Foto](seleccionar%20idioma.png)

NOTA: Per disposar d'un determinat idioma, primer cal instal.lar-lo des de **Administració del lloc** > **Idioma** > **Paquets d'idioma**
e) Canvia la política de contrasenyes de manera que els usuaris que es creiïn tinguin una contrasenya de com a mínim 4 caràcters incloent-hi, majúscules, minúscules i xifres. Això es pot fer anant a l'opció **Administració del lloc** > **Seguretat** > **Normatives del lloc**.

![Foto](longitud.png)
![Foto](mayusculas.png)

2. Crea els següents cursos: un curs anomenat A (sense categoria) que estigui format per 3 temes i un altre anomenat B (també sense categoria) que estigui format per 5 temes. Tot això ho pots fer des de Administració del lloc->Gestiona cursos i categories o també des del quadre **Navegació** anant a **Cursos** > **Afegeix curs**

![Foto](curso%20a.png)
![Foto](CURSO%20B.png)

3. Vés a algun dels cursos creats al punt anterior (simplement seleccionant-lo dins del quadre **Navegació**) i fes que contingui en algun del seus temes algun tipus de material (un document PDF, per exemple), canvia el títol d'algun tema i, en general, investiga les possibilitats que et dóna el botó **Activar edició** en un curs.

![Foto](josecamu%C3%B1ez.png)

NOTA: Aquestes possibilitats no les estudiarem a fons perquè són una tasca més pròpia del professor que no pas de l'administrador del Moodle, però sempre va bé tenir-ne alguna idea.

4. Creació d’usuaris i alumnes.

a) Crea manualment un usuari anomenat **Bob** que ha de fer servir el **mètode d'autenticació manual**. Això es pot fer des de **Administració del lloc** > **Usuaris** > **Comptes** > **Afegeix un usuari**

![Foto](bob.png)

b) Genera deu alumnes que ho seran dels dos cursos A i B . Fes servir un arxiu CSV per realitzar aquesta creació en bloc. Vés a **Administració del lloc** > **Usuaris** > **Comptes** > **Carrega usuaris** i segueix els passos que et marca.

![Codigo para los usuarios](csv)

![Foto](archivousuarios.png)
![Foto](usuarioscreados.png)

NOTA: Per saber el contingut que hauria de tenir aquest fitxer, consulteu més abaix a la secció **Usuaris**.

c) Elimina dos dels deu alumnes creats a l'apartat anterior fent servir l'opció **Administració del lloc** > **Usuaris** > **Accions amb usuaris en bloc**

![Foto](eliminarusuario1.png)
![Foto](eliminarusuario2.png)

5. Ara matricula aquests usuaris als diferents cursos.

a) Fes que al curs A no hi hagi possibilitat d'inscripció (és a dir, que només es permeti l'accés de visitant de manera que el curs sigui totalment públic sense control d'usuaris -ni alumnes ni professors-). D'altra banda, fes que al curs B es necessiti registre manual d'usuaris (és a dir, que sigui l'administrador -tu- qui matriculi cada usuari al curs, ja sigui com a professor o com a alumne). Tot això ho pots fer des de **Administració del curs** > **Ususaris** > **Mètodes d'inscripció**. Si no surt algun mètode d'inscripció disponible, has d'activar-lo a: **Administració de lloc** > **Connectors** > **Autenticació** > **Gestió de l'autenticació**

![Foto](metododeinscripcion.png)
![Foto](metododeinscripcionB.png)

b) Assigna com a professor del curs B l'usuari "Bob" i com a alumnes a tots els que fas afegir des de l'arxiu CSV Tot això ho pots fer anant a **Administració del curs** > **Usuaris inscrits** > **Inscriure**.

![Foto](bobprofe.png)

c) Comprova que efectivament, el contingut del curs A (afegit per l'administrador del sistema -és a dir, tu- estigui disponible públicament i que per accedir al curs B s'hagi d'iniciar sessió amb un usuari registrat (alumne o professor)

6. Canvia l'aparença estètica del teu lloc. Concretament, descarrega't i activa un tema diferent dels que venen per defecte i prova de canviar també la capçalera i el peu de pàgina del lloc. Això ho pots fer primer anant a Administració del lloc > Connectors > Instal·lar complement i després a Administració del lloc > Aparença > Temes > Selector de temes Sempre pots fer servir l'enllaç Canvi de rol del menú de la dreta per observar com es veuria el lloc sent alumne, professor, etc.

![Foto]()

