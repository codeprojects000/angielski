# Mój angielski

Aplikacja do nauki angielskiego: słówka i zdania z tłumaczeniem, wymową po polsku, fiszki z inteligentnym powtarzaniem, gramatyka, testy i pomoc AI.

## Uruchomienie na GitHub Pages
1. Wrzuć wszystkie pliki z tego folderu do repozytorium (Add file → Upload files).
2. Settings → Pages → Source: „Deploy from a branch”, branch `main`, folder `/ (root)`.
3. Po chwili aplikacja działa pod adresem `https://<twoj-login>.github.io/<nazwa-repo>/`.

## Konfiguracja (wszystko poza kodem)
- **Klucze AI** (Gemini, Groq, OpenAI) wpisujesz w aplikacji w ⚙️ Ustawienia. Są zapisywane tylko w przeglądarce danego urządzenia, nie w pliku ani w repozytorium.
- **Baza w chmurze (Firebase, opcjonalnie):** w pliku `index.html` na górze uzupełnij obiekt `firebaseConfig` danymi z konsoli Firebase. Dopóki jest pusty, słówka zapisują się tylko na tym urządzeniu.

## Pliki
- `index.html` – cała aplikacja
- `manifest.webmanifest`, `sw.js`, `icon-*.png`, `apple-touch-icon.png` – instalacja na telefonie (ekran główny)
