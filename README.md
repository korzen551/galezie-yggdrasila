# Gałęzie Yggdrasila

Mod do Minecrafta **26.3** (Fabric): sześć nordyckich krain w klimacie God of War.

## Instalacja (jeden raz)
1. Zainstaluj **Fabric Loader 0.19.5** dla Minecrafta 26.3 (instalator: https://fabricmc.net/use/installer/).
2. Pobierz **Fabric API 0.161.0+26.3** (https://modrinth.com/mod/fabric-api) i wrzuć do folderu `.minecraft/mods`.
3. Pobierz najnowszy plik `yggdrasil-*.jar` z zakładki **Releases** (po prawej) i wrzuć go do `.minecraft/mods`.
4. Uruchom grę profilem **Fabric**.

## Aktualizacje
Mod aktualizuje się sam: przy starcie gry sprawdza, czy jest nowa wersja, pobiera ją i pokazuje komunikat.
Wystarczy wtedy zamknąć i ponownie uruchomić grę.

## Na start
- Trzy zakładki w trybie kreatywnym: „Yggdrasil — przedmioty i bramy”, „bloki”, „jaja spawnu”.
- Komenda (świat z kodami): `/kraina midgard`, `/kraina dawn_isles`, `/kraina hel`, `/kraina muspel`, `/kraina jotunheim`, `/kraina overworld`.
- Pokazy mobów: `/ygg pokaz fjallgleypir|oczodrzew|baron <akcja>` (np. `/ygg pokaz oczodrzew sen`, `/ygg pokaz baron wspinaczka`).
- Brama Drzewa: rama z **Kamienia Trzech Światów** (wnętrze od 2×3, można powiększać jak portal do Netheru;
  górna i dolna belka wystają o 1 blok po bokach), zapalana **Krzesiwem Światów**.

## Zmiany w 0.4.0
- **Muspelheim**: ogromne, samotne wulkany (420–720) z jeziorami Lawy Wulkanicznej, rzeki zwykłej Lawy Muspelu, 8 biomów,
  **Baron** (bardzo szybki, skacze wysoko, bije jak Hulk) i rzadszy **Baron z Mieczami** (wspina się po ścianach i nawisach, zostawia dziury).
- **Hel**: 7 biomów (Kościane Pola, Mgliste Bagna, Las Dusz, Iglice Lodu, Nastrond, Pola Grobów, Szronowe Równiny), mosty w każdym.
- **Wyspy Świtu**: wyspy bez końca w górę i w dół (spadasz przez Morze Chmur i lądujesz znowu nad wyspami), 7 krain wysp
  (od drobnych archipelagów po kontynenty nieba), **Złota Woda Świtu** (leczy), wodospady ~400 bloków, 8 nowych spokojnych mobów.
- **Jotunheim** (nowa kraina): góry do 1200, otchłanie do -1000, rzadkie Doliny Olbrzymów na wysokości 400–600, brama z Granitu Jotunów.
- **Midgard**: nowe budowle — długi dom jarla, gród z palisadą, kościół klepkowy, kurhan królewski z kamienną łodzią,
  wieża strażnicza, kuźnia run + 5 nowych budowli w jaskiniach.
- Nowy teren pojawia się tylko w nowych (nieodwiedzonych) chunkach.

## Zmiany w 0.4.1
- **Baron** przebudowany od zera: 5 bloków wzrostu, wygląd jak Baron of Hell z DOOM Eternal (kamienna skóra z pęknięciami lawy,
  płonące przedramiona, wielkie rogi), rzuca kule ognia, uderzenie w ziemię puszcza falę ognia, 260 HP. Baron z Mieczami — płonące ostrza.
- **Pegaz Świtu**: wygląda jak koń z dużymi skrzydłami; oswajasz jak konia, zakładasz siodło i latasz (skok = machnięcie skrzydłami,
  także w powietrzu; w locie szybuje). Bez obrażeń od upadku.
- **Alabastrowy Strażnik**: kamienny anioł-wojownik z mieczem, tarczą i skrzydłami.
- Rzemiosło: Midgardzki Stół Rzemieślniczy, Midgardzki Piec, **Ciężki Piec** (Przepalony Głębinowy Łupek + Czaszka Trolla + 2 sztabki
  Runostali; tylko w nim przetopisz Runostal), Czaszka Trolla z Kamiennego Trolla, deski z wszystkich drzew krain i dużo nowych przepisów.

## Zmiany w 0.4.2
- **Świątynie Wysp Świtu** w świecie: Świątynia Świtu (3 tarasy z kolumnadami, sanktuarium ze złotą kopułą, 4 wieże, skrzydlate
  posągi, sadzawki złotej wody) i Katedra Skrzydeł (nawa 110 bloków, wieża ze złotym hełmem, witraże, anioł nad portalem). Każda na własnej
  latającej wyspie (~190–200 bloków), w środku beczki z łupem. Ręcznie: `/place structure yggdrasil:dawn_temple`.
- Dziczyzna z Zająca Obłoków, Złotego Pawia, Lisa Świtu, Salamandry i Mchowca; naprawione łupy nowych mobów Świtu.

## Zmiany w 0.11.4
- **Fjallgleypir ma 3400 życia** (wcześniej gra po cichu obcinała mu życie do 1024).
- Jego ogień nie zostawia już tysięcy przedmiotów z wypalonych bloków. To one wieszały grę w czasie walki: bloki wracały,
  moby nie dostawały obrażeń. Zawartość skrzyń nadal wypada.
- Przy oczach i łbie Fjallgleypira nie ma już niewidzialnych ścian (w oczy nadal da się trafić).
- **Hel: zamki i więzienia ok. 3 razy rzadziej.** Gra najpierw losuje „tu będzie zamek”, a dopiero potem jaki.
- Wioski Wojowników nie zalewają już logu tysiącami ostrzeżeń „unsafe terrain read”.

## Zmiany w 0.11.3
- Łuk z `/gear` ma Nieskończoność zamiast Naprawy.

## Zmiany w 0.11.2
- `/gear` daje też łuk (Moc V, Odrzut II, Płomień, Niezniszczalność III, Naprawa), stak strzał i drugi stak fajerwerków (lot 3).

## Zmiany w 0.11.1
- **Naprawiony crash (brak pamięci)** przy dłuższej grze z dużym zasięgiem: napełnianie głębokich jezior i lejów w Midgardzie
  planowało osobny „tick” dla każdego bloku wody (do 160 tys. na chunk). Teraz tylko tam, gdzie woda może spłynąć.
  Stare zapisane chunki są czyszczone przy wczytywaniu — świat jest bezpieczny.
- Symulacja ustawiona na 32 (więcej gra i tak nie przyjmuje).

## Zmiany w 0.11.0
- **Duża optymalizacja**. Render 64 chunki + symulacja 32 w Midgardzie: stojąc **~225 FPS** (było 13), w locie ~580 FPS,
  tick serwera ~11 ms (było 64 ms). Hel ~740 FPS w locie.
  - Nowy teren generuje się 2–3 razy szybciej, a gra wczytuje naraz tyle chunków, ile ma wątków procesora (zamiast 4).
  - Światło nie kopiuje już całej mapy wszystkich sekcji po każdej zmianie. To ono najbardziej zjadało pamięć i powodowało zacięcia.
  - Serwer co tick zagląda tylko do sekcji, w których coś rośnie lub się zmienia, a nie do wszystkich ~130 w każdym chunku.
  - Klient nie szuka co klatkę w ogromnej tablicy, gdzie leży każda sekcja w pamięci karty graficznej.
  - Mniej zbędnych danych w pamięci (strażniki wątków, puste ticki jezior). Woda w świeżo wygenerowanych jaskiniach nie zostawia
    już tysięcy leżących roślin.
- Zalecane ustawienia Javy w launcherze: `-Xmx16G` i `-XX:+UseCompactObjectHeaders` (przy 32 GB RAM).

## Zmiany w 0.10.0
- **Fjallgleypir dokończony**:
  - **Trafia się w całe ciało**: grzbiet, boki, brzuch, pierś, szyję, nogi, łapy, ogon, skrzydła i łeb. Strzały już nie przelatują.
  - **Ciało jest twarde jak skała**: można po nim chodzić, a gdy się porusza, niesie cię na grzbiecie. Nie da się w niego wejść.
    Wlecenie w niego elytrą kończy się uderzeniem, utratą życia i spadaniem.
  - **Zrzucanie z grzbietu**: jeśli stoisz na nim 10–20 sekund, zaczyna się wiercić, staje dęba i przewala z boku na bok.
    Podrzuca cię coraz wyżej, a na końcu wyrzuca daleko w bok.
  - **Trafienie**: zamiast czerwienienia całej bestii na ułamek sekundy zapala się na czerwono tylko trafiony kawałek skóry.
  - **Skok**: po lądowaniu zostają w ziemi cztery wielkie odciski łap z podeszwą i śladami palców.
- Naprawione w całym modzie: odrzut i podrzut gracza (od T-rexa, Barona, fali uderzeniowej itd.) wcześniej nie działał na gracza.

## Zmiany w 0.9.2
- Naprawione: zamach ogonem tyranozaura w prawo wyrzucał gracza ze świata (błąd „Sniffer” w logu).

## Zmiany w 0.9.1
- Proste komendy do bestii:
  - **`/jednorozec`**: oswojony jednorożec z siodłem stanie 6 bloków przed tobą. Od razu możesz na niego wsiąść i latać.
  - **`/trex`**: tyranozaur stanie 22 bloki przed tobą, zwrócony w twoją stronę.
  - Nadal działają też `/summon yggdrasil:unicorn` i `/summon yggdrasil:tyrannosaurus`.
- Wrogi osadnik nie zasypuje już czatu okrzykiem „Precz z naszej wioski, zbóju!”, gdy trzymasz na nim prawy przycisk myszy.

## Zmiany w 0.9.0
- **Jednorożec** (`/summon yggdrasil:unicorn`, nie pojawia się sam w świecie):
  - Większy od konia: srebrzysta sierść w jabłka, długa złota grzywa z koralowym warkoczem, jedwabiste szczotki nad kopytami,
    spiralny perłowo-złoty róg.
  - Oswajasz go jak konia (jeździsz na oklep, aż przestanie zrzucać), potem zakładasz siodło. Z siodłem ma też nordycką derkę i uzdę.
  - **Lata magią**, bez skrzydeł. Skok (przytrzymaj spację) wzbija go w powietrze, a każdy kolejny skok w locie dodaje wzlotu.
    Z klawiszem „do przodu” leci tam, gdzie patrzysz: w górę, żeby się wznieść, w dół, żeby zanurkować. Bez ruchu wisi w powietrzu
    i powoli opada. Spod kopyt sypią się iskry, a upadek nic mu nie robi.
  - **Róg zależy od jedzenia**:
    - Dobre jedzenie (złota marchew, złote jabłko, marchew, jabłko, siano, pszenica, cukier, jagody, ciasto, chleb…): róg świeci
      na różowo, a jednorożec co ~2 sekundy strzela w ciebie promieniem z dobrym efektem (regeneracja, pochłanianie, odporność,
      szybkość, siła, wyższe skoki, odporność na ogień, widzenie w ciemności).
    - Złe jedzenie (zgniłe mięso, oko pająka, trujący ziemniak, rozdymka, surowe mięso): róg płonie na lazurowo-zielono,
      jednorożec się wścieka i strzela złymi efektami (trucizna, słabość, spowolnienie, mdłości, zmęczenie, ślepota, głód).
  - Każde karmienie przedłuża nastrój, maksymalnie do 2 minut.
- **Tyranozaur** (`/summon yggdrasil:tyrannosaurus`, nie pojawia się sam w świecie):
  - Ok. 10 bloków wysokości i 14 długości: brązowa łuska w ciemne pręgi, kły w obu szczękach, małe łapki, trzy palce z pazurami.
  - Poluje na graczy i zwierzęta. Na widok ofiary ryczy: spowalnia graczy i odpycha małe stwory.
  - Ataki: ugryzienie (schyla łeb i kłapie, ogromne obrażenia), zamach ogonem na stojących z boku albo za nim, tupnięcie na tych,
    co weszli mu pod brzuch.
  - Chodzi ciężkim krokiem: ziemia pyli się spod stóp, a liście łamią się, gdy przez nie przechodzi.
  - Da się go trafić na całej długości: łeb (×1,5 obrażeń), szyja, pierś, ogon.
  - Zostawia dużo dziczyzny i kości.
- Naprawione: siodło na **Pegazie Świtu** pozwala nim sterować (wcześniej jeździec nie miał kontroli).

## Zmiany w 0.8.0
- **Fjallgleypir od nowa, z mnóstwem animacji**:
  - **Różowy ogień Seidu** wychodzi z samej głębi gardła, jakby z żołądka. Najpierw bestia nabiera powietrza: odchyla łeb,
    zasysa iskry, z nozdrzy leci dym, gardło świeci. Potem zieje strumieniem albo strzela serią ognistych kul.
  - Ogień **wypala kratery** wg twardości bloków: ziemię i drewno mocno, kamień słabiej, najtwardsze skały ledwo.
  - **Na oślep albo celnie**: dopóki cię nie wypatrzy, strzela z pamięci, gdzie byłeś (rozrzut do 15 bloków). Wypatrzy cię, gdy
    atakujesz i stoisz w miejscu; wtedy trafia bardzo celnie. Chowanie się, skoki i przerwa w atakach sprawiają, że cię gubi.
  - **Nowy, ciężki chód**: barki, biodra, szyja i ogon pracują, każdy krok wzbija pył. Bestia jest szybsza, a zęby siedzą w szczękach.
  - **Skok**: dłuższy lot, przednie łapy wyciągnięte, tylne podkulone, bez machania.
- **Słabe punkty** (jak głowa smoka Kresu):
  - **Oczy** biorą ×3 obrażeń, **język** przy otwartej paszczy ×3,5, **spody łap** ×3.
  - 2–3 trafienia w łapy w czasie skoku: bestia **przewraca się**, skok przepada, przez chwilę leży i dostaje więcej obrażeń.
  - Kilka trafień w język przerywa zionięcie i pożeranie, a bestia wypluwa ofiarę.
  - Gdy cię wypatrzy, 4–5 trafień w oko sprawia, że **zamyka oczy** na kilka sekund, gubi cię i musi szukać od nowa.
- **Pożeranie**: czasem opuszcza łeb nisko jak pies nad miską i próbuje cię zjeść. Czasem łapą **podrzuca cię na ~400 bloków**,
  staje na tylnych łapach i łapie paszczą. Kto zostanie w paszczy dłużej niż sekundę, ginie pożarty.

## Zmiany w 0.7.0
- **Mieszkańcy Wiosek Wojowników**: wysocy (ok. 2,5 bloku), z długimi rękami i ciałem jak u wieśniaka, ale z brodami, warkoczami
  i strojami zawodów. Każdy ma imię, a kolor włosów, fryzurę i brodę losuje.
  W jednej wiosce mieszka ok. 40 osadników i 30 wojowników: kupcy za ladami na rynku, kowal w kuźni, łucznik na strzelnicy,
  rybak nad jeziorkiem, myśliwy, rolnicy na polach, bibliotekarz w bibliotece twierdzy, wojownicy w koszarach, długim domu,
  na arenie, w bramie i na każdej wieży.
- **Handel**: PPM na osadniku otwiera wymianę. Handlują materiałami za materiały, a główną monetą jest **Bursztyn**.
  Kowal przetapia rudy i kuje broń, łucznik robi strzały, myśliwy skupuje skóry i poroża itd. Towar odnawia się codziennie.
- **Targowanie się** z kupcami na rynku: skradanie + PPM daje 10% taniej, do 50%. Kupiec coraz bardziej się złości, aż
  czerwienieje na twarzy. Gdy przesadzisz, uderzy cię i do końca dnia nic ci nie sprzeda.
- **Wojownicy rang I–V** (Drengr, Tarczownik, Weteran, Huskarl, Ulfhedinn): im wyższa ranga, tym lepsza zbroja i broń, więcej
  życia i drożej. W oknie handlu kupuje się u nich usługi, płaci się bursztynem, srebrem, Runostalą, diamentami i Zorzytem:
  - **Najem**: ranga I towarzyszy ci 20 minut, ranga V 2 godziny. Wojownik idzie za tobą (także do innych krain), broni cię
    i atakuje twoich wrogów, ale może zginąć. Sekundę po końcu czasu żegna się, odchodzi i wraca do swojego budynku w wiosce.
  - **Wyprawa**: wybierasz łup (wyższa ranga = rzadsze rzeczy, aż po Smoczą Łuskę i Helgrind). Wojownik wyrusza i wraca po
    czasie. Gdy jesteś daleko, przylatuje do ciebie **sowa**, siada ci na ramieniu i daje **list**: kto wrócił, z czym i gdzie
    czeka. Na miejscu wojownik sam podchodzi i rzuca ci łup, a potem odpoczywa 3 dni.
  - **Umowa** (dostajesz ją przy zakupie): PPM pokazuje, ile czasu zostało albo gdzie czeka wojownik.
- **Burmistrz-jarl** siedzi w twierdzy na tronie przy stole biesiadnym, najsilniejszy w wiosce. Jeśli go zaatakujesz, cała
  wioska chce cię zabić przez dzień (a gdy go zabijesz, przez 3 dni). Brama z kratą nie otworzy się wtedy na pukanie.
- **Własne głosy** mieszkańców (żadnych dźwięków wieśniaków): krótkie słowa w nieznanym, nordyckim języku i pomruki, osobno
  męskie i kobiece. Do tego okrzyki bojowe wojowników, jęki, zgoda i odmowa przy handlu oraz huk sowy.
- Jaja spawnu osadnika i wojownika (w zakładce jaj).

## Zmiany w 0.6.0
- **Wielka Wieża Obserwacyjna Helu** (ok. 500 bloków): stoi na dnie rozpadlin, na skrzyżowaniu dwóch linii mostów, więc mosty
  dochodzą do niej z czterech stron prosto do bram sali mostów. W środku są jedne kręcone schody od dna aż na szczyt wokół otwartego
  szybu z łańcuchami. Na samej górze, pod bardzo wąską, ostrą piramidą, jest izba latarni.
- **Latarnia i Wój Światła**: w izbie stoi zgaszony **Kamień Latarniany**, a pod nim wisi ramka z **Kościaną Dźwignią**. Postaw
  dźwignię na kamieniu i ją przełącz, a obudzi się mini-boss **Wój Światła**: oślepiająco jasna istota, która unosi się nad posadzką.
  Z bliska tnie dwoma świetlistymi mieczami, z daleka strzela promieniem światła, który mocno odrzuca, a gdy stoisz przy nim
  za długo, wybucha światłem dookoła.
- Z Woja wypada **Ogień Życia**. Włóż go w Kamień Latarniany, a latarnia zapłonie: jasny punkt widać z każdej odległości,
  na jaką gra rysuje świat, także w nocy, a po okolicy krążą wiązki jak z latarni morskiej. Zapalony kamień da się wykopać tylko
  kilofem z moda (długo), a zgaszony nic nie daje.
- **Kompas Pradawnego Światła** (kompas + kość Helu): kliknij nim zapalony Kamień Latarniany, a będzie stale wskazywał to miejsce.
  **Kościana Dźwignia**: kość Helu na Grobowym Łupku.
- **Mosty**: podpory co 12 bloków aż do dna; część jest rozwalona (kikuty, urwane kawałki pod pomostem, gruz), a czasem podpory brak.
- **Zamki przy moście**: gdy zamek powstaje blisko mostu, dosuwa się do niego (do ok. 50 bloków). Dostaje wieżę schodową
  z wejściem na wysokości mostu i kamienną groblę prosto na most.

## Zmiany w 0.5.2
- Lawa Muspelu, Lawa Wulkaniczna i Płynny Ogień działają jak prawdziwa lawa: nie przelatuje się przez nie, tylko grzęźnie w nich jak w lawie.

## Zmiany w 0.5.1
- Komenda **/gear** (wymaga kodów): pełna zbroja, miecz, kilof, topór i łopata z Runostali z najlepszymi zaklęciami na maksymalnym
  poziomie, elytra (niezniszczalność, naprawa), stak fajerwerków (lot 3) i stak zaklętych złotych jabłek.

## Zmiany w 0.5.0
- **Nowe szkielety Helu**: wyglądają jak prawdziwe szkielety, ale mają rogaty hełm i okrągłą tarczę z runą. Szkielet-Rycerz walczy
  Rdzawym Mieczem, rzadszy Szkielet-Łucznik strzela z łuku. Obaj naprawdę blokują tarczą ciosy i strzały z przodu,
  a cios toporem wytrąca im tarczę na kilka sekund.
- **Jaskinie Helu**: pod dolinami (pod mostami) ciągną się pieczary i tunele do ok. 480 bloków w głąb. Są tylko w nowo odkrytych
  częściach Helu.
- **Nowy metal Helu**: w jaskiniach jest ruda **Gjallsafiru** (blado-błękitny szafir). 2 Gjallsafiry i 2 kości Helu dają
  **Surowy Helgrind**, a Ciężki Piec przetapia go na **Sztabkę Helgrindu**. Z niej robi się narzędzia (trzonki z kości Helu)
  i zbroję, mocniejsze od Runostali.

## Zmiany w 0.4.9
- **Gigantyczne struktury Helu** (6 rodzajów, rzadkie, ogromne):
  - **Plac Ostatniej Drogi**: okrągły plac z ośmioma alejami posągów. Przez bramy wchodzą **widma potworów ze wszystkich krain**
    i idą prosto do **Wielkiej Czarnej Dziury** (100 bloków w dół), gdzie giną w **Płynnym Voidzie**. Wokół dziury stoi ośmiu
    **Strażników Śmierci**: olbrzymów na 7 bloków z mieczem, toporem, młotem albo siekierą. Są neutralni, ale gdy kręcisz się
    po placu za długo albo któregoś uderzysz, ruszają do ataku: wolni, z długim zamachem i bardzo mocnym ciosem. Da się odskoczyć.
  - **Studnia Dusz**: zrujnowana okrągła wieża nad otchłanią. W środku spiralna galeria z celami za rdzawymi kratami,
    klatki wiszące na łańcuchach, a na dnie Płynny Void.
  - **Wiszące Klatkowisko**: wielka przepaść z czterema piętrami cel wykutych w skale, kamienne łuki z klatkami, pomost na łańcuchach
    i szkielet olbrzyma na dnie.
  - **Twierdza Nastrond**: mury z fosą i wieżami, Sala Królewska z zawalonym dachem i żebrami olbrzymów, donżon (skarbiec, zbrojownia,
    komnata pana, sala rytuałów), biblioteka z galerią, sala biesiadna z kuchnią, kaplica z kryptą, koszary, lochy, pracownia alchemika.
  - **Éljúðnir, Pałac Hel**: trzy tarasy z wielkimi schodami, Galeria Umarłych i Kostnica, **Próg Upadku** (zapadnia nad Voidem!),
    Sala Hungr ze sługami Ganglati i Ganglöt, łoże Kör, Straż Tronu (dwaj Strażnicy Śmierci) i sala tronowa z kolosalnym posągiem Hel.
  - **Rozdarta Twierdza**: zamek przecięty przepaścią z Voidem. Połowa się zapadła i przechyliła, Wielka Sala jest rozdarta na pół,
    jest krzywa wieża nad otchłanią i dwa mosty (jeden urwany).
- W salach siedzą **potężne potwory z imionami** (np. Król Nastrondu, Pożeracz Ksiąg, Cień Hel), a w skrzyniach są nowe łupy Helu.
- **Uwięzione Dusze** w celach i klatkach: przebij się do duszy i jej dotknij, a zostanie uwolniona i da doświadczenie.
- Nowe bloki Helu: Latarnia Helu (stoi albo wisi), Spleśniały Dywan, Spleśniały Regał, cegły, łupek, kraty, łańcuchy, kosze dusz,
  sztandary, pajęczyny i Płynny Void (z wiadrem).

## Zmiany w 0.4.8
- **Wioska Wojowników całkiem od nowa i 3× większa** (mur 217×217 bloków): 15 wielkich wież (kamienny trzon, nadwieszone drewniane
  piętro, galeria widokowa, stromy dach z gontów ze smoczą głową) i nowa brama z dwiema basztami. **Krata w bramie sama się podnosi
  w dzień, a opada w nocy albo gdy przy bramie kręcą się potwory.** Zapukaj w kratę (prawy przycisk), żeby otworzyć ją na chwilę.
- Ulice z latarniami i dzielnice: rolników (pola, wiatrak, spichlerz na palach), rzemieślników (kuźnia, garbarnia, stajnie, warsztat
  cieśli, wędzarnia), mieszkalne, świątynna (kościół, cmentarz z kurhanami, święty gaj) i wojowników (dom wojowników, arena, koszary);
  rynek ze straganami i plac przed twierdzą z fontannami.
- **Twierdza jarla**: taras z reprezentacyjnymi schodami i wieżyczkami, dziedziniec z fontanną, dwa piętrowe skrzydła z krużgankami,
  wielka sala miodowa z ucztą i tronem, ogród ze świętym drzewem, kuchnia z browarem, kaplica, wieża jarla i skarbiec.
- **Domy o różnych kształtach**: dwór piętrowy, zagroda ze stodołą, dom kupca z wieżyczką, dom torfowy z trawiastym dachem, okrągła chata,
  spichlerz na palach, dom z galerią, dom-wieża, dwór z dziedzińcem, karczma. Dawne małe chatki zostały jako najbiedniejsze.
- **Wszystko urządzone w środku**: stoły z krzesłami i świecami, ławy, posłania ze skór, paleniska, regały z księgami, stojaki z bronią,
  żyrandole z poroża, dywany, beczułki miodu, zioła i ryby pod belkami, skóry na ścianach.
- **38 nowych bloków**: schody i płyty ze strzechy, desek i gontów, smołowane gonty, płot, furtka, drzwi, okiennice, okienko z błony,
  smocza głowa, proporce, kaganek ścienny, Kołowrót Kraty, meble (stół, krzesło, posłanie, regał, stojak na broń, beczułka, skrzynia),
  dywany, świece, żyrandol z poroża, latarnia, łańcuch z Runostali, pęki ziół, suszone ryby, skóra na ścianę.
- Nowe wioski pojawiają się tylko w nowych (nieodwiedzonych) chunkach.

## Zmiany w 0.4.7
- **Wyspy Świtu jeszcze wyższe**: każdy etap ma teraz 4064 bloki wysokości (maksimum gry), od y -2032 do 2031, i 15 pięter
  wysp zamiast 7. Mgła i przejście na inne wyspy dopiero powyżej y 1800 i poniżej -1800.
- Latanie w kółko działa w obie strony: spod najniższego piętra (-20) trafiasz na najwyższe (+20) i odwrotnie.
- Nowe piętra wysp pojawiają się tylko w nowych (nieodwiedzonych) chunkach.

## Zmiany w 0.4.6
- **Etapy Wysp Świtu**: wlot w górną mgłę (od 0.4.7 powyżej y 1800) przenosi na **inne wyspy** — piętro wyżej, z innym terenem
  i innymi krainami, przy tych samych X/Z. Spadek w dolną mgłę (od 0.4.7 poniżej -1800) — piętro niżej. Powrót tą samą mgłą prowadzi
  dokładnie tam, skąd się przyleciało. Poziomo nie da się dolecieć do innego piętra.
- Pięter jest 41 (20 w górę, 20 w dół od Wysp z bramy); tworzą pierścień — nad najwyższym jest najniższe.

## Zmiany w 0.4.5
- **Wioski Wojowników w Midgardzie** (część 1: budowle). Na płaskich nizinach (łąki, wrzosowiska) co ~600 bloków.
  Mur 97×97 o wysokości 7 bloków z blankami, chodnikiem i schodami, 4 wieże narożne, brama z wieżyczkami i nową
  **Runiczną Kratą**. W środku rynek ze studnią, straganami i pomnikami, zamek z salą tronową, kościół klepkowy, dom wojowników,
  kuźnia, domy osadników, farma, rybak z jeziorkiem, myśliwy, biblioteka i strzelnica. W beczkach łupy.
  Szukanie: `/locate structure yggdrasil:warrior_village` (w Midgardzie).
- Runiczna Krata: 6 sztuk z 7 sztabek Runostali (I_I / III / I_I).
- Mieszkańcy, handel, wynajem wojowników i mechanizm kraty — w kolejnych wersjach.

## Zmiany w 0.4.4
- Fjallgleypir: nie lewituje już na zboczach. Wysokość ciała liczona głównie z gruntu pod tułowiem
  (stopy na zboczu tylko lekko je unoszą). Zmierzone w marszu: 36–39 bloków nad gruntem przy wzroście 36
  (wcześniej było nawet 55). Nie zapada się w ziemię.
- Fjallgleypir: kroki animowane w czasie gry, a nie w klatkach — tak samo płynne przy każdym FPS.

## Zmiany w 0.4.3
- Oczodrzew przyspiesza wzrost roślin w promieniu 20 bloków (~50%).
- Pegaz: patrząc mocno w dół w locie, nurkuje.
