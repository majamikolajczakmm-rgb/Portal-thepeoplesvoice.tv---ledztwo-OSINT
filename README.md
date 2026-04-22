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
| **Badane źródło** | thepeoplesvoice.tv |
| **Narzędzia** | BuiltWith (Relationship) |
| **Kluczowe ustalenia** | Identyczne kody Google AdSense oraz Analytics łączące badany portal z zablokowanymi domenami. |


#### Dowód wizualny: Wykaz współdzielonych atrybutów technicznych (BuiltWith)

<img width="736" height="543" alt="image" src="https://github.com/user-attachments/assets/bcbaeb71-0d33-46ad-b0d5-1cc08b065a1f" />
<img width="1038" height="746" alt="image" src="https://github.com/user-attachments/assets/20e9585c-b541-4294-b337-00c8ea0c96fe" />
<img width="992" height="750" alt="image" src="https://github.com/user-attachments/assets/e7e61c34-7b3f-48fb-a21d-ef6a07fff234" />


### Refleksja śledcza

Analiza profilu relacji w narzędziu BuiltWith ujawniła cyfrowy ślad, identyfikator **Google AdSense (CA-PUB-3980300725513096)**. 
Fakt, że ten sam identyfikator płatności jest przypisany do `The People's Voice`, jak i do portali takich jak `detroitdailynews.com` czy `tipsto.live`, rzuca nowe światło na charakter witryny. Mamy tu do czynienia z modelem **"Pink Slime Journalism"**, czyli zjawiskiem tworzenia dziesiątek stron udających lokalne serwisy informacyjne, które w rzeczywistości są zarządzane centralnie w celu masowego zarabiania na reklamach i manipulowania zasięgami. 


### Krok 3: Analiza historyczna i demaskowanie mechanizmu rebrandingu

**Cel:** Udokumentowanie ewolucji portalu oraz wykazanie bezpośredniej ciągłości między thepeoplesvoice.tv a podmiotami wcześniej zbanowanymi za szerzenie dezinformacji.

| Atrybut | Szczegóły |
| :--- | :--- |
| **Data weryfikacji** | 21 kwietnia 2026 |
| **Badane źródła** | yournewswire.com, newspunch.com, thepeoplesvoice.tv |
| **Narzędzia** | Wayback Machine |
| **Kluczowe ustalenia** | Potwierdzenie ciągłości autorskiej i prawnej; znalezienie śladów nazwy "The People's Voice" już w 2017 roku pod innym szyldem. |

[Ewolucja 2017-2024]
<img width="1875" height="861" alt="image" src="https://github.com/user-attachments/assets/342ec694-43a1-4785-b7e1-417077ce1ae3" />
<img width="1380" height="675" alt="image" src="https://github.com/user-attachments/assets/c014ff29-0e99-4226-a355-8d9f74074855" />
<img width="1895" height="868" alt="image" src="https://github.com/user-attachments/assets/5850d713-315e-48c4-a2b1-bcaf777785f5" />
<img width="1885" height="862" alt="image" src="https://github.com/user-attachments/assets/b6d355c6-966e-4350-a5dc-de20537fc617" />

[Stopka 2017]
<img width="1318" height="347" alt="image" src="https://github.com/user-attachments/assets/8fdf52f4-2ce8-4c56-9a00-ea84ba10ab6a" />


### Refleksja śledcza
Analiza archiwalnych wersji witryny przy użyciu Wayback Machine pozwoliła na ostateczne powiązanie badanego portalu z jego przeszłością. Najważniejszym odkryciem w tej fazie jest stopka strony `yournewswire.com` z **marca 2017 roku**. Widnieje w niej zapis: **"Copyright © 2017 The People’s Voice, Inc."**. Dowodzi to, że obecna nazwa portalu nie jest nowym bytem, lecz nazwą spółki matki, która zarządzała operacją już 7 lat temu.

Gdy portal *Your News Wire* stał się zbyt rozpoznawalny dla organizacji fact-checkingowych i zaczął tracić zasięgi przez bany na Facebooku, właściciele (Sean Adl-Tabatabai i Baxter Dmitry) dokonali "ucieczki domenowej". Najpierw przenieśli treści na `newspunch.com` (co widać na screenach z 2020 r.), a ostatecznie na `thepeoplesvoice.tv`.

Mimo zmiany logotypów i domen, "DNA" portalu pozostaje identyczne:
**1. Ciągłość personalna:** Te same nazwiska redaktorów od 2017 roku.
**2. Ciągłość wizualna:** Agresywny styl nagłówków, charakterystyczne czcionki i recykling tych samych teorii spiskowych.
**3. Ciągłość prawna:** Ta sama firma (The People's Voice, Inc.) widniejąca w dokumentach od lat.







