# Porównanie modeli sztucznej inteligencji

## 1. Generowanie kodu

**Prompt:**

Napisz w Pythonie prosty program, który pobiera dwie liczby, oblicza ich sumę i wyświetla wynik. Dodaj komentarze po polsku.



**ChatGPT:**

Oto prosty program w Pythonie, który pobiera dwie liczby od użytkownika, oblicza ich sumę i wyświetla wynik. Wszystkie komentarze są po polsku.

python
```
# Pobranie pierwszej liczby od użytkownika
liczba1 = float(input("Podaj pierwszą liczbę: "))

# Pobranie drugiej liczby od użytkownika
liczba2 = float(input("Podaj drugą liczbę: "))

# Obliczenie sumy dwóch liczb
suma = liczba1 + liczba2

# Wyświetlenie wyniku
print("Suma podanych liczb wynosi:", suma)
```

### Jak działa program?

1. `input()` pobiera dane wpisane przez użytkownika.
2. `float()` zamienia wprowadzony tekst na liczbę, dzięki czemu można dodawać również liczby dziesiętne.
3. Operator `+` oblicza sumę dwóch liczb.
4. `print()` wyświetla wynik na ekranie.

### Przykład działania

text
```
Podaj pierwszą liczbę: 5
Podaj drugą liczbę: 3
Suma podanych liczb wynosi: 8.0
```

Wskazówka: Jeśli chcesz, aby program obsługiwał wyłącznie liczby całkowite, zamień `float()` na `int()`.



**Google Gemini:**

Oto prosty program w Pythonie, który pobiera od użytkownika dwie liczby, sumuje je i wyświetla wynik.

```python
# Program pobierający dwie liczby od użytkownika i obliczający ich sumę

# Pobranie pierwszej liczby od użytkownika (używamy float, aby obsługiwać zarówno liczby całkowite, jak i zmiennoprzecinkowe)
liczba1 = float(input("Wprowadź pierwszą liczbę: "))

# Pobranie drugiej liczby od użytkownika
liczba2 = float(input("Wprowadź drugą liczbę: "))

# Obliczenie sumy podanych liczb
suma = liczba1 + liczba2

# Wyświetlenie wyniku na ekranie
print(f"Suma liczb {liczba1} i {liczba2} wynosi: {suma}")

```

### Jak to działa?

* **`input()`**: Pozwala na wpisanie danych przez użytkownika w konsoli.
* **`float()`**: Konwertuje tekst wpisany przez użytkownika na liczbę (dzięki temu program działa poprawnie również dla ułamków, np. `2.5`).
* **Formatowanie f-string (`print(f"...")`)**: Umożliwia łatwe wstawienie zmiennych bezpośrednio do tekstu wyświetlanego na ekranie.



**Devin:**

Oto prosty program w Pythonie:

```python
# Program dodający dwie liczby

# Pobranie pierwszej liczby od użytkownika
a = float(input("Podaj pierwszą liczbę: "))

# Pobranie drugiej liczby od użytkownika
b = float(input("Podaj drugą liczbę: "))

# Obliczenie sumy dwóch liczb
suma = a + b

# Wyświetlenie wyniku na ekranie
print("Suma wynosi:", suma)
```

Jak działa:

- `input()` pobiera dane od użytkownika jako tekst, a `float()` zamienia je na liczbę (obsługuje też liczby dziesiętne). Jeśli chcesz tylko liczby całkowite, użyj `int()`.
- `suma` przechowuje wynik dodawania.
- `print()` wyświetla wynik.

Przykładowe uruchomienie:

```
Podaj pierwszą liczbę: 5
Podaj drugą liczbę: 3
Suma wynosi: 8.0
```

---

## 2. Informacje o lekturze

**Prompt:**

Opisz bohaterów lektury „Kamienie na szaniec” Aleksandra Kamińskiego. Podaj ich imiona i nazwiska, cechy charakteru, przykładowe wydarzenia oraz trzy motywy literackie.



**ChatGPT:**

[Tutaj wklej odpowiedź]



**Google Gemini:**

[Tutaj wklej odpowiedź]



**Devin:**

„Kamienie na szaniec" (1943) Aleksandra Kamińskiego to książka o konspiracyjnej działalności harcerzy Szarych Szeregów w okupowanej Warszawie. Bohaterowie opisani są pod pseudonimami:

## Główni bohaterowie

**Rudy – Jan Bytnar** (pseudonim „Rudy")
- Cechy: zdolny, bystry, opanowany, dobry organizator; harcmistrz, odpowiedzialny za innych
- Wydarzenia: aresztowany przez Gestapo w marcu 1943 r., brutalnie przesłuchiwany w al. Szucha (zapamiętał i przekazał rozmówcom śpiew „Dni pracy"), zginął w czasie akcji „Arsenał" — trafił do transportu i skonał po torturach mimo odbicia

**Zośka – Tadeusz Zawadzki** (pseudonim „Zośka")
- Cechy: ujmująco skromny, charyzmatyczny przywódca, idealista, pełen poświęcenia; dyrektor Małego Sabotażu i dowódca akcji
- Wydarzenia: organizował akcje Waweru (malowanie emblematów), dowodził akcją „Arsenał" (odbicie „Rudego"), zginął w akcji pod Siecychem („Taśma") w sierpniu 1943 r.

**Alek – Maciej Aleksy Dawidowski** (pseudonim „Alek")
- Cechy: wesoły, odważny, zdolny technicznie, dusza towarzystwa; stawiał sprawę wyżej niż życie
- Wydarzenia: wziął udział w odbiciu „Rudego", zginął od ran odniesionych w akcji „Arsenał" (dowiódł odwagą, wracając po broń mimo ran), zmarł w kwietniu 1943 r.

## Trzy motywy literackie

1. **Patriotyzm i poświęcenie dla ojczyzny** – bohaterowie świadomie ryzykują życie w konspiracji, traktują walkę jako obowiązek pokolenia (akcja „Arsenał", udział w Małym Sabotażu).
2. **Przyjaźń i kolektyw** – więź trzech przyjaciół, wspólne działanie drużyny; solidarność wyraża się w gotowości do śmierci za kolegów (odbicie „Rudego").
3. **Dojrzewanie i tragedia pokolenia** („Kolumbowie") – młodzi ludzie muszą dorosnąć w wojnie; kontrast między normalną młodością (nauka, miłość) a życiem w konspiracji; motyw ofiary i wczesnej śmierci.

Warto dodać, że książka ma charakter dokumentalny — Kamiński (bohaterowie nazywali go „Kamyk") opisał prawdziwych ludzi i realne wydarzenia, co wzmacnia autentyczność opowieści.

---

## 3. Wyszukiwanie informacji

**Prompt:**

Wyjaśnij, jak działa recykling odpadów w Polsce. Podaj pięć informacji o segregacji i roli gmin. Dołącz wiarygodne linki do źródeł.



**ChatGPT:**

[Tutaj wklej odpowiedź i linki]

**Google Gemini:**

[Tutaj wklej odpowiedź i linki]



**Devin:**

## Jak działa recykling odpadów w Polsce

System gospodarki odpadami opiera się na ustawie o utrzymaniu czystości i porządku w gminach oraz ustawie o odpadach. Gmina odpowiada za odbiór odpadów komunalnych od mieszkańców, a segregacja u źródła (w domu) jest obowiązkowa.

## Pięć kluczowych informacji

1. **Obowiązkowa segregacja 5 frakcji** – od 2022 r. obowiązuje jednolity system kolorów pojemników w całej Polsce:
   - żółty – metale i tworzywa sztuczne,
   - niebieski – papier,
   - zielony – szkło,
   - brązowy – bioodpady,
   - czarny (lub szary) – odpady zmieszane/pozostałości.
   Niektóre gminy mają dodatkowe frakcje (np. tekstylia, przydomowe odpady niebezpieczne).

2. **Gmina organizuje i finansuje system** – gminy przeprowadzają przetargi na odbiór odpadów, ustalają harmonogramy i stawki opłat za gospodarowanie odpadami, które mieszkańcy płacą zwykle za osobę lub za metr sześcienny zużytej wody. Właściciele nieruchomości mają obowiązek przystąpić do systemu.

3. **Wyższa opłata za brak segregacji** – jeśli właściciel nieruchomości nie segreguje, gmina może naliczyć opłatę podwyższoną (często 2- lub 4-krotnie wyższą), co jest narzędziem zachęcającym do segregacji.

4. **PSZOK i odpady problemowe** – gminy prowadzą Punkty Selektywnego Zbierania Odpadów Komunalnych, gdzie bezpłatnie można oddać m.in. elektroodpady, baterie, meble, opony i odpady niebezpieczne (farby, leki, chemikalia).

5. **Cele recyklingu i weryfikacja** – gminy muszą osiągać ustawowe poziomy recyklingu i przygotowania do ponownego użycia odpadów komunalnych (docelowo 55% w 2025 r., 60% w 2030 r., 65% w 2035 r. według prawa UE). Za nieosiągnięcie poziomów grożą kary z wojewódzkiego funduszu ochrony środowiska.

## Źródła

- Ustawa z dnia 13 września 1996 r. o utrzymaniu czystości i porządku w gminach: https://isap.sejm.gov.pl/isap.nsf/DocDetails.xsp?id=WDU19961320622
- Ustawa z dnia 14 grudnia 2012 r. o odpadach: https://isap.sejm.gov.pl/isap.nsf/DocDetails.xsp?id=WDU20130000021
- Ministerstwo Klimatu i Środowiska – gospodarka odpadami: https://www.gov.pl/web/klimat/gospodarka-odpadami
- Dyrektywa ramowa 2008/98/WE (cele recyklingu UE): https://eur-lex.europa.eu/legal-content/PL/TXT/?uri=CELEX%3A32008L0098
- Informator o segregacji (jednolity system kolorów): https://www.gov.pl/web/klimat/segregacja-odpadow

---

## 4. Tworzenie obrazu

**Prompt:**

Wygeneruj realistyczną ilustrację biblioteki przyszłości w 2050 roku. Dodaj regały z książkami, robota, interaktywne ekrany, rośliny i duże okna. Zastosuj szeroki kadr 16:9, bez napisów.



**ChatGPT:**

[Tutaj wstaw obraz]



**Google Gemini:**

[Tutaj wstaw obraz]



**Devin:**

[Tutaj wstaw obraz]

---

## 5. Tworzenie dokumentu HTML do druku

**Prompt:**

Utwórz dokument HTML do wydruku na jednej stronie A4 pod tytułem „Potwierdzenie przyjęcia dokumentu”. Uwzględnij nazwę i adres instytucji, dane osoby przekazującej, datę, nazwę dokumentu, liczbę załączników, numer sprawy, miejsce na uwagi oraz pola na podpis osoby przekazującej i przyjmującej. Dodaj style CSS do druku.



**ChatGPT:**

[Tutaj wklej kod HTML]



**Google Gemini:**

[Tutaj wklej kod HTML]



**Devin:**

```html
<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Potwierdzenie przyjęcia dokumentu</title>
<style>
  /* ===== Ustawienia strony i druku ===== */
  @page {
    size: A4 portrait;
    margin: 0;
  }

  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    font-family: "Segoe UI", "Helvetica Neue", Arial, sans-serif;
    font-size: 11pt;
    color: #1a1a1a;
    background: #e8e8e8;
  }

  .page {
    width: 210mm;
    height: 297mm;
    padding: 20mm 22mm;
    margin: 12px auto;
    background: #fff;
    box-shadow: 0 2px 12px rgba(0, 0, 0, 0.18);
    display: flex;
    flex-direction: column;
  }

  /* ===== Nagłówek ===== */
  header {
    text-align: center;
    border-bottom: 2.5px solid #1a1a1a;
    padding-bottom: 5mm;
    margin-bottom: 8mm;
  }

  h1 {
    font-size: 17pt;
    letter-spacing: 0.5px;
    text-transform: uppercase;
    margin-bottom: 2mm;
  }

  .subtitle {
    font-size: 9.5pt;
    color: #444;
  }

  /* ===== Sekcje formularza ===== */
  section {
    margin-bottom: 6mm;
  }

  h2 {
    font-size: 9pt;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 0.8px;
    color: #333;
    border-bottom: 1px solid #999;
    padding-bottom: 1.2mm;
    margin-bottom: 4mm;
  }

  .row {
    display: flex;
    gap: 8mm;
    margin-bottom: 4.5mm;
  }

  .field {
    display: flex;
    align-items: flex-end;
    flex: 1;
  }

  .field .label {
    font-size: 9pt;
    color: #333;
    white-space: nowrap;
    padding-right: 2.5mm;
  }

  .field .line {
    flex: 1;
    border-bottom: 1px solid #666;
    height: 7mm;
  }

  .field .line.multi {
    height: 9mm;
  }

  /* ===== Uwagi ===== */
  .notes-box {
    border: 1px solid #666;
    height: 30mm;
    padding: 2mm;
  }

  /* ===== Podpisy ===== */
  .signatures {
    margin-top: auto;
    display: flex;
    justify-content: space-between;
    gap: 20mm;
    padding-top: 6mm;
  }

  .sig {
    flex: 1;
    text-align: center;
  }

  .sig .sig-line {
    border-top: 1px solid #1a1a1a;
    padding-top: 2mm;
    font-size: 8.5pt;
    color: #444;
  }

  .sig .sig-space {
    height: 14mm;
  }

  /* ===== Stopka ===== */
  footer {
    margin-top: 6mm;
    text-align: center;
    font-size: 7.5pt;
    color: #777;
  }

  /* ===== Style do druku ===== */
  @media print {
    body {
      background: #fff;
    }

    .page {
      margin: 0;
      box-shadow: none;
      width: auto;
      height: auto;
      min-height: 257mm;
      page-break-after: avoid;
    }

    .notes-box,
    .sig .sig-line,
    .field .line {
      -webkit-print-color-adjust: exact;
      print-color-adjust: exact;
    }
  }
</style>
</head>
<body>
  <div class="page">
    <header>
      <h1>Potwierdzenie przyjęcia dokumentu</h1>
      <div class="subtitle">Formularz potwierdzający odbiór dokumentacji</div>
    </header>

    <section>
      <h2>Nazwa i adres instytucji</h2>
      <div class="row">
        <div class="field"><span class="label">Nazwa instytucji:</span><span class="line"></span></div>
      </div>
      <div class="row">
        <div class="field"><span class="label">Ulica i numer:</span><span class="line"></span></div>
        <div class="field"><span class="label">Kod pocztowy:</span><span class="line" style="max-width: 30mm;"></span></div>
        <div class="field"><span class="label">Miejscowość:</span><span class="line"></span></div>
      </div>
    </section>

    <section>
      <h2>Dane osoby przekazującej</h2>
      <div class="row">
        <div class="field"><span class="label">Imię i nazwisko:</span><span class="line"></span></div>
      </div>
      <div class="row">
        <div class="field"><span class="label">Stanowisko:</span><span class="line"></span></div>
        <div class="field"><span class="label">Jednostka / dział:</span><span class="line"></span></div>
      </div>
      <div class="row">
        <div class="field"><span class="label">Telefon:</span><span class="line"></span></div>
        <div class="field"><span class="label">E-mail:</span><span class="line"></span></div>
      </div>
    </section>

    <section>
      <h2>Dane przekazywanego dokumentu</h2>
      <div class="row">
        <div class="field"><span class="label">Nazwa dokumentu:</span><span class="line"></span></div>
      </div>
      <div class="row">
        <div class="field"><span class="label">Data przekazania:</span><span class="line" style="max-width: 40mm;"></span></div>
        <div class="field"><span class="label">Liczba załączników:</span><span class="line" style="max-width: 40mm;"></span></div>
        <div class="field"><span class="label">Numer sprawy:</span><span class="line"></span></div>
      </div>
    </section>

    <section>
      <h2>Uwagi</h2>
      <div class="notes-box"></div>
    </section>

    <div class="signatures">
      <div class="sig">
        <div class="sig-space"></div>
        <div class="sig-line">Podpis osoby przekazującej</div>
      </div>
      <div class="sig">
        <div class="sig-space"></div>
        <div class="sig-line">Podpis osoby przyjmującej</div>
      </div>
    </div>

    <footer>
      Potwierdzenie przyjęcia dokumentu — wypełnić czytelnie, drukowanymi literami
    </footer>
  </div>
</body>
</html>
```
