#1.5 Característiques dels llenguatges més difosos

Existeixen molts llenguatges de programació diferents, fins al punt que moltes
tecnologies tenen el seu llenguatge propi. Cada un d’aquests llenguatges té un
seguit de particularitats que el fan diferent de la resta.

**Els llenguatges de programació més difosos** són aquells que més es fan servir
en cadascun dels diferents àmbits de la informàtica. En l’àmbit educatiu, per
exemple, es considera un llenguatge de programació molt difós aquell que es fa
servir a moltes universitats o centres educatius per a la docència de la iniciació a
la programació.

###Característiques de la programació estructurada

La programació estructurada va ser desenvolupada pel neerlandès *Edsger W.
Dijkstra* i es basa en el denominat teorema de l’estructura. Per això utilitza
únicament **tres estructures:**seqüència, selecció i iteració, essent innecessari
l’ús de la instrucció o instruccions de transferència incondicional.

####Claretat

Hi haurà d’haver prou informació al codi per tal que el programa pugui ser
entès i verificat: comentaris, noms de variables comprensibles i procediments
entenedors... Tot programa estructurat pot ser llegit des del principi a la fi sense
interrupcions en la seqüència normal de lectura.

####Teorema de l’estructura

*Demostra que tot programa es pot escriure utilitzant únicament les tres estructures
bàsiques de control:*

    • **Seqüència:** instruccions executades successivament, una darrere l’altra.
    
    • **Selecció:** la instrucció condicional amb doble alternativa, de la forma
    “si condició, llavors SentènciaA, sinó SentènciaB”.
    
    • **Iteració**: el bucle condicional “mentre condició, fes SentènciaA”, que
    executa les instruccions repetidament mentre la condició es compleixi.

####Disseny descendent

El disseny descendent és una tècnica que es basa en el concepte de “divideix i
venceràs” per tal de resoldre un problema en l’àmbit de la programació. Es tracta
de la resolució del problema al llarg de diferents nivells d’abstracció partint d’un
nivell més abstracte i finalitzant en un nivell de detall.

####Programació modular

La realització d’un programa sense seguir una **tècnica de programació modular**
produeix sovint un conjunt enorme de sentències l’execució de les quals és
complexa de seguir, i d’entendre, amb la qual cosa es fa gairebé impossible la
depuració d’errors i la introducció de millores. 

Quan es parla de **programació modular**, ens referim a la divisió d’un programa
en parts més manejables i independents. Una regla pràctica per aconseguir aquest
propòsit és establir que cada segment del programa no excedeixi, en longitud, d’un
pam de codificació.

*En la majoria de llenguatges, els mòduls es tradueixen a:*

    • **Procediments:** són subprogrames que duen a terme una tasca determinada
    i retornen 0 o més d’un valor. S’utilitzen per estructurar un programa i
    millorar la seva claredat.
    
    • **Funcions:** són subprogrames que duen a terme una determinada tasca i
    retornen un únic resultat o valor. S’utilitzen per crear operacions noves que
    no ofereix el llenguatge.

####Tipus abstractes de dades (TAD)

En programació, *el tipus de dades d’una variable* és el conjunt de valors que la
variable pot assumir.Per exemple, una variable de tipus booleà pot adoptar només
dos valors possibles: Cert o Fals

Els llenguatges de programació assumeixen un nombre determinat de tipus de
dades, que pot variar d’un llenguatge a un altre.

Fins fa uns anys, tota la programació es basava en aquest concepte de tipus i no
eren pocs els problemes que apareixien, lligats molt especialment a la complexitat
de les dades que s’havien de definir. Va aparèixer la possibilitat de poder *definir
tipus abstractes de dades*, on el programador pot *definir un nou tipus de dades* i
les seves possibles operacions.



