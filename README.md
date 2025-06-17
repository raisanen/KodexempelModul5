# Kodexempel - Modul 5

## Exempeluppgift 1

Skapa en metod med metodhuvudet

```csharp
static double ExchangeToSEK(string currency, double val)
```

Metoden ska ta emot namnet p� en valuta som en str�ng currency, och v�xla v�rdet val i den valutan till svenska kronor.
De valutor metoden ska k�nna till �r:

- USD � 10.92
- GBP � 13.65
- EUR � 11.46
- (Om en annan valuta anges, returneras v�rdet of�r�ndrat)

Testa metoden i `Main()` genom att anropa den med n�gra v�rden och skriv ut resultatet.

## Exempeluppgift 2

Skapa en metod med metodhuvudet
```csharp
static void TestExchangeToSEK(string currency, double val)
```

Metoden ska anv�ndas f�r att testa metoden ExchangeToSEK fr�n f�rra uppgiften:
Den anropar ExchangeToSEK och skriver sedan ut resultatet i formatet:

```csharp
"{val} {currency} �r {resultat} SEK"
``` 

Anropa den tre g�nger fr�n Main, med olika testv�rden.

