# Plan ćwiczeń

* Podręcznik podstawowy: Michaelis. **Essential C#** 6 (lub **lepiej 7**)
* Oficjalna dokumentacja C# na stronach Microsoft (z przykładami!!!)

## Lab. 01. Poprawnie zdefiniowana klasa (_well formed class_)

* Cel: **poprawne**, **kompletne** definiowanie typu w C#.

* Zagadnienia: typy referencyjne i strukturalne, konstruktory (przeciążenia, łańcuchowanie), destruktor, 
implementacje - jeśli wymagane - kluczowych interfejsów (`IEquatable`, `IComparable`, `IDisposable`, ...), poprawna implementacja 
`Equals`, `GetHashCode`, klonowanie, przeciążanie operatorów, definiowanie konwersji jawnej i niejawnej, 
pieczętowanie klasy, metody rozszerzające, testy jednostkowe, czas życia obiektu

* Przykładowe problemy: klasa `Uamek`, klasa `Wielomian`, struktury `Time` oraz `TimeSpan`

## Lab. 02. Złożone hierarchie klas

* Cel: Projektowanie złożonej hierarchii klas i interfejsów, czytanie diagramów UML, ich interpretacja i implementowanie kodu

* Zagadnienia: klasa, interfejs, dziedziczenie, hermetyzacja, polimorfizm, klasy pochodne, przesłanianie składników, klasy abstrakcyjne, 
interfejsy, implementacja wielodziedziczenia, ...

* Przykładowe problemy: hierarchia klas pojazdów, mieszkanie, ...

## Lab. 03. Metody i typy generyczne. Kolekcje (projektowanie własnych)

* Cel: Projektowanie własnej kolekcji generycznej

* Zagadnienia: metody i typy generyczne, implementacja indeksera, implementacja iteratora (iteratorów), 
`IEnumerable`, `foreach`, `yield`, testy jednostkowe

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
