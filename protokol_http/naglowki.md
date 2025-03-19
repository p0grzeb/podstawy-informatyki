# Nagłówki HTTP

## Nagłówki zapytania

1. **Accept**: Określa, jakie formaty odpowiedzi klient jest w stanie zaakceptować. W tym przypadku, klient akceptuje wszystkie typy mediów (`*/*`).
2. **User-Agent**: Informuje serwer, jaką przeglądarkę lub klienta HTTP używa klient, czyli użytkownik. W tym przypadku jest to `Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/134.0.0.0 Safari/537.36`.
3. **Referer**: Określa adres URL strony, z której pochodzi zapytanie. W tym przypadku jest to `https://pl.wikipedia.org/`, co oznacza, że zapytanie zostało wysłane ze strony Wikipedii w języku polskim.

## Nagłówki odpowiedzi

1. **Content-Type**: Określa typ zawartości w odpowiedzi serwera. W tym przypadku jest to `application/json`, co oznacza, że odpowiedź jest w formacie JSON.
2. **Date**: Data i godzina, kiedy odpowiedź została wysłana przez serwer. W tym przypadku odpowiedź została wysłana 19 marca 2025 roku o godzinie 13:25:12 GMT.
3. **Server**: Nazwa oprogramowania serwera, który obsłużył zapytanie. W tym przypadku jest to `gunicorn/19.9.0`, co oznacza, że serwer działa na silniku `gunicorn` w wersji 19.9.0.
