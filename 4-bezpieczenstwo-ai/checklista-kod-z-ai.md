# Checklista przeglądu kodu wygenerowanego przez AI

[↑ faza 4](README.md)

Wersja robocza: rozwijaj ją na podstawie cotygodniowych ćwiczeń `ai-review.md` z fazy 1.

- [ ] Autoryzacja: czy każda akcja sprawdza, czy użytkownik ma prawo do **tego** zasobu (IDOR)?
- [ ] Logika biznesowa: czy da się obejść kroki (np. płatność, limity)?
- [ ] Dane wejściowe: walidacja, parametryzowane zapytania, kodowanie wyjścia
- [ ] Sekrety: żadnych kluczy i haseł w kodzie
- [ ] Zależności: czy paczki istnieją, są aktualne i bez znanych CVE (uwaga na zmyślone nazwy paczek)
- [ ] Obsługa błędów: brak wycieku stack trace i danych wrażliwych
- [ ] Kryptografia: brak własnych algorytmów, brak MD5/SHA1 do haseł
- [ ] Logowanie: zdarzenia bezpieczeństwa logowane, dane wrażliwe nie
