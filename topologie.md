# Topologie Sieci

## Sieci Fizyczne
Sieci fizyczne odnoszą się do fizycznego ułożenia kabli, urządzeń i połączeń. Przykłady:
- **Topologia magistrali** (Bus): jest to topologia, w której wszystkie urządzenia są podłączone do jednej wspólnej linii transmisyjnej.
  - Wady: Awaria kabla powoduje przerwanie komunikacji całej sieci.
  - Zalety: Prosta do zaimplementowania i tania w budowie.
  - Gdzie stosowane: Stosowana w małych sieciach, gdzie koszt i prostota są kluczowe.

- **Topologia pierścienia** (Ring): urządzenia są połączone w zamknięty pierścień, a dane krążą w jednym kierunku.
  - Wady: Awaria jednego urządzenia przerywa działanie całej sieci.
  - Zalety: Niskie opóźnienia transmisji, dobra w przypadku dużych sieci.
  - Gdzie stosowane: Często w sieciach WAN, szczególnie w starszych systemach.

- **Topologia gwiazdy** (Star): urządzenia są połączone z centralnym punktem (np. przełącznikiem).
  - Wady: Awaria centralnego punktu powoduje przerwanie komunikacji całej sieci.
  - Zalety: Łatwa w konfiguracji i zarządzaniu, łatwo dodawać nowe urządzenia.
  - Gdzie stosowane: Powszechnie w lokalnych sieciach komputerowych (LAN).

## Sieci Logiczne
Sieci logiczne opisują sposób przesyłania danych między urządzeniami, niezależnie od fizycznej struktury. Przykłady:
- **Punkt-punkt** (Point-to-Point): jest to topologia, w której dane są przesyłane bezpośrednio między dwoma urządzeniami.
  - Wady: Ograniczona liczba urządzeń, nie ma elastyczności w rozbudowie.
  - Zalety: Prosta i wydajna, idealna do łączy dedykowanych.
  - Zastosowanie: Połączenia między dwoma urządzeniami, np. łącza dedykowane w telekomunikacji.

- **Przekazywanie żetonu** (Token Passing): dane są przesyłane w sieci przez urządzenia, które posiadają specjalny "żeton" umożliwiający im nadawanie.
  - Wady: Potrzebny jest mechanizm kontroli, aby zapobiec kolizjom.
  - Zalety: Zmniejsza ryzyko kolizji w porównaniu do innych metod dostępu.
  - Zastosowanie: Stosowane w starszych sieciach, takich jak Token Ring.

- **Wielodostępowa** (Multiple Access): polega na tym, że wszystkie urządzenia mogą nadawać dane w tym samym czasie, ale z kontrolą dostępu.
  - Wady: Kolizje mogą występować, jeśli urządzenia nadadzą dane w tym samym czasie.
  - Zalety: Umożliwia efektywne wykorzystanie medium w sieci.
  - Zastosowanie: Sieci Ethernet oraz inne technologie, które umożliwiają współdzielenie medium transmisyjnego.


