# ksiegowy-kursy

Dane rynkowe i parametry przepisów dla aplikacji Księgowy JDG. **Bez żadnych danych osobowych.**

- `market.json` — kurs VWCE, EUR/PLN, oferta obligacji, stopa NBP, CPI, parametry prawne (ZUS, zdrowotna, limity IKE/IKZE) i krótkie wiadomości o zmianach w przepisach, a także `promos` — sprawdzone w regulaminach promocje bankowe (premie za konta, zwrot ZUS).
- Aktualizuje go zaplanowane zadanie w Claude (dni robocze; przegląd przepisów w poniedziałki).
- Aplikacja przyjmuje z tego pliku wyłącznie znane pola w rozsądnych zakresach i nigdy nie wykonuje jego treści.
