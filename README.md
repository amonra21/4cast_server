4cast — prognozy i podsumowania pogodowe

To aplikacja webowa umożliwiająca:
- wybór lokalizacji na mapie
- pobranie prognozy pogody na najbliższy tydzień
- wyświetlenie podsumowania tygodniowego

Projekt podzielony jest na dwie części:
frontend — React + Vite
backend — serwer Deno (z Oak), który pobiera dane z open-meteo.com i je przetwarza.

Aktualnie otwarta część to backend

Jak uruchomić projekt?
Wymagania
Node.js (>= 16)
npm
Deno (>= 1.36)

Uruchomienie backendu (Deno):
Przejdź do katalogu backendu (tam gdzie jest main.ts).
Uruchom serwer: deno run --allow-net --allow-read --allow-env main.ts

Domyślnie serwer będzie nasłuchiwał na: http://localhost:8000


Testy odpala się poprzez: deno test --allow-net