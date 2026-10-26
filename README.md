# Porównanie modeli sztucznej inteligencji

## 1. Generowanie kodu

**Prompt:**

Napisz w Pythonie prosty program, który pobiera dwie liczby, oblicza ich sumę i wyświetla wynik. Dodaj komentarze po polsku.



**ChatGPT:**

Oto prosty program w Pythonie, który pobiera dwie liczby od użytkownika, oblicza ich sumę i wyświetla wynik. Wszystkie komentarze są po polsku.

```python
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

# „Kamienie na szaniec” – bohaterowie, cechy charakteru i motywy literackie

„Kamienie na szaniec” to książka Aleksandra Kamińskiego opowiadająca o losach młodych Polaków podczas II wojny światowej. Bohaterowie, związani z harcerstwem i Szarymi Szeregami, walczą z niemieckim okupantem, ryzykując własne życie w imię wolności ojczyzny.

Głównymi bohaterami są Alek, Rudy i Zośka. Ich postawy pokazują odwagę, przyjaźń, patriotyzm i gotowość do poświęceń.

Kamienie na szaniec - Aleksander Kamiński - jak nowa | SkupSzop

## 1. Główni bohaterowie

### Alek – Maciej Aleksy Dawidowski

76 lat temu Maciej Aleksy Dawidowski Alek z Szarych Szeregów usunął z pomnika Mikołaja Kopernika w Warszawie tablicę ...

Cechy charakteru:

- Odważny i brawurowy.
- Wesoły, pogodny i pełen energii.
- Pomysłowy i zaradny.
- Patriotyczny i lojalny wobec przyjaciół.
- Gotowy do poświęceń.

Przykładowe wydarzenia:

- Zdjęcie niemieckiej tablicy z pomnika Mikołaja Kopernika w Warszawie.
- Udział w akcjach Małego Sabotażu, m.in. w malowaniu znaków Polski Walczącej.
- Udział w akcji pod Arsenałem, podczas której został ciężko ranny. Zmarł 30 marca 1943 roku.

### Rudy – Jan Bytnar

Akcja pod Arsenałem – 80. rocznica - Rocznice | dzieje.pl - Historia Polski

Cechy charakteru:

- Inteligentny i uzdolniony.
- Pracowity, dokładny i systematyczny.
- Skromny i wrażliwy.
- Odważny i wytrwały.
- Wierny swoim ideałom i przyjaciołom.

Przykładowe wydarzenia:

- Udział w akcjach Małego Sabotażu, m.in. w malowaniu symboli Polski Walczącej.
- Aresztowanie przez Gestapo 23 marca 1943 roku i brutalne przesłuchania, podczas których nie wydał swoich towarzyszy.
- Uwolnienie podczas akcji pod Arsenałem 26 marca 1943 roku. Zmarł 30 marca wskutek odniesionych obrażeń.

### Zośka – Tadeusz Zawadzki

80 lat temu w akcji pod Sieczychami poległ Tadeusz Zawadzki "Zośka"

Cechy charakteru:

- Inteligentny i ambitny.
- Odpowiedzialny i zdyscyplinowany.
- Opanowany i rozsądny.
- Wrażliwy i refleksyjny.
- Przywódczy, wierny przyjaciołom i patriotyczny.

Przykładowe wydarzenia:

- Kierowanie działaniami konspiracyjnymi i udział w akcjach przeciw okupantowi.
- Dowodzenie akcją pod Arsenałem, której celem było odbicie Rudego i innych więźniów.
- Udział w akcji pod Celestynowem, polegającej na uwolnieniu więźniów przewożonych pociągiem.
- Śmierć 20 sierpnia 1943 roku podczas akcji w Sieczychach.

## 2. Inni ważni bohaterowie

- Stanisław Broniewski „Orsza” – instruktor harcerski i dowódca akcji pod Arsenałem. Odpowiedzialny, odważny, opanowany i dobrze zorganizowany.
- Henryk Ostrowski „Heniek” – harcerz i przyjaciel bohaterów, aresztowany przez Gestapo. Jego zatrzymanie wiąże się z wydarzeniami prowadzącymi do aresztowania Rudego.
- Rodzice Rudego – Zdzisław i Zofia Bytnarowie – wspierają syna i reprezentują wartości rodzinne, patriotyzm oraz przywiązanie do zasad moralnych.

## 3. Trzy motywy literackie

File:Pomnik małego powstańca w Warszawie.jpg - Wikimedia Commons

### 1. Motyw patriotyzmu

Bohaterowie kochają ojczyznę i walczą o jej wolność mimo zagrożenia życia. Angażują się w działalność konspiracyjną i Mały Sabotaż.

Przykład: Alek zdejmuje niemiecką tablicę z pomnika Kopernika, pokazując sprzeciw wobec okupanta.

Bohaterowie Akcji pod Arsenałem - Rajd Arsenał

### 2. Motyw przyjaźni i poświęcenia

Prawdziwa przyjaźń oznacza lojalność, wzajemną pomoc i gotowość do ryzykowania własnym życiem dla drugiego człowieka.

Przykład: Akcja pod Arsenałem zostaje przeprowadzona, aby uwolnić Rudego z rąk Gestapo. Biorą w niej udział jego przyjaciele, w tym Zośka i Alek.

"Kamienie na szaniec" Aleksandra Kamińskiego - prawdziwa opowieść o bohaterach czy mit, w który uwierzyliśmy?

### 3. Motyw bohaterstwa i ofiary

Młodzi ludzie podejmują niebezpieczne działania w imię wyższych wartości. Ich odwaga wiąże się z cierpieniem i utratą życia.

Przykład: Rudy podczas tortur nie zdradza przyjaciół, a Alek i Zośka angażują się w walkę z okupantem, mimo że grozi im śmierć.

## 4. Podsumowanie – co warto zapamiętać?

| Bohater | Najważniejsze cechy | Przykład |
| --- | --- | --- |
| Alek – Maciej Aleksy Dawidowski | Odwaga, pomysłowość, pogoda ducha | Zdjęcie tablicy z pomnika Kopernika |
| Rudy – Jan Bytnar | Wytrwałość, inteligencja, wierność | Nie wydaje przyjaciół podczas przesłuchań |
| Zośka – Tadeusz Zawadzki | Odpowiedzialność, przywództwo, wrażliwość | Dowodzi akcją pod Arsenałem |

Główne przesłanie lektury: „Kamienie na szaniec” pokazują, że patriotyzm, przyjaźń i odwaga mogą wymagać najwyższej ofiary. Tytuł nawiązuje do młodych ludzi, którzy niczym kamienie rzucane na szaniec poświęcają się w obronie ojczyzny.



**Google Gemini:**

A oto szczegółowe opracowanie głównych bohaterów lektury **„Kamienie na szaniec”** Aleksandra Kamińskiego wraz z przykładami wydarzeń oraz najważniejszymi motywami literackimi.

---

## Główni bohaterowie

### 1. Jan Bytnar („Rudy”)

* **Imię i nazwisko / Pseudonim:** Jan Bytnar, pseudonim „Rudy”.
* **Cechy charakteru:**
* **Inteligentny i twórczy:** Pomysłowy, niezwykle zdolny konstruktor i majsterkowicz (zbudował m.in. kajak i zainstalował blokadę drzwi w mieszkaniu).
* **Refleksyjny i wrażliwy:** Dbał o rozwój duchowy, lubił rozmyślać i analizować świat.
* **Odważny i wierny do końca:** Niezłomny w trakcie okrutnych przesłuchań na Szucha; mimo straszliwych tortur nie wydał nikogo ze swoich przyjaciół.


* **Przykładowe wydarzenia:**
* **Słynna akcja z kotwicą:** Namalował dużą Kotwicę Polski Walczącej na Pomniku Lotnika na placu Unii Lubelskiej – wyczyn niezwykle brawurowy ze względu na bliskość posterunku policji.
* **Aresztowanie i Akcja pod Arsenałem:** Został aresztowany przez Gestapo, zmaltretowany i brutalnie przesłuchany. Odbity przez kolegów w Akcji pod Arsenałem, zmarł kilka dni później w wyniku odniesionych obrażeń.



---

### 2. Maciej Aleksy Dawidowski („Alek”)

* **Imię i nazwisko / Pseudonim:** Maciej Aleksy Dawidowski, pseudonim „Alek” (używał też pseudonimu „Glizda”).
* **Cechy charakteru:**
* **Porywczy i energiczny:** Działał impulsywnie, cechował go wysoki wzrost i niespożyta energia.
* **Opanowany w walce:** Mimo wysokiej wrażliwości potrafił zachować zimną krew w kluczowych momentach akcji.
* **Ofiarny i szczery:** Bardzo wierzący, dążący do ciągłego doskonalenia własnego charakteru.


* **Przykładowe wydarzenia:**
* **Zdjęcie niemieckiej tablicy z pomnika Mikołaja Kopernika:** Alek samowolnie, pod nosem niemieckiej komendantury (Głównego Stoiska Policji), odkręcił zasłaniającą polski napis niemiecką tablicę.
* **Uczestnictwo w Akcji pod Arsenałem:** Dowodził sekcją „Struktura” w czasie odbijania „Rudego”. Został ciężko ranny w brzuch podczas odwrotu, chroniąc kolegów, i zmarł tego samego dnia co Rudy.



---

### 3. Tadeusz Zawadzki („Zośka”)

* **Imię i nazwisko / Pseudonim:** Tadeusz Zawadzki, pseudonim „Zośka” (pseudonim nadano mu ze względu na delikatną, chłopięcą, wręcz dziewczęcą urodę).
* **Cechy charakteru:**
* **Naturalny lider i strateg:** Posiadał niezwykłe zdolności przywódcze, potrafił świetnie planować i organizować najbardziej skomplikowane akcje dywersyjne.
* **Wybitnie inteligentny i амbitny:** Wyznaczał wysokie standardy sobie i podwładnym.
* **Głęboko przywiązany do przyjaciół:** Śmierć Rudego i Alka była dla niego wielkim cosem, po którym popadł w czasową depresję i zaczął pisać wspomnienia (które stały się podstawą książki).


* **Przykładowe wydarzenia:**
* **Zaplanowanie i przeprowadzenie Akcji pod Arsenałem:** Opracował szczegółowy plan odbicia Rudego i wziął w nim udział jako dowódca.
* **Akcja pod Sieczychami:** Ostatnia akcja Zośki, mająca na celu likwidację posterunku żandarmerii niemieckiej na granicy. Akcja zakończyła się sukcesem, jednak Zośka ginie w niej jako jedyny z polskiego oddziału.



---

## 3 Najważniejsze motywy literackie

1. **Motyw przyjaźni i braterstwa:**
* Przyjaźń Alka, Rudego i Zośki oraz ich więź z harcerskim środowiskiem stanowi fundament utworu. Jest to relacja oparta na pełnym zaufaniu, lojalności i skrajnym poświęceniu (gotowość do oddania życia za drugiego człowieka, jak podczas Akcji pod Arsenałem).


2. **Motyw heroizmu i patriotyzmu:**
* Bohaterowie to młodzi ludzie, którzy musieli dojrzeć w cieniu wojny. Ich patriotyzm nie sprowadzał się do walki z bronią w ręku (Mały Sabotaż, Dywersja), ale również do walki o zachowanie polskości, własnego morale i godności.


3. **Motyw dojrzewania w czasie wojny:**
* Młodzieńcze marzenia, plany na przyszłość, pierwsze miłości i beztroska zostają zderzone z brutalną rzeczywistością okupacji. Chłopcy przechodzą szybką ewolucję – od harcerskich wybryków po dojrzałe decyzje o życiu i śmierci.



---

Czy chciałbyś omówić wybraną postać lub akcję bardziej szczegółowo?



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

# Jak działa recykling odpadów w Polsce?

Recykling to proces przetwarzania zużytych materiałów w surowce lub nowe produkty. W Polsce ważną rolę odgrywają mieszkańcy, firmy odbierające odpady, zakłady przetwarzania oraz gminy. Podstawowe zasady segregacji określa Jednolity System Segregacji Odpadów.

Portal Gov.pl

+1

## Pięć najważniejszych informacji o segregacji i roli gmin

### 1. Odpady segreguje się na pięć podstawowych frakcji

Niebieski – papier

Gazety, zeszyty, kartony i papierowe opakowania. Nie wrzucamy tu papieru zatłuszczonego lub mocno zabrudzonego.

Żółty – metale i tworzywa sztuczne

Plastikowe butelki, puszki, metalowe opakowania i kartony po napojach.

Zielony – szkło

Szklane butelki i słoiki. W niektórych gminach szkło bezbarwne i kolorowe zbiera się osobno.

Brązowy – bioodpady

Resztki roślinne, obierki warzyw i owoców oraz odpady z pielęgnacji ogrodu, zgodnie z lokalnymi zasadami.

Czarny lub szary – odpady zmieszane

Pozostałe odpady, których nie można umieścić w innych frakcjach. Nie powinny tu trafiać odpady niebezpieczne.

Źródło: Ministerstwo Klimatu i Środowiska – [zasady segregacji odpadów](<https://www.gov.pl/web/klimat/segregacjaodpadow?utm_source=chatgpt.com>). Kolory i szczegółowe zasady warto sprawdzić w swojej gminie.

Portal Gov.pl

+1

### 2. Segregacja umożliwia odzyskiwanie surowców

Po odebraniu odpady trafiają do odpowiednich instalacji, gdzie mogą być dodatkowo sortowane i przygotowywane do przetworzenia. Z papieru produkuje się m.in. papier z recyklingu, ze szkła – nowe opakowania, a z części tworzyw sztucznych – nowe wyroby.

Nie wszystkie odpady nadają się do recyklingu. Zanieczyszczenia i pomieszanie materiałów mogą utrudniać ich przetwarzanie. Dlatego ważne jest prawidłowe segregowanie już w domu.

Portal Gov.pl

+1

### 3. Gminy organizują system odbioru odpadów

Do obowiązków gmin należy organizowanie lokalnego systemu gospodarowania odpadami komunalnymi. W praktyce obejmuje to m.in. ustalanie zasad odbioru, organizację odbierania odpadów oraz informowanie mieszkańców, jak je segregować.

Gminy określają też lokalne rozwiązania dotyczące opłat i harmonogramów odbioru, zgodnie z obowiązującymi przepisami.

ISAP

+1

### 4. Gminy prowadzą Punkty Selektywnego Zbierania Odpadów Komunalnych (PSZOK)

PSZOK-i pozwalają mieszkańcom oddawać odpady, których nie należy wyrzucać do zwykłych pojemników, np.:

- zużyty sprzęt elektroniczny i elektryczny,
- odpady wielkogabarytowe, np. stare meble,
- farby i inne odpady problemowe, zgodnie z zasadami danego punktu,
- zużytą odzież i tekstylia.

Od 2025 roku gminy muszą zapewniać możliwość selektywnego zbierania tekstyliów. Szczegółowe zasady i lokalizację punktów można znaleźć na stronie urzędu gminy.

Portal Gov.pl

+1

### 5. Gminy kontrolują system, a mieszkańcy mają obowiązek segregacji

Gminy organizują gospodarowanie odpadami i monitorują działanie systemu. Mieszkańcy natomiast powinni przestrzegać zasad selektywnego zbierania odpadów. W przypadku niewłaściwej segregacji mogą zostać zastosowane podwyższone opłaty, na zasadach określonych w ustawie.

Dodatkowo od 1 października 2025 roku działa w Polsce system kaucyjny dla wybranych opakowań po napojach. Oznaczone opakowania można zwracać w punktach zbiórki, aby odzyskać kaucję.

ISAP

+1

## Jak przebiega recykling? W skrócie

1. Segregacja w domu

Mieszkaniec umieszcza odpady we właściwych pojemnikach.

2. Odbiór i transport

Firma odbiera odpady zgodnie z harmonogramem.

3. Sortowanie i przetwarzanie

Odpady są rozdzielane i przygotowywane do odzysku surowców.

4. Powstawanie nowych produktów

Odzyskane materiały mogą posłużyć do produkcji nowych przedmiotów.

## Wiarygodne źródła i linki

1. [Ministerstwo Klimatu i Środowiska – segregacja odpadów](<https://www.gov.pl/web/klimat/segregacjaodpadow?utm_source=chatgpt.com>) – zasady segregacji, PSZOK-i i tekstylia.
2. [Ministerstwo Klimatu i Środowiska – Jednolity System Segregacji Odpadów](<https://www.gov.pl/web/klimat/segregacjaodpadow-system?utm_source=chatgpt.com>) – kolory pojemników i podstawowe frakcje.
3. [Internetowy System Aktów Prawnych – ustawa o utrzymaniu czystości i porządku w gminach](<https://isap.sejm.gov.pl/isap.nsf/DocDetails.xsp?id=WDU20250000733&utm_source=chatgpt.com>) – podstawa prawna obowiązków gmin i mieszkańców.
4. [Ministerstwo Klimatu i Środowiska – pytania i odpowiedzi dotyczące segregacji](<https://www.gov.pl/web/edukacja-ekologiczna/pytania-i-odpowiedzi?utm_source=chatgpt.com>) – praktyczne wskazówki dotyczące sortowania odpadów.

Podsumowanie: skuteczny recykling w Polsce zależy od prawidłowej segregacji przez mieszkańców, sprawnego odbioru i przetwarzania odpadów oraz dobrej organizacji systemu przez gminy. Dzięki temu można ograniczyć ilość śmieci trafiających na składowiska i oszczędzać surowce naturalne.

**Google Gemini:**

Recykling w Polsce opiera się na **Jednolitym Systemie Segregacji Odpadów (JSSO)** oraz zasadzie tzw. **Rowerowej/Hierarchii Sposobów Postępowania z Odpadami**, w której priorytetem jest zapobieganie powstawaniu śmieci, a w drugiej kolejności ich odzysk i przetwórstwo.

Cały proces w praktyce polega na podzieleniu śmieci w gospodarstwach domowych, ich odbiorze, transportowaniu do sortowni oraz instalacji przetwarzania (gdzie trafiają do odzysku surowcowego lub recyklingu), a na końcu unieszkodliwieniu pozostałości, których nie da się przetworzyć.

---

## 5 kluczowych informacji o segregacji i roli gmin

1. **Jednolity System Segregacji Odpadów (JSSO):**
W całej Polsce obowiązuje podział na 5 podstawowych frakcji (kolorów pojemników):
* **Niebieski:** Papier
* **Żółty:** Metale i tworzywa sztuczne (oraz opakowania wielomateriałowe)
* **Zielony:** Szkło (opakowaniowe)
* **Brązowy:** Bioodpady (pochodzenia roślinnego)
* **Czarny/Szary:** Odpady zmieszane (to, czego nie da się wysegregować, z wyłączeniem odpadów niebezpiecznych).


2. **Obowiązkowe Punkty Selektywnego Zbierania (PSZOK):**
Każda gmina w Polsce ma prawny obowiązek utworzenia i utrzymywania co najmniej jednego **PSZOK-u**. Jest to miejsce, do którego mieszkańcy mogą bezpłatnie oddać odpady problematyczne i niebezpieczne, takie jak: meble, gabaryty, sprzęt RTV/AGD, przeterminowane leki, chemikalia czy zużyte opony.
3. **Gmina jako organizator i zarządca systemu:**
Zgodnie z ustawą o utrzymaniu czystości i porządku w gminach, gospodarowanie odpadami komunalnymi należy do zadań własnych samorządu. Gminy wybierają w przetargach firmy wywozowe, ustalają tzw. „opłatę śmieciową”, pobierają deklaracje od mieszkańców oraz kontrolują prawidłowość wywozu i przetwarzania śmieci.
4. **Wymagane poziomy recyklingu i kary:**
Unia Europejska i polskie prawo nakładają na gminy obowiązek osiągania z roku na rok coraz wyższych poziomów przygotowania odpadów do ponownego użycia i recyklingu (np. do 2025 r. poziom ten wynosi min. 55%). Jeśli gmina nie osiągnie wyznaczonych progów, grożą jej wysokie kary finansowe.
5. **Różnicowanie opłat i powszechność segregacji:**
Segregacja odpadów jest w Polsce obowiązkowa dla wszystkich mieszkańców. Osoby lub wspólnoty, które nie wywiązują się z tego obowiązku i wyrzucają surowce do odpadów zmieszanych, muszą liczyć się z podwyższoną opłatą za wywóz śmieci (tzw. opłatą karną), ustalaną przez radę gminy.

---

## Wiarygodne źródła wiedzy

Więcej oficjalnych informacji i wytycznych znajdziesz na stronach rządowych:

* 🌿 [Portal Gov.pl – Zasady segregacji odpadów (JSSO)](https://www.gov.pl/web/klimat/segregacjaodpadow) – oficjalne zestawienie Ministerstwa Klimatu i Środowiska dotyczące prawidłowego podziału śmieci.
* 📜 [Portal Gov.pl – Jednolity System Segregacji Odpadów](https://www.gov.pl/web/klimat/poznaj-jednolity-system-segregacji-odpadow) – szczegółowe informacje o podstawach prawnych i standardach pojemników.
* 🏛️ [LEX / Ustawa o utrzymaniu czystości i porządku w gminach](https://sip.lex.pl/akty-prawne/dzu-dziennik-ustaw/utrzymanie-czystosci-i-porzadku-w-gminach-16797931/roz-2) – treść ustawy określającej bezpośrednie zadania i obowiązki gmin w zakresie gospodarki odpadami.

Czy chciałbyś dowiedzieć się więcej o konkretnym pojemniku, działaniu PSZOK-u w Twojej okolicy lub o systemie kaucyjnym?



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

[chatgpt.png](chatgpt.png)



**Google Gemini:**

[gemini.png](gemini.png)



**Devin:**

[devin.png](devin.png)

---

## 5. Tworzenie dokumentu HTML do druku

**Prompt:**

Utwórz dokument HTML do wydruku na jednej stronie A4 pod tytułem „Potwierdzenie przyjęcia dokumentu”. Uwzględnij nazwę i adres instytucji, dane osoby przekazującej, datę, nazwę dokumentu, liczbę załączników, numer sprawy, miejsce na uwagi oraz pola na podpis osoby przekazującej i przyjmującej. Dodaj style CSS do druku.



**ChatGPT:**

<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Potwierdzenie przyjęcia dokumentu</title>
  <style>
    :root {
      --ink: #172033;
      --muted: #5b6474;
      --line: #9aa3b2;
      --light: #e8edf3;
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      background: #eef1f5;
      color: var(--ink);
      font-family: Arial, Helvetica, sans-serif;
      font-size: 10.5pt;
      line-height: 1.35;
    }

    .sheet {
      width: 210mm;
      min-height: 297mm;
      margin: 12mm auto;
      padding: 15mm 17mm 14mm;
      background: #fff;
      box-shadow: 0 2mm 8mm rgba(20, 30, 50, .12);
    }

    .institution {
      display: grid;
      grid-template-columns: 1fr 55mm;
      gap: 8mm;
      padding-bottom: 7mm;
      border-bottom: 1.5px solid var(--ink);
    }

    .institution h2 {
      margin: 0 0 2mm;
      font-size: 11pt;
      letter-spacing: .04em;
      text-transform: uppercase;
    }

    .institution p {
      margin: 1mm 0;
      color: var(--muted);
    }

    .logo-placeholder {
      min-height: 23mm;
      border: 1px dashed var(--line);
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 3mm;
      color: var(--muted);
      text-align: center;
      font-size: 9pt;
    }

    h1 {
      margin: 9mm 0 2mm;
      text-align: center;
      font-size: 19pt;
      line-height: 1.2;
      letter-spacing: .015em;
    }

    .subtitle {
      margin: 0 0 8mm;
      text-align: center;
      color: var(--muted);
      font-size: 9.5pt;
    }

    .section-title {
      margin: 6mm 0 3mm;
      padding-bottom: 1.5mm;
      border-bottom: 1px solid var(--light);
      font-size: 10pt;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: .045em;
    }

    .grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 5mm 8mm;
    }

    .field { min-width: 0; }

    .field.full { grid-column: 1 / -1; }

    .label {
      display: block;
      margin-bottom: 1.5mm;
      color: var(--muted);
      font-size: 9pt;
    }

    .write-line {
      min-height: 7mm;
      border-bottom: 1px solid var(--line);
    }

    .write-box {
      min-height: 22mm;
      border: 1px solid var(--line);
      border-radius: 1mm;
    }

    .declaration {
      margin: 7mm 0 0;
      padding: 4mm 4.5mm;
      border-left: 3px solid var(--ink);
      background: #f6f8fa;
      font-size: 9.5pt;
    }

    .signatures {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 18mm;
      margin-top: 15mm;
    }

    .signature-space {
      height: 17mm;
      border-bottom: 1px solid var(--ink);
    }

    .signature-label {
      margin-top: 2mm;
      text-align: center;
      font-size: 9pt;
      color: var(--muted);
    }

    .footer {
      margin-top: 9mm;
      padding-top: 3mm;
      border-top: 1px solid var(--light);
      display: flex;
      justify-content: space-between;
      gap: 8mm;
      color: var(--muted);
      font-size: 8pt;
    }

    @page {
      size: A4 portrait;
      margin: 0;
    }

    @media print {
      html, body {
        width: 210mm;
        height: 297mm;
        margin: 0;
        padding: 0;
        background: #fff;
        print-color-adjust: exact;
        -webkit-print-color-adjust: exact;
      }

      .sheet {
        width: 210mm;
        height: 297mm;
        min-height: 0;
        margin: 0;
        padding: 14mm 16mm 12mm;
        box-shadow: none;
        overflow: hidden;
      }

      .no-print { display: none !important; }
    }

    @media screen and (max-width: 700px) {
      .sheet {
        width: 100%;
        min-height: 0;
        margin: 0;
        padding: 24px;
      }
      .institution { grid-template-columns: 1fr; }
      .grid { grid-template-columns: 1fr; }
      .field.full { grid-column: auto; }
      .signatures { gap: 10mm; }
    }
  </style>
</head>
<body>
  <main class="sheet">
    <header class="institution">
      <div>
        <h2>Nazwa instytucji</h2>
        <p>Pełna nazwa jednostki / urzędu</p>
        <p>Ulica i numer, kod pocztowy, miejscowość</p>
        <p>Telefon / e-mail (opcjonalnie)</p>
      </div>
      <div class="logo-placeholder">Miejsce na logo<br>lub pieczęć instytucji</div>
    </header>

    <h1>Potwierdzenie przyjęcia dokumentu</h1>
    <p class="subtitle">Potwierdzenie odbioru dokumentu i ewentualnych załączników</p>

    <div class="section-title">Dane przyjęcia</div>
    <section class="grid">
      <div class="field">
        <span class="label">Data przyjęcia</span>
        <div class="write-line"></div>
      </div>
      <div class="field">
        <span class="label">Numer sprawy / znak sprawy</span>
        <div class="write-line"></div>
      </div>
    </section>

    <div class="section-title">Osoba przekazująca dokument</div>
    <section class="grid">
      <div class="field full">
        <span class="label">Imię i nazwisko / nazwa podmiotu</span>
        <div class="write-line"></div>
      </div>
      <div class="field full">
        <span class="label">Adres (opcjonalnie)</span>
        <div class="write-line"></div>
      </div>
    </section>

    <div class="section-title">Przyjęty dokument</div>
    <section class="grid">
      <div class="field full">
        <span class="label">Nazwa / tytuł dokumentu</span>
        <div class="write-line"></div>
      </div>
      <div class="field">
        <span class="label">Liczba załączników</span>
        <div class="write-line"></div>
      </div>
      <div class="field">
        <span class="label">Liczba stron dokumentu (opcjonalnie)</span>
        <div class="write-line"></div>
      </div>
    </section>

    <div class="section-title">Uwagi</div>
    <div class="write-box" aria-label="Miejsce na uwagi"></div>

    <p class="declaration">
      Potwierdza się przyjęcie wskazanego powyżej dokumentu wraz z liczbą załączników
      wpisaną w niniejszym formularzu. Potwierdzenie dotyczy odbioru dokumentu i nie
      stanowi oceny jego treści ani kompletności merytorycznej.
    </p>

    <section class="signatures">
      <div>
        <div class="signature-space"></div>
        <div class="signature-label">Podpis osoby przekazującej</div>
      </div>
      <div>
        <div class="signature-space"></div>
        <div class="signature-label">Podpis osoby przyjmującej / pieczęć</div>
      </div>
    </section>

    <footer class="footer">
      <span>Egzemplarz dla osoby przekazującej / do dokumentacji</span>
      <span>Formularz potwierdzenia odbioru</span>
    </footer>
  </main>
</body>
</html>



**Google Gemini:**

<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Potwierdzenie przyjęcia dokumentu</title>
    <style>
        /* Style ogólne i podglądu */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        /* Strona A4 */
        .page {
            width: 210mm;
            height: 297mm;
            background-color: #fff;
            padding: 20mm;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        /* Nagłówek */
        .header {
            display: flex;
            justify-content: space-between;
            border-bottom: 2px solid #2c3e50;
            padding-bottom: 15px;
            margin-bottom: 25px;
        }

        .institution-details {
            font-size: 14px;
            line-height: 1.5;
        }

        .institution-name {
            font-weight: bold;
            font-size: 16px;
            color: #2c3e50;
            margin-bottom: 5px;
        }

        .date-location {
            text-align: right;
            font-size: 14px;
        }

        /* Tytuł */
        .title {
            text-align: center;
            margin: 20px 0 30px 0;
        }

        .title h1 {
            font-size: 22px;
            text-transform: uppercase;
            letter-spacing: 1px;
            color: #2c3e50;
        }

        .case-number {
            font-size: 14px;
            color: #666;
            margin-top: 5px;
        }

        /* Sekcje formularza */
        .section {
            margin-bottom: 20px;
        }

        .section-title {
            font-size: 14px;
            font-weight: bold;
            color: #2c3e50;
            border-bottom: 1px solid #ddd;
            padding-bottom: 4px;
            margin-bottom: 12px;
            text-transform: uppercase;
        }

        .grid-2 {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
        }

        .field {
            margin-bottom: 12px;
        }

        .field label {
            display: block;
            font-size: 12px;
            color: #555;
            margin-bottom: 4px;
            font-weight: bold;
        }

        .field-value {
            font-size: 14px;
            padding: 8px;
            border: 1px solid #ccc;
            border-radius: 4px;
            min-height: 36px;
            background-color: #fafafa;
        }

        .notes-box {
            min-height: 100px;
            border: 1px solid #ccc;
            border-radius: 4px;
            padding: 10px;
            font-size: 14px;
            background-color: #fafafa;
        }

        /* Sekcja podpisów */
        .signatures {
            margin-top: 40px;
            display: flex;
            justify-content: space-between;
        }

        .signature-box {
            width: 45%;
            text-align: center;
        }

        .signature-line {
            border-top: 1px dashed #333;
            margin-top: 60px;
            padding-top: 5px;
            font-size: 12px;
            color: #555;
        }

        /* Przycisk drukowania (ukryty podczas druku) */
        .print-btn {
            position: fixed;
            top: 20px;
            right: 20px;
            padding: 10px 20px;
            background-color: #2c3e50;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 14px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }

        .print-btn:hover {
            background-color: #34495e;
        }

        /* Style do druku */
        @media print {
            body {
                background-color: #fff;
                padding: 0;
            }

            .page {
                box-shadow: none;
                width: 100%;
                height: 100vh;
                padding: 0;
            }

            .print-btn {
                display: none;
            }

            .field-value, .notes-box {
                background-color: #fff;
            }

            @page {
                size: A4;
                margin: 20mm;
            }
        }
    </style>
</head>
<body>

    <button class="print-btn" onclick="window.print()">Drukuj dokument</button>

    <div class="page">
        <div>
            <!-- Nagłówek -->
            <div class="header">
                <div class="institution-details">
                    <div class="institution-name">Urząd Miejski / Instytucja</div>
                    <div>ul. Przykładowa 123</div>
                    <div>00-001 Warszawa</div>
                    <div>Tel.: (22) 123 45 67</div>
                </div>
                <div class="date-location">
                    Miejscowość: Warszawa<br>
                    Data: 26.10.2026 r.
                </div>
            </div>

            <!-- Tytuł dokumentu -->
            <div class="title">
                <h1>Potwierdzenie Przyjęcia Dokumentu</h1>
                <div class="case-number">Numer sprawy: <strong>UM/2026/01027/K</strong></div>
            </div>

            <!-- Dane osoby przekazującej -->
            <div class="section">
                <div class="section-title">Dane osoby przekazującej</div>
                <div class="grid-2">
                    <div class="field">
                        <label>Imię i Nazwisko / Nazwa firmy:</label>
                        <div class="field-value">Jan Kowalski</div>
                    </div>
                    <div class="field">
                        <label>PESEL / NIP:</label>
                        <div class="field-value">84011212345</div>
                    </div>
                </div>
                <div class="field">
                    <label>Adres zamieszkania / Siedziby:</label>
                    <div class="field-value">ul. Słoneczna 15/4, 00-001 Warszawa</div>
                </div>
            </div>

            <!-- Szczegóły dokumentu -->
            <div class="section">
                <div class="section-title">Informacje o przyjętym dokumencie</div>
                <div class="field">
                    <label>Nazwa / Tytuł dokumentu:</label>
                    <div class="field-value">Wniosek o wydanie pozwolenia na budowę</div>
                </div>
                <div class="grid-2">
                    <div class="field">
                        <label>Liczba załączników:</label>
                        <div class="field-value">4</div>
                    </div>
                    <div class="field">
                        <label>Forma przekazania:</label>
                        <div class="field-value">Osobiście / Papierowa</div>
                    </div>
                </div>
            </div>

            <!-- Uwagi -->
            <div class="section">
                <div class="section-title">Uwagi / Dodatkowe informacje</div>
                <div class="notes-box">
                    Dokumenty przyjęte w oryginale. Załącznik nr 3 zawiera projekt budowlany w 3 egzemplarzach. Opłata skarbowa uiszczona.
                </div>
            </div>
        </div>

        <!-- Podpisy -->
        <div class="signatures">
            <div class="signature-box">
                <div class="signature-line">
                    Podpis osoby przekazującej
                </div>
            </div>
            <div class="signature-box">
                <div class="signature-line">
                    Pieczęć i podpis osoby przyjmującej
                </div>
            </div>
        </div>
    </div>

</body>
</html>



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
