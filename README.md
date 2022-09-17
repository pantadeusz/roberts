# roberts
Pomoc do lasera

# Problemy

## 1

Chaotyczne ruchy na jednej z osi

### Objawy

Ruch w jednej z osi wyglada jak szarpanie się w obie strony, a na osi Z delikatnie opada

### Przyczyna i rozwiązanie

Problem ze sterowaniem silnikiem krokowym. Zasilanie działa, ale sterowanie nie.

Należy sprawdzić, czy kabel nie jest uszkodzony od silnika do sterownika (rozłączony, złamany, urwany), jeśli tak, to należy przywrócić styk

Jeśli kable są OK, to wymienić [stepstick]([https://duckduckgo.com](https://reprap.org/wiki/StepStick)).

## 2

Brak ruchu na jednej z osi

### Objawy

Maszyna nie porusza się wzdłuż jednej z osi. Nie słychać pracy silnika.

### Przyczyna i rozwiązanie

Problem ze sterowaniem silnikiem krokowym. Zasilanie działa, ale sterowanie nie.

Należy sprawdzić, czy kabel nie jest uszkodzony od silnika do sterownika (rozłączony, złamany, urwany), jeśli tak, to należy przywrócić styk

Jeśli kable są OK, to wymienić [stepstick]([https://duckduckgo.com](https://reprap.org/wiki/StepStick).

## 3

Na interfejsie webowym pokazuje się błąd ```Hardware Connection Error - check USB cable```

### Objawy

Nie można wykonać żadnego projektu. Jest wyświetlany błąd ```Hardware Connection Error - check USB cable```

### Przyczyna i rozwiązanie

Możliwe że jest rozłączony kabel USB między modułem na wieży [Raspberry Pi](https://en.wikipedia.org/wiki/Raspberry_Pi), albo jest jakaś bardzo poważna awaria modułu [Arduino](https://en.wikipedia.org/wiki/Arduino)

Należy sprawdzić kabel USB łączący oba urządzenia i w razie czego go spiąć, albo wymienić.

## 4

Maszyna nie rusza się, mimo wykonania programu.

### Objawy

Maszyna nie rusza się, mimo rozkazu wykonania zadania.

### Przyczyna i rozwiązanie

Zasilanie nie jest podłączone do elektroniki. Należy sprawdzić kable zasilające.

## 5

Maszyna przekasza się podczas ruchu na osi Z

### Objawy

Luźna jest jedna strona mostu. Wycina nierówno. Chodzi głośniej niż zwykle

### Przyczyna i rozwiązanie

Poluzowane sprzęgło przy silniku krokowym od strony "luźniejszej", albo poluzowana zębatka do paska zębatego od strony "luźniejszej".

Należy dokręcić kluczem imbusowym albo sprzęgło, albo zębatkę.

## 6

Maszyna nie rusza się na jednej z osi.

### Objawy

Maszyna nie rusza się na jednej z osi, ale wydaje dźwięki silnika.


### Przyczyna i rozwiązanie

Poluzowane łączenie silnika z elementem ruszającym maszynę w danej osi, na przykład poluzowane sprzęgło między silnikiem a śrubą trapezową osi Z.

Należy dokręcić sprzęgło łączące silnik z elementem który powinien się ruszać.
