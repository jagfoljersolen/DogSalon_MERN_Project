## Projekt zaliczeniowy z laboratorium "Szkielety programistyczne w aplikacjach internetowych"

## Tematyka projektu: Salon Fryzjerski dla Psów - umawianie wizyt

## Funkcjonalności
- uwierzytelnienie z wykorzystaniem tokenów
- umawianie wizyty 
- przeglądanie historii wizyt
- edytowanie wizyty
- anulowanie wizyty
- walidacja po stronie klienta i serwer
- interfejs API w architekturze REST
- haszowanie haseł


## Narzędzia i technologie
- serwer: Node.js v22.12.0 + Express ^5.1.0
- klient: React ^19.1.0
- baza danych: MongoDB v8.0.10

## Wymagania
Wersje programów wykorzystane do tworzenia aplikacji (aplikacja nie została przetestowana z kompatybilnością wcześniejszych wersji):
Node.js v22.12.0
Express ^5.1.0
React ^19.1.0
MongoDB v8.0.10

## Uruchomienie
1. W katalogu głównym backendu (serwera) uruchom:
	npm install
2. W katalogu frontendowym (klienta) uruchom:
	npm install
3. Upewnij się, że MongoDB v8.0.10 jest uruchomiony lokalnie 
4. Najpierw uruchom serwer backend:
	npm start
5. Następnie uruchom frontend:
	npm start
Frontend powinien sam włączyć się w przeglądarce pod adresem http://localhost:3000 
