# Przewodnik pracy z AI / agentem

Ten dokument opisuje, jak używać repozytorium `deving` w taki sposób, aby kolejni agenci mogli płynnie kontynuować pracę.

## Założenie

Agent nie powinien musieć odgadywać:

- po co istnieje repo,
- co już zostało zrobione,
- co jest w toku,
- co ma zrobić dalej.

Właśnie dlatego istnieją dokumenty projektowe w `docs/project/`.

## Minimalny zestaw do przeczytania przed pracą

Każdy agent powinien zacząć od:

1. `/README.md`
2. `/docs/project/source-of-truth.md`
3. `/docs/project/project-status.md`
4. `/docs/project/agent-handoff.md`

Opcjonalnie:

5. `/docs/guides/documentation-workflow.md`
6. `/docs/project/documentation-map.md`

## Obowiązki agenta po zmianie

Po każdej istotnej zmianie agent powinien:

1. zaktualizować właściwy dokument merytoryczny,
2. zaktualizować `project-status.md`,
3. zaktualizować `agent-handoff.md`,
4. upewnić się, że README nadal mówi prawdę,
5. dopisać nowe pliki do mapy dokumentacji.

## Jak pisać handoff

Dobry handoff powinien zawierać:

- krótki opis aktualnego stanu,
- listę dokumentów już utworzonych,
- najbliższy kolejny krok,
- rzeczy, których nie wolno zgubić,
- otwarte wątpliwości.

## Jak nie pracować

Nie należy:

- kończyć dużej partii pracy bez aktualizacji statusu,
- zostawiać ważnych decyzji wyłącznie w historii czatu,
- dodawać dokumentów bez dopisywania ich do mapy,
- pisać README tak, jakby repo miało funkcje, których jeszcze nie ma.

## Co robić przy przejęciu pracy

1. przeczytaj handoff,
2. potwierdź aktualny status,
3. wykonaj jeden mały krok,
4. po kroku odśwież status i handoff,
5. pozostaw kolejny krok jasno opisany.

## Po co to wszystko

Celem nie jest nadmiar formalności. Celem jest:

- ograniczenie utraty kontekstu,
- przyspieszenie kontynuacji pracy,
- poprawa jakości dokumentacji,
- możliwość spokojnego skalowania repo i procesu.
