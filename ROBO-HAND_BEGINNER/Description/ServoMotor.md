# Сервопривод: краткое введение

[Сервопривод](https://habr.com/ru/articles/750222/#:~:text=22-,%D0%A3%D1%81%D1%82%D1%80%D0%BE%D0%B9%D1%81%D1%82%D0%B2%D0%BE%20%D1%81%D0%B5%D1%80%D0%B2%D0%BE%D0%BF%D1%80%D0%B8%D0%B2%D0%BE%D0%B4%D0%B0,-%D0%94%D0%BB%D1%8F%20%D1%81%D0%B2%D0%BE%D0%B5%D0%B9%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B) - это устройство совмещающее в себе двигатель постоянного вращения с редуктором изменяющим скорость вращения и силу, а также считывающим устройством (энкодером), позволяющим получать угол положения ведущего вала и предеравать его на контроллер, также можно управлять положением и скоростью вращения передавая на контроллер параметры из вне.

## Подключение  
Большинство популярных решений для Arduino управляется при помощи контроллера, а к плате Arduino подключаются при помощи  выходного шлейфа из трёх проводов (питание - красный, земля - коричневый,  - желтый). *Далее по проекту будет использоваться сервопривод модели MG996R с углом поворота 180 градусов.*  

**Общий вид и схема с размерами **
<picture>
 <source media="(prefers-color-scheme: dark)" srcset="https://github.com/EngineerZavoda/ROSE-Robotic-Open-Source-Education/blob/9514f9716fee31dc185fbe311bff393d21c90672/ROBO-HAND_BEGINNER/Image/ServoMotor/MG996R_FIG1.png">
 <source media="(prefers-color-scheme: light)" srcset="https://github.com/EngineerZavoda/ROSE-Robotic-Open-Source-Education/blob/9514f9716fee31dc185fbe311bff393d21c90672/ROBO-HAND_BEGINNER/Image/ServoMotor/MG996R_FIG1.png">
 <img alt="YOUR-ALT-TEXT" src="https://github.com/EngineerZavoda/ROSE-Robotic-Open-Source-Education/blob/9514f9716fee31dc185fbe311bff393d21c90672/ROBO-HAND_BEGINNER/Image/ServoMotor/MG996R_FIG1.png">
</picture>

Подключение можно выполнить как на прямую используя имеющиеся пины на плате Arduino [Схема подключения прямая](https://github.com/EngineerZavoda/ROSE-Robotic-Open-Source-Education/blob/de13cb19e74fd2e6127f4e5552f6b4b85e8dfdf0/ROBO-HAND_BEGINNER/Image/ServoMotor/DirectConnection.gif), так и с импользованием плат расширения которые позволяют как облегчить подключение так и увеличить функциональность. В текущем проекте будет использованна плата расширения [...](...).
