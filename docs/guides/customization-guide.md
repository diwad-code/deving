# Jak dostosować ten bogaty szablon do własnego celu

Ten przewodnik opisuje, jak przejść od wersji „maksymalnej” do wariantu dopasowanego do konkretnego zastosowania, bez utraty ważnych informacji.

## Główna zasada

Najpierw rozumiesz całość. Dopiero potem usuwasz nadmiar.

Nie tnij repo według odruchu „to wygląda na za dużo”, tylko według logiki:

1. co jest źródłem prawdy,
2. co jest instrukcją,
3. co jest dodatkiem,
4. co naprawdę wspiera Twój cel.

## Najpierw zachowaj

Na starcie warto zachować bez zmian:

- `README.md`,
- `docs/project/source-of-truth.md`,
- `docs/project/project-status.md`,
- `docs/project/agent-handoff.md`,
- `docs/project/documentation-map.md`.

To są elementy, które dają strukturę i zapobiegają chaosowi.

## Następnie oceń przewodniki

Przewodniki w `docs/guides/` zostaw, jeśli:

- projekt ma więcej niż jednego odbiorcę,
- repo będzie rozwijane etapami,
- zależy Ci na dobrym onboardingu,
- chcesz mieć jasne zasady pracy z dokumentacją.

Możesz ograniczać przewodniki, jeśli:

- projekt jest bardzo mały,
- cały zespół ma wspólne, dobrze ustalone praktyki,
- część zasad jest przeniesiona gdzie indziej.

## Jak oceniać sekcje README

### Zostaw obowiązkowo
- opis czym jest repo,
- dla kogo jest repo,
- mapa dokumentów,
- aktualny stan repo,
- najważniejsze linki.

### Zostaw, jeśli pomagają
- sekcje ścieżek użytkownika,
- FAQ,
- rozbudowane uzasadnienie filozofii.

### Usuń lub skróć, jeśli przeszkadzają
- sekcje dotyczące użytkowników, których nie obsługujesz,
- rozbudowane akapity kontekstowe, jeśli repo jest już bardzo konkretne,
- informacje o wariantach, których nie planujesz rozwijać.

## Czego nie usuwać bez zastępstwa

Nie usuwaj bezpośrednio:

- źródeł prawdy,
- dokumentu statusowego,
- handoffu dla kolejnego agenta,
- zasad aktualizacji dokumentacji.

Jeśli naprawdę chcesz uprościć ten obszar, najpierw wprowadź alternatywny mechanizm o tej samej funkcji.

## Jak dopasować repo do celu

### Mały projekt solo
- zostaw prosty README,
- zachowaj status i źródła prawdy,
- skróć przewodniki do minimum potrzebnego Tobie,
- zostaw handoff, jeśli pracujesz z AI.

### Projekt zespołowy
- zostaw pełny README,
- utrzymaj przewodniki onboardingowe,
- rozbuduj workflow dokumentacyjny,
- nie usuwaj sekcji o spójności.

### Repo jako baza pod późniejszy starter stackowy
- zostaw pełną architekturę dokumentacyjną,
- traktuj obecne dokumenty jako warstwę meta,
- dopiero później dodawaj warianty technologiczne.

## Bezpieczna kolejność redukcji

1. usuń tylko to, co jest ewidentnie poza zakresem projektu,
2. skróć treści dodatkowe,
3. dopiero potem redukuj liczbę przewodników,
4. na końcu oceniaj, czy jakiś dokument projektowy da się połączyć z innym.

## Checklista przed usunięciem sekcji

- [ ] wiem, po co ta sekcja istnieje
- [ ] wiem, skąd bierze się jej treść
- [ ] wiem, kto z niej korzysta
- [ ] wiem, czym ją zastępuję lub dlaczego jest zbędna
- [ ] po usunięciu README i status nadal pozostaną spójne
