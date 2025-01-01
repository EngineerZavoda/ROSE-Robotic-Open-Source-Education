# Сервопривод: краткое введение

[Сервопривод](https://habr.com/ru/articles/750222/#:~:text=22-,%D0%A3%D1%81%D1%82%D1%80%D0%BE%D0%B9%D1%81%D1%82%D0%B2%D0%BE%20%D1%81%D0%B5%D1%80%D0%B2%D0%BE%D0%BF%D1%80%D0%B8%D0%B2%D0%BE%D0%B4%D0%B0,-%D0%94%D0%BB%D1%8F%20%D1%81%D0%B2%D0%BE%D0%B5%D0%B9%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B) — это устройство, совмещающее в себе двигатель постоянного вращения с редуктором, который изменяет скорость вращения и силу, а также считывающее устройство (энкодер). Эндкодер позволяет получать угол положения ведущего вала и передавать его на контроллер. Также можно управлять положением и скоростью вращения, передавая параметры на контроллер извне.

<table>
	<tr>
    <td colspan="2" align="center">
      Общий вид и схема с размерами
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://github.com/EngineerZavoda/ROSE-Robotic-Open-Source-Education/blob/9514f9716fee31dc185fbe311bff393d21c90672/ROBO-HAND_BEGINNER/Image/ServoMotor/MG996R_FIG1.png" alt="MG996R Servomotor" height="170" width="250">
    </td>
    <td>
      <i>Далее по проекту будет использоваться сервопривод модели MG996R с углом поворота 180 градусов.</i>
    </td>
  </tr>
	<tr>
    <td colspan="2" align="center">
      Прямое подключение к Arduino
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://github.com/EngineerZavoda/ROSE-Robotic-Open-Source-Education/blob/bc0417dbb39ec42fefeef30e8f18cc052103d3f8/ROBO-HAND_BEGINNER/Image/ServoMotor/DirectConnection.gif" alt="Direct Connection Example" height="170" width="250">
    </td>
    <td>
      Большинство популярных сервоприводов для Arduino управляется при помощи контроллера, а к плате Arduino подключаются при помощи выходного шлейфа из трёх проводов (питание — красный, земля — коричневый, сигнал — жёлтый).
    </td>
  </tr>
	<tr>
    <td colspan="2" align="center">
      Плата расширения
  	</td>
  </tr>
  <tr>
    <td>
      <img src="https://github.com/EngineerZavoda/ROSE-Robotic-Open-Source-Education/blob/a8b87e8602bc7f74fda92e55c75d24c96354b590/ROBO-HAND_BEGINNER/Image/Arduino/SensorShield.jpg" alt="Arduino Sensor Shield" height="170" width="250">
    </td>
    <td>
      Использование плат расширения, позволяет как облегчить подключение, так и увеличить функциональность. В текущем проекте будет использована плата расширения Arduino Sensor Shield V4.0.
    </td>
  </tr>
</table>
