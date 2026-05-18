# Status projektu

## Cel aktualnej fazy

Zbudować bardzo mocną, bogatą warstwę dokumentacyjną dla repozytorium `deving`, tak aby repo mogło działać jako rozbudowany szablon projektu i dokumentacji, a nie tylko pusty szkic.

## Stan bieżący

### Zrobione
- rozpoznano, że repo jest obecnie szkieletem bez kodu aplikacyjnego i bez skonfigurowanych narzędzi build/test/lint,
- przygotowano plan wdrożenia dokumentacji krok po kroku,
- utworzono mapę dokumentacji,
- utworzono dokument źródeł prawdy i reguł spójności,
- utworzono ten centralny plik statusowy.

### W toku
- budowa podstawowej warstwy dokumentacyjnej zarządzającej pracą,
- przygotowanie dokumentów, które będą prowadzić użytkownika i kolejnego agenta.

### Jeszcze niegotowe
- główny README w wersji bogatej,
- przewodniki użytkownika,
- instrukcje dostosowywania szablonów,
- dokumentacja dla AI/agenta,
- katalog treści szablonowych.

## Następne małe kroki

1. utworzyć `agent-handoff.md`,
2. rozbudować `README.md`,
3. dodać przewodniki w `docs/guides/`,
4. dodać dokumenty szablonowe w `docs/templates/`,
5. zsynchronizować wszystko i zrobić końcowy przegląd spójności.

## Decyzje podjęte

- dokumentacja będzie tworzona w wariancie bogatym, nie minimalnym,
- po każdej zmianie trzeba aktualizować stan projektu i handoff,
- README ma pełnić rolę mocnego wejścia do repo, a nie tylko krótkiego opisu,
- status projektu i handoff są obowiązkowymi dokumentami utrzymywanymi na bieżąco.

## Ryzyka

- łatwo dopuścić do rozjazdu między README a dokumentami projektowymi,
- przy dużej liczbie instrukcji może pojawić się nadmiar treści bez jasnej nawigacji,
- jeśli nie będziemy jasno oznaczać treści „gotowych” i „planowanych”, użytkownik może błędnie ocenić dojrzałość projektu.

## Otwarte pytania

- czy docelowo repo ma być neutralnym meta-szablonem, czy bardziej szablonem pod konkretny typ produktu,
- czy później powstaną osobne warianty stackowe (np. Python/Node/Go) jako osobne przewodniki albo katalogi,
- czy README powinno pozostać głównie po polsku, czy w przyszłości wymagać wersji dwujęzycznej.

## Wątpliwości robocze

- jak szeroki powinien być katalog szablonów bez wchodzenia jeszcze w stack-specyficzne szczegóły,
- jak mocno rozdzielać instrukcje dla człowieka i dla AI, żeby nie dublować treści.

## Zależności

- jakość README zależy od najpierw ustalonej mapy dokumentacji i zasad spójności,
- przewodniki powinny odwoływać się do już istniejących dokumentów projektowych,
- dokument handoff musi być aktualizowany po każdym większym kroku.

## Walidacja techniczna

- nie znaleziono plików konfiguracyjnych sugerujących istniejący build, testy lub linting,
- obecnie zmiany dotyczą dokumentacji i struktury plików Markdown,
- brak istniejących poleceń do uruchomienia przed wdrożeniem dokumentacji.
