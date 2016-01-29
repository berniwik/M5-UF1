Codi font, codi objecte i codi executable: maquines virtuals
Per a crear un programa el que es farà serà crear un arxiu i escriure un seguit de ordes que 
vols que l’ordinador executi, aquestes instruccions han de seguir unes pautes 
determinades, segons el llenguatge de programació varien, per a començar amb un editor 
de text pot servir per fer el nostre codi font, que es el conjunt de fitxer on estan guardades 
les nostres instruccions, aquest codi pot ser de diferents nivells o molt alt i que sigui 
interpretable per una persona o que sigui de baix nivell que es mes proper a les maquines. 
Normalment s’utilitza el llenguatge de alt nivell però la maquina no l’entén i per tant ha de 
passar per un procés de traducció  a codi maquina això s’anomena complicació, el 
contingut de aquest codi compilat s’anomena codi objecte i per últim fa falta una altre 
traducció a codi executable per a que la maquina el pugui entendre i es fa mitjançant un 
linker.

El linker es l’encarregat de agafar el codi objecte a les funcions de les llibreries que son 
necessàries per a el programa, es a dir una llibreria es un conjunt de codi executable que 
te un codi predefinit que ja te una funció especifica.
El concepte de maquina virtual es per a que diferents codis puguin ser interpretats per diferents processadors , per tant la compilació es diferents.
Primer amb el codi font el tradueix a un altre codi que no pot ser executat per la maquina però que es diferent al original, i després es tradueix a un altre comprensible per a la maquina, es a dir el primer tros de codi generat es comprensible per a tots els ordinadors i després es complida de manera especifica per a cada processador.
La principal marca que s’encarrega de fer això es JVM o Maquina Virtual de Java.
Les diferencies entre un compilador (es el que utilitza els linkers) i un intèrpret (maquina virtual de java), principalment es que el intèrpret es molt mes lent ja que va executant el codi mentre el tradueix en canvi el compilador nomes l’executa una vegada l’avantatges es que l’intèrpret es mes portable a altres sistemes operatius.
