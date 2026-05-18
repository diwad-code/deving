# Warianty według celu projektu

Ten dokument zbiera warianty budowane według **rodzaju celu projektu**. To obecnie preferowany kierunek rozwoju repo `deving`.

## Dlaczego warianty celu są teraz ważniejsze niż warianty stackowe

Na obecnym etapie użytkownik częściej wie:
- jaki efekt chce osiągnąć,
- jaki typ projektu chce uruchomić,
- jakie treści i pliki będą mu potrzebne,

niż:
- jaki framework chce wybrać,
- jaki pipeline techniczny ustawić,
- jaki zestaw narzędzi będzie najlepszy.

Dlatego najpierw porządkujemy repo wokół celu projektu, a dopiero później możemy dopinać do tych wariantów warstwy stackowe.

## Co wynika z researchu

Najbardziej użyteczne szablony dla początkujących redukują cztery typowe problemy:

1. setup complexity,
2. environment confusion,
3. deployment uncertainty,
4. documentation overload.

Warianty celu mają pomagać rozbrajać te problemy przez:
- lepszy quick start,
- wyraźniejsze README,
- bardziej sensowną strukturę katalogów,
- osobne instrukcje publikacji,
- lepszą współpracę z AI i handoffem,
- prostą odpowiedź na pytanie: „co mam edytować najpierw?”.

## Aktualny zestaw wariantów

### 1. Strona firmowa
Najlepsza dla:
- stron usługowych,
- stron marki,
- prostych stron sprzedażowo-informacyjnych,
- repo z naciskiem na content, sekcje biznesowe i publikację.

Dokument:
- `/docs/templates/goal-variants/company-website.md`

### 2. Gra w formie aplikacji webowej
Najlepsza dla:
- gier przeglądarkowych,
- interaktywnych projektów gameplayowych,
- repo z assetami, buildami, mechanikami i testami smoke.

Dokument:
- `/docs/templates/goal-variants/web-game.md`

### 3. Landing / portfolio / strona osobista
Najlepsza dla:
- portfolio,
- stron osobistych,
- prostych landingów,
- pierwszych projektów publikowanych przez początkujących.

Dokument:
- `/docs/templates/goal-variants/landing-portfolio-personal-site.md`

### 4. Web app / SaaS MVP
Najlepsza dla:
- aplikacji produktowych,
- MVP budowanych z pomocą AI,
- repo wymagających statusu funkcji, środowisk i bardziej złożonej organizacji.

Dokument:
- `/docs/templates/goal-variants/web-app-saas-mvp.md`

## Jak wybrać wariant

### Wybierz stronę firmową, jeśli:
- główny nacisk jest na komunikację oferty,
- kluczowe są sekcje biznesowe i treść,
- publikacja ma być prosta,
- AI ma pomagać głównie przy copy, FAQ i strukturze strony.

### Wybierz web game, jeśli:
- kluczowe są mechaniki i assety,
- potrzebujesz miejsca na gameplay loop i backlog eksperymentów,
- chcesz planować buildy i playtesty,
- AI ma pomagać przy balansie, pomysłach i dokumentacji gameplayowej.

### Wybierz landing / portfolio / stronę osobistą, jeśli:
- chcesz szybko opublikować mały projekt,
- potrzebujesz bardzo prostego flow wejścia,
- najważniejsze są bio, projekty, CTA i szybki deploy,
- repo ma być lekkie, ale nadal uporządkowane.

### Wybierz web app / SaaS MVP, jeśli:
- tworzysz produkt, a nie tylko stronę,
- potrzebujesz opisać MVP, scope, env i deployment,
- AI ma wspierać rozwój funkcji etapami,
- chcesz utrzymać porządek mimo większej złożoności.

## Rekomendowana kolejność rozbudowy

1. najpierw meta-szablon wariantu celu,
2. potem landing / portfolio / strona osobista,
3. potem strona firmowa,
4. potem web game,
5. na końcu web app / SaaS MVP.

Ta kolejność ogranicza chaos i pozwala najpierw utrwalić wspólny model, a dopiero później wchodzić w większą złożoność.

## Co wszystkie warianty mają wspólne

Każdy wariant powinien finalnie dostarczać:
- opis dla kogo jest,
- quick start,
- listę plików obowiązkowych,
- listę plików opcjonalnych,
- listę pierwszych rzeczy do edycji,
- strukturę README,
- guidance deploymentu,
- guidance pracy z AI,
- typowe błędy początkujących,
- zasady redukcji,
- następny najmniejszy krok.

## Czego jeszcze nie robimy

Na tym etapie jeszcze:
- nie schodzimy głęboko w konkretne stacki,
- nie rozpisujemy pełnych gotowych starterów technologicznych,
- nie mieszamy logiki celu projektu z wyborem frameworka,
- nie próbujemy zamknąć wszystkiego w jednym uniwersalnym README.

## Najważniejsze pytanie kontrolne

Każdy wariant powinien odpowiadać na pytanie:

**„Co użytkownik chce osiągnąć w pierwszych 30 minutach po wejściu do repo?”**

Jeśli wariant nie prowadzi do pierwszego małego sukcesu, jest jeszcze za słaby.
