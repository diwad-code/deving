# Meta-szablon wariantu celu projektu

Ten dokument definiuje wspólny model dla wariantów budowanych **według rodzaju celu projektu**, a nie według stacku technologicznego. Ma pomóc tworzyć kolejne warianty w sposób spójny, porównywalny i naprawdę użyteczny dla osób zaczynających.

## Dlaczego ten poziom jest potrzebny

Na obecnym etapie repo ma pomagać użytkownikowi odpowiedzieć najpierw na pytanie:

**„Co chcę zbudować?”**

Dopiero później ma wejść pytanie:

**„Na jakim stacku chcę to postawić?”**

To podejście jest szczególnie ważne dla:
- osób początkujących na GitHubie,
- osób startujących z pomocą AI,
- osób, które najpierw potrzebują porządku w README, strukturze plików i publikacji,
- osób, które nie chcą od razu wybierać frameworka.

## Zasada projektowa

Każdy wariant celu powinien być zaprojektowany tak, aby użytkownik:

1. zrozumiał, czy to wariant dla niego,
2. osiągnął pierwszy sensowny postęp w ciągu pierwszych 30 minut,
3. wiedział, które pliki są obowiązkowe,
4. wiedział, które elementy można uprościć później,
5. mógł bezpiecznie pracować z AI bez zgadywania.

## Wspólny rdzeń każdego wariantu

Każdy wariant musi zawierać następujące sekcje.

### 1. Tożsamość wariantu
- dla kogo jest,
- kiedy warto go wybrać,
- kiedy nie jest najlepszym wyborem,
- jaki typ rezultatu użytkownik chce osiągnąć.

### 2. Pierwsze 30 minut
- jaki ma być pierwszy sukces użytkownika,
- jaki ma być pierwszy mały efekt w repo,
- jaki ma być pierwszy punkt orientacyjny w dokumentacji,
- jaka ma być pierwsza bezpieczna interakcja z AI.

### 3. Priorytety repo
- co w tym wariancie jest najważniejsze,
- co ma najwyższy priorytet w README,
- co ma najwyższy priorytet w strukturze plików,
- gdzie początkujący najczęściej się gubi.

### 4. Quick start
- od czego zacząć,
- które dokumenty czytać najpierw,
- co edytować jako pierwsze,
- jaki jest pierwszy punkt publikacji albo preview.

### 5. Docelowa struktura repo
- główne katalogi,
- pliki obowiązkowe,
- pliki opcjonalne,
- katalogi robocze,
- miejsca na treści, assety, status i handoff.

### 6. Struktura README
- sekcje obowiązkowe,
- sekcje opcjonalne,
- sekcje specyficzne dla typu projektu,
- sekcje, które można później skrócić.

### 7. Deployment i publikacja
- co użytkownik ma rozumieć o publikacji,
- jaki minimalny flow publikacji trzeba opisać,
- jakie checklisty są potrzebne,
- czego nie wolno zakładać bez wyjaśnienia.

### 8. Workflow AI
- co AI może wspierać,
- czego AI nie powinno zgadywać,
- jakie dokumenty agent czyta najpierw,
- co agent musi zaktualizować po zmianie.

### 9. Ryzyka i typowe błędy początkujących
- setup complexity,
- environment confusion,
- deployment uncertainty,
- documentation overload,
- błędy specyficzne dla danego rodzaju projektu.

### 10. Zasady redukcji
- co zachować obowiązkowo,
- co można skrócić,
- co można usunąć dopiero po ustabilizowaniu projektu,
- czego nie usuwać bez zastępstwa.

### 11. Następny najmniejszy krok
- jaki ruch użytkownik powinien zrobić zaraz po wyborze wariantu,
- jaki ruch powinien zrobić kolejny agent,
- co powinno pojawić się w statusie projektu.

## Wspólna logika katalogów

Nie każdy wariant będzie używał tych samych katalogów, ale poniższy model jest punktem odniesienia:

```text
/
├── README.md
├── docs/
│   ├── project/
│   ├── guides/
│   ├── templates/
│   ├── content/
│   ├── ai/
│   └── operations/
├── src/
├── public/
├── assets/
├── content/
├── config/
├── tests/
└── .github/
```

## Wspólna logika plików obowiązkowych

Wariant powinien zakładać istnienie albo jasne uzasadnienie braku dla:

- `README.md`,
- `docs/project/project-status.md`,
- `docs/project/agent-handoff.md`,
- `docs/project/source-of-truth.md`,
- `docs/project/documentation-map.md`.

Wariant może też rekomendować dodatkowo:

- `CONTRIBUTING.md`,
- `SECURITY.md`,
- `CODE_OF_CONDUCT.md`,
- `.github/ISSUE_TEMPLATE/`,
- `.github/pull_request_template.md`,
- `.env.example`,
- `devcontainer.json`,
- dokument deploymentu,
- dokument pracy z AI dla danego celu.

## Jak odróżniać warianty od siebie

Warianty nie mogą różnić się tylko nazwą. Muszą różnić się co najmniej w tych obszarach:

- priorytetami README,
- strukturą quick startu,
- zakresem dokumentacji pomocniczej,
- typem assetów i treści,
- logiką deploymentu,
- logiką AI workflow,
- zakresem rzeczy, które można bezpiecznie okroić.

## Jak oceniać jakość nowego wariantu

Nowy wariant jest gotowy dopiero wtedy, gdy:

- wiadomo, dla kogo jest,
- wiadomo, co użytkownik robi najpierw,
- wiadomo, które pliki są obowiązkowe,
- wiadomo, jak ma wyglądać pierwszy sukces,
- wiadomo, jak AI ma pracować bez zgadywania,
- wiadomo, co można później uprościć,
- wiadomo, jak ten wariant różni się od pozostałych.
