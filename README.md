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
