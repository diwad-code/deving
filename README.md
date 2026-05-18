# deving

> Bogaty szablon dokumentacyjno-projektowy do budowania repozytorium od mocnych podstaw — z myślą o ludziach, zespołach i agentach AI.

## Czym jest to repo

`deving` to repozytorium budowane jako **rozszerzony szablon startowy**. Nie jest jeszcze gotowym produktem ani działającą aplikacją. Na obecnym etapie stanowi świadomie rozbudowywaną bazę dokumentacyjną, która ma pomóc:

- startować nowe projekty w uporządkowany sposób,
- szybciej budować README i instrukcje wysokiej jakości,
- utrzymywać spójność między stanem projektu a dokumentacją,
- przekazywać pracę między ludźmi i agentami bez utraty kontekstu,
- zaczynać od wariantu „bogatego”, a potem świadomie go upraszczać.

## Dlaczego taka forma

Zamiast budować minimalny szablon i później desperacko go uzupełniać, ten projekt idzie w przeciwną stronę:

- najpierw tworzy szeroki, dobrze objaśniony fundament,
- potem użytkownik usuwa to, czego nie potrzebuje,
- dokumentacja tłumaczy nie tylko **co** jest w repo, ale też **po co**, **skąd bierze się treść** i **jak dopasować ją do własnego celu**.

## Dla kogo jest `deving`

To repo może być użyteczne, jeśli:

- zaczynasz nowy projekt i nie chcesz startować od pustki,
- chcesz mieć „super README”, a nie tylko krótki opis repo,
- budujesz dokumentację, która ma być zrozumiała dla kolejnych osób,
- chcesz pracować z AI/agentami i zostawiać im dobry kontekst,
- porządkujesz projekt, który urósł bez jasnej struktury dokumentacyjnej.

## Co znajdziesz w środku

### Warstwa wejściowa
- `README.md` — główny punkt wejścia i mapa startowa.

### Dokumenty projektowe
- `/docs/project/documentation-map.md` — mapa dokumentów i ich ról,
- `/docs/project/source-of-truth.md` — zasady spójności i źródła prawdy,
- `/docs/project/project-status.md` — bieżący stan projektu, ryzyka i kolejne kroki,
- `/docs/project/agent-handoff.md` — przewodnik dla kolejnego czatu/agenta.

### Przewodniki użytkowe
- `/docs/guides/getting-started.md` — od czego zacząć,
- `/docs/guides/choose-your-path.md` — ścieżki zależnie od celu użytkownika,
- `/docs/guides/customization-guide.md` — jak okrajać bogaty szablon do własnych potrzeb,
- `/docs/guides/documentation-workflow.md` — jak utrzymywać dokumentację w zgodzie ze stanem repo,
- `/docs/guides/ai-agent-guide.md` — jak pracować z tym repo przez kolejnych agentów.

### Szablony i katalog treści
- `/docs/templates/template-philosophy.md` — filozofia „szablonu maksymalnego”,
- `/docs/templates/content-catalog.md` — katalog typów treści, które można rozwijać dalej.
- `/docs/templates/goal-variant-meta-template.md` — wspólny model wariantów budowanych według celu projektu,
- `/docs/templates/goal-variants-overview.md` — przegląd wariantów celu projektu,
- `/docs/templates/goal-variants/` — szczegółowe warianty m.in. dla strony firmowej, web game, landingu i SaaS MVP.

### Notatki robocze
- `/docs/notes/` — miejsce pomocnicze na materiały tymczasowe, które nie powinny zastępować dokumentów źródłowych.

## Szybki start

### Jeśli chcesz tylko się zorientować
1. Przeczytaj ten README.
2. Przejdź do `/docs/guides/choose-your-path.md`.
3. Wybierz ścieżkę odpowiadającą Twojemu celowi.

### Jeśli chcesz zacząć budować na tym własny projekt
1. Przeczytaj `/docs/guides/getting-started.md`.
2. Sprawdź `/docs/guides/customization-guide.md`.
3. Sprawdź `/docs/templates/goal-variants-overview.md`, jeśli wiesz już jaki typ projektu chcesz budować.
4. Zobacz, które sekcje zachować, a które usunąć.
5. Traktuj `project-status.md` jako punkt kontroli postępu.

### Jeśli przejmujesz pracę po innym agencie
1. Zacznij od `/docs/project/agent-handoff.md`.
2. Potem przeczytaj `/docs/project/source-of-truth.md`.
3. Na końcu sprawdź `project-status.md`.

## Wybierz swoją ścieżkę

| Typ użytkownika | Od czego zacząć | Co jest najważniejsze |
| --- | --- | --- |
| Start od zera | `/docs/guides/getting-started.md` | zrozumienie układu repo |
| Szybkie użycie szablonu | `/docs/guides/customization-guide.md` | co zostawić, co wyrzucić |
| Budowa porządnego projektu | `/docs/guides/choose-your-path.md` | dopasowanie struktury do celu |
| Uporządkowanie istniejącego repo | `/docs/templates/content-catalog.md` | wybór brakujących elementów |
| Kontynuacja przez AI/agenta | `/docs/project/agent-handoff.md` | bieżący stan i następny krok |

## Warianty według celu projektu

Aktualnie repo rozwija dodatkową warstwę: **warianty według rodzaju celu projektu**. To ma pomóc osobom zaczynającym od pytania:

**„Co chcę zbudować?”**

Zamiast od razu pytać o framework albo stack.

Punkt wejścia:

- `/docs/templates/goal-variants-overview.md`

Aktualne warianty:

- strona firmowa,
- gra w formie aplikacji webowej,
- landing / portfolio / strona osobista,
- web app / SaaS MVP.

Każdy wariant opisuje:
- dla kogo jest,
- jak powinien wyglądać quick start,
- jakie pliki i katalogi są potrzebne,
- co edytować najpierw,
- jakie sekcje README są obowiązkowe,
- jak planować deployment,
- jak pracować z AI bez zgadywania.

## Jak korzystać z repo jako bogatego szablonu

To repo nie zakłada, że wszystko musisz zostawić. Wręcz przeciwnie — ma dać Ci **więcej niż potrzebujesz**, abyś mógł świadomie wybrać:

- które sekcje są krytyczne,
- które są opcjonalne,
- które są tylko pomocnicze na etapie startu,
- które warto usunąć po ustabilizowaniu projektu.

Najpierw pracujesz na wersji pełnej. Dopiero później ją upraszczasz.

## Co można później „okroić”

Najczęściej redukcji podlegają:

- rozbudowane sekcje kontekstowe README,
- część ścieżek użytkownika, jeśli repo ma jeden konkretny cel,
- instrukcje dla AI, jeśli projekt nie korzysta z agentów,
- sekcje statusowe po przejściu do bardziej dojrzałych narzędzi zarządzania pracą.

Nie usuwaj jednak w ciemno:

- dokumentów źródeł prawdy,
- zasad spójności,
- przewodników wyjaśniających skąd bierze się treść dokumentów,
- handoffu, jeśli projekt jest współtworzony przez więcej niż jedną osobę lub przez AI.

## Aktualny stan repo

Obecnie repo:

- ma już podstawową architekturę dokumentacji projektowej,
- buduje bogaty zestaw przewodników i opisów,
- ma pierwszy model wariantów budowanych według celu projektu,
- nie zawiera jeszcze kodu produktu ani skonfigurowanego stacku,
- jest przygotowywane jako solidna baza pod dalsze warianty i rozszerzenia.

Szczegóły bieżącego postępu znajdziesz w:

- `/docs/project/project-status.md`
- `/docs/project/agent-handoff.md`

## Zasady spójności

Jeśli edytujesz repo, pamiętaj:

- README musi odpowiadać aktualnemu stanowi repo,
- status projektu musi odzwierciedlać realny postęp,
- handoff ma wystarczyć komuś, kto nie czytał poprzedniej rozmowy,
- nowe dokumenty trzeba dopisać do mapy dokumentacji.

Pełne zasady są tutaj:

- `/docs/project/source-of-truth.md`
- `/docs/guides/documentation-workflow.md`

## FAQ

### Czy to jest gotowy starter aplikacji?
Nie. To obecnie głównie rozbudowywany starter dokumentacyjno-strukturalny.

### Czy repo jest zbyt rozbudowane na mały projekt?
Na start może być większe niż potrzebujesz — i to jest celowe. Łatwiej usunąć nadmiar niż odtwarzać brakujący kontekst.

### Czy później można przygotować warianty pod konkretne stacki?
Tak. Ten fundament ma to ułatwić, ale aktualnie repo pozostaje neutralne technologicznie.

### Od czego zacząć, jeśli chcę przejąć pracę po innym agencie?
Od `/docs/project/agent-handoff.md`.

## Najważniejsze linki

- [Mapa dokumentacji](/docs/project/documentation-map.md)
- [Źródła prawdy i zasady spójności](/docs/project/source-of-truth.md)
- [Status projektu](/docs/project/project-status.md)
- [Handoff dla kolejnego agenta](/docs/project/agent-handoff.md)
- [Getting started](/docs/guides/getting-started.md)
- [Wybór ścieżki użytkownika](/docs/guides/choose-your-path.md)
- [Przewodnik dostosowania szablonu](/docs/guides/customization-guide.md)
- [Workflow dokumentacyjny](/docs/guides/documentation-workflow.md)
- [Przewodnik AI/agenta](/docs/guides/ai-agent-guide.md)
- [Filozofia szablonu](/docs/templates/template-philosophy.md)
- [Katalog treści](/docs/templates/content-catalog.md)
- [Meta-szablon wariantu celu](/docs/templates/goal-variant-meta-template.md)
- [Przegląd wariantów celu](/docs/templates/goal-variants-overview.md)
