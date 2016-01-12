#Codi font

##Codi objecte i codi executable

Per crear un programa el que es farà serà crear un arxiu i escriure a un fitxer el
seguit d’instruccions que es vol que l’ordinador executi. *Aquestes instruccions
hauran de seguir unes pautes determinades* en funció del llenguatge de programa-
ció escollit. 

Un cop s’ha acabat d’escriure el programa, **el conjunt de
fitxers de text resultants**, on es troben les instruccions, es diu que contenen el
**codi font**.
Aquest codi font pot ser des d’un nivell molt alt, molt a prop del llenguatge
humà,fins a un de nivell més baix, més proper al codi de les màquines, com
ara el codi assemblador.

El procés anomenat **compilació** es la traducció del codi font dels fitxers del programa en fitxers en format binari que contenen les instruccions
en un format que el processador pot entendre. 

**El codi objecte** és el codi font traduït (pel compilador) a codi màquina, però
aquest codi encara no pot ser executat per l’ordinador.

**El codi executable** és la traducció completa a codi màquina, duta a terme per
l’enllaçador (en anglès,linker). El codi executable és interpretat directament
per l’ordinador.

**L’enllaçadorés** l’encarregat d’inserir al codi objecte les funcions de les llibreries
que són necessàries per al programa i de dur a terme el procés de muntatge
generant un arxiu executable.

**Una llibreria** és una col·lecció de codi predefinit que facilita la tasca del programador a l'hora de 
codificar un programa.

##Maquina virtual

El concepte de **màquina virtual* sorgeix amb l’objectiu de facilitar el desenvolupa-
ment de compiladors que generen codi per a diferents processadors.

La compilació consta de dues fases:

• La primera *parteix del codi font a un llenguatge intermedi* obtenint un
programa equivalent amb un menor nivell d’abstracció que l’original i que
no pot ser directament executat.

• La segona fase *tradueix el llenguatge intermedi* a un llenguatge comprensi-
ble per la màquina


###La maquina virtual Java

La màquina virtual Java (JVM) és l’entorn en què s’executen els programes Java.
És un **programa natiu**, és a dir, executable en una plataforma específica, 
que éscapaç d’interpretar i executar instruccions expressades en un codi de bytes o (*el
bytecode de Java*) que és generat pel compilador del llenguatge Java.

*La màquina virtual Java és una peça fonamental de la tecnologia Java*. Se situa
en un nivell superior al maquinari sobre el qual es vol executar l’aplicació i
actua com un pont entre el codi de bytes a executar i el sistema. Així, quan un
programador escriu una aplicació Java, ho fa pensant en la JVM encarregada
d’executar l’aplicació i no hi ha cap motiu per pensar en les característiques
de la plataforma física sobre la qual s’ha d’executar l’aplicació. *La JVM serà
l’encarregada, en executar l’aplicació, de convertir el codi de bytes a codi natiu de
la plataforma física*


