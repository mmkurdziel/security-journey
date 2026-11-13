# Tydzień 1: praktyka

[← notatki tygodnia](notatki.md)

## Zaplanowane

- [ ] TryHackMe – Pre Security: Network Fundamentals
- [ ] Wireshark: przechwyć własny ruch (DNS, HTTP, TLS) i opisz, co widzisz

## TryHackMe

Zapisz się na aktualną ścieżkę [Pre Security](https://tryhackme.com/path/outline/presecurity) (wersja z 2026 r.; stara jest oznaczona jako „Legacy”). Część pokojów jest płatna, ale te darmowe wystarczą na ten tydzień:

- [ ] What Is Networking?
- [ ] Intro to Networking
- [ ] Networking Concepts
- [ ] Network Traffic Basics
- [ ] DNS in Detail

## Wireshark (sobota, 1–2 h)

1. Zainstaluj [Wireshark](https://www.wireshark.org/).
2. Rozpocznij przechwytywanie na swojej karcie sieciowej, otwórz kilka stron, uruchom `nslookup example.com`.
3. Użyj filtrów: `dns`, `http`, `tls.handshake`, `tcp.flags.syn == 1`.
4. Opisz poniżej: zapytanie i odpowiedź DNS, three-way handshake TCP, początek handshake TLS (Client Hello / Server Hello).

> Nie commituj plików `.pcap` / `.pcapng` – mogą zawierać Twoje dane (są w `.gitignore`).

## Dziennik

Skopiuj [szablon writeupu](../../szablony/writeup-labu.md) dla każdego labu, który warto opisać.

