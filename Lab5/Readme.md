# Лабораторная работа №5
## Исследование инструментов классификации библиотеки Scikit-learn 
В качестве набора данных для классификации выбраны Ирисы Фишера. 

Выбранные классификаторы:
1. Линейный классификатор с SGD-обучением
2. Метод дерева решений
3. Метод гауссовских процессов

Для обучения были взяты все признаки.

### Результаты работы классификаторов
### SGD: 

![image](https://user-images.githubusercontent.com/71949457/210827718-7bc26d11-9fe7-4091-b8ce-1ad09771da1e.png)

Точность составила 62%

### DT: 

![image](https://user-images.githubusercontent.com/71949457/210827900-5ff9c18a-1f24-4d74-b553-92427a573cf8.png)

Точность составила 93%

### GP:

![image](https://user-images.githubusercontent.com/71949457/210828008-cd347ea3-3c1a-495c-87f6-87b59257c70e.png)

Точность составила 95%

Вывод: для данного набора данных лучший результат показал метод гауссовских процессов - 95%, 
следом метод дерева решений - 93% и самая низкая точность оказалась у метода с SGD-обучением - 62%.