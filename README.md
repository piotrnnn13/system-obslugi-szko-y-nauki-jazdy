# system-obslugi-szko-y-nauki-jazdy

 Cel: Celem projektu jest stworzenie systemu informatycznego wspomagającego organizację szkoły nauki jazdy. System będzie umożliwiać zarządzanie kursantami, instruktorami, pojazdami oraz harmonogramem zajęć teoretycznych i praktycznych. Dzięki niemu kursanci będą mogli rezerwować zajęcia online, a instruktorzy zarządzać swoimi lekcjami.
Zakres: System będzie obejmować: 
• Rejestrację kursantów, instruktorów i wykładowców. 
• Planowanie i zarządzanie lekcjami teoretycznymi oraz praktycznymi. 
• Monitorowanie postępów kursantów. 
• Obsługę płatności za kursy. 
• Zarządzanie pojazdami.
Kontekst: System przeznaczony jest dla kursanta, instruktora i pracownika administracji szkoły nauki jazdy.
Wymagania funkcjonalne: 
• Rejestracja kursantów (imię, nazwisko, nr telefonu, adres, nr PESEL, nr PKK, status wewnętrznego egzaminu teoretycznego, status wewnętrznego egzaminu praktycznego) w systemie wraz z wyborem ich kursu (edycja, kategoria, kwota, liczba godzin teoretycznych, liczba godzin praktycznych). Kursant musi posiadać dokładnie jeden kurs, a kurs ma jednego lub wielu kursantów. 
• Zarządzanie kursantami (dodawanie, edycja, usuwanie). 
• Zarządzanie instruktorami (nr ewidencyjny, imię, nazwisko, uprawnienia, adres, nr telefonu) oraz pojazdami (marka, model, kategoria, numer rejestracyjny). Instruktor ma przypisany jeden lub wiele pojazdów, ale pojazd jest przypisany
• Moduł płatności (nr PKK, status, metoda płatności, data, kwota). Każda płatność musi mieć dokładnie jednego kursanta, który jej dokonuje oraz dokładnie jeden kurs, którego dotyczy. Kursant realizuje zero lub wiele płatności. 
• Zarządzanie zajęciami praktycznymi (id lekcji, data, godz. rozpoczęcia, godz. zakończenia). Instruktor prowadzi zero lub jedne zajęcia, ale jazdy mają dokładnie jednego instruktora. Kursant uczestniczy w jednych lub w wielu jazdach. Zajęcia mają dokładnie jednego kursanta. Wykonana jazda nadpisuje poczyniony postęp dokładnie raz, ale postęp może być nadpisywany przez zero lub wiele jazd. Jazda dotyczy dokładnie jednego kursu. 
• Zarządzanie zajęciami teoretycznymi (id wykładu, data, godz. rozpoczęcia, godz. zakończenia). Każdy wykład jest uczęszczany przez 0 lub wielu kursantów (z czego każdy z nich może uczęszczać na 0 lub wiele wykładów), prowadzony przez dokładnie jednego wykładowcę (który może prowadzić kilka wykładów) oraz uaktualnia 0 lub wiele postępów. Postęp natomiast jest uaktualniany przez 0 lub więcej wykładów. Wykład dotyczy dokładnie jednego kursu.
