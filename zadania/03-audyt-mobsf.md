# Zadanie 3 – Audyt bezpieczeństwa aplikacji za pomocą MobSF

**Poziom:** trudny  
**Obszar:** automatyczna analiza bezpieczeństwa  
**Narzędzie:** Mobile Security Framework (MobSF)

## Cel

Przeprowadzenie podstawowego audytu bezpieczeństwa aplikacji Android, interpretacja wyników skanowania i zaproponowanie działań naprawczych.

## Przygotowanie

- Przygotuj APK aplikacji szkoleniowej, do której masz prawo.
- Uruchom MobSF zgodnie z oficjalną dokumentacją.
- Korzystaj z lokalnego, kontrolowanego środowiska laboratoryjnego.

## Polecenie

1. Otwórz interfejs MobSF.
2. Wgraj plik APK aplikacji szkoleniowej.
3. Poczekaj na zakończenie analizy statycznej.
4. Przejrzyj raport, zwracając uwagę na:
   - konfigurację aplikacji i manifest;
   - uprawnienia;
   - ustawienia debugowania;
   - konfigurację komunikacji sieciowej;
   - potencjalnie ujawnione dane lub sekrety;
   - eksportowane komponenty.
5. Wybierz co najmniej trzy ostrzeżenia lub potencjalne problemy.
6. Dla każdego problemu uzupełnij tabelę poniżej.
7. Oceń, czy każde ostrzeżenie rzeczywiście wskazuje podatność. Jeśli to możliwe, zweryfikuj je ręcznie w JADX lub w konfiguracji aplikacji.
8. Przygotuj krótkie podsumowanie audytu.

## Tabela wyników

| Lp. | Problem / ostrzeżenie | Dowód lub lokalizacja | Możliwe konsekwencje | Poziom ryzyka | Proponowana poprawka |
|---|---|---|---|---|---|
| 1 |  |  |  |  |  |
| 2 |  |  |  |  |  |
| 3 |  |  |  |  |  |

## Przykładowe obszary do sprawdzenia

- Sekrety lub klucze API zapisane w kodzie.
- Niebezpieczna konfiguracja komunikacji sieciowej.
- Nadmierne lub zbędne uprawnienia.
- Niepotrzebnie eksportowane komponenty.
- Włączony tryb debugowania w kompilacji przeznaczonej do wydania.

To przykładowe kategorie, a nie gwarantowana lista wyników. Konkretne ustalenia zależą od analizowanej aplikacji i wersji narzędzia.

## Pytania kontrolne

1. Czy MobSF wykrywa wszystkie możliwe podatności?
2. Czy każde ostrzeżenie oznacza rzeczywistą lukę bezpieczeństwa?
3. Dlaczego wyniki automatycznej analizy należy weryfikować ręcznie?
4. Który z wykrytych problemów uznajesz za najpoważniejszy i dlaczego?
5. Jakie poprawki zaproponujesz zespołowi programistycznemu?
