# Hier sind Fragen aufgelistet, mit dessen Hilfe man den Stoff von WAF testen kann.

## Webarchitekturen

1. Nenne alle Schichten des 4 Tier Modells und erkläre sie.

2. Auf welche Schicht im 4 Tier Modell läuft Groovy and Grails?

3. Was ist ein Servlet?

4. Was ist ein Servlet Container? 

5. [Was versteht man unter Dynamische Interaktive Webseiten mit AJAX?](https://molily.de/js/ajax.html)

## Groovy

1. Nenne einige Anforderungen an Sprachen für Dynamische Webseiten.

2. Ist Groovy eine Compilierte oder eine Interpretierte Sprache?

3. Welche vereinfachungen bietet Groovy gegenüber Java?

4. In welchem Fall muss in Groovy ein Semikolon angegeben werden?

5. Wann muss in Groovy das ''def'' angegeben werden?

6. Woraus ergibt sich der Datentyp einer Varibale, wenn nicht explitiz angegeben?

7. Was ist der Unterschied zwischen den  Exception Handling in Java und Groovy?

8. Welche Funktion hat in Groovy das "as" Schlüsselwort?

9. Was sind benannte Parameter und wie werden sie realisiert?

10. Welchen Scope haben die Methoden/Funktionen, wenn nichts anderes angegeben?

11. Was ist der Vorteil, wenn auch Methoden/Funktionen Objekte sind?

12. Was ist eine Closure?

13. Wie gibt man Closures Parameter?

14. Wie wandelt man eine Methode/Funktion in eine Closure um?

15. Was ist eine Multimethoden-Closure?

16. Welche Möglichkeiten gibt es, eine Closure an eine Methode/Funktion zu übergeben?

17. Mit welcher Funktion kann man in einer Collection Filtern?

18. Skiziere ein Beispiel für ein Autoboxing in Groovy.

19. Welche unterschiede gibt es bei den Vergleichsoperationen?

20. Was ist der unterschied zwischen den as-Operator und einem Typecast?

21. Was ist das Problem mit den Character Typ in Groovy?

22. Was ist ein GString?

23. Zeige die Stringoperatoren.

24. Füge in einem StringBuffer ein Zeichen hinzu.

25. Füge einer Collection in einer Zeile mehrere Werte hinzu.

26. Wie kann man eine Liste Sortien, welches aus Strings besteht?

27. Was sind Ranges?

28. Was ist eine Groovy Bean?

29. Wie ist der Ablauf bei einem Attributzugriff?

30. Wieso ist es möglich, auf private Attribute zuzugreifen?

31. Wie kann man in Groovy Derefernezieren?

32. Nenne 3 unterschiedliche Arten auf ein Attribute eines Objektes zuzugreifen.

33. Was ist ein Expando?

34. Erkläre Regex anhand eines Beispiels.

35. Was sind Capture Groups?

36. Welche Strategien ieren gibt mit den Capture Groups?

37. Für was eignet sich der Find operator besonders gut? 

38. Was ist der Pattern-Operator?

39.  Was ist die Metaprogrammierung?

40. Nenne 3 Varianten um die Metaprogrammierung zu realisieren.

41. Was ist Reflection? Vor- und Nachteile?

42. Was versteht man unter Echte Metraprogrammierung?

43. Was bewirkt ExpandoMetaClass.enableGlobally()?

44. Was unterscheidet beim Hinzufügen eines neuen Kontruktors bei der Metaprogrammierung von dem Bereits bestehenden Kontruktor?

45. Was versteht man unter Intercept?

46. Wann wird die Methode methodMissing aufgerufen?

47. Was ist das Intercept-Cache-Invoke Pattern?

48. [Was versteht man unter Aspektorientierte Programmierung?](https://blog.mayflower.de/3413-Grundlagen-aspektorientierter-Programmierung.html)

49. Was ist die invokeMethod() Methode?


## Grails-Framework

1. Was sind die 4 Grails Prinzipien und was bedeuten sie?

2. Erkläre, welche 2 Design Patterns Grails nutzt. 

3. In welchem Teil des MVC Patterns befinden sich die Domänenklassen, die GSP Dateien und die selbst erstellten Klassen?

4. [Was ist das Scaffolding?](https://de.wikipedia.org/wiki/Scaffolding) 

5. [Was ist der Unterschied zwischen dem statischen und dem Dynamischen Scaffolding?](http://www.careerride.com/view/what-is-the-difference-between-static-and-dynamic-scaffolding-ruby-on-rails-2430.aspx)

6. [Erkläre das MVC Pattern](https://glossar.hs-augsburg.de/Model-View-Controller-Paradigma)

7. Mit Welcher Technologie werden die Domänenklassen Persistiert?

8. Wie genau wird eine Domainklasse in einer Datenbank repräsentiert?

9. [Was ist ein Groovy Bean?](http://mrhaki.blogspot.de/2009/08/groovy-goodness-groovybeans-simpler.html)

10. [Zähle mindestens 4 Integritätsregeln aus der Domänenklasse auf](https://docs.grails.org/latest/ref/Constraints/Usage.html)

11. Wozu dient eine Controllerklasse?

12. [Was ist eine Controlleraktion?](http://docs.grails.org/latest/guide/theWebLayer.html#understandingControllersAndActions)

13. Welche HTTP Methoden sollte für Save, Update und Delete sinnvolerweise verboten werden und warum?

14. In welcher Umgebungsvariable in der Controllerklasse sind alle HTTP-Parameter enthalten?

15. Zeige wie mit einer URL eine Controlleraktion aufgerufen werden kann, z.b. mit der Methode def edit(Professor prof)

16. Nenne 4 Umgebungsvariablen die im Controller enthalten sind.

17. Was ist der unterschied zwischen [Logging](http://docs.grails.org/3.2.1/ref/Plug-ins/logging.html) und [Flash](https://docs.grails.org/latest/ref/Controllers/flash.html)?

18. Zeige einen Codeabschnitt, wie man einen bestimmten Controller loggt.

19. [Was ist Content Negotiation?](https://de.wikipedia.org/wiki/Content_Negotiation)

20. [Was ist eine Rendernde Instanz?](https://docs.grails.org/latest/ref/Controllers/render.html)

21. Was ist ein Interzeptor?

22. Was bewirken die Methoden befor,afeter und afterView?

23. Was bewirkt die Methode redirect?

24. Was ist ein Un/bedingter Interzeptor?

25. Wofür steht GORM?

26. [Was ist das optimischtes Sperren?](http://datenbanken-verstehen.de/lexikon/optimistische-sperrverfahren/)

27. [Was ist Lazy Loading?](https://de.wikipedia.org/wiki/Lazy_Loading)

28. Wann kann es bei einer angabe von einer Kardinalität bei Domänenklassen zu einem Henne-Ei problem kommen?

29. Wie kann man das m:n Problem lösen?

30. Nenne die 3 Abbildungsvarianten der POGOs in einer Datenbank.

