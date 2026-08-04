# Publiczna witryna dokumentów Bratersko

Ścieżki docelowe:
- https://bratersko.pl/regulamin
- https://bratersko.pl/polityka-prywatnosci
- https://bratersko.pl/usun-konto

## Regeneracja HTML z treści JS

```bash
node legal/buildWebsitePages.js
```

## Ważne — nie wdrażać

Generator blokuje budowę, jeśli w kanonicznej treści (`legal/termsContent.js`, `legal/privacyContent.js`) pozostają niedokończone placeholdery.
Przed publikacją na produkcji / DNS: przebuduj strony, zaktualizuj wersje w `lib/legalVersions.js` (gdy trzeba) i wykonaj końcowy przegląd treści.
