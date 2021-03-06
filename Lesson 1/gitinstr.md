# Первый файл по контролю версий

## Заголовки
Заголовки бывают нескольких уровней.
Каждый уровень создается путем добавления дополнительной решетки #
# Заголовок 1
## Заголовок 2
### Заголовок 3

Для создания разрыва строки необходимо нажать проблем несколько раз - текст следующего предложения автоматически перенесется на новую строку

## Цитаты

Для обозначения цитат в языке Markdown используется знак «больше» («>»). Его можно вставлять как перед каждой строкой цитаты, так и только перед первой строкой параграфа. Также синтаксис Markdown позволяет создавать вложенные цитаты (цитаты внутри цитат). Для их разметки используются дополнительные уровни знаков цитирования («>»)

> Объясню полегче по жизни есть две любимые вещи - планчик и рэпчик,и они не разу не давали повода любить себя меньше
## Выделение текста

Чтобы выделить текст курсивом необходимо обраминть его звездачками (*)
*Курсив*
Чтобы выделить текст полужирным необходимо обрамить его двойными звездачками. Например:
**Полужирный**

## Списки
Markdown поддерживает упорядоченные (нумерованные) и неупорядоченные (ненумерованные) списки. Для формирования неупорядоченный списков используются такие маркеры, как звездочки, плюсы и дефисы. Все перечисленные маркеры могут использоваться взаимозаменяемо.
* Элемент 1
* Элемент 2
* Элемент 3

- Элемент 1
- Элемент 2
- Элемент 3

# Ссылки
Markdown поддерживает два стиля оформления ссылок:

Гиперссылка, с немедленным указанием адреса (внутритекстовая);
Гиперссылка, подобная сноске.
[пример](http://example.com/ "Необязательная подсказка")

## Изображения

В Markdown существует 2 способа вставки изображений в документ:

a. С помощью непосредственного указания URL-адреса изображения. Синтаксис данной команды выглядит следующим образом:

![This is Sparta](sparta.jpg)


![Альтернативный текст](/путь/к/изображению.jpg "Подсказка")
Иными словами, он состоит из следующих элементов:

восклицательный знак;
квадратные скобки, в которых указывается альтернативный изображению текст (он станет содержимым атрибута в элементе img);
круглые скобки, содержащие URL-адрес или относительный путь изображения, а также (необязательно) всплывающую подсказку, заключённуе в двойные или одиночные кавычки.
b. С помощью метки-идентификатора. Синтаксис данной команды записывается следующим образом:

![Альтернативный текст][id]
где «id» — имя определённой метки изображения. Метки изображений определяются при помощи синтаксиса, совершенно идентичного меткам гиперссылок:

[id]: путь/к/изображению "Необязательная подсказка"
