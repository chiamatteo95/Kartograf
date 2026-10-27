# Kartograf

Prosty edytor map i plansz do gier strategicznych. Działa w przeglądarce, w jednym pliku `index.html`, bez instalacji i bez zewnętrznych bibliotek.

## Funkcje

- siatka heksagonalna lub kwadratowa (od 2×2 do 40×40 pól)
- 8 typów terenu: trawa, las, woda, góry, pustynia, bagno, śnieg, miasto
- własne kolory (do 16) wybierane w RGB, CMYK lub próbnikiem
- zmiana nazw i kolorów wszystkich terenów, także wbudowanych
- malowanie przeciąganiem (mysz i dotyk) oraz wypełnianie obszaru
- wgrywanie obrazu z konturami jako tła, do którego dopasowuje się siatka
- ukrywanie pól nad pustym tłem
- dodawanie i usuwanie pojedynczych pól
- eksport mapy do PNG oraz zapis i wczytanie projektu (JSON)
- przeglądarka pamięta własne kolory i nazwy terenów, a plansza po otwarciu jest pusta (do zachowania planszy służy zapis projektu)

## Uruchomienie

Otwórz `index.html` w przeglądarce. Możesz też opublikować stronę przez GitHub Pages
(Settings → Pages → Deploy from a branch → `main` / `/ (root)`).

## Uwagi

- Wgrane tło nie jest zapisywane w autozapisie ani w pliku projektu. Po ponownym otwarciu wgraj je jeszcze raz.
- Kontur wgrany jako tło powinien być zamknięty, inaczej wnętrze zostanie uznane za puste.
