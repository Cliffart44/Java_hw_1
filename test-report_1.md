# Отчёт о [тестировании](https://github.com/netology-code/javaqa-homeworks/tree/master/intro#%D0%B4%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D0%B5%D0%B5-%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BA-%D0%B7%D0%B0%D0%BD%D1%8F%D1%82%D0%B8%D1%8E-11-%D0%B2%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B2-java-jdk-jre-jvm-intellij-idea) инструкции по установке `OpenJDK 11`

### Краткое описание

13.8.20 было проведено тестирование документации.

На тестирование затрачено: один час.

В результате тестирования выявлены следующие дефекты:
* [Неактуальная версия ПО в инструкции по установке `OpenJDK11`](https://github.com/Cliffart44/Java_hw_1/issues/1)

### Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Инструкция по установке `OpenJDK 11`](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)

В качестве тестовых данных использовались:
* [Официальный сайт проекта `OpenJDK`](https://adoptopenjdk.net/)

Тестирование производилось в следующем окружении:
* `Windows 10`; `версия 2004`; `тип x64`.
_______________________________________________________________

# Отчёт о [тестировании](https://github.com/netology-code/javaqa-homeworks/tree/master/intro#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-1---keyvalidator) запуска `KeyValidator`

### Краткое описание

13.8.20 было проведено тестирование запуска приложения `KeyValidator`.

На тестирование затрачено: полчаса.

В результате тестирования [не](https://st3.depositphotos.com/3969727/18463/v/450/depositphotos_184636702-stock-illustration-word-woohoo-splash-paint-letters.jpg) выявлено дефектов.

### Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* файл [`KeyValidator.class`](https://github.com/netology-code/javaqa-homeworks/raw/master/intro/artifacts/KeyValidator.class)

В качестве тестовых данных использовались данные:
* [Ключи для проверки](https://raw.githubusercontent.com/Cliffart44/Java_hw_1/master/keys2test.txt) из [руководства использования `KeyValidator`](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md#%D0%BA%D0%BB%D1%8E%D1%87%D0%B8-%D0%B4%D0%BB%D1%8F-%D0%BF%D1%80%D0%BE%D0%B2%D0%B5%D1%80%D0%BA%D0%B8).

Тестирование производилось в следующем окружении:
* `Windows 10`; `версия 2004`; `тип x64`.
* `openjdk version "11.0.8" 2020-07-14`;
`OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)`;
`OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)`.
_______________________________________________________________

# Отчёт о [тестировании](https://github.com/netology-code/javaqa-homeworks/tree/master/intro#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-1---keyvalidator) `KeyValidator`

### Краткое описание

13.8.20 было проведено функциональное тестирование приложения `KeyValidator`.

На тестирование затрачено: один час.

В результате тестирования выявлены следующие дефекты:
* [Отказ верификации валидных ключей](https://github.com/Cliffart44/Java_hw_1/issues/2)
* [Верификация невалидных ключей](https://github.com/Cliffart44/Java_hw_1/issues/3)

### Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* файл [`KeyValidator.class`](https://github.com/netology-code/javaqa-homeworks/raw/master/intro/artifacts/KeyValidator.class)

В качестве тестовых данных использовались данные:
* [Ключи для проверки](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md#%D0%BA%D0%BB%D1%8E%D1%87%D0%B8-%D0%B4%D0%BB%D1%8F-%D0%BF%D1%80%D0%BE%D0%B2%D0%B5%D1%80%D0%BA%D0%B8) из [руководства использования `KeyValidator`](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md#%D1%80%D1%83%D0%BA%D0%BE%D0%B2%D0%BE%D0%B4%D1%81%D1%82%D0%B2%D0%BE-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-keyvalidator).

Тестирование производилось в следующем окружении:
* `Windows 10`; `версия 2004`; `тип x64`.
* `openjdk version "11.0.8" 2020-07-14`;
`OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)`;
`OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)`.
