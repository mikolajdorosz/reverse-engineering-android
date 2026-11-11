# Zadanie 2 – Dekompilacja i analiza kodu aplikacji

**Poziom:** średni  
**Obszar:** analiza statyczna, DEX i dekompilacja  
**Narzędzie:** JADX-GUI

## Cel

Sprawdzenie, jakie informacje o działaniu aplikacji można uzyskać z pliku APK bez dostępu do oryginalnego projektu i kodu źródłowego.

## Przygotowanie

- Przygotuj APK legalnej aplikacji szkoleniowej.
- Pobierz JADX z oficjalnego repozytorium projektu.
- Otwórz aplikację w JADX-GUI.

## Polecenie

1. Otwórz plik APK w JADX-GUI.
2. Przejrzyj drzewo pakietów, klas i zasobów.
3. Odszukaj klasę głównej aktywności lub klasę odpowiedzialną za ekran logowania.
4. Znajdź metodę, która reaguje na dane wpisywane przez użytkownika albo wykonuje prostą kontrolę.
5. Opisz własnymi słowami, co robi ta metoda.
6. Użyj wyszukiwania w projekcie dla haseł:
   - `password`
   - `token`
   - `secret`
   - `api_key`
   - `username`
7. Oceń kontekst znalezionych wystąpień. Nie zakładaj, że każde wystąpienie oznacza ujawnienie sekretu.
8. Zapisz, jakie informacje można odczytać, a czego nie da się jednoznacznie ustalić na podstawie samej dekompilacji.

## Pytania kontrolne

1. Czy kod po dekompilacji wygląda identycznie jak oryginalny kod napisany przez programistę?
2. Czy udało się rozpoznać nazwy klas i metod?
3. Dlaczego dekompilacja może ułatwić analizę aplikacji przez osobę atakującą?
4. Dlaczego umieszczanie sekretów w kodzie aplikacji jest ryzykowne?
5. Czy obfuskacja całkowicie uniemożliwia analizę kodu?
