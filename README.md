# Portal thepeoplesvoice.tv – Analiza techniczna, chronologia rebrandingu i badanie autentyczności źródeł informacji

**Autor:** Maja Mikołajczak **Data:** Kwiecień 2026

**Wstęp do projektu**

Portal thepeoplesvoice.tv (wcześniej znany jako Your News Wire) jest identyfikowany przez organizacje fact-checkingowe jako jedno z głównych źródeł dezinformacji w języku angielskim. Niniejszy notatnik analityczny dokumentuje proces śledczy mający na celu wykazanie braku transparentności portalu oraz analizę jego cyfrowej ewolucji.

**Pytanie badawcze:**
   *Jakie ślady cyfrowe pozostawione przez twórców thepeoplesvoice.tv świadczą o braku transparentności portalu i w jaki sposób rebranding z 'Your News Wire' wpłynął na omijanie systemów weryfikacji faktów?*


### Krok 1. Identyfikacja i analiza rekordów domenowych

**Cel:** Ustalenie struktury własnościowej, daty powstania infrastruktury oraz fizycznej lokalizacji podmiotu zarządzającego portalem.

| Atrybut | Szczegóły |
| :--- | :--- |
| **Data weryfikacji** | 20 kwietnia 2026 |
| **Badane źródło** | thepeoplesvoice.tv |
| **Narzędzia** | Terminal (WHOIS), ICANN Lookup |
| **Kluczowe ustalenia** | Całkowita anonimizacja danych, ślad w Arizonie (USA), domena aktywna od 2013 r. |


#### Dowód wizualny: Wynik zapytania WHOIS
```bash
# Komenda wywołana w terminalu:
whois thepeoplesvoice.tv
```

<img width="1064" height="184" alt="{89ED91DE-8284-4685-A122-8AB490FFDED6}" src="https://github.com/user-attachments/assets/6fcf05ca-2c99-4e8a-ab4c-f7cc7e685d99" />
<img width="443" height="103" alt="{33D30DCD-EF46-4E19-9478-A2E6CC9A3CDF}" src="https://github.com/user-attachments/assets/b2e3add7-84a1-4bcc-ab56-45ae93ee31ae" />
<img width="506" height="88" alt="{729AC28B-A413-4358-AB71-47320B1263CC}" src="https://github.com/user-attachments/assets/2ba514de-7928-48c4-b7fc-53fda8f6bee2" />

### Refleksja śledcza
Pierwszy etap dochodzenia przyniósł kilka nieoczywistych wniosków. Choć portal The People’s Voice zyskał na znaczeniu w ostatnich latach, analiza rekordów wskazuje, że domena została zarejestrowana już w czerwcu 2013 roku. Sugeruje to dwa scenariusze: albo operacja ma znacznie dłuższą historię, niż podają oficjalne źródła, albo właściciele przejęli istniejącą domenę o ugruntowanej pozycji (SEO), by uwiarygodnić swoje działania.
Uwagę zwraca również skrajny brak transparentności. Prawie każde pole dotyczące właściciela zostało zastąpione frazą REDACTED FOR PRIVACY, w przypadku portalu mieniącego się „źródłem niezależnego dziennikarstwa”, ukrywanie tożsamości redakcji podważa jej autentyczność. Jedynym konkretnym śladem geograficznym jest stan Arizona (USA), co stanowi punkt wyjścia do dalszej analizy powiązań z amerykańskimi sieciami dezinformacyjnymi. Całość infrastruktury jest chroniona przez Cloudflare, co skutecznie maskuje realne IP serwera i uniemożliwia prostą lokalizację hostingu.

### Krok 2: Analiza powiązań infrastrukturalnych i identyfikacja "cyfrowych odcisków palców"

**Cel:** Wykazanie ukrytych powiązań technicznych między portalem thepeoplesvoice.tv a innymi witrynami dezinformacyjnymi przy użyciu identyfikatorów usług reklamowych i analitycznych.

| Atrybut | Szczegóły |
| :--- | :--- |
| **Data weryfikacji** | 20 kwietnia 2026 |
| **Badane źródło** | thepeoplesvoice.tv, yournewswire.com |
| **Narzędzia** | BuiltWith (Relationship Profile) |
| **Kluczowe ustalenia** | Identyczne kody Google AdSense oraz Analytics łączące badany portal z zablokowanymi domenami. |


#### Dowód wizualny: Wykaz współdzielonych atrybutów technicznych (BuiltWith)

<img width="736" height="543" alt="image" src="https://github.com/user-attachments/assets/bcbaeb71-0d33-46ad-b0d5-1cc08b065a1f" />
<img width="1038" height="746" alt="image" src="https://github.com/user-attachments/assets/20e9585c-b541-4294-b337-00c8ea0c96fe" />
<img width="992" height="750" alt="image" src="https://github.com/user-attachments/assets/e7e61c34-7b3f-48fb-a21d-ef6a07fff234" />

<img width="731" height="588" alt="image" src="https://github.com/user-attachments/assets/10c3d1c7-0dca-415c-9421-725f87a6b5a7" />
<img width="1064" height="733" alt="image" src="https://github.com/user-attachments/assets/339df71d-a1f7-415f-b344-20901075e6e6" />

### Refleksja śledcza
Dzięki analizie narzędziem BuiltWith udało się odnaleźć współdzielone atrybuty. Portal *The People's Voice* korzysta z identycznego identyfikatora **Google AdSense (CA-PUB-3980300725513096)** co szereg innych witryn, w tym m.in. `detroitdailynews.com` czy `tipsto.live`. 

Co więcej, odnaleziony kod **Google Analytics (UA-53594309)** jest bezpośrednio powiązany z portalem `yournewswire.com` – pierwotną wersją serwisu, która została zablokowana w mediach społecznościowych za masowe szerzenie dezinformacji. Fakt, że te same kody śledzące są aktywne jeszcze w marcu 2025 roku, dowodzi ciągłości operacyjnej. Właściciele nie zamknęli działalności, a jedynie dokonali rebrandingu, aby omijać algorytmy weryfikujące prawdę. To klasyczny model "farmy newsów", gdzie jeden podmiot zarządza siecią stron udających lokalne media.




### 3. Wayback Machine






