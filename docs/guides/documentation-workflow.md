# Workflow dokumentacyjny

Ten dokument opisuje, jak pracować z dokumentacją w tym repo, aby instrukcje, README i status projektu stale odpowiadały rzeczywistości.

## Reguła nadrzędna

Dokumentacja nie jest dodatkiem „na później”. Jest częścią produktu repozytorium i musi być aktualizowana równolegle z pracą.

## Minimalny rytm po każdej zmianie

Po każdej istotnej zmianie:

1. zaktualizuj dokument, którego dotyczy zmiana,
2. sprawdź, czy `README.md` nadal pasuje do aktualnego stanu,
3. zaktualizuj `docs/project/project-status.md`,
4. zaktualizuj `docs/project/agent-handoff.md`,
5. jeśli dodano nowy dokument, dopisz go do `documentation-map.md`.

## Co musi być zsynchronizowane

### README
Musi odpowiadać na pytania:
- czym repo jest dziś,
- dla kogo jest,
- jak się po nim poruszać,
- które dokumenty są kluczowe.

### Project status
Musi odpowiadać na pytania:
- co zrobiono,
- co jest w toku,
- co jest następne,
- jakie są ryzyka i otwarte pytania.

### Agent handoff
Musi odpowiadać na pytania:
- gdzie zatrzymano pracę,
- co przeczytać na wejściu,
- jaki jest kolejny najmniejszy krok.

## Kiedy dokumentacja jest niespójna

Dokumentacja jest niespójna, gdy:

- README obiecuje elementy, których jeszcze nie ma,
- status nie zawiera już wykonanych kroków,
- handoff prowadzi do nieaktualnego następnego kroku,
- przewodniki linkują do plików, które nie istnieją.

## Jak pracować małymi porcjami

Preferowany model:

1. wybierz jeden mały krok,
2. wykonaj go,
3. natychmiast zaktualizuj dokumenty stanu,
4. dopiero potem przejdź dalej.

To repo nie powinno rozwijać się przez duże paczki zmian bez dokumentacyjnej synchronizacji.

## Miejsce na niepewności

Niepewności i pomysły eksperymentalne trzeba zapisywać. Nie należy liczyć na to, że pozostaną w pamięci rozmowy.

Zapisuj je w:

- `project-status.md` — jeśli wpływają na plan,
- `agent-handoff.md` — jeśli są ważne dla kolejnego agenta.

## Przed zamknięciem większego etapu

Sprawdź:

- [ ] README jest zgodne z realnym stanem repo
- [ ] status projektu pokazuje prawdziwy postęp
- [ ] handoff prowadzi do właściwego następnego kroku
- [ ] mapa dokumentacji uwzględnia nowe pliki
- [ ] linki między dokumentami są poprawne
