# Java
## _*Introducció*_
El Java és un [llenguatge de programació] dissenyat el 1990 per James Gosling amb altres companys de Sun Microsystems a partir del [llenguatge C]. Des del seu naixement fou pensat com un llenguatge orientat a objectes. Entre el 13 de novembre de 2006 i el maig del 2007 Sun va alliberar parts de Java com a programari lliure de codi obert amb llicència GPL. És un dels llenguatges de programació més utilitzats, i s'utilitza tant per aplicacions web com per aplicacions d'escriptori.

El Java és un llenguatge compilat amb una màquina virtual d'intermediari i, per tant, pot semblar lent en comparació amb altres llenguatges, però ofereix un índex de re-utilització de codi molt elevat, sent possible trobar moltes llibreries lliures de Java. És un llenguatge flexible i potent tot i la facilitat amb la qual es programa i dels resultats que ofereix. Un dels trets que el caracteritza i que el fa una eina molt valorada a l'hora de desenvolupar aplicacions distribuïdes, és el fet que és un llenguatge multi-plataforma.

Generalment els programes de Java es compilen en un bytecode (fitxer .class) que pot córrer en una Màquina Virtual Java. Sun Microsystems disposa de tres implementacions diferents de Java: J2SE per a aplicacions d'escriptori; J2EE per a aplicacions distribuïdes i J2ME per a plataformes amb recursos més reduïts com ara mòbils o PDAs. Per a cada una de les tres implementacions és possible descarregar el JRE (entorn d'execució Java) per a executar aplicacions o el SDK (Eines per al desenvolupament d'aplicacions) per a programar aplicacions en Java, aquest últim també inclou el JRE.

Un programa desenvolupat amb Java no necessita compilar-se de nou per a poder executar-se en qualsevol de les plataformes que disposi d'una versió instal·lada de JRE prou actualitzada per al programa.

## _*Característiques*_

* **Senzill**: Java s'ha creat perquè sigui un llenguatge senzill amb una sintaxi elegant. Únicament consta de tres tipus de dades primàries, eliminant els punters i l'herència múltiple
* **Orientat a objectes**: Java segueix els paradigmes de la programació orientada a objectes, ja que la programació amb Java se centralitza en la manipulació, creació i construcció d'objectes.
* **Distribuït**: Java permet la construcció d'aplicacions distribuïdes per mitjà d'una col·lecció específica de classes.
* **Interpretat**: Es necessita un intèrpret per executar els programes de Java, això alenteix als programes però els hi dona flexibilitat.
* **Robust**: Java és un llenguatge robust i fiable, s'ha escrit pensant a poder verificar errors i està molt tipificat.
* **Segur**: Java té pocs problemes de seguretat, característica molt important en les aplicacions distribuïdes d'Internet.
* **Arquitectura neutral**: Java és independent de la plataforma final on s'executarà el programa.
* **Portable**: Java és un llenguatge d'alt nivell i de plataforma independent, això li dona portabilitat.
* **Alt rendiment**: Els compiladors Java han anat millorant les seves prestacions. Els nous compiladors coneguts com a JIT permeten un rendiment molt semblant als llenguatges convencionals compilats.

##### Sintaxi

> La sintaxi del Java deriva en gran part del C. Però a diferència d'aquest, que combina la sintaxi per a programació genèrica, estructurada i orientada a objectes, el Java va ser dissenyat gairebé exclusivament com a llenguatge orientat a objectes. Tot el codi es troba dins d'una classe, i tot és un objecte (excepte nombres ordinals i reals, booleans i caràcters per motius de rendiment).
> Utilitza mètodes per comentar similars al C. Hi ha diferents tipus de comentari: una sola línia amb dues barres obliqües, múltiples línies començades per /* i acabades amb */, i el tipus de comentari de Javadoc que comença amb una barra obliqua i dos asteriscs i acaba amb */. L'estil Javadoc permet fer córrer l'executable de Javadoc per compilar la documentació del programa.

### **Exemples de codi**

```
// Hola.java
import java.io.IOException;

   public class Hola {
   
       public static void main(String[] args)throws IOException {
       
        System.out.println("Hola, món!"); 
        
    }
    
}
```

### **Aplicacions i miniaplicacions**

* Els programes de Java es divideixen principalment en dues categories
  * **Aplicacions**: són programes autònoms i independents
  * **Miniaplicacions**: les miniaplicacions o _applets_ Java són programes incrustats en pàgines HTML, i aquests s'executen damunt de navegadors Web.






[llenguatge de programació]:https://ca.wikipedia.org/wiki/Llenguatge_de_programaci%C3%B3 
[llenguatge C]:https://ca.wikipedia.org/wiki/Llenguatge_C