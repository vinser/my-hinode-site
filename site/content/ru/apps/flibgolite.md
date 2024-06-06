---
author: Serguei Vine
title: FLibGoLite
date: 2024-05-15
description: Just enough for free OPDS server
# tags: ["apps"]
thumbnail:
  url: img/card-flibgolite.png
weight: 10
---
__FLibGoLite__ — это простой в использовании легкий сервер домашней библиотеки с каталогом {{< abbr "OPDS" >}}.

{{< alert type="info" >}}
Формат каталога OPDS — это формат распространения электронных публикаций на основе Atom и HTTP. Каталоги OPDS позволяют агрегировать, распространять, обнаруживать и приобретать электронные публикации. [(Википедия)](https://en.wikipedia.org/wiki/Open_Publication_Distribution_System)
{{< /alert >}}

__FLibGoLite__ является мультиплатформенным и может работать на Windows, MacOs и Linux. Он использует базу данных SQLite для индекса поиска книг.

Текущая версия __FLibGoLite__ поддерживает формат публикаций [EPUB](https://en.wikipedia.org/wiki/EPUB) и [FB2 (отдельные файлы и zip-архивы)](https://github.com/gribuser/fb2).

Каталог __FLibGoLite__ OPDS протестирован и работает с мобильными приложениями для чтения книг __PocketBook Reader__, __FBReader__, __Librera Reader__, __Cool Reader__, а также настольными приложениями __Foliate__ и __Thorium Reader__. Вы можете использовать любые другие приложения или устройства e-ink, которые умеют читать перечисленные форматы книг и работать с каталогами OPDS.

Программа __FLibGoLite__ написана на GO в виде единого исполняемого файла и не требует какого-либо дополнительного программного обеспечения.

__Все, что вам нужно сделать, это скачать, установить и запустить его.__  

Подробные инструкции о том, как это сделать, можно найти на {{< link href=flibgolite_site external=true >}}веб-сайте продукта{{< /link >}}  

Используйте __FLibGoLite__!
