# Сервопривод: краткое введение

[Сервопривод](https://habr.com/ru/articles/750222/#:~:text=22-,%D0%A3%D1%81%D1%82%D1%80%D0%BE%D0%B9%D1%81%D1%82%D0%B2%D0%BE%20%D1%81%D0%B5%D1%80%D0%B2%D0%BE%D0%BF%D1%80%D0%B8%D0%B2%D0%BE%D0%B4%D0%B0,-%D0%94%D0%BB%D1%8F%20%D1%81%D0%B2%D0%BE%D0%B5%D0%B9%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B) - это устройство совмещающее в себе двигатель постоянного вращения с редуктором изменяющим скорость вращения и силу, а также считывающим устройством (энкодером), позволяющим получать угол положения ведущего вала и предеравать его на контроллер, также можно управлять положением и скоростью вращения передавая на контроллер параметры из вне.

## Подключение  
Большинство популярных решений для Arduino управляется при помощи контроллера, а к плате Arduino подключаются при помощи  выходного шлейфа из трёх проводов (питание - красный, земля - коричневый,  - желтый). *Далее по проекту будет использоваться сервопривод модели MG996R с углом поворота 180 градусов.*   

**Общий вид сервопривода**
<picture>
 <source media="(prefers-color-scheme: dark)" srcset="https://github.com/EngineerZavoda/ROSE-Robotic-Open-Source-Education/blob/941c01ec695bbc355c71a3d1c1845f7b24092576/ROBO-HAND_BEGINNER/Image/ServoMotor/MG996R.jpg">
 <source media="(prefers-color-scheme: light)" srcset="hhttps://github.com/EngineerZavoda/ROSE-Robotic-Open-Source-Education/blob/941c01ec695bbc355c71a3d1c1845f7b24092576/ROBO-HAND_BEGINNER/Image/ServoMotor/MG996R.jpg">
 <img alt="YOUR-ALT-TEXT" src=srcset="https://github.com/EngineerZavoda/ROSE-Robotic-Open-Source-Education/blob/941c01ec695bbc355c71a3d1c1845f7b24092576/ROBO-HAND_BEGINNER/Image/ServoMotor/MG996R.jpg">
</picture>  
  
- [Схема с размерами](Image\ServoMotor\MG996R_PLAN.png).

Подключение можно выполнить как на прямую используя имеющиеся пины на плате Arduino [Схема подключения прямая](...), так и с импользованием плат расширения которые позволяют как облегчить подключение так и увеличить функциональность. В текущем проекте будет использованна плата расширения [...](...).
