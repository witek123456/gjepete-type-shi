# MP4 → MP3 konwerter (web)

Prosta aplikacja przeglądarkowa, która:

1. przyjmuje plik `.mp4`,
2. konwertuje go lokalnie do `.mp3` (FFmpeg WebAssembly),
3. pozwala odtwarzać dźwięk w pętli,
4. umożliwia pobranie gotowego pliku MP3.

## Uruchomienie

Wystarczy uruchomić dowolny serwer statyczny, np.:

```bash
python3 -m http.server 8000
```

Następnie wejdź na `http://localhost:8000`.

## Uwaga

Konwersja jest wykonywana po stronie klienta, więc większe pliki mogą przetwarzać się dłużej.
