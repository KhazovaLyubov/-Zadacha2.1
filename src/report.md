Отчёт о тестировании приложения "Money Transfer"

Задача:
Для проверки пополнения счета в банке был написан код в IDEA:

       < public class Main {
             public static void main (String[]args) {
                 int balance = 2_000_000_000;
                 int transfer = 500_000_000;
                 int total = balance + transfer;
             System.out.println(total);>
    
    Результат - отрицательное число


  


Описание тестов
Проводилось функциональное тестирование

Результаты
100% не успешных тестов

Ссылки на баг-репорты
https://github.com/KhazovaLyubov/-Zadacha2.1/issues/1

Общие рекомендации
Необходимо устранить ошибку в коде так, чтобы программа верно суммировала числа и не выдавала отрицательный результат
