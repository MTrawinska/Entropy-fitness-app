# Entropy-fitness-app 

## Opis dzialania

Określenie stanu zdrowia użytkownika w określonym przedziale czasowym.
Informacja o skladzie posiłków oraz aktyności fizycznej z wyliczeniem bilansu energetycznego.

## CEL PROJEKTU

### zarządzanie kontem użytkownika >> zapis do bazy
- podzial wg planu fitnesowego (heavy user/ light user/ normal)
- indykatory (BMI/ AMR/ BMR/ WHR)

### śledzenie wpisywanych kcal (dieta oraz aktywność fizyczna) >> zapis do bazy
- informacje o kaloriach w posilku (API us gov)
- kompozycja posilkow porcja
- informacje o wydatku energtycznym (scrap Harvard edu)
- plan fitnes wydatek energetyczny

### weryfikacja bilansu kalorycznego
- zliczenie przyjętych oraz spalonych kalorii w danym momencie wraz z przypisanymi przeliczeniami zmiany wagi
według podziału na użytkownika

### 'cardio bunny' -  trening biegowy >> zapis do bazy
- pogoda Warszawa (API weatherdata)
- ocena treningu (REST Django > serializer>> JSON)

### znizka email
- podanie adresu email oraz wyslanie bonu zniżkowego 'on demand'

### 'gentle reminder'
- przypomnienie o powrocie do aplikacji (crone email)

### wersja hiszpanska 


### Requirements: 
Vanilla Js es6, CSS3, HTML5, Django2.2.7, Python 3.5

### Schemas

Project layout

![alt mapping](https://github.com/MTrawinska/Entropy-fitness-app/blob/master/entropy1.png)

Project slicing

![alt diagram](https://github.com/MTrawinska/Entropy-fitness-app/blob/master/entropy2.png)

!CODE ON DEMAND

Interested? Please contact me to see the code
