# Lecture 8

## Table of Contents

- 1)MODULES

- 2)EXPORT

- 3)IMPORT

## MODULE


>Сначала программы на JavaScript были небольшими — в прежние времена они использовались для изолированных задач, добавляя при необходимости немного интерактивности веб-страницам, так что большие скрипты в основном не требовались. Прошло несколько лет, и вот мы уже видим полномасштабные приложения, работающие в браузерах и содержащие массу кода на JavaScript; кроме того, язык стал использоваться и в других контекстах (например, Node.js).
>
>Таким образом, в последние годы появились причины на то, чтобы подумать о механизмах деления программ на JavaScript на отдельные модули, которые можно импортировать по мере необходимости. Node.js включал такую возможность уже давно, кроме того, некоторые библиотеки и фреймворки JavaScript разрешали использование модулей (например, CommonJS и основанные на AMD системы модулей типа RequireJS, а позднее также Webpack и Babel)
>
>К счастью, современные браузеры стали сами поддерживать функциональность модулей, о чем и рассказывает эта статья. Этому можно только порадоваться — браузеры могут оптимизировать загрузку модулей, что было бы гораздо эффективнее использования библиотеки, и взять на себя обработку на стороне клиента и прочие накладные расходы.

![](https://hacks.mozilla.org/files/2018/03/10_construction.png)