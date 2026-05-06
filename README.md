# Universal E-mail Signature Template for Gov/Edu

Uniwersalny szablon stopki e-mail dla instytucji publicznych (urzędy, szkoły, uczelnie).  
Zaprojektowany tak, aby jeden plik HTML mógł być łatwo dostosowany do dowolnej instytucji przez zastąpienie oznaczonych znaczników.

Gotowy przykład wypełnionego szablonu: [`template-signature-example.html`](template-signature-example.html)

---

## Szybki start

1. Otwórz plik `template-signature-generic.html` w edytorze tekstowym (np. Notepad++, VS Code).
2. Użyj **Znajdź i zamień** (`Ctrl+H`), aby zastąpić każdy znacznik `[...]` właściwą wartością — lista poniżej.
3. Opcjonalnie zmień kolor przewodni (domyślnie `#003366`) na kolor instytucji.
4. Wklej gotową stopkę do klienta pocztowego jako podpis HTML.

---

## Znaczniki do uzupełnienia

### Pracownik

| Znacznik | Opis |
|---|---|
| `[IMIĘ I NAZWISKO]` | Imię i nazwisko pracownika |
| `[STANOWISKO]` | Stanowisko / funkcja pracownika |
| `[NUMER TELEFONU]` | Numer telefonu, np. `+48 75 781 23 45 wewn. 100` |
| `[EMAIL@DOMENA.PL]` | Służbowy adres e-mail pracownika |

### Instytucja

| Znacznik | Opis |
|---|---|
| `[URL_LOGO]` | Bezpośredni URL do pliku graficznego logo (png/jpg) — **opcjonalne**, jeśli brak logo usuń całe `<td>` z logo z pliku |
| `[NAZWA INSTYTUCJI]` | Pełna nazwa instytucji |
| `[ADRES INSTYTUCJI]` | Ulica, kod pocztowy, miejscowość |
| `[URL_WWW]` | Adres strony internetowej, np. `https://nazwa.pl` |
| `[ETYKIETA_WWW]` | Tekst wyświetlanego linku, np. `www.nazwa.pl` |
| `[URL_BIP]` | Adres BIP, np. `https://bip.nazwa.pl` — **opcjonalne**, jeśli brak BIP usuń fragment `| BIP: [ETYKIETA_BIP]` |
| `[ETYKIETA_BIP]` | Tekst wyświetlanego linku BIP, np. `bip.nazwa.pl` |

### Klauzula RODO

| Znacznik | Opis |
|---|---|
| `[ADMINISTRATOR DANYCH]` | Pełna nazwa podmiotu będącego administratorem danych |
| `[PEŁNA NAZWA INSTYTUCJI]` | Pełna nazwa instytucji / siedziby |
| `[TYTUŁ KIEROWNIKA]` | Tytuł i stanowisko, np. `Dyrektora Szkoły Podstawowej nr 1` |
| `[ADRES INSTYTUCJI]` | Adres siedziby, np. `ul. Rynek 1, 59-620 Gryfów Śląski` |
| `[TEL INSTYTUCJI]` | Telefon główny instytucji |
| `[EMAIL SEKRETARIATU]` | Adres e-mail sekretariatu |
| `[URL_RODO]` | Link do strony z informacją o przetwarzaniu danych osobowych |

---

## Zmiana koloru

Domyślny kolor przewodni to `#003366` (granatowy).

Aby zmienić kolor na własny:
1. Otwórz plik w edytorze.
2. Użyj **Znajdź i zamień** (`Ctrl+H`).
3. Znajdź: `#003366`
4. Zamień na: wybrany kolor w formacie HEX, np. `#005A2B` (zieleń), `#8B0000` (bordo).

---

## Jak wkleić podpis do klienta pocztowego

### Outlook (Windows)
1. **Plik → Opcje → Poczta → Podpisy**
2. Kliknij **Nowy**, nadaj nazwę.
3. Kliknij przycisk **\</\>** (Edytor HTML) lub otwórz plik `.htm` bezpośrednio.
4. Wklej zawartość pliku i zapisz.

### Thunderbird
1. Otwórz **Ustawienia konta → Podpis**.
2. Zaznacz **Użyj HTML**.
3. Wklej zawartość pliku do pola podpisu.

### Gmail / Google Workspace
1. Otwórz **Ustawienia (⚙) → Ogólne → Podpis → Utwórz nowy**.
2. Skopiuj zawartość pliku HTML i wklej do pola podpisu.
   - Dla dokładniejszego wyniku skorzystaj z rozszerzenia przeglądarki umożliwiającego wklejanie HTML, np. *"Signature HTML editor"*.

---

## Licencja

MIT — szczegóły w pliku [LICENSE](LICENSE).
