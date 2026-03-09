# Changelog 
Wszystkie znaczące zmiany w tym projekcie będą dokumentowane w tym pliku. W sposób przyjazny dla czytelnika :) Format bazuje na standardzie

```Markdown
Przykładowy wpis: 
## [Wersja] - ROK-MIESIĄC-DZIEŃ

### ChangeType (Typ Zmiany) 

- Jedna zmiana.
- Druga zmiana. - Itd.
```

---

## Dobre praktyki

### Typy zmian (słownik)

- `Added` dla nowych funkcji (features).
- `Changed` dla zmian w istniejącej funkcjonalności.
- `Deprecated` dla funkcji, które wkrótce zostaną usunięte.
- `Removed` dla funkcji, które zostały usunięte w tej wersji.
- `Fixed` dla wszelkich naprawionych błędów (bug fixes).
- `Security` w przypadku poprawek bezpieczeństwa. 

### Wytyczne

- **Changelogi** są dla ludzi, nie dla ejajków!!
- Powinien istnieć wpis dla każdej pojedynczej wersji.
- Te same typy zmian powinny być zgrupowane.
- Odwrócona chronologia = najnowsza wersja jest na samej górze.
- Data wydania każdej wersji jest widoczna.

## Jak się nie wypalić

- Trzymaj sekcję `Unreleased` (Niewydane) na samej górze, aby śledzić nadchodzące zmiany. 
- Służy to dwóm celom: 1. Ludzie widzą, jakich zmian mogą się spodziewać w nadchodzących wersjach. 2. W momencie publikacji (release), możesz po prostu przenieść zmiany z sekcji `Unreleased` do sekcji z numerem nowej wersji.