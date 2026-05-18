# Status projektu

## Cel aktualnej fazy

Zbudować bardzo mocną, bogatą warstwę dokumentacyjną dla repozytorium `deving`, tak aby repo mogło działać jako rozbudowany szablon projektu i dokumentacji, a nie tylko pusty szkic.

## Stan bieżący

### Zrobione
- rozpoznano, że repo jest obecnie szkieletem bez kodu aplikacyjnego i bez skonfigurowanych narzędzi build/test/lint,
- przygotowano plan wdrożenia dokumentacji krok po kroku,
- utworzono mapę dokumentacji,
- utworzono dokument źródeł prawdy i reguł spójności,
- utworzono ten centralny plik statusowy,
- utworzono dokument handoff dla kolejnego czatu/agenta,
- rozbudowano główny `README.md`,
- dodano przewodniki użytkowe w `docs/guides/`,
- dodano dokumenty szablonowe w `docs/templates/`,
- sprawdzono poprawność linków między dokumentami,
- potwierdzono ponownie brak istniejących konfiguracji build/test/lint do uruchomienia.

### W toku
- końcowe domknięcie bieżącego etapu i przygotowanie gruntu pod następne rozszerzenia.

### Jeszcze niegotowe
- ewentualne dalsze warianty tematyczne lub stackowe,
- decyzja o przyszłym kierunku rozszerzeń technologicznych,
- potencjalna wersja dwujęzyczna dokumentacji.

## Następne małe kroki

1. zdecydować, czy następny mały etap dotyczy wariantów stackowych czy dalszego wzmacniania meta-szablonu,
2. jeśli pozostajemy neutralni technologicznie, rozwinąć jeszcze katalog gotowych sekcji i przykładów użycia,
3. jeśli wchodzimy w stacki, przygotować osobny plan dla wariantów Python/Node/Go,
4. utrzymać aktualność statusu i handoffu przy każdym kolejnym kroku.

## Decyzje podjęte

- dokumentacja będzie tworzona w wariancie bogatym, nie minimalnym,
- po każdej zmianie trzeba aktualizować stan projektu i handoff,
- README ma pełnić rolę mocnego wejścia do repo, a nie tylko krótkiego opisu,
- status projektu i handoff są obowiązkowymi dokumentami utrzymywanymi na bieżąco,
- przewodniki i katalog treści mają wyjaśniać nie tylko „co”, ale też „po co”, „skąd” i „jak używać”.

## Ryzyka

- łatwo dopuścić do rozjazdu między README a dokumentami projektowymi,
- przy dużej liczbie instrukcji może pojawić się nadmiar treści bez jasnej nawigacji,
- jeśli nie będziemy jasno oznaczać treści „gotowych” i „planowanych”, użytkownik może błędnie ocenić dojrzałość projektu,
- w przyszłości warianty stackowe mogą wymagać osobnej warstwy organizacyjnej, aby nie przeładować README.

## Otwarte pytania

- czy docelowo repo ma być neutralnym meta-szablonem, czy bardziej szablonem pod konkretny typ produktu,
- czy później powstaną osobne warianty stackowe (np. Python/Node/Go) jako osobne przewodniki albo katalogi,
- czy README powinno pozostać głównie po polsku, czy w przyszłości wymagać wersji dwujęzycznej,
- czy przyszłe rozszerzenia mają dotyczyć bardziej „strony projektu”, czy stricte zestawów plików startowych.

## Wątpliwości robocze

- jak szeroki powinien być katalog szablonów bez wchodzenia jeszcze w stack-specyficzne szczegóły,
- jak mocno rozdzielać instrukcje dla człowieka i dla AI, żeby nie dublować treści.

## Zależności

- jakość README zależy od najpierw ustalonej mapy dokumentacji i zasad spójności,
- przewodniki powinny odwoływać się do już istniejących dokumentów projektowych,
- dokument handoff musi być aktualizowany po każdym większym kroku,
- rozbudowa kolejnych warstw repo powinna utrzymać zgodność z obecnym modelem źródeł prawdy.

## Walidacja techniczna

- nie znaleziono plików konfiguracyjnych sugerujących istniejący build, testy lub linting,
- obecnie zmiany dotyczą dokumentacji i struktury plików Markdown,
- brak istniejących poleceń do uruchomienia przed wdrożeniem dokumentacji,
- sprawdzono ręcznie poprawność linków absolutnych w plikach Markdown — wszystkie odwołania wskazują istniejące pliki.
