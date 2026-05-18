# Źródła prawdy i zasady spójności

Ten dokument definiuje, które pliki są nadrzędne dla konkretnych informacji i jak utrzymywać zgodność między README, przewodnikami i dokumentacją stanu projektu.

## Najważniejsza zasada

README, instrukcje i dokumenty projektowe muszą opisywać **aktualny stan repozytorium**, a nie wyłącznie docelową wizję. Jeśli coś zostało zaplanowane, ale jeszcze nie istnieje, trzeba to wyraźnie oznaczyć.

## Źródła prawdy

### 1. Stan projektu
**Źródło prawdy:** `/docs/project/project-status.md`

Tutaj zapisujemy:
- co już zostało wykonane,
- co jest w toku,
- co jest następne,
- jakie są ryzyka i zależności,
- jakie są otwarte pytania.

### 2. Przekazanie pracy kolejnemu agentowi
**Źródło prawdy:** `/docs/project/agent-handoff.md`

Tutaj zapisujemy:
- gdzie prace zostały zatrzymane,
- co koniecznie przeczytać na wejściu,
- jaki jest następny najmniejszy krok,
- jakie są decyzje oczekujące,
- czego nie pominąć przy kontynuacji.

### 3. Rola i układ dokumentów
**Źródło prawdy:** `/docs/project/documentation-map.md`

Tutaj zapisujemy:
- jakie dokumenty istnieją,
- po co istnieją,
- do którego obszaru należą,
- jaką funkcję pełnią.

### 4. Zasady zgodności dokumentacji
**Źródło prawdy:** `/docs/project/source-of-truth.md`

Tutaj zapisujemy:
- reguły aktualizacji,
- zależności między dokumentami,
- sposób rozstrzygania rozjazdów treści.

### 5. Wejście dla użytkownika
**Źródło główne:** `/README.md`

README nie jest źródłem prawdy dla statusu projektu. Jest źródłem prawdy dla:
- narracji startowej,
- obietnicy wartości projektu,
- nawigacji po repo,
- ścieżek użytkownika.

Jeżeli README rozmija się ze stanem projektu, poprawiamy README albo status — ale nie zostawiamy rozjazdu.

## Zasady aktualizacji po każdej zmianie

Po każdej istotnej zmianie trzeba sprawdzić:

1. czy `project-status.md` opisuje faktyczny postęp,
2. czy `agent-handoff.md` mówi prawdę o stanie prac,
3. czy `README.md` nadal pasuje do aktualnej struktury repo,
4. czy przewodniki w `docs/guides/` odsyłają do istniejących plików,
5. czy `documentation-map.md` zawiera wszystkie nowe dokumenty.

## Co robić przy rozjeździe informacji

Jeżeli dwa pliki mówią coś innego:

1. najpierw sprawdzić źródło prawdy z tej listy,
2. poprawić dokument wtórny,
3. dopisać korektę do `project-status.md`, jeśli rozjazd wpływał na plan pracy,
4. zaktualizować `agent-handoff.md`, jeśli kolejny agent mógłby się pomylić.

## Zasada „bogaty szablon najpierw”

Repo jest budowane jako szablon bogaty, szeroko opisany i gotowy do redukcji. To oznacza:

- najpierw tworzymy treść pełną,
- dopiero później użytkownik wybiera, co usuwa,
- instrukcje mają pomagać w świadomym upraszczaniu,
- nie projektujemy dokumentów wyłącznie pod wariant minimalny.

## Stała checklista spójności

Przed zakończeniem każdej większej partii prac:

- [ ] README zgadza się z aktualną strukturą repo
- [ ] status projektu opisuje realny postęp
- [ ] handoff pozwala innemu agentowi wejść bez kontekstu rozmowy
- [ ] przewodniki odpowiadają istniejącym plikom
- [ ] nie ma linków do nieistniejących materiałów
- [ ] otwarte pytania są zapisane, a nie „trzymane w głowie”
