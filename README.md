# Czujnik temperatury i wilgotności
Czujnik pozwala na obserwacje i analizę temperatury i wilgotności, potrzebnych dla prawidlowego wzrostu wybranego kwiatka. Program odczytuje dane z czujnika podłączonego do komputera przez port szeregowy, porównuje odebrane dane z wymaganiami środowiskowymi rośliny oraz podaje jak czuje się roślina.

## Funkcjonalność
- Odczytywanie danych w czasie rzeczywistym przez port szeregowy
- Obliczanie średniej pomiarów z ostatnich 5, 30 i 60 minut
- Porównywanie warunków środowiska w pomieszczeniu z wymaganiami rośliny
- Funkcyjny interface graficzny dla użytkownika, w tym wyświetlanie wykresów
- Zapis danych do pliku txt
## GUI Layout

### Main Window:
- Wybranie rodzaju rośliny
- Nadanie roślinie imienia
- Przycisk submit pozwalający na rozpoczęcie analizy danych

### Sensor Data Window:
- Pokazywanie aktualnych pomiarów co sekunde oraz wyświetlanie średnich
- Pokazanie statusu kwiatka (czy środowisko jest odpowiednie)
- Przyciski pozwalalające na przejście do wykresu, zapisanie pomiarów i zamkięcie aplikacji

### Chart Window:
- Aktualizujące się w czasie rzeczywistym wykresy temperatury i wilgotności
- Przycisk back pozwalający na powrót do okna głównego aplikacji
