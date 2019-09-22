# Plan ćwiczeń

* Podręcznik podstawowy: Michaelis. **Essential C#** 6 (lub **lepiej 7**)
* Oficjalna dokumentacja C# na stronach Microsoft (z przykładami!!!)

## Lab. 01. Poprawnie zdefiniowany typ (_well-formed type_)

* Cel: **poprawne**, **kompletne** definiowanie typu w C#.

* Zagadnienia: typy referencyjne i strukturalne, konstruktory (przeciążenia, łańcuchowanie), destruktor, 
implementacje - jeśli wymagane - kluczowych interfejsów (`IEquatable`, `IComparable`, `IDisposable`, ...), poprawna implementacja 
`Equals`, `GetHashCode`, klonowanie, przeciążanie operatorów, definiowanie konwersji jawnej i niejawnej, 
pieczętowanie klasy, metody rozszerzające, testy jednostkowe, czas życia obiektu

* Do przeczytania i zrozumienia: 
    * Michaelis, Essential C# 7 - rozdziały: 2. Data Types, 3. More with Data Types, 4. Operators and Control Flow, 5. Methods and Parameters, 6. Classes, 9. Value Types, **10. Well-Formed Types**, 11. Exception Handling

* Przykładowe problemy: klasa `Uamek`, klasa `Wielomian`, struktury `Time` oraz `TimeSpan`

## Lab. 02. Złożone hierarchie klas

* Cel: Projektowanie złożonej hierarchii klas i interfejsów, czytanie diagramów UML, ich interpretacja i implementowanie kodu

* Zagadnienia: klasa, interfejs, dziedziczenie, hermetyzacja, polimorfizm, klasy pochodne, przesłanianie składników, klasy abstrakcyjne, 
interfejsy, implementacja wielodziedziczenia, ...

* Do przeczytania i zrozumienia: 
    * Michaelis, Essential C# 7 - rozdziały: 6. Classes, **7. Inheritance**, **8. Interfaces**

* Przykładowe problemy: hierarchia klas pojazdów, mieszkanie, ...

## Lab. 03. Metody i typy generyczne. Kolekcje (projektowanie własnych)

* Cel: Projektowanie własnej kolekcji generycznej

* Zagadnienia: metody i typy generyczne, implementacja indeksera, implementacja iteratora (iteratorów), 
`IEnumerable`, `foreach`, `yield`, testy jednostkowe

* Do przeczytania i zrozumienia: 
    * Michaelis, Essential C# 7 - rozdziały: **12. Generics**, **15. Collection Interfaces with Standard Query Operators**

* Przykładowe problemy: własna implementacja stosu na podstawie interfejsu i zestawu testów jednostkowych (w tablicy, w formie listy wiązanej), 
implementacja kolejki priorytetowej (nie ma w bibliotekach C#), implementacja kolekcji `MultiSet`, ...

## Lab. 04. Delegaty. Notacja funkcyjna. Zdarzenia

* ToDo

## Lab. 05. LINQ

* ToDo

## Lab. 06. Programowanie wielowątkowe i równoległe. `async`/`await`

* ToDo

## Lab. 07. Refleksje. Programowanie dynamiczne. Kod niezarządzalny

* ToDo

## Lab. 08. Sprawdzian semestralny

---

## Zagadnienia uzupełniające wymienione lab'y

* Serializacja, deserializacja
* `System.IO`
* Entity Framework
