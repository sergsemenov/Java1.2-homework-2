# Отчет о тестировании приложения Precision

## Краткое описание

16.02.2020 было создано и протестировано java-приложение Precision с кодом
```java
public class Main {
    public static void main(String[] args) {
        double regularBonus = 0.3;
        double specialBonus = 0.6;
        double totalBonus = regularBonus + specialBonus;
        System.out.println(totalBonus);
    }
}
```

## Описание тестов

Код приложения размещен в новом проекте в среде IntelliJ IDEA, запущен на исполнение в режиме smoke-теста, процесс завершился с кодом 0 без ошибок.

## Результат 

Приложение запустилось и вернуло в консоли "0.8999999999999999". Ожидалось значение "0.9". 
 
 Оформлен [баг-репорт](https://github.com/sergsemenov/Java1.2-homework-2/issues/1).