# Wybierz ścieżkę zależnie od celu

Ten dokument pomaga dobrać właściwy sposób użycia repozytorium `deving` do Twojego celu. Nie każdy użytkownik potrzebuje czytać wszystko w tej samej kolejności.

## Profil 1: Startuję od zera

### Kim jesteś
Masz pomysł albo nowy projekt i chcesz wystartować z sensowną strukturą, zamiast budować wszystko od pustego katalogu.

### Czytaj najpierw
1. `/README.md`
2. `/docs/guides/getting-started.md`
3. `/docs/guides/customization-guide.md`

### Sekcje obowiązkowe
- opis celu projektu,
- podstawowa struktura dokumentacji,
- źródła prawdy,
- zasady aktualizacji.

### Sekcje opcjonalne
- rozbudowane ścieżki użytkownika,
- część materiałów dla AI, jeśli nie używasz agentów.

### Co możesz później usunąć
- nadmiarowe warianty użycia, które nie pasują do Twojego projektu,
- część katalogu treści szablonowych.

## Profil 2: Chcę szybko użyć gotowego szablonu

### Kim jesteś
Masz mało czasu i chcesz szybko przejąć dobrą strukturę, ale bez czytania wszystkiego.

### Czytaj najpierw
1. `/README.md`
2. `/docs/guides/customization-guide.md`
3. `/docs/project/source-of-truth.md`

### Sekcje obowiązkowe
- co zostawić,
- czego nie usuwać,
- jak nie rozwalić spójności dokumentacji.

### Sekcje opcjonalne
- szeroki kontekst strategiczny,
- część materiałów opisujących filozofię szablonu.

### Co możesz później usunąć
- obszerne wyjaśnienia, jeśli po wdrożeniu struktura jest już zrozumiała,
- elementy nieużywane w codziennej pracy.

## Profil 3: Buduję porządny projekt lub produkt

### Kim jesteś
Chcesz, żeby repo od początku było czytelne, skalowalne i gotowe do rozwoju.

### Czytaj najpierw
1. `/README.md`
2. `/docs/project/documentation-map.md`
3. `/docs/project/source-of-truth.md`
4. `/docs/templates/content-catalog.md`

### Sekcje obowiązkowe
- pełna architektura dokumentacji,
- rozdział źródeł prawdy,
- zasady przekazywania pracy,
- bogate sekcje README.

### Sekcje opcjonalne
- niektóre wskazówki dla małych projektów,
- tymczasowe notatki organizacyjne.

### Co możesz później usunąć
- elementy czysto przejściowe po osiągnięciu stabilnej struktury,
- treści dotyczące wariantów, których nigdy nie wdrożysz.

## Profil 4: Uporządkowuję istniejące repo

### Kim jesteś
Masz już projekt, ale dokumentacja jest niespójna, biedna lub trudna do utrzymania.

### Czytaj najpierw
1. `/docs/templates/content-catalog.md`
2. `/docs/project/source-of-truth.md`
3. `/docs/guides/documentation-workflow.md`

### Sekcje obowiązkowe
- katalog brakujących elementów,
- zasady synchronizacji dokumentacji,
- status projektu i handoff.

### Sekcje opcjonalne
- część startowa dla greenfield,
- elementy stricte onboardingowe.

### Co możesz później usunąć
- sekcje, które dublują już istniejące sprawdzone procesy w Twoim repo.

## Profil 5: Używam repo jako ramy dla pracy z AI

### Kim jesteś
Chcesz, żeby kolejni agenci lub czaty mogli bezpiecznie i płynnie przejmować pracę.

### Czytaj najpierw
1. `/docs/project/agent-handoff.md`
2. `/docs/guides/ai-agent-guide.md`
3. `/docs/project/project-status.md`
4. `/docs/project/source-of-truth.md`

### Sekcje obowiązkowe
- handoff,
- status projektu,
- zasady aktualizacji po każdej zmianie,
- opis następnego małego kroku.

### Sekcje opcjonalne
- część materiałów ogólnych dla ludzi niepracujących z AI.

### Co możesz później usunąć
- niewiele — jeśli repo stale współpracuje z AI, ten obszar raczej należy wzmacniać, a nie redukować.

## Zasada wyboru

Jeśli nie jesteś pewien, którą ścieżkę wybrać:

- zacznij od wariantu szerszego,
- nie usuwaj niczego zbyt wcześnie,
- potraktuj repo jako zestaw klocków,
- tnij dopiero po zrozumieniu zależności między dokumentami.
