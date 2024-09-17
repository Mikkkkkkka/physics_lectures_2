# Задание ко 2й лекции по Физическим основам компьютерных систем

Вариант 2 - программа, визуализирующая траекторию движения тела, брошенного под углом к горизонту.

## Использованные библиотеки:

- numpy (библиотека для математических операций)
- matplotlib (библиотека для построения графиков)

## Физические формулы:

V0 - начальная скорость
Vx, Vy - моментальная скорость по осям Ox и Oy соответственно
V - полная моментальная скорость
g = 9.81 - ускорение свободного падения 

t - время 
angle - угол броска

--- 

Vx = V0 * cos(angle)
Vy = V0 * sin(angle)

## Сценарий взаимодействия с программой:

1. Запустить программу (main.exe)
2. В терминале, программа попросит ввести начальные данные: угол, начальную скорость, начальную высоту
3. После ввода начальных данных терминал закроется и появится визуальный интерфейс, в котором будут три графика: траектория движения тела, графики зависимости скорости от времени, и график зависимости координат (x и y) от времени.

### Скриншоты

#### Терминал
![](/Terminal.png)

#### Визуальный интерфейс
![](/VIscreenshot.png)
