---
layout: single
title:  "Zasada 4%"
date:   2022-09-28 19:20:00 +0200
tags: definicje filozofia
excerpt: "Zasada czterech procent to prosta reguła pozwalająca ocenić, ile pieniędzy potrzebujesz do niezależności finansowej."
header:
  overlay_image: /assets/2022-09-28/jonas-msuj3PtW5fk-unsplash.jpg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  caption: "Photo credit: [**Jonas @ Unsplash**](https://unsplash.com/@jonason_b)"
  teaser: /assets/2022-09-28/jonas-msuj3PtW5fk-unsplash_s.jpg
---
W **1998** trzech profesorów z Uniwersytetu Trinity w Teksasie:  Philip L. Cooley, Carl M. Hubbard i Daniel T. Walz; opublikowało artykuł analizujący [teoretyczne wyniki portfolio emerytalnych na podstawie danych historycznych z lat 1926-1995 z USA][3]. Dokument jest krótki, raptem 6 stron, i warto go przeczytać, a przynajmniej zapoznać się z wnioskami końcowymi: dla portfolio składającego się głównie z akcji[^5] i horyzontu czasowego 30 lat, wypłaty na poziomie 4% początkowej wartości inwestycji rocznie oznaczają, z prawdopodobieństwem 98%, że pieniądze nie tylko się nie skończą, ale będzie ich pod koniec rozpatrywanego okresu znacząco więcej.

Traktując sprawy w dużym skrócie, ruch [FIRE][2] wyciągnął z badania wniosek, że uzbieranie oszczędności w wysokości 25 krotności rocznych wydatków oznacza pełną niezależność finansową.

Czyli, hipotetycznie, jeśli moje wydatki[^3] miesięczne wynoszą średnio 6500 zł, a roczne - 78 000 zł, to inwestycje[^8] w kwocie 1&nbsp;950&nbsp;000&nbsp;zł wystarczą, żeby pokryć moje wydatki na zawsze.

Jest to użyteczna heurystyka, chociaż pomija lub po prostu ignoruje wiele założeń oryginalnego badania.

Autorzy patrzyli tylko na dane z rynku amerykańskiego, gdzie średni długoletni wzrost giełdy wynosi 8-9% a inflacja 2-3%. Ze względu na olbrzymi rozmiar gospodarki amerykańskiej, nie jest to zbyt duże uproszczenie: większość inwestorów FIRE będzie korzystać albo z giełdy amerykańskiej, albo z funduszy giełdy światowej, bardzo zależnej od USA.

Artykuł zwraca uwagę jak krytyczne opłaty brokera i funduszu są dla wyników inwestycji — został napisany w czasach, gdy ["dwa i dwadzieścia"][4] było zwyczajową praktyką brokerów i funduszy. Ta lekcja bardzo dobrze została przyswojona przez orędowników FIRE — każdy blog zwraca uwagę na koszty i opłaty, a fundusze od kilkunastu lat prześcigają się w obniżaniu opłat do poniżej 0.2%. Uwaga: w Polsce jest z tym nadal bardzo słabo, dlatego zdecydowanie odradzam większość polskich produktów inwestycyjnych.

Najdłuższy analizowany horyzont czasowy to 30 lat. Planując niezależność finansową — jeśli masz zamiar całkowicie zaprzestać pracy zarobkowej — warto spojrzeć w [tablice statystyczne][5] i ocenić, na ile lat twoje oszczędności będą musiały wystarczyć. W moim przypadku: mężczyzny w Polsce dobiegającego czterdziestki, mam przed sobą — statystycznie — jeszcze kolejne 37 lat. Długowieczność rodziny pozwala mi zakładać, że prawdopodobnie pożyję dłużej. To wymaga bardziej ostrożnego planowania wydatków, by nie skończyć bez pieniędzy.

Badany przez autorów okres to lata 1926-1995, w tym Wielki Kryzys i Druga Wojna Światowa. To dwa bardzo ciężkie dla światowej gospodarki momenty, które wyjątkowo mocno rzutują na powodzenie emerytury.  Rozpoczęcie okna symulacji od roku 1946 powoduje, że nawet wypłaty w wysokości 7% początkowego kapitału dają 100% sukcesu (czyli majątek nie wyczerpuje się przez 30 lat). Podobne wyniki daje rozszerzenie symulacji o dane ekonomiczne z ostatnich 25 lat — mimo kryzysów które dla osób żyjących obecnie zdecydowanie były trudne, lata po Drugiej Wojnie Światowej są praktycznie złotym wiekiem w historii świata. Narzędziem które pozwala przetestować swoje własne założenia, w oparciu o aktualne dane statystyczno-ekonomiczne, jest [cFIREsim][7].

Blogerzy FIRE często publikują swoją całkowitą wartość majątku z uwzględnieniem nieruchomości, w których mieszkają oraz samochodów, a po odliczeniu zobowiązań kredytowych. Zazwyczaj od tej właśnie kwoty liczą swoje 4%. To stoi w sprzeczności z wnioskami z badania: punktem odniesienia jest całkowita wartość inwestycji, a nie cały majątek. Tak, dom czy mieszkanie, z którego korzystasz, obniża twoje wydatki, bo nie musisz płacić za wynajem — ale pomijając (rzadką w Polsce) pożyczkę hipoteczną — nie będziesz w stanie wykorzystać ich do wygenerowania przepływów gotówkowych, a to one są tak naprawdę najważniejsze, jeśli chodzi o wypłacalność i pokrywanie codziennych zobowiązań.

Aktualizowanie kwoty wypłaty o inflację (co roku, względem poprzedniego roku) powoduje, że prawdopodobieństwo sukcesu spada do 95%. To niby niewielka różnica, ale nie brzmi już tak dobrze. Z drugiej strony, w komentarzach do badania, autorzy wielokrotnie powtarzali, że prawdziwi ludzie nie trzymają się tak sztywno reguł: w latach chudych, kiedy wszyscy wokół zaczynają oszczędzać ze względu na inflację, emeryci też zwykle zmniejszają wydatki. Do tego na starość mamy skłonność do redukowania konsumpcji, a główny strach amerykańskich emerytów: olbrzymie koszty pobytu na starość w szpitalu — nie dotyczy Europejczyków.

Jest jeszcze jeden czynnik wpływający istotnie na wyliczenia, a przy tym mocno zależny od kraju, w którym mieszkasz: emerytura. Najniższa emerytura z ZUS w tej chwili to 1338 zł miesięcznie. Aby osiągnąć taki przychód, trzeba by mieć — zgodnie z zasadą 4% — inwestycje o wartości 401 400 zł. Owszem, najpierw trzeba się "dokulać" do wieku emerytalnego (a ten zapewne jeszcze wzrośnie, zanim go osiągniemy), ale każdy dodatkowy przychód zmniejsza konieczną do uzbierania kwotę. Z drugiej strony, jeśli spodziewasz się żyć dwadzieścia kilka lat "na emeryturze" zanim zaczniesz ją dostawać z ZUS, to faktycznie jest to niewielka pomoc.

No dobrze, a jak często tę wypłatę realizować (i aktualizować jej wysokość)? [Nick Magguilli, prowadzący kapitalny blog Of Dollars And Data][6], analizował niedawno to zagadnienie: im częściej sprzedajesz część swoich inwestycji, tym lepiej (bo tym dłużej pieniądze pracują na rynku). W związku z tym przyjąłem moją uproszczoną wersję reguły 4%: jedna trzecia procenta (0.33%) co miesiąc.

[^3]: Jak liczę wydatki? O tym będzie później.
[^5]: Jak/gdzie trzymać oszczędności? O tym będzie później.
[^8]: W co inwestuję? O tym będzie później.

[2]: {% post_url 2022-09-12-czym-jest-fire %}
[3]: https://www.aaii.com/files/pdf/6794_retirement-savings-choosing-a-withdrawal-rate-that-is-sustainable.pdf
[4]: https://www.investopedia.com/terms/t/two_and_twenty.asp
[5]: https://stat.gov.pl/sygnalne/komunikaty-i-obwieszczenia/lista-komunikatow-i-obwieszczen/komunikat-w-sprawie-tablicy-sredniego-dalszego-trwania-zycia-kobiet-i-mezczyzn,285,10.html
[6]: https://ofdollarsanddata.com/sell-slowly/
[7]: https://cfiresim.com/
