# Publiczna witryna dokumentów Bratersko

Ścieżki docelowe:
- https://bratersko.eu/regulamin
- https://bratersko.eu/polityka-prywatnosci
- https://bratersko.eu/usun-konto

## Regeneracja HTML z treści JS

```bash
node legal/buildWebsitePages.js
```

## Ważne — nie wdrażać

Generator blokuje budowę, jeśli w kanonicznej treści (`legal/termsContent.js`, `legal/privacyContent.js`) pozostają niedokończone placeholdery.
Przed publikacją na produkcji / DNS: przebuduj strony, zaktualizuj wersje w `lib/legalVersions.js` (gdy trzeba) i wykonaj końcowy przegląd treści.
