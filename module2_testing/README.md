## Задание:

1. Сформулируйте набор требований к «идеальному телефону». Пофантазируйте.
2. Сформулируйте набор вопросов, которые позволили бы улучшить следующее требование: «Консольное приложение должно получать из командной строки имена входного и выходного файлов, после чего преобразовывать текст во входном файле в кодировку UTF-8 и записывать результат в выходной файл».
3. Сформируйте чек-лист для тестирования следующего требования: «Консольный калькулятор получает из командной строки два числа и операцию, после чего выполняет операцию и отображает в консоли результат».
4. На основе чек-листа к требованию (см. предыдущее задание) «Консольный калькулятор получает из командной строки два числа и операцию, после чего выполняет операцию и отображает в консоли результат» оформите 2-3 полноценных тест-кейса.
5. Ситуация: при попытке загрузить на Facebook фотографию размером более 200 Mb через какое-то время соединение с сервером просто обрывается, и операция не выполняется. Опишите это в виде баг-репорта.
##
## Ответы:
#
### 		1 задание
1.	Цвет идеального телефона должен быть чёрным
2.	Диагональ идеального телефона должна быть не менее 6.1 дюйма
3.	Фотокамера идеального телефона должна быть не менее 12 мп
4.	Дисплей идеального телефона должен быть серсорным
5.	Объектив идеального телефона должен быть шестилинзовым
6.	У идеального телефона должна быть доступна функция видеозаписи
7.	Частота кадров видеосъемки у идеального телефона должна быть не менее 60
8.	Фронтальная камера идеального телефона должна быть не менее 7 мп
9.	Частота процессора идеального телефона должна быть не менее 2.5 ГГц
10.	Количество ядер процессора идеального телефона должно быть равно 6
11. Встроенная память идеального телефона должна быть не менее 64 Гб
12.	Оперативная память идеального телефона должна быть не менее 3 Гб
13.	У идеального телефона должен быть реализован аудиоплеер
14.	У идеального телефона должен быть реализован видеоплеер
15.	У идеального телефона должны быть стереодинамики
16.	Количество разъёмов для SIM-карты идеального телефона должно быть равно 1
17.	Емкость аккумулятора идеального телефона должн быть не менее 2500 мАч
18.	Материал корпуса идеального телефона должен быть металлическим
19. Идеальный телефон должен иметь защиту от влаги и пыли
20.	Идеальный телефон должен иметь гарантию от производителя
21.	У идеального телефона должен быть Bluetooth
22.	У идеального телефона должен быть NFC
23.	У идеального телефона год выпуска должен быть не ранее 2018 года
24.	У идеального телефона вес должен быть менее 200 г
25.	У идеального телефона разъем для зарядки должен быть Lightning
26.	Ширина корпуса идеального телефона должна быть не более 80 мм
27.	Высота корпуса идеального телефона должна быть не более 152 мм
28.	Толщина корпуса идеального телефона должна быть не более 8.5 мм
##
### 		2 задание
1.	Имена входного и выходного файлов должен вводить пользователь?							
2.	Что произойдет, если из командной строки консольное приложение получит имя только входного файла?							
3.	Что произойдет, если из командной строки консольное приложение получит имя только выходного файла?							
4.	Что произойдёт, если из командной строки консольное приложение не получит ни одного имени файла?							
5.	Какой формат имени должен иметь входной файл?							
6.	Какой формат имени должен иметь выходной файл?							
7.	На каком языке может быть введено имя входного файла?							
8.	На каком языке может быть введено имя выходного файла?							
9.	Имена входного и выходного файлов необходимо записать через точку, запятую, пробел или другой знак?							
10.	Что произойдёт, если приложение из командной строки получит имя входного файла, который не создан?							
11.	Кто должен создавать выходной файл, приложение или пользователь?							
12.	Как приложение узнает расположение входного и выходного файла? Должен ли пользователь прописать путь к ним?							
13.	В выходной файл должен записываться только текст, преобразованный в кодировку UTF-8, или еще и исходный текст?							
14.	После того, как приложение запишет результат в выходной файл, должно ли появиться оповещение?							
15.	После того, как приложение запишет результат в выходной файл, приложение начнет работу заново или закончит свою работу?							
##
### 		3 задание


ID|Priority|Module|Idea	
------------- | ------------- | ------------- | ------------- |
1 | B |	Консоль	 |	Ввод символа отличного от числа вместо одного из аругементов
4 | B |	Консоль	 |	Ввод невалидного названия операции
6|		B	|Консоль|		Ввод вместо операции соответствующего ей знака (например, +,-,*,/)
8	|	A|	Консоль	|	Ввод двух чисел через любой знак припинания (точка, запята, точка с запятой)
8	|	A|	Консоль	|	Ввод двух чисел через любой непечаемый символ
11	|	A|	Консоль	|	Отделить операцию при вводе от чисел любым знаком припинания
11	|	A|	Консоль	|	Отделить операцию при вводе от чисел любым непечаемым символом
14	|	B|	Консоль	|	Ввод одного дробного числа, а другого целочисленного
15	|	B|	Консоль	|	Ввод названия операции на различных языках
17	|	B|	Консоль	|	Ввод названия операции в разном регистре (строчные, прописные)
19	|	B|	Консоль	|	Ввод одного отрицательного числа, а другого положительного
20	|	A|	Консоль	|	Результат операции с ошибочным исходом (например, сделать вторым числом 0 и ввести операцию деления)
21	|	A|	Консоль	|	Результат операции при вводе валидных числел и валидного названия операции
22	|	B|	Консоль	|	Ввести валидное название операции, но не ввести числа
23	|	B|	Консоль	|	Ввести валидное название операции, но не вводить одно из двух чисел
24	|	B|	Консоль	|	Ввести валидные числа, но не вводить название операции

##

### 		4 задание
ID	|Priority|	Req. ID |	Module	|	Test Description|	Expected Result
--------- | ------- | ------------- | ------------- |	------------- | -------------		
1|	B|  3 зад-е|	Консоль	|	"Вместо любого из двух чисел ввести букву |	Отображение в консоли сообщения о 
 | | | | Приготовления: отсутствуют | некорректности введенного числового 
 | | | | 1. Открыть приложение |значения и предложение ввести число 
 | | | | 2. Ввести в качестве значения первого числа любую букву"|ещё раз
.
2|	B|	3 зад-е|  Консоль	|	"Ввести название операции прописными буквами |Отображение в консоли правильного
 | | | | Приготовления: отсутствуют |результата вычислений
 | | | | 1. Открыть приложение |
 | | | | 2. Ввести два валидных числа |
 | | | | 3. Ввести название валидной операции прописными буквами"|
.
3|	B|	3 зад-е|	Консоль|	"Ввести валидные числа, но не вводить название операции |Отображение в консоли сообщения о 
 | | | | Приготовления: отсутствуют |некорректности введенного названия 
 | | | | 1. Открыть приложение |операции и предложение ввести 
 | | | | 2. Ввести валидное значение первого числа |название операции ещё раз
 | | | | 3. Ввести валидное значение второго числа |
 | | | | 4. Не вводить название операции"	|

##
### 		5 задание
 №	|Summary|	Steps to reproduce	|Repro-ducibility|	Severity	|Priority|	Symptom|	Attachment
  --------- | ------------- | ------------- | ------------- | -------------| ------------- |	------------- | -------------	
1 | При попытке загрузить на |1. Открыть Facebook  							 | Всегда	| Средняя	| Обычная | Не выполнение операции| -
  | Facebook фотографию      |2. Загрузить фотографию размером более 200 Mb  | 			| 			| 		  | 					  | 
  | размером более 200 Mb    |3. Увидеть, что соединение с сервером оборвано"| 			| 			| 		  | 					  | 
  | через какое-то время     |**Ожидаемый результат:**									 | 			| 			| 		  | 					  | 
  | соединение с сервером    |фотография успешно загружается на Facebook.												 | 			| 			| 		  | 					  | 
  | обрывается, и операция   |**Фактический результат:**											 | 			| 			| 		  | 					  | 
  | не выполняется           |соединение с сервером обрывается и операция не выполняется.|||||
  | |**Требование:** 3 задание	 |||||

	
