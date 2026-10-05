# Naturalnie. Karina Zontek – strona internetowa

Strona mobilnego gabinetu kosmetologii i naturoterapii **„Naturalnie. Karina Zontek”**.

🌍 **Adres:** [naturalnie-karinazontek.pl](http://naturalnie-karinazontek.pl)
📱 **Instagram:** [@karina_zontek_naturalnie](https://instagram.com/karina_zontek_naturalnie)

## 🌿 O projekcie

Statyczna, w pełni responsywna strona zbudowana w czystym HTML5, CSS3 i odrobinie JavaScriptu (bez frameworków i bez procesu budowania).

* **Przyklejony nagłówek** z logo i menu „hamburger” na telefonach.
* **Wspólny arkusz stylów** – zmiana wyglądu w jednym miejscu dla wszystkich podstron.
* **Zoptymalizowane grafiki** – zdjęcia w WebP/JPG zamiast wielomegabajtowych PNG (strona ładuje się wielokrotnie szybciej).
* **Dostępność i SEO** – semantyczne znaczniki, opisy `meta`, Open Graph, favicon, link „Przejdź do treści”, obsługa klawiatury.

### Paleta kolorów marki

| Kolor | HEX | Zastosowanie |
|---|---|---|
| Szałwiowa zieleń | `#CCD8C7` | nagłówki podstron, sekcje CTA, akcenty, ikony |
| Głęboki morski | `#17687A` | sekcja powitalna, stopka, przyciski, nagłówki |
| Kość słoniowa | `#faf9f6` | tło strony, menu |

Kolory zdefiniowane są jako zmienne CSS na początku `assets/css/style.css` (`--sage`, `--sea`, `--ivory`).

### Typografia

Google Fonts: *Libre Baskerville* (nagłówki) i *Lato* (tekst).

## 📂 Struktura repozytorium

```
.
├── index.html          # Strona główna
├── o-mnie.html         # O mnie – misja, wykształcenie, doświadczenie
├── zabiegi.html        # Opis zabiegów
├── cennik.html         # Cennik
├── kontakt.html        # Kontakt i mapa
└── assets/
    ├── css/
    │   └── style.css   # Wszystkie style strony
    ├── js/
    │   └── main.js     # Menu mobilne, animacje, rok w stopce
    └── img/
        ├── karina-zontek.webp / .jpg   # Zdjęcie Kariny
        ├── logo-morski.png             # Logo w kolorze morskim (nagłówek)
        ├── logo-biale.png              # Logo białe (sekcja powitalna, stopka)
        ├── favicon.png                 # Ikona karty przeglądarki
        └── og-image.jpg                # Grafika do udostępniania w social mediach
```

## ✏️ Jak edytować

* **Tekst / ceny** – edytuj bezpośrednio odpowiedni plik `.html`.
* **Wygląd** – `assets/css/style.css`.
* **Nagłówek i stopka** są powtórzone w każdym pliku HTML – przy zmianie (np. numeru telefonu) zaktualizuj wszystkie pięć plików.
* **Nowe zdjęcia** – dodaj do `assets/img/`, najlepiej przeskalowane do ok. 1000–1600 px szerokości.

## 🚀 Podgląd lokalny

Pobierz repozytorium (`Code` → `Download ZIP`), wypakuj i otwórz `index.html` w przeglądarce. Struktura folderów musi zostać zachowana.
