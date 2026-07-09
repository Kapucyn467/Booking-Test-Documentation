#  Test Plan – Wyszukiwarka Booking.com

##  Cel dokumentu

Celem działań testowych jest dostarczenie interesariuszom informacji o jakości testowanego produktu oraz wykrycie ewentualnych nieprawidłowości przed jego wdrożeniem.

Dokument zawiera plan testów dla modułu wyszukiwarki serwisu *Booking.com*. Określa zakres testów, środowisko testowe, kryteria wejścia i wyjścia, harmonogram oraz narzędzia wykorzystywane podczas procesu testowego.

---

#  Zakres testów

## Typy testów objęte planem

- ✅ Testy funkcjonalne
- ✅ Testy walidacji
- ✅ Testy eksploracyjne

## Typy testów nieobjęte planem

- ❌ Testy automatyczne
- ❌ Testy bezpieczeństwa
- ❌ Testy kompatybilności mobilnej

---

#  Przedmiot testów

Przedmiotem testów jest moduł wyszukiwarki serwisu *Booking.com*.

Zakres obejmuje weryfikację:

- wyszukiwania lokalizacji,
- walidacji wymaganych pól,
- wyboru dat pobytu,
- wyboru liczby gości,
- poprawności prezentowanych wyników wyszukiwania.

---

#  Kryteria zaliczenia testów

Testy zostaną uznane za zakończone, jeżeli:

- wykonano wszystkie zaplanowane przypadki testowe,
- wszystkie błędy o priorytecie *Critical* i *High* zostały naprawione lub zaakceptowane,
- podstawowe funkcjonalności działają zgodnie z wymaganiami.

---

#  Kryteria wejścia

Przed rozpoczęciem testów:

- zakończono implementację modułu wyszukiwarki,
- środowisko testowe jest dostępne,
- dostępna jest aktualna wersja aplikacji,
- dostępna jest dokumentacja funkcjonalna.

# 🏁 Kryteria wyjścia

Po zakończeniu testów:

- wykonano 100% zaplanowanych przypadków testowych,
- przygotowano raport z testów,
- zweryfikowano wszystkie błędy krytyczne,
- zakończono retesty zgłoszonych błędów.

---

#  Środowisko testowe

### Środowisko

*QA*

### System operacyjny

- Windows 11 Pro 64-bit

### Przeglądarki

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Opera
- Safari

---

#  Harmonogram testów

## Testy funkcjonalne

- Analiza wymagań – około *3 godziny*
- Wykonanie przypadków testowych – około *1 godziny*
- Analiza wyników testów

---

#  Raportowanie wyników

Raport z testów zawiera:

- liczbę wykonanych przypadków testowych,
- status wykonania testów,
- listę wykrytych błędów,
- podsumowanie procesu testowego.

---

#  Narzędzia

- TestLink
- Jira
- BrowserStack

---

#  Zarządzanie błędami

Każdy wykryty błąd jest zgłaszany w systemie *Jira*.

Zgłoszenie zawiera:

- tytuł błędu,
- opis problemu,
- kroki reprodukcji,
- oczekiwany rezultat,
- rzeczywisty rezultat,
- priorytet,
- załączniki (np. zrzuty ekranu).

Po naprawieniu błędu wykonywany jest *retest* oraz – w razie potrzeby – *testy regresji*.

---

#  Role i odpowiedzialność

| Rola | Odpowiedzialność |
|------|------------------|
| Tester Manualny | Projektowanie przypadków testowych |
| Tester Manualny | Wykonywanie testów |
| Tester Manualny | Raportowanie błędów |
| Tester Manualny | Przygotowanie raportu z testów |

---

#  Ryzyka

- zmiany wymagań podczas testów,
- niedostępność środowiska testowego,
- ograniczony czas na wykonanie testów,
- błędy uniemożliwiające wykonanie części scenariuszy.

---

#  Podsumowanie

Projekt został wykonany samodzielnie w celu rozwijania umiejętności z zakresu *testowania manualnego*.

Podczas realizacji projektu wykorzystałem:

- projektowanie przypadków testowych,
- planowanie procesu testowego,
- dokumentowanie wyników testów,
- raportowanie błędów,
- pracę z narzędziami *TestLink*, *Jira* oraz *BrowserStack*.