# Kodexempel - Modul 5

## Exempeluppgift 1

Skapa en metod med metodhuvudet

```csharp
static double ExchangeToSEK(string currency, double val)
```

Metoden ska ta emot namnet på en valuta som en sträng currency, och växla värdet val i den valutan till svenska kronor.
De valutor metoden ska känna till är:

- USD – 10.92
- GBP – 13.65
- EUR – 11.46
- (Om en annan valuta anges, returneras värdet oförändrat)

Testa metoden i `Main()` genom att anropa den med några värden och skriv ut resultatet.

## Exempeluppgift 2

Skapa en metod med metodhuvudet
```csharp
static void TestExchangeToSEK(string currency, double val)
```

Metoden ska användas för att testa metoden ExchangeToSEK från förra uppgiften:
Den anropar ExchangeToSEK och skriver sedan ut resultatet i formatet:

```csharp
"{val} {currency} är {resultat} SEK"
``` 

Anropa den tre gånger från Main, med olika testvärden.

