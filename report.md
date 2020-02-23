# Отчёт о тестировании 
## Краткое описание
22.02.2020 было проведено тестирование Precision

В результате тестирования выявлены следующие дефекты:
 * [При выполнении кода появляется значение 0.899999999999999](https://user-images.githubusercontent.com/60143597/75119640-cc8b0480-5695-11ea-8949-f0cf161b8e68.png)

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:
* [Входные данные в Задаче №2](https://github.com/netology-code/javaqa-homeworks/tree/master/programming#задача-2---precision)
 
В качестве тестовых данных использовался код программы: 
```
 public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```

* Тестирование работы кода программы:

  * Запустить установленную программу IntelliJ IDEA
  * В Project нажать Alt+Insert и выбрать Java Class
  * В поле окна New Java Class ввести Main
  * Скопировать код из тестовых данных
  * Нажать Ctrl+Shift+F10
  * Ожидаемый результат: значение 0,9


Тестирование производилось в следующем окружении:
* Windows 7 SP1 x64
* Java 11
* Git c оболочкой Bash 
* IntelliJ IDEA  2019.3.3