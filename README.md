# Итоговая проверочная работа

## Задание:
1. [Создать репозиторий на GitHub](#task1)
2. [Нарисовать блок схему алгоритма](#task2)
3. [Снабдить репозиторий оформленным текстовым описанием (файл Readмe.md)](#task3)
4. [Написать программу, решающую поставленную задачу](#task4)
5. [Использовать контроль версий в работе над этим небольшим проектом Не должно быть так, что всё залито одним коммитом. 
Как минимум этапы 2, 3 и 4 должны быть расположены в разных коммитах.](#task5)

_____________________________________________________________________________________________________________________________

## Решение:
### <a name="task1"></a>1. Создать репозиторий на GitHub:

Созданный репозиторий -> [https://github.com/Mart9nov/Verification_work.git][id1]

### <a name="task2"></a>2. Нарисовать блок схему алгоритма:

Блок схема алгоритма -> [https://github.com/Mart9nov/Verification_work/blob/main/BS.png][id2]

### <a name="task3"></a>3. Снабдить репозиторий оформленным текстовым описанием (файл Readme.md):

Файл Readme.md -> [https://github.com/Mart9nov/Verification_work/blob/main/README.md][id3]

### <a name="task4"></a>4. Написать программу, решающую поставленную задачу:

Файл Program.cs -> [https://github.com/Mart9nov/Verification_work/blob/main/Program][id4]

>***Задача:*** Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа.<br/>*Первоначальный массив можно ввести с клавиатуры либо задать на старте выполнения алгоритма.*<br/>*При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.*

В коде используются следующие операторы:
```
// Для преобразования строки в массив, где разделителем между элементами является запятая,
// используется оператор .Split :
string Line = "стол,стул,стена";
string[] ArrayInput = Line.Split(",");
//результат выполнения:
// ArrayInput[0] = "стол"
// ArrayInput[1] = "стул"
// ArrayInput[2] = "стена"

//Для преобразования массива в строку, где разделителем между элементами является запятая,
//используется оператор .Join :
string MergerToString = string.Join(",", ArrayInput);
//результат выполнения:
//MergerToString = "стол,стул,стена"

// Для увеличения размера массива с сохранением данных, находящихся в нём,
// используется оператор Array.Resize :
string[] ArrayOutput = new string[1];
ArrayOutput[0]="Элемент1";
Array.Resize(ref ArrayOutput, ArrayOutput.Length + 1);
ArrayOutput[1]="Элемент2";
//результат выполнения:
// ArrayOutput[0]="Элемент1"
// ArrayOutput[1]="Элемент2"
```
### <a name="task5"></a>5. Использовать контроль версий в работе над этим небольшим проектом: не должно быть так что все залито одним коммитом.

Коммиты -> [https://github.com/Mart9nov/Verification_work/commits/main][id5]


[id1]: https://github.com/Mart9nov/Verification_work.git
[id2]: https://github.com/Mart9nov/Verification_work/blob/main/BS.png
[id3]: https://github.com/Mart9nov/Verification_work/blob/main/README.md
[id4]: https://github.com/Mart9nov/Verification_work/blob/main/Program
[id5]: https://github.com/Mart9nov/Verification_work/commits/main
