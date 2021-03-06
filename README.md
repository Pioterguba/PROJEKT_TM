# PROJEKT_TM


## Cel: Wyświetlenie temperatury w stopniach Celsjusza na wyświetlaczu przy pomocy czujnika temperatury 



## Elementy

* Wyświetlacz LCD 2x16
* Konwerter I2C
* Czujnik temperatury DS18B20 - cyfrowy 1-wire THT
* Arduino UNO
	
## Linki

https://botland.com.pl/konwertery-pozostale/2352-konwerter-i2c-dla-wyswietlacza-lcd-hd44780-5903351248693.html

![img](./konwerter.jpg)

https://botland.com.pl/cyfrowe-czujniki-temperatury/165-czujnik-temperatury-ds18b20-cyfrowy-1-wire-tht-5904422366513.html

![img](./czujniktemp.jpg)

https://allegro.pl/oferta/zestaw-startowy-do-arduino-uno-r3-atmega328-ch340-10102800766  

![img](./zestawarduino.jpg)

https://modulosy.pl/wyswietlacze-alfanumeryczne-i-graficzne/338-wyswietlacz-lcd-2x16-1602-niebieski-ze-sterownikiem-hd44780-konwerter-i2c-5903689131766.html

![img](./LCD.jpg)

## Budowa

Lutujemy konwerter I2C do wyświetlacza LCD i podłączamy w następujący sposób 

* GND > GND 
* VCC > 5V
* SDA > A4
* SCL > A5


Następnie łączymy nóżki czujnika z płytką stykową w sposób jaki przedstawiono to w dokumentacji.


![img](./temperatura1.jpg)

![img](./temperatura2.jpg)

## Wyniki

![img](./Wyniki.jpg)

## KOD
![img](./kod.jpg)
