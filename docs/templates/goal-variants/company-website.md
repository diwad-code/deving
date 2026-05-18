# Wariant celu: strona firmowa

## Dla kogo jest ten wariant

Ten wariant jest dla osób, które chcą zbudować repo pod:
- stronę firmy,
- stronę marki,
- stronę usługową,
- prostą stronę produktowo-informacyjną,
- repo, w którym content biznesowy jest tak samo ważny jak warstwa techniczna.

## Kiedy wybrać ten wariant

Wybierz go, jeśli:
- chcesz szybko uporządkować sekcje biznesowe,
- najważniejsze są oferta, wiarygodność i kontakt,
- zależy Ci na prostym deployu,
- AI ma wspierać copy, SEO i strukturę treści.

Nie jest to najlepszy wariant, jeśli głównym celem jest logika aplikacyjna, złożone konta użytkowników albo rozbudowany backlog funkcji produktowych.

## Co użytkownik powinien osiągnąć w pierwszych 30 minutach

1. zrozumieć strukturę strony,
2. znaleźć miejsce na teksty, assety i sekcje biznesowe,
3. wiedzieć, co edytować jako pierwsze,
4. przygotować prosty preview albo plan pierwszej publikacji,
5. skorzystać z AI do poprawienia treści bez naruszenia struktury repo.

## Najważniejsze priorytety repo

W tym wariancie najwyższy priorytet mają:
- czytelny README,
- porządek treści biznesowych,
- jasna mapa sekcji strony,
- prosty deployment,
- spójność między contentem, README i dokumentacją statusową.

## Quick start w 4 ruchach

1. przeczytaj README i krótki opis sekcji strony,
2. uzupełnij home, ofertę i kontakt,
3. sprawdź gdzie trafiają zdjęcia, logo i pliki do pobrania,
4. dopisz prostą checklistę publikacji albo preview.

## Obowiązkowe sekcje README

- czym jest projekt,
- dla jakiego typu firmy lub marki jest budowany,
- jakie sekcje strony obejmuje,
- jak uruchomić projekt lokalnie,
- jak przygotować publikację,
- co edytować najpierw,
- gdzie znajdują się teksty i assety,
- aktualny stan repo lub link do statusu.

## Sekcje README opcjonalne

- FAQ dla treści i marketingu,
- przykłady tonu komunikacji,
- checklista SEO,
- przykłady CTA,
- przewodnik po wariantach sekcji.

## Dokumenty pomocnicze, które warto przewidzieć

- przewodnik tworzenia treści biznesowych,
- przewodnik sekcji strony,
- checklista publikacji,
- checklista aktualizacji contentu,
- guide AI do copy, FAQ, CTA i SEO,
- dokument z decyzjami o tonie komunikacji albo grupie docelowej.

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
│   ├── guides/
│   │   ├── getting-started.md
│   │   ├── customization-guide.md
│   │   └── ai-agent-guide.md
│   ├── content/
│   │   ├── site-sections.md
│   │   ├── tone-of-voice.md
│   │   ├── faq-source.md
│   │   └── seo-checklist.md
│   ├── operations/
│   │   ├── publish-checklist.md
│   │   └── content-update-workflow.md
│   └── ai/
│       └── company-website-ai-workflow.md
├── src/
├── public/
│   ├── images/
│   ├── icons/
│   └── brand/
├── content/
│   ├── home/
│   ├── offer/
│   ├── about/
│   ├── faq/
│   └── contact/
├── assets/
│   ├── logos/
│   ├── photos/
│   └── downloads/
├── config/
│   └── env/
└── .github/
```

## Pliki obowiązkowe

- `README.md`
- `docs/project/project-status.md`
- `docs/project/agent-handoff.md`
- `docs/project/source-of-truth.md`
- `docs/project/documentation-map.md`
- dokument opisujący sekcje strony
- dokument publikacji albo minimum wyraźna sekcja deployu w README

## Co edytować najpierw

- `README.md` — krótki opis projektu i sposób uruchomienia,
- dokument sekcji strony — żeby było jasne co trafia na home, ofertę i kontakt,
- pliki treści w `content/home/`, `content/offer/` i `content/contact/`,
- checklistę publikacji albo sekcję deployu.

## Pliki opcjonalne

- `CONTRIBUTING.md`
- `SECURITY.md`
- `CODE_OF_CONDUCT.md`
- `docs/content/tone-of-voice.md`
- `docs/content/seo-checklist.md`
- `.env.example`
- `devcontainer.json`

## Kluczowe sekcje biznesowe

- hero,
- oferta / usługi,
- o firmie,
- proces współpracy,
- dowody zaufania,
- case studies,
- FAQ,
- kontakt,
- CTA.

## Kluczowe sekcje techniczne

- gdzie są assety,
- gdzie są teksty,
- jak robić preview zmian,
- jak wygląda deploy,
- jak aktualizować treść bez psucia struktury.

## Workflow AI

AI może wspierać:
- generowanie i redakcję copy,
- propozycje sekcji strony,
- warianty CTA,
- FAQ,
- checklisty SEO i publikacji.

AI nie powinno zgadywać:
- finalnego tonu marki,
- prawdziwych danych firmy,
- obietnic sprzedażowych,
- danych kontaktowych i prawnych.

Minimalny flow dla agenta:
1. przeczytać README,
2. przeczytać `project-status.md`,
3. przeczytać dokument sekcji strony,
4. zaktualizować status i handoff po każdej zmianie.

## Typowe błędy początkujących

- mieszanie assetów z finalnym contentem bez struktury,
- brak rozdziału między tekstami roboczymi a gotowymi,
- brak jasnego miejsca dla FAQ i proofów,
- wrzucanie deployu „na później” bez instrukcji,
- nadmierne poleganie na AI przy treściach wymagających wiedzy o firmie.

## Co można później okroić

- rozbudowane instrukcje strategii treści,
- część wariantów sekcji marketingowych,
- dodatkowe przykłady CTA,
- rozbudowane prompty AI dla wielu tonów komunikacji.

## Czego nie usuwać bez zastępstwa

- opisu sekcji strony,
- instrukcji publikacji,
- statusu projektu,
- handoffu,
- źródeł prawdy.

## Następny najmniejszy krok po wyborze tego wariantu

1. rozpisać sekcje biznesowe strony,
2. ustalić gdzie trafiają teksty i assety,
3. dopisać prostą checklistę publikacji,
4. opisać pierwszy workflow AI dla copy.
