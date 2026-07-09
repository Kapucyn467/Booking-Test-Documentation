# Test Report – Booking.com Search Module

## Informacje ogólne

| Pole | Wartość |
|------|----------|
| Projekt | Booking.com |
| Moduł | Wyszukiwarka noclegów |
| Tester | Kacper Dyrcz |
| Data rozpoczęcia testów | 01.07.2026 |
| Data zakończenia testów | 02.07.2026 |
| Wersja aplikacji | Produkcyjna |
| Typ testów | Manualne |

---

# Cel testów

Celem testów było sprawdzenie poprawności działania wyszukiwarki Booking.com oraz weryfikacja najważniejszych funkcjonalności związanych z wyszukiwaniem obiektów noclegowych.

---

# Zakres testów

Przetestowano:

- ✅ wyszukiwanie lokalizacji
- ✅ wybór dat pobytu
- ✅ wybór liczby gości
- ✅ wyszukiwanie bez podania lokalizacji
- ✅ walidację pól formularza
- ✅ działanie filtrów
- ✅ sortowanie wyników

Nie testowano:

- ❌ wydajności
- ❌ bezpieczeństwa
- ❌ kompatybilności mobilnej

---

# Wyniki testów

| Status | Liczba |
|---------|--------:|
| Wszystkie przypadki testowe | 20 |
| Zaliczone | 18 |
| Niezaliczone | 2 |
| Zablokowane | 0 |

---

# Wykryte błędy

| ID | Priorytet | Status | Opis |
|----|-----------|--------|------|
| BUG-001 | Medium | Open | Możliwość wyszukania bez podania lokalizacji |
| BUG-002 | Low | Open | Niepoprawne wyświetlanie komunikatu walidacyjnego |

---

# Podsumowanie

W trakcie testów wykonano 20 przypadków testowych.

Większość funkcjonalności działa zgodnie z oczekiwaniami. Wykryto dwa błędy, które nie uniemożliwiają korzystania z aplikacji, jednak wymagają poprawy.

Nie wykryto błędów krytycznych.

---

# Rekomendacje

- poprawić walidację formularza wyszukiwania,
- zweryfikować komunikaty błędów,
- po wdrożeniu poprawek wykonać testy regresji.

---

# Załączniki

- Test_Plan.md
- Test_Cases.md
- Bug_Report.md