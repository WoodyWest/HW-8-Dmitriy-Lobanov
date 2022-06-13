# Задача создать информационную систему позволяющую работать с сотрудниками некой компании \ студентами вуза \ учениками школы


## Порядок работы информационной системы: 

Программа генерирует (или уже имеет) готовый файл *school_list* который содержит например ID, ФИО, ДР, успеваемость, пол ученика. Пользователю предлагается на выбор отсортировать данные в файле, далее программа выводит результат на экран.  

## Структура информационной системы: 

1. модуль Processing_Data  
функции  
def append_info\
def delete_info\
(+ функция генерации)\
возвращает обработанный список  
пишет - Александр https://github.com/Aaallleeexxx97

2. модуль Editor_file  
функции  
def read_file\
def write_file\
def create_test_file\
def save_file\
1) Считывает инф из БД
2) Кладет в перем
3) Получает список для сохр
4) Сохраняет полученную инф в новый файл
пишет - Снежана https://github.com/SnezhannaPristavka 

3. модуль Processing_file
def ...
1) Получает данные (выбор юзера)
2) Получаете исходный список
3) Формирует необходимый список
4) Отдает список
пишет - Всеволод https://github.com/PEBU3OP1

4. модуль Print_List 
функция  
def console_print  
1) Получает список 
2) Выводит его на консоль
3) Возвращает список
пишет- Анна https://github.com/AnnaAdjikiss

5. модуль User_Interface  
функция  
def user_choice  
Обращается к  пользователю для выбора режима
1) Вывод всей инф
2) Вывод всех ДР
3) Вывод успеваемости
4) Вывод пола
Возвращает выбор пользователя
пишет- Илья https://github.com/ILYA-NASA