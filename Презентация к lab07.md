# Презентация к лабораторной работе №7

----

# Тема:
## Поиск файлов. Перенаправление ввода-вывода. Просмотр запущенных процессов

----

## Российский Университет Дружбы Народов

### Факультет Физико-Математических и Естественных Наук

*Дисциплина: Операционные системы*

Студент: Мухамедияр Адиль

Группа: НКНбд-01-20

Москва, 2021г.

----

### Цель работы

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных. Приобретение практических навыков: по управлению процессами (и заданиями), по проверке использования диска и обслуживанию файловых систем.

----

### Ход работы:

1. Осуществил вход в систему, используя соответствующее имя пользователя.

![1f0718113ef25a8ba.png](https://raw.githubusercontent.com/adil-cpu/lab_07/main/img_07/1.PNG)

2. Записал в файл file.txt названия файлов, содержащихся в каталоге /etc. Дописал в этот же файл названия файлов, содержащихся в домашнем каталоге.

![2718070ee190d189c.png](https://raw.githubusercontent.com/adil-cpu/lab_07/main/img_07/2.PNG)

 
3. Вывел имена всех файлов из file.txt, имеющих расширение .conf, после чего записал их в новый текстовой файл conf.txt.

![3_1.png](https://raw.githubusercontent.com/adil-cpu/lab_07/main/img_07/3_1.PNG)

![3_2.png](https://raw.githubusercontent.com/adil-cpu/lab_07/main/img_07/3_2.PNG)

4. Определил, какие файлы в домашнем каталоге имеют имена, начинающиеся с символа c. Есть несколько вариантов, как сделать это:

![4.png](https://raw.githubusercontent.com/adil-cpu/lab_07/main/img_07/4.PNG)

5. Вывел на экран (по странично) имена файлов из каталога /etc, начинающиеся с символа h.

![5_1.png](https://raw.githubusercontent.com/adil-cpu/lab_07/main/img_07/5_1.PNG)

![5_2.png](https://raw.githubusercontent.com/adil-cpu/lab_07/main/img_07/5_2.PNG)

6. Запустил в фоновом режиме процесс, который будет записывать в файл ~/logfile файлы, имена которых начинаются с log.

![6.png](https://raw.githubusercontent.com/adil-cpu/lab_07/main/img_07/6.PNG)

7. Удалил файл ~/logfile.

![7.png](https://raw.githubusercontent.com/adil-cpu/lab_07/main/img_07/7.PNG)

8. Запустил из консоли в фоновом режиме редактор gedit.

![8_1.png](https://raw.githubusercontent.com/adil-cpu/lab_07/main/img_07/8_1.PNG)

![8_2.png](https://raw.githubusercontent.com/adil-cpu/lab_07/main/img_07/8_2.PNG)

9. Определил идентификатор процесса gedit, используя команду ps, конвейер и фильтр grep. Более простым способом определить этот идентификатор не получилось.

![9.png](https://raw.githubusercontent.com/adil-cpu/lab_07/main/img_07/9.PNG)

10.  Прочел справку (man) команды kill, после чего использовал её для завершения процесса gedit.

![10_1.png](https://raw.githubusercontent.com/adil-cpu/lab_07/main/img_07/10_1.PNG)

![10_2.png](https://raw.githubusercontent.com/adil-cpu/lab_07/main/img_07/10_2.PNG)

11.  Выполнил команды df и du, предварительно получив более подробную информацию об этих командах, с помощью команды man.

![11_1.png](https://raw.githubusercontent.com/adil-cpu/lab_07/main/img_07/11_1.PNG)

![11_2.png](https://raw.githubusercontent.com/adil-cpu/lab_07/main/img_07/11_2.PNG)

![11_3.png](https://raw.githubusercontent.com/adil-cpu/lab_07/main/img_07/11_3.PNG)

12.  Воспользовавшись справкой команды find, вывел имена всех директорий, имеющихся в домашнем каталоге.

![12_1.png](https://raw.githubusercontent.com/adil-cpu/lab_07/main/img_07/12_1.PNG)

![12_2.png](https://raw.githubusercontent.com/adil-cpu/lab_07/main/img_07/12_2.PNG)

----

### Вывод

Ознакомился с инструментами поиска файлов и фильтрацией текстовых данных, приобрел практические навыки: по управлению процессами (и заданиями), по проверке использования диска и обслуживанию файловых систем.

----
