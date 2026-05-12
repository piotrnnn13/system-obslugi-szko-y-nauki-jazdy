# System Zarządzania Szkołą Nauki Jazdy

## Opis projektu

System informatyczny wspomagający organizację szkoły nauki jazdy. Aplikacja umożliwia zarządzanie kursantami, instruktorami, wykładowcami, pojazdami, płatnościami oraz harmonogramem zajęć teoretycznych i praktycznych.

Celem projektu jest usprawnienie działania szkoły jazdy poprzez cyfryzację procesów administracyjnych i organizacyjnych.

---

# Metadane projektu

| Pole                  | Wartość                                                                |
| --------------------- | ---------------------------------------------------------------------- |
| Nazwa projektu        | System Zarządzania Szkołą Nauki Jazdy                                  |
| Typ projektu          | System informatyczny / aplikacja webowa                                |
| Przeznaczenie         | Organizacja pracy szkoły jazdy                                         |
| Główne technologie    | SQL, system bazodanowy, backend, frontend                              |
| Użytkownicy systemu   | Kursant, Instruktor, Wykładowca, Administracja                         |
| Zakres projektu       | Zarządzanie kursami, płatnościami, harmonogramem i postępami kursantów |
| Główna funkcjonalność | Rezerwacja i zarządzanie zajęciami online                              |
| Status projektu       | Projekt akademicki                                                     |

---

# Cel projektu

Celem projektu jest stworzenie systemu informatycznego wspomagającego organizację szkoły nauki jazdy. System umożliwia:

* zarządzanie kursantami,
* zarządzanie instruktorami,
* zarządzanie pojazdami,
* planowanie zajęć teoretycznych i praktycznych,
* monitorowanie postępów kursantów,
* obsługę płatności,
* internetową rezerwację zajęć.

---

# Zakres systemu

System obejmuje:

* rejestrację kursantów, instruktorów i wykładowców,
* zarządzanie kursami prawa jazdy,
* planowanie zajęć teoretycznych i praktycznych,
* monitorowanie postępów kursantów,
* obsługę płatności za kursy,
* zarządzanie flotą pojazdów,
* harmonogram zajęć,
* obsługę egzaminów wewnętrznych.

---

# Role użytkowników

## Kursant

* zapis na kurs,
* podgląd harmonogramu,
* rezerwacja jazd,
* śledzenie postępów,
* podgląd płatności.

## Instruktor

* zarządzanie jazdami praktycznymi,
* podgląd harmonogramu,
* aktualizacja postępów kursanta,
* obsługa przypisanych pojazdów.

## Wykładowca

* prowadzenie wykładów,
* zarządzanie zajęciami teoretycznymi,
* aktualizacja postępów kursantów.

## Administracja

* zarządzanie użytkownikami,
* zarządzanie kursami,
* zarządzanie płatnościami,
* zarządzanie pojazdami,
* organizacja harmonogramu.

---

# Wymagania funkcjonalne

## Kursanci

* rejestracja kursanta,
* edycja danych kursanta,
* usuwanie kursanta,
* przypisanie kursu,
* monitorowanie postępów,
* obsługa egzaminów wewnętrznych.

## Instruktorzy i pojazdy

* dodawanie instruktorów,
* edycja danych instruktorów,
* przypisywanie pojazdów,
* zarządzanie flotą pojazdów.

## Płatności

* rejestracja płatności,
* obsługa różnych metod płatności,
* śledzenie statusu płatności,
* przypisanie płatności do kursanta i kursu.

## Zajęcia praktyczne

* planowanie jazd,
* przypisanie instruktora,
* przypisanie kursanta,
* aktualizacja postępów.

## Zajęcia teoretyczne

* planowanie wykładów,
* przypisywanie wykładowców,
* przypisywanie kursantów,
* aktualizacja postępów.

---

# Model danych

## Główne encje

* Kursant
* Kurs
* Instruktor
* Wykładowca
* Pojazd
* Płatność
* Jazda praktyczna
* Wykład
* Postęp

---

# Relacje biznesowe

* Kursant posiada dokładnie jeden kurs.
* Kurs może mieć jednego lub wielu kursantów.
* Instruktor może mieć przypisany jeden lub wiele pojazdów.
* Pojazd jest przypisany do jednego instruktora.
* Kursant może realizować wiele płatności.
* Każda płatność dotyczy jednego kursanta i jednego kursu.
* Jazda praktyczna posiada dokładnie jednego instruktora i jednego kursanta.
* Wykład może być uczęszczany przez wielu kursantów.
* Wykład prowadzony jest przez dokładnie jednego wykładowcę.
* Postępy kursanta są aktualizowane przez wykłady oraz jazdy praktyczne.

---

# Przykładowe technologie

## Backend

* Java / Spring Boot
* ASP.NET
* Node.js

## Frontend

* React
* Angular
* Vue

## Baza danych

* PostgreSQL
* MySQL
* SQL Server

---

# Możliwe rozszerzenia

* system powiadomień SMS/email,
* integracja z płatnościami online,
* aplikacja mobilna,
* raporty i statystyki,
* eksport danych do PDF/Excel,
* integracja z systemami egzaminacyjnymi.

---

# Autor

Projekt wykonany w celach edukacyjnych.
 Instruktor, Wykładowca, Administ |
