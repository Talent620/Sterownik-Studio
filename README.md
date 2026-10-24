# Sterownik Studio

**Obróbka zdjęć produktowych z AI — od materiału źródłowego do sprawdzonego eksportu.**

[Opis projektu w portfolio](https://github.com/Talent620/Talent620/blob/main/projects/sterownik-studio.md) · [Wydania Windows](https://github.com/Talent620/Sterownik-Studio/releases) · [Portfolio autora](https://github.com/Talent620)

Sterownik Studio to aplikacja Windows do retuszu zdjęć produktowych z porównaniem wyniku z oryginałem. Kontrola obejmuje zachowanie numerów, etykiet, kodów i widocznych cech produktu. Niepewny wynik blokuje automatyczny eksport; zdjęcie należy również obejrzeć obok źródła.

## Jak wygląda praca

**Dodaj zdjęcia → obróbka AI → kontrola → porównanie → eksport.**

Program łączy panel pracy, obsługę zadań i konfigurację integracji AI. Publiczne repozytorium udostępnia instalatory i instrukcje; kod źródłowy jest utrzymywany oddzielnie.

## Instalacja Windows

Prezentowane wydanie: **1.9.4, Windows x64**.

1. Otwórz [wydanie 1.9.4](https://github.com/Talent620/Sterownik-Studio/releases/tag/v1.9.4).
2. Pobierz `Sterownik-Studio-Setup-1.9.4.exe`, instrukcję `INSTRUKCJA-WINDOWS-CODEX-1.9.4.md` i plik `SHA256SUMS-1.9.4.txt`.
3. Porównaj SHA-256 instalatora z wartością w pliku sum. Instalator nie ma podpisu Authenticode.
4. Zainstaluj program i otwórz Sterownik Studio z menu Start. Nie trzeba osobno instalować Node.js ani npm.
5. Zgodnie z instrukcją wydania skonfiguruj logowanie silnika retuszu i klucz API do analizy oraz kontroli zdjęć.

Logowanie i dostęp API to osobne elementy konfiguracji. Płatne operacje wymagają konta użytkownika i dostępnych środków zgodnie z warunkami wybranego dostawcy.

## Co potwierdzono

Opis wydania 1.9.4 odnotowuje weryfikację budowania i instalacji, uruchomienia backendu i panelu oraz dołączonych narzędzi w czystym profilu Windows CI. Testy z atrapami integracji nie zastępują logowania na rzeczywistym koncie i próby płatnego retuszu.

Zakres testów, konfiguracja i ograniczenia znajdują się w [opisie wydania oraz załączonej instrukcji](https://github.com/Talent620/Sterownik-Studio/releases/tag/v1.9.4). Wersje historyczne pozostają dostępne w [Releases](https://github.com/Talent620/Sterownik-Studio/releases).
