# **Задача №2 - "Менеджер Товаров" (Rich Model)"**

Создать "умную" модель продуктов

Что нужно сделать:

1.    Создайте новую ветку на базе ветки, в которой вы решали первую задачу
2.    Реализуйте в классе Product метод public boolean matches(String search), который определяет, подходит ли продукт поисковому запросу исходя из названия
3.    Переопределите этот метод в дочерних классах, чтобы они сначала вызывали родительский метод и только если родительский метод вернул false, тогда проводили доп.проверки (Book - по автору, Smartphone - по производителю).
4.    Уберите из менеджера все instanceof и метод matches, т.к. теперь у вас "умные" модели и благодаря переопределению методов вам этот код больше не нужен
5.    Зато теперь вам нужны unit-тесты на методы ваших умных моделей (напишите их)
6.    Удостоверьтесь, что ранее написанные тесты на менеджера (из решения задачи 1) проходят

