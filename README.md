# Fluo
System magazynowo-sprzedażowy rozwijany i prowadzony przez **Golpin sp. z o.o.**
(NIP 5911724053). W Allegro Developer Apps zarejestrowany jako aplikacja
**Golpin Magazyn** — tę nazwę niesie nagłówek `User-Agent`, którym program
przedstawia się API: `GolpinMagazyn/<wersja> (+https://github.com/Zaczykl/Fluo-info)`.

## Do czego służy
Obsługuje sprzedaż internetową: pobiera zamówienia, prowadzi magazyn i stany,
synchronizuje liczbę sztuk w ofertach, nadaje przesyłki (Wysyłam z Allegro),
wystawia dokumenty sprzedaży, prowadzi zwroty oraz korespondencję z kupującymi
— wiadomości, dyskusje i reklamacje.

## Kto z niego korzysta
Golpin sp. z o.o. do sprzedaży własnej oraz dwa inne podmioty, których towar
leży w magazynie Golpin i których zamówienia Golpin kompletuje i wysyła.
Każde konto sprzedażowe autoryzuje program samodzielnie (OAuth, device flow)
i w każdej chwili może tę zgodę cofnąć.

## Zakres korzystania z Allegro REST API
Program pobiera wyłącznie dane kont, które go autoryzowały: zamówienia, własne
oferty tych kont, rozliczenia, korespondencję oraz dyskusje i reklamacje.
Nie pobiera danych ofert innych sprzedawców, nie prowadzi scrapingu i nie
przekazuje treści z Allegro do innych serwisów.

Kod źródłowy pozostaje zamknięty.

## Kontakt
z@golpin.pl
