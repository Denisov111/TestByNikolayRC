# TestByNikolayRC
Тестовое задание на вакансию «Разработчик C#»

Имеется система, в которой радиопередатчик перемещается по случайной траектории в декартовой системе координат (2 оси). Через равные промежутки времени (1 секунда) радиопередатчик отправляет сигнал, движущийся в пространстве, к 3 статичным радиоприемникам с заданными координатами, которые измеряют время прохождения этого сигнала от источника до приемника с погрешностью в 5%. 
Практическое задание состоит из двух частей:
1. Необходимо восстановить траекторию движения источника в пространстве, используя эту информацию, и вывести ее в файл. Помимо этого, также необходимо визуализировать полученную траекторию в графическом интерфейсе пользователя.
2. Необходимо создать эмулятор данной системы со следующими возможностями:
Расположение радиоприемников задает пользователь;
Пользователь может перемещать радиопередатчик;
Система рисует траекторию за радиопередатчиком в реальном времени;
Пользователь может сохранить полученные результаты в файл. Формат файла идентичен формату входных данных, и может быть использован вместо входного файла.
Формат входных данных - текстовый:
x1,y1,x2,y2,x3,y3 		: координаты статичных приемников
dt1,dt2,dt3			: время прохождения сигнала до трех точек, 1 измерение
…
d1,d2,d3			: время прохождения сигнала до трех точек, n измерение
Формат выходных данных - текстовый:
x,y				: точка начала движения
...
x,y				: точка окончания движения

Пример входных и выходных данных во вложении.
Программа должна быть написана на C#, использование сторонних библиотек не воспрещено. Строгих ограничений по визуализации также не имеется. Главное, чтобы происходящее в ней было понятно человеку, прочитавшему этот документ.
Следует учитывать, что на выходе ожидается лишь приблизительная траектория, в которой допускается погрешность, ввиду шумных входных данных.
Подход к структуре кода приложения будет учитываться в оценке.