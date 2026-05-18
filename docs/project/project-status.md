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
- przygotowano warstwę wariantów budowanych według celu projektu,
- dodano meta-szablon wspólny dla wariantów celu,
- dodano przegląd wariantów celu projektu,
- dodano cztery szczegółowe warianty: strona firmowa, web game, landing / portfolio / strona osobista, web app / SaaS MVP,
- zsynchronizowano README i przewodniki z nową warstwą wariantów celu.

### W toku
- końcowe domknięcie etapu wariantów celu i przygotowanie gruntu pod dalszą rozbudowę.

### Jeszcze niegotowe
- ewentualne dalsze warianty tematyczne lub stackowe dopięte pod każdy wariant celu,
- decyzja o przyszłym kierunku rozszerzeń technologicznych wewnątrz wariantów celu,
- potencjalna wersja dwujęzyczna dokumentacji.

## Następne małe kroki

1. zdecydować, czy następny mały etap rozwija jeszcze warianty celu, czy przechodzi już do warstwy stackowej pod wybrane warianty,
2. jeśli pozostajemy przy wariantach celu, rozwinąć dokładne listy docelowych plików roboczych i dokumentów pomocniczych dla każdego z nich,
3. jeśli wchodzimy w stacki, przygotować osobny plan wariantów technologicznych pod wybrane cele,
4. utrzymać aktualność statusu i handoffu przy każdym kolejnym kroku.

## Decyzje podjęte

- dokumentacja będzie tworzona w wariancie bogatym, nie minimalnym,
- po każdej zmianie trzeba aktualizować stan projektu i handoff,
- README ma pełnić rolę mocnego wejścia do repo, a nie tylko krótkiego opisu,
- status projektu i handoff są obowiązkowymi dokumentami utrzymywanymi na bieżąco,
- przewodniki i katalog treści mają wyjaśniać nie tylko „co”, ale też „po co”, „skąd” i „jak używać”,
- najbliższe rozszerzenia repo są porządkowane według rodzaju celu projektu, a nie od razu według stacku.

## Ryzyka

- łatwo dopuścić do rozjazdu między README a dokumentami projektowymi,
- przy dużej liczbie instrukcji może pojawić się nadmiar treści bez jasnej nawigacji,
- jeśli nie będziemy jasno oznaczać treści „gotowych” i „planowanych”, użytkownik może błędnie ocenić dojrzałość projektu,
- w przyszłości warianty stackowe mogą wymagać osobnej warstwy organizacyjnej podpiętej pod warianty celu, aby nie przeładować README,
- przy zwiększaniu liczby wariantów celu trzeba pilnować, żeby nie powielać tych samych reguł w wielu miejscach.

## Otwarte pytania

- czy docelowo repo ma być neutralnym meta-szablonem, czy bardziej szablonem pod konkretny typ produktu,
- czy później powstaną osobne warianty stackowe (np. Python/Node/Go) jako osobne przewodniki podpięte pod warianty celu,
- czy README powinno pozostać głównie po polsku, czy w przyszłości wymagać wersji dwujęzycznej,
- czy przyszłe rozszerzenia mają dotyczyć bardziej „strony projektu”, czy stricte zestawów plików startowych,
- czy każdy wariant celu powinien dostać osobne przewodniki robocze, czy wystarczy wspólny meta-model plus katalog plików.

## Wątpliwości robocze

- jak szeroki powinien być katalog szablonów bez wchodzenia jeszcze w stack-specyficzne szczegóły,
- jak mocno rozdzielać instrukcje dla człowieka i dla AI, żeby nie dublować treści,
- jak szczegółowe mają być docelowe mapy plików dla wariantów celu przed wejściem w konkretny stack.

## Zależności

- jakość README zależy od najpierw ustalonej mapy dokumentacji i zasad spójności,
- przewodniki powinny odwoływać się do już istniejących dokumentów projektowych,
- dokument handoff musi być aktualizowany po każdym większym kroku,
- rozbudowa kolejnych warstw repo powinna utrzymać zgodność z obecnym modelem źródeł prawdy,
- warianty celu powinny opierać się na wspólnym meta-szablonie, a dopiero potem rozwijać własne różnice.

## Walidacja techniczna

- nie znaleziono plików konfiguracyjnych sugerujących istniejący build, testy lub linting,
- obecnie zmiany dotyczą dokumentacji i struktury plików Markdown,
- brak istniejących poleceń do uruchomienia przed wdrożeniem dokumentacji,
- sprawdzono ręcznie poprawność linków absolutnych w plikach Markdown — wszystkie odwołania wskazują istniejące pliki.
