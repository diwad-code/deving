# Wariant celu: web app / SaaS MVP

## Dla kogo jest ten wariant

Ten wariant jest dla osób, które chcą budować:
- aplikację webową,
- produktowe MVP,
- prosty SaaS,
- repo, które ma szybciej rosnąć i wymagać większego porządku.

## Kiedy wybrać ten wariant

Wybierz go, jeśli:
- tworzysz produkt z funkcjami, a nie tylko stronę,
- potrzebujesz opisać scope MVP,
- musisz uporządkować env, deployment i status funkcji,
- chcesz etapowo rozwijać projekt z pomocą AI.

Nie jest to najlepszy wariant, jeśli głównym celem jest szybka strona contentowa bez większej logiki aplikacyjnej.

## Co użytkownik powinien osiągnąć w pierwszych 30 minutach

1. zrozumieć problem i zakres MVP,
2. znaleźć miejsce na status funkcji i decyzje,
3. wiedzieć, gdzie jest konfiguracja środowiska,
4. zrozumieć podstawowy model publikacji,
5. wiedzieć, jak współpracować z AI przy małych taskach bez gubienia kontekstu.

## Najważniejsze priorytety repo

W tym wariancie najwyższy priorytet mają:
- zakres MVP,
- porządek funkcji i decyzji,
- env i deployment,
- podział między dokumentacją produktu i dokumentacją techniczną,
- solidny workflow AI i handoff.

## Obowiązkowe sekcje README

- problem i wartość produktu,
- zakres MVP,
- użytkownik docelowy,
- szybki start lokalny,
- env i konfiguracja,
- architektura wysokiego poziomu,
- deployment,
- status produktu albo link do statusu.

## Sekcje README opcjonalne

- roadmap po MVP,
- decyzje projektowe,
- FAQ produktowe,
- zasady release’ów,
- przewodnik AI dla feature development.

## Dokumenty pomocnicze, które warto przewidzieć

- backlog / roadmap,
- dokument decyzji projektowych,
- status funkcji,
- release checklist,
- AI workflow dla feature development,
- dokument o środowiskach i konfiguracji.

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
│   ├── product/
│   │   ├── mvp-scope.md
│   │   ├── roadmap.md
│   │   ├── feature-status.md
│   │   └── target-user.md
│   ├── architecture/
│   │   ├── system-overview.md
│   │   ├── env-and-config.md
│   │   └── decisions.md
│   ├── operations/
│   │   ├── release-checklist.md
│   │   ├── deployment-flow.md
│   │   └── incident-notes.md
│   └── ai/
│       └── saas-mvp-ai-workflow.md
├── src/
├── tests/
├── config/
│   ├── env/
│   └── feature-flags/
├── public/
└── .github/
```

## Pliki obowiązkowe

- `README.md`
- `docs/project/project-status.md`
- `docs/project/agent-handoff.md`
- `docs/project/source-of-truth.md`
- `docs/project/documentation-map.md`
- dokument zakresu MVP,
- dokument env / konfiguracji,
- dokument statusu funkcji,
- dokument deploymentu albo wyraźna sekcja deployu w README.

## Pliki opcjonalne

- `CONTRIBUTING.md`
- `SECURITY.md`
- `CODE_OF_CONDUCT.md`
- `.env.example`
- `devcontainer.json`
- dokument decyzji architektonicznych,
- dokument release notes.

## Kluczowe obszary dokumentacyjne

- MVP scope,
- target user,
- status funkcji,
- środowiska,
- deployment preview / staging / production,
- release flow,
- decyzje i zależności.

## Workflow AI

AI może wspierać:
- dzielenie pracy na małe taski,
- propozycje struktury feature’ów,
- checklisty release,
- opisy zmian,
- utrzymanie porządku dokumentacyjnego.

AI nie powinno zgadywać:
- reguł bezpieczeństwa i prywatności,
- produkcyjnej konfiguracji,
- danych użytkowników,
- finalnych decyzji produktowych bez potwierdzenia.

Minimalny flow dla agenta:
1. przeczytać README,
2. przeczytać `project-status.md`,
3. przeczytać dokument MVP scope,
4. przeczytać dokument env / konfiguracji,
5. po każdej zmianie uaktualnić status i handoff.

## Typowe błędy początkujących

- zbyt szybkie mieszanie MVP z „future scope”,
- brak osobnego miejsca dla env i deploymentu,
- brak statusu funkcji,
- dokumentowanie produktu i techniki w jednym chaosie,
- proszenie AI o zbyt duże zmiany bez małych kroków i źródeł prawdy.

## Co można później okroić

- szeroki kontekst strategiczny po ustabilizowaniu produktu,
- część pomocniczych checklist,
- część materiałów brainstormingowych,
- duplikaty informacji przeniesione do bardziej dojrzałych narzędzi.

## Czego nie usuwać bez zastępstwa

- zakresu MVP,
- instrukcji env / konfiguracji,
- statusu funkcji,
- instrukcji deploymentu,
- statusu projektu i handoffu.

## Następny najmniejszy krok po wyborze tego wariantu

1. opisać problem i zakres MVP,
2. utworzyć sekcję env / konfiguracji,
3. utworzyć status funkcji,
4. dopisać podstawowy AI workflow dla małych tasków.
