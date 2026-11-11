# Zadanie 1 – Analiza struktury pliku APK

**Poziom:** łatwy  
**Obszar:** analiza statyczna  
**Narzędzie:** 7-Zip lub inny program obsługujący archiwa

## Cel

Poznanie budowy pakietu aplikacji Android (APK) oraz rozpoznawanie najważniejszych plików i katalogów.

## Przygotowanie

- Przygotuj plik APK aplikacji szkoleniowej, do której masz prawo.
- Zainstaluj 7-Zip lub podobny program.
- Pracuj na kopii pliku, aby zachować oryginał.

## Polecenie

1. Zmień rozszerzenie kopii pliku z `.apk` na `.zip` (możesz też otworzyć APK bez zmiany rozszerzenia).
2. Otwórz archiwum w 7-Zip.
3. Odszukaj następujące elementy:
   - `AndroidManifest.xml`
   - `classes.dex`
   - `resources.arsc`
   - katalog `res`
   - katalog `assets`
   - katalog `lib` (jeśli występuje).
4. Zapisz, jakie informacje lub zasoby mogą znajdować się w każdym z nich.
5. Zwróć uwagę, czy w archiwum znajduje się więcej niż jeden plik `classes*.dex`.

## Pytania kontrolne

1. Za co odpowiada `AndroidManifest.xml`?
2. Gdzie znajduje się kod aplikacji?
3. Czym różnią się katalogi `res` i `assets`?
4. Do czego mogą służyć biblioteki w katalogu `lib`?
5. Dlaczego plik APK można otworzyć jak archiwum ZIP, mimo że jest pakietem aplikacji?
