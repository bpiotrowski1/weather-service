Utwórz aplikację zwracającą z poziomu konsoli dane pogodowe dla wskazanego miasta. W zwracanych danych powinna znajdować obecna temperatura. Adres API oraz dane dostępowe odczytaj z konfiguracji aplikacji.

Opcjonalnie: 

Dane źródłowe powinny być pobierane z zewnętrznego API i cache'owane na poziomie aplikacji. Tj. jeśli w ciągu ostatnich 60 minut wystąpiło zapytanie o dane miasto, należy zwrócić zapamiętane dane. W przeciwnym wypadku należy pobrać dane z zewnętrznego serwera i zapisać je w aplikacji.

Opcjonalnie:

Zaimportuj listę dostępnych miast i użyj jej do walidacji wpisanego miasta
Rozszerz aplikację o możliwość wyświetlenia prognozy pogody dla kolejnych dni

API: https://openweathermap.org/api 
Lista miast: http://bulk.openweathermap.org/sample/city.list.json.gz