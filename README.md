# Todo List Application
## Opis projektu
- Aplikacja Todo List to interfejs użytkownika oparty na JavaScript, który komunikuje się z zewnętrznym API w celu zarządzania zadaniami i ich operacjami. Aplikacja umożliwia tworzenie, edytowanie, usuwanie oraz aktualizowanie zadań i operacji na zadaniach. Dane są pobierane i zapisywane za pomocą zapytań HTTP do API.

## Technologie
- HTML, CSS, JavaScript: Interfejs użytkownika.
- Fetch API: Komunikacja z zewnętrznym API.
- Bootstrap: Biblioteka CSS do stylizacji interfejsu.
- API: https://todo-api.coderslab.pl.

## Funkcjonalności
- Lista zadań (tasks):
- Wyświetlanie listy zadań.
- Tworzenie nowego zadania.
- Usuwanie zadania.
- Zamykanie zadania (zmiana statusu na "closed").
- Operacje na zadaniach (operations):
- Wyświetlanie operacji przypisanych do zadania.
- Dodawanie nowej operacji do zadania.
- Aktualizowanie czasu poświęconego na operację.
- Usuwanie operacji z zadania.

## Wymagania
- Przeglądarka obsługująca ES6 (ECMAScript 2015) i Fetch API.

## Wymagania dotyczące API
- Authorization: Wymagany jest nagłówek Authorization z Twoim kluczem API.
- Content-Type: W przypadku zapytań POST i PUT wymagany jest nagłówek Content-Type: application/json.

## Uwagi
- Jeśli wystąpi błąd podczas komunikacji z API, sprawdź konsolę przeglądarki i zakładkę „Network” w narzędziach deweloperskich, aby zdiagnozować problem.
- Upewnij się, że Twój klucz API jest poprawny i działa.

## Autor
- Mateusz Maciejewski - Twórca projektu.

##Licencja
- Projekt jest dostępny na licencji MIT.
