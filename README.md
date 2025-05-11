LibrarySystem/Addbook: Saknade kontroller för att se om ISBN är null eller saknades.

LibrarySystem/RemoveBook: Kontrollerade inte om boken var utlånad innan den beslutade om att ta bort den.

LibrarySystem/SearchByTitle: Ignorerade inte skiftläge.

LibrarySystem/ReturnBook: Satte inte lånedatumet till null efter retur av bok.

LibrarySystem/CalculateLateFee: Dagliga avgiften var satt till 0.5kr och inte 5, beräkningen av avgiften använde sig av addition istället för multiplikation.
