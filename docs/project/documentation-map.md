# Mapa dokumentacji

Ten dokument opisuje docelową strukturę dokumentacji w repozytorium `deving` oraz rolę każdego pliku. Ma pomagać utrzymać porządek, spójność i jasny podział odpowiedzialności między README, instrukcjami, dokumentami statusowymi i materiałami dla kolejnych agentów.

## Cel tej mapy

- pokazać pełny układ dokumentacji,
- określić, po co istnieje każdy dokument,
- ułatwić rozbudowę repo bez chaosu,
- pilnować, aby README i instrukcje nie rozmijały się ze stanem projektu.

## Aktualna architektura dokumentacji

```text
/
├── README.md
└── docs/
    ├── guides/
    │   ├── getting-started.md
    │   ├── choose-your-path.md
    │   ├── customization-guide.md
    │   ├── documentation-workflow.md
    │   └── ai-agent-guide.md
    ├── project/
    │   ├── documentation-map.md
    │   ├── source-of-truth.md
    │   ├── project-status.md
    │   └── agent-handoff.md
    └── templates/
        ├── template-philosophy.md
        └── content-catalog.md
```

## Role dokumentów

### Poziom główny

#### `/README.md`
- główna strona wejściowa projektu,
- tłumaczy czym jest repozytorium,
- prowadzi użytkownika do odpowiedniej ścieżki,
- pokazuje jak korzystać z repo jako bogatego szablonu,
- odsyła do dokumentów szczegółowych.

### Dokumenty zarządzające projektem

#### `/docs/project/documentation-map.md`
- mapa całej dokumentacji,
- opis ról plików i katalogów,
- punkt odniesienia przy dodawaniu nowych dokumentów.

#### `/docs/project/source-of-truth.md`
- reguły spójności,
- wskazanie źródeł prawdy dla statusu, decyzji i instrukcji,
- zasady aktualizacji po każdej zmianie.

#### `/docs/project/project-status.md`
- aktualny stan projektu,
- lista rzeczy zrobionych,
- lista kolejnych kroków,
- wątpliwości, ryzyka i decyzje.

#### `/docs/project/agent-handoff.md`
- przewodnik dla kolejnego czatu/agenta,
- opis aktualnej sytuacji roboczej,
- najbliższy kolejny krok,
- lista miejsc wymagających uwagi.

### Dokumenty użytkowe

#### `/docs/guides/getting-started.md`
- szybkie wejście do repo,
- opis od czego zacząć,
- skrócona orientacja w strukturze.

#### `/docs/guides/choose-your-path.md`
- ścieżki dla różnych typów użytkowników,
- wskazanie co czytać najpierw,
- rozróżnienie treści obowiązkowych i opcjonalnych.

#### `/docs/guides/customization-guide.md`
- instrukcja dostosowania szablonów,
- opis co zostawić, co usuwać i kiedy,
- reguły „okrajania” bogatego szablonu do konkretnego celu.

#### `/docs/guides/documentation-workflow.md`
- zasady pracy z dokumentacją,
- sposób utrzymywania spójności,
- checklista aktualizacji po zmianach.

#### `/docs/guides/ai-agent-guide.md`
- instrukcja współpracy z AI/agentami,
- wskazanie jak kontynuować pracę bez zgadywania,
- opis dokumentów, które trzeba czytać i aktualizować.

### Dokumenty szablonowe

#### `/docs/templates/template-philosophy.md`
- filozofia repo jako szablonu „maksymalnego”,
- uzasadnienie, dlaczego zaczynamy od bogatej wersji,
- zasady redukcji do mniejszych wariantów.

#### `/docs/templates/content-catalog.md`
- katalog elementów, które można umieszczać w README i instrukcjach,
- opis skąd bierze się treść danych sekcji,
- pomoc przy rozbudowie kolejnych szablonów.

## Zasady rozbudowy mapy

Przy dodawaniu nowego dokumentu należy:

1. dopisać go do tej mapy,
2. wskazać jego rolę,
3. określić, czy jest źródłem prawdy, czy dokumentem wtórnym,
4. zaktualizować `project-status.md` oraz `agent-handoff.md`,
5. sprawdzić, czy README albo przewodniki powinny do niego linkować.

## Czego tu nie trzymamy

Ten dokument nie przechowuje:

- bieżącego postępu prac,
- historii drobnych zmian,
- roboczych decyzji tymczasowych.

Te elementy należą odpowiednio do:

- `project-status.md`,
- `agent-handoff.md`,
- sekcji decyzji i wątpliwości w dokumentach projektowych.
