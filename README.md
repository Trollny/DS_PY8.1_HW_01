# Проект 0. Угадай число

## Оглавление  
[1. Описание проекта](README.md#Описание-проекта)  
[2. Какой кейс решаем?](README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](README.md#Этапы-работы-над-проектом)  
[5. Результат](README.md#Результаты)    
[6. Выводы](README.md#Выводы) 

### Описание проекта    
Угадать загаданное компьютером число за минимальное число попыток.

:arrow_up:[к оглавлению](README.md#Оглавление)


### Какой кейс решаем?    
Нужно написать программу, которая угадывает число за минимальное число попыток

**Условия соревнования:**  
- Компьютер загадывает целое число от 0 до 100, и нам его нужно угадать. Под «угадать», подразумевается «написать программу, которая угадывает число».
- Алгоритм учитывает информацию о том, больше ли случайное число или меньше нужного нам.

**Метрика качества**     
Результаты оцениваются по среднему количеству попыток при 1000 повторений

**Что практикуем**     
- Учимся писать хороший код на python;
- Учимся работать с IDE;
- Учимся работать с GitHub.


### Краткая информация о данных
....
  
:arrow_up:[к оглавлению](README.md#Оглавление)


### Этапы работы над проектом  
В рамках проекта реализованы 3 алгоритма угадывания числа:
1) Выбор случайных чисел из диапазона угадывания до тех пор, пока загаданное число не будет найдено.
2) Выбор случайного числа из диапазона угадывания с последующим увеличением или уменьшением данного числа (в зависимости от того, меньше оно или больше загаданного) пока загадонное число не будет обнаружено.
3) Выбор случайного числа из диапазона угадывания. Каждое следующее число определяется как среднее между ранее полученным числом и соответсвующей границей диапазона:
    
    **верхней** - если полученное число меньше загаданного. Нижняя граница корректируется;
    
    **нижней** - если полученное число больше загаданного. Верхняя граница корректируется.

:arrow_up:[к оглавлению](README.md#Оглавление)


### Результаты:  
Третий вариант алгоритма угадывания сокращает количество попыток в среднем до **5**.

:arrow_up:[к оглавлению](README.md#Оглавление)


### Выводы:  
- В рамках данного проекта был реализован алгоритм позволяющий угадать, задуманное компьютером число, в среднем за пять попыток;
- Проект был реализован в среде разработки IDE - VS Code;
- 
- Проект был оформлен и загружен на GitHub. 

:arrow_up:[к оглавлению](README.md#Оглавление)


Если информация по этому проекту покажется вам интересной или полезной, то я буду очень вам благодарен, если отметите репозиторий и профиль ⭐️⭐️⭐️-дами
