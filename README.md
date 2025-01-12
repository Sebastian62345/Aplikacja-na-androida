Serwis pogodowy z asynchronicznym pobieraniem danych z API. Opis; Tworzenie aplikacji pogodowej , która umożliwia użytkownikom pokazania pogody oraz warunkach atmosferycznych w jakim mogą występować w danej miejscowości.

HTML: To podstawowy szkielet strony internetowej, który zawiera formularz do wprowadzania miasta oraz przyciski do pobierania pogody i przeliczania temperatury. Jest również miejsce na wyświetlanie szczegółów pogodowych oraz zanieczyszczenia powietrza dla danego miasta.

O kodzie JS :

console.log("Weather app");: Wypisuje "Weather app" w konsoli.
getWeatherButton: Pobiera przycisk do pobierania pogody z dokumentu.
getWeatherInput: Pobiera pole wejściowe do wprowadzenia miasta z dokumentu.
displayWeather: Funkcja wyświetla informacje o pogodzie w elemencie HTML.
getAirPollution: Funkcja pobiera dane o zanieczyszczeniu powietrza z API OpenWeatherMap.
displayPollution: Funkcja wyświetla informacje o zanieczyszczeniu powietrza w elemencie HTML.
getWeather: Funkcja pobiera dane pogodowe i zanieczyszczenia powietrza dla podanego miasta z API OpenWeatherMap i wyświetla je na stronie.
convertTemperature: Funkcja przelicza temperaturę między jednostkami Celsiusza i Fahrenheita i wyświetla przeliczoną temperaturę na stronie.
convertTime: Funkcja konwertująca znacznik czasu na godzinę i minutę.
