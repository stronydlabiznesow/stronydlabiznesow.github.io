# Strona — korepetycje (build gotowy do wdrożenia)

To jest gotowy, zbudowany (static) folder strony — można go wrzucić bezpośrednio
na GitHub Pages, Netlify, Vercel albo dowolny hosting statyczny.

## Wrzucenie na GitHub (GitHub Pages)

1. Utwórz nowe repozytorium na GitHub (np. `korepetycje-strona`).
2. W tym folderze zainicjuj repo i wypchnij zawartość:
   ```bash
   git init
   git add .
   git commit -m "Pierwsza wersja strony"
   git branch -M main
   git remote add origin https://github.com/<twoj-uzytkownik>/<nazwa-repo>.git
   git push -u origin main
   ```
3. W ustawieniach repozytorium: **Settings → Pages → Source** wybierz branch `main`
   i folder `/ (root)`, zapisz.
4. Po chwili strona będzie dostępna pod adresem
   `https://<twoj-uzytkownik>.github.io/<nazwa-repo>/`.

## Zawartość

- `index.html` — strona główna (zawiera nowy ekran ładowania z animowanym,
  odręcznym napisem).
- `assets/` — zbudowane pliki JS/CSS oraz zdjęcie.
- `belka.html` — osadzalny przykład animacji (belka statycznie wyznaczalna).
- `favicon.ico`, `robots.txt`.

## Numer telefonu

Numer kontaktowy (`+48 694 072 521`) jest ustawiony w linkach `tel:` oraz
w przycisku WhatsApp na dole strony.
