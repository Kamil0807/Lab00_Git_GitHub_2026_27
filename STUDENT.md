# Moje wykonanie Lab00

- Login GitHub / pseudonim: Kamil0807
- System i terminal (np. Windows + WSL Ubuntu): Windows + Visual Studio Code Terminal (CMD / PowerShell)
- Edytor / IDE: Visual Studio Code
- Wersja Git: 2.56.0.windows.1
- Wersja kompilatora C++: g++.exe (Rev13, Built by MSYS2 project) 15.2.0
- Wersje java i javac: java version "25" 2025-09-16 LTS; javac 25
- Link do pierwszego PR (uzupełnij w zadaniu 5): https://github.com/Kamil0807/Lab00_Git_GitHub_2026_27/pull/1

## Uruchomienie lokalne
Wynik programu C++:
Hello from C++! Author: Kamil0807
Wynik programu Java:
Hello from Java! Author: Kamil0807

## Błąd i poprawka (zadanie 5)
- Krótki fragment komunikatu błędu i numer linii: cpp/main.cpp:5:61: error: expected ';' before 'return'
- Przyczyna oraz sposób naprawy: Celowe usunięcie średnika ; na końcu instrukcji wypisującej tekst w cpp/main.cpp. Sposób naprawy: ponowne dopisanie średnika na końcu linii 5.
- Commit z błędem (SHA lub link): 30e7b24
- Czy Actions pokazały błąd, a po naprawie sukces? Tak, na gałęzi lab00-debug po wprowadzeniu błędu Actions zgłosiło błąd, a po wysłaniu poprawki testy zakończyły się sukcesem

## Krótkie odpowiedzi
1. Co różni commit od push? Commit zapisuje zmiany lokalnie w historii Git na komputerze. Push wysyła te zapisane lokalnie commity do zdalnego repozytorium na GitHubie.
2. Dlaczego po scaleniu PR wykonuję lokalnie pull? Scalenie PR następuje na serwerach GitHuba, więc lokalna gałąź main na komputerze nie ma jeszcze tych zmian. Komenda git pull pobiera i aktualizuje lokalne repozytorium o najnowszą wersję z serwera.
3. Co potwierdza zielony wynik naszego CI, a czego nie potwierdza? 
Potwierdza: Że kod bez błędów kompiluje się i prawidłowo uruchamia w czystym środowisku testowym (Linux) na GitHubie.
Nie potwierdza: Poprawności konfiguracji środowiska na lokalnym komputerze studenta ani pełnej poprawności logicznej całego programu.

## Ewentualne problemy środowiska
Brak / opis problemu i sposób rozwiązania: Brak
