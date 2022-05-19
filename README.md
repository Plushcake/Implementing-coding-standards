# Задание 3*. Внедряем стандарты кодирования (НЕобязательная задача) #
[CheckStyle](https://checkstyle.sourceforge.io/) и [Maven Plugin для него](https://maven.apache.org/plugins/maven-checkstyle-plugin/usage.html) предоставляют возможность производить проверки для выявления соответствия стиля написания кода заданным стандартам\.

Стандарты в организации формируют ведущие программисты и от организации к организации стандарты могут отличаться\.

Мы будем использовать [Google Java Style Guide](https://checkstyle.sourceforge.io/styleguides/google-java-style-20180523/javaguide.html)

Используйте приложенный файл [checkstyle.xml](https://raw.githubusercontent.com/netology-code/javaqa2-homeworks/main/files/checkstyle.xml) в качестве набора правил \(положите его в корень проекта и укажите в качестве настройки `configLocation`\)\.

Ваша задача:

1. Подключить плагин к вашему проекту \(возьмите проект с первой задачи, либо создайте новый на его базе\)

2. Настроить goal `check` в фазу `verify`

3. Удостовериться, что код не проходит проверки CheckStyle \(фиксить не нужно\)

4. Сделать push в GitHub и удостовериться, что сборка не проходит именно по причине наличия ошибок CheckStyle

Итого: отправьте на проверку ссылку гитхаб-репозиторий с вашим проектом\.