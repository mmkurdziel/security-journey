# Faza 3: DevSecOps

[↑ start](../README.md)

**Okres:** lip – wrz 2027

**Projekt portfolio (publiczne repo):** `dotnet-devsecops-demo` → _wstaw link po utworzeniu_

Celowo podatna aplikacja ASP.NET Core + pipeline, który wyłapuje i blokuje błędy.

- [ ] Aplikacja z celowymi błędami: SQLi, IDOR, sekret w kodzie, podatna paczka NuGet
- [ ] SAST: Semgrep
- [ ] SCA: Dependabot / `dotnet list package --vulnerable`
- [ ] Wykrywanie sekretów: gitleaks
- [ ] Skan kontenera: Trivy
- [ ] DAST: OWASP ZAP
- [ ] Naprawa błędów, pipeline na zielono
- [ ] README z opisem każdej podatności
- [ ] Model zagrożeń STRIDE

Notatki: [narzedzia.md](narzedzia.md) · [threat-model-stride.md](threat-model-stride.md)
