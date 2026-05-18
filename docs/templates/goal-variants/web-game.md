# Wariant celu: gra w formie aplikacji webowej

## Dla kogo jest ten wariant

Ten wariant jest dla osób, które chcą zbudować repo pod:
- grę przeglądarkową,
- prostą grę 2D albo 3D na web,
- interaktywny projekt gameplayowy,
- repo, w którym assety i mechaniki są równie ważne jak kod.

## Kiedy wybrać ten wariant

Wybierz go, jeśli:
- najważniejsze są mechaniki i gameplay loop,
- potrzebujesz czytelnej struktury assetów,
- chcesz mieć miejsce na eksperymenty, buildy i playtesty,
- AI ma wspierać pomysły, balans i porządkowanie pracy.

Nie jest to najlepszy wariant, jeśli budujesz przede wszystkim stronę contentową albo klasyczne SaaS MVP.

## Co użytkownik powinien osiągnąć w pierwszych 30 minutach

1. zrozumieć założenie gry i core loop,
2. znaleźć miejsce na logikę gry i assety,
3. wiedzieć, jak uruchomić lokalny build albo przynajmniej jak taki build ma być opisany,
4. znaleźć miejsce na backlog mechanik,
5. zrozumieć, jak AI może pomagać bez naruszania spójności assetów i dokumentacji.

## Najważniejsze priorytety repo

W tym wariancie najwyższy priorytet mają:
- opis gry i mechanik,
- porządek assetów,
- czytelny workflow buildów i publikacji,
- rozdzielenie eksperymentów od stabilnych elementów,
- dobry handoff przy szybkich iteracjach.

## Quick start w 4 ruchach

1. przeczytaj README i opis core loop,
2. sprawdź gdzie jest logika gry, a gdzie assety,
3. opisz najważniejszą mechanikę i sterowanie,
4. dopisz prostą checklistę builda albo playtestu.

## Obowiązkowe sekcje README

- pitch gry,
- core loop,
- jak uruchomić projekt,
- jak grać,
- gdzie są assety,
- gdzie jest logika gry,
- jak publikować build,
- gdzie śledzić status mechanik.

## Sekcje README opcjonalne

- roadmap mechanik,
- FAQ gameplayowe,
- plan buildów i release’ów,
- lista inspiracji,
- sekcja o generowaniu assetów albo użyciu AI.

## Dokumenty pomocnicze, które warto przewidzieć

- przewodnik assetów,
- przewodnik scen / poziomów,
- status mechanik,
- lista eksperymentów,
- plan buildów / release’ów,
- AI workflow dla balansu, testów smoke i dokumentacji gameplayowej.

## Docelowa mapa plików i katalogów

```text
/
├── README.md
├── docs/
│   ├── project/
│   │   ├── project-status.md
│   │   ├── agent-handoff.md
│   │   ├── source-of-truth.md
│   │   └── documentation-map.md
│   ├── gameplay/
│   │   ├── game-loop.md
│   │   ├── mechanics-status.md
│   │   ├── levels-scenes.md
│   │   └── playtest-notes.md
│   ├── assets/
│   │   ├── asset-map.md
│   │   ├── naming-rules.md
│   │   └── replacement-rules.md
│   ├── operations/
│   │   ├── build-release-plan.md
│   │   └── smoke-test-checklist.md
│   └── ai/
│       └── web-game-ai-workflow.md
├── src/
│   ├── game/
│   ├── scenes/
│   ├── systems/
│   └── ui/
├── assets/
│   ├── sprites/
│   ├── audio/
│   ├── effects/
│   ├── fonts/
│   └── levels/
├── public/
├── tests/
│   ├── smoke/
│   └── gameplay/
└── .github/
```

## Pliki obowiązkowe

- `README.md`
- `docs/project/project-status.md`
- `docs/project/agent-handoff.md`
- `docs/project/source-of-truth.md`
- `docs/project/documentation-map.md`
- dokument core loop albo mechanik,
- dokument mapy assetów,
- dokument buildów albo wyraźna sekcja release/build w README.

## Co edytować najpierw

- `README.md` — pitch gry, sterowanie i sposób uruchomienia,
- dokument `game-loop.md` albo równoważny opis mechanik,
- dokument mapy assetów,
- status mechanik albo prostą checklistę build / playtest.

## Pliki opcjonalne

- `CONTRIBUTING.md`
- `SECURITY.md`
- `CODE_OF_CONDUCT.md`
- `docs/gameplay/playtest-notes.md`
- `docs/assets/replacement-rules.md`
- `.env.example`
- `devcontainer.json`

## Kluczowe sekcje projektowe

- założenie gry,
- sterowanie,
- kluczowe mechaniki,
- status mechanik,
- typy assetów,
- plan buildów,
- zasady playtestów,
- testy smoke.

## Kluczowe sekcje techniczne

- struktura `src`,
- struktura `assets`,
- zasady nazewnictwa assetów,
- sposób uruchamiania dev builda,
- sposób przygotowania produkcyjnej wersji,
- reguły aktualizacji dokumentacji po zmianie mechanik.

## Workflow AI

AI może wspierać:
- pomysły na mechaniki,
- balans i warianty zasad,
- checklisty playtestów,
- opisy poziomów,
- porządkowanie dokumentacji gameplayowej.

AI nie powinno zgadywać:
- finalnego balansu gry jako faktu,
- licencji do assetów,
- źródła muzyki lub grafiki,
- zachowania silnika albo pipeline’u, jeśli nie jest opisany.

Minimalny flow dla agenta:
1. przeczytać README,
2. przeczytać `project-status.md`,
3. przeczytać dokument game loop,
4. przeczytać dokument mapy assetów,
5. po zmianie zaktualizować status i handoff.

## Typowe błędy początkujących

- wrzucanie assetów bez nazewnictwa i mapy,
- brak rozdziału między eksperymentem a stabilną mechaniką,
- brak prostego opisu sterowania,
- zbyt późne myślenie o buildzie i publikacji,
- mieszanie dokumentacji gameplayowej z luźnymi notatkami.

## Co można później okroić

- rozbudowane notatki koncepcyjne,
- część dokumentów eksperymentalnych,
- nadmiar wariantów mechanik,
- szerokie prompty AI do brainstormingu.

## Czego nie usuwać bez zastępstwa

- mapy assetów,
- opisu game loop,
- statusu mechanik,
- zasad buildów albo release’u,
- statusu projektu i handoffu.

## Następny najmniejszy krok po wyborze tego wariantu

1. opisać pitch i core loop,
2. rozpisać strukturę `src` i `assets`,
3. stworzyć podstawowy dokument statusu mechanik,
4. dopisać prostą checklistę build / playtest.
