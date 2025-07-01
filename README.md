# 🇺🇸 American Flag mit Java (ASCII-Format)
* Dieses Java-Programm gibt eine einfache stilisierte Darstellung der amerikanischen Flagge mit Hilfe von `System.out.printf()` in der Konsole aus. Es nutzt eine Kombination aus Sternen (`*`) und Gleichheitszeichen (`=`), um die typischen Elemente der Flagge symbolisch darzustellen.

# 📄 Beschreibung
* Das Programm besteht aus einer `for`-Schleife mit 16 Zeilen. Die ersten 10 Zeilen enthalten ein Sternenmuster für den linken Bereich und `=`-Zeichen für die Streifen. Ab Zeile 11 werden nur noch Streifen (=`=`) dargestellt.

# 🔧 Code
```java
public class AmericanFlag {
    public static void main(String[] args) {
        for (int i = 0; i <= 15; i++){
            if (i <= 9){
                System.out.printf("* * * * * * ===================================\n");
            }
        else{
            System.out.printf("===============================================\n");
        }
        }
    }
}
```
# 🧚🏻‍♀️
Diese Übung basiert auf Aufgaben von [w3resource](https://www.w3resource.com/java-exercises/basic/index.php)  

Die Lösungen wurden selbstständig von mir entwickelt und sind nur für Lernzwecke gedacht.
